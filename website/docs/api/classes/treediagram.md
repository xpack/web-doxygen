---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/treediagram
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TreeDiagram` Class Reference

<p>Class representing the tree layout for the built-in class diagram. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class TreeDiagram { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24f44b8b412970f25bb7713658d0e9dc">Ptr</a> = std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/diagramrow">DiagramRow</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfc3de9439000aad71ce8d342a0319e1">Vec</a> = std::vector&lt; <a href="#a24f44b8b412970f25bb7713658d0e9dc">Ptr</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8782f25da29e8a967b2f9620c8fe4d03">iterator</a> = typename Vec::iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab648d038ab3cd0dc8ca7aa632dfcab7b">TreeDiagram</a> (const ClassDef *root, bool doBases)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a940a3aaf1985a9f2ff19dc95aa91716b">computeLayout</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa037c6667baaaab9ba4c69897df7caa0">computeRows</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80bd153a4b94ab9513d9d957b9953b1c">moveChildren</a> (DiagramItem *root, int dx)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf058c8bdaf9bc5f58e3b3a2097c4faa">computeExtremes</a> (uint32_t *labelWidth, uint32_t *xpos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7916cd8dbb3b48d335e036c9717ac00d">drawBoxes</a> (TextStream &amp;t, Image *image, bool doBase, bool bitmap, uint32_t baseRows, uint32_t superRows, uint32_t cellWidth, uint32_t cellHeight, QCString relPath="", bool generateMap=TRUE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0993890eece743a86f2d874f288b6f7d">drawConnectors</a> (TextStream &amp;t, Image *image, bool doBase, bool bitmap, uint32_t baseRows, uint32_t superRows, uint32_t cellWidth, uint32_t cellheight)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diagramrow">DiagramRow</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a722288bd9e075f9d49bce2e204abb33b">row</a> (int index)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeffe87b83ec63afbb431f8a7c0f59fcb">numRows</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diagramrow">DiagramRow</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcb49e50de77029d4b8d03cc4aa58e7d">addRow</a> (uint32_t l)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8782f25da29e8a967b2f9620c8fe4d03">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af54e6e1bea669bf1290d8587307e4d8e">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a8782f25da29e8a967b2f9620c8fe4d03">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a280423956def2398d3d8b05333615903">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37b661752d147469cfe557cd651763c9">layoutTree</a> (DiagramItem *root, uint32_t row)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acfc3de9439000aad71ce8d342a0319e1">Vec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a></td>
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

<p>Class representing the tree layout for the built-in class diagram.</p>

<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#a8782f25da29e8a967b2f9620c8fe4d03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using TreeDiagram::iterator =  typename Vec::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 108 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8782f25da29e8a967b2f9620c8fe4d03">108</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a8782f25da29e8a967b2f9620c8fe4d03">iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::iterator;</span></span></div>

</div>

</div>
</div>

### Ptr {#a24f44b8b412970f25bb7713658d0e9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using TreeDiagram::Ptr =  std::unique_ptr&lt;DiagramRow&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24f44b8b412970f25bb7713658d0e9dc">106</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a24f44b8b412970f25bb7713658d0e9dc">Ptr</a> = std::unique_ptr&lt;DiagramRow&gt;;</span></span></div>

</div>

</div>
</div>

### Vec {#acfc3de9439000aad71ce8d342a0319e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using TreeDiagram::Vec =  std::vector&lt;Ptr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acfc3de9439000aad71ce8d342a0319e1">107</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#acfc3de9439000aad71ce8d342a0319e1">Vec</a> = std::vector&lt;Ptr&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TreeDiagram() {#ab648d038ab3cd0dc8ca7aa632dfcab7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeDiagram::TreeDiagram (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * root, bool doBases)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab648d038ab3cd0dc8ca7aa632dfcab7b">398</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ab648d038ab3cd0dc8ca7aa632dfcab7b">TreeDiagram::TreeDiagram</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *root,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> doBases)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="#a722288bd9e075f9d49bce2e204abb33b">row</a> = std::make_unique&lt;DiagramRow&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/diagramrow">DiagramRow</a> *row_ptr = <a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.push_back(std::move(<a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">  row_ptr-&gt;<a href="/web-doxygen/docs/api/classes/diagramrow/#a8c301e781bb14b1a23c00974d2050496">insertClass</a>(</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,root,doBases,Protection::Public,Specifier::Normal,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/diagramrow/#a8c301e781bb14b1a23c00974d2050496">DiagramRow::insertClass</a>, <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a> and <a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addRow() {#abcb49e50de77029d4b8d03cc4aa58e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagramRow * TreeDiagram::addRow (uint32_t l)</td>
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



<p>Definition at line 126 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abcb49e50de77029d4b8d03cc4aa58e7d">126</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/diagramrow">DiagramRow</a> *<a href="#abcb49e50de77029d4b8d03cc4aa58e7d">addRow</a>(uint32_t l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">    { <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.push_back(std::make_unique&lt;DiagramRow&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,l)); </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.back().get(); }</span></span></div>

</div>


<p>Reference <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.</p>

</div>
</div>

### begin() {#af54e6e1bea669bf1290d8587307e4d8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator TreeDiagram::begin ()</td>
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



<p>Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af54e6e1bea669bf1290d8587307e4d8e">128</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8782f25da29e8a967b2f9620c8fe4d03">iterator</a> <a href="#af54e6e1bea669bf1290d8587307e4d8e">begin</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.begin();  }</span></span></div>

</div>


<p>Reference <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.</p>

</div>
</div>

### computeExtremes() {#acf058c8bdaf9bc5f58e3b3a2097c4faa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TreeDiagram::computeExtremes (uint32_t * labelWidth, uint32_t * xpos)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acf058c8bdaf9bc5f58e3b3a2097c4faa">539</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acf058c8bdaf9bc5f58e3b3a2097c4faa">TreeDiagram::computeExtremes</a>(uint32_t *maxLabelLen,uint32_t *maxXPos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t ml=0,mx=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dr : <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>) </span><span class="doxyHighlightComment">// for each row</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;di : *dr) </span><span class="doxyHighlightComment">// for each item in a row</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (di-&gt;isInList()) done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (maxXPos) mx=std::max(mx,di-&gt;xPos());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (maxLabelLen) ml=std::max(ml,<a href="/web-doxygen/docs/api/classes/image/#af25a570683d7f6392bdba0bf433f6c30">Image::stringLength</a>(di-&gt;label()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (done) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (maxLabelLen) *maxLabelLen=ml;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (maxXPos)     *maxXPos=mx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>, <a href="/web-doxygen/docs/api/classes/image/#af25a570683d7f6392bdba0bf433f6c30">Image::stringLength</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### computeLayout() {#a940a3aaf1985a9f2ff19dc95aa91716b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TreeDiagram::computeLayout ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a940a3aaf1985a9f2ff19dc95aa91716b">458</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a940a3aaf1985a9f2ff19dc95aa91716b">TreeDiagram::computeLayout</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (it!=<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.end() &amp;&amp; (*it)-&gt;numItems()&lt;<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a08f611cf182c7d6d2e6c7b944c7511dc">maxTreeWidth</a>) ++it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;<a href="#a722288bd9e075f9d49bce2e204abb33b">row</a> = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("computeLayout() list row at %d\n",row-&gt;number());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *opi=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> delta=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;di : *<a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *pi=di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">parentItem</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pi==opi &amp;&amp; !first) { delta-=<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">      first = pi!=opi;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">      opi=pi;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">      di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aca2295801c4b08a1565e86da1c04c242">move</a>(delta,0); </span><span class="doxyHighlightComment">// collapse all items in the same</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightComment">// list (except the first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">      di-&gt;putInList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// re-organize the diagram items</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *root=<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.front()-&gt;item(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="#a37b661752d147469cfe557cd651763c9">layoutTree</a>(root,0)) { }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// move first items of the lists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;<a href="#a722288bd9e075f9d49bce2e204abb33b">row</a> = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> rit = <a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>-&gt;begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (rit!=<a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>-&gt;end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *pi=(*rit)-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">parentItem</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pi-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aa5fb00694025122c8fd33f506bf37cb7">numChildren</a>()&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">        (*rit)-&gt;move(<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (rit!=<a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>-&gt;end() &amp;&amp; (*rit)-&gt;parentItem()==pi)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">          ++rit;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">        ++rit;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>, <a href="#a37b661752d147469cfe557cd651763c9">layoutTree</a>, <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a08f611cf182c7d6d2e6c7b944c7511dc">maxTreeWidth</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#aca2295801c4b08a1565e86da1c04c242">DiagramItem::move</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#aa5fb00694025122c8fd33f506bf37cb7">DiagramItem::numChildren</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">DiagramItem::parentItem</a>, <a href="#a722288bd9e075f9d49bce2e204abb33b">row</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### computeRows() {#aa037c6667baaaab9ba4c69897df7caa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t TreeDiagram::computeRows ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa037c6667baaaab9ba4c69897df7caa0">509</a></span><span class="doxyLineContent"><span class="doxyHighlight">uint32_t <a href="#aa037c6667baaaab9ba4c69897df7caa0">TreeDiagram::computeRows</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("TreeDiagram::computeRows()=%d\n",count());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t count=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (it!=<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.end() &amp;&amp; !(*it)-&gt;item(0)-&gt;isInList())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">    ++it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">    ++count;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("count=%d row=%p\n",count,row);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;<a href="#a722288bd9e075f9d49bce2e204abb33b">row</a> = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t maxListLen=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t curListLen=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *opi=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;di : *<a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>) </span><span class="doxyHighlightComment">// for each item in a row</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (di-&gt;parentItem()!=opi) curListLen=1; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> curListLen++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (curListLen&gt;maxListLen) maxListLen=curListLen;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">      opi=di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">parentItem</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("maxListLen=%d\n",maxListLen);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">    count+=maxListLen;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> count;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">DiagramItem::parentItem</a> and <a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>.</p>

</div>
</div>

### drawBoxes() {#a7916cd8dbb3b48d335e036c9717ac00d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TreeDiagram::drawBoxes (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/classes/image">Image</a> * image, bool doBase, bool bitmap, uint32_t baseRows, uint32_t superRows, uint32_t cellWidth, uint32_t cellHeight, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> relPath="", bool generateMap=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7916cd8dbb3b48d335e036c9717ac00d">592</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7916cd8dbb3b48d335e036c9717ac00d">TreeDiagram::drawBoxes</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="/web-doxygen/docs/api/classes/image">Image</a> *image,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> doBase,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bitmap,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">                            uint32_t baseRows,uint32_t superRows,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">                            uint32_t cellWidth,uint32_t cellHeight,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">                            <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.end() &amp;&amp; !doBase) ++it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> firstRow = doBase;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlight"> superRowsF = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(superRows);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (;it!=<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.end() &amp;&amp; !done;++it) </span><span class="doxyHighlightComment">// for each row</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dr = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t x=0,y=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlight"> xf=0.0f,yf=0.0f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *firstDi = dr-&gt;item(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (firstDi-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ac41f2e7b5f1de27cec87bc9a366dc687">isInList</a>()) </span><span class="doxyHighlightComment">// put boxes in a list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *opi=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/dualdiriterator">DualDirIterator&lt;DiagramRow,const std::unique_ptr&lt;DiagramItem&gt;</a>&amp;&gt; dit(*dr,!doBase);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!dit.<a href="/web-doxygen/docs/api/classes/dualdiriterator/#a1373c495765f5f449d68ad5352290ffb">atEnd</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *di = (*dit).get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">parentItem</a>()==opi)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitmap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase) y -= cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight">        y += cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase) yf += 1.0f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight">        yf -= 1.0f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitmap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">            x = di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ae9a8464ab6a8101b4a0ca6059006bd76">xPos</a>()*(cellWidth+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">              y = image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a72407363edfd7a8d706105b28c702a5f">height</a>()-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">                superRows*cellHeight-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">                (superRows-1)*<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">                di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#af6845bd28d71f2779264b4759ca51fbf">yPos</a>()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">              y = (baseRows-1)*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">                di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#af6845bd28d71f2779264b4759ca51fbf">yPos</a>()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">            xf = di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ab10397c2aeb1007eff18ca2d715041c3">xfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">              yf = di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aecbb22c7af5b0840b7da32e1c12dd1b5">yfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>+superRowsF-1.0f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">              yf = superRowsF-1.0f-di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aecbb22c7af5b0840b7da32e1c12dd1b5">yfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">        opi=di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">parentItem</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitmap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasDocs=di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a8beb033dd57d4d460942a3078242acf0">getClassDef</a>()-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a4a6853a6b7f98f30da5d61d680d86041">writeBitmapBox</a>(di,image,x,y,cellWidth,cellHeight,firstRow,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">              hasDocs,di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aa5fb00694025122c8fd33f506bf37cb7">numChildren</a>()&gt;0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!firstRow &amp;&amp; generateMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2e8ce3b3d8bd736fca765b669093772c">writeMapArea</a>(t,di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a8beb033dd57d4d460942a3078242acf0">getClassDef</a>(),relPath,x,y,cellWidth,cellHeight);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac45380e90067e3138b21af2a68dc19f3">writeVectorBox</a>(t,di,xf,yf,di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aa5fb00694025122c8fd33f506bf37cb7">numChildren</a>()&gt;0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">        ++dit;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">      done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// draw a tree of boxes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;di : *dr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitmap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">          x = di-&gt;xPos()*(cellWidth+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">            y = image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a72407363edfd7a8d706105b28c702a5f">height</a>()-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">              superRows*cellHeight-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">              (superRows-1)*<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">              di-&gt;yPos()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">            y = (baseRows-1)*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">              di-&gt;yPos()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasDocs=di-&gt;getClassDef()-&gt;isLinkable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a4a6853a6b7f98f30da5d61d680d86041">writeBitmapBox</a>(di.get(),image,x,y,cellWidth,cellHeight,firstRow,hasDocs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!firstRow &amp;&amp; generateMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2e8ce3b3d8bd736fca765b669093772c">writeMapArea</a>(t,di-&gt;getClassDef(),relPath,x,y,cellWidth,cellHeight);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">          xf=di-&gt;xfPos()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">            yf = di-&gt;yfPos()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>+superRowsF-1.0f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">            yf = superRowsF-1.0f-di-&gt;yfPos()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac45380e90067e3138b21af2a68dc19f3">writeVectorBox</a>(t,di.get(),xf,yf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">    firstRow=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dualdiriterator/#a1373c495765f5f449d68ad5352290ffb">DualDirIterator&lt; C, I &gt;::atEnd</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#a8beb033dd57d4d460942a3078242acf0">DiagramItem::getClassDef</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>, <a href="/web-doxygen/docs/api/classes/image/#a72407363edfd7a8d706105b28c702a5f">Image::height</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ac41f2e7b5f1de27cec87bc9a366dc687">DiagramItem::isInList</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>, <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#aa5fb00694025122c8fd33f506bf37cb7">DiagramItem::numChildren</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">DiagramItem::parentItem</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a4a6853a6b7f98f30da5d61d680d86041">writeBitmapBox</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2e8ce3b3d8bd736fca765b669093772c">writeMapArea</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac45380e90067e3138b21af2a68dc19f3">writeVectorBox</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ab10397c2aeb1007eff18ca2d715041c3">DiagramItem::xfPos</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ae9a8464ab6a8101b4a0ca6059006bd76">DiagramItem::xPos</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#aecbb22c7af5b0840b7da32e1c12dd1b5">DiagramItem::yfPos</a> and <a href="/web-doxygen/docs/api/classes/diagramitem/#af6845bd28d71f2779264b4759ca51fbf">DiagramItem::yPos</a>.</p>

</div>
</div>

### drawConnectors() {#a0993890eece743a86f2d874f288b6f7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TreeDiagram::drawConnectors (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/classes/image">Image</a> * image, bool doBase, bool bitmap, uint32_t baseRows, uint32_t superRows, uint32_t cellWidth, uint32_t cellheight)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0993890eece743a86f2d874f288b6f7d">723</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="/web-doxygen/docs/api/classes/image">Image</a> *image,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> doBase,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bitmap,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">                                 uint32_t baseRows,uint32_t superRows,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">                                 uint32_t cellWidth,uint32_t cellHeight)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlight"> superRowsF = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(superRows);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (;it!=<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.end() &amp;&amp; !done;++it) </span><span class="doxyHighlightComment">// for each row</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dr = *it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *rootDi = dr-&gt;item(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rootDi-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ac41f2e7b5f1de27cec87bc9a366dc687">isInList</a>()) </span><span class="doxyHighlightComment">// row consists of list connectors</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">      uint32_t x=0,y=0,ys=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlight"> xf=0.0f,yf=0.0f,ysf=0.0f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> rit = dr-&gt;begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (rit!=dr-&gt;end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *di=(*rit).get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *pi=di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">parentItem</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a603348be77849aaf4416a4673fa207b6">DiagramItemList</a> dil=pi-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a48ef173c810becf58f4b38685b778db1">getChildren</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *last=dil.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (di==last) </span><span class="doxyHighlightComment">// single child</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitmap) </span><span class="doxyHighlightComment">// draw pixels</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">            x = di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ae9a8464ab6a8101b4a0ca6059006bd76">xPos</a>()*(cellWidth+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a> + cellWidth/2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase) </span><span class="doxyHighlightComment">// base classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">              y = image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a72407363edfd7a8d706105b28c702a5f">height</a>()-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">                (superRows-1)*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">                di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#af6845bd28d71f2779264b4759ca51fbf">yPos</a>()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">              image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a444548aa9f3f1221a2f617e3f363b049">drawVertArrow</a>(x,y,y+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">                                   <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">                                   <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">              y = (baseRows-1)*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">                di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#af6845bd28d71f2779264b4759ca51fbf">yPos</a>()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">              image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a06adca4400b6ae51ca4b53bc1d021dcb">drawVertLine</a>(x,y,y+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">                                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">                                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// draw vectors</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ad92050b3f6c2e59066cbf6f03a76c1d8">protToString</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"1 "</span><span class="doxyHighlight"> &lt;&lt; (di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ab10397c2aeb1007eff18ca2d715041c3">xfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">                &lt;&lt; (di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aecbb22c7af5b0840b7da32e1c12dd1b5">yfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>+superRowsF-1.0f) &lt;&lt; </span><span class="doxyHighlightStringLiteral">" in\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"0 "</span><span class="doxyHighlight"> &lt;&lt; (di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ab10397c2aeb1007eff18ca2d715041c3">xfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">                &lt;&lt; (superRowsF-0.25f-di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aecbb22c7af5b0840b7da32e1c12dd1b5">yfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">                &lt;&lt; </span><span class="doxyHighlightStringLiteral">" in\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// multiple children, put them in a vertical list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitmap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">            x = di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">parentItem</a>()-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ae9a8464ab6a8101b4a0ca6059006bd76">xPos</a>()*</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">              (cellWidth+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>+cellWidth/2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase) </span><span class="doxyHighlightComment">// base classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">              ys = image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a72407363edfd7a8d706105b28c702a5f">height</a>()-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">                (superRows-1)*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">                di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#af6845bd28d71f2779264b4759ca51fbf">yPos</a>()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">              y = ys - cellHeight/2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">              ys = (baseRows-1)*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">                di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#af6845bd28d71f2779264b4759ca51fbf">yPos</a>()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">              y = ys + cellHeight/2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">            xf = di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">parentItem</a>()-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ab10397c2aeb1007eff18ca2d715041c3">xfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">              ysf = di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aecbb22c7af5b0840b7da32e1c12dd1b5">yfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>+superRowsF-1.0f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">              yf = ysf + 0.5f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">              ysf = superRowsF-0.25f-di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aecbb22c7af5b0840b7da32e1c12dd1b5">yfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">              yf = ysf - 0.25f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (di!=last) </span><span class="doxyHighlightComment">// more children to add</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitmap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase) </span><span class="doxyHighlightComment">// base classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">                image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a762d73040ae4821bb84d4bdf7d7658e0">drawHorzArrow</a>(y,x,x+cellWidth/2+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">                y -= cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">                image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a3963507ed7da8333a1b7766d890e12b4">drawHorzLine</a>(y,x,x+cellWidth/2+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">                    <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">                y += cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ad92050b3f6c2e59066cbf6f03a76c1d8">protToString</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">                t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"1 "</span><span class="doxyHighlight"> &lt;&lt; xf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; yf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" hedge\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">                yf += 1.0f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">                t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"0 "</span><span class="doxyHighlight"> &lt;&lt; xf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; yf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" hedge\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">                yf -= 1.0f;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">            ++rit;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rit!=dr-&gt;end()) di = (*rit).get(); </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> di=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// add last horizontal line and a vertical connection line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitmap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase) </span><span class="doxyHighlightComment">// base classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">              image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a762d73040ae4821bb84d4bdf7d7658e0">drawHorzArrow</a>(y,x,x+cellWidth/2+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">              image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a06adca4400b6ae51ca4b53bc1d021dcb">drawVertLine</a>(x,y,ys+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aa7edd2f3dfefdfd9655c162adc982e70">getMinProtectionLevel</a>(dil)),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>(<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aa7edd2f3dfefdfd9655c162adc982e70">getMinProtectionLevel</a>(dil)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">              image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a3963507ed7da8333a1b7766d890e12b4">drawHorzLine</a>(y,x,x+cellWidth/2+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">              image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a06adca4400b6ae51ca4b53bc1d021dcb">drawVertLine</a>(x,ys-<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2,y,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aa7edd2f3dfefdfd9655c162adc982e70">getMinProtectionLevel</a>(dil)),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>(<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aa7edd2f3dfefdfd9655c162adc982e70">getMinProtectionLevel</a>(dil)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ad92050b3f6c2e59066cbf6f03a76c1d8">protToString</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">protection</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"1 "</span><span class="doxyHighlight"> &lt;&lt; xf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; yf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" hedge\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"0 "</span><span class="doxyHighlight"> &lt;&lt; xf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; yf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" hedge\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ad92050b3f6c2e59066cbf6f03a76c1d8">protToString</a>(<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aa7edd2f3dfefdfd9655c162adc982e70">getMinProtectionLevel</a>(dil)) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; xf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; ysf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; yf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" vedge\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; xf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; (ysf + 0.25f) &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; yf &lt;&lt; </span><span class="doxyHighlightStringLiteral">" vedge\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rit!=dr-&gt;end()) ++rit;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">      done=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightComment">// the tree is drawn now</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// normal tree connector</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;di : *dr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">907</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">        uint32_t x=0,y=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a603348be77849aaf4416a4673fa207b6">DiagramItemList</a> dil = di-&gt;getChildren();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>  = di-&gt;parentItem();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>) </span><span class="doxyHighlightComment">// item has a parent -&gt; connect to it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitmap) </span><span class="doxyHighlightComment">// draw pixels</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">            x = di-&gt;xPos()*(cellWidth+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a> + cellWidth/2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase) </span><span class="doxyHighlightComment">// base classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">              y = image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a72407363edfd7a8d706105b28c702a5f">height</a>()-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">                (superRows-1)*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">                di-&gt;yPos()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">/* write input line */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">              image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a444548aa9f3f1221a2f617e3f363b049">drawVertArrow</a>(x,y,y+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(di-&gt;protection()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">924</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>(di-&gt;protection()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">              y = (baseRows-1)*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">929</span><span class="doxyLineContent"><span class="doxyHighlight">                <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">                di-&gt;yPos()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightComment">/* write output line */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">              image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a06adca4400b6ae51ca4b53bc1d021dcb">drawVertLine</a>(x,y,y+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(di-&gt;protection()),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">934</span><span class="doxyLineContent"><span class="doxyHighlight">                  <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>(di-&gt;protection()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// draw pixels</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ad92050b3f6c2e59066cbf6f03a76c1d8">protToString</a>(di-&gt;protection()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">940</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"1 "</span><span class="doxyHighlight"> &lt;&lt; di-&gt;xfPos()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">                &lt;&lt; (di-&gt;yfPos()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>+superRowsF-1.0f) &lt;&lt; </span><span class="doxyHighlightStringLiteral">" in\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"0 "</span><span class="doxyHighlight"> &lt;&lt; di-&gt;xfPos()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">                &lt;&lt; (superRowsF-0.25f-di-&gt;yfPos()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">                &lt;&lt; </span><span class="doxyHighlightStringLiteral">" in\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!dil.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p=<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aa7edd2f3dfefdfd9655c162adc982e70">getMinProtectionLevel</a>(dil);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">          uint32_t mask=<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">          uint8_t col=<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitmap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">            x = di-&gt;xPos()*(cellWidth+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a> + cellWidth/2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase) </span><span class="doxyHighlightComment">// base classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span><span class="doxyLineContent"><span class="doxyHighlight">              y = image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a72407363edfd7a8d706105b28c702a5f">height</a>()-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">                (superRows-1)*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">                cellHeight-<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2-</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">                di-&gt;yPos()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">              image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a06adca4400b6ae51ca4b53bc1d021dcb">drawVertLine</a>(x,y,y+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2-1,col,mask);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">              y = (baseRows-1)*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">                cellHeight+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">                di-&gt;yPos()*(cellHeight+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight">              image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a444548aa9f3f1221a2f617e3f363b049">drawVertArrow</a>(x,y,y+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2-1,col,mask);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ad92050b3f6c2e59066cbf6f03a76c1d8">protToString</a>(p) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"0 "</span><span class="doxyHighlight"> &lt;&lt; di-&gt;xfPos()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>  &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">                &lt;&lt; (di-&gt;yfPos()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>+superRowsF-1.0f) &lt;&lt; </span><span class="doxyHighlightStringLiteral">" out\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"1 "</span><span class="doxyHighlight"> &lt;&lt; di-&gt;xfPos()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>  &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">                &lt;&lt; (superRowsF-1.75f-di-&gt;yfPos()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">                &lt;&lt; </span><span class="doxyHighlightStringLiteral">" out\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">/* write input line */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *first = dil.front();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *last  = dil.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (first!=last &amp;&amp; !first-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ac41f2e7b5f1de27cec87bc9a366dc687">isInList</a>()) </span><span class="doxyHighlightComment">/* connect with all base classes */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitmap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight">              uint32_t xs = first-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ae9a8464ab6a8101b4a0ca6059006bd76">xPos</a>()*(cellWidth+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">                + cellWidth/2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">              uint32_t xe = last-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ae9a8464ab6a8101b4a0ca6059006bd76">xPos</a>()*(cellWidth+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>)/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">                + cellWidth/2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase) </span><span class="doxyHighlightComment">// base classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">                image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a3963507ed7da8333a1b7766d890e12b4">drawHorzLine</a>(y,xs,xe,col,mask);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">                image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a3963507ed7da8333a1b7766d890e12b4">drawHorzLine</a>(y+<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>/2,xs,xe,col,mask);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1011</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">              t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ad92050b3f6c2e59066cbf6f03a76c1d8">protToString</a>(p) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1015</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doBase)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1016</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">                t &lt;&lt; first-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ab10397c2aeb1007eff18ca2d715041c3">xfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight">                  &lt;&lt; last-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ab10397c2aeb1007eff18ca2d715041c3">xfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">                  &lt;&lt; (first-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aecbb22c7af5b0840b7da32e1c12dd1b5">yfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>+superRowsF-1.0f)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">                  &lt;&lt; </span><span class="doxyHighlightStringLiteral">" conn\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1022</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1023</span><span class="doxyLineContent"><span class="doxyHighlight">              {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">                t &lt;&lt; first-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ab10397c2aeb1007eff18ca2d715041c3">xfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight">                  &lt;&lt; last-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ab10397c2aeb1007eff18ca2d715041c3">xfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">                  &lt;&lt; (superRowsF-first-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aecbb22c7af5b0840b7da32e1c12dd1b5">yfPos</a>()/<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1027</span><span class="doxyLineContent"><span class="doxyHighlight">                  &lt;&lt; </span><span class="doxyHighlightStringLiteral">" conn\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">              }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1034</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1035</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/image/#a762d73040ae4821bb84d4bdf7d7658e0">Image::drawHorzArrow</a>, <a href="/web-doxygen/docs/api/classes/image/#a3963507ed7da8333a1b7766d890e12b4">Image::drawHorzLine</a>, <a href="/web-doxygen/docs/api/classes/image/#a444548aa9f3f1221a2f617e3f363b049">Image::drawVertArrow</a>, <a href="/web-doxygen/docs/api/classes/image/#a06adca4400b6ae51ca4b53bc1d021dcb">Image::drawVertLine</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#a48ef173c810becf58f4b38685b778db1">DiagramItem::getChildren</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aa7edd2f3dfefdfd9655c162adc982e70">getMinProtectionLevel</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>, <a href="/web-doxygen/docs/api/classes/image/#a72407363edfd7a8d706105b28c702a5f">Image::height</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ac41f2e7b5f1de27cec87bc9a366dc687">DiagramItem::isInList</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a486228a1ff55861685b37025028df553">labelHorSpacing</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a>, <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#a82d6af599475dd6408cfacb5c1181598">DiagramItem::parentItem</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#aaca11d38f246c2a3f673d29720cc0426">DiagramItem::protection</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac815a4d282922c6d48976d582826d1b5">protToColor</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ae83b8312932399969490a2948e15a7db">protToMask</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ad92050b3f6c2e59066cbf6f03a76c1d8">protToString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ab10397c2aeb1007eff18ca2d715041c3">DiagramItem::xfPos</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ae9a8464ab6a8101b4a0ca6059006bd76">DiagramItem::xPos</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#aecbb22c7af5b0840b7da32e1c12dd1b5">DiagramItem::yfPos</a> and <a href="/web-doxygen/docs/api/classes/diagramitem/#af6845bd28d71f2779264b4759ca51fbf">DiagramItem::yPos</a>.</p>

</div>
</div>

### end() {#a280423956def2398d3d8b05333615903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator TreeDiagram::end ()</td>
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



<p>Definition at line 129 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a280423956def2398d3d8b05333615903">129</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8782f25da29e8a967b2f9620c8fe4d03">iterator</a> <a href="#a280423956def2398d3d8b05333615903">end</a>()   { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.end();    }</span></span></div>

</div>


<p>Reference <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.</p>

</div>
</div>

### moveChildren() {#a80bd153a4b94ab9513d9d957b9953b1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TreeDiagram::moveChildren (<a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> * root, int dx)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a80bd153a4b94ab9513d9d957b9953b1c">406</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a80bd153a4b94ab9513d9d957b9953b1c">TreeDiagram::moveChildren</a>(<a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *root,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dx)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;di : root-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a48ef173c810becf58f4b38685b778db1">getChildren</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">    di-&gt;move(dx,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a80bd153a4b94ab9513d9d957b9953b1c">moveChildren</a>(di,dx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/diagramitem/#a48ef173c810becf58f4b38685b778db1">DiagramItem::getChildren</a> and <a href="#a80bd153a4b94ab9513d9d957b9953b1c">moveChildren</a>.</p>


<p>Referenced by <a href="#a80bd153a4b94ab9513d9d957b9953b1c">moveChildren</a>.</p>

</div>
</div>

### numRows() {#aeffe87b83ec63afbb431f8a7c0f59fcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t TreeDiagram::numRows ()</td>
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



<p>Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeffe87b83ec63afbb431f8a7c0f59fcb">125</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t <a href="#aeffe87b83ec63afbb431f8a7c0f59fcb">numRows</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.size()); }</span></span></div>

</div>


<p>Reference <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.</p>

</div>
</div>

### row() {#a722288bd9e075f9d49bce2e204abb33b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagramRow * TreeDiagram::row (int index)</td>
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



<p>Definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a722288bd9e075f9d49bce2e204abb33b">124</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/diagramrow">DiagramRow</a> *<a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.at(index).get(); }</span></span></div>

</div>


<p>Reference <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.</p>


<p>Referenced by <a href="#a940a3aaf1985a9f2ff19dc95aa91716b">computeLayout</a>, <a href="#aa037c6667baaaab9ba4c69897df7caa0">computeRows</a>, <a href="#a37b661752d147469cfe557cd651763c9">layoutTree</a> and <a href="#ab648d038ab3cd0dc8ca7aa632dfcab7b">TreeDiagram</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### layoutTree() {#a37b661752d147469cfe557cd651763c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool TreeDiagram::layoutTree (<a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> * root, uint32_t row)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 131 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a37b661752d147469cfe557cd651763c9">415</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a37b661752d147469cfe557cd651763c9">TreeDiagram::layoutTree</a>(<a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *root,uint32_t r)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> moved=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("layoutTree(%s,%d)\n",qPrint(root-&gt;label()),r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (root-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#aa5fb00694025122c8fd33f506bf37cb7">numChildren</a>()&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> children = root-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a48ef173c810becf58f4b38685b778db1">getChildren</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t pPos=root-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ae9a8464ab6a8101b4a0ca6059006bd76">xPos</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t cPos=root-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a82b5409be85251e7ced40ed8751dfdd5">avgChildPos</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pPos&gt;cPos) </span><span class="doxyHighlightComment">// move children</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;<a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>=<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.at(r+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Moving children %d-%d in row %d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//    dil-&gt;getFirst()-&gt;number(),row-&gt;count()-1,r+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (uint32_t k=children.front()-&gt;number();k&lt;row-&gt;numItems();k++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>-&gt;item(k)-&gt;move(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(pPos-cPos),0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">      moved=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pPos&lt;cPos) </span><span class="doxyHighlightComment">// move parent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;<a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>=<a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>.at(r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Moving parents %d-%d in row %d\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//    root-&gt;number(),row-&gt;count()-1,r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (uint32_t k=root-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a7eae5306f0a400f134bfa635b4d37eb1">number</a>();k&lt;row-&gt;numItems();k++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>-&gt;item(k)-&gt;move(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(cPos-pPos),0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">      moved=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// recurse to children</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = children.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (;it!=children.end() &amp;&amp; !moved &amp;&amp; !(*it)-&gt;isInList();++it)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">      moved = <a href="#a37b661752d147469cfe557cd651763c9">layoutTree</a>(*it,r+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> moved;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/diagramitem/#a82b5409be85251e7ced40ed8751dfdd5">DiagramItem::avgChildPos</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#a48ef173c810becf58f4b38685b778db1">DiagramItem::getChildren</a>, <a href="#a37b661752d147469cfe557cd651763c9">layoutTree</a>, <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#a7eae5306f0a400f134bfa635b4d37eb1">DiagramItem::number</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#aa5fb00694025122c8fd33f506bf37cb7">DiagramItem::numChildren</a>, <a href="#a722288bd9e075f9d49bce2e204abb33b">row</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/diagramitem/#ae9a8464ab6a8101b4a0ca6059006bd76">DiagramItem::xPos</a>.</p>


<p>Referenced by <a href="#a940a3aaf1985a9f2ff19dc95aa91716b">computeLayout</a> and <a href="#a37b661752d147469cfe557cd651763c9">layoutTree</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_rows {#a640c77fec2dc17c487ed70aa0ae78689}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Vec TreeDiagram::m_rows</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a640c77fec2dc17c487ed70aa0ae78689">132</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#acfc3de9439000aad71ce8d342a0319e1">Vec</a> <a href="#a640c77fec2dc17c487ed70aa0ae78689">m_rows</a>;</span></span></div>

</div>


<p>Referenced by <a href="#abcb49e50de77029d4b8d03cc4aa58e7d">addRow</a>, <a href="#af54e6e1bea669bf1290d8587307e4d8e">begin</a>, <a href="#acf058c8bdaf9bc5f58e3b3a2097c4faa">computeExtremes</a>, <a href="#a940a3aaf1985a9f2ff19dc95aa91716b">computeLayout</a>, <a href="#aa037c6667baaaab9ba4c69897df7caa0">computeRows</a>, <a href="#a7916cd8dbb3b48d335e036c9717ac00d">drawBoxes</a>, <a href="#a0993890eece743a86f2d874f288b6f7d">drawConnectors</a>, <a href="#a280423956def2398d3d8b05333615903">end</a>, <a href="#a37b661752d147469cfe557cd651763c9">layoutTree</a>, <a href="#aeffe87b83ec63afbb431f8a7c0f59fcb">numRows</a>, <a href="#a722288bd9e075f9d49bce2e204abb33b">row</a> and <a href="#ab648d038ab3cd0dc8ca7aa632dfcab7b">TreeDiagram</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
