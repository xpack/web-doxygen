---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/dotgfxhierarchytable
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DotGfxHierarchyTable` Class Reference

Represents a graphical class hierarchy. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class DotGfxHierarchyTable { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">src/dotgfxhierarchytable.h</a>&gt;
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

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcc58e76f024a560b3ac0f6b210023e8">DotNodeMap</a> = std::unordered_multimap&lt; std::string, std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> &gt; &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e9a28f1f5867cc3d2de69b7db30c15f">DotGfxHierarchyTable</a> (const QCString &amp;prefix="", ClassDef::CompoundType ct=ClassDef::Class)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434bb97932efb57dc0df493217c9a687">~DotGfxHierarchyTable</a> () override=default</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a98b48366bc0fc41ee0d43eb425087a">createGraph</a> (DotNode *rootNode, TextStream &amp;t, const QCString &amp;path, const QCString &amp;fileName, int id)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47c5aeaf257c00ebecc958a4c78c5de9">writeGraph</a> (TextStream &amp;t, const QCString &amp;path, const QCString &amp;fileName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const std::vector&lt; <a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69d80de93b7cc6481722f0a79d7fc6c0">subGraphs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d49e892872b87e8c5d19fc190b6512">getBaseName</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20d5e5fc185059e80b4c080a28ba550a">getMapLabel</a> () const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75c5c04dae25cb36a4715d0c49a4b196">computeTheGraph</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45107701951da66c41e13c127fc1e6e6">addHierarchy</a> (DotNode *n, const ClassDef *cd, ClassDefSet &amp;visited)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c46ad2d91b685cb40efdc4ffeb85e61">addClassList</a> (const ClassLinkedMap &amp;cl, ClassDefSet &amp;visited)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b7f4e1246f73f8aaded6883e990a57b">m_graphId</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addef5c344b77e954bd92c44c6f768126">m_prefix</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">ClassDef::CompoundType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2416c7105ffa6921afb732f1ae02576">m_classType</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae95c2d0497af31d870cdec866e18e97f">m_rootNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#adcc58e76f024a560b3ac0f6b210023e8">DotNodeMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bd18aa03f734599e511071075d2d0a5">m_usedNodes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m_rootSubgraphs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4ca8f1f6de9f177db00629f53a75c6c">m_rootSubgraphNode</a></td>
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

Represents a graphical class hierarchy.

Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>.

<div class="doxySectionDef">

## Private Member Typedefs

### DotNodeMap {#adcc58e76f024a560b3ac0f6b210023e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DotGfxHierarchyTable::DotNodeMap =  std::unordered_multimap&lt; std::string, std::unique_ptr&lt;DotNode&gt; &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 52 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adcc58e76f024a560b3ac0f6b210023e8">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#adcc58e76f024a560b3ac0f6b210023e8">DotNodeMap</a> = std::unordered_multimap&lt; std::string, std::unique_ptr&lt;DotNode&gt; &gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DotGfxHierarchyTable() {#a3e9a28f1f5867cc3d2de69b7db30c15f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotGfxHierarchyTable::DotGfxHierarchyTable (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; prefix="", <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">ClassDef::CompoundType</a> ct=<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939a5261cde79065c9b6af97195e43e8073b">ClassDef::Class</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 34 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>, definition at line 226 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-cpp">dotgfxhierarchytable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3e9a28f1f5867cc3d2de69b7db30c15f">226</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a3e9a28f1f5867cc3d2de69b7db30c15f">DotGfxHierarchyTable::DotGfxHierarchyTable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>,<a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">ClassDef::CompoundType</a> ct)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#addef5c344b77e954bd92c44c6f768126">m_prefix</a>(<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  , <a href="#ae2416c7105ffa6921afb732f1ae02576">m_classType</a>(ct)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// build a graph with each class as a node and the inheritance relations</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// as edges</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/classdef-h/#a2e17794c6e9690fd7c30698ae3abe9bf">ClassDefSet</a> visitedClasses;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2c46ad2d91b685cb40efdc4ffeb85e61">addClassList</a>(*<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>,visitedClasses);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2c46ad2d91b685cb40efdc4ffeb85e61">addClassList</a>(*<a href="/web-doxygen/docs/api/classes/doxygen/#aa0f09f8179e2e4b6da595beaa37e17dd">Doxygen::hiddenClassLinkedMap</a>,visitedClasses);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// m_usedNodes now contains all nodes in the graph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// color the graph into a set of independent subgraphs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> curColor=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!done) </span><span class="doxyHighlightComment">// there are still nodes to color</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightComment">// we are done unless there are still uncolored nodes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> n : <a href="#ae95c2d0497af31d870cdec866e18e97f">m_rootNodes</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n-&gt;subgraphId()==-1) </span><span class="doxyHighlightComment">// not yet colored</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("Starting at node %s (%p): %d\n",qPrint(n-&gt;label()),n,curColor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">        done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; </span><span class="doxyHighlightComment">// still uncolored nodes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">        n-&gt;setSubgraphId(curColor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">        n-&gt;markAsVisible();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">        n-&gt;colorConnectedNodes(curColor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">        curColor++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m_rootSubgraphs</a>.push_back(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Number of independent subgraphs: %d\n",curColor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> n : <a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m_rootSubgraphs</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Node %s color=%d (c=%d,p=%d)\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    qPrint(n-&gt;label()),n-&gt;m_subgraphId,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    n-&gt;children()?n-&gt;children()-&gt;count():0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    n-&gt;parents()?n-&gt;parents()-&gt;count():0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> number=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">    n-&gt;renumberNodes(number);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a2c46ad2d91b685cb40efdc4ffeb85e61">addClassList</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#aa0f09f8179e2e4b6da595beaa37e17dd">Doxygen::hiddenClassLinkedMap</a>, <a href="#ae2416c7105ffa6921afb732f1ae02576">m\_classType</a>, <a href="#addef5c344b77e954bd92c44c6f768126">m\_prefix</a>, <a href="#ae95c2d0497af31d870cdec866e18e97f">m\_rootNodes</a>, <a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m\_rootSubgraphs</a>, <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a434bb97932efb57dc0df493217c9a687">\~DotGfxHierarchyTable</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DotGfxHierarchyTable() {#a434bb97932efb57dc0df493217c9a687}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotGfxHierarchyTable::~DotGfxHierarchyTable ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>.

References <a href="#a3e9a28f1f5867cc3d2de69b7db30c15f">DotGfxHierarchyTable</a> and <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createGraph() {#a7a98b48366bc0fc41ee0d43eb425087a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotGfxHierarchyTable::createGraph (<a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * rootNode, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int id)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 38 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>, definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-cpp">dotgfxhierarchytable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a98b48366bc0fc41ee0d43eb425087a">65</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7a98b48366bc0fc41ee0d43eb425087a">DotGfxHierarchyTable::createGraph</a>(<a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *n,<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;out,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac4ca8f1f6de9f177db00629f53a75c6c">m_rootSubgraphNode</a> = n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5b7f4e1246f73f8aaded6883e990a57b">m_graphId</a> = id;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#a0e2edc905a769cb9613f050ef092f82b">m_noDivTag</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#aa7fd99414b3925cf99fcffb171ce3d1b">m_zoomable</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>(out, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">EmbeddedOutputFormat::Html</a>, path, fileName, </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, 0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="#a5b7f4e1246f73f8aaded6883e990a57b">m\_graphId</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a0e2edc905a769cb9613f050ef092f82b">DotGraph::m\_noDivTag</a>, <a href="#ac4ca8f1f6de9f177db00629f53a75c6c">m\_rootSubgraphNode</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aa7fd99414b3925cf99fcffb171ce3d1b">DotGraph::m\_zoomable</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>.

Referenced by <a href="#a47c5aeaf257c00ebecc958a4c78c5de9">writeGraph</a>.
</div>
</div>

### subGraphs() {#a69d80de93b7cc6481722f0a79d7fc6c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; DotNode * &gt; DotGfxHierarchyTable::subGraphs ()</td>
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



Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a69d80de93b7cc6481722f0a79d7fc6c0">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::vector&lt;DotNode*&gt; <a href="#a69d80de93b7cc6481722f0a79d7fc6c0">subGraphs</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m_rootSubgraphs</a>; }</span></span></div>

</div>


Reference <a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m\_rootSubgraphs</a>.
</div>
</div>

### writeGraph() {#a47c5aeaf257c00ebecc958a4c78c5de9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotGfxHierarchyTable::writeGraph (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 40 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>, definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-cpp">dotgfxhierarchytable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a47c5aeaf257c00ebecc958a4c78c5de9">75</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a47c5aeaf257c00ebecc958a4c78c5de9">DotGfxHierarchyTable::writeGraph</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;out,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DotGfxHierarchyTable::writeGraph(%s)\n",name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("m_rootNodes=%p count=%d\n",m_rootNodes,m_rootNodes-&gt;count());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m_rootSubgraphs</a>.empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> d(path.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// store the original directory</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!d.<a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Output dir {} does not exist!\n"</span><span class="doxyHighlight">,path);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// put each connected subgraph of the hierarchy in a row of the HTML output</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table border=\"0\" cellspacing=\"10\" cellpadding=\"0\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  std::stable_sort(<a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m_rootSubgraphs</a>.begin(),<a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m_rootSubgraphs</a>.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">            [](</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> n1,</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> n2) { return qstricmp_sort(n1-&gt;label(),n2-&gt;label())&lt;0; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> n : <a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m_rootSubgraphs</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">    out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tr&gt;&lt;td&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7a98b48366bc0fc41ee0d43eb425087a">createGraph</a>(n,out,path,fileName,count++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">    out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;&lt;/tr&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a7a98b48366bc0fc41ee0d43eb425087a">createGraph</a>, <a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">Dir::exists</a>, <a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m\_rootSubgraphs</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ad05e0b9d1baf567428af8a4e6b96b0ca">HtmlGenerator::writeGraphicalHierarchy</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Functions

### computeTheGraph() {#a75c5c04dae25cb36a4715d0c49a4b196}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotGfxHierarchyTable::computeTheGraph ()</td>
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



Declaration at line 46 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>, definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-cpp">dotgfxhierarchytable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75c5c04dae25cb36a4715d0c49a4b196">37</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a75c5c04dae25cb36a4715d0c49a4b196">DotGfxHierarchyTable::computeTheGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> md5stream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#a4e1ec8b0e7ecc8e0d27c869e43d75640">writeGraphHeader</a>(md5stream,<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trGraphicalHierarchy());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  rankdir=\"LR\";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> node : <a href="#ae95c2d0497af31d870cdec866e18e97f">m_rootNodes</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (node-&gt;subgraphId()==<a href="#ac4ca8f1f6de9f177db00629f53a75c6c">m_rootSubgraphNode</a>-&gt;subgraphId())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">      node-&gt;clearWriteFlag();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> node : <a href="#ae95c2d0497af31d870cdec866e18e97f">m_rootNodes</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (node-&gt;subgraphId()==<a href="#ac4ca8f1f6de9f177db00629f53a75c6c">m_rootSubgraphNode</a>-&gt;subgraphId())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      node-&gt;write(md5stream,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a0748856bca50f42e2abd5b36ca083bae">GraphType::Hierarchy</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#a256ce4336c69cbb9b15e473afc456805">writeGraphFooter</a>(md5stream);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotgraph/#ab5e616cb48fb662c41e80b713792bc58">m_theGraph</a> = md5stream.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a0c7c85309652245e03563b127f451f72a0748856bca50f42e2abd5b36ca083bae">Hierarchy</a>, <a href="#ae95c2d0497af31d870cdec866e18e97f">m\_rootNodes</a>, <a href="#ac4ca8f1f6de9f177db00629f53a75c6c">m\_rootSubgraphNode</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#ab5e616cb48fb662c41e80b713792bc58">DotGraph::m\_theGraph</a>, <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a256ce4336c69cbb9b15e473afc456805">DotGraph::writeGraphFooter</a> and <a href="/web-doxygen/docs/api/classes/dotgraph/#a4e1ec8b0e7ecc8e0d27c869e43d75640">DotGraph::writeGraphHeader</a>.
</div>
</div>

### getBaseName() {#ae3d49e892872b87e8c5d19fc190b6512}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotGfxHierarchyTable::getBaseName ()</td>
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



Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>, definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-cpp">dotgfxhierarchytable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3d49e892872b87e8c5d19fc190b6512">27</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae3d49e892872b87e8c5d19fc190b6512">DotGfxHierarchyTable::getBaseName</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">28</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#addef5c344b77e954bd92c44c6f768126">m_prefix</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">    baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"inherit_graph_%d"</span><span class="doxyHighlight">, <a href="#a5b7f4e1246f73f8aaded6883e990a57b">m_graphId</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">    baseName.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%sinherit_graph_%d"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(<a href="#addef5c344b77e954bd92c44c6f768126">m_prefix</a>), <a href="#a5b7f4e1246f73f8aaded6883e990a57b">m_graphId</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a5b7f4e1246f73f8aaded6883e990a57b">m\_graphId</a>, <a href="#addef5c344b77e954bd92c44c6f768126">m\_prefix</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>.
</div>
</div>

### getMapLabel() {#a20d5e5fc185059e80b4c080a28ba550a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotGfxHierarchyTable::getMapLabel ()</td>
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



Declaration at line 45 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>, definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-cpp">dotgfxhierarchytable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a20d5e5fc185059e80b4c080a28ba550a">60</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a20d5e5fc185059e80b4c080a28ba550a">DotGfxHierarchyTable::getMapLabel</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>(<a href="#ac4ca8f1f6de9f177db00629f53a75c6c">m_rootSubgraphNode</a>-&gt;label(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#ac4ca8f1f6de9f177db00629f53a75c6c">m\_rootSubgraphNode</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addClassList() {#a2c46ad2d91b685cb40efdc4ffeb85e61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotGfxHierarchyTable::addClassList (const <a href="/web-doxygen/docs/api/classes/classlinkedmap">ClassLinkedMap</a> &amp; cl, <a href="/web-doxygen/docs/api/files/src/classdef-h/#a2e17794c6e9690fd7c30698ae3abe9bf">ClassDefSet</a> &amp; visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>, definition at line 179 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-cpp">dotgfxhierarchytable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2c46ad2d91b685cb40efdc4ffeb85e61">179</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2c46ad2d91b685cb40efdc4ffeb85e61">DotGfxHierarchyTable::addClassList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classlinkedmap">ClassLinkedMap</a> &amp;cl,<a href="/web-doxygen/docs/api/files/src/classdef-h/#a2e17794c6e9690fd7c30698ae3abe9bf">ClassDefSet</a> &amp;visitedClasses)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : cl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Trying %s subClasses=%d\n",qPrint(cd-&gt;name()),cd-&gt;subClasses()-&gt;count());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;getLanguage()==SrcLangExt::VHDL &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab1ab1504610c798f4924026a48bb4301">VhdlDocGen::convert</a>(cd-&gt;protection())!=<a href="/web-doxygen/docs/api/classes/vhdldocgen/#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">VhdlDocGen::ENTITYCLASS</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">      )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_SLICE) &amp;&amp; cd-&gt;compoundType() != <a href="#ae2416c7105ffa6921afb732f1ae02576">m_classType</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/classdef-cpp/#aa17b12d6a1e62b6d01659a5c9857aa4e">classHasVisibleRoot</a>(cd-&gt;baseClasses()) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">      cd-&gt;isVisibleInHierarchy()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">      ) </span><span class="doxyHighlightComment">// root node in the forest</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp_url=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;isLinkable() &amp;&amp; !cd-&gt;isHidden())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">        tmp_url=cd-&gt;getReference()+</span><span class="doxyHighlightStringLiteral">"$"</span><span class="doxyHighlight">+cd-&gt;getOutputFileBase();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cd-&gt;anchor().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">          tmp_url+=</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">+cd-&gt;anchor();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Inserting root class %s\n",qPrint(cd-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip = cd-&gt;briefDescriptionAsTooltip();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> n = std::make_unique&lt;DotNode&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">        cd-&gt;displayName(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">        tooltip,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">        tmp_url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *root = n.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6bd18aa03f734599e511071075d2d0a5">m_usedNodes</a>.emplace(cd-&gt;name().str(),std::move(n));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae95c2d0497af31d870cdec866e18e97f">m_rootNodes</a>.push_back(root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (visitedClasses.find(cd.get())==visitedClasses.end() &amp;&amp; !cd-&gt;subClasses().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a45107701951da66c41e13c127fc1e6e6">addHierarchy</a>(root,cd.get(),visitedClasses);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">        visitedClasses.insert(cd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a45107701951da66c41e13c127fc1e6e6">addHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#aa17b12d6a1e62b6d01659a5c9857aa4e">classHasVisibleRoot</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab1ab1504610c798f4924026a48bb4301">VhdlDocGen::convert</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a010ab08982f29df8c0f3d3f0f642f0f0a0f87010297b89ed715ad63fccec9b90e">VhdlDocGen::ENTITYCLASS</a>, <a href="#ae2416c7105ffa6921afb732f1ae02576">m\_classType</a>, <a href="#ae95c2d0497af31d870cdec866e18e97f">m\_rootNodes</a> and <a href="#a6bd18aa03f734599e511071075d2d0a5">m\_usedNodes</a>.

Referenced by <a href="#a3e9a28f1f5867cc3d2de69b7db30c15f">DotGfxHierarchyTable</a>.
</div>
</div>

### addHierarchy() {#a45107701951da66c41e13c127fc1e6e6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DotGfxHierarchyTable::addHierarchy (<a href="/web-doxygen/docs/api/classes/dotnode">DotNode</a> * n, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, <a href="/web-doxygen/docs/api/files/src/classdef-h/#a2e17794c6e9690fd7c30698ae3abe9bf">ClassDefSet</a> &amp; visited)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>, definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-cpp">dotgfxhierarchytable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a45107701951da66c41e13c127fc1e6e6">105</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a45107701951da66c41e13c127fc1e6e6">DotGfxHierarchyTable::addHierarchy</a>(<a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *n,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,<a href="/web-doxygen/docs/api/files/src/classdef-h/#a2e17794c6e9690fd7c30698ae3abe9bf">ClassDefSet</a> &amp;visitedClasses)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("addHierarchy '%s' baseClasses=%d\n",qPrint(cd-&gt;name()),cd-&gt;baseClasses()-&gt;count());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *bClass=bcd.classDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("  Trying sub class='%s' usedNodes=%d\n",qPrint(bClass-&gt;name()),m_usedNodes-&gt;count());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bClass &amp;&amp; bClass-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3067e647412a923d7743258c89eabe75">isVisibleInHierarchy</a>() &amp;&amp; <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#aa17b12d6a1e62b6d01659a5c9857aa4e">classHasVisibleRoot</a>(bClass-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a6bd18aa03f734599e511071075d2d0a5">m_usedNodes</a>.find(bClass-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("  Node '%s' Found visible class='%s'\n",qPrint(n-&gt;label()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//                                              qPrint(bClass-&gt;name()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *root = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#a6bd18aa03f734599e511071075d2d0a5">m_usedNodes</a>.end()) </span><span class="doxyHighlightComment">// node already present</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bn = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">        root = bn.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;children = n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#ad8b1f38e1403f73fc4f8745b5fbe00c9">children</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> child_it = std::find(children.begin(),children.end(),bn.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (child_it==children.end()) </span><span class="doxyHighlightComment">// no arrow yet</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">          n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#ac54555a412724c31181a40a50213e38e">addChild</a>(bn.get(),<a href="/web-doxygen/docs/api/classes/edgeinfo/#a8988355568d7d2f2fe1b876be67bac92">EdgeInfo::protectionToColor</a>(bcd.prot));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">          bn-&gt;addParent(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("  Adding node %s to existing base node %s (c=%d,p=%d)\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//       qPrint(n-&gt;label()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//       qPrint(bn-&gt;label()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//       bn-&gt;children() ? bn-&gt;children()-&gt;count() : 0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//       bn-&gt;parents()  ? bn-&gt;parents()-&gt;count()  : 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//     );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//  printf("  Class already has an arrow!\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp_url=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bClass-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>() &amp;&amp; !bClass-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">isHidden</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">          tmp_url=bClass-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>()+</span><span class="doxyHighlightStringLiteral">"$"</span><span class="doxyHighlight">+bClass-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!bClass-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">            tmp_url+=</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">+bClass-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip = bClass-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> bn = std::make_unique&lt;DotNode&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">            bClass-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac4741f70f06baac174cf71b3e11d06ac">displayName</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">            tooltip,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">            tmp_url</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">            );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">        n-&gt;<a href="/web-doxygen/docs/api/classes/dotnode/#ac54555a412724c31181a40a50213e38e">addChild</a>(bn.get(),<a href="/web-doxygen/docs/api/classes/edgeinfo/#a8988355568d7d2f2fe1b876be67bac92">EdgeInfo::protectionToColor</a>(bcd.prot));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">        bn-&gt;addParent(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">        root = bn.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("  Adding node %s to new base node %s (c=%d,p=%d)\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//   qPrint(n-&gt;label()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//   qPrint(bn-&gt;label()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//   bn-&gt;children() ? bn-&gt;children()-&gt;count() : 0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//   bn-&gt;parents()  ? bn-&gt;parents()-&gt;count()  : 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("  inserting %s (%p)\n",qPrint(bClass-&gt;name()),bn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a6bd18aa03f734599e511071075d2d0a5">m_usedNodes</a>.emplace(bClass-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),std::move(bn)); </span><span class="doxyHighlightComment">// add node to the used list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (visitedClasses.find(bClass)==visitedClasses.end() &amp;&amp; !bClass-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">        visitedClasses.insert(bClass);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a45107701951da66c41e13c127fc1e6e6">addHierarchy</a>(root,bClass,visitedClasses);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("end addHierarchy\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dotnode/#ac54555a412724c31181a40a50213e38e">DotNode::addChild</a>, <a href="#a45107701951da66c41e13c127fc1e6e6">addHierarchy</a>, <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">ClassDef::baseClasses</a>, <a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">Definition::briefDescriptionAsTooltip</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#ad8b1f38e1403f73fc4f8745b5fbe00c9">DotNode::children</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#aa17b12d6a1e62b6d01659a5c9857aa4e">classHasVisibleRoot</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac4741f70f06baac174cf71b3e11d06ac">Definition::displayName</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotGraph::DotNode</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definition/#a930740d353cfe143eb9efe0d12b7f938">Definition::isHidden</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a3067e647412a923d7743258c89eabe75">ClassDef::isVisibleInHierarchy</a>, <a href="#a6bd18aa03f734599e511071075d2d0a5">m\_usedNodes</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/edgeinfo/#a8988355568d7d2f2fe1b876be67bac92">EdgeInfo::protectionToColor</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">ClassDef::subClasses</a>.

Referenced by <a href="#a2c46ad2d91b685cb40efdc4ffeb85e61">addClassList</a> and <a href="#a45107701951da66c41e13c127fc1e6e6">addHierarchy</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_classType {#ae2416c7105ffa6921afb732f1ae02576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClassDef::CompoundType DotGfxHierarchyTable::m_classType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae2416c7105ffa6921afb732f1ae02576">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classdef/#ae70cf86d35fe954a94c566fbcfc87939">ClassDef::CompoundType</a> <a href="#ae2416c7105ffa6921afb732f1ae02576">m_classType</a>;</span></span></div>

</div>


Referenced by <a href="#a2c46ad2d91b685cb40efdc4ffeb85e61">addClassList</a> and <a href="#a3e9a28f1f5867cc3d2de69b7db30c15f">DotGfxHierarchyTable</a>.
</div>
</div>

### m\_graphId {#a5b7f4e1246f73f8aaded6883e990a57b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotGfxHierarchyTable::m_graphId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 53 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b7f4e1246f73f8aaded6883e990a57b">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                    <a href="#a5b7f4e1246f73f8aaded6883e990a57b">m_graphId</a>;</span></span></div>

</div>


Referenced by <a href="#a7a98b48366bc0fc41ee0d43eb425087a">createGraph</a> and <a href="#ae3d49e892872b87e8c5d19fc190b6512">getBaseName</a>.
</div>
</div>

### m\_prefix {#addef5c344b77e954bd92c44c6f768126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotGfxHierarchyTable::m_prefix</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#addef5c344b77e954bd92c44c6f768126">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>               <a href="#addef5c344b77e954bd92c44c6f768126">m_prefix</a>;</span></span></div>

</div>


Referenced by <a href="#a3e9a28f1f5867cc3d2de69b7db30c15f">DotGfxHierarchyTable</a> and <a href="#ae3d49e892872b87e8c5d19fc190b6512">getBaseName</a>.
</div>
</div>

### m\_rootNodes {#ae95c2d0497af31d870cdec866e18e97f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DotNode*&gt; DotGfxHierarchyTable::m_rootNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae95c2d0497af31d870cdec866e18e97f">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;DotNode*&gt;  <a href="#ae95c2d0497af31d870cdec866e18e97f">m_rootNodes</a>;</span></span></div>

</div>


Referenced by <a href="#a2c46ad2d91b685cb40efdc4ffeb85e61">addClassList</a>, <a href="#a75c5c04dae25cb36a4715d0c49a4b196">computeTheGraph</a> and <a href="#a3e9a28f1f5867cc3d2de69b7db30c15f">DotGfxHierarchyTable</a>.
</div>
</div>

### m\_rootSubgraphNode {#ac4ca8f1f6de9f177db00629f53a75c6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNode* DotGfxHierarchyTable::m_rootSubgraphNode</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac4ca8f1f6de9f177db00629f53a75c6c">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotgraph/#aef4faee1d16e4f21bb649b73001e3261">DotNode</a> *              <a href="#ac4ca8f1f6de9f177db00629f53a75c6c">m_rootSubgraphNode</a>;</span></span></div>

</div>


Referenced by <a href="#a75c5c04dae25cb36a4715d0c49a4b196">computeTheGraph</a>, <a href="#a7a98b48366bc0fc41ee0d43eb425087a">createGraph</a> and <a href="#a20d5e5fc185059e80b4c080a28ba550a">getMapLabel</a>.
</div>
</div>

### m\_rootSubgraphs {#a12cd9c4ea2e895b0a789e7480f9dae60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;DotNode*&gt; DotGfxHierarchyTable::m_rootSubgraphs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a12cd9c4ea2e895b0a789e7480f9dae60">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;DotNode*&gt;  <a href="#a12cd9c4ea2e895b0a789e7480f9dae60">m_rootSubgraphs</a>;</span></span></div>

</div>


Referenced by <a href="#a3e9a28f1f5867cc3d2de69b7db30c15f">DotGfxHierarchyTable</a>, <a href="#a69d80de93b7cc6481722f0a79d7fc6c0">subGraphs</a> and <a href="#a47c5aeaf257c00ebecc958a4c78c5de9">writeGraph</a>.
</div>
</div>

### m\_usedNodes {#a6bd18aa03f734599e511071075d2d0a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotNodeMap DotGfxHierarchyTable::m_usedNodes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6bd18aa03f734599e511071075d2d0a5">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#adcc58e76f024a560b3ac0f6b210023e8">DotNodeMap</a>             <a href="#a6bd18aa03f734599e511071075d2d0a5">m_usedNodes</a>;</span></span></div>

</div>


Referenced by <a href="#a2c46ad2d91b685cb40efdc4ffeb85e61">addClassList</a> and <a href="#a45107701951da66c41e13c127fc1e6e6">addHierarchy</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-cpp">dotgfxhierarchytable.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/dotgfxhierarchytable-h">dotgfxhierarchytable.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
