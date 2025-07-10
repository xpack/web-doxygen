---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/reg/match
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Match` Class Reference

<p>Object representing the matching results. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class reg::Match { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/regex-h">src/regex.h</a>&gt;
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ce15d3df1c5aa85342f8949e00a8287">Ex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37a5c2911063058b342cc51cb480c85e">Match</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an empty match object. <a href="#a37a5c2911063058b342cc51cb480c85e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8320717bb5a3371ce6aa32dc0e5a8f39">operator[]</a> (size_t index) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the n-th <a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a> object. <a href="#a8320717bb5a3371ce6aa32dc0e5a8f39">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef72503a2d2337b2f594839ea10c819">position</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the position of the match or std::string::npos if no position is set. <a href="#a8ef72503a2d2337b2f594839ea10c819">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3ac6e9dcc408056ba2e32861da9294e">length</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the position of the match or std::string::npos if no length is set. <a href="#ad3ac6e9dcc408056ba2e32861da9294e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97649b62cb59c9a30ce309559ad0f818">str</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return a string representing the matching part. <a href="#a97649b62cb59c9a30ce309559ad0f818">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b332adf8f8813fda1d938314c92dfb8">prefix</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the part of the string before the match. <a href="#a8b332adf8f8813fda1d938314c92dfb8">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2301e49e73b68b27e4825fc38e04d41">suffix</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Return the part of the string after the match. <a href="#ab2301e49e73b68b27e4825fc38e04d41">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89c66a7065ac811107702a905b37da11">size</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the number of sub matches available in this match. <a href="#a89c66a7065ac811107702a905b37da11">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c65c2d340c94527959a847251d67d1e">init</a> (std::string_view str)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89ab2cb5d0f2b74478440d52453fa414">startCapture</a> (size_t index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b061b3e6c2ef44438814dc864ae0c1d">endCapture</a> (size_t index)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aacef95793e84d76e5c05fdf1b2063fc5">setMatch</a> (size_t pos, size_t len)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1549543d1aeb2b085f589dd3a17835e">m_captureIndex</a> =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string_view</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0be30a011c1bad8e0b50cb5a2998c160">m_insideCapture</a> =false</td>
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

<p>Object representing the matching results.</p>


<p>It consists of an array of <a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a> objects. The first entry of the array represents the whole match, any next elements represent each of the capture ranges.</p>


<p>For example string <span class="doxyComputerOutput">@42</span> and expression <span class="doxyComputerOutput">@(\\d+)</span> will have two Submatches, match[0] will point to the input string as a whole, and match[1] will point to the number 42 only.</p>


<p>Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxySectionDef">

## Friends

### Ex {#a0ce15d3df1c5aa85342f8949e00a8287}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 191 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ce15d3df1c5aa85342f8949e00a8287">191</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight"><a href="#a0ce15d3df1c5aa85342f8949e00a8287">Ex</a>;</span></span></div>

</div>


<p>Reference <a href="#a0ce15d3df1c5aa85342f8949e00a8287">Ex</a>.</p>


<p>Referenced by <a href="#a0ce15d3df1c5aa85342f8949e00a8287">Ex</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Match() {#a37a5c2911063058b342cc51cb480c85e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::Match::Match ()</td>
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

<p>Creates an empty match object.</p>

<p>Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a37a5c2911063058b342cc51cb480c85e">156</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a37a5c2911063058b342cc51cb480c85e">Match</a>() {}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator\[\]() {#a8320717bb5a3371ce6aa32dc0e5a8f39}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const SubMatch &amp; reg::Match::operator[] (size_t index)</td>
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

<p>Returns the n-th <a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a> object.</p>


<p>Note that there is always 1 <a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a> object representing the whole match.</p>


<p>Definition at line 188 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8320717bb5a3371ce6aa32dc0e5a8f39">188</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a> &amp;<a href="#a8320717bb5a3371ce6aa32dc0e5a8f39">operator[]</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>[index]; }</span></span></div>

</div>


<p>Reference <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### length() {#ad3ac6e9dcc408056ba2e32861da9294e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t reg::Match::length ()</td>
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

<p>Returns the position of the match or std::string::npos if no length is set.</p>

<p>Definition at line 162 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad3ac6e9dcc408056ba2e32861da9294e">162</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#ad3ac6e9dcc408056ba2e32861da9294e">length</a>()</span><span class="doxyHighlightKeyword">   const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>[0].length();   }</span></span></div>

</div>


<p>Reference <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a> and <a href="#ab2301e49e73b68b27e4825fc38e04d41">suffix</a>.</p>

</div>
</div>

### position() {#a8ef72503a2d2337b2f594839ea10c819}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t reg::Match::position ()</td>
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

<p>Returns the position of the match or std::string::npos if no position is set.</p>

<p>Definition at line 159 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ef72503a2d2337b2f594839ea10c819">159</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a8ef72503a2d2337b2f594839ea10c819">position</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>[0].position(); }</span></span></div>

</div>


<p>Reference <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.</p>


<p>Referenced by <a href="#a8b332adf8f8813fda1d938314c92dfb8">prefix</a> and <a href="#ab2301e49e73b68b27e4825fc38e04d41">suffix</a>.</p>

</div>
</div>

### prefix() {#a8b332adf8f8813fda1d938314c92dfb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubMatch reg::Match::prefix ()</td>
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

<p>Return the part of the string before the match.</p>

<p>Definition at line 168 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8b332adf8f8813fda1d938314c92dfb8">168</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a> <a href="#a8b332adf8f8813fda1d938314c92dfb8">prefix</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a> m(<a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a>); m.<a href="/web-doxygen/docs/api/classes/reg/submatch/#a5a9307c50ec4361b8f81eccc1953d10a">setMatch</a>(0,<a href="#a8ef72503a2d2337b2f594839ea10c819">position</a>()); </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> m; }</span></span></div>

</div>


<p>References <a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a>, <a href="#a8ef72503a2d2337b2f594839ea10c819">position</a> and <a href="/web-doxygen/docs/api/classes/reg/submatch/#a5a9307c50ec4361b8f81eccc1953d10a">reg::SubMatch::setMatch</a>.</p>

</div>
</div>

### size() {#a89c66a7065ac811107702a905b37da11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t reg::Match::size ()</td>
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

<p>Returns the number of sub matches available in this match.</p>

<p>Definition at line 183 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a89c66a7065ac811107702a905b37da11">183</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a89c66a7065ac811107702a905b37da11">size</a>()</span><span class="doxyHighlightKeyword">     const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.size(); }</span></span></div>

</div>


<p>Reference <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.</p>

</div>
</div>

### str() {#a97649b62cb59c9a30ce309559ad0f818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string reg::Match::str ()</td>
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

<p>Return a string representing the matching part.</p>

<p>Definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97649b62cb59c9a30ce309559ad0f818">165</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="#a97649b62cb59c9a30ce309559ad0f818">str</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::string{<a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>[0].str()}; }</span></span></div>

</div>


<p>Reference <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.</p>


<p>Referenced by <a href="#a9c65c2d340c94527959a847251d67d1e">init</a> and <a href="/web-doxygen/docs/api/files/src/pre-l/#a35e7ee6baadfec49f7e85a2cf14d5deb">initPredefined</a>.</p>

</div>
</div>

### suffix() {#ab2301e49e73b68b27e4825fc38e04d41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SubMatch reg::Match::suffix ()</td>
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

<p>Return the part of the string after the match.</p>

<p>Definition at line 171 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab2301e49e73b68b27e4825fc38e04d41">171</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a> <a href="#ab2301e49e73b68b27e4825fc38e04d41">suffix</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a> m(<a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> e = <a href="#a8ef72503a2d2337b2f594839ea10c819">position</a>()+<a href="#ad3ac6e9dcc408056ba2e32861da9294e">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">        m.<a href="/web-doxygen/docs/api/classes/reg/submatch/#a5a9307c50ec4361b8f81eccc1953d10a">setMatch</a>(e,<a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a>.length()-e);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ad3ac6e9dcc408056ba2e32861da9294e">length</a>, <a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a>, <a href="#a8ef72503a2d2337b2f594839ea10c819">position</a> and <a href="/web-doxygen/docs/api/classes/reg/submatch/#a5a9307c50ec4361b8f81eccc1953d10a">reg::SubMatch::setMatch</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### endCapture() {#a8b061b3e6c2ef44438814dc864ae0c1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reg::Match::endCapture (size_t index)</td>
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



<p>Definition at line 209 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8b061b3e6c2ef44438814dc864ae0c1d">209</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8b061b3e6c2ef44438814dc864ae0c1d">endCapture</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index&gt;<a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.back().position())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ac1549543d1aeb2b085f589dd3a17835e">m_captureIndex</a>=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.back().setEnd(index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a0be30a011c1bad8e0b50cb5a2998c160">m_insideCapture</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ac1549543d1aeb2b085f589dd3a17835e">m_captureIndex</a>, <a href="#a0be30a011c1bad8e0b50cb5a2998c160">m_insideCapture</a> and <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.</p>

</div>
</div>

### init() {#a9c65c2d340c94527959a847251d67d1e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reg::Match::init (std::string_view str)</td>
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



<p>Definition at line 192 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c65c2d340c94527959a847251d67d1e">192</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9c65c2d340c94527959a847251d67d1e">init</a>(std::string_view <a href="#a97649b62cb59c9a30ce309559ad0f818">str</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.emplace_back(<a href="#a97649b62cb59c9a30ce309559ad0f818">str</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a> = <a href="#a97649b62cb59c9a30ce309559ad0f818">str</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a>, <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a> and <a href="#a97649b62cb59c9a30ce309559ad0f818">str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a>.</p>

</div>
</div>

### setMatch() {#aacef95793e84d76e5c05fdf1b2063fc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reg::Match::setMatch (size_t pos, size_t len)</td>
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



<p>Definition at line 218 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aacef95793e84d76e5c05fdf1b2063fc5">218</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aacef95793e84d76e5c05fdf1b2063fc5">setMatch</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>[<a href="#ac1549543d1aeb2b085f589dd3a17835e">m_captureIndex</a>].setMatch(pos,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ac1549543d1aeb2b085f589dd3a17835e">m_captureIndex</a> and <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.</p>

</div>
</div>

### startCapture() {#a89ab2cb5d0f2b74478440d52453fa414}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reg::Match::startCapture (size_t index)</td>
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



<p>Definition at line 198 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a89ab2cb5d0f2b74478440d52453fa414">198</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a89ab2cb5d0f2b74478440d52453fa414">startCapture</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a0be30a011c1bad8e0b50cb5a2998c160">m_insideCapture</a>) </span><span class="doxyHighlightComment">// when backtracking we can re-entry the capture multiple times</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightComment">// only update the index, example `\s*(x)`</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ac1549543d1aeb2b085f589dd3a17835e">m_captureIndex</a> = <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.emplace_back(<a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a0be30a011c1bad8e0b50cb5a2998c160">m_insideCapture</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.back().setStart(index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ac1549543d1aeb2b085f589dd3a17835e">m_captureIndex</a>, <a href="#a0be30a011c1bad8e0b50cb5a2998c160">m_insideCapture</a>, <a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a> and <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_captureIndex {#ac1549543d1aeb2b085f589dd3a17835e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t reg::Match::m_captureIndex =0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 224 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac1549543d1aeb2b085f589dd3a17835e">224</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#ac1549543d1aeb2b085f589dd3a17835e">m_captureIndex</a>=0;</span></span></div>

</div>


<p>Referenced by <a href="#a8b061b3e6c2ef44438814dc864ae0c1d">endCapture</a>, <a href="#aacef95793e84d76e5c05fdf1b2063fc5">setMatch</a> and <a href="#a89ab2cb5d0f2b74478440d52453fa414">startCapture</a>.</p>

</div>
</div>

### m\_insideCapture {#a0be30a011c1bad8e0b50cb5a2998c160}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::Match::m_insideCapture =false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 226 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0be30a011c1bad8e0b50cb5a2998c160">226</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0be30a011c1bad8e0b50cb5a2998c160">m_insideCapture</a>=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a8b061b3e6c2ef44438814dc864ae0c1d">endCapture</a> and <a href="#a89ab2cb5d0f2b74478440d52453fa414">startCapture</a>.</p>

</div>
</div>

### m\_str {#a41c4cc9115ef016ff22c311f01491785}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view reg::Match::m_str</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41c4cc9115ef016ff22c311f01491785">225</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string_view <a href="#a41c4cc9115ef016ff22c311f01491785">m_str</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a9c65c2d340c94527959a847251d67d1e">init</a>, <a href="#a8b332adf8f8813fda1d938314c92dfb8">prefix</a>, <a href="#a89ab2cb5d0f2b74478440d52453fa414">startCapture</a> and <a href="#ab2301e49e73b68b27e4825fc38e04d41">suffix</a>.</p>

</div>
</div>

### m\_subMatches {#aa0f4a2cb8f0612a01cc7aefe8e6fb351}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;SubMatch&gt; reg::Match::m_subMatches</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 223 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">223</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;SubMatch&gt; <a href="#aa0f4a2cb8f0612a01cc7aefe8e6fb351">m_subMatches</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a8b061b3e6c2ef44438814dc864ae0c1d">endCapture</a>, <a href="#a9c65c2d340c94527959a847251d67d1e">init</a>, <a href="#ad3ac6e9dcc408056ba2e32861da9294e">length</a>, <a href="#a8320717bb5a3371ce6aa32dc0e5a8f39">operator[]</a>, <a href="#a8ef72503a2d2337b2f594839ea10c819">position</a>, <a href="#aacef95793e84d76e5c05fdf1b2063fc5">setMatch</a>, <a href="#a89c66a7065ac811107702a905b37da11">size</a>, <a href="#a89ab2cb5d0f2b74478440d52453fa414">startCapture</a> and <a href="#a97649b62cb59c9a30ce309559ad0f818">str</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
