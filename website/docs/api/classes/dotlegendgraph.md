---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/dotlegendgraph
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DotLegendGraph` Class Reference

<p>Representation of a legend explaining the meaning of boxes, arrows, and colors. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DotLegendGraph { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dotlegendgraph-h">src/dotlegendgraph.h</a>&gt;
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c9836cd65db658dbf7eb0c6ecf7b40c">writeGraph</a> (const QCString &amp;path)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1b7b82b5688691f9b4518bd36331d38">getBaseName</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af02bfaa220696e0722080995d191d001">computeTheGraph</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0829196d87b7b0e0b5e38803b641ca32">getMapLabel</a> () const override</td>
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

<p>Representation of a legend explaining the meaning of boxes, arrows, and colors.</p>

<p>Definition at line 22 of file <a href="/web-doxygen/docs/api/files/src/dotlegendgraph-h">dotlegendgraph.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### writeGraph() {#a3c9836cd65db658dbf7eb0c6ecf7b40c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotLegendGraph::writeGraph (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 25 of file <a href="/web-doxygen/docs/api/files/src/dotlegendgraph-h">dotlegendgraph.h</a>, definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/dotlegendgraph-cpp">dotlegendgraph.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c9836cd65db658dbf7eb0c6ecf7b40c">27</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3c9836cd65db658dbf7eb0c6ecf7b40c">DotLegendGraph::writeGraph</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">28</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> ts;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>(ts, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">EmbeddedOutputFormat::Html</a>, path, </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, 0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>()==</span><span class="doxyHighlightStringLiteral">"svg"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotmanager/#af6eb5ac505738992f7440e4a5948997f">DotManager::instance</a>()-&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">      createFilePatcher(<a href="/web-doxygen/docs/api/classes/dotgraph/#a00a105210cfc45c863c9cdc3ffbf846b">absBaseName</a>()+<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_FILE_EXTENSION))-&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">      addSVGObject(</span><span class="doxyHighlightStringLiteral">"graph_legend"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/dotgraph/#a241721d514fbcc695b83683c2be89018">absImgName</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dotgraph/#a00a105210cfc45c863c9cdc3ffbf846b">DotGraph::absBaseName</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a241721d514fbcc695b83683c2be89018">DotGraph::absImgName</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="/web-doxygen/docs/api/classes/dotmanager/#af6eb5ac505738992f7440e4a5948997f">DotManager::instance</a> and <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### computeTheGraph() {#af02bfaa220696e0722080995d191d001}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotLegendGraph::computeTheGraph ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 29 of file <a href="/web-doxygen/docs/api/files/src/dotlegendgraph-h">dotlegendgraph.h</a>, definition at line 45 of file <a href="/web-doxygen/docs/api/files/src/dotlegendgraph-cpp">dotlegendgraph.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af02bfaa220696e0722080995d191d001">45</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af02bfaa220696e0722080995d191d001">DotLegendGraph::computeTheGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> md5stream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#a4e1ec8b0e7ecc8e0d27c869e43d75640">writeGraphHeader</a>(md5stream,<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trLegendTitle());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>{</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"Inherited"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>}.setNodeId(9).writeBox(md5stream, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a9d0f6d0fe9c95c9cb09769b9879db1ff">GraphType::CallGraph</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>, </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node10 -&gt; Node9 [dir=\"back\",color=\"steelblue1\",style=\"solid\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>{</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"PublicBase"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/dotnode/#ad1c9b1e1192faac2bf956a6a3043be0c">DotNode::placeholderUrl</a>}.setNodeId(10).markHasDocumentation().writeBox(md5stream, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a9d0f6d0fe9c95c9cb09769b9879db1ff">GraphType::CallGraph</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>, </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node11 -&gt; Node10 [dir=\"back\",color=\"steelblue1\",style=\"solid\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>{</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"Truncated"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/dotnode/#ad1c9b1e1192faac2bf956a6a3043be0c">DotNode::placeholderUrl</a>}.setNodeId(11).markAsTruncated().markHasDocumentation().writeBox(md5stream, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a9d0f6d0fe9c95c9cb09769b9879db1ff">GraphType::CallGraph</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>, </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node13 -&gt; Node9 [dir=\"back\",color=\"darkgreen\",style=\"solid\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node13 [label=\"ProtectedBase\",color=\"gray40\",fillcolor=\"white\",style=\"filled\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node14 -&gt; Node9 [dir=\"back\",color=\"firebrick4\",style=\"solid\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node14 [label=\"PrivateBase\",color=\"gray40\",fillcolor=\"white\",style=\"filled\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node15 -&gt; Node9 [dir=\"back\",color=\"steelblue1\",style=\"solid\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a>{</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"Undocumented"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">}.setNodeId(15).writeBox(md5stream, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a9d0f6d0fe9c95c9cb09769b9879db1ff">GraphType::CallGraph</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>, </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node16 -&gt; Node9 [dir=\"back\",color=\"steelblue1\",style=\"solid\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node16 [label=\"Templ\\&lt; int \\&gt;\",color=\"gray40\",fillcolor=\"white\",style=\"filled\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node17 -&gt; Node16 [dir=\"back\",color=\"orange\",style=\"dashed\",label=\"&lt; int &gt;\",fontcolor=\"grey\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node17 [label=\"Templ\\&lt; T \\&gt;\",color=\"gray40\",fillcolor=\"white\",style=\"filled\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node18 -&gt; Node9 [dir=\"back\",color=\"darkorchid3\",style=\"dashed\",label=\"m_usedClass\",fontcolor=\"grey\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  Node18 [label=\"Used\",color=\"gray40\",fillcolor=\"white\",style=\"filled\" tooltip=\" \"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#a256ce4336c69cbb9b15e473afc456805">writeGraphFooter</a>(md5stream);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#ab5e616cb48fb662c41e80b713792bc58">m_theGraph</a> = md5stream.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a9d0f6d0fe9c95c9cb09769b9879db1ff">CallGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#ab5e616cb48fb662c41e80b713792bc58">DotGraph::m_theGraph</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#ad1c9b1e1192faac2bf956a6a3043be0c">DotNode::placeholderUrl</a>, <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a256ce4336c69cbb9b15e473afc456805">DotGraph::writeGraphFooter</a> and <a href="/web-doxygen/docs/api/classes/dotgraph/#a4e1ec8b0e7ecc8e0d27c869e43d75640">DotGraph::writeGraphHeader</a>.</p>

</div>
</div>

### getBaseName() {#ae1b7b82b5688691f9b4518bd36331d38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotLegendGraph::getBaseName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 28 of file <a href="/web-doxygen/docs/api/files/src/dotlegendgraph-h">dotlegendgraph.h</a>, definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/dotlegendgraph-cpp">dotlegendgraph.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae1b7b82b5688691f9b4518bd36331d38">40</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae1b7b82b5688691f9b4518bd36331d38">DotLegendGraph::getBaseName</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"graph_legend"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### getMapLabel() {#a0829196d87b7b0e0b5e38803b641ca32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotLegendGraph::getMapLabel ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-doxygen/docs/api/files/src/dotlegendgraph-h">dotlegendgraph.h</a>, definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/dotlegendgraph-cpp">dotlegendgraph.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0829196d87b7b0e0b5e38803b641ca32">71</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0829196d87b7b0e0b5e38803b641ca32">DotLegendGraph::getMapLabel</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dotlegendgraph-cpp">dotlegendgraph.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/dotlegendgraph-h">dotlegendgraph.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
