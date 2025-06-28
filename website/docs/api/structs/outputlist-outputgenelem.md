---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/outputlist/outputgenelem
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `OutputGenElem` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct OutputList::OutputGenElem { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ff15d48f2ef2dd3c4331f3b52ce7af8">OutputGenElem</a> (OutputGenIntfPtr &amp;&amp;v)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2574275bc562aee534dea2d0d69ada1b">OutputGenElem</a> (const OutputGenElem &amp;other)</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/outputlist/outputgenelem">OutputGenElem</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a214ab216cf86227161871c767e25894a">operator=</a> (const OutputGenElem &amp;other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdfd6c09a87d2b3f2f82fef1773064c7">setEnabled</a> (bool e)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputlist/#ab96ab5436b6d039364d65aa7b05b37d3">OutputGenIntfPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cccf76e743722b3abedc9106b1d8152">intf</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f0a79681a684027e4db44b3cb7b7500">enabled</a> = true</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::stack&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa32c82630fc16b83b4925744420f0d6b">enabledStack</a></td>
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


<p>Definition at line 319 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### OutputGenElem() {#a0ff15d48f2ef2dd3c4331f3b52ce7af8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputList::OutputGenElem::OutputGenElem (<a href="/web-doxygen/docs/api/classes/outputlist/#ab96ab5436b6d039364d65aa7b05b37d3">OutputGenIntfPtr</a> &amp;&amp; v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputlist-h/#l00321">321</a> of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ff15d48f2ef2dd3c4331f3b52ce7af8">321</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#a0ff15d48f2ef2dd3c4331f3b52ce7af8">OutputGenElem</a>(<a href="/web-doxygen/docs/api/classes/outputlist/#ab96ab5436b6d039364d65aa7b05b37d3">OutputGenIntfPtr</a> &amp;&amp;v) : <a href="#a0cccf76e743722b3abedc9106b1d8152">intf</a>(std::move(v)) {}</span></span></div>

</div>


Reference <a href="#a0cccf76e743722b3abedc9106b1d8152">intf</a>.

Referenced by <a href="#a214ab216cf86227161871c767e25894a">operator=</a> and <a href="#a2574275bc562aee534dea2d0d69ada1b">OutputGenElem</a>.
</div>
</div>

### OutputGenElem() {#a2574275bc562aee534dea2d0d69ada1b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputList::OutputGenElem::OutputGenElem (const <a href="/web-doxygen/docs/api/structs/outputlist/outputgenelem">OutputGenElem</a> &amp; other)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputlist-h/#l00322">322</a> of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2574275bc562aee534dea2d0d69ada1b">322</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a2574275bc562aee534dea2d0d69ada1b">OutputGenElem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a0ff15d48f2ef2dd3c4331f3b52ce7af8">OutputGenElem</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a0cccf76e743722b3abedc9106b1d8152">intf</a> = other.<a href="#a0cccf76e743722b3abedc9106b1d8152">intf</a>-&gt;clone();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a8f0a79681a684027e4db44b3cb7b7500">enabled</a> = other.<a href="#a8f0a79681a684027e4db44b3cb7b7500">enabled</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


References <a href="#a8f0a79681a684027e4db44b3cb7b7500">enabled</a>, <a href="#a0cccf76e743722b3abedc9106b1d8152">intf</a> and <a href="#a0ff15d48f2ef2dd3c4331f3b52ce7af8">OutputGenElem</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a214ab216cf86227161871c767e25894a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputGenElem &amp; OutputList::OutputGenElem::operator= (const <a href="/web-doxygen/docs/api/structs/outputlist/outputgenelem">OutputGenElem</a> &amp; other)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputlist-h/#l00327">327</a> of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a214ab216cf86227161871c767e25894a">327</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a0ff15d48f2ef2dd3c4331f3b52ce7af8">OutputGenElem</a> &amp;<a href="#a214ab216cf86227161871c767e25894a">operator=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a0ff15d48f2ef2dd3c4331f3b52ce7af8">OutputGenElem</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (&amp;other!=</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a0cccf76e743722b3abedc9106b1d8152">intf</a> = other.<a href="#a0cccf76e743722b3abedc9106b1d8152">intf</a>-&gt;clone();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a8f0a79681a684027e4db44b3cb7b7500">enabled</a> = other.<a href="#a8f0a79681a684027e4db44b3cb7b7500">enabled</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


References <a href="#a8f0a79681a684027e4db44b3cb7b7500">enabled</a>, <a href="#a0cccf76e743722b3abedc9106b1d8152">intf</a> and <a href="#a0ff15d48f2ef2dd3c4331f3b52ce7af8">OutputGenElem</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### setEnabled() {#afdfd6c09a87d2b3f2f82fef1773064c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::OutputGenElem::setEnabled (bool e)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputlist-h/#l00337">337</a> of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afdfd6c09a87d2b3f2f82fef1773064c7">337</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afdfd6c09a87d2b3f2f82fef1773064c7">setEnabled</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> e) { <a href="#a8f0a79681a684027e4db44b3cb7b7500">enabled</a> = e &amp;&amp; !<a href="#aa32c82630fc16b83b4925744420f0d6b">enabledStack</a>.empty() ? <a href="#aa32c82630fc16b83b4925744420f0d6b">enabledStack</a>.top() : e; }</span></span></div>

</div>


References <a href="#a8f0a79681a684027e4db44b3cb7b7500">enabled</a> and <a href="#aa32c82630fc16b83b4925744420f0d6b">enabledStack</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### enabled {#a8f0a79681a684027e4db44b3cb7b7500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OutputList::OutputGenElem::enabled = true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputlist-h/#l00338">338</a> of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8f0a79681a684027e4db44b3cb7b7500">338</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8f0a79681a684027e4db44b3cb7b7500">enabled</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a214ab216cf86227161871c767e25894a">operator=</a>, <a href="#a2574275bc562aee534dea2d0d69ada1b">OutputGenElem</a> and <a href="#afdfd6c09a87d2b3f2f82fef1773064c7">setEnabled</a>.
</div>
</div>

### enabledStack {#aa32c82630fc16b83b4925744420f0d6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::stack&lt;bool&gt; OutputList::OutputGenElem::enabledStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputlist-h/#l00339">339</a> of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa32c82630fc16b83b4925744420f0d6b">339</a></span><span class="doxyLineContent"><span class="doxyHighlight">      std::stack&lt;bool&gt; <a href="#aa32c82630fc16b83b4925744420f0d6b">enabledStack</a>;</span></span></div>

</div>


Referenced by <a href="#afdfd6c09a87d2b3f2f82fef1773064c7">setEnabled</a>.
</div>
</div>

### intf {#a0cccf76e743722b3abedc9106b1d8152}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputGenIntfPtr OutputList::OutputGenElem::intf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputlist-h/#l00336">336</a> of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0cccf76e743722b3abedc9106b1d8152">336</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputlist/#ab96ab5436b6d039364d65aa7b05b37d3">OutputGenIntfPtr</a> <a href="#a0cccf76e743722b3abedc9106b1d8152">intf</a>;</span></span></div>

</div>


Referenced by <a href="#a214ab216cf86227161871c767e25894a">operator=</a>, <a href="#a2574275bc562aee534dea2d0d69ada1b">OutputGenElem</a> and <a href="#a0ff15d48f2ef2dd3c4331f3b52ce7af8">OutputGenElem</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
