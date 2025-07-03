---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/htmlgenerator/tocstate
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `TocState` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct HtmlGenerator::TocState { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24ecffb6da464b55f6cb283055a2b555">writeIndent</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac55cb6fab4d89747141a689fd61f748">incIndent</a> (TextStream &amp;t, const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a090ee525f877596abeff5d8d1de5d11c">decIndent</a> (TextStream &amp;t, const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dcaa00beacd89595060968814df86f7">level</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cc9e074c1afcf2c0add6fef7fd29f6f">indent</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93e1d78bc5664d59f6b16ae84eb58ca2">maxLevel</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#af473e8b17774fe44ba6746b9e7bff90a">BoolVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97d5697208aa81ff8fc9f52321333a5b">inLi</a></td>
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


<p>Definition at line 352 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### decIndent() {#a090ee525f877596abeff5d8d1de5d11c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::TocState::decIndent (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Definition at line 360 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a090ee525f877596abeff5d8d1de5d11c">360</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a090ee525f877596abeff5d8d1de5d11c">decIndent</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text) { <a href="#a1cc9e074c1afcf2c0add6fef7fd29f6f">indent</a>--; <a href="#a24ecffb6da464b55f6cb283055a2b555">writeIndent</a>(t); t &lt;&lt; text &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">; };</span></span></div>

</div>


<p>References <a href="#a1cc9e074c1afcf2c0add6fef7fd29f6f">indent</a> and <a href="#a24ecffb6da464b55f6cb283055a2b555">writeIndent</a>.</p>

</div>
</div>

### incIndent() {#aac55cb6fab4d89747141a689fd61f748}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::TocState::incIndent (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Definition at line 359 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac55cb6fab4d89747141a689fd61f748">359</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aac55cb6fab4d89747141a689fd61f748">incIndent</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text) { <a href="#a24ecffb6da464b55f6cb283055a2b555">writeIndent</a>(t); t &lt;&lt; text &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">; <a href="#a1cc9e074c1afcf2c0add6fef7fd29f6f">indent</a>++; };</span></span></div>

</div>


<p>References <a href="#a1cc9e074c1afcf2c0add6fef7fd29f6f">indent</a> and <a href="#a24ecffb6da464b55f6cb283055a2b555">writeIndent</a>.</p>

</div>
</div>

### writeIndent() {#a24ecffb6da464b55f6cb283055a2b555}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlGenerator::TocState::writeIndent (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



<p>Definition at line 358 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24ecffb6da464b55f6cb283055a2b555">358</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a24ecffb6da464b55f6cb283055a2b555">writeIndent</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t) { </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;i&lt;<a href="#a1cc9e074c1afcf2c0add6fef7fd29f6f">indent</a>*2;i++) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">; };</span></span></div>

</div>


<p>Reference <a href="#a1cc9e074c1afcf2c0add6fef7fd29f6f">indent</a>.</p>


<p>Referenced by <a href="#a090ee525f877596abeff5d8d1de5d11c">decIndent</a> and <a href="#aac55cb6fab4d89747141a689fd61f748">incIndent</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### indent {#a1cc9e074c1afcf2c0add6fef7fd29f6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int HtmlGenerator::TocState::indent = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 355 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1cc9e074c1afcf2c0add6fef7fd29f6f">355</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a1cc9e074c1afcf2c0add6fef7fd29f6f">indent</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a090ee525f877596abeff5d8d1de5d11c">decIndent</a>, <a href="#aac55cb6fab4d89747141a689fd61f748">incIndent</a> and <a href="#a24ecffb6da464b55f6cb283055a2b555">writeIndent</a>.</p>

</div>
</div>

### inLi {#a97d5697208aa81ff8fc9f52321333a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">BoolVector HtmlGenerator::TocState::inLi</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 357 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97d5697208aa81ff8fc9f52321333a5b">357</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/containers-h/#af473e8b17774fe44ba6746b9e7bff90a">BoolVector</a> <a href="#a97d5697208aa81ff8fc9f52321333a5b">inLi</a>;</span></span></div>

</div>

</div>
</div>

### level {#a6dcaa00beacd89595060968814df86f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int HtmlGenerator::TocState::level = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 354 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6dcaa00beacd89595060968814df86f7">354</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a6dcaa00beacd89595060968814df86f7">level</a> = 0;</span></span></div>

</div>

</div>
</div>

### maxLevel {#a93e1d78bc5664d59f6b16ae84eb58ca2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int HtmlGenerator::TocState::maxLevel = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 356 of file <a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a93e1d78bc5664d59f6b16ae84eb58ca2">356</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a93e1d78bc5664d59f6b16ae84eb58ca2">maxLevel</a> = 0;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
