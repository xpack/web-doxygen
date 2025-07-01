---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/dotfilepatcher
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DotFilePatcher` Class Reference

Helper class to insert a set of map file into an output file. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class DotFilePatcher { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">src/dotfilepatcher.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4993d9e9855116cd4fee5bd950c19bb8">DotFilePatcher</a> (const QCString &amp;patchFile)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa53ad66e5d0c6a04f6d198aa030b63f3">addMap</a> (const QCString &amp;mapFile, const QCString &amp;relPath, bool urlOnly, const QCString &amp;context, const QCString &amp;label)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af67aa4441f3e872f6d3c69667572c052">addFigure</a> (const QCString &amp;baseName, const QCString &amp;figureName, bool heightCheck)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac97171a3985fd07e09fef2a25819a16">addSVGConversion</a> (const QCString &amp;relPath, bool urlOnly, const QCString &amp;context, bool zoomable, int graphId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0183f93570ac3b1a8df3e0f7229a2b">addSVGObject</a> (const QCString &amp;baseName, const QCString &amp;figureName, const QCString &amp;relPath)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02cd92c7c61a35c61c601ff6b409c5e5">run</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36fcbf6fe68086f734c114a2d30c5516">isSVGFile</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map">Map</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28f0ce1e173d0f12f0a4425af69958a5">convertMapFile</a> (TextStream &amp;t, const QCString &amp;mapName, const QCString &amp;relPath, bool urlOnly=FALSE, const QCString &amp;context=QCString())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae41b4e8b1817e1d1de1732e4c4f9069c">writeSVGFigureLink</a> (TextStream &amp;out, const QCString &amp;relPath, const QCString &amp;baseName, const QCString &amp;absImgName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Check if a reference to a SVG figure can be written and do so if possible. <a href="#ae41b4e8b1817e1d1de1732e4c4f9069c">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e56aa086c8135c76d84de764845c20e">writeVecGfxFigure</a> (TextStream &amp;out, const QCString &amp;baseName, const QCString &amp;figureName)</td>
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

Helper class to insert a set of map file into an output file.

Definition at line 26 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>.

<div class="doxySectionDef">

## Public Constructors

### DotFilePatcher() {#a4993d9e9855116cd4fee5bd950c19bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DotFilePatcher::DotFilePatcher (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; patchFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 29 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>, definition at line 262 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp">dotfilepatcher.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4993d9e9855116cd4fee5bd950c19bb8">262</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a4993d9e9855116cd4fee5bd950c19bb8">DotFilePatcher::DotFilePatcher</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;patchFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>(patchFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m\_patchFile</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFigure() {#af67aa4441f3e872f6d3c69667572c052}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotFilePatcher::addFigure (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; baseName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; figureName, bool heightCheck)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>, definition at line 280 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp">dotfilepatcher.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af67aa4441f3e872f6d3c69667572c052">280</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#af67aa4441f3e872f6d3c69667572c052">DotFilePatcher::addFigure</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;figureName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> heightCheck)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.emplace_back(figureName,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,heightCheck,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m\_maps</a>.
</div>
</div>

### addMap() {#aa53ad66e5d0c6a04f6d198aa030b63f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotFilePatcher::addMap (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; mapFile, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, bool urlOnly, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; context, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; label)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 30 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>, definition at line 272 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp">dotfilepatcher.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa53ad66e5d0c6a04f6d198aa030b63f3">272</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aa53ad66e5d0c6a04f6d198aa030b63f3">DotFilePatcher::addMap</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;mapFile,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> urlOnly,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;context,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;label)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.emplace_back(mapFile,relPath,urlOnly,context,label);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m\_maps</a>.
</div>
</div>

### addSVGConversion() {#aac97171a3985fd07e09fef2a25819a16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotFilePatcher::addSVGConversion (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, bool urlOnly, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; context, bool zoomable, int graphId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 36 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>, definition at line 288 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp">dotfilepatcher.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac97171a3985fd07e09fef2a25819a16">288</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aac97171a3985fd07e09fef2a25819a16">DotFilePatcher::addSVGConversion</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> urlOnly,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;context,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> zoomable,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> graphId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.emplace_back(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,relPath,urlOnly,context,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,zoomable,graphId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m\_maps</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/dot-cpp/#ada988a5303d67622cb43bd75c247fec2">writeDotImageMapFromFile</a>.
</div>
</div>

### addSVGObject() {#a8a0183f93570ac3b1a8df3e0f7229a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DotFilePatcher::addSVGObject (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; baseName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; figureName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 39 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>, definition at line 297 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp">dotfilepatcher.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8a0183f93570ac3b1a8df3e0f7229a2b">297</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a8a0183f93570ac3b1a8df3e0f7229a2b">DotFilePatcher::addSVGObject</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;absImgName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.emplace_back(absImgName,relPath,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,baseName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m\_maps</a>.
</div>
</div>

### isSVGFile() {#a36fcbf6fe68086f734c114a2d30c5516}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotFilePatcher::isSVGFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 42 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>, definition at line 267 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp">dotfilepatcher.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a36fcbf6fe68086f734c114a2d30c5516">267</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a36fcbf6fe68086f734c114a2d30c5516">DotFilePatcher::isSVGFile</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>.endsWith(</span><span class="doxyHighlightStringLiteral">".svg"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m\_patchFile</a>.

Referenced by <a href="#a02cd92c7c61a35c61c601ff6b409c5e5">run</a>.
</div>
</div>

### run() {#a02cd92c7c61a35c61c601ff6b409c5e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotFilePatcher::run ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 41 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>, definition at line 306 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp">dotfilepatcher.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02cd92c7c61a35c61c601ff6b409c5e5">306</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("DotFilePatcher::run(): %s\n",qPrint(m_patchFile));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> interactiveSVG = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(INTERACTIVE_SVG);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a36fcbf6fe68086f734c114a2d30c5516">isSVGFile</a> = <a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>.endsWith(</span><span class="doxyHighlightStringLiteral">".svg"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> graphId = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> relPath;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a36fcbf6fe68086f734c114a2d30c5516">isSVGFile</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map">Map</a> &amp;map = <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.front(); </span><span class="doxyHighlightComment">// there is only one 'map' for a SVG file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">    interactiveSVG = interactiveSVG &amp;&amp; map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a8e657340f36c6d423a2c0d1e417b3407">zoomable</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">    graphId = map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a1bf5d3f2543719b345339e1ec307f24e">graphId</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">    relPath = map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a1039cf6923ea60a919d092990d86bb07">relPath</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("DotFilePatcher::addSVGConversion: file=%s zoomable=%d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    qPrint(m_patchFile),map-&gt;zoomable);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmpName = <a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>+</span><span class="doxyHighlightStringLiteral">".tmp"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> thisDir;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!thisDir.<a href="/web-doxygen/docs/api/classes/dir/#ab14881c67dae32902aa709517177e5ce">rename</a>(<a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>.str(),tmpName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Failed to rename file {} to {}!\n"</span><span class="doxyHighlight">,<a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>,tmpName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ifstream fi = <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>(tmpName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream fo = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(<a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fi.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"problem opening file {} for patching!\n"</span><span class="doxyHighlight">,tmpName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">    thisDir.<a href="/web-doxygen/docs/api/classes/dir/#ab14881c67dae32902aa709517177e5ce">rename</a>(tmpName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fo.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"problem opening file {} for patching!\n"</span><span class="doxyHighlight">,<a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">    thisDir.<a href="/web-doxygen/docs/api/classes/dir/#ab14881c67dae32902aa709517177e5ce">rename</a>(tmpName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;fo);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> width=0,height=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideHeader=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> replacedHeader=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> useNagivation=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string lineStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> reSVG(R</span><span class="doxyHighlightStringLiteral">"([\[&lt;]!-- SVG [0-9]+)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> reMAP(R</span><span class="doxyHighlightStringLiteral">"(&lt;!-- MAP [0-9]+)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> reFIG(R</span><span class="doxyHighlightStringLiteral">"(% FIG [0-9]+)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (getline(fi,lineStr))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> line = lineStr+</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("line=[%s]\n",qPrint(line.stripWhiteSpace()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a36fcbf6fe68086f734c114a2d30c5516">isSVGFile</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (interactiveSVG)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (line.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"&lt;svg"</span><span class="doxyHighlight">)!=-1 &amp;&amp; !replacedHeader)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count = sscanf(line.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),</span><span class="doxyHighlightStringLiteral">"&lt;svg width=\"%dpt\" height=\"%dpt\""</span><span class="doxyHighlight">,&amp;width,&amp;height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count != 2) count = sscanf(line.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),</span><span class="doxyHighlightStringLiteral">"&lt;svg xmlns=\"http://www.w3.org/2000/svg\" xmlns:xlink=\"http://www.w3.org/1999/xlink\" width=\"%d\" height=\"%d\""</span><span class="doxyHighlight">,&amp;width,&amp;height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("width=%d height=%d\n",width,height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">          useNagivation = count==2 &amp;&amp; (width&gt;500 || height&gt;450);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">          insideHeader = count==2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (insideHeader &amp;&amp; !replacedHeader &amp;&amp; line.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"&lt;g id=\"graph"</span><span class="doxyHighlight">)!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useNagivation)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// insert special replacement header for interactive SVGs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!--zoomable "</span><span class="doxyHighlight"> &lt;&lt; height &lt;&lt; </span><span class="doxyHighlightStringLiteral">" --&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#abcdd4ae5d4cb0d1827d8340d7a178a2c">svgZoomHeader0</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a83a06206861ee463b6db5e4e746be795">svgZoomHeader0_noinit</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a44fb192166e5d8a2221d974be2c46b8b">svgZoomHeader1</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useNagivation)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a606bbb50bfa79fc3d6da01a37bde1ea0">svgZoomHeader2</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useNagivation)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"application/ecmascript\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"var viewWidth = "</span><span class="doxyHighlight"> &lt;&lt; width &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"var viewHeight = "</span><span class="doxyHighlight"> &lt;&lt; height &lt;&lt; </span><span class="doxyHighlightStringLiteral">";\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (graphId&gt;=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"var sectionId = 'dynsection-"</span><span class="doxyHighlight"> &lt;&lt; graphId &lt;&lt; </span><span class="doxyHighlightStringLiteral">"';\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/script&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;script type=\"application/ecmascript\" xlink:href=\""</span><span class="doxyHighlight"> &lt;&lt; relPath &lt;&lt; </span><span class="doxyHighlightStringLiteral">"svg.min.js\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;svg id=\"graph\" class=\"graph\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useNagivation)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;g id=\"viewport\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">          line=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">          insideHeader=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">          replacedHeader=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideHeader || !useNagivation) </span><span class="doxyHighlightComment">// copy SVG and replace refs,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightComment">// unless we are inside the header of the SVG.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">                                       </span><span class="doxyHighlightComment">// Then we replace it with another header.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map">Map</a> &amp;map = <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.front(); </span><span class="doxyHighlightComment">// there is only one 'map' for a SVG file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>(line,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a1039cf6923ea60a919d092990d86bb07">relPath</a>,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a4e0032ccbfd53bb27adc4d0252da9a6f">urlOnly</a>,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#acd850ca81fb232e7b253746937702e66">context</a>,</span><span class="doxyHighlightStringLiteral">"_top"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (line.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"SVG"</span><span class="doxyHighlight">)!=-1 &amp;&amp; (i=<a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>(line.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),reSVG))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Found marker at %d\n",i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> mapId=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; line.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n = sscanf(line.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+i+1,</span><span class="doxyHighlightStringLiteral">"!-- SVG %d"</span><span class="doxyHighlight">,&amp;mapId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n==1 &amp;&amp; mapId&gt;=0 &amp;&amp; mapId&lt;</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.size()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> e = std::max(line.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"--]"</span><span class="doxyHighlight">),line.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"--&gt;"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map">Map</a> &amp;map = <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.at(mapId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("DotFilePatcher::writeSVGFigure: file=%s zoomable=%d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//  qPrint(m_patchFile),map.zoomable);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ae41b4e8b1817e1d1de1732e4c4f9069c">writeSVGFigureLink</a>(t,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a1039cf6923ea60a919d092990d86bb07">relPath</a>,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a7aa1ae8828fec8377ddf808132a52f24">label</a>,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#aec1d56210a55b5bae168f4492d786b6a">mapFile</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Problem extracting size from SVG file {}\n"</span><span class="doxyHighlight">,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#aec1d56210a55b5bae168f4492d786b6a">mapFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e!=-1) t &lt;&lt; line.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(e+3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// error invalid map id!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Found invalid SVG id in file {}!\n"</span><span class="doxyHighlight">,<a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; line.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (line.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"MAP"</span><span class="doxyHighlight">)!=-1 &amp;&amp; (i=<a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>(line.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),reMAP))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> mapId=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; line.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n = sscanf(line.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+i,</span><span class="doxyHighlightStringLiteral">"&lt;!-- MAP %d"</span><span class="doxyHighlight">,&amp;mapId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n==1 &amp;&amp; mapId&gt;=0 &amp;&amp; mapId&lt;</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.size()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> tt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map">Map</a> &amp;map = <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.at(mapId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("patching MAP %d in file %s with contents of %s\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//   mapId,qPrint(m_patchFile),qPrint(map.mapFile));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a28f0ce1e173d0f12f0a4425af69958a5">convertMapFile</a>(tt,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#aec1d56210a55b5bae168f4492d786b6a">mapFile</a>,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a1039cf6923ea60a919d092990d86bb07">relPath</a>,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a4e0032ccbfd53bb27adc4d0252da9a6f">urlOnly</a>,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#acd850ca81fb232e7b253746937702e66">context</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tt.<a href="/web-doxygen/docs/api/classes/textstream/#a0859a9bfd6a7b6bafc7050d9f3aef046">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;map name=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa9203c86bf68f5df83a758b49fae64a1">correctId</a>(map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a7aa1ae8828fec8377ddf808132a52f24">label</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" id=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa9203c86bf68f5df83a758b49fae64a1">correctId</a>(map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a7aa1ae8828fec8377ddf808132a52f24">label</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; tt.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/map&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// error invalid map id!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Found invalid MAP id in file {}!\n"</span><span class="doxyHighlight">,<a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; line.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (line.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"FIG"</span><span class="doxyHighlight">)!=-1 &amp;&amp; (i=<a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>(line.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),reFIG))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> mapId=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n = sscanf(line.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+i+2,</span><span class="doxyHighlightStringLiteral">"FIG %d"</span><span class="doxyHighlight">,&amp;mapId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("line='%s' n=%d\n",qPrint(line)+i,n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n==1 &amp;&amp; mapId&gt;=0 &amp;&amp; mapId&lt;</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.size()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map">Map</a> &amp;map = <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.at(mapId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("patching FIG %d in file %s with contents of %s\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//   mapId,qPrint(m_patchFile),qPrint(map.mapFile));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a1e56aa086c8135c76d84de764845c20e">writeVecGfxFigure</a>(t,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a7aa1ae8828fec8377ddf808132a52f24">label</a>,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#aec1d56210a55b5bae168f4492d786b6a">mapFile</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"problem writing FIG {} figure!\n"</span><span class="doxyHighlight">,mapId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// error invalid map id!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Found invalid bounding FIG {} in file {}!\n"</span><span class="doxyHighlight">,mapId,<a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a36fcbf6fe68086f734c114a2d30c5516">isSVGFile</a> &amp;&amp; interactiveSVG &amp;&amp; !useNagivation) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/svg&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">  fi.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a36fcbf6fe68086f734c114a2d30c5516">isSVGFile</a> &amp;&amp; interactiveSVG &amp;&amp; replacedHeader)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> orgName=<a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>.left(<a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>.length()-4)+</span><span class="doxyHighlightStringLiteral">"_org.svg"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (useNagivation)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(<a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#ae0a0d97bc61404c8310be7b49030af25">svgZoomFooter1</a>,</span><span class="doxyHighlightStringLiteral">"$orgname"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(orgName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a8447cc3ca40e42b36b89aada700573b9">svgZoomFooter2</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">    t.<a href="/web-doxygen/docs/api/classes/textstream/#a907937b613a56aa4124608b3a092b820">flush</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">    fo.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// keep original SVG file so we can refer to it, we do need to replace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// dummy link by real ones</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">    fi = <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>(tmpName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">    fo = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(orgName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fi.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"problem opening file {} for reading!\n"</span><span class="doxyHighlight">,tmpName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fo.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"problem opening file {} for writing!\n"</span><span class="doxyHighlight">,orgName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">    t.<a href="/web-doxygen/docs/api/classes/textstream/#a18a4ee87242fc2b8e31941a71e622fd2">setStream</a>(&amp;fo);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (getline(fi,lineStr)) </span><span class="doxyHighlightComment">// foreach line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string line = lineStr+</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map">Map</a> &amp;map = <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>.front(); </span><span class="doxyHighlightComment">// there is only one 'map' for a SVG file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>(line.c_str(),map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a1039cf6923ea60a919d092990d86bb07">relPath</a>,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a4e0032ccbfd53bb27adc4d0252da9a6f">urlOnly</a>,map.<a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#acd850ca81fb232e7b253746937702e66">context</a>,</span><span class="doxyHighlightStringLiteral">"_top"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">    t.<a href="/web-doxygen/docs/api/classes/textstream/#a907937b613a56aa4124608b3a092b820">flush</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">    fi.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">    fo.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// remove temporary file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">  thisDir.<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(tmpName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#acd850ca81fb232e7b253746937702e66">DotFilePatcher::Map::context</a>, <a href="#a28f0ce1e173d0f12f0a4425af69958a5">convertMapFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa9203c86bf68f5df83a758b49fae64a1">correctId</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/textstream/#a0859a9bfd6a7b6bafc7050d9f3aef046">TextStream::empty</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa148f513c64eba8bfd7f3e775c711514">findIndex</a>, <a href="/web-doxygen/docs/api/classes/textstream/#a907937b613a56aa4124608b3a092b820">TextStream::flush</a>, <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a1bf5d3f2543719b345339e1ec307f24e">DotFilePatcher::Map::graphId</a>, <a href="#a36fcbf6fe68086f734c114a2d30c5516">isSVGFile</a>, <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a7aa1ae8828fec8377ddf808132a52f24">DotFilePatcher::Map::label</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m\_maps</a>, <a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m\_patchFile</a>, <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#aec1d56210a55b5bae168f4492d786b6a">DotFilePatcher::Map::mapFile</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a1039cf6923ea60a919d092990d86bb07">DotFilePatcher::Map::relPath</a>, <a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">Dir::remove</a>, <a href="/web-doxygen/docs/api/classes/dir/#ab14881c67dae32902aa709517177e5ce">Dir::rename</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>, <a href="/web-doxygen/docs/api/classes/textstream/#a18a4ee87242fc2b8e31941a71e622fd2">TextStream::setStream</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#ae0a0d97bc61404c8310be7b49030af25">svgZoomFooter1</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a8447cc3ca40e42b36b89aada700573b9">svgZoomFooter2</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#abcdd4ae5d4cb0d1827d8340d7a178a2c">svgZoomHeader0</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a83a06206861ee463b6db5e4e746be795">svgZoomHeader0\_noinit</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a44fb192166e5d8a2221d974be2c46b8b">svgZoomHeader1</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a606bbb50bfa79fc3d6da01a37bde1ea0">svgZoomHeader2</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a4e0032ccbfd53bb27adc4d0252da9a6f">DotFilePatcher::Map::urlOnly</a>, <a href="#ae41b4e8b1817e1d1de1732e4c4f9069c">writeSVGFigureLink</a>, <a href="#a1e56aa086c8135c76d84de764845c20e">writeVecGfxFigure</a> and <a href="/web-doxygen/docs/api/structs/dotfilepatcher/map/#a8e657340f36c6d423a2c0d1e417b3407">DotFilePatcher::Map::zoomable</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/dot-cpp/#ada988a5303d67622cb43bd75c247fec2">writeDotImageMapFromFile</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_maps {#a52738c3a25bf0b8a076ad4e0c301162a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Map&gt; DotFilePatcher::m_maps</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52738c3a25bf0b8a076ad4e0c301162a">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;Map&gt; <a href="#a52738c3a25bf0b8a076ad4e0c301162a">m_maps</a>;</span></span></div>

</div>


Referenced by <a href="#af67aa4441f3e872f6d3c69667572c052">addFigure</a>, <a href="#aa53ad66e5d0c6a04f6d198aa030b63f3">addMap</a>, <a href="#aac97171a3985fd07e09fef2a25819a16">addSVGConversion</a>, <a href="#a8a0183f93570ac3b1a8df3e0f7229a2b">addSVGObject</a> and <a href="#a02cd92c7c61a35c61c601ff6b409c5e5">run</a>.
</div>
</div>

### m\_patchFile {#ae17984831f2efe1fab30c6ab5d9e36f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DotFilePatcher::m_patchFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae17984831f2efe1fab30c6ab5d9e36f0">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae17984831f2efe1fab30c6ab5d9e36f0">m_patchFile</a>;</span></span></div>

</div>


Referenced by <a href="#a4993d9e9855116cd4fee5bd950c19bb8">DotFilePatcher</a>, <a href="#a36fcbf6fe68086f734c114a2d30c5516">isSVGFile</a> and <a href="#a02cd92c7c61a35c61c601ff6b409c5e5">run</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### convertMapFile() {#a28f0ce1e173d0f12f0a4425af69958a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotFilePatcher::convertMapFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; mapName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, bool urlOnly=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; context=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
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




converts the rectangles in a client site image map into a stream

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">t</td>
<td class="doxyParamItemDescription">the stream to which the result is written.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">mapName</td>
<td class="doxyParamItemDescription">the name of the map file.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">relPath</td>
<td class="doxyParamItemDescription">the relative path to the root of the output directory (used in case CREATE\_SUBDIRS is enabled).</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">urlOnly</td>
<td class="doxyParamItemDescription">if FALSE the url field in the map contains an external references followed by a $ and then the URL.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">context</td>
<td class="doxyParamItemDescription">the context (file, class, or namespace) in which the map file was found</td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
TRUE if successful.
</dd>
</dl>


Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>, definition at line 220 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp">dotfilepatcher.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28f0ce1e173d0f12f0a4425af69958a5">220</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;mapName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> urlOnly,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;context)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ifstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>(mapName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"problems opening map file {} for inclusion in the docs!\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"If you installed Graphviz/dot after a previous failing run, \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"try deleting the output directory and rerun doxygen.\n"</span><span class="doxyHighlight">,mapName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (getline(f,line)) </span><span class="doxyHighlightComment">// foreach line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> buf = line+</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (buf.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"&lt;area"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> replBuf = <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>(buf,relPath,urlOnly,context);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// in dot version 7.0.2 the alt attribute is, incorrectly, removed.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// see https://gitlab.com/graphviz/graphviz/-/issues/265</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indexA = replBuf.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"alt="</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (indexA == -1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">        replBuf = replBuf.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(5) + </span><span class="doxyHighlightStringLiteral">" alt=\"\""</span><span class="doxyHighlight"> + replBuf.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(replBuf.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() - 5);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// strip id="..." from replBuf since the id's are not needed and not unique.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indexS = replBuf.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"id=\""</span><span class="doxyHighlight">), indexE = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (indexS&gt;0 &amp;&amp; (indexE=replBuf.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">,indexS+4))!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; replBuf.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(indexS-1) &lt;&lt; replBuf.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(replBuf.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() - indexE - 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; replBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/dotgraph-cpp/#a174bf83fed06cf0780ec37022bfb931c">insertMapFile</a>, <a href="#a02cd92c7c61a35c61c601ff6b409c5e5">run</a> and <a href="/web-doxygen/docs/api/files/src/dot-cpp/#ada988a5303d67622cb43bd75c247fec2">writeDotImageMapFromFile</a>.
</div>
</div>

### writeSVGFigureLink() {#ae41b4e8b1817e1d1de1732e4c4f9069c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotFilePatcher::writeSVGFigureLink (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; out, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; baseName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; absImgName)</td>
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

Check if a reference to a SVG figure can be written and do so if possible.


Returns FALSE if not possible (for instance because the SVG file is not yet generated).

Declaration at line 48 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>, definition at line 582 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp">dotfilepatcher.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae41b4e8b1817e1d1de1732e4c4f9069c">582</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae41b4e8b1817e1d1de1732e4c4f9069c">DotFilePatcher::writeSVGFigureLink</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;out,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;absImgName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> width=600,height=600;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a1ee465ed3ecc9e198028ac98d6536546">readSVGSize</a>(absImgName,&amp;width,&amp;height))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (width==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (height&lt;=60) height=300; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> height+=300; </span><span class="doxyHighlightComment">// add some extra space for zooming</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (height&gt;600) height=600; </span><span class="doxyHighlightComment">// clip to maximum height of 600 pixels</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">    out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;div class=\"zoom\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//out &lt;&lt; "&lt;object type=\"image/svg+xml\" data=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//out &lt;&lt; "&lt;embed type=\"image/svg+xml\" src=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">    out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;iframe scrolling=\"no\" loading=\"lazy\" frameborder=\"0\" src=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; relPath &lt;&lt; baseName &lt;&lt; </span><span class="doxyHighlightStringLiteral">".svg\" width=\"100%\" height=\""</span><span class="doxyHighlight"> &lt;&lt; height &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//out &lt;&lt; "&lt;object type=\"image/svg+xml\" data=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//out &lt;&lt; "&lt;embed type=\"image/svg+xml\" src=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">    out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;iframe scrolling=\"no\" loading=\"lazy\" frameborder=\"0\" src=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; relPath &lt;&lt; baseName &lt;&lt; </span><span class="doxyHighlightStringLiteral">".svg\" width=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; ((width*96+48)/72) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" height=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; ((height*96+48)/72) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a244a836815fe16d7315c414105b8cfee">writeSVGNotSupported</a>(out);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//out &lt;&lt; "&lt;/object&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//out &lt;&lt; "&lt;/embed&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">  out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/iframe&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (width==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">    out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/div&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a1ee465ed3ecc9e198028ac98d6536546">readSVGSize</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a244a836815fe16d7315c414105b8cfee">writeSVGNotSupported</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgraph/#a456518c674e7ae8f45d4eea8935bdc38">DotGraph::generateCode</a>, <a href="#a02cd92c7c61a35c61c601ff6b409c5e5">run</a> and <a href="/web-doxygen/docs/api/files/src/dot-cpp/#ada988a5303d67622cb43bd75c247fec2">writeDotImageMapFromFile</a>.
</div>
</div>

### writeVecGfxFigure() {#a1e56aa086c8135c76d84de764845c20e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotFilePatcher::writeVecGfxFigure (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; out, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; baseName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; figureName)</td>
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



Declaration at line 51 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>, definition at line 621 of file <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp">dotfilepatcher.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1e56aa086c8135c76d84de764845c20e">621</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1e56aa086c8135c76d84de764845c20e">DotFilePatcher::writeVecGfxFigure</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;out,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;figureName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> width=400,height=550;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(USE_PDFLATEX))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/dotrunner/#aec96a0d40271cb4f17bf0290e145d74b">DotRunner::readBoundingBox</a>(figureName+</span><span class="doxyHighlightStringLiteral">".pdf"</span><span class="doxyHighlight">,&amp;width,&amp;height,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("writeVecGfxFigure()=0\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/dotrunner/#aec96a0d40271cb4f17bf0290e145d74b">DotRunner::readBoundingBox</a>(figureName+</span><span class="doxyHighlightStringLiteral">".eps"</span><span class="doxyHighlight">,&amp;width,&amp;height,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("writeVecGfxFigure()=0\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Got PDF/EPS size %d,%d\n",width,height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> maxWidth  = 350;  </span><span class="doxyHighlightComment">/* approx. page width in points, excl. margins */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> maxHeight = 550;  </span><span class="doxyHighlightComment">/* approx. page height in points, excl. margins */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">  out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\nopagebreak\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\begin{figure}[H]\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\begin{center}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\leavevmode\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (width&gt;maxWidth || height&gt;maxHeight) </span><span class="doxyHighlightComment">// figure too big for page</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// c*width/maxWidth &gt; c*height/maxHeight, where c=maxWidth*maxHeight&gt;0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (width*maxHeight&gt;height*maxWidth)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">      out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\includegraphics[width="</span><span class="doxyHighlight"> &lt;&lt; maxWidth &lt;&lt; </span><span class="doxyHighlightStringLiteral">"pt]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">      out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\includegraphics[height="</span><span class="doxyHighlight"> &lt;&lt; maxHeight &lt;&lt; </span><span class="doxyHighlightStringLiteral">"pt]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">    out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\includegraphics[width="</span><span class="doxyHighlight"> &lt;&lt; width &lt;&lt; </span><span class="doxyHighlightStringLiteral">"pt]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">  out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{"</span><span class="doxyHighlight"> &lt;&lt; baseName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\end{center}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\\end{figure}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("writeVecGfxFigure()=1\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/dotrunner/#aec96a0d40271cb4f17bf0290e145d74b">DotRunner::readBoundingBox</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dotgraph/#a456518c674e7ae8f45d4eea8935bdc38">DotGraph::generateCode</a> and <a href="#a02cd92c7c61a35c61c601ff6b409c5e5">run</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp">dotfilepatcher.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
