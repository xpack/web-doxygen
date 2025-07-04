---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/dualdiriterator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DualDirIterator` Class Template Reference

<p>helper class representing an iterator that can iterate forwards or backwards <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class C, class I&gt;
class DualDirIterator&lt;C, I&gt; { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class C, class I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#ab11a6e918725dcfe806978f3744e85aa">DualDirIterator</a> (C &amp;container, bool fwd)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class C, class I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a14e6d78f7b7c31704e5ce390701dd0da">operator++</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class C, class I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">I &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aedcb6e69e2cc5ba14f50652be03a523a">operator*</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class C, class I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a1373c495765f5f449d68ad5352290ffb">atEnd</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class C, class I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">C &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aec819b73d1ab5d124e91e376a96557c7">m_container</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class C, class I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a77c834a909aede3162f95ff478dc694f">m_forward</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class C, class I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">C::iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aebec7abd6c90c22c837ad7d321f5a47b">m_it</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class C, class I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">C::reverse_iterator</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aad92bde29514b1eb15c84c2033a06416">m_rit</a></td>
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

<p>helper class representing an iterator that can iterate forwards or backwards</p>

<p>Definition at line 559 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DualDirIterator() {#ab11a6e918725dcfe806978f3744e85aa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DualDirIterator&lt; C, I &gt;::DualDirIterator (C &amp; container, bool fwd)</td>
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



<p>Definition at line 562 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab11a6e918725dcfe806978f3744e85aa">562</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab11a6e918725dcfe806978f3744e85aa">DualDirIterator</a>(C &amp;container,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> fwd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="#aec819b73d1ab5d124e91e376a96557c7">m_container</a>(container), <a href="#a77c834a909aede3162f95ff478dc694f">m_forward</a>(fwd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fwd) <a href="#aebec7abd6c90c22c837ad7d321f5a47b">m_it</a> = container.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#aad92bde29514b1eb15c84c2033a06416">m_rit</a> = container.rbegin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aec819b73d1ab5d124e91e376a96557c7">DualDirIterator&lt; C, I &gt;::m_container</a>, <a href="#a77c834a909aede3162f95ff478dc694f">DualDirIterator&lt; C, I &gt;::m_forward</a>, <a href="#aebec7abd6c90c22c837ad7d321f5a47b">DualDirIterator&lt; C, I &gt;::m_it</a> and <a href="#aad92bde29514b1eb15c84c2033a06416">DualDirIterator&lt; C, I &gt;::m_rit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\*() {#aedcb6e69e2cc5ba14f50652be03a523a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">I &amp; DualDirIterator&lt; C, I &gt;::operator* ()</td>
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



<p>Definition at line 572 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aedcb6e69e2cc5ba14f50652be03a523a">572</a></span><span class="doxyLineContent"><span class="doxyHighlight">    I &amp;<a href="#aedcb6e69e2cc5ba14f50652be03a523a">operator*</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a77c834a909aede3162f95ff478dc694f">m_forward</a> ? *<a href="#aebec7abd6c90c22c837ad7d321f5a47b">m_it</a> : *<a href="#aad92bde29514b1eb15c84c2033a06416">m_rit</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a77c834a909aede3162f95ff478dc694f">DualDirIterator&lt; C, I &gt;::m_forward</a>, <a href="#aebec7abd6c90c22c837ad7d321f5a47b">DualDirIterator&lt; C, I &gt;::m_it</a> and <a href="#aad92bde29514b1eb15c84c2033a06416">DualDirIterator&lt; C, I &gt;::m_rit</a>.</p>

</div>
</div>

### operator++() {#a14e6d78f7b7c31704e5ce390701dd0da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DualDirIterator&lt; C, I &gt;::operator++ ()</td>
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



<p>Definition at line 568 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a14e6d78f7b7c31704e5ce390701dd0da">568</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a14e6d78f7b7c31704e5ce390701dd0da">operator++</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a77c834a909aede3162f95ff478dc694f">m_forward</a>) ++<a href="#aebec7abd6c90c22c837ad7d321f5a47b">m_it</a>++; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> ++<a href="#aad92bde29514b1eb15c84c2033a06416">m_rit</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a77c834a909aede3162f95ff478dc694f">DualDirIterator&lt; C, I &gt;::m_forward</a>, <a href="#aebec7abd6c90c22c837ad7d321f5a47b">DualDirIterator&lt; C, I &gt;::m_it</a> and <a href="#aad92bde29514b1eb15c84c2033a06416">DualDirIterator&lt; C, I &gt;::m_rit</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### atEnd() {#a1373c495765f5f449d68ad5352290ffb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DualDirIterator&lt; C, I &gt;::atEnd ()</td>
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



<p>Definition at line 577 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1373c495765f5f449d68ad5352290ffb">577</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1373c495765f5f449d68ad5352290ffb">atEnd</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a77c834a909aede3162f95ff478dc694f">m_forward</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aebec7abd6c90c22c837ad7d321f5a47b">m_it</a>==<a href="#aec819b73d1ab5d124e91e376a96557c7">m_container</a>.end();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aad92bde29514b1eb15c84c2033a06416">m_rit</a>==<a href="#aec819b73d1ab5d124e91e376a96557c7">m_container</a>.rend();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aec819b73d1ab5d124e91e376a96557c7">DualDirIterator&lt; C, I &gt;::m_container</a>, <a href="#a77c834a909aede3162f95ff478dc694f">DualDirIterator&lt; C, I &gt;::m_forward</a>, <a href="#aebec7abd6c90c22c837ad7d321f5a47b">DualDirIterator&lt; C, I &gt;::m_it</a> and <a href="#aad92bde29514b1eb15c84c2033a06416">DualDirIterator&lt; C, I &gt;::m_rit</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a7916cd8dbb3b48d335e036c9717ac00d">TreeDiagram::drawBoxes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_container {#aec819b73d1ab5d124e91e376a96557c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">C&amp; DualDirIterator&lt; C, I &gt;::m_container</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 586 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aec819b73d1ab5d124e91e376a96557c7">586</a></span><span class="doxyLineContent"><span class="doxyHighlight">    C &amp;<a href="#aec819b73d1ab5d124e91e376a96557c7">m_container</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1373c495765f5f449d68ad5352290ffb">DualDirIterator&lt; C, I &gt;::atEnd</a> and <a href="#ab11a6e918725dcfe806978f3744e85aa">DualDirIterator&lt; C, I &gt;::DualDirIterator</a>.</p>

</div>
</div>

### m\_forward {#a77c834a909aede3162f95ff478dc694f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DualDirIterator&lt; C, I &gt;::m_forward</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 587 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a77c834a909aede3162f95ff478dc694f">587</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a77c834a909aede3162f95ff478dc694f">m_forward</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1373c495765f5f449d68ad5352290ffb">DualDirIterator&lt; C, I &gt;::atEnd</a>, <a href="#ab11a6e918725dcfe806978f3744e85aa">DualDirIterator&lt; C, I &gt;::DualDirIterator</a>, <a href="#aedcb6e69e2cc5ba14f50652be03a523a">DualDirIterator&lt; C, I &gt;::operator*</a> and <a href="#a14e6d78f7b7c31704e5ce390701dd0da">DualDirIterator&lt; C, I &gt;::operator++</a>.</p>

</div>
</div>

### m\_it {#aebec7abd6c90c22c837ad7d321f5a47b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">C::iterator DualDirIterator&lt; C, I &gt;::m_it</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 588 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebec7abd6c90c22c837ad7d321f5a47b">588</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> C::iterator <a href="#aebec7abd6c90c22c837ad7d321f5a47b">m_it</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1373c495765f5f449d68ad5352290ffb">DualDirIterator&lt; C, I &gt;::atEnd</a>, <a href="#ab11a6e918725dcfe806978f3744e85aa">DualDirIterator&lt; C, I &gt;::DualDirIterator</a>, <a href="#aedcb6e69e2cc5ba14f50652be03a523a">DualDirIterator&lt; C, I &gt;::operator*</a> and <a href="#a14e6d78f7b7c31704e5ce390701dd0da">DualDirIterator&lt; C, I &gt;::operator++</a>.</p>

</div>
</div>

### m\_rit {#aad92bde29514b1eb15c84c2033a06416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">C::reverse_iterator DualDirIterator&lt; C, I &gt;::m_rit</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 589 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad92bde29514b1eb15c84c2033a06416">589</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> C::reverse_iterator <a href="#aad92bde29514b1eb15c84c2033a06416">m_rit</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1373c495765f5f449d68ad5352290ffb">DualDirIterator&lt; C, I &gt;::atEnd</a>, <a href="#ab11a6e918725dcfe806978f3744e85aa">DualDirIterator&lt; C, I &gt;::DualDirIterator</a>, <a href="#aedcb6e69e2cc5ba14f50652be03a523a">DualDirIterator&lt; C, I &gt;::operator*</a> and <a href="#a14e6d78f7b7c31704e5ce390701dd0da">DualDirIterator&lt; C, I &gt;::operator++</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
