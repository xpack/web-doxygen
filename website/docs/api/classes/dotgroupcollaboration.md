---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/dotgroupcollaboration
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DotGroupCollaboration` Class Reference

<p>Representation of a group collaboration graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DotGroupCollaboration { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">src/dotgroupcollaboration.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dotgraph">DotGraph</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A dot graph. <a href="/web-doxygen/docs/api/classes/dotgraph/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EdgeType { <a href="#ab83aa11b8617398a50923c04c2541624">...</a> }</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20ec74da8ed6727681b3ba3c61fffb42">DotGroupCollaboration</a> (const GroupDef *gd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8315009d3686b8d8801a31caf475e644">~DotGroupCollaboration</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e26ce5a2563ee5144ef66ff9cf88461">writeGraph</a> (TextStream &amp;t, GraphOutputFormat gf, EmbeddedOutputFormat ef, const QCString &amp;path, const QCString &amp;fileName, const QCString &amp;relPath, bool writeImageMap=TRUE, int graphId=-1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff85d0009e3f7499e83ec7c346025a9e">isTrivial</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1db90341c93fc11a590f5403d2e18e5">isTooBig</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40cf87a24ee828fd3daf22d77bad7f23">numNodes</a> () const</td>
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

## Protected Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcbee4b731f5695ac36a624fe4df0fd6">getBaseName</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247386ccd7fb55bc0c2e9a6f8e9c54f5">getMapLabel</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f8dac0366f837a5880dc420d7c914d">computeTheGraph</a> () override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec9c9ed7417986a64b442811c1fccd9f">buildGraph</a> (const GroupDef *gd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a> (const Definition *def, QCString &amp;url, EdgeType eType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cc4fd1745dd5af379937db46ac15761">addMemberList</a> (class MemberList *ml)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60113bd74bebf89e32507a8e5a303715">writeGraphHeader</a> (TextStream &amp;t, const QCString &amp;title) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/dotgroupcollaboration/edge">Edge</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf63a5af48b746aaa8638bfbb8d787b0">addEdge</a> (DotNode *_pNStart, DotNode *_pNEnd, EdgeType _eType, const QCString &amp;_label, const QCString &amp;_url)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dotnodemap">DotNodeMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb242ac701301dbd4beb2ba011af5e43">m_diskName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/dotgroupcollaboration/edge">Edge</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07de7ef68c8e29450010ffa684609401">m_edges</a></td>
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

<p>Representation of a group collaboration graph.</p>

<p>Definition at line 28 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### EdgeType {#ab83aa11b8617398a50923c04c2541624}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum DotGroupCollaboration::EdgeType </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tmember<a id="ab83aa11b8617398a50923c04c2541624a6a203a336e7cfcbd7aff57f2c73399cd"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tclass<a id="ab83aa11b8617398a50923c04c2541624ae9c350dfd0a91744d191b0c72c4aa90f"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tnamespace<a id="ab83aa11b8617398a50923c04c2541624ae29bf2589c994b4a77c5d8fcb4cc0ea1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tfile<a id="ab83aa11b8617398a50923c04c2541624a7fa22c95ee2968afb94c0a0ea5699509"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tpages<a id="ab83aa11b8617398a50923c04c2541624ad8208b1bd621d3b751e42e015d9ea21c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">tdir<a id="ab83aa11b8617398a50923c04c2541624a2e54350e7f5aadd30f553c402c9c0a82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">thierarchy<a id="ab83aa11b8617398a50923c04c2541624a6e085e15ff653f37b1923a3c3053d11b"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab83aa11b8617398a50923c04c2541624a6a203a336e7cfcbd7aff57f2c73399cd">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab83aa11b8617398a50923c04c2541624a6a203a336e7cfcbd7aff57f2c73399cd">tmember</a> = 0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab83aa11b8617398a50923c04c2541624ae9c350dfd0a91744d191b0c72c4aa90f">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab83aa11b8617398a50923c04c2541624ae9c350dfd0a91744d191b0c72c4aa90f">tclass</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab83aa11b8617398a50923c04c2541624ae29bf2589c994b4a77c5d8fcb4cc0ea1">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab83aa11b8617398a50923c04c2541624ae29bf2589c994b4a77c5d8fcb4cc0ea1">tnamespace</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab83aa11b8617398a50923c04c2541624a7fa22c95ee2968afb94c0a0ea5699509">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab83aa11b8617398a50923c04c2541624a7fa22c95ee2968afb94c0a0ea5699509">tfile</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab83aa11b8617398a50923c04c2541624ad8208b1bd621d3b751e42e015d9ea21c">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab83aa11b8617398a50923c04c2541624ad8208b1bd621d3b751e42e015d9ea21c">tpages</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab83aa11b8617398a50923c04c2541624a2e54350e7f5aadd30f553c402c9c0a82">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab83aa11b8617398a50923c04c2541624a2e54350e7f5aadd30f553c402c9c0a82">tdir</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab83aa11b8617398a50923c04c2541624a6e085e15ff653f37b1923a3c3053d11b">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab83aa11b8617398a50923c04c2541624a6e085e15ff653f37b1923a3c3053d11b">thierarchy</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DotGroupCollaboration() {#a20ec74da8ed6727681b3ba3c61fffb42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotGroupCollaboration::DotGroupCollaboration (const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 25 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a20ec74da8ed6727681b3ba3c61fffb42">25</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a20ec74da8ed6727681b3ba3c61fffb42">DotGroupCollaboration::DotGroupCollaboration</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a>* gd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">26</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">27</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp_url = gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>()+</span><span class="doxyHighlightStringLiteral">"$"</span><span class="doxyHighlight">+gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">28</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip = gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a> = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a2caedefd187d92eb8c4afe01d403456e">groupTitle</a>(), tooltip, tmp_url, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a>-&gt;markAsVisible();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.emplace(gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(), <a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adb242ac701301dbd4beb2ba011af5e43">m_diskName</a> = gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aec9c9ed7417986a64b442811c1fccd9f">buildGraph</a>( gd );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">Definition::briefDescriptionAsTooltip</a>, <a href="#aec9c9ed7417986a64b442811c1fccd9f">buildGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a2caedefd187d92eb8c4afe01d403456e">GroupDef::groupTitle</a>, <a href="#adb242ac701301dbd4beb2ba011af5e43">m_diskName</a>, <a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a>, <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DotGroupCollaboration() {#a8315009d3686b8d8801a31caf475e644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotGroupCollaboration::~DotGroupCollaboration ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8315009d3686b8d8801a31caf475e644">38</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a8315009d3686b8d8801a31caf475e644">DotGroupCollaboration::~DotGroupCollaboration</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// delete all created Nodes saved in m_usedNodes map</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,node] : <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">delete</span><span class="doxyHighlight"> node;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isTooBig() {#ac1db90341c93fc11a590f5403d2e18e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotGroupCollaboration::isTooBig ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 324 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac1db90341c93fc11a590f5403d2e18e5">324</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac1db90341c93fc11a590f5403d2e18e5">DotGroupCollaboration::isTooBig</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a40cf87a24ee828fd3daf22d77bad7f23">numNodes</a>()&gt;=<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(DOT_GRAPH_MAX_NODES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a> and <a href="#a40cf87a24ee828fd3daf22d77bad7f23">numNodes</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ac6dfccae4079d225ca50634529b384">GroupDefImpl::writeGroupGraph</a>.</p>

</div>
</div>

### isTrivial() {#aff85d0009e3f7499e83ec7c346025a9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotGroupCollaboration::isTrivial ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 319 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff85d0009e3f7499e83ec7c346025a9e">319</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aff85d0009e3f7499e83ec7c346025a9e">DotGroupCollaboration::isTrivial</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.size() &lt;= 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ac6dfccae4079d225ca50634529b384">GroupDefImpl::writeGroupGraph</a>.</p>

</div>
</div>

### numNodes() {#a40cf87a24ee828fd3daf22d77bad7f23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotGroupCollaboration::numNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 329 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a40cf87a24ee828fd3daf22d77bad7f23">329</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a40cf87a24ee828fd3daf22d77bad7f23">DotGroupCollaboration::numNodes</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.</p>


<p>Referenced by <a href="#ac1db90341c93fc11a590f5403d2e18e5">isTooBig</a> and <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ac6dfccae4079d225ca50634529b384">GroupDefImpl::writeGroupGraph</a>.</p>

</div>
</div>

### writeGraph() {#a1e26ce5a2563ee5144ef66ff9cf88461}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotGroupCollaboration::writeGraph (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> gf, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcc">EmbeddedOutputFormat</a> ef, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, bool writeImageMap=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, int graphId=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 249 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1e26ce5a2563ee5144ef66ff9cf88461">249</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a1e26ce5a2563ee5144ef66ff9cf88461">DotGroupCollaboration::writeGraph</a>( <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> graphFormat, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcc">EmbeddedOutputFormat</a> textFormat,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateImageMap,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> graphId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#a8e161ad6a2fe2bb4cd58fccb1338f304">m_doNotAddImageToIndex</a> = textFormat!=<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">EmbeddedOutputFormat::Html</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>(t, graphFormat, textFormat, path, fileName, relPath, generateImageMap, graphId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a8e161ad6a2fe2bb4cd58fccb1338f304">DotGraph::m_doNotAddImageToIndex</a> and <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a640f85f2e2b3f829d6561aaed542d20b">DocbookGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aabf59d930dff9f6aa46e3e5674678a35">HtmlGenerator::endGroupCollaboration</a> and <a href="/web-doxygen/docs/api/classes/latexgenerator/#abfd430d5e5caa0536c58bc174a510cf0">LatexGenerator::endGroupCollaboration</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### computeTheGraph() {#a33f8dac0366f837a5880dc420d7c914d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotGroupCollaboration::computeTheGraph ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 45 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 216 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a33f8dac0366f837a5880dc420d7c914d">216</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a33f8dac0366f837a5880dc420d7c914d">DotGroupCollaboration::computeTheGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> md5stream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a60113bd74bebf89e32507a8e5a303715">writeGraphHeader</a>(md5stream,<a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a>-&gt;label());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// clean write flags</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,node] : <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">    node-&gt;clearWriteFlag();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// write other nodes.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,node] : <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    node-&gt;write(md5stream,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72ae40489cd1e7102e35469c937e05c8bba">GraphType::Inheritance</a>,<a href="/web-doxygen/docs/api/classes/dotgraph/#a352bf93d2d15ed13d368233c85892a9f">m_graphFormat</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// write edges</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;edge : <a href="#a07de7ef68c8e29450010ffa684609401">m_edges</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">    edge-&gt;write( md5stream );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#a256ce4336c69cbb9b15e473afc456805">writeGraphFooter</a>(md5stream);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#ab5e616cb48fb662c41e80b713792bc58">m_theGraph</a> = md5stream.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72ae40489cd1e7102e35469c937e05c8bba">Inheritance</a>, <a href="#a07de7ef68c8e29450010ffa684609401">m_edges</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a352bf93d2d15ed13d368233c85892a9f">DotGraph::m_graphFormat</a>, <a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#ab5e616cb48fb662c41e80b713792bc58">DotGraph::m_theGraph</a>, <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>, <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a256ce4336c69cbb9b15e473afc456805">DotGraph::writeGraphFooter</a> and <a href="#a60113bd74bebf89e32507a8e5a303715">writeGraphHeader</a>.</p>

</div>
</div>

### getBaseName() {#adcbee4b731f5695ac36a624fe4df0fd6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotGroupCollaboration::getBaseName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 211 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adcbee4b731f5695ac36a624fe4df0fd6">211</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#adcbee4b731f5695ac36a624fe4df0fd6">DotGroupCollaboration::getBaseName</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#adb242ac701301dbd4beb2ba011af5e43">m_diskName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#adb242ac701301dbd4beb2ba011af5e43">m_diskName</a>.</p>

</div>
</div>

### getMapLabel() {#a247386ccd7fb55bc0c2e9a6f8e9c54f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotGroupCollaboration::getMapLabel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 244 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a247386ccd7fb55bc0c2e9a6f8e9c54f5">244</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a247386ccd7fb55bc0c2e9a6f8e9c54f5">DotGroupCollaboration::getMapLabel</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>(<a href="/web-doxygen/docs/api/classes/dotgraph/#ab85aa68cac9a9551d8076146f358355e">m_baseName</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="/web-doxygen/docs/api/classes/dotgraph/#ab85aa68cac9a9551d8076146f358355e">DotGraph::m_baseName</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addCollaborationMember() {#ab6cc9aafe7eb910bca59ef9cea2dff14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotGroupCollaboration::addCollaborationMember (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; url, <a href="#ab83aa11b8617398a50923c04c2541624">EdgeType</a> eType)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 80 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 186 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">186</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">DotGroupCollaboration::addCollaborationMember</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a>* def, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; url, <a href="#ab83aa11b8617398a50923c04c2541624">EdgeType</a> eType )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Create group nodes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp_str;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;d : def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ab91d34cb9d5a993d3cae3356bc97232e">partOfGroups</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.find(d-&gt;name().str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>* nnode = it!=<a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.end() ? it-&gt;second : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( nnode != <a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( nnode==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">      { </span><span class="doxyHighlightComment">// add node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">        tmp_str = d-&gt;getReference()+</span><span class="doxyHighlightStringLiteral">"$"</span><span class="doxyHighlight">+d-&gt;getOutputFileBase();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip = d-&gt;briefDescriptionAsTooltip();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">        nnode = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, d-&gt;groupTitle(), tooltip, tmp_str );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">        nnode-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a2592b8669b2aba1c2f0476e1011d48cd">markAsVisible</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.emplace(d-&gt;name().str(), nnode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">      tmp_str = def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abf63a5af48b746aaa8638bfbb8d787b0">addEdge</a>( <a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a>, nnode, eType, tmp_str, url );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#abf63a5af48b746aaa8638bfbb8d787b0">addEdge</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a>, <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a2592b8669b2aba1c2f0476e1011d48cd">DotNode::markAsVisible</a>, <a href="/web-doxygen/docs/api/classes/definition/#ab91d34cb9d5a993d3cae3356bc97232e">Definition::partOfGroups</a> and <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>.</p>


<p>Referenced by <a href="#a2cc4fd1745dd5af379937db46ac15761">addMemberList</a> and <a href="#aec9c9ed7417986a64b442811c1fccd9f">buildGraph</a>.</p>

</div>
</div>

### addEdge() {#abf63a5af48b746aaa8638bfbb8d787b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotGroupCollaboration::Edge * DotGroupCollaboration::addEdge (<a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * _pNStart, <a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * _pNEnd, <a href="#ab83aa11b8617398a50923c04c2541624">EdgeType</a> _eType, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; _label, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; _url)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 162 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf63a5af48b746aaa8638bfbb8d787b0">162</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/dotgroupcollaboration/edge">DotGroupCollaboration::Edge</a>* <a href="#abf63a5af48b746aaa8638bfbb8d787b0">DotGroupCollaboration::addEdge</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>* _pNStart, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>* _pNEnd, <a href="#ab83aa11b8617398a50923c04c2541624">EdgeType</a> _eType,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; _label, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; _url )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// search a existing link.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::find_if(<a href="#a07de7ef68c8e29450010ffa684609401">m_edges</a>.begin(),<a href="#a07de7ef68c8e29450010ffa684609401">m_edges</a>.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">      [&amp;_pNStart,&amp;_pNEnd,&amp;_eType](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;edge)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">      { return edge-&gt;pNStart==_pNStart &amp;&amp; edge-&gt;pNEnd==_pNEnd &amp;&amp; edge-&gt;eType==_eType; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#a07de7ef68c8e29450010ffa684609401">m_edges</a>.end()) </span><span class="doxyHighlightComment">// new link</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a07de7ef68c8e29450010ffa684609401">m_edges</a>.emplace_back(std::make_unique&lt;Edge&gt;(_pNStart,_pNEnd,_eType));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">    it = <a href="#a07de7ef68c8e29450010ffa684609401">m_edges</a>.end()-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!_label.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// add label</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    (*it)-&gt;links.emplace_back(_label,_url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// return found or added edge</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (*it).get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#a07de7ef68c8e29450010ffa684609401">m_edges</a>.</p>


<p>Referenced by <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a> and <a href="#aec9c9ed7417986a64b442811c1fccd9f">buildGraph</a>.</p>

</div>
</div>

### addMemberList() {#a2cc4fd1745dd5af379937db46ac15761}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotGroupCollaboration::addMemberList (class <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> * ml)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 81 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2cc4fd1745dd5af379937db46ac15761">151</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2cc4fd1745dd5af379937db46ac15761">DotGroupCollaboration::addMemberList</a>( <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a>* ml )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( ml==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || ml-&gt;<a href="/web-doxygen/docs/api/classes/membervector/#a8211803ee32d3deef9aafca1cc061101">empty</a>() ) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;def : *ml)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp/#aa0dc283b279488f29402e4b9db1d1f30">makeURL</a>(def,url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a>( def, url, <a href="#ab83aa11b8617398a50923c04c2541624a6a203a336e7cfcbd7aff57f2c73399cd">DotGroupCollaboration::tmember</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a>, <a href="/web-doxygen/docs/api/classes/membervector/#a8211803ee32d3deef9aafca1cc061101">MemberVector::empty</a>, <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp/#aa0dc283b279488f29402e4b9db1d1f30">makeURL</a> and <a href="#ab83aa11b8617398a50923c04c2541624a6a203a336e7cfcbd7aff57f2c73399cd">tmember</a>.</p>


<p>Referenced by <a href="#aec9c9ed7417986a64b442811c1fccd9f">buildGraph</a>.</p>

</div>
</div>

### buildGraph() {#aec9c9ed7417986a64b442811c1fccd9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotGroupCollaboration::buildGraph (const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aec9c9ed7417986a64b442811c1fccd9f">58</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aec9c9ed7417986a64b442811c1fccd9f">DotGroupCollaboration::buildGraph</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a>* gd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//===========================</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// hierarchy.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Write parents</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;d : gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ab91d34cb9d5a993d3cae3356bc97232e">partOfGroups</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *nnode = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.find(d-&gt;name().str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( it==<a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// add node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp/#aa0dc283b279488f29402e4b9db1d1f30">makeURL</a>(d,url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip = d-&gt;briefDescriptionAsTooltip();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">      nnode = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, d-&gt;groupTitle(), tooltip, url );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">      nnode-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a2592b8669b2aba1c2f0476e1011d48cd">markAsVisible</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.emplace(d-&gt;name().str(), nnode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">      nnode = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">    url = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#abf63a5af48b746aaa8638bfbb8d787b0">addEdge</a>( nnode, <a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a>, <a href="#ab83aa11b8617398a50923c04c2541624a6e085e15ff653f37b1923a3c3053d11b">DotGroupCollaboration::thierarchy</a>, url, url );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Add subgroups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;def : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a29954976b38072020da6c0c0dbde6520">getSubGroups</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *nnode = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.find(def-&gt;name().str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( it==<a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightComment">// add node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp/#aa0dc283b279488f29402e4b9db1d1f30">makeURL</a>(def,url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip = def-&gt;briefDescriptionAsTooltip();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">      nnode = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, def-&gt;groupTitle(), tooltip, url );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">      nnode-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a2592b8669b2aba1c2f0476e1011d48cd">markAsVisible</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>.emplace(def-&gt;name().str(), nnode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">      nnode = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    url = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#abf63a5af48b746aaa8638bfbb8d787b0">addEdge</a>( <a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a>, nnode, <a href="#ab83aa11b8617398a50923c04c2541624a6e085e15ff653f37b1923a3c3053d11b">DotGroupCollaboration::thierarchy</a>, url, url );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//=======================</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Write collaboration</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Add members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2cc4fd1745dd5af379937db46ac15761">addMemberList</a>( gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#ae1e55ed1172103ac1072cde37b3fd578">getMemberList</a>(MemberListType::AllMembersList()) );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Add classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;def : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#adc93620cc6002b6e7919565cb32b29ed">getClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp/#aa0dc283b279488f29402e4b9db1d1f30">makeURL</a>(def,url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a>( def, url, <a href="#ab83aa11b8617398a50923c04c2541624ae9c350dfd0a91744d191b0c72c4aa90f">DotGroupCollaboration::tclass</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Add namespaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;def : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a9ac892052b696a7c561f7dfa7be68f72">getNamespaces</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp/#aa0dc283b279488f29402e4b9db1d1f30">makeURL</a>(def,url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a>( def, url, <a href="#ab83aa11b8617398a50923c04c2541624ae29bf2589c994b4a77c5d8fcb4cc0ea1">DotGroupCollaboration::tnamespace</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Add files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;def : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a2cb0a3622503ad4232eabc2b7ff86753">getFiles</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp/#aa0dc283b279488f29402e4b9db1d1f30">makeURL</a>(def,url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a>( def, url, <a href="#ab83aa11b8617398a50923c04c2541624a7fa22c95ee2968afb94c0a0ea5699509">DotGroupCollaboration::tfile</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Add pages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;def : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a97d9ddba395f4c011a01966dc7a61568">getPages</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp/#aa0dc283b279488f29402e4b9db1d1f30">makeURL</a>(def,url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a>( def, url, <a href="#ab83aa11b8617398a50923c04c2541624ad8208b1bd621d3b751e42e015d9ea21c">DotGroupCollaboration::tpages</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Add directories</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a25362a91e571718de606e663975c6a1b">getDirs</a>().empty() )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> def : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a25362a91e571718de606e663975c6a1b">getDirs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp/#aa0dc283b279488f29402e4b9db1d1f30">makeURL</a>(def,url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a>( def, url, <a href="#ab83aa11b8617398a50923c04c2541624a2e54350e7f5aadd30f553c402c9c0a82">DotGroupCollaboration::tdir</a> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a>, <a href="#abf63a5af48b746aaa8638bfbb8d787b0">addEdge</a>, <a href="#a2cc4fd1745dd5af379937db46ac15761">addMemberList</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#adc93620cc6002b6e7919565cb32b29ed">GroupDef::getClasses</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a25362a91e571718de606e663975c6a1b">GroupDef::getDirs</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a2cb0a3622503ad4232eabc2b7ff86753">GroupDef::getFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#ae1e55ed1172103ac1072cde37b3fd578">GroupDef::getMemberList</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a9ac892052b696a7c561f7dfa7be68f72">GroupDef::getNamespaces</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a97d9ddba395f4c011a01966dc7a61568">GroupDef::getPages</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a29954976b38072020da6c0c0dbde6520">GroupDef::getSubGroups</a>, <a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a>, <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>, <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp/#aa0dc283b279488f29402e4b9db1d1f30">makeURL</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a2592b8669b2aba1c2f0476e1011d48cd">DotNode::markAsVisible</a>, <a href="/web-doxygen/docs/api/classes/definition/#ab91d34cb9d5a993d3cae3356bc97232e">Definition::partOfGroups</a>, <a href="#ab83aa11b8617398a50923c04c2541624ae9c350dfd0a91744d191b0c72c4aa90f">tclass</a>, <a href="#ab83aa11b8617398a50923c04c2541624a2e54350e7f5aadd30f553c402c9c0a82">tdir</a>, <a href="#ab83aa11b8617398a50923c04c2541624a7fa22c95ee2968afb94c0a0ea5699509">tfile</a>, <a href="#ab83aa11b8617398a50923c04c2541624a6e085e15ff653f37b1923a3c3053d11b">thierarchy</a>, <a href="#ab83aa11b8617398a50923c04c2541624ae29bf2589c994b4a77c5d8fcb4cc0ea1">tnamespace</a> and <a href="#ab83aa11b8617398a50923c04c2541624ad8208b1bd621d3b751e42e015d9ea21c">tpages</a>.</p>


<p>Referenced by <a href="#a20ec74da8ed6727681b3ba3c61fffb42">DotGroupCollaboration</a>.</p>

</div>
</div>

### writeGraphHeader() {#a60113bd74bebf89e32507a8e5a303715}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotGroupCollaboration::writeGraphHeader (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>, definition at line 334 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60113bd74bebf89e32507a8e5a303715">334</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a60113bd74bebf89e32507a8e5a303715">DotGroupCollaboration::writeGraphHeader</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#a4e1ec8b0e7ecc8e0d27c869e43d75640">DotGraph::writeGraphHeader</a>(t, title);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  rankdir=LR;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/dotgraph/#a4e1ec8b0e7ecc8e0d27c869e43d75640">DotGraph::writeGraphHeader</a>.</p>


<p>Referenced by <a href="#a33f8dac0366f837a5880dc420d7c914d">computeTheGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_diskName {#adb242ac701301dbd4beb2ba011af5e43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotGroupCollaboration::m_diskName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adb242ac701301dbd4beb2ba011af5e43">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>        <a href="#adb242ac701301dbd4beb2ba011af5e43">m_diskName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a20ec74da8ed6727681b3ba3c61fffb42">DotGroupCollaboration</a> and <a href="#adcbee4b731f5695ac36a624fe4df0fd6">getBaseName</a>.</p>

</div>
</div>

### m\_edges {#a07de7ef68c8e29450010ffa684609401}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::unique_ptr&lt;Edge&gt; &gt; DotGroupCollaboration::m_edges</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07de7ef68c8e29450010ffa684609401">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt; std::unique_ptr&lt;Edge&gt; &gt;     <a href="#a07de7ef68c8e29450010ffa684609401">m_edges</a>;</span></span></div>

</div>


<p>Referenced by <a href="#abf63a5af48b746aaa8638bfbb8d787b0">addEdge</a> and <a href="#a33f8dac0366f837a5880dc420d7c914d">computeTheGraph</a>.</p>

</div>
</div>

### m\_rootNode {#a082a33c662fd404a5fb5073c34863af7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNode* DotGroupCollaboration::m_rootNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a082a33c662fd404a5fb5073c34863af7">86</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>        *<a href="#a082a33c662fd404a5fb5073c34863af7">m_rootNode</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a>, <a href="#aec9c9ed7417986a64b442811c1fccd9f">buildGraph</a>, <a href="#a33f8dac0366f837a5880dc420d7c914d">computeTheGraph</a> and <a href="#a20ec74da8ed6727681b3ba3c61fffb42">DotGroupCollaboration</a>.</p>

</div>
</div>

### m\_usedNodes {#a56c5879b481a9e2df4bce580767176ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNodeMap DotGroupCollaboration::m_usedNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a56c5879b481a9e2df4bce580767176ee">87</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotnodemap">DotNodeMap</a>      <a href="#a56c5879b481a9e2df4bce580767176ee">m_usedNodes</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ab6cc9aafe7eb910bca59ef9cea2dff14">addCollaborationMember</a>, <a href="#aec9c9ed7417986a64b442811c1fccd9f">buildGraph</a>, <a href="#a33f8dac0366f837a5880dc420d7c914d">computeTheGraph</a>, <a href="#a20ec74da8ed6727681b3ba3c61fffb42">DotGroupCollaboration</a>, <a href="#aff85d0009e3f7499e83ec7c346025a9e">isTrivial</a>, <a href="#a40cf87a24ee828fd3daf22d77bad7f23">numNodes</a> and <a href="#a8315009d3686b8d8801a31caf475e644">~DotGroupCollaboration</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-cpp">dotgroupcollaboration.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
