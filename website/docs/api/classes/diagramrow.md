---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/diagramrow
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DiagramRow` Class Reference

<p>Class representing a row in the built-in class diagram. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DiagramRow { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a283ccf6a29e8c54697d6451786e23420">Ptr</a> = std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25e693d6876a38a4bf35019bfb365cb8">Vec</a> = std::vector&lt; <a href="#a283ccf6a29e8c54697d6451786e23420">Ptr</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6244a83f24329ccc40b48d4ddc8e71a9">iterator</a> = typename Vec::iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34cb1ca03889cd1f2ed7366e05009148">reverse_iterator</a> = typename Vec::reverse_iterator</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582a842c520400a016f12213246c39b5">DiagramRow</a> (TreeDiagram *d, uint32_t l)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c301e781bb14b1a23c00974d2050496">insertClass</a> (DiagramItem *parent, const ClassDef *cd, bool doBases, Protection prot, Specifier virt, const QCString &amp;ts)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57d2eb1d8877f2efb52cf75f8d154347">number</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a299e30b31cf11240efea369be1276df5">item</a> (int index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1270798b1430f690b3e1f91f4857eb55">numItems</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6244a83f24329ccc40b48d4ddc8e71a9">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8488330f275e6f40ea01f5c647c0c565">begin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6244a83f24329ccc40b48d4ddc8e71a9">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a849d1f6e44be3be59c6f3b790a61b603">end</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a34cb1ca03889cd1f2ed7366e05009148">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbf4140a44d1f329d84a8a777ac38a7a">rbegin</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a34cb1ca03889cd1f2ed7366e05009148">reverse_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9841e9db5016f609ca98b4b8c394c880">rend</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/treediagram">TreeDiagram</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f408150b4d9388a2eb169d2216c33df">m_diagram</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a25e693d6876a38a4bf35019bfb365cb8">Vec</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e2233999b2726198204c55106feb8af">m_items</a></td>
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

<p>Class representing a row in the built-in class diagram.</p>

<p>Definition at line 78 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### iterator {#a6244a83f24329ccc40b48d4ddc8e71a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DiagramRow::iterator =  typename Vec::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6244a83f24329ccc40b48d4ddc8e71a9">83</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a6244a83f24329ccc40b48d4ddc8e71a9">iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::iterator;</span></span></div>

</div>

</div>
</div>

### Ptr {#a283ccf6a29e8c54697d6451786e23420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DiagramRow::Ptr =  std::unique_ptr&lt;DiagramItem&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a283ccf6a29e8c54697d6451786e23420">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a283ccf6a29e8c54697d6451786e23420">Ptr</a> = std::unique_ptr&lt;DiagramItem&gt;;</span></span></div>

</div>

</div>
</div>

### reverse\_iterator {#a34cb1ca03889cd1f2ed7366e05009148}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DiagramRow::reverse_iterator =  typename Vec::reverse_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34cb1ca03889cd1f2ed7366e05009148">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a34cb1ca03889cd1f2ed7366e05009148">reverse_iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::reverse_iterator;</span></span></div>

</div>

</div>
</div>

### Vec {#a25e693d6876a38a4bf35019bfb365cb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DiagramRow::Vec =  std::vector&lt;Ptr&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a25e693d6876a38a4bf35019bfb365cb8">82</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a25e693d6876a38a4bf35019bfb365cb8">Vec</a> = std::vector&lt;Ptr&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DiagramRow() {#a582a842c520400a016f12213246c39b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagramRow::DiagramRow (<a href="/web-doxygen/docs/api/classes/treediagram">TreeDiagram</a> * d, uint32_t l)</td>
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



<p>Definition at line 85 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a582a842c520400a016f12213246c39b5">85</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a582a842c520400a016f12213246c39b5">DiagramRow</a>(<a href="/web-doxygen/docs/api/classes/treediagram">TreeDiagram</a> *d,uint32_t l) : <a href="#a0f408150b4d9388a2eb169d2216c33df">m_diagram</a>(d), <a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a>(l) {}</span></span></div>

</div>


<p>References <a href="#a0f408150b4d9388a2eb169d2216c33df">m_diagram</a> and <a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a>.</p>


<p>Referenced by <a href="#a8c301e781bb14b1a23c00974d2050496">insertClass</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a8488330f275e6f40ea01f5c647c0c565}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator DiagramRow::begin ()</td>
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



<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8488330f275e6f40ea01f5c647c0c565">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6244a83f24329ccc40b48d4ddc8e71a9">iterator</a> <a href="#a8488330f275e6f40ea01f5c647c0c565">begin</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.begin();  }</span></span></div>

</div>


<p>Reference <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.</p>

</div>
</div>

### end() {#a849d1f6e44be3be59c6f3b790a61b603}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator DiagramRow::end ()</td>
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



<p>Definition at line 93 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a849d1f6e44be3be59c6f3b790a61b603">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6244a83f24329ccc40b48d4ddc8e71a9">iterator</a> <a href="#a849d1f6e44be3be59c6f3b790a61b603">end</a>()   { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.end();    }</span></span></div>

</div>


<p>Reference <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.</p>

</div>
</div>

### insertClass() {#a8c301e781bb14b1a23c00974d2050496}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DiagramRow::insertClass (<a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> * parent, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, bool doBases, <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot, <a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> virt, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ts)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c301e781bb14b1a23c00974d2050496">356</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8c301e781bb14b1a23c00974d2050496">DiagramRow::insertClass</a>(<a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> doBases,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">                             <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot,<a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> virt,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ts)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> di = std::make_unique&lt;DiagramItem&gt;(<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>, <a href="#a0f408150b4d9388a2eb169d2216c33df">m_diagram</a>-&gt;row(<a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a>)-&gt;numItems(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">                                          cd,prot,virt,ts);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *di_ptr = di.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>) <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a>-&gt;addChild(di_ptr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">  di-&gt;move(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.size()*<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>),</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a>*<a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.push_back(std::move(di));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : doBases ? cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>() : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">/* there are base/sub classes */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *ccd=bcd.classDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ccd &amp;&amp; ccd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3067e647412a923d7743258c89eabe75">isVisibleInHierarchy</a>()) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count&gt;0 &amp;&amp; (prot!=Protection::Private || !doBases))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a582a842c520400a016f12213246c39b5">DiagramRow</a> *row=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a0f408150b4d9388a2eb169d2216c33df">m_diagram</a>-&gt;numRows()&lt;=<a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a>+1) </span><span class="doxyHighlightComment">/* add new row */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">      row=<a href="#a0f408150b4d9388a2eb169d2216c33df">m_diagram</a>-&gt;addRow(<a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a>+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* get next row */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">      row=<a href="#a0f408150b4d9388a2eb169d2216c33df">m_diagram</a>-&gt;row(<a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a>+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : doBases ? cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>() : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *ccd=bcd.classDef;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ccd &amp;&amp; ccd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a3067e647412a923d7743258c89eabe75">isVisibleInHierarchy</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">        row-&gt;<a href="#a8c301e781bb14b1a23c00974d2050496">insertClass</a>(di_ptr,ccd,doBases,bcd.prot,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">            doBases ? bcd.virt            : Specifier::Normal,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">            doBases ? bcd.templSpecifiers : <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">ClassDef::baseClasses</a>, <a href="#a582a842c520400a016f12213246c39b5">DiagramRow</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>, <a href="#a8c301e781bb14b1a23c00974d2050496">insertClass</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a3067e647412a923d7743258c89eabe75">ClassDef::isVisibleInHierarchy</a>, <a href="#a0f408150b4d9388a2eb169d2216c33df">m_diagram</a>, <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>, <a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa08872da61afee56859056e5a0612633">parent</a> and <a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">ClassDef::subClasses</a>.</p>


<p>Referenced by <a href="#a8c301e781bb14b1a23c00974d2050496">insertClass</a> and <a href="/web-doxygen/docs/api/classes/treediagram/#ab648d038ab3cd0dc8ca7aa632dfcab7b">TreeDiagram::TreeDiagram</a>.</p>

</div>
</div>

### item() {#a299e30b31cf11240efea369be1276df5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DiagramItem * DiagramRow::item (int index)</td>
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



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a299e30b31cf11240efea369be1276df5">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *<a href="#a299e30b31cf11240efea369be1276df5">item</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.at(index).get(); }</span></span></div>

</div>


<p>Reference <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.</p>

</div>
</div>

### number() {#a57d2eb1d8877f2efb52cf75f8d154347}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DiagramRow::number ()</td>
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



<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a57d2eb1d8877f2efb52cf75f8d154347">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t <a href="#a57d2eb1d8877f2efb52cf75f8d154347">number</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a>; }</span></span></div>

</div>


<p>Reference <a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a>.</p>

</div>
</div>

### numItems() {#a1270798b1430f690b3e1f91f4857eb55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DiagramRow::numItems ()</td>
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



<p>Definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1270798b1430f690b3e1f91f4857eb55">91</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t <a href="#a1270798b1430f690b3e1f91f4857eb55">numItems</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.size()); }</span></span></div>

</div>


<p>Reference <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.</p>

</div>
</div>

### rbegin() {#adbf4140a44d1f329d84a8a777ac38a7a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator DiagramRow::rbegin ()</td>
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



<p>Definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adbf4140a44d1f329d84a8a777ac38a7a">94</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a34cb1ca03889cd1f2ed7366e05009148">reverse_iterator</a> <a href="#adbf4140a44d1f329d84a8a777ac38a7a">rbegin</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.rbegin();  }</span></span></div>

</div>


<p>Reference <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.</p>

</div>
</div>

### rend() {#a9841e9db5016f609ca98b4b8c394c880}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reverse_iterator DiagramRow::rend ()</td>
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



<p>Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9841e9db5016f609ca98b4b8c394c880">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a34cb1ca03889cd1f2ed7366e05009148">reverse_iterator</a> <a href="#a9841e9db5016f609ca98b4b8c394c880">rend</a>()   { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.rend();    }</span></span></div>

</div>


<p>Reference <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_diagram {#a0f408150b4d9388a2eb169d2216c33df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TreeDiagram* DiagramRow::m_diagram</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 97 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f408150b4d9388a2eb169d2216c33df">97</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/treediagram">TreeDiagram</a> *<a href="#a0f408150b4d9388a2eb169d2216c33df">m_diagram</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a582a842c520400a016f12213246c39b5">DiagramRow</a> and <a href="#a8c301e781bb14b1a23c00974d2050496">insertClass</a>.</p>

</div>
</div>

### m\_items {#a3e2233999b2726198204c55106feb8af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Vec DiagramRow::m_items</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3e2233999b2726198204c55106feb8af">99</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a25e693d6876a38a4bf35019bfb365cb8">Vec</a> <a href="#a3e2233999b2726198204c55106feb8af">m_items</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a8488330f275e6f40ea01f5c647c0c565">begin</a>, <a href="#a849d1f6e44be3be59c6f3b790a61b603">end</a>, <a href="#a8c301e781bb14b1a23c00974d2050496">insertClass</a>, <a href="#a299e30b31cf11240efea369be1276df5">item</a>, <a href="#a1270798b1430f690b3e1f91f4857eb55">numItems</a>, <a href="#adbf4140a44d1f329d84a8a777ac38a7a">rbegin</a> and <a href="#a9841e9db5016f609ca98b4b8c394c880">rend</a>.</p>

</div>
</div>

### m\_level {#ae7d273d5c0bb289738072dc4e4bffe61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t DiagramRow::m_level</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae7d273d5c0bb289738072dc4e4bffe61">98</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t <a href="#ae7d273d5c0bb289738072dc4e4bffe61">m_level</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a582a842c520400a016f12213246c39b5">DiagramRow</a>, <a href="#a8c301e781bb14b1a23c00974d2050496">insertClass</a> and <a href="#a57d2eb1d8877f2efb52cf75f8d154347">number</a>.</p>

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
