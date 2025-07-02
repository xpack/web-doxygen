---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/dotdirdeps-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `dotdirdeps.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/dotdirdeps-h">dotdirdeps.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/image-h">image.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>"
#include &lt;algorithm&gt;
#include &lt;iterator&gt;
#include &lt;utility&gt;
#include &lt;cstdint&gt;
#include &lt;math.h&gt;
#include &lt;cassert&gt;
#include &lt;map&gt;
#include &lt;memory&gt;
#include &lt;string&gt;
#include &lt;vector&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Properties are used to format the directories in the graph distinctively. <a href="/web-doxygen/docs/api/structs/dotdirproperty/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dotdirpropertybuilder">DotDirPropertyBuilder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Builder helper to create instances of the <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> struct. <a href="/web-doxygen/docs/api/classes/dotdirpropertybuilder/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa012bdc6c0e896cccb8121b3c6b7ad60">DirDefMap</a> = std::map&lt; std::string, const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">std::vector&lt; std::pair&lt; std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/dirrelation">DirRelation</a> &gt;, bool &gt; &gt; <a href="#a0540771f72e56700a0d30f72580d0065">DirRelations</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Elements consist of (1) directory relation and (2) whether it is pointing only to inherited dependees. <a href="#a0540771f72e56700a0d30f72580d0065">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a683792f7f7df231861acd54ff905211d">getDirectoryBackgroundColor</a> (int depthIndex)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns a DOT color name according to the directory depth. <a href="#a683792f7f7df231861acd54ff905211d">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed9febe225f49a478f1ac4ab8c92786d">getDirectoryBorderColor</a> (const DotDirProperty &amp;property)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns a DOT color name according to the directory properties. <a href="#aed9febe225f49a478f1ac4ab8c92786d">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa3fa8ed5c1cb6cfe4a5f821d1c776f">getDirectoryBorderStyle</a> (const DotDirProperty &amp;property)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns a DOT node style according to the directory properties. <a href="#a6aa3fa8ed5c1cb6cfe4a5f821d1c776f">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a120714f9fe392105dac20e1759dcb1d6">common_attributes</a> (TextStream &amp;t, const DirDef *const dir, const DotDirProperty &amp;prop)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a> (TextStream &amp;t, const DirDef *const directory, const DotDirProperty &amp;property, DirDefMap &amp;directoriesInGraph, int startLevel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Puts DOT code for drawing directory to stream and adds it to the list. <a href="#a840611db0f9ff308b7167b3fd3e0c4d2">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20837cde372c359b1ce5070096d472e0">isAtMaxDepth</a> (const DirDef *const directory, const int startLevel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Checks, if the directory is a the maximum drawn directory level. <a href="#a20837cde372c359b1ce5070096d472e0">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a> (TextStream &amp;outputStream, const DirDef *const directory, const DotDirProperty &amp;directoryProperty, DirDefMap &amp;directoriesInGraph, const bool isAncestor, int startLevel)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Writes DOT code for opening a cluster subgraph to stream. <a href="#a8c294bd8cf4c31b846744d5e5ca845fa">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ec4e307f44771f6dfa0a0fe76c00495">drawClusterClosing</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cae8568157c4b4b1c9a96af855d2b85">addDependencies</a> (DirRelations &amp;dependencies, const DirDef *const srcDir, bool isLeaf)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Assembles a list of the directory relations and whether or not they result from "inheritance". <a href="#a4cae8568157c4b4b1c9a96af855d2b85">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa598dce9105a7992d33b10a15beb70d5">drawTree</a> (DirRelations &amp;dependencies, TextStream &amp;t, const DirDef *const directory, int startLevel, DirDefMap &amp;directoriesInGraph, const bool isTreeRoot)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Recursively draws directory tree. <a href="#aa598dce9105a7992d33b10a15beb70d5">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4e7090b3ce2c42151afd6b83298096f">writeDotDirDepGraph</a> (TextStream &amp;t, const DirDef *dd, bool linkRelations)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Write DOT code for directory dependency graph. <a href="#ac4e7090b3ce2c42151afd6b83298096f">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Typedefs

### DirDefMap {#aa012bdc6c0e896cccb8121b3c6b7ad60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DirDefMap =  std::map&lt;std::string,const DirDef *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa012bdc6c0e896cccb8121b3c6b7ad60">34</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#aa012bdc6c0e896cccb8121b3c6b7ad60">DirDefMap</a> = std::map&lt;std::string,const DirDef *&gt;;</span></span></div>

</div>

</div>
</div>

### DirRelations {#a0540771f72e56700a0d30f72580d0065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef std::vector&lt; std::pair&lt; std::unique_ptr&lt;DirRelation&gt;, bool&gt; &gt; DirRelations</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Elements consist of (1) directory relation and (2) whether it is pointing only to inherited dependees.

Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0540771f72e56700a0d30f72580d0065">61</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> std::vector&lt; std::pair&lt; std::unique_ptr&lt;DirRelation&gt;, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">&gt; &gt; <a href="#a0540771f72e56700a0d30f72580d0065">DirRelations</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### addDependencies() {#a4cae8568157c4b4b1c9a96af855d2b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addDependencies (<a href="#a0540771f72e56700a0d30f72580d0065">DirRelations</a> &amp; dependencies, const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *const srcDir, bool isLeaf)</td>
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

Assembles a list of the directory relations and whether or not they result from "inheritance".


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">dependencies</td>
<td class="doxyParamItemDescription">Array to add the dependencies to.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">srcDir</td>
<td class="doxyParamItemDescription">is the source of the dependency.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">isLeaf</td>
<td class="doxyParamItemDescription">true, if no children are drawn for this directory.</td>
</tr>
</table>
</dd>
</dl>

Definition at line 215 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4cae8568157c4b4b1c9a96af855d2b85">215</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4cae8568157c4b4b1c9a96af855d2b85">addDependencies</a>(<a href="#a0540771f72e56700a0d30f72580d0065">DirRelations</a> &amp;dependencies,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> srcDir, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isLeaf)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;usedDirectory : srcDir-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#acf2258b5d619e2eb34f09dd33d34de0f">usedDirs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> dstDir = usedDirectory-&gt;dir();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!dstDir-&gt;isParentOf(srcDir) &amp;&amp; (isLeaf || usedDirectory-&gt;hasDirectSrcDeps()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> relationName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">      relationName.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"dir_%06d_%06d"</span><span class="doxyHighlight">, srcDir-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#a5fa1d07e132f8bd8d7f2ee10e712e978">dirIndex</a>(), dstDir-&gt;dirIndex());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> directRelation = isLeaf ? usedDirectory-&gt;hasDirectDstDeps() : usedDirectory-&gt;hasDirectDeps();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">      dependencies.emplace_back(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">          std::make_unique&lt;DirRelation&gt;(relationName, srcDir, usedDirectory.get()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">          directRelation);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dirdef/#a5fa1d07e132f8bd8d7f2ee10e712e978">DirDef::dirIndex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a> and <a href="/web-doxygen/docs/api/classes/dirdef/#acf2258b5d619e2eb34f09dd33d34de0f">DirDef::usedDirs</a>.

Referenced by <a href="#aa598dce9105a7992d33b10a15beb70d5">drawTree</a>.
</div>
</div>

### common\_attributes() {#a120714f9fe392105dac20e1759dcb1d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream &amp; common_attributes (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *const dir, const <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> &amp; prop)</td>
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



Definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a120714f9fe392105dac20e1759dcb1d6">137</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;<a href="#a120714f9fe392105dac20e1759dcb1d6">common_attributes</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> dir, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> &amp;prop)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url = dir-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> t &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"style=\""</span><span class="doxyHighlight">   &lt;&lt; <a href="#a6aa3fa8ed5c1cb6cfe4a5f821d1c776f">getDirectoryBorderStyle</a>(prop) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\", "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"URL=\""</span><span class="doxyHighlight">     &lt;&lt; url &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\","</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"tooltip=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#a1833cf88609789ddbebeeb77747e593f">escapeTooltip</a>(dir-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">Definition::briefDescriptionAsTooltip</a>, <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#a1833cf88609789ddbebeeb77747e593f">escapeTooltip</a>, <a href="#a6aa3fa8ed5c1cb6cfe4a5f821d1c776f">getDirectoryBorderStyle</a> and <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>.

Referenced by <a href="#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a> and <a href="#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a>.
</div>
</div>

### drawClusterClosing() {#a3ec4e307f44771f6dfa0a0fe76c00495}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void drawClusterClosing (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



Definition at line 204 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3ec4e307f44771f6dfa0a0fe76c00495">204</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3ec4e307f44771f6dfa0a0fe76c00495">drawClusterClosing</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  }\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="#aa598dce9105a7992d33b10a15beb70d5">drawTree</a>.
</div>
</div>

### drawClusterOpening() {#a8c294bd8cf4c31b846744d5e5ca845fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void drawClusterOpening (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; outputStream, const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *const directory, const <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> &amp; directoryProperty, <a href="#aa012bdc6c0e896cccb8121b3c6b7ad60">DirDefMap</a> &amp; directoriesInGraph, const bool isAncestor, int startLevel)</td>
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

Writes DOT code for opening a cluster subgraph to stream.


Ancestor clusters directly get a label. Other clusters get a plain text node with a label instead. This is because the plain text node can be used to draw dependency relationships.

Definition at line 179 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c294bd8cf4c31b846744d5e5ca845fa">179</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;outputStream, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> directory,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> &amp;directoryProperty, <a href="#aa012bdc6c0e896cccb8121b3c6b7ad60">DirDefMap</a> &amp;directoriesInGraph, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isAncestor,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">  outputStream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  subgraph cluster"</span><span class="doxyHighlight"> &lt;&lt; directory-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"    graph [ "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"bgcolor=\""</span><span class="doxyHighlight">  &lt;&lt; <a href="#a683792f7f7df231861acd54ff905211d">getDirectoryBackgroundColor</a>(directory-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#a033ad6b8c0287ed15da29dadca48eb6f">level</a>()-startLevel) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\", "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"pencolor=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="#aed9febe225f49a478f1ac4ab8c92786d">getDirectoryBorderColor</a>(directoryProperty) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\", "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"label=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isAncestor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">    outputStream &lt;&lt; <a href="/web-doxygen/docs/api/classes/dotnode/#a6bc845933b52f07e32502d844a9b2794">DotNode::convertLabel</a>(directory-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#aa198c67f6d58fdae57c8502913ed35d7">shortName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  outputStream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\", "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">       &lt;&lt; <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOT_COMMON_ATTR) &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a120714f9fe392105dac20e1759dcb1d6">common_attributes</a>(outputStream, directory, directoryProperty)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isAncestor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    outputStream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    "</span><span class="doxyHighlight"> &lt;&lt; directory-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" [shape=plaintext, "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"label=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/dotnode/#a6bc845933b52f07e32502d844a9b2794">DotNode::convertLabel</a>(directory-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#aa198c67f6d58fdae57c8502913ed35d7">shortName</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">    directoriesInGraph.emplace(directory-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(), directory);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a120714f9fe392105dac20e1759dcb1d6">common\_attributes</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config\_getString</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a6bc845933b52f07e32502d844a9b2794">DotNode::convertLabel</a>, <a href="#a683792f7f7df231861acd54ff905211d">getDirectoryBackgroundColor</a>, <a href="#aed9febe225f49a478f1ac4ab8c92786d">getDirectoryBorderColor</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/dirdef/#a033ad6b8c0287ed15da29dadca48eb6f">DirDef::level</a>, <a href="/web-doxygen/docs/api/classes/dirdef/#aa198c67f6d58fdae57c8502913ed35d7">DirDef::shortName</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="#aa598dce9105a7992d33b10a15beb70d5">drawTree</a> and <a href="#ac4e7090b3ce2c42151afd6b83298096f">writeDotDirDepGraph</a>.
</div>
</div>

### drawDirectory() {#a840611db0f9ff308b7167b3fd3e0c4d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void drawDirectory (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *const directory, const <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> &amp; property, <a href="#aa012bdc6c0e896cccb8121b3c6b7ad60">DirDefMap</a> &amp; directoriesInGraph, int startLevel)</td>
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

Puts DOT code for drawing directory to stream and adds it to the list.


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] t</td>
<td class="doxyParamItemDescription">stream to which the DOT code is written to</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] directory</td>
<td class="doxyParamItemDescription">will be mapped to a node in DOT code</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] property</td>
<td class="doxyParamItemDescription">are evaluated for formatting</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] directoriesInGraph</td>
<td class="doxyParamItemDescription">lists the directories which have been written to the output stream</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] startLevel</td>
<td class="doxyParamItemDescription">current level to calculate relative distances from to determine the background color</td>
</tr>
</table>
</dd>
</dl>

Definition at line 155 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a840611db0f9ff308b7167b3fd3e0c4d2">155</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> directory, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> &amp;property,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa012bdc6c0e896cccb8121b3c6b7ad60">DirDefMap</a> &amp;directoriesInGraph,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight"> &lt;&lt; directory-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">" ["</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"label=\""</span><span class="doxyHighlight">     &lt;&lt; <a href="/web-doxygen/docs/api/classes/dotnode/#a6bc845933b52f07e32502d844a9b2794">DotNode::convertLabel</a>(directory-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#aa198c67f6d58fdae57c8502913ed35d7">shortName</a>())                &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\", "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"fillcolor=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="#a683792f7f7df231861acd54ff905211d">getDirectoryBackgroundColor</a>(directory-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#a033ad6b8c0287ed15da29dadca48eb6f">level</a>()-startLevel)   &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\", "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"color=\""</span><span class="doxyHighlight">     &lt;&lt; <a href="#aed9febe225f49a478f1ac4ab8c92786d">getDirectoryBorderColor</a>(property)                            &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a120714f9fe392105dac20e1759dcb1d6">common_attributes</a>(t, directory, property)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; </span><span class="doxyHighlightStringLiteral">"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  directoriesInGraph.emplace(directory-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(), directory);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a120714f9fe392105dac20e1759dcb1d6">common\_attributes</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a6bc845933b52f07e32502d844a9b2794">DotNode::convertLabel</a>, <a href="#a683792f7f7df231861acd54ff905211d">getDirectoryBackgroundColor</a>, <a href="#aed9febe225f49a478f1ac4ab8c92786d">getDirectoryBorderColor</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/dirdef/#a033ad6b8c0287ed15da29dadca48eb6f">DirDef::level</a>, <a href="/web-doxygen/docs/api/classes/dirdef/#aa198c67f6d58fdae57c8502913ed35d7">DirDef::shortName</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="#aa598dce9105a7992d33b10a15beb70d5">drawTree</a>.
</div>
</div>

### drawTree() {#aa598dce9105a7992d33b10a15beb70d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void drawTree (<a href="#a0540771f72e56700a0d30f72580d0065">DirRelations</a> &amp; dependencies, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *const directory, int startLevel, <a href="#aa012bdc6c0e896cccb8121b3c6b7ad60">DirDefMap</a> &amp; directoriesInGraph, const bool isTreeRoot)</td>
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

Recursively draws directory tree.

Definition at line 233 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa598dce9105a7992d33b10a15beb70d5">233</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa598dce9105a7992d33b10a15beb70d5">drawTree</a>(<a href="#a0540771f72e56700a0d30f72580d0065">DirRelations</a> &amp;dependencies, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> directory,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLevel, <a href="#aa012bdc6c0e896cccb8121b3c6b7ad60">DirDefMap</a> &amp;directoriesInGraph, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isTreeRoot)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!directory-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#afa5aedb69f8e651bb29d872f2f143a8d">hasSubdirs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> directoryProperty = <a href="/web-doxygen/docs/api/classes/dotdirpropertybuilder">DotDirPropertyBuilder</a>().<a href="/web-doxygen/docs/api/classes/dotdirpropertybuilder/#a20342858b48a1b0233393928ffc85b57">makeOriginal</a>(isTreeRoot);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a>(t, directory, directoryProperty, directoriesInGraph,startLevel);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4cae8568157c4b4b1c9a96af855d2b85">addDependencies</a>(dependencies, directory, </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a20837cde372c359b1ce5070096d472e0">isAtMaxDepth</a>(directory, startLevel)) </span><span class="doxyHighlightComment">// maximum nesting level reached</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> directoryProperty = <a href="/web-doxygen/docs/api/classes/dotdirpropertybuilder">DotDirPropertyBuilder</a>().<a href="/web-doxygen/docs/api/classes/dotdirpropertybuilder/#a20342858b48a1b0233393928ffc85b57">makeOriginal</a>(isTreeRoot);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a>(t, directory, directoryProperty, directoriesInGraph,startLevel);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4cae8568157c4b4b1c9a96af855d2b85">addDependencies</a>(dependencies, directory, </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// start a new nesting level</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// open cluster</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> directoryProperty = <a href="/web-doxygen/docs/api/classes/dotdirpropertybuilder">DotDirPropertyBuilder</a>().<a href="/web-doxygen/docs/api/classes/dotdirpropertybuilder/#a20342858b48a1b0233393928ffc85b57">makeOriginal</a>(isTreeRoot);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a>(t, directory, directoryProperty, directoriesInGraph, </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">, startLevel);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4cae8568157c4b4b1c9a96af855d2b85">addDependencies</a>(dependencies, directory, </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// process all sub directories</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> subDirectory : directory-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#abc75cce4fc67690a3ebbd158e3d63938">subDirs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa598dce9105a7992d33b10a15beb70d5">drawTree</a>(dependencies, t, subDirectory, startLevel, directoriesInGraph, </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// close cluster</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a3ec4e307f44771f6dfa0a0fe76c00495">drawClusterClosing</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a4cae8568157c4b4b1c9a96af855d2b85">addDependencies</a>, <a href="#a3ec4e307f44771f6dfa0a0fe76c00495">drawClusterClosing</a>, <a href="#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a>, <a href="#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a>, <a href="#aa598dce9105a7992d33b10a15beb70d5">drawTree</a>, <a href="/web-doxygen/docs/api/classes/dirdef/#afa5aedb69f8e651bb29d872f2f143a8d">DirDef::hasSubdirs</a>, <a href="#a20837cde372c359b1ce5070096d472e0">isAtMaxDepth</a>, <a href="/web-doxygen/docs/api/classes/dotdirpropertybuilder/#a20342858b48a1b0233393928ffc85b57">DotDirPropertyBuilder::makeOriginal</a> and <a href="/web-doxygen/docs/api/classes/dirdef/#abc75cce4fc67690a3ebbd158e3d63938">DirDef::subDirs</a>.

Referenced by <a href="#aa598dce9105a7992d33b10a15beb70d5">drawTree</a>.
</div>
</div>

### getDirectoryBackgroundColor() {#a683792f7f7df231861acd54ff905211d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString getDirectoryBackgroundColor (int depthIndex)</td>
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

Returns a DOT color name according to the directory depth.

Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a683792f7f7df231861acd54ff905211d">64</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a683792f7f7df231861acd54ff905211d">getDirectoryBackgroundColor</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> depthIndex)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> hue   = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(HTML_COLORSTYLE_HUE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> sat   = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(HTML_COLORSTYLE_SAT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> gamma = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(HTML_COLORSTYLE_GAMMA);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(depthIndex&gt;=0 &amp;&amp; depthIndex&lt;=<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(DIR_GRAPH_MAX_DEPTH));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlight"> fraction = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(depthIndex)/</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(DIR_GRAPH_MAX_DEPTH));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[] = </span><span class="doxyHighlightStringLiteral">"0123456789abcdef"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> range = 0x40; </span><span class="doxyHighlightComment">// range from darkest color to lightest color</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> luma   = 0xef-</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(fraction*</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(range)); </span><span class="doxyHighlightComment">// interpolation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> r=0, g=0, b=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/coloredimage/#aa28cffecb75cf52b6b457178851704c5">ColoredImage::hsl2rgb</a>(hue/360.0,sat/255.0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">                        pow(luma/255.0,gamma/100.0),&amp;r,&amp;g,&amp;b);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> red   = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(r*255.0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> green = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(g*255.0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> blue  = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(b*255.0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(red&gt;=0   &amp;&amp; red&lt;=255);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(green&gt;=0 &amp;&amp; green&lt;=255);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(blue&gt;=0  &amp;&amp; blue&lt;=255);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> colStr[8];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  colStr[0]=</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  colStr[1]=<a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[red&gt;&gt;4];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  colStr[2]=<a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[red&amp;0xf];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  colStr[3]=<a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[green&gt;&gt;4];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  colStr[4]=<a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[green&amp;0xf];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  colStr[5]=<a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[blue&gt;&gt;4];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  colStr[6]=<a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[blue&amp;0xf];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  colStr[7]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("i=%d max=%d fraction=%f luma=%d %02x %02x %02x -&gt; color=%s\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    depthIndex,Config_getInt(DIR_GRAPH_MAX_DEPTH),fraction,luma,red,green,blue,colStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> colStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config\_getInt</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a> and <a href="/web-doxygen/docs/api/classes/coloredimage/#aa28cffecb75cf52b6b457178851704c5">ColoredImage::hsl2rgb</a>.

Referenced by <a href="#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a> and <a href="#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a>.
</div>
</div>

### getDirectoryBorderColor() {#aed9febe225f49a478f1ac4ab8c92786d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getDirectoryBorderColor (const <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> &amp; property)</td>
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

Returns a DOT color name according to the directory properties.

Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed9febe225f49a478f1ac4ab8c92786d">98</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* <a href="#aed9febe225f49a478f1ac4ab8c92786d">getDirectoryBorderColor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> &amp;property)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (property.<a href="/web-doxygen/docs/api/structs/dotdirproperty/#a13d7c0ae8df6a6a0d7d1298ce5b2fbd5">isTruncated</a> &amp;&amp; property.<a href="/web-doxygen/docs/api/structs/dotdirproperty/#a725a202c71456e1caf086cdd20a9baf9">isOrphaned</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"red"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (property.<a href="/web-doxygen/docs/api/structs/dotdirproperty/#a13d7c0ae8df6a6a0d7d1298ce5b2fbd5">isTruncated</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"red"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (property.<a href="/web-doxygen/docs/api/structs/dotdirproperty/#a725a202c71456e1caf086cdd20a9baf9">isOrphaned</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"grey50"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"grey25"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/dotdirproperty/#a725a202c71456e1caf086cdd20a9baf9">DotDirProperty::isOrphaned</a> and <a href="/web-doxygen/docs/api/structs/dotdirproperty/#a13d7c0ae8df6a6a0d7d1298ce5b2fbd5">DotDirProperty::isTruncated</a>.

Referenced by <a href="#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a> and <a href="#a840611db0f9ff308b7167b3fd3e0c4d2">drawDirectory</a>.
</div>
</div>

### getDirectoryBorderStyle() {#a6aa3fa8ed5c1cb6cfe4a5f821d1c776f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string getDirectoryBorderStyle (const <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> &amp; property)</td>
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

Returns a DOT node style according to the directory properties.

Definition at line 119 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6aa3fa8ed5c1cb6cfe4a5f821d1c776f">119</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::string <a href="#a6aa3fa8ed5c1cb6cfe4a5f821d1c776f">getDirectoryBorderStyle</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> &amp;property)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string style = </span><span class="doxyHighlightStringLiteral">"filled"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (property.<a href="/web-doxygen/docs/api/structs/dotdirproperty/#ac8ed0c0d9a9e5638b80ba4d96b1f7b7b">isOriginal</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    style += </span><span class="doxyHighlightStringLiteral">",bold"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (property.<a href="/web-doxygen/docs/api/structs/dotdirproperty/#afa37640375733ea38413a589b3f90718">isIncomplete</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">    style += </span><span class="doxyHighlightStringLiteral">",dashed"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (property.<a href="/web-doxygen/docs/api/structs/dotdirproperty/#a13d7c0ae8df6a6a0d7d1298ce5b2fbd5">isTruncated</a> &amp;&amp; property.<a href="/web-doxygen/docs/api/structs/dotdirproperty/#a725a202c71456e1caf086cdd20a9baf9">isOrphaned</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">    style += </span><span class="doxyHighlightStringLiteral">",dashed"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> style;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/dotdirproperty/#afa37640375733ea38413a589b3f90718">DotDirProperty::isIncomplete</a>, <a href="/web-doxygen/docs/api/structs/dotdirproperty/#ac8ed0c0d9a9e5638b80ba4d96b1f7b7b">DotDirProperty::isOriginal</a>, <a href="/web-doxygen/docs/api/structs/dotdirproperty/#a725a202c71456e1caf086cdd20a9baf9">DotDirProperty::isOrphaned</a> and <a href="/web-doxygen/docs/api/structs/dotdirproperty/#a13d7c0ae8df6a6a0d7d1298ce5b2fbd5">DotDirProperty::isTruncated</a>.

Referenced by <a href="#a120714f9fe392105dac20e1759dcb1d6">common\_attributes</a>.
</div>
</div>

### isAtMaxDepth() {#a20837cde372c359b1ce5070096d472e0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAtMaxDepth (const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *const directory, const int startLevel)</td>
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

Checks, if the directory is a the maximum drawn directory level.

Definition at line 168 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a20837cde372c359b1ce5070096d472e0">168</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a20837cde372c359b1ce5070096d472e0">isAtMaxDepth</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> directory, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (directory-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#a033ad6b8c0287ed15da29dadca48eb6f">level</a>() - startLevel) &gt;= <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(DIR_GRAPH_MAX_DEPTH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config\_getInt</a> and <a href="/web-doxygen/docs/api/classes/dirdef/#a033ad6b8c0287ed15da29dadca48eb6f">DirDef::level</a>.

Referenced by <a href="#aa598dce9105a7992d33b10a15beb70d5">drawTree</a>.
</div>
</div>

### writeDotDirDepGraph() {#ac4e7090b3ce2c42151afd6b83298096f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDotDirDepGraph (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> * dd, bool linkRelations)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Write DOT code for directory dependency graph.


Code is generated for a directory. Successors (sub-directories) of this directory are recursively drawn. Recursion is limited by <code>DIR\_GRAPH\_MAX\_DEPTH</code>. The dependencies of those directories are drawn.

If a dependee is not part of directory tree above, then the dependency is drawn to the first parent of the dependee, whose parent is an ancestor (sub-directory) of the original directory.

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">t</td>
<td class="doxyParamItemDescription">stream where the DOT code is written to</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">dd</td>
<td class="doxyParamItemDescription">directory for which the graph is generated for</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">linkRelations</td>
<td class="doxyParamItemDescription">if true, hyperlinks to the list of file dependencies are added</td>
</tr>
</table>
</dd>
</dl>

Definition at line 287 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac4e7090b3ce2c42151afd6b83298096f">287</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac4e7090b3ce2c42151afd6b83298096f">writeDotDirDepGraph</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *dd,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> linkRelations)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa012bdc6c0e896cccb8121b3c6b7ad60">DirDefMap</a> dirsInGraph;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">  dirsInGraph.emplace(dd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),dd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">  std::vector&lt;const DirDef *&gt; usedDirsNotDrawn, usedDirsDrawn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight">&amp; usedDir : dd-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#acf2258b5d619e2eb34f09dd33d34de0f">usedDirs</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">    usedDirsNotDrawn.push_back(usedDir-&gt;dir());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> moveDrawnDirs = [&amp;usedDirsDrawn,&amp;usedDirsNotDrawn](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::vector&lt;const DirDef *&gt;::iterator &amp;newEnd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// usedDirsNotDrawn is split into two segments: [begin()....newEnd-1] and [newEnd....end()]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// where the second segment starting at newEnd has been drawn, so append this segment to the usedDirsDrawn list and</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// remove it from the usedDirsNotDrawn list.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">    std::move(newEnd, std::end(usedDirsNotDrawn), std::back_inserter(usedDirsDrawn));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">    usedDirsNotDrawn.erase(newEnd, usedDirsNotDrawn.end());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if dd has a parent draw it as the outer layer</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a> = dd-&gt;<a href="/web-doxygen/docs/api/classes/dirdef/#a6ddd6f5e08f9a04cc43cf15e388bc2af">parent</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotdirproperty">DotDirProperty</a> parentDirProperty = <a href="/web-doxygen/docs/api/classes/dotdirpropertybuilder">DotDirPropertyBuilder</a>().</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">                                             makeIncomplete().</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">                                             makeOrphaned(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>-&gt;parent()!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a>(t, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, parentDirProperty, dirsInGraph, </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>-&gt;level());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// draw all directories which have `dd-&gt;parent()` as parent and `dd` as dependent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> newEnd = std::stable_partition(usedDirsNotDrawn.begin(), usedDirsNotDrawn.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">        [&amp;](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> usedDir)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">          if (dd!=usedDir &amp;&amp; dd-&gt;parent()==usedDir-&gt;parent()) </span><span class="doxyHighlightComment">// usedDir and dd share the same parent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">            const DotDirProperty usedDirProperty = DotDirPropertyBuilder().makeTruncated(usedDir-&gt;hasSubdirs());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">            drawDirectory(t, usedDir, usedDirProperty, dirsInGraph, parent-&gt;level());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">            return false; </span><span class="doxyHighlightComment">// part of the drawn partition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// part of the not-drawn partition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">        });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">      moveDrawnDirs(newEnd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// draw the directory tree with dd as root</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0540771f72e56700a0d30f72580d0065">DirRelations</a> dependencies;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa598dce9105a7992d33b10a15beb70d5">drawTree</a>(dependencies, t, dd, dd-&gt;level(), dirsInGraph, </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3ec4e307f44771f6dfa0a0fe76c00495">drawClusterClosing</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// add nodes for other used directories (i.e. outside of the cluster of directories directly connected to dd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> newEnd = std::stable_partition(usedDirsNotDrawn.begin(), usedDirsNotDrawn.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">     [&amp;](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> usedDir) </span><span class="doxyHighlightComment">// for each used dir (=directly used or a parent of a directly used dir)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">       const DirDef *dir=dd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">       while (dir)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">         if (dir!=usedDir &amp;&amp; dir-&gt;parent()==usedDir-&gt;parent()) </span><span class="doxyHighlightComment">// include if both have the same parent (or no parent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">           const DotDirProperty usedDirProperty = DotDirPropertyBuilder().</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  makeOrphaned(usedDir-&gt;parent()!=nullptr).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  makeTruncated(usedDir-&gt;hasSubdirs()).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">                                                  makePeripheral();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">           drawDirectory(t, usedDir, usedDirProperty, dirsInGraph, dir-&gt;level());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">           return false; </span><span class="doxyHighlightComment">// part of the drawn partition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">         dir=dir-&gt;parent();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// part of the not-drawn partition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">     });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">    moveDrawnDirs(newEnd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// add relations between all selected directories</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;relationPair : dependencies)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;relation         = relationPair.first;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> directRelation    = relationPair.second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> udir              = relation-&gt;destination();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> usedDir           = udir-&gt;dir();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> destIsSibling     = std::find(std::begin(usedDirsDrawn), std::end(usedDirsDrawn), usedDir) != std::end(usedDirsDrawn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> destIsDrawn       = dirsInGraph.find(usedDir-&gt;getOutputFileBase().str())!=dirsInGraph.end(); </span><span class="doxyHighlightComment">// only point to nodes that are in the graph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> atMaxDepth        = <a href="#a20837cde372c359b1ce5070096d472e0">isAtMaxDepth</a>(usedDir, dd-&gt;level());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (destIsSibling || (destIsDrawn &amp;&amp; (directRelation || atMaxDepth)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> relationName = relation-&gt;getOutputFileBase();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> dir = relation-&gt;source();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/doxygen/#aeb009dfd4eca1e806843a68765b975db">Doxygen::dirRelations</a>.add(relationName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">            std::make_unique&lt;DirRelation&gt;(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">               relationName,dir,udir));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> nrefs = udir-&gt;filePairs().size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight"> &lt;&lt; dir-&gt;getOutputFileBase() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-&gt;"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">          &lt;&lt; usedDir-&gt;getOutputFileBase();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" [headlabel=\""</span><span class="doxyHighlight"> &lt;&lt; nrefs &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\", labeldistance=1.5"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (linkRelations)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = relationName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" headhref=\""</span><span class="doxyHighlight"> &lt;&lt; fn &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" href=\""</span><span class="doxyHighlight"> &lt;&lt; fn &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" color=\"steelblue1\" fontcolor=\"steelblue1\"];\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a8c294bd8cf4c31b846744d5e5ca845fa">drawClusterOpening</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/dirdef/#a6ddd6f5e08f9a04cc43cf15e388bc2af">DirDef::parent</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/classes/dirdef/#acf2258b5d619e2eb34f09dd33d34de0f">DirDef::usedDirs</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotdirdeps/#a8cb59745acc5f950c7fb14f28f4bfded">DotDirDeps::computeTheGraph</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
