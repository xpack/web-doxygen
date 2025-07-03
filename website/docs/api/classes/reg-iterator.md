---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/reg/iterator
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Iterator` Class Reference

<p>Class to iterate through matches. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class reg::Iterator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/regex-h">src/regex.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b099961d63d2f65eb8d1b7d2936c4c7">value_type</a> = <a href="/web-doxygen/docs/api/classes/reg/match">Match</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6424b2f931a5cb860a7d60bf777b3c03">difference_type</a> = std::ptrdiff_t</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae79f435778ab5f63ae779a81cd746d98">pointer</a> = <a href="#a8b099961d63d2f65eb8d1b7d2936c4c7">value_type</a> *</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17a0714961a7aaf703925fb2c2c2cede">reference</a> = <a href="#a8b099961d63d2f65eb8d1b7d2936c4c7">value_type</a> &amp;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fb1af3a9c9e6ec4913f40548eba2352">iterator_category</a> = std::forward_iterator_tag</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c2aec67346b247815d974cad0bfc2a">Iterator</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an end-of-sequence iterator. <a href="#a87c2aec67346b247815d974cad0bfc2a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd6bea314f4c0b0b7f44fd80d4c1db20">Iterator</a> (std::string_view str, const Ex &amp;re, size_t pos=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates an iterator for input string <em>str</em>, using regular expression <em>re</em> to search. <a href="#abd6bea314f4c0b0b7f44fd80d4c1db20">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b23469c2d102e4747e43a3fa6470d34">Iterator</a> (std::string &amp;&amp;str, const Ex &amp;re)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54d6b3d9d07a1f0f828654aef2ad8ce0">Iterator</a> (const std::string &amp;str, Ex &amp;&amp;re)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a219f1d3fc2e92b0901d2ac8b94e31be3">Iterator</a> (std::string &amp;&amp;str, Ex &amp;&amp;re)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad00ffd6c0f81540663118248ca9f1aa3">operator==</a> (const Iterator &amp;rhs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the iterators point to the same match (or both are end-of-sequence iterators) <a href="#ad00ffd6c0f81540663118248ca9f1aa3">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0ae906d2bb88ff783d099521209753f">operator!=</a> (const Iterator &amp;rhs) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if the iterators are not pointing to the same match. <a href="#af0ae906d2bb88ff783d099521209753f">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="#a8b099961d63d2f65eb8d1b7d2936c4c7">value_type</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1554335044a2747390e3e94b7f220575">operator*</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a reference to the current match. <a href="#a1554335044a2747390e3e94b7f220575">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="#a8b099961d63d2f65eb8d1b7d2936c4c7">value_type</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d0e5734c6f0d6026964916052bf35ac">operator-&gt;</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns a pointer to the current match. <a href="#a8d0e5734c6f0d6026964916052bf35ac">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/reg/iterator">Iterator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a402252cc0f8cbd8dcda1a3b1dd046a5f">operator++</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Advances the iterator to the next match. <a href="#a402252cc0f8cbd8dcda1a3b1dd046a5f">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af06b7b83aaebb6a7966f4232a613bfc3">findNext</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string_view</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95fadf06dfffc63a2ce6996b7ad8e51c">m_str</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebd291f5387d2877957ee97b04ec099c">m_re</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a> = std::string::npos</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/reg/match">Match</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa58bdff90e2e70b4f24af28daa8ce601">m_match</a></td>
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

<p>Class to iterate through matches.</p>

<p>Definition at line 231 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### difference\_type {#a6424b2f931a5cb860a7d60bf777b3c03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using reg::Iterator::difference_type =  std::ptrdiff_t</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6424b2f931a5cb860a7d60bf777b3c03">235</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a6424b2f931a5cb860a7d60bf777b3c03">difference_type</a> = std::ptrdiff_t;</span></span></div>

</div>

</div>
</div>

### iterator\_category {#a5fb1af3a9c9e6ec4913f40548eba2352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using reg::Iterator::iterator_category =  std::forward_iterator_tag</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 238 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fb1af3a9c9e6ec4913f40548eba2352">238</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a5fb1af3a9c9e6ec4913f40548eba2352">iterator_category</a> = std::forward_iterator_tag;</span></span></div>

</div>

</div>
</div>

### pointer {#ae79f435778ab5f63ae779a81cd746d98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using reg::Iterator::pointer =  value_type*</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 236 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae79f435778ab5f63ae779a81cd746d98">236</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ae79f435778ab5f63ae779a81cd746d98">pointer</a> = <a href="#a8b099961d63d2f65eb8d1b7d2936c4c7">value_type</a>*;</span></span></div>

</div>

</div>
</div>

### reference {#a17a0714961a7aaf703925fb2c2c2cede}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using reg::Iterator::reference =  value_type&amp;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 237 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a17a0714961a7aaf703925fb2c2c2cede">237</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a17a0714961a7aaf703925fb2c2c2cede">reference</a> = <a href="#a8b099961d63d2f65eb8d1b7d2936c4c7">value_type</a>&amp;;</span></span></div>

</div>

</div>
</div>

### value\_type {#a8b099961d63d2f65eb8d1b7d2936c4c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using reg::Iterator::value_type =  Match</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8b099961d63d2f65eb8d1b7d2936c4c7">234</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a8b099961d63d2f65eb8d1b7d2936c4c7">value_type</a> = <a href="/web-doxygen/docs/api/classes/reg/match">Match</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Iterator() {#a87c2aec67346b247815d974cad0bfc2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::Iterator::Iterator ()</td>
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

<p>Creates an end-of-sequence iterator.</p>

<p>Definition at line 241 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87c2aec67346b247815d974cad0bfc2a">241</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a87c2aec67346b247815d974cad0bfc2a">Iterator</a>() {}</span></span></div>

</div>


<p>Referenced by <a href="#af0ae906d2bb88ff783d099521209753f">operator!=</a>, <a href="#a402252cc0f8cbd8dcda1a3b1dd046a5f">operator++</a> and <a href="#ad00ffd6c0f81540663118248ca9f1aa3">operator==</a>.</p>

</div>
</div>

### Iterator() {#abd6bea314f4c0b0b7f44fd80d4c1db20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::Iterator::Iterator (std::string_view str, const <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp; re, size_t pos=0)</td>
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

<p>Creates an iterator for input string <em>str</em>, using regular expression <em>re</em> to search.</p>



:::info
<p>the string and regular expression objects should remain valid while iterating.</p>
:::


<p>Definition at line 246 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd6bea314f4c0b0b7f44fd80d4c1db20">246</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#abd6bea314f4c0b0b7f44fd80d4c1db20">Iterator</a>(std::string_view str, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp;re, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="#a95fadf06dfffc63a2ce6996b7ad8e51c">m_str</a>(str), <a href="#aebd291f5387d2877957ee97b04ec099c">m_re</a>(&amp;re), <a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>(pos) { <a href="#af06b7b83aaebb6a7966f4232a613bfc3">findNext</a>(); }</span></span></div>

</div>


<p>References <a href="#af06b7b83aaebb6a7966f4232a613bfc3">findNext</a>, <a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>, <a href="#aebd291f5387d2877957ee97b04ec099c">m_re</a> and <a href="#a95fadf06dfffc63a2ce6996b7ad8e51c">m_str</a>.</p>

</div>
</div>

### Iterator() {#a0b23469c2d102e4747e43a3fa6470d34}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::Iterator::Iterator (std::string &amp;&amp; str, const <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp; re)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 251 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

</div>
</div>

### Iterator() {#a54d6b3d9d07a1f0f828654aef2ad8ce0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::Iterator::Iterator (const std::string &amp; str, <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp;&amp; re)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 252 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

</div>
</div>

### Iterator() {#a219f1d3fc2e92b0901d2ac8b94e31be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::Iterator::Iterator (std::string &amp;&amp; str, <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp;&amp; re)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 253 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator-&gt;() {#a8d0e5734c6f0d6026964916052bf35ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const value_type * reg::Iterator::operator-&gt; ()</td>
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

<p>Returns a pointer to the current match.</p>

<p>Definition at line 265 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8d0e5734c6f0d6026964916052bf35ac">265</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a8b099961d63d2f65eb8d1b7d2936c4c7">value_type</a> *<a href="#a8d0e5734c6f0d6026964916052bf35ac">operator-&gt;</a>()</span><span class="doxyHighlightKeyword">       const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#aa58bdff90e2e70b4f24af28daa8ce601">m_match</a>;  }</span></span></div>

</div>


<p>Reference <a href="#aa58bdff90e2e70b4f24af28daa8ce601">m_match</a>.</p>

</div>
</div>

### operator!=() {#af0ae906d2bb88ff783d099521209753f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::Iterator::operator!= (const <a href="/web-doxygen/docs/api/classes/reg/iterator">Iterator</a> &amp; rhs)</td>
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

<p>Returns true if the iterators are not pointing to the same match.</p>

<p>Definition at line 259 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af0ae906d2bb88ff783d099521209753f">259</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af0ae906d2bb88ff783d099521209753f">operator!=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a87c2aec67346b247815d974cad0bfc2a">Iterator</a> &amp;rhs)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> rhs.<a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>!=<a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>; }</span></span></div>

</div>


<p>References <a href="#a87c2aec67346b247815d974cad0bfc2a">Iterator</a> and <a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>.</p>

</div>
</div>

### operator\*() {#a1554335044a2747390e3e94b7f220575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const value_type &amp; reg::Iterator::operator* ()</td>
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

<p>Returns a reference to the current match.</p>

<p>Definition at line 262 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1554335044a2747390e3e94b7f220575">262</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a8b099961d63d2f65eb8d1b7d2936c4c7">value_type</a> &amp;<a href="#a1554335044a2747390e3e94b7f220575">operator*</a>()</span><span class="doxyHighlightKeyword">        const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa58bdff90e2e70b4f24af28daa8ce601">m_match</a>; }</span></span></div>

</div>


<p>Reference <a href="#aa58bdff90e2e70b4f24af28daa8ce601">m_match</a>.</p>

</div>
</div>

### operator++() {#a402252cc0f8cbd8dcda1a3b1dd046a5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Iterator &amp; reg::Iterator::operator++ ()</td>
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

<p>Advances the iterator to the next match.</p>

<p>Definition at line 268 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a402252cc0f8cbd8dcda1a3b1dd046a5f">268</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a87c2aec67346b247815d974cad0bfc2a">Iterator</a> &amp;<a href="#a402252cc0f8cbd8dcda1a3b1dd046a5f">operator++</a>() { <a href="#af06b7b83aaebb6a7966f4232a613bfc3">findNext</a>(); </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">; }</span></span></div>

</div>


<p>References <a href="#af06b7b83aaebb6a7966f4232a613bfc3">findNext</a> and <a href="#a87c2aec67346b247815d974cad0bfc2a">Iterator</a>.</p>

</div>
</div>

### operator==() {#ad00ffd6c0f81540663118248ca9f1aa3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::Iterator::operator== (const <a href="/web-doxygen/docs/api/classes/reg/iterator">Iterator</a> &amp; rhs)</td>
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

<p>Returns true if the iterators point to the same match (or both are end-of-sequence iterators)</p>

<p>Definition at line 256 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad00ffd6c0f81540663118248ca9f1aa3">256</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad00ffd6c0f81540663118248ca9f1aa3">operator==</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a87c2aec67346b247815d974cad0bfc2a">Iterator</a> &amp;rhs)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> rhs.<a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>==<a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>; }</span></span></div>

</div>


<p>References <a href="#a87c2aec67346b247815d974cad0bfc2a">Iterator</a> and <a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findNext() {#af06b7b83aaebb6a7966f4232a613bfc3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reg::Iterator::findNext ()</td>
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



<p>Definition at line 271 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af06b7b83aaebb6a7966f4232a613bfc3">271</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af06b7b83aaebb6a7966f4232a613bfc3">findNext</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#aebd291f5387d2877957ee97b04ec099c">m_re</a> || <a href="#a95fadf06dfffc63a2ce6996b7ad8e51c">m_str</a>.empty()) { <a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>=std::string::npos; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; } </span><span class="doxyHighlightComment">// end marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aebd291f5387d2877957ee97b04ec099c">m_re</a>-&gt;match(<a href="#a95fadf06dfffc63a2ce6996b7ad8e51c">m_str</a>,<a href="#aa58bdff90e2e70b4f24af28daa8ce601">m_match</a>,<a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>=<a href="#aa58bdff90e2e70b4f24af28daa8ce601">m_match</a>.position()+<a href="#aa58bdff90e2e70b4f24af28daa8ce601">m_match</a>.length(); </span><span class="doxyHighlightComment">// update m_pos to point beyond last match</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// no more matches, make the iterator point to the 'end-of-sequence'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>=std::string::npos;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aa58bdff90e2e70b4f24af28daa8ce601">m_match</a>, <a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a>, <a href="#aebd291f5387d2877957ee97b04ec099c">m_re</a> and <a href="#a95fadf06dfffc63a2ce6996b7ad8e51c">m_str</a>.</p>


<p>Referenced by <a href="#abd6bea314f4c0b0b7f44fd80d4c1db20">Iterator</a> and <a href="#a402252cc0f8cbd8dcda1a3b1dd046a5f">operator++</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_match {#aa58bdff90e2e70b4f24af28daa8ce601}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Match reg::Iterator::m_match</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 286 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa58bdff90e2e70b4f24af28daa8ce601">286</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/match">Match</a> <a href="#aa58bdff90e2e70b4f24af28daa8ce601">m_match</a>;</span></span></div>

</div>


<p>Referenced by <a href="#af06b7b83aaebb6a7966f4232a613bfc3">findNext</a>, <a href="#a1554335044a2747390e3e94b7f220575">operator*</a> and <a href="#a8d0e5734c6f0d6026964916052bf35ac">operator-&gt;</a>.</p>

</div>
</div>

### m\_pos {#a51b9b1ce207fe269f65a68cb701d8cdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t reg::Iterator::m_pos = std::string::npos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 285 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a51b9b1ce207fe269f65a68cb701d8cdf">285</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a51b9b1ce207fe269f65a68cb701d8cdf">m_pos</a> = std::string::npos;</span></span></div>

</div>


<p>Referenced by <a href="#af06b7b83aaebb6a7966f4232a613bfc3">findNext</a>, <a href="#abd6bea314f4c0b0b7f44fd80d4c1db20">Iterator</a>, <a href="#af0ae906d2bb88ff783d099521209753f">operator!=</a> and <a href="#ad00ffd6c0f81540663118248ca9f1aa3">operator==</a>.</p>

</div>
</div>

### m\_re {#aebd291f5387d2877957ee97b04ec099c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Ex* reg::Iterator::m_re = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 284 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebd291f5387d2877957ee97b04ec099c">284</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> *<a href="#aebd291f5387d2877957ee97b04ec099c">m_re</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#af06b7b83aaebb6a7966f4232a613bfc3">findNext</a> and <a href="#abd6bea314f4c0b0b7f44fd80d4c1db20">Iterator</a>.</p>

</div>
</div>

### m\_str {#a95fadf06dfffc63a2ce6996b7ad8e51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view reg::Iterator::m_str</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 283 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a95fadf06dfffc63a2ce6996b7ad8e51c">283</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string_view <a href="#a95fadf06dfffc63a2ce6996b7ad8e51c">m_str</a>;</span></span></div>

</div>


<p>Referenced by <a href="#af06b7b83aaebb6a7966f4232a613bfc3">findNext</a> and <a href="#abd6bea314f4c0b0b7f44fd80d4c1db20">Iterator</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
