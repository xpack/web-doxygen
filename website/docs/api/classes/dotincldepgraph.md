---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/dotincldepgraph
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DotInclDepGraph` Class Reference

<p>Representation of an include dependency graph. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DotInclDepGraph { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">src/dotincldepgraph.h</a>&gt;
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph</a> (const FileDef *fd, bool inverse)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af16036a50c08251c90de8841af69858a">~DotInclDepGraph</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a197a7b8e9b068d122b062c80b21784e4">writeGraph</a> (TextStream &amp;t, GraphOutputFormat gf, EmbeddedOutputFormat ef, const QCString &amp;path, const QCString &amp;fileName, const QCString &amp;relPath, bool writeImageMap=TRUE, int graphId=-1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe9784772becb74106aa3978a52105eb">isTrivial</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab00dfe31a3deec8e36ed043b0cd3be6f">isTooBig</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd9c22a1f88a178e369914f0c8fb55b0">numNodes</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28fef240bd687173e6e9184e82bcf391">writeXML</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c2162d40ea8f7ab188a37247b5b2bb5">writeDocbook</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac80224cf47d91c0235efbe9a2b9fef08">getBaseName</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae40c9c4198c440c72aaa52f8f1ada8eb">getMapLabel</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0eb34c13a6a603939648310908c1b6b2">computeTheGraph</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00b3a6cdc1fbbc725b862fd6f474eefc">diskName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88aa8095a13ae269eb1a17631909f06">buildGraph</a> (DotNode *n, const FileDef *fd, int distance)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a4d42a2191cbdac155f1f9b67c4bfb5">determineVisibleNodes</a> (DotNodeDeque &amp;queue, int &amp;maxNodes)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aa3c90f1ef0858e708cb5636e9ed73b">determineTruncatedNodes</a> (DotNodeDeque &amp;queue)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3bf314d8bc14e0501b11d9633ea040fb">m_usedNodes</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b1ac9f793179e523b7c91fbf6ec7610">m_inclDepFileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2e50c911e5a8a9522b91e6ffcc7bd58">m_inclByDepFileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a441c062f595f392e77c874d57faafa73">m_inverse</a></td>
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

<p>Representation of an include dependency graph.</p>

<p>Definition at line 30 of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### DotInclDepGraph() {#aa6f427f748bd461630a7656583fc729e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotInclDepGraph::DotInclDepGraph (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, bool inverse)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00033">33</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00123">123</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa6f427f748bd461630a7656583fc729e">123</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph::DotInclDepGraph</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inverse)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a441c062f595f392e77c874d57faafa73">m_inverse</a> = inverse;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(fd!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5b1ac9f793179e523b7c91fbf6ec7610">m_inclDepFileName</a>   = fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#ae0cf64cd4de49e26166e60dffa2c2136">includeDependencyGraphFileName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af2e50c911e5a8a9522b91e6ffcc7bd58">m_inclByDepFileName</a> = fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a839282776181f9ae9798a4f7e04e2a42">includedByDependencyGraphFileName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp_url=fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>()+</span><span class="doxyHighlightStringLiteral">"$"</span><span class="doxyHighlight">+fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip = fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a> = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">                            fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#ad7d5e7ac753d7247cfaad5be9ea3eaec">docName</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">                            tooltip,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">                            tmp_url,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">                            <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);    </span><span class="doxyHighlightComment">// root node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>-&gt;setDistance(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3bf314d8bc14e0501b11d9633ea040fb">m_usedNodes</a>.emplace(fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad88aa8095a13ae269eb1a17631909f06">buildGraph</a>(<a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>,fd,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> maxNodes = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(DOT_GRAPH_MAX_NODES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotnodedeque">DotNodeDeque</a> openNodeQueue;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  openNodeQueue.push_back(<a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1a4d42a2191cbdac155f1f9b67c4bfb5">determineVisibleNodes</a>(openNodeQueue,maxNodes);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  openNodeQueue.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  openNodeQueue.push_back(<a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8aa3c90f1ef0858e708cb5636e9ed73b">determineTruncatedNodes</a>(openNodeQueue);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>, <a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">Definition::briefDescriptionAsTooltip</a>, <a href="#ad88aa8095a13ae269eb1a17631909f06">buildGraph</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config&#95;getInt</a>, <a href="#a8aa3c90f1ef0858e708cb5636e9ed73b">determineTruncatedNodes</a>, <a href="#a1a4d42a2191cbdac155f1f9b67c4bfb5">determineVisibleNodes</a>, <a href="/web-doxygen/docs/api/classes/filedef/#ad7d5e7ac753d7247cfaad5be9ea3eaec">FileDef::docName</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a839282776181f9ae9798a4f7e04e2a42">FileDef::includedByDependencyGraphFileName</a>, <a href="/web-doxygen/docs/api/classes/filedef/#ae0cf64cd4de49e26166e60dffa2c2136">FileDef::includeDependencyGraphFileName</a>, <a href="#af2e50c911e5a8a9522b91e6ffcc7bd58">m&#95;inclByDepFileName</a>, <a href="#a5b1ac9f793179e523b7c91fbf6ec7610">m&#95;inclDepFileName</a>, <a href="#a441c062f595f392e77c874d57faafa73">m&#95;inverse</a>, <a href="#ab7e7a007c38e953df49b925d902e634e">m&#95;startNode</a>, <a href="#a3bf314d8bc14e0501b11d9633ea040fb">m&#95;usedNodes</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### ~DotInclDepGraph() {#af16036a50c08251c90de8841af69858a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotInclDepGraph::~DotInclDepGraph ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00034">34</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00149">149</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af16036a50c08251c90de8841af69858a">149</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#af16036a50c08251c90de8841af69858a">DotInclDepGraph::~DotInclDepGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotnode/#a748649462fd72baa804eccd77fcfa612">DotNode::deleteNodes</a>(<a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dotnode/#a748649462fd72baa804eccd77fcfa612">DotNode::deleteNodes</a> and <a href="#ab7e7a007c38e953df49b925d902e634e">m&#95;startNode</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isTooBig() {#ab00dfe31a3deec8e36ed043b0cd3be6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotInclDepGraph::isTooBig ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00041">41</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00201">201</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab00dfe31a3deec8e36ed043b0cd3be6f">201</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab00dfe31a3deec8e36ed043b0cd3be6f">DotInclDepGraph::isTooBig</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9c22a1f88a178e369914f0c8fb55b0">numNodes</a>()&gt;=<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(DOT_GRAPH_MAX_NODES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config&#95;getInt</a> and <a href="#acd9c22a1f88a178e369914f0c8fb55b0">numNodes</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>.
</div>
</div>

### isTrivial() {#afe9784772becb74106aa3978a52105eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotInclDepGraph::isTrivial ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00040">40</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00196">196</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afe9784772becb74106aa3978a52105eb">196</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#afe9784772becb74106aa3978a52105eb">DotInclDepGraph::isTrivial</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>-&gt;children().empty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ab7e7a007c38e953df49b925d902e634e">m&#95;startNode</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a541a7f1681d4e6c18ba0fb4902f2b9d3">generateXMLForFile</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>.
</div>
</div>

### numNodes() {#acd9c22a1f88a178e369914f0c8fb55b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotInclDepGraph::numNodes ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00042">42</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00206">206</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd9c22a1f88a178e369914f0c8fb55b0">206</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#acd9c22a1f88a178e369914f0c8fb55b0">DotInclDepGraph::numNodes</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>-&gt;children().size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ab7e7a007c38e953df49b925d902e634e">m&#95;startNode</a>.

Referenced by <a href="#ab00dfe31a3deec8e36ed043b0cd3be6f">isTooBig</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>.
</div>
</div>

### writeDocbook() {#a8c2162d40ea8f7ab188a37247b5b2bb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotInclDepGraph::writeDocbook (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00044">44</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00219">219</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c2162d40ea8f7ab188a37247b5b2bb5">219</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8c2162d40ea8f7ab188a37247b5b2bb5">DotInclDepGraph::writeDocbook</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,node] : <a href="#a3bf314d8bc14e0501b11d9633ea040fb">m_usedNodes</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">    node-&gt;writeDocbook(t,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#a3bf314d8bc14e0501b11d9633ea040fb">m&#95;usedNodes</a>.
</div>
</div>

### writeGraph() {#a197a7b8e9b068d122b062c80b21784e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotInclDepGraph::writeGraph (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> gf, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcc">EmbeddedOutputFormat</a> ef, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, bool writeImageMap=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, int graphId=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00037">37</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00184">184</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a197a7b8e9b068d122b062c80b21784e4">184</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a197a7b8e9b068d122b062c80b21784e4">DotInclDepGraph::writeGraph</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;out,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> graphFormat,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcc">EmbeddedOutputFormat</a> textFormat,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateImageMap,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> graphId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>(out, graphFormat, textFormat, path, fileName, relPath, generateImageMap, graphId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afa0db463a17513f4e3ae08e03d6e2615">DocbookGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac78029628ccb4f7aef7ca0c4cbce0ae3">HtmlGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3fd1e2fb8150b2b29985a8031854d4b9">LatexGenerator::endInclDepGraph</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa1a701e0ab2c31d782a7faae9e0135e1">RTFGenerator::endInclDepGraph</a>.
</div>
</div>

### writeXML() {#a28fef240bd687173e6e9184e82bcf391}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotInclDepGraph::writeXML (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00043">43</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00211">211</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28fef240bd687173e6e9184e82bcf391">211</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a28fef240bd687173e6e9184e82bcf391">DotInclDepGraph::writeXML</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,node] : <a href="#a3bf314d8bc14e0501b11d9633ea040fb">m_usedNodes</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">    node-&gt;writeXML(t,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#a3bf314d8bc14e0501b11d9633ea040fb">m&#95;usedNodes</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a541a7f1681d4e6c18ba0fb4902f2b9d3">generateXMLForFile</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### computeTheGraph() {#a0eb34c13a6a603939648310908c1b6b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotInclDepGraph::computeTheGraph ()</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00049">49</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00166">166</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0eb34c13a6a603939648310908c1b6b2">166</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0eb34c13a6a603939648310908c1b6b2">DotInclDepGraph::computeTheGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">computeGraph</a>(<a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a90a95d6639a7bbbeff7f36a7ec8f3b10">GraphType::Dependency</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a352bf93d2d15ed13d368233c85892a9f">m_graphFormat</a>, </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">               <a href="#a441c062f595f392e77c874d57faafa73">m_inverse</a>, <a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>-&gt;label(), <a href="/web-doxygen/docs/api/classes/dotgraph/#ab5e616cb48fb662c41e80b713792bc58">m_theGraph</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">DotGraph::computeGraph</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a90a95d6639a7bbbeff7f36a7ec8f3b10">Dependency</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a352bf93d2d15ed13d368233c85892a9f">DotGraph::m&#95;graphFormat</a>, <a href="#a441c062f595f392e77c874d57faafa73">m&#95;inverse</a>, <a href="#ab7e7a007c38e953df49b925d902e634e">m&#95;startNode</a> and <a href="/web-doxygen/docs/api/classes/dotgraph/#ab5e616cb48fb662c41e80b713792bc58">DotGraph::m&#95;theGraph</a>.
</div>
</div>

### getBaseName() {#ac80224cf47d91c0235efbe9a2b9fef08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotInclDepGraph::getBaseName ()</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00047">47</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00154">154</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac80224cf47d91c0235efbe9a2b9fef08">154</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ac80224cf47d91c0235efbe9a2b9fef08">DotInclDepGraph::getBaseName</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a441c062f595f392e77c874d57faafa73">m_inverse</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af2e50c911e5a8a9522b91e6ffcc7bd58">m_inclByDepFileName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5b1ac9f793179e523b7c91fbf6ec7610">m_inclDepFileName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#af2e50c911e5a8a9522b91e6ffcc7bd58">m&#95;inclByDepFileName</a>, <a href="#a5b1ac9f793179e523b7c91fbf6ec7610">m&#95;inclDepFileName</a> and <a href="#a441c062f595f392e77c874d57faafa73">m&#95;inverse</a>.
</div>
</div>

### getMapLabel() {#ae40c9c4198c440c72aaa52f8f1ada8eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotInclDepGraph::getMapLabel ()</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00048">48</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00172">172</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae40c9c4198c440c72aaa52f8f1ada8eb">172</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae40c9c4198c440c72aaa52f8f1ada8eb">DotInclDepGraph::getMapLabel</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a441c062f595f392e77c874d57faafa73">m_inverse</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>(<a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>-&gt;label(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>) + </span><span class="doxyHighlightStringLiteral">"dep"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>(<a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>-&gt;label(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a441c062f595f392e77c874d57faafa73">m&#95;inverse</a> and <a href="#ab7e7a007c38e953df49b925d902e634e">m&#95;startNode</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### buildGraph() {#ad88aa8095a13ae269eb1a17631909f06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotInclDepGraph::buildGraph (<a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * n, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, int distance)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00053">53</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00022">22</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad88aa8095a13ae269eb1a17631909f06">22</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad88aa8095a13ae269eb1a17631909f06">DotInclDepGraph::buildGraph</a>(<a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *n,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> distance)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">23</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">24</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/includeinfolist">IncludeInfoList</a> &amp;includeFiles = <a href="#a441c062f595f392e77c874d57faafa73">m_inverse</a> ? fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#ae9c6fecec7ff96fded91315943519a25">includedByFileList</a>() : fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aaa1fd01a880dff1fb1724a1dd209693f">includeFileList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">25</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ii : includeFiles)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">26</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">27</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *bfd = ii.fileDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">28</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> in = ii.includeName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("&gt;&gt;&gt;&gt; in='%s' bfd=%p\n",qPrint(ii-&gt;includeName),bfd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> doc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,src=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bfd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">      in  = bfd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">absFilePath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">      doc = bfd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>() &amp;&amp; !bfd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">isHidden</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">      src = bfd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a6702563833af37fc90c00d231c4574b5">generateSourceFile</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doc || src || !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HIDE_UNDOC_RELATIONS))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bfd) url=bfd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!doc &amp;&amp; src)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">        url=bfd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ab7ecf3e26ca026ed20af225f332e5fe7">getSourceFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a3bf314d8bc14e0501b11d9633ea040fb">m_usedNodes</a>.find(in.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#a3bf314d8bc14e0501b11d9633ea040fb">m_usedNodes</a>.end()) </span><span class="doxyHighlightComment">// file is already a node in the graph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *bn = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">        n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#ac54555a412724c31181a40a50213e38e">addChild</a>(bn,<a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>,<a href="/web-doxygen/docs/api/classes/edgeinfo/#a4fe2d2921d0f51d84da1bf48b3b4f2c5a26f6a09cd44415e9be80ccabf5195989">EdgeInfo::Solid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">        bn-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a98f7fc0d1caa3e53622039e86903b04e">addParent</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">        bn-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a21956cf8ee9e3f8b750c221f6d00ee84">setDistance</a>(distance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp_url;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bfd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">          tmp_url=doc || src ? bfd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>()+</span><span class="doxyHighlightStringLiteral">"$"</span><span class="doxyHighlight">+url : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">          tooltip = bfd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *bn = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">                         ii.includeName,   </span><span class="doxyHighlightComment">// label</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">                         tooltip,           </span><span class="doxyHighlightComment">// tip</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">                         tmp_url,           </span><span class="doxyHighlightComment">// url</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,             </span><span class="doxyHighlightComment">// rootNode</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);                </span><span class="doxyHighlightComment">// cd</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">        n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#ac54555a412724c31181a40a50213e38e">addChild</a>(bn,<a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>,<a href="/web-doxygen/docs/api/classes/edgeinfo/#a4fe2d2921d0f51d84da1bf48b3b4f2c5a26f6a09cd44415e9be80ccabf5195989">EdgeInfo::Solid</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">        bn-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a98f7fc0d1caa3e53622039e86903b04e">addParent</a>(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a3bf314d8bc14e0501b11d9633ea040fb">m_usedNodes</a>.emplace(in.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),bn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">        bn-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a21956cf8ee9e3f8b750c221f6d00ee84">setDistance</a>(distance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bfd) <a href="#ad88aa8095a13ae269eb1a17631909f06">buildGraph</a>(bn,bfd,distance+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/filedef/#a800e157b3a9d9d68b3961528e60117d9">FileDef::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#ac54555a412724c31181a40a50213e38e">DotNode::addChild</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a98f7fc0d1caa3e53622039e86903b04e">DotNode::addParent</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#afd9f10f4693123d11e52bb1127f23228ad86037d0f4029916bab272b972da808e">EdgeInfo::Blue</a>, <a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">Definition::briefDescriptionAsTooltip</a>, <a href="#ad88aa8095a13ae269eb1a17631909f06">buildGraph</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a6702563833af37fc90c00d231c4574b5">FileDef::generateSourceFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>, <a href="/web-doxygen/docs/api/classes/definition/#ab7ecf3e26ca026ed20af225f332e5fe7">Definition::getSourceFileBase</a>, <a href="/web-doxygen/docs/api/classes/filedef/#ae9c6fecec7ff96fded91315943519a25">FileDef::includedByFileList</a>, <a href="/web-doxygen/docs/api/classes/filedef/#aaa1fd01a880dff1fb1724a1dd209693f">FileDef::includeFileList</a>, <a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">Definition::isHidden</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>, <a href="#a441c062f595f392e77c874d57faafa73">m&#95;inverse</a>, <a href="#a3bf314d8bc14e0501b11d9633ea040fb">m&#95;usedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a21956cf8ee9e3f8b750c221f6d00ee84">DotNode::setDistance</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#a4fe2d2921d0f51d84da1bf48b3b4f2c5a26f6a09cd44415e9be80ccabf5195989">EdgeInfo::Solid</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#ad88aa8095a13ae269eb1a17631909f06">buildGraph</a> and <a href="#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph</a>.
</div>
</div>

### determineTruncatedNodes() {#a8aa3c90f1ef0858e708cb5636e9ed73b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotInclDepGraph::determineTruncatedNodes (<a href="/web-doxygen/docs/api/classes/dotnodedeque">DotNodeDeque</a> &amp; queue)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00055">55</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00098">98</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8aa3c90f1ef0858e708cb5636e9ed73b">98</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8aa3c90f1ef0858e708cb5636e9ed73b">DotInclDepGraph::determineTruncatedNodes</a>(<a href="/web-doxygen/docs/api/classes/dotnodedeque">DotNodeDeque</a> &amp;queue)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!queue.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *n = queue.front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">    queue.pop_front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a9e97a698e9e6460cd7fac782e38f0ce7">isVisible</a>() &amp;&amp; n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#adcfb83215c88dcdd5c39391547e3882b">isTruncated</a>()==<a href="/web-doxygen/docs/api/classes/dotnode/#ac40de94762a7659599b2056942373102adba69679a9bcc9333c7165d4e7bdade0">DotNode::Unknown</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> truncated = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dn : n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!dn-&gt;isVisible())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">          truncated = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">          queue.push_back(dn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a543c8aa7d944877ff050dbdb9bbfd7db">markAsTruncated</a>(truncated);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dotnode/#ad8b1f38e1403f73fc4f8745b5fbe00c9">DotNode::children</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#adcfb83215c88dcdd5c39391547e3882b">DotNode::isTruncated</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a9e97a698e9e6460cd7fac782e38f0ce7">DotNode::isVisible</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a543c8aa7d944877ff050dbdb9bbfd7db">DotNode::markAsTruncated</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/dotnode/#ac40de94762a7659599b2056942373102adba69679a9bcc9333c7165d4e7bdade0">DotNode::Unknown</a>.

Referenced by <a href="#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph</a>.
</div>
</div>

### determineVisibleNodes() {#a1a4d42a2191cbdac155f1f9b67c4bfb5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotInclDepGraph::determineVisibleNodes (<a href="/web-doxygen/docs/api/classes/dotnodedeque">DotNodeDeque</a> &amp; queue, int &amp; maxNodes)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00054">54</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp/#l00079">79</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a4d42a2191cbdac155f1f9b67c4bfb5">79</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1a4d42a2191cbdac155f1f9b67c4bfb5">DotInclDepGraph::determineVisibleNodes</a>(<a href="/web-doxygen/docs/api/classes/dotnodedeque">DotNodeDeque</a> &amp;queue, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;maxNodes)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!queue.empty() &amp;&amp; maxNodes&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *n = queue.front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">    queue.pop_front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a9e97a698e9e6460cd7fac782e38f0ce7">isVisible</a>() &amp;&amp; n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a196e6efc147272506e3e0564dfe47bfe">distance</a>()&lt;=<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(MAX_DOT_GRAPH_DEPTH)) </span><span class="doxyHighlightComment">// not yet processed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">      n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#a2592b8669b2aba1c2f0476e1011d48cd">markAsVisible</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">      maxNodes--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// add direct children</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dn : n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">        queue.push_back(dn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dotnode/#ad8b1f38e1403f73fc4f8745b5fbe00c9">DotNode::children</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config&#95;getInt</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a196e6efc147272506e3e0564dfe47bfe">DotNode::distance</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a9e97a698e9e6460cd7fac782e38f0ce7">DotNode::isVisible</a> and <a href="/web-doxygen/docs/api/classes/dotnode/#a2592b8669b2aba1c2f0476e1011d48cd">DotNode::markAsVisible</a>.

Referenced by <a href="#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph</a>.
</div>
</div>

### diskName() {#a00b3a6cdc1fbbc725b862fd6f474eefc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotInclDepGraph::diskName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00052">52</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>.</p>

Reference <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;inclByDepFileName {#af2e50c911e5a8a9522b91e6ffcc7bd58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotInclDepGraph::m_inclByDepFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00060">60</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af2e50c911e5a8a9522b91e6ffcc7bd58">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>        <a href="#af2e50c911e5a8a9522b91e6ffcc7bd58">m_inclByDepFileName</a>;</span></span></div>

</div>


Referenced by <a href="#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph</a> and <a href="#ac80224cf47d91c0235efbe9a2b9fef08">getBaseName</a>.
</div>
</div>

### m&#95;inclDepFileName {#a5b1ac9f793179e523b7c91fbf6ec7610}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotInclDepGraph::m_inclDepFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00059">59</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b1ac9f793179e523b7c91fbf6ec7610">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>        <a href="#a5b1ac9f793179e523b7c91fbf6ec7610">m_inclDepFileName</a>;</span></span></div>

</div>


Referenced by <a href="#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph</a> and <a href="#ac80224cf47d91c0235efbe9a2b9fef08">getBaseName</a>.
</div>
</div>

### m&#95;inverse {#a441c062f595f392e77c874d57faafa73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotInclDepGraph::m_inverse</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00061">61</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a441c062f595f392e77c874d57faafa73">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">            <a href="#a441c062f595f392e77c874d57faafa73">m_inverse</a>;</span></span></div>

</div>


Referenced by <a href="#ad88aa8095a13ae269eb1a17631909f06">buildGraph</a>, <a href="#a0eb34c13a6a603939648310908c1b6b2">computeTheGraph</a>, <a href="#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph</a>, <a href="#ac80224cf47d91c0235efbe9a2b9fef08">getBaseName</a> and <a href="#ae40c9c4198c440c72aaa52f8f1ada8eb">getMapLabel</a>.
</div>
</div>

### m&#95;startNode {#ab7e7a007c38e953df49b925d902e634e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNode* DotInclDepGraph::m_startNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00057">57</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab7e7a007c38e953df49b925d902e634e">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>        *<a href="#ab7e7a007c38e953df49b925d902e634e">m_startNode</a>;</span></span></div>

</div>


Referenced by <a href="#a0eb34c13a6a603939648310908c1b6b2">computeTheGraph</a>, <a href="#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph</a>, <a href="#ae40c9c4198c440c72aaa52f8f1ada8eb">getMapLabel</a>, <a href="#afe9784772becb74106aa3978a52105eb">isTrivial</a>, <a href="#acd9c22a1f88a178e369914f0c8fb55b0">numNodes</a> and <a href="#af16036a50c08251c90de8841af69858a">~DotInclDepGraph</a>.
</div>
</div>

### m&#95;usedNodes {#a3bf314d8bc14e0501b11d9633ea040fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNodeMap DotInclDepGraph::m_usedNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h/#l00058">58</a> of file <a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3bf314d8bc14e0501b11d9633ea040fb">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotnodemap">DotNodeMap</a>      <a href="#a3bf314d8bc14e0501b11d9633ea040fb">m_usedNodes</a>;</span></span></div>

</div>


Referenced by <a href="#ad88aa8095a13ae269eb1a17631909f06">buildGraph</a>, <a href="#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph</a>, <a href="#a8c2162d40ea8f7ab188a37247b5b2bb5">writeDocbook</a> and <a href="#a28fef240bd687173e6e9184e82bcf391">writeXML</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dotincldepgraph-cpp">dotincldepgraph.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
