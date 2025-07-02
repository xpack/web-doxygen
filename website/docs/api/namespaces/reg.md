---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/namespaces/reg
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - namespace
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `reg` Namespace Reference

Namespace for the regular expression functions. <a href="#details">More...</a>

## Definition

<div class="doxyDefinition">
namespace reg { ... }
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class representing a regular expression. <a href="/web-doxygen/docs/api/classes/reg/ex/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/reg/iterator">Iterator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class to iterate through matches. <a href="/web-doxygen/docs/api/classes/reg/iterator/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/reg/match">Match</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Object representing the matching results. <a href="/web-doxygen/docs/api/classes/reg/match/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class representing a token in the compiled regular expression token stream. <a href="/web-doxygen/docs/api/classes/reg/ptoken/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/reg/submatch">SubMatch</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Object representing the match results of a capture range. <a href="/web-doxygen/docs/api/classes/reg/submatch/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6d291c9b035591b3bc2373dfbb14315">isspace</a> (char c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10c804e03b6d547a3748c3042fd5120b">isalpha</a> (char c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ff1342d768df1b4b668b072a33863f">isdigit</a> (char c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae874a7238f39cd3a0510485027015ef5">isalnum</a> (char c)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470992837f9356c9ed07fb0913072ac2">wildcard2regex</a> (std::string_view pattern)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a168f937e54607f4cf5597fa8e5aabcb7">search</a> (std::string_view str, Match &amp;match, const Ex &amp;re, size_t pos=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Search in a given string <em>str</em> starting at position <em>pos</em> for a match against regular expression <em>re</em>. <a href="#a168f937e54607f4cf5597fa8e5aabcb7">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d1ef4b86632c8deaa796bf008205ff9">search</a> (std::string_view str, const Ex &amp;re, size_t pos=0)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Search in a given string <em>str</em> starting at position <em>pos</em> for a match against regular expression <em>re</em>. <a href="#a4d1ef4b86632c8deaa796bf008205ff9">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a> (std::string_view str, Match &amp;match, const Ex &amp;re)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Matches a given string <em>str</em> for a match against regular expression <em>re</em>. <a href="#abd83bf57cdc053d40135b7c8f211f2b9">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64421aecc141803690cdb0d6d235354b">match</a> (std::string_view str, const Ex &amp;re)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Matches a given string <em>str</em> for a match against regular expression <em>re</em>. <a href="#a64421aecc141803690cdb0d6d235354b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6913d787be9fe9992c8804af851fab9">replace</a> (std::string_view str, const Ex &amp;re, std::string_view replacement)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Searching in a given input string <em>for</em> parts that match regular expression <em>re</em> and replaces those parts by string <em>replacement</em>. <a href="#ab6913d787be9fe9992c8804af851fab9">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

Namespace for the regular expression functions.

<div class="doxySectionDef">

## Functions

### isalnum() {#ae874a7238f39cd3a0510485027015ef5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::isalnum (char c)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae874a7238f39cd3a0510485027015ef5">48</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae874a7238f39cd3a0510485027015ef5">isalnum</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a10c804e03b6d547a3748c3042fd5120b">isalpha</a>(c) || <a href="#af7ff1342d768df1b4b668b072a33863f">isdigit</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a10c804e03b6d547a3748c3042fd5120b">isalpha</a> and <a href="#af7ff1342d768df1b4b668b072a33863f">isdigit</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a>.
</div>
</div>

### isalpha() {#a10c804e03b6d547a3748c3042fd5120b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::isalpha (char c)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a10c804e03b6d547a3748c3042fd5120b">38</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a10c804e03b6d547a3748c3042fd5120b">isalpha</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(c)&gt;=128 || (c&gt;=</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">) || (c&gt;=</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'Z'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="#ae874a7238f39cd3a0510485027015ef5">isalnum</a> and <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a>.
</div>
</div>

### isdigit() {#af7ff1342d768df1b4b668b072a33863f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::isdigit (char c)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7ff1342d768df1b4b668b072a33863f">43</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af7ff1342d768df1b4b668b072a33863f">isdigit</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c&gt;=</span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="#ae874a7238f39cd3a0510485027015ef5">isalnum</a> and <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a>.
</div>
</div>

### isspace() {#ad6d291c9b035591b3bc2373dfbb14315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::isspace (char c)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 33 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6d291c9b035591b3bc2373dfbb14315">33</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad6d291c9b035591b3bc2373dfbb14315">isspace</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\r'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a>.
</div>
</div>

### match() {#abd83bf57cdc053d40135b7c8f211f2b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::match (std::string_view str, <a href="/web-doxygen/docs/api/classes/reg/match">Match</a> &amp; match, const <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp; re)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Matches a given string <em>str</em> for a match against regular expression <em>re</em>.


Returns true iff a match was found for the whole string. Any capture groups are returned via the <em>match</em> object.

Definition at line 759 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd83bf57cdc053d40135b7c8f211f2b9">759</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>(std::string_view str,<a href="/web-doxygen/docs/api/classes/reg/match">Match</a> &amp;<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp;re)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> re.<a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>(str,<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>,0) &amp;&amp; <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.position()==0 &amp;&amp; <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.length()==str.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">reg::Ex::match</a> and <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#ad9d60769e8d4d67f018bc58c3e7b4e6f">dateTimeFromString</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#abc7e7b10db0467ec67569096d637bf01">endBrief</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0ab63cb2f20e16fa82b9b687d2b4b00">genericPatternMatch</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad8f45edef0c9f7b3b0468e6fdb7cef71">getFilterFromList</a>, <a href="/web-doxygen/docs/api/classes/docparser/#abf46a000544ae1a4f45df6430cd3e6bf">DocParser::handleStyleArgument</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a6a0f5ef9f02fff9ab8ad1b70709cd887">VhdlDocGen::isNumber</a>, <a href="#a64421aecc141803690cdb0d6d235354b">match</a>, <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>, <a href="#ab6913d787be9fe9992c8804af851fab9">replace</a>, <a href="#a4d1ef4b86632c8deaa796bf008205ff9">search</a>, <a href="#a168f937e54607f4cf5597fa8e5aabcb7">search</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a3de3cea0489d29101ce232bbc41789da">setOutput</a> and <a href="/web-doxygen/docs/api/classes/layoutparser/#ae1e94d4f205f79a8b052e4140d575cb9">LayoutParser::startLayout</a>.
</div>
</div>

### match() {#a64421aecc141803690cdb0d6d235354b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::match (std::string_view str, const <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp; re)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Matches a given string <em>str</em> for a match against regular expression <em>re</em>.


Returns true iff a match was found for the whole string.

Definition at line 764 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64421aecc141803690cdb0d6d235354b">764</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>(std::string_view str,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp;re)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/reg/match">Match</a> <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> re.<a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>(str,<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>,0) &amp;&amp; <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.position()==0 &amp;&amp; <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.length()==str.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">reg::Ex::match</a> and <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.
</div>
</div>

### replace() {#ab6913d787be9fe9992c8804af851fab9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string reg::replace (std::string_view str, const <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp; re, std::string_view replacement)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Searching in a given input string <em>for</em> parts that match regular expression <em>re</em> and replaces those parts by string <em>replacement</em>.

Definition at line 770 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6913d787be9fe9992c8804af851fab9">770</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="#ab6913d787be9fe9992c8804af851fab9">replace</a>(std::string_view str,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp;re,std::string_view replacement)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/reg/match">Match</a> <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> p=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (re.<a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>(str,<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>,p))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.position();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l=<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;p) result+=str.substr(p,i-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">    result+=replacement;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">    p=i+l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p&lt;str.length()) result+=str.substr(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">reg::Ex::match</a> and <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4892ca19efc7055ce4b5c3004ce550ed">VhdlDocGen::addBaseClass</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a9b95266661529a9ec041d5e91f4c302f">FlowChart::printNode</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#af4b3385c65dda5f0cd99eb8c122c8eef">replaceAnonymousScopes</a>.
</div>
</div>

### search() {#a168f937e54607f4cf5597fa8e5aabcb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::search (std::string_view str, <a href="/web-doxygen/docs/api/classes/reg/match">Match</a> &amp; match, const <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp; re, size_t pos=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Search in a given string <em>str</em> starting at position <em>pos</em> for a match against regular expression <em>re</em>.


Returns true iff a match was found. Details of what part of the string has matched is returned via the <em>match</em> object.

An example to show how to match all identifiers in a string.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re(R</span><span class="doxyHighlightStringLiteral">"(\a\w*)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">std::string = u8</span><span class="doxyHighlightStringLiteral">"void(Func是&lt;B_C::Códe42&gt;(42));"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(str,<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>,re,pos))</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  std::cout &lt;&lt; <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.str() &lt;&lt; std::endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">  pos=<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.position()+<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


produces:

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">Func是</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">B_C</span></span></div>
<div class="doxyCodeLine"><span class="doxyNoLineNumber">&nbsp;</span><span class="doxyLineContent"><span class="doxyHighlight">Códe42</span></span></div>

</div>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd><a href="/web-doxygen/docs/api/classes/reg/ex/#a54ed63c6793f8b7f2e026c26f12d4e67">Ex::Ex()</a> for <a href="/web-doxygen/docs/api/namespaces/details">details</a> on the regular expression patterns.</dd>
</dl>


Definition at line 748 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a168f937e54607f4cf5597fa8e5aabcb7">748</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a168f937e54607f4cf5597fa8e5aabcb7">search</a>(std::string_view str,<a href="/web-doxygen/docs/api/classes/reg/match">Match</a> &amp;<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp;re,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> re.<a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>(str,<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>,pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">reg::Ex::match</a> and <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmlhelpindex/#a70d9d3885e2b3e6a8587e6c59e02afa0">HtmlHelpIndex::addItem</a>, <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#ad1fa14f7ebd8d6adedcac12a2fb83ae1">addValidAliasToMap</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#acbc401cf2a803e0e3517389a8a1a5f2e">expandAliasRec</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a46231fc8d72391f38170f184dd956ed1">Markdown::Private::extractTitleId</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e693bc88f52ca1575ff19ce054824c6">findFunctionPtr</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0b4385a8257f0b917af2bc2a093c6c7b">findIndex</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a371cb64a5cbed0c787cec472f0b04857">MemberDefImpl::getClassDefOfAnonymousType</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#a10998c967b5e151acf3dad299deb0bc9">FormulaManager::initFromRepository</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab17d77238a46be34e30fc71ed51db35a">insertDimension</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a36e764c0a931ef05c53d3695489d198e">loadExtensions</a>, <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp/#a1a60858edb01bcbd780025cecdf65c8f">loadStylesheet</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10e8f1fbd720c602f867aa536e450462">runQHelpGenerator</a>, <a href="/web-doxygen/docs/api/structs/styledata/#a7a9ef51c3d04534f0d123bc771ab3367">StyleData::setStyle</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a0fcfb1e72d24be27533f0a69fd651264">simplifyTypeForTable</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#ada088a153d3ab756e5be8bd628b10e9a">splitKnRArg</a>, <a href="/web-doxygen/docs/api/structs/styledata/#afa4e839cadb0aa89001d0a3b45845ce9">StyleData::StyleData</a>, <a href="/web-doxygen/docs/api/classes/dotattributes/#a379cba80b5c667d8d41d85426c4f5376">DotAttributes::updateValue</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### search() {#a4d1ef4b86632c8deaa796bf008205ff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::search (std::string_view str, const <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp; re, size_t pos=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Search in a given string <em>str</em> starting at position <em>pos</em> for a match against regular expression <em>re</em>.


Returns true iff a match was found.

Definition at line 753 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4d1ef4b86632c8deaa796bf008205ff9">753</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a168f937e54607f4cf5597fa8e5aabcb7">search</a>(std::string_view str,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">Ex</a> &amp;re,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/reg/match">Match</a> <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> re.<a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">match</a>(str,<a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>,pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">reg::Ex::match</a> and <a href="#abd83bf57cdc053d40135b7c8f211f2b9">match</a>.
</div>
</div>

### wildcard2regex() {#a470992837f9356c9ed07fb0913072ac2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string reg::wildcard2regex (std::string_view pattern)</td>
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



Definition at line 649 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a470992837f9356c9ed07fb0913072ac2">649</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::string <a href="#a470992837f9356c9ed07fb0913072ac2">wildcard2regex</a>(std::string_view pattern)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string result=</span><span class="doxyHighlightStringLiteral">"^"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// match start of input</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">  result.reserve(pattern.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;pattern.length();i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=pattern[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=</span><span class="doxyHighlightStringLiteral">".*"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// '*' =&gt; '.*'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'?'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// '?' =&gt; '.'</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'+'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">         result+=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">; result+=c;  </span><span class="doxyHighlightComment">// escape</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;pattern.length()-1 &amp;&amp; pattern[i+1]==</span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// don't escape ^ after [</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">           result+=</span><span class="doxyHighlightStringLiteral">"[^"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">           i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">         {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">           result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">         }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:  </span><span class="doxyHighlightComment">// just copy</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">  result+=</span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// match end of input</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/reg/ex/#a54ed63c6793f8b7f2e026c26f12d4e67">reg::Ex::Ex</a>.
</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
