---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/reg/ex
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Ex` Class Reference

<p>Class representing a regular expression. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class reg::Ex { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/regex-h">src/regex.h</a>&gt;
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Mode { <a href="#a8c11e4a47acf40a6747e2709961acdf9">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Matching algorithm. <a href="#a8c11e4a47acf40a6747e2709961acdf9">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54ed63c6793f8b7f2e026c26f12d4e67">Ex</a> (std::string_view pattern, Mode mode=Mode::RegEx)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a regular expression object given the pattern as a string. <a href="#a54ed63c6793f8b7f2e026c26f12d4e67">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a197664abdebf160b5b621c3a78c01cf7">~Ex</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Destroys the regular expression object. <a href="#a197664abdebf160b5b621c3a78c01cf7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45dcd4878848bcefa4894aa48a2d9b83">match</a> (std::string_view str, Match &amp;match, size_t pos=0) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Check if a given string matches this regular expression. <a href="#a45dcd4878848bcefa4894aa48a2d9b83">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab26ac71412d978b0a03ac996da2beb74">isValid</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/reg/ex/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a></td>
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

<p>Class representing a regular expression.</p>


<p>It has a similar API as <span class="doxyComputerOutput">std::regex</span>, but is much faster (and also somewhat more limited).</p>

<p>Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### Mode {#a8c11e4a47acf40a6747e2709961acdf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class reg::Ex::Mode </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Matching algorithm.</p>

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RegEx<a id="a8c11e4a47acf40a6747e2709961acdf9aaa3c0312d71dacb7f28dd70f21d32ac0"></a></td>
<td class="doxyEnumItemDescription"><p>full regular expression</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Wildcard<a id="a8c11e4a47acf40a6747e2709961acdf9ac4a0dbaac3bd0f3bf581ad822f5fb4b4"></a></td>
<td class="doxyEnumItemDescription"><p>simple globbing pattern</p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/regex-h/#l00042">42</a> of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c11e4a47acf40a6747e2709961acdf9aaa3c0312d71dacb7f28dd70f21d32ac0">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a8c11e4a47acf40a6747e2709961acdf9aaa3c0312d71dacb7f28dd70f21d32ac0">RegEx</a>,    </span><span class="doxyHighlightComment">/**&lt; full regular expression. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c11e4a47acf40a6747e2709961acdf9ac4a0dbaac3bd0f3bf581ad822f5fb4b4">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a8c11e4a47acf40a6747e2709961acdf9ac4a0dbaac3bd0f3bf581ad822f5fb4b4">Wildcard</a>  </span><span class="doxyHighlightComment">/**&lt; simple globbing pattern. */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### Ex() {#a54ed63c6793f8b7f2e026c26f12d4e67}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::Ex::Ex (std::string_view pattern, <a href="#a8c11e4a47acf40a6747e2709961acdf9">Mode</a> mode=<a href="#a8c11e4a47acf40a6747e2709961acdf9aaa3c0312d71dacb7f28dd70f21d32ac0">Mode::RegEx</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Creates a regular expression object given the pattern as a string.</p>


<p>Two modes of matching are supported: RegEx and Wildcard</p>

<p>The following special characters are supported in <a href="#a8c11e4a47acf40a6747e2709961acdf9aaa3c0312d71dacb7f28dd70f21d32ac0">Mode::RegEx</a> mode.</p>

<ul class="doxyList ">
<li><span class="doxyComputerOutput">c</span> matches character <span class="doxyComputerOutput">c</span></li>
<li><span class="doxyComputerOutput">.</span> matches any character</li>
<li><span class="doxyComputerOutput">^</span> matches the start of the input</li>
<li><span class="doxyComputerOutput">$</span> matches the end of the input</li>
<li><span class="doxyComputerOutput">\&lt;</span> matches the start of a word</li>
<li><span class="doxyComputerOutput">\&gt;</span> matches the end of a word</li>
<li><span class="doxyComputerOutput">[]</span> matches a set of characters</li>
<li><span class="doxyComputerOutput">x*</span> matches a sequence of zero or more <span class="doxyComputerOutput">x</span>'s</li>
<li><span class="doxyComputerOutput">x+</span> matches a sequence of one or more <span class="doxyComputerOutput">x</span>'s</li>
<li><span class="doxyComputerOutput">x?</span> matches an optional <span class="doxyComputerOutput">x</span></li>
<li><span class="doxyComputerOutput">(</span> matches the start of a capture range</li>
<li><span class="doxyComputerOutput">)</span> matches the ends a capture range</li>
<li><span class="doxyComputerOutput">\c</span> to escape a special character, such as <span class="doxyComputerOutput">+</span>, <span class="doxyComputerOutput">[</span>, <span class="doxyComputerOutput">*</span>, <span class="doxyComputerOutput">(</span>, etc.</li>
<li><span class="doxyComputerOutput">\t</span> matches a tab character</li>
<li><span class="doxyComputerOutput">\n</span> matches a newline character</li>
<li><span class="doxyComputerOutput">\r</span> matches a return character</li>
<li><span class="doxyComputerOutput">\s</span> matches any whitespace as defined by <span class="doxyComputerOutput">std::isspace()</span></li>
<li><span class="doxyComputerOutput">\d</span> matches any digit as defined by <span class="doxyComputerOutput">std::digit()</span></li>
<li><span class="doxyComputerOutput">\a</span> matches any alphabetical characters, same as <span class="doxyComputerOutput">[a-z_A-Z\x80-\xFF]</span></li>
<li><span class="doxyComputerOutput">\w</span> matches any alpha numerical character, same as <span class="doxyComputerOutput">[a-z_A-Z0-9\x80-\xFF]</span></li>
<li><span class="doxyComputerOutput">\xHH</span> matches a hexadecimal character, e.g. <span class="doxyComputerOutput">\xA0</span> matches character code 160.</li>
</ul>

<p>A character range can be used to match a character that falls inside a range (or set of ranges). Within the opening <span class="doxyComputerOutput">[</span> and closing <span class="doxyComputerOutput">]</span> brackets of a character ranges the following is supported:</p>

<ul class="doxyList ">
<li><span class="doxyComputerOutput">^</span> if at the start of the range, a character matches if it is <em>not</em> in the range, e.g. <span class="doxyComputerOutput">[^\d]</span> matches any character not a digit</li>
<li><span class="doxyComputerOutput">-</span> when placed between 2 characters it defines a range from the first character to the second. any character that falls in the range will match, e.g. [0-9] matches the digit from 0 to 9.</li>
<li><span class="doxyComputerOutput">\s</span>, <span class="doxyComputerOutput">\d</span>, <span class="doxyComputerOutput">\a</span>, and <span class="doxyComputerOutput">\w</span> as explained above.</li>
</ul>

:::info
<p>that special characters <span class="doxyComputerOutput">.</span>, <span class="doxyComputerOutput">*</span>, <span class="doxyComputerOutput">?</span>, <span class="doxyComputerOutput">$</span>, <span class="doxyComputerOutput">+</span>, <span class="doxyComputerOutput">[</span> do not have a special meaning in a character range. <span class="doxyComputerOutput">^</span> only has a special meaning as the first character.</p>
:::


:::info
<p>that capture ranges cannot be nested, and <span class="doxyComputerOutput">*</span>, <span class="doxyComputerOutput">+</span>, and <span class="doxyComputerOutput">?</span> do not work on capture ranges. e.g. <span class="doxyComputerOutput">(abd)?</span> is not valid. If multiple capture ranges are specified then some character has to be in between them, e.g. this does not work <span class="doxyComputerOutput">(.*)(a.*)</span>, but this does <span class="doxyComputerOutput">(.*)a(.*)</span>.</p>
:::


<p>In Wildcard mode <span class="doxyComputerOutput">*</span> is used to match any sequence of zero or more characters. The character <span class="doxyComputerOutput">?</span> can be used to match an optional character. Character ranges are also supported, but other characters like <span class="doxyComputerOutput">$</span> and <span class="doxyComputerOutput">+</span> are just treated as literal characters.</p>

<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/regex-h/#l00097">97</a> of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/regex-cpp/#l00694">694</a> of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a54ed63c6793f8b7f2e026c26f12d4e67">694</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a54ed63c6793f8b7f2e026c26f12d4e67">Ex::Ex</a>(std::string_view pattern, <a href="#a8c11e4a47acf40a6747e2709961acdf9">Mode</a> mode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/classes/reg/ex/private">Private</a>&gt;(mode==<a href="#a8c11e4a47acf40a6747e2709961acdf9">Mode</a>::<a href="#a8c11e4a47acf40a6747e2709961acdf9aaa3c0312d71dacb7f28dd70f21d32ac0">RegEx</a> ? pattern : <a href="/web-doxygen/docs/api/namespaces/reg/#a470992837f9356c9ed07fb0913072ac2">wildcard2regex</a>(pattern)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;compile();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#if ENABLE_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;dump();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(!<a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;error);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>, <a href="#a8c11e4a47acf40a6747e2709961acdf9aaa3c0312d71dacb7f28dd70f21d32ac0">RegEx</a> and <a href="/web-doxygen/docs/api/namespaces/reg/#a470992837f9356c9ed07fb0913072ac2">reg::wildcard2regex</a>.

Referenced by <a href="#a197664abdebf160b5b621c3a78c01cf7">~Ex</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### ~Ex() {#a197664abdebf160b5b621c3a78c01cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::Ex::~Ex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Destroys the regular expression object.</p>


<p>Frees resources.</p>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/regex-h/#l00100">100</a> of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

References <a href="#a54ed63c6793f8b7f2e026c26f12d4e67">Ex</a> and <a href="#a45dcd4878848bcefa4894aa48a2d9b83">match</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### isValid() {#ab26ac71412d978b0a03ac996da2beb74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::Ex::isValid ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/regex-h/#l00109">109</a> of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/regex-cpp/#l00741">741</a> of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab26ac71412d978b0a03ac996da2beb74">741</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab26ac71412d978b0a03ac996da2beb74">Ex::isValid</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;pattern.empty() &amp;&amp; !<a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;error;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0ab63cb2f20e16fa82b9b687d2b4b00">genericPatternMatch</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad8f45edef0c9f7b3b0468e6fdb7cef71">getFilterFromList</a>.
</div>
</div>

### match() {#a45dcd4878848bcefa4894aa48a2d9b83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::Ex::match (std::string_view str, <a href="/web-doxygen/docs/api/classes/reg/match">Match</a> &amp; match, size_t pos=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Check if a given string matches this regular expression.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">str</td>
<td class="doxyParamItemDescription"><p>The input string to match against.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">match</td>
<td class="doxyParamItemDescription"><p>The match object to hold the matching results.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">pos</td>
<td class="doxyParamItemDescription"><p>The position in the string at which to start the match.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
<p>true iff a match is found. Details are stored in the match object.</p>
</dd>
</dl>


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/regex-h/#l00108">108</a> of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/regex-cpp/#l00706">706</a> of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a45dcd4878848bcefa4894aa48a2d9b83">706</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a45dcd4878848bcefa4894aa48a2d9b83">Ex::match</a>(std::string_view str,<a href="/web-doxygen/docs/api/classes/reg/match">Match</a> &amp;<a href="#a45dcd4878848bcefa4894aa48a2d9b83">match</a>,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;data.size()==0 || <a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;error) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> found;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a45dcd4878848bcefa4894aa48a2d9b83">match</a>.init(str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/reg/ptoken">PToken</a> tok = <a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;data[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153">PToken::Kind::BeginOfLine</a>) </span><span class="doxyHighlightComment">// only test match at the given position</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">    found = <a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;matchAt(0,<a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;data.size(),str,<a href="#a45dcd4878848bcefa4894aa48a2d9b83">match</a>,pos,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">PToken::Kind::Character</a>) </span><span class="doxyHighlightComment">// search for the start character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> index = str.find(tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a34589c92a4e8ff59eb14c5536e760929">asciiValue</a>(),pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index==std::string::npos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>(</span><span class="doxyHighlightStringLiteral">"Ex::match(str='%s',pos=%zu)=false (no start char '%c')\n"</span><span class="doxyHighlight">,str.c_str(),pos,tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a34589c92a4e8ff59eb14c5536e760929">asciiValue</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>(</span><span class="doxyHighlightStringLiteral">"pos=%zu str='%s' char='%c' index=%zu\n"</span><span class="doxyHighlight">,index,str.c_str(),tok.<a href="/web-doxygen/docs/api/classes/reg/ptoken/#a34589c92a4e8ff59eb14c5536e760929">asciiValue</a>(),index);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">      pos=index;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (pos&lt;str.length()) </span><span class="doxyHighlightComment">// search for a match starting at pos</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">      found = <a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;matchAt(0,<a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>-&gt;data.size(),str,<a href="#a45dcd4878848bcefa4894aa48a2d9b83">match</a>,pos,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">      pos++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>(</span><span class="doxyHighlightStringLiteral">"Ex::match(str='%s',pos=%zu)=%d\n"</span><span class="doxyHighlight">,str.c_str(),pos,found);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> found;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a34589c92a4e8ff59eb14c5536e760929">reg::PToken::asciiValue</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153">reg::PToken::BeginOfLine</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">reg::PToken::Character</a>, <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#a32adf79142f0a426b5e782fb7cd4cad3">DBG</a>, <a href="/web-doxygen/docs/api/classes/reg/ptoken/#a5b947291aff91a346d6526074989a9fa">reg::PToken::kind</a>, <a href="#a45dcd4878848bcefa4894aa48a2d9b83">match</a> and <a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>.

Referenced by <a href="#a45dcd4878848bcefa4894aa48a2d9b83">match</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a64421aecc141803690cdb0d6d235354b">reg::match</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#abd83bf57cdc053d40135b7c8f211f2b9">reg::match</a>, <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#ab6913d787be9fe9992c8804af851fab9">reg::replace</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a4d1ef4b86632c8deaa796bf008205ff9">reg::search</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a> and <a href="#a197664abdebf160b5b621c3a78c01cf7">~Ex</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a22ceaa4b6fdbc31b5f65db3f03aadd89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; reg::Ex::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/regex-h/#l00114">114</a> of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">114</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a22ceaa4b6fdbc31b5f65db3f03aadd89">p</a>;</span></span></div>

</div>


Referenced by <a href="#a54ed63c6793f8b7f2e026c26f12d4e67">Ex</a>, <a href="#ab26ac71412d978b0a03ac996da2beb74">isValid</a> and <a href="#a45dcd4878848bcefa4894aa48a2d9b83">match</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
