---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/dotcallgraph
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DotCallGraph` Class Reference

Representation of an call graph. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class DotCallGraph { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">src/dotcallgraph.h</a>&gt;
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
A dot graph. <a href="/web-doxygen/docs/api/classes/dotgraph/#details">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a027224fbb504c5436845bb85a7c511a0">DotCallGraph</a> (const MemberDef *md, bool inverse)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a3d80fa9ab081c5458268636796bfbc">~DotCallGraph</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7f297903a3fe6ea2ac638f381125767">isTrivial</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f0c9cfab017f669e5c83e4ecd9ef760">isTooBig</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a114c8bc9e302f996906978fc86eab28c">numNodes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad59c94658b83032817c03c0d59c7e5da">writeGraph</a> (TextStream &amp;t, GraphOutputFormat gf, EmbeddedOutputFormat ef, const QCString &amp;path, const QCString &amp;fileName, const QCString &amp;relPath, bool writeImageMap=TRUE, int graphId=-1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a155835e7c8db6c6d61e2b22961e04c6f">getBaseName</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad0e2a7afbc4b291102374da44368347a">getMapLabel</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c6b9b0bc77f8dd62648d9a7b47aeb9f">computeTheGraph</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fe67fd46cab2683e2d10271f90bfb2a">buildGraph</a> (DotNode *n, const MemberDef *md, int distance)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3afda59cf627bb7ebb4771ad47fcfbc">determineVisibleNodes</a> (DotNodeDeque &amp;queue, int &amp;maxNodes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebbdfe5eff5c5f7d8ed348daed0e44dc">determineTruncatedNodes</a> (DotNodeDeque &amp;queue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ffff1435fecbdd5b6c730dbfcbbf18">m_usedNodes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65f12160a5000391308b49812f6fb719">m_inverse</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2c67f86e5fec126e82b294c2e0dea3a">m_diskName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a287c3883ae4ff612ee9a2ab729ebbe93">m_scope</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f66d82e77635c3fdd4ccd92effea216">isTrivial</a> (const MemberDef *md, bool inverse)</td>
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

Representation of an call graph.

Definition at line 26 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>.

<div class="doxySectionDef">

## Public Constructors

### DotCallGraph() {#a027224fbb504c5436845bb85a7c511a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotCallGraph::DotCallGraph (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, bool inverse)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 29 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a027224fbb504c5436845bb85a7c511a0">120</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a027224fbb504c5436845bb85a7c511a0">DotCallGraph::DotCallGraph</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inverse)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a65f12160a5000391308b49812f6fb719">m_inverse</a> = inverse;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad2c67f86e5fec126e82b294c2e0dea3a">m_diskName</a> = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>()+</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">+md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a287c3883ae4ff612ee9a2ab729ebbe93">m_scope</a>    = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> uniqueId = <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp/#a8162981adf82bd139a6f62da022783bf">getUniqueId</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HIDE_SCOPE_NAMES))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">    name = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">    name = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a> = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>(),name,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">    tooltip,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    uniqueId,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>     </span><span class="doxyHighlightComment">// root node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a>-&gt;setDistance(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa0ffff1435fecbdd5b6c730dbfcbbf18">m_usedNodes</a>.emplace(uniqueId.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0fe67fd46cab2683e2d10271f90bfb2a">buildGraph</a>(<a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a>,md,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> maxNodes = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(DOT_GRAPH_MAX_NODES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotnodedeque">DotNodeDeque</a> openNodeQueue;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  openNodeQueue.push_back(<a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af3afda59cf627bb7ebb4771ad47fcfbc">determineVisibleNodes</a>(openNodeQueue,maxNodes);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">  openNodeQueue.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  openNodeQueue.push_back(<a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aebbdfe5eff5c5f7d8ed348daed0e44dc">determineTruncatedNodes</a>(openNodeQueue);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">Definition::briefDescriptionAsTooltip</a>, <a href="#a0fe67fd46cab2683e2d10271f90bfb2a">buildGraph</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config\_getInt</a>, <a href="#aebbdfe5eff5c5f7d8ed348daed0e44dc">determineTruncatedNodes</a>, <a href="#af3afda59cf627bb7ebb4771ad47fcfbc">determineVisibleNodes</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp/#a8162981adf82bd139a6f62da022783bf">getUniqueId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>, <a href="#ad2c67f86e5fec126e82b294c2e0dea3a">m\_diskName</a>, <a href="#a65f12160a5000391308b49812f6fb719">m\_inverse</a>, <a href="#a287c3883ae4ff612ee9a2ab729ebbe93">m\_scope</a>, <a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m\_startNode</a>, <a href="#aa0ffff1435fecbdd5b6c730dbfcbbf18">m\_usedNodes</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DotCallGraph() {#a3a3d80fa9ab081c5458268636796bfbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotCallGraph::~DotCallGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 30 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 155 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a3d80fa9ab081c5458268636796bfbc">155</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a3a3d80fa9ab081c5458268636796bfbc">DotCallGraph::~DotCallGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotnode/#a748649462fd72baa804eccd77fcfa612">DotNode::deleteNodes</a>(<a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dotnode/#a748649462fd72baa804eccd77fcfa612">DotNode::deleteNodes</a> and <a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m\_startNode</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isTooBig() {#a1f0c9cfab017f669e5c83e4ecd9ef760}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotCallGraph::isTooBig ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 34 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 202 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f0c9cfab017f669e5c83e4ecd9ef760">202</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1f0c9cfab017f669e5c83e4ecd9ef760">DotCallGraph::isTooBig</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a114c8bc9e302f996906978fc86eab28c">numNodes</a>()&gt;=<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(DOT_GRAPH_MAX_NODES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config\_getInt</a> and <a href="#a114c8bc9e302f996906978fc86eab28c">numNodes</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a0410c3e0f3f2fd5fdb341546e40d4a7d">MemberDefImpl::\_writeCallerGraph</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af8b226a288cd0a1825db1a191d10a760">MemberDefImpl::\_writeCallGraph</a>.
</div>
</div>

### isTrivial() {#ae7f297903a3fe6ea2ac638f381125767}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotCallGraph::isTrivial ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 197 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae7f297903a3fe6ea2ac638f381125767">197</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae7f297903a3fe6ea2ac638f381125767">DotCallGraph::isTrivial</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a>-&gt;children().empty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m\_startNode</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a00514e707a17d68b52b60218ae7c1dfd">MemberDefImpl::\_hasVisibleCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a32cd3e688d0489c3b35a362162fe7acf">MemberDefImpl::\_hasVisibleCallGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a0410c3e0f3f2fd5fdb341546e40d4a7d">MemberDefImpl::\_writeCallerGraph</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af8b226a288cd0a1825db1a191d10a760">MemberDefImpl::\_writeCallGraph</a>.
</div>
</div>

### numNodes() {#a114c8bc9e302f996906978fc86eab28c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotCallGraph::numNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 35 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 207 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a114c8bc9e302f996906978fc86eab28c">207</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a114c8bc9e302f996906978fc86eab28c">DotCallGraph::numNodes</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a>-&gt;children().size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m\_startNode</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a0410c3e0f3f2fd5fdb341546e40d4a7d">MemberDefImpl::\_writeCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af8b226a288cd0a1825db1a191d10a760">MemberDefImpl::\_writeCallGraph</a> and <a href="#a1f0c9cfab017f669e5c83e4ecd9ef760">isTooBig</a>.
</div>
</div>

### writeGraph() {#ad59c94658b83032817c03c0d59c7e5da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotCallGraph::writeGraph (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> gf, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcc">EmbeddedOutputFormat</a> ef, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, bool writeImageMap=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, int graphId=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 36 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 183 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad59c94658b83032817c03c0d59c7e5da">183</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad59c94658b83032817c03c0d59c7e5da">DotCallGraph::writeGraph</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;out,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> graphFormat,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcc">EmbeddedOutputFormat</a> textFormat,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateImageMap,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> graphId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#a8e161ad6a2fe2bb4cd58fccb1338f304">m_doNotAddImageToIndex</a> = textFormat!=<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">EmbeddedOutputFormat::Html</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>(out, graphFormat, textFormat, path, fileName, relPath, generateImageMap, graphId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a8e161ad6a2fe2bb4cd58fccb1338f304">DotGraph::m\_doNotAddImageToIndex</a> and <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aab1ce69f9718b3c1e05f6c1b697664e4">DocbookGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#add957a1f68cc9b99a4c57caa58b33a9b">HtmlGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#abf21f797d89eb90ceb085c27649df03c">LatexGenerator::endCallGraph</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adeb275db39d63df2f74c728adaa70849">RTFGenerator::endCallGraph</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### computeTheGraph() {#a0c6b9b0bc77f8dd62648d9a7b47aeb9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotCallGraph::computeTheGraph ()</td>
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



Declaration at line 45 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c6b9b0bc77f8dd62648d9a7b47aeb9f">165</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0c6b9b0bc77f8dd62648d9a7b47aeb9f">DotCallGraph::computeTheGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">computeGraph</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a9d0f6d0fe9c95c9cb09769b9879db1ff">GraphType::CallGraph</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#a352bf93d2d15ed13d368233c85892a9f">m_graphFormat</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a65f12160a5000391308b49812f6fb719">m_inverse</a> ? </span><span class="doxyHighlightStringLiteral">"RL"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"LR"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a65f12160a5000391308b49812f6fb719">m_inverse</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a>-&gt;label(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#ab5e616cb48fb662c41e80b713792bc58">m_theGraph</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a9d0f6d0fe9c95c9cb09769b9879db1ff">CallGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">DotGraph::computeGraph</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a352bf93d2d15ed13d368233c85892a9f">DotGraph::m\_graphFormat</a>, <a href="#a65f12160a5000391308b49812f6fb719">m\_inverse</a>, <a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m\_startNode</a> and <a href="/web-doxygen/docs/api/classes/dotgraph/#ab5e616cb48fb662c41e80b713792bc58">DotGraph::m\_theGraph</a>.
</div>
</div>

### getBaseName() {#a155835e7c8db6c6d61e2b22961e04c6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotCallGraph::getBaseName ()</td>
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



Declaration at line 43 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 160 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a155835e7c8db6c6d61e2b22961e04c6f">160</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a155835e7c8db6c6d61e2b22961e04c6f">DotCallGraph::getBaseName</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad2c67f86e5fec126e82b294c2e0dea3a">m_diskName</a> + (<a href="#a65f12160a5000391308b49812f6fb719">m_inverse</a> ? </span><span class="doxyHighlightStringLiteral">"_icgraph"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"_cgraph"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ad2c67f86e5fec126e82b294c2e0dea3a">m\_diskName</a> and <a href="#a65f12160a5000391308b49812f6fb719">m\_inverse</a>.
</div>
</div>

### getMapLabel() {#ad0e2a7afbc4b291102374da44368347a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotCallGraph::getMapLabel ()</td>
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



Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 178 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad0e2a7afbc4b291102374da44368347a">178</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad0e2a7afbc4b291102374da44368347a">DotCallGraph::getMapLabel</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#ab85aa68cac9a9551d8076146f358355e">m_baseName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/dotgraph/#ab85aa68cac9a9551d8076146f358355e">DotGraph::m\_baseName</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildGraph() {#a0fe67fd46cab2683e2d10271f90bfb2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotCallGraph::buildGraph (<a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * n, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, int distance)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 48 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 33 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0fe67fd46cab2683e2d10271f90bfb2a">33</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0fe67fd46cab2683e2d10271f90bfb2a">DotCallGraph::buildGraph</a>(<a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *n,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> distance)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> refs = <a href="#a65f12160a5000391308b49812f6fb719">m_inverse</a> ? md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad3359130ee4ef83bdf7ce453fb3d1525">getReferencedByMembers</a>() : md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af21ed7be937dbdb153d5ccab3d9abf12">getReferencesMembers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;rmd : refs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rmd-&gt;isCallable())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> uniqueId = <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp/#a8162981adf82bd139a6f62da022783bf">getUniqueId</a>(rmd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#aa0ffff1435fecbdd5b6c730dbfcbbf18">m_usedNodes</a>.find(uniqueId.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#aa0ffff1435fecbdd5b6c730dbfcbbf18">m_usedNodes</a>.end()) </span><span class="doxyHighlightComment">// file is already a node in the graph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *bn = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">        n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#ac54555a412724c31181a40a50213e38e">addChild</a>(bn,<a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>,<a href="/web-doxygen/docs/api/classes/edgeinfo/#a4fe2d2921d0f51d84da1bf48b3b4f2c5a26f6a09cd44415e9be80ccabf5195989">EdgeInfo::Solid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">        bn-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a98f7fc0d1caa3e53622039e86903b04e">addParent</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">        bn-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a21956cf8ee9e3f8b750c221f6d00ee84">setDistance</a>(distance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HIDE_SCOPE_NAMES))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">          name  = rmd-&gt;getOuterScope()==<a href="#a287c3883ae4ff612ee9a2ab729ebbe93">m_scope</a> ?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">            rmd-&gt;name() : rmd-&gt;qualifiedName();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">          name = rmd-&gt;qualifiedName();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip = rmd-&gt;briefDescriptionAsTooltip();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *bn = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>(rmd-&gt;getLanguage(),name,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">            tooltip,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">            uniqueId,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">            0 </span><span class="doxyHighlightComment">//distance</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">            );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">        n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#ac54555a412724c31181a40a50213e38e">addChild</a>(bn,<a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>,<a href="/web-doxygen/docs/api/classes/edgeinfo/#a4fe2d2921d0f51d84da1bf48b3b4f2c5a26f6a09cd44415e9be80ccabf5195989">EdgeInfo::Solid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">        bn-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a98f7fc0d1caa3e53622039e86903b04e">addParent</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">        bn-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a21956cf8ee9e3f8b750c221f6d00ee84">setDistance</a>(distance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa0ffff1435fecbdd5b6c730dbfcbbf18">m_usedNodes</a>.emplace(uniqueId.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),bn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a0fe67fd46cab2683e2d10271f90bfb2a">buildGraph</a>(bn,rmd,distance+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dotnode/#ac54555a412724c31181a40a50213e38e">DotNode::addChild</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a98f7fc0d1caa3e53622039e86903b04e">DotNode::addParent</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>, <a href="#a0fe67fd46cab2683e2d10271f90bfb2a">buildGraph</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/definition/#ad3359130ee4ef83bdf7ce453fb3d1525">Definition::getReferencedByMembers</a>, <a href="/web-doxygen/docs/api/classes/definition/#af21ed7be937dbdb153d5ccab3d9abf12">Definition::getReferencesMembers</a>, <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp/#a8162981adf82bd139a6f62da022783bf">getUniqueId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>, <a href="#a65f12160a5000391308b49812f6fb719">m\_inverse</a>, <a href="#a287c3883ae4ff612ee9a2ab729ebbe93">m\_scope</a>, <a href="#aa0ffff1435fecbdd5b6c730dbfcbbf18">m\_usedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a21956cf8ee9e3f8b750c221f6d00ee84">DotNode::setDistance</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#a4fe2d2921d0f51d84da1bf48b3b4f2c5a26f6a09cd44415e9be80ccabf5195989">EdgeInfo::Solid</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="#a0fe67fd46cab2683e2d10271f90bfb2a">buildGraph</a> and <a href="#a027224fbb504c5436845bb85a7c511a0">DotCallGraph</a>.
</div>
</div>

### determineTruncatedNodes() {#aebbdfe5eff5c5f7d8ed348daed0e44dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotCallGraph::determineTruncatedNodes (<a href="/web-doxygen/docs/api/classes/dotnodedeque">DotNodeDeque</a> &amp; queue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 99 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebbdfe5eff5c5f7d8ed348daed0e44dc">99</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aebbdfe5eff5c5f7d8ed348daed0e44dc">DotCallGraph::determineTruncatedNodes</a>(<a href="/web-doxygen/docs/api/classes/dotnodedeque">DotNodeDeque</a> &amp;queue)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!queue.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *n = queue.front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">    queue.pop_front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a9e97a698e9e6460cd7fac782e38f0ce7">isVisible</a>() &amp;&amp; n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#adcfb83215c88dcdd5c39391547e3882b">isTruncated</a>()==<a href="/web-doxygen/docs/api/classes/dotnode/#ac40de94762a7659599b2056942373102adba69679a9bcc9333c7165d4e7bdade0">DotNode::Unknown</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> truncated = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dn : n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!dn-&gt;isVisible())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">          truncated = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">          queue.push_back(dn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">      n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a543c8aa7d944877ff050dbdb9bbfd7db">markAsTruncated</a>(truncated);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dotnode/#ad8b1f38e1403f73fc4f8745b5fbe00c9">DotNode::children</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#adcfb83215c88dcdd5c39391547e3882b">DotNode::isTruncated</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a9e97a698e9e6460cd7fac782e38f0ce7">DotNode::isVisible</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a543c8aa7d944877ff050dbdb9bbfd7db">DotNode::markAsTruncated</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/dotnode/#ac40de94762a7659599b2056942373102adba69679a9bcc9333c7165d4e7bdade0">DotNode::Unknown</a>.

Referenced by <a href="#a027224fbb504c5436845bb85a7c511a0">DotCallGraph</a>.
</div>
</div>

### determineVisibleNodes() {#af3afda59cf627bb7ebb4771ad47fcfbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotCallGraph::determineVisibleNodes (<a href="/web-doxygen/docs/api/classes/dotnodedeque">DotNodeDeque</a> &amp; queue, int &amp; maxNodes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3afda59cf627bb7ebb4771ad47fcfbc">80</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af3afda59cf627bb7ebb4771ad47fcfbc">DotCallGraph::determineVisibleNodes</a>(<a href="/web-doxygen/docs/api/classes/dotnodedeque">DotNodeDeque</a> &amp;queue, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;maxNodes)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!queue.empty() &amp;&amp; maxNodes&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *n = queue.front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    queue.pop_front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a9e97a698e9e6460cd7fac782e38f0ce7">isVisible</a>() &amp;&amp; n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a196e6efc147272506e3e0564dfe47bfe">distance</a>()&lt;=<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(MAX_DOT_GRAPH_DEPTH)) </span><span class="doxyHighlightComment">// not yet processed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">      n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a2592b8669b2aba1c2f0476e1011d48cd">markAsVisible</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      maxNodes--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// add direct children</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dn : n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">        queue.push_back(dn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dotnode/#ad8b1f38e1403f73fc4f8745b5fbe00c9">DotNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config\_getInt</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a196e6efc147272506e3e0564dfe47bfe">DotNode::distance</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a9e97a698e9e6460cd7fac782e38f0ce7">DotNode::isVisible</a> and <a href="/web-doxygen/docs/api/classes/dotnode/#a2592b8669b2aba1c2f0476e1011d48cd">DotNode::markAsVisible</a>.

Referenced by <a href="#a027224fbb504c5436845bb85a7c511a0">DotCallGraph</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_diskName {#ad2c67f86e5fec126e82b294c2e0dea3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotCallGraph::m_diskName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad2c67f86e5fec126e82b294c2e0dea3a">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>        <a href="#ad2c67f86e5fec126e82b294c2e0dea3a">m_diskName</a>;</span></span></div>

</div>


Referenced by <a href="#a027224fbb504c5436845bb85a7c511a0">DotCallGraph</a> and <a href="#a155835e7c8db6c6d61e2b22961e04c6f">getBaseName</a>.
</div>
</div>

### m\_inverse {#a65f12160a5000391308b49812f6fb719}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotCallGraph::m_inverse</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 53 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a65f12160a5000391308b49812f6fb719">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">            <a href="#a65f12160a5000391308b49812f6fb719">m_inverse</a>;</span></span></div>

</div>


Referenced by <a href="#a0fe67fd46cab2683e2d10271f90bfb2a">buildGraph</a>, <a href="#a0c6b9b0bc77f8dd62648d9a7b47aeb9f">computeTheGraph</a>, <a href="#a027224fbb504c5436845bb85a7c511a0">DotCallGraph</a> and <a href="#a155835e7c8db6c6d61e2b22961e04c6f">getBaseName</a>.
</div>
</div>

### m\_scope {#a287c3883ae4ff612ee9a2ab729ebbe93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Definition* DotCallGraph::m_scope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a287c3883ae4ff612ee9a2ab729ebbe93">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * <a href="#a287c3883ae4ff612ee9a2ab729ebbe93">m_scope</a>;</span></span></div>

</div>


Referenced by <a href="#a0fe67fd46cab2683e2d10271f90bfb2a">buildGraph</a> and <a href="#a027224fbb504c5436845bb85a7c511a0">DotCallGraph</a>.
</div>
</div>

### m\_startNode {#a1f88faa3e2d93cfe34001d759f45cbc1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNode* DotCallGraph::m_startNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f88faa3e2d93cfe34001d759f45cbc1">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>        *<a href="#a1f88faa3e2d93cfe34001d759f45cbc1">m_startNode</a>;</span></span></div>

</div>


Referenced by <a href="#a0c6b9b0bc77f8dd62648d9a7b47aeb9f">computeTheGraph</a>, <a href="#a027224fbb504c5436845bb85a7c511a0">DotCallGraph</a>, <a href="#ae7f297903a3fe6ea2ac638f381125767">isTrivial</a>, <a href="#a114c8bc9e302f996906978fc86eab28c">numNodes</a> and <a href="#a3a3d80fa9ab081c5458268636796bfbc">\~DotCallGraph</a>.
</div>
</div>

### m\_usedNodes {#aa0ffff1435fecbdd5b6c730dbfcbbf18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNodeMap DotCallGraph::m_usedNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 52 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0ffff1435fecbdd5b6c730dbfcbbf18">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotnodemap">DotNodeMap</a>      <a href="#aa0ffff1435fecbdd5b6c730dbfcbbf18">m_usedNodes</a>;</span></span></div>

</div>


Referenced by <a href="#a0fe67fd46cab2683e2d10271f90bfb2a">buildGraph</a> and <a href="#a027224fbb504c5436845bb85a7c511a0">DotCallGraph</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### isTrivial() {#a4f66d82e77635c3fdd4ccd92effea216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotCallGraph::isTrivial (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, bool inverse)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 40 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>, definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f66d82e77635c3fdd4ccd92effea216">212</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae7f297903a3fe6ea2ac638f381125767">DotCallGraph::isTrivial</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inverse)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> refs = inverse ? md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad3359130ee4ef83bdf7ce453fb3d1525">getReferencedByMembers</a>() : md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#af21ed7be937dbdb153d5ccab3d9abf12">getReferencesMembers</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;rmd : refs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rmd-&gt;isCallable())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/definition/#ad3359130ee4ef83bdf7ce453fb3d1525">Definition::getReferencedByMembers</a>, <a href="/web-doxygen/docs/api/classes/definition/#af21ed7be937dbdb153d5ccab3d9abf12">Definition::getReferencesMembers</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dotcallgraph-cpp">dotcallgraph.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
