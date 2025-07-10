---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/typespecifier
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TypeSpecifier` Class Reference

<p>Wrapper class for a number of boolean properties. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class TypeSpecifier { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/types-h">src/types.h</a>&gt;
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc5b5d3a4fe7693a2982eb6de5dacfe">operator==</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf05eb3083ab16aea5ec98f06820f8a0">operator!=</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf48bb190be47d496fd56c7ce9ddd40">TypeSpecifier</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbf2149359d4d4a0f9db4cd57e2b64a8">reset</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adc33a4d3e53f2ef1064cb32f0c3811e9">merge</a> (const TypeSpecifier &amp;other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a253f39d5231d613732dc149a1e00bd55">to_string</a> () const</td>
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

<p>Wrapper class for a number of boolean properties.</p>


<p>The properties are packed together, and initialized to false.</p>


<p>Definition at line 653 of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>


<div class="doxySectionDef">

## Friends

### operator!= {#abf05eb3083ab16aea5ec98f06820f8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool const <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a> &amp; t1, const <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a> &amp; t2</td>
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


<p>Definition at line 676 of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf05eb3083ab16aea5ec98f06820f8a0">676</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#abf05eb3083ab16aea5ec98f06820f8a0">operator!=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a3cf48bb190be47d496fd56c7ce9ddd40">TypeSpecifier</a> &amp;t1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a3cf48bb190be47d496fd56c7ce9ddd40">TypeSpecifier</a> &amp;t2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !(<a href="#a4dc5b5d3a4fe7693a2982eb6de5dacfe">operator==</a>(t1,t2));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a4dc5b5d3a4fe7693a2982eb6de5dacfe">operator==</a> and <a href="#a3cf48bb190be47d496fd56c7ce9ddd40">TypeSpecifier</a>.</p>

</div>
</div>

### operator== {#a4dc5b5d3a4fe7693a2982eb6de5dacfe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend bool const <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a> &amp; t1, const <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a> &amp; t2</td>
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


<p>Definition at line 667 of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4dc5b5d3a4fe7693a2982eb6de5dacfe">667</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4dc5b5d3a4fe7693a2982eb6de5dacfe">operator==</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a3cf48bb190be47d496fd56c7ce9ddd40">TypeSpecifier</a> &amp;t1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a3cf48bb190be47d496fd56c7ce9ddd40">TypeSpecifier</a> &amp;t2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> eq = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define TSPEC(x) eq = eq &amp;&amp; (t1.m_is##x == t2.m_is##x);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/types-h/#a41aa73212f991bad715476690521886c">TYPE_SPECIFIERS</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef TSPEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> eq;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/types-h/#a41aa73212f991bad715476690521886c">TYPE_SPECIFIERS</a> and <a href="#a3cf48bb190be47d496fd56c7ce9ddd40">TypeSpecifier</a>.</p>


<p>Referenced by <a href="#abf05eb3083ab16aea5ec98f06820f8a0">operator!=</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### TypeSpecifier() {#a3cf48bb190be47d496fd56c7ce9ddd40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TypeSpecifier::TypeSpecifier ()</td>
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



<p>Definition at line 656 of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3cf48bb190be47d496fd56c7ce9ddd40">656</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3cf48bb190be47d496fd56c7ce9ddd40">TypeSpecifier</a>() { <a href="#afbf2149359d4d4a0f9db4cd57e2b64a8">reset</a>(); }</span></span></div>

</div>


<p>Reference <a href="#afbf2149359d4d4a0f9db4cd57e2b64a8">reset</a>.</p>


<p>Referenced by <a href="#adc33a4d3e53f2ef1064cb32f0c3811e9">merge</a>, <a href="#abf05eb3083ab16aea5ec98f06820f8a0">operator!=</a> and <a href="#a4dc5b5d3a4fe7693a2982eb6de5dacfe">operator==</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### merge() {#adc33a4d3e53f2ef1064cb32f0c3811e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TypeSpecifier::merge (const <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a> &amp; other)</td>
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



<p>Definition at line 660 of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adc33a4d3e53f2ef1064cb32f0c3811e9">660</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adc33a4d3e53f2ef1064cb32f0c3811e9">merge</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a3cf48bb190be47d496fd56c7ce9ddd40">TypeSpecifier</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define TSPEC(x) m_is##x = m_is##x || other.is##x();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/types-h/#a41aa73212f991bad715476690521886c">TYPE_SPECIFIERS</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef TSPEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/types-h/#a41aa73212f991bad715476690521886c">TYPE_SPECIFIERS</a> and <a href="#a3cf48bb190be47d496fd56c7ce9ddd40">TypeSpecifier</a>.</p>

</div>
</div>

### reset() {#afbf2149359d4d4a0f9db4cd57e2b64a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TypeSpecifier::reset ()</td>
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



<p>Definition at line 658 of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afbf2149359d4d4a0f9db4cd57e2b64a8">658</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afbf2149359d4d4a0f9db4cd57e2b64a8">reset</a>() { std::memset(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">, 0, </span><span class="doxyHighlightKeyword">sizeof</span><span class="doxyHighlight">(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">)); }</span></span></div>

</div>


<p>Referenced by <a href="#a3cf48bb190be47d496fd56c7ce9ddd40">TypeSpecifier</a>.</p>

</div>
</div>

### to\_string() {#a253f39d5231d613732dc149a1e00bd55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string TypeSpecifier::to_string ()</td>
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



<p>Definition at line 682 of file <a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a253f39d5231d613732dc149a1e00bd55">682</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="#a253f39d5231d613732dc149a1e00bd55">to_string</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string result=</span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define TSPEC(x)                                                          \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      if (m_is##x) {                                                      \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">        if (!first) result+=",";                                          \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">        result+=#x; first=false;                                          \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/types-h/#a41aa73212f991bad715476690521886c">TYPE_SPECIFIERS</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#undef TSPEC</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">      result+=</span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/types-h/#a41aa73212f991bad715476690521886c">TYPE_SPECIFIERS</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/fmt/formatter-3bc0763cf07398a7c5644ce192ea65ea/#a5185feae6dcec945c021b1e40ced47f1">fmt::formatter&lt; TypeSpecifier &gt;::format</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a001e5e4b6b99ed83d3333cc3adf5afd2">printNavTree</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/types-h">types.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
