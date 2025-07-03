---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/growvector/iterator
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Iterator` Class Template Reference

<p>bidirectional iterator <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
template &lt;class C, class I&gt;
class GrowVector::Iterator&lt;C, I&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/growvector-h">src/growvector.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class C, class I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a15a2504df24138f9ef0c760ad8a5610e">iterator_category</a> = std::bidirectional_iterator_tag</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a303b2faf2e9f7000a612dbabeb68fd1a">difference_type</a> = std::ptrdiff_t</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a7a88c99cdbf752deb008f7c408521aea">value_type</a> = I</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4a7268f9de5d3be96c3ad8c4a6e996ca">pointer</a> = I *</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ac0c88db900f588226a06c2d0670c9ef0">reference</a> = I &amp;</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class C, class I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#adf9a9358b475317bd816d7b47a0f5cd1">operator==</a></td>
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
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a27aed9f3ea67a677964fa51de28a5824">operator!=</a></td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class C, class I&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a> (C &amp;vec, size_t pos)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#ac0c88db900f588226a06c2d0670c9ef0">reference</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a0efb945ff9c2e86dac803a11911706">operator*</a> () const</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="#a4a7268f9de5d3be96c3ad8c4a6e996ca">pointer</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a6221b47203d0511e34e2ff2d2259a7cb">operator-&gt;</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a5e9c2e89b1cfe99e6bdc3b8420a36ed1">operator++</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a49e00b9084ba7231f29234f939573910">operator++</a> (int)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator</a> &amp;</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8a9b31597cc30527d72c7f4439a63df0">operator--</a> ()</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator</a></td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a685318d21faa5018a4ed1d8165eb69da">operator--</a> (int)</td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">C *</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a8b69ce24c4135c1155b61a1e3be45327">m_vec</a></td>
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
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4fd14ed7a676ff310d34bc1360f04419">m_pos</a></td>
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

<p>bidirectional iterator</p>

<p>Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### difference\_type {#a303b2faf2e9f7000a612dbabeb68fd1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::difference_type =  std::ptrdiff_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a303b2faf2e9f7000a612dbabeb68fd1a">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a303b2faf2e9f7000a612dbabeb68fd1a">difference_type</a>   = std::ptrdiff_t;</span></span></div>

</div>

</div>
</div>

### iterator\_category {#a15a2504df24138f9ef0c760ad8a5610e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::iterator_category =  std::bidirectional_iterator_tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15a2504df24138f9ef0c760ad8a5610e">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a15a2504df24138f9ef0c760ad8a5610e">iterator_category</a> = std::bidirectional_iterator_tag;</span></span></div>

</div>

</div>
</div>

### pointer {#a4a7268f9de5d3be96c3ad8c4a6e996ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::pointer =  I*</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a7268f9de5d3be96c3ad8c4a6e996ca">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a4a7268f9de5d3be96c3ad8c4a6e996ca">pointer</a>           = I*;</span></span></div>

</div>

</div>
</div>

### reference {#ac0c88db900f588226a06c2d0670c9ef0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::reference =  I&amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac0c88db900f588226a06c2d0670c9ef0">62</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ac0c88db900f588226a06c2d0670c9ef0">reference</a>         = I&amp;;</span></span></div>

</div>

</div>
</div>

### value\_type {#a7a88c99cdbf752deb008f7c408521aea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::value_type =  I</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a88c99cdbf752deb008f7c408521aea">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a7a88c99cdbf752deb008f7c408521aea">value_type</a>        = I;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### operator!= {#a27aed9f3ea67a677964fa51de28a5824}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool const <a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator</a> &amp; a, const <a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator</a> &amp; b</td>
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


<p>Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a27aed9f3ea67a677964fa51de28a5824">73</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a27aed9f3ea67a677964fa51de28a5824">operator!=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a>&amp; a, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a>&amp; b) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> a.<a href="#a4fd14ed7a676ff310d34bc1360f04419">m_pos</a> != b.<a href="#a4fd14ed7a676ff310d34bc1360f04419">m_pos</a>; };</span></span></div>

</div>

</div>
</div>

### operator== {#adf9a9358b475317bd816d7b47a0f5cd1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool const <a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator</a> &amp; a, const <a href="/web-doxygen/docs/api/classes/growvector/iterator">Iterator</a> &amp; b</td>
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


<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adf9a9358b475317bd816d7b47a0f5cd1">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#adf9a9358b475317bd816d7b47a0f5cd1">operator==</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a>&amp; a, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a>&amp; b) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> a.<a href="#a4fd14ed7a676ff310d34bc1360f04419">m_pos</a> == b.<a href="#a4fd14ed7a676ff310d34bc1360f04419">m_pos</a>; };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Iterator() {#a55b4821006a5d1653581dd733ba438f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::Iterator (C &amp; vec, size_t pos)</td>
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



<p>Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a55b4821006a5d1653581dd733ba438f0">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a>(C &amp;vec,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos) : <a href="#a8b69ce24c4135c1155b61a1e3be45327">m_vec</a>(&amp;vec), <a href="#a4fd14ed7a676ff310d34bc1360f04419">m_pos</a>(pos) {}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator--() {#a8a9b31597cc30527d72c7f4439a63df0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Iterator &amp; GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::operator-- ()</td>
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



<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8a9b31597cc30527d72c7f4439a63df0">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a>&amp; <a href="#a8a9b31597cc30527d72c7f4439a63df0">operator--</a>()      { <a href="#a4fd14ed7a676ff310d34bc1360f04419">m_pos</a>--; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">; }</span></span></div>

</div>

</div>
</div>

### operator--() {#a685318d21faa5018a4ed1d8165eb69da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Iterator GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::operator-- (int)</td>
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



<p>Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a685318d21faa5018a4ed1d8165eb69da">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a> <a href="#a685318d21faa5018a4ed1d8165eb69da">operator--</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)    { <a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a> tmp = *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">; --(*this); </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> tmp; }</span></span></div>

</div>

</div>
</div>

### operator-&gt;() {#a6221b47203d0511e34e2ff2d2259a7cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">pointer GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::operator-&gt; ()</td>
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



<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6221b47203d0511e34e2ff2d2259a7cb">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a4a7268f9de5d3be96c3ad8c4a6e996ca">pointer</a> <a href="#a6221b47203d0511e34e2ff2d2259a7cb">operator-&gt;</a>()        { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#a8b69ce24c4135c1155b61a1e3be45327">m_vec</a>-&gt;at(<a href="#a4fd14ed7a676ff310d34bc1360f04419">m_pos</a>); }</span></span></div>

</div>

</div>
</div>

### operator\*() {#a8a0efb945ff9c2e86dac803a11911706}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reference GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::operator* ()</td>
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



<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8a0efb945ff9c2e86dac803a11911706">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ac0c88db900f588226a06c2d0670c9ef0">reference</a> operator*()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8b69ce24c4135c1155b61a1e3be45327">m_vec</a>-&gt;at(<a href="#a4fd14ed7a676ff310d34bc1360f04419">m_pos</a>); }</span></span></div>

</div>

</div>
</div>

### operator++() {#a5e9c2e89b1cfe99e6bdc3b8420a36ed1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Iterator &amp; GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::operator++ ()</td>
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



<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e9c2e89b1cfe99e6bdc3b8420a36ed1">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a>&amp; <a href="#a5e9c2e89b1cfe99e6bdc3b8420a36ed1">operator++</a>()      { <a href="#a4fd14ed7a676ff310d34bc1360f04419">m_pos</a>++; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">; }</span></span></div>

</div>

</div>
</div>

### operator++() {#a49e00b9084ba7231f29234f939573910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Iterator GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::operator++ (int)</td>
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



<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49e00b9084ba7231f29234f939573910">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a> <a href="#a49e00b9084ba7231f29234f939573910">operator++</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)    { <a href="#a55b4821006a5d1653581dd733ba438f0">Iterator</a> tmp = *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">; ++(*this); </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> tmp; }</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_pos {#a4fd14ed7a676ff310d34bc1360f04419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::m_pos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4fd14ed7a676ff310d34bc1360f04419">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a4fd14ed7a676ff310d34bc1360f04419">m_pos</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a27aed9f3ea67a677964fa51de28a5824">GrowVector&lt; T &gt;::Iterator&lt; GrowVector, T &gt;::operator!=</a> and <a href="#adf9a9358b475317bd816d7b47a0f5cd1">GrowVector&lt; T &gt;::Iterator&lt; GrowVector, T &gt;::operator==</a>.</p>

</div>
</div>

### m\_vec {#a8b69ce24c4135c1155b61a1e3be45327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class C, class I&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">C* GrowVector&lt; T &gt;::Iterator&lt; C, I &gt;::m_vec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8b69ce24c4135c1155b61a1e3be45327">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">        C     *<a href="#a8b69ce24c4135c1155b61a1e3be45327">m_vec</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
