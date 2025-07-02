---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/reg/ptoken
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `PToken` Class Reference

Class representing a token in the compiled regular expression token stream. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class reg::PToken { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Kind : uint16_t { <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
The kind of token. <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63a09d68f5ded8c563f5a06cdd32db27">PToken</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Creates a token of kind 'End'. <a href="#a63a09d68f5ded8c563f5a06cdd32db27">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a383d4137455b9fdc268fd0db4b050db0">PToken</a> (Kind k)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Creates a token of the given kind <em>k</em>. <a href="#a383d4137455b9fdc268fd0db4b050db0">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c769c7cb9e8961e5f52187237f94992">PToken</a> (char c)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Create a token for an ASCII character. <a href="#a3c769c7cb9e8961e5f52187237f94992">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec4f875592b933d86407f7e98bff68ee">PToken</a> (uint16_t v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Create a token for a byte of an UTF-8 character. <a href="#aec4f875592b933d86407f7e98bff68ee">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7714d26eaa9913922be030737df02b2">PToken</a> (uint16_t from, uint16_t to)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Create a token representing a range from one character <em>from</em> to another character <em>to</em>. <a href="#af7714d26eaa9913922be030737df02b2">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9648ec9cffa7fc0d1ef165fc5882a552">kindStr</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
returns a string representation of the tokens kind (useful for debugging). <a href="#a9648ec9cffa7fc0d1ef165fc5882a552">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3fca62e036f3fa3cc2ce3a6e79e709b">setValue</a> (uint16_t value)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Sets the value for a token. <a href="#ac3fca62e036f3fa3cc2ce3a6e79e709b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0">Kind</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b947291aff91a346d6526074989a9fa">kind</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the kind of the token. <a href="#a5b947291aff91a346d6526074989a9fa">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93203bf3f74828336b477ea31fde1a1c">from</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the 'from' part of the character range. <a href="#a93203bf3f74828336b477ea31fde1a1c">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2def1e14eeb96c08b25e4c906af071b6">to</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the 'to' part of the character range. <a href="#a2def1e14eeb96c08b25e4c906af071b6">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint16_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac897faa4d75c143ca24924a5754aa369">value</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the value for this token. <a href="#ac897faa4d75c143ca24924a5754aa369">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a34589c92a4e8ff59eb14c5536e760929">asciiValue</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the value for this token as a ASCII character. <a href="#a34589c92a4e8ff59eb14c5536e760929">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bcf1a48342ff492138d3aff1e0a6fc0">isRange</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns true iff this token represents a range of characters. <a href="#a4bcf1a48342ff492138d3aff1e0a6fc0">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef9ece1aec9504adcf4deb03d803c378">isCharClass</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns true iff this token is a positive or negative character class. <a href="#aef9ece1aec9504adcf4deb03d803c378">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a></td>
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

Class representing a token in the compiled regular expression token stream.


A token has a kind and an optional value whose meaning depends on the kind. It is also possible to store a (from,to) character range in a token.

Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxySectionDef">

## Enumerations

### Kind {#a9649bb8ecf7bd3f7faf60b56c6fa72f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class reg::PToken::Kind : uint16_t</td>
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

The kind of token.

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">End<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0a87557f11575c0ad78e4e28abedc13b6e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x0000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WhiteSpace<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0a1043facb02056549cfa595ce3622fe77"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Digit<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0a83d25adab16b42ea36124318d7e6f4c1"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1002)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Alpha<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0a6132295fcf5570fb8b0a944ef322a598"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1003)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AlphaNum<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0ace2517d5ebbfbacb523d54ac962ec398"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1004)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CharClass<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0ac1033972d40514e4ae13188bd76154a3"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NegCharClass<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0a7751fdcc5884cd61bbf7c0e9ddc4d5b9"></a></td>
<td class="doxyEnumItemDescription"> (= 0x2002)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BeginOfLine<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4001)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndOfLine<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0a5d8c95ca9e91a87bd9c90b0f309fd740"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4002)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BeginOfWord<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0ab906a68270604e574f9efe7e4e04fb00"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4003)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndOfWord<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0a0074dd6a055a769d905f34a741d19511"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4004)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BeginCapture<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4005)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EndCapture<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0a7a8c9c3e0b4b26bfe0ac9f9eb0745666"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4006)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Any<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0aed36a1ef76a59ee3f15180e0441188ad"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4007)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Star<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0a26f93e6e68e28a698377e941cb59f29a"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4008)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Optional<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0aebb061953c0454b2c8ee7b0ac615ebcd"></a></td>
<td class="doxyEnumItemDescription"> (= 0x4009)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Character<a id="a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4"></a></td>
<td class="doxyEnumItemDescription"> (= 0x8000)</td>
</tr>

</table>
</dd>
</dl>


Ranges per bit mask:

<ul class="doxyList ">
<li><code>255</code> from part of a range, except for <code>0</code> which is the End marker</li>
<li><code>8191</code> built-in ranges</li>
<li><code>12287</code> user defined ranges</li>
<li><code>20479</code> special operations</li>
<li><code>32768</code> literal character</li>
</ul>

Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a87557f11575c0ad78e4e28abedc13b6e">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a87557f11575c0ad78e4e28abedc13b6e">End</a>            = 0x0000,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a1043facb02056549cfa595ce3622fe77">73</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a1043facb02056549cfa595ce3622fe77">WhiteSpace</a>     = 0x1001,    </span><span class="doxyHighlightComment">// \s    range [ \t\r\n]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a83d25adab16b42ea36124318d7e6f4c1">74</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a83d25adab16b42ea36124318d7e6f4c1">Digit</a>          = 0x1002,    </span><span class="doxyHighlightComment">// \d    range [0-9]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6132295fcf5570fb8b0a944ef322a598">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6132295fcf5570fb8b0a944ef322a598">Alpha</a>          = 0x1003,    </span><span class="doxyHighlightComment">// \a    range [a-z_A-Z\x80-\xFF]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ace2517d5ebbfbacb523d54ac962ec398">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ace2517d5ebbfbacb523d54ac962ec398">AlphaNum</a>       = 0x1004,    </span><span class="doxyHighlightComment">// \w    range [a-Z_A-Z0-9\x80-\xFF]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ac1033972d40514e4ae13188bd76154a3">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ac1033972d40514e4ae13188bd76154a3">CharClass</a>      = 0x2001,    </span><span class="doxyHighlightComment">// []</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7751fdcc5884cd61bbf7c0e9ddc4d5b9">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7751fdcc5884cd61bbf7c0e9ddc4d5b9">NegCharClass</a>   = 0x2002,    </span><span class="doxyHighlightComment">// [^]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153">BeginOfLine</a>    = 0x4001,    </span><span class="doxyHighlightComment">// ^</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a5d8c95ca9e91a87bd9c90b0f309fd740">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a5d8c95ca9e91a87bd9c90b0f309fd740">EndOfLine</a>      = 0x4002,    </span><span class="doxyHighlightComment">// $</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ab906a68270604e574f9efe7e4e04fb00">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ab906a68270604e574f9efe7e4e04fb00">BeginOfWord</a>    = 0x4003,    </span><span class="doxyHighlightComment">// \&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a0074dd6a055a769d905f34a741d19511">82</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a0074dd6a055a769d905f34a741d19511">EndOfWord</a>      = 0x4004,    </span><span class="doxyHighlightComment">// \&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e">83</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e">BeginCapture</a>   = 0x4005,    </span><span class="doxyHighlightComment">// (</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7a8c9c3e0b4b26bfe0ac9f9eb0745666">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7a8c9c3e0b4b26bfe0ac9f9eb0745666">EndCapture</a>     = 0x4006,    </span><span class="doxyHighlightComment">// )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0aed36a1ef76a59ee3f15180e0441188ad">85</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0aed36a1ef76a59ee3f15180e0441188ad">Any</a>            = 0x4007,    </span><span class="doxyHighlightComment">// .</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a26f93e6e68e28a698377e941cb59f29a">86</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a26f93e6e68e28a698377e941cb59f29a">Star</a>           = 0x4008,    </span><span class="doxyHighlightComment">// *</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0aebb061953c0454b2c8ee7b0ac615ebcd">87</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0aebb061953c0454b2c8ee7b0ac615ebcd">Optional</a>       = 0x4009,    </span><span class="doxyHighlightComment">// ?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">Character</a>      = 32768     </span><span class="doxyHighlightComment">// c</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### PToken() {#a63a09d68f5ded8c563f5a06cdd32db27}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::PToken::PToken ()</td>
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

Creates a token of kind 'End'.

Definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a63a09d68f5ded8c563f5a06cdd32db27">124</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a63a09d68f5ded8c563f5a06cdd32db27">PToken</a>() : <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>(0) {}</span></span></div>

</div>


Reference <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a>.
</div>
</div>

### PToken() {#a383d4137455b9fdc268fd0db4b050db0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::PToken::PToken (<a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0">Kind</a> k)</td>
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

Creates a token of the given kind <em>k</em>.

Definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a383d4137455b9fdc268fd0db4b050db0">127</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#a383d4137455b9fdc268fd0db4b050db0">PToken</a>(<a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0">Kind</a> k)    : <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>(static_cast&lt;uint32_t&gt;(k)&lt;&lt;16) {}</span></span></div>

</div>


Reference <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a>.
</div>
</div>

### PToken() {#a3c769c7cb9e8961e5f52187237f94992}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::PToken::PToken (char c)</td>
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

Create a token for an ASCII character.

Definition at line 130 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c769c7cb9e8961e5f52187237f94992">130</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3c769c7cb9e8961e5f52187237f94992">PToken</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)             : <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>((static_cast&lt;uint32_t&gt;(<a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0">Kind</a>::<a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">Character</a>)&lt;&lt;16) |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">                                        static_cast&lt;uint32_t&gt;(c)) {}</span></span></div>

</div>


References <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">Character</a> and <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a>.
</div>
</div>

### PToken() {#aec4f875592b933d86407f7e98bff68ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::PToken::PToken (uint16_t v)</td>
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

Create a token for a byte of an UTF-8 character.

Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aec4f875592b933d86407f7e98bff68ee">134</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aec4f875592b933d86407f7e98bff68ee">PToken</a>(uint16_t v)         : <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>((static_cast&lt;uint32_t&gt;(<a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0">Kind</a>::<a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">Character</a>)&lt;&lt;16) |</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">                                        static_cast&lt;uint32_t&gt;(v)) {}</span></span></div>

</div>


References <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">Character</a> and <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a>.
</div>
</div>

### PToken() {#af7714d26eaa9913922be030737df02b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::PToken::PToken (uint16_t from, uint16_t to)</td>
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

Create a token representing a range from one character <em>from</em> to another character <em>to</em>.

Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7714d26eaa9913922be030737df02b2">138</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af7714d26eaa9913922be030737df02b2">PToken</a>(uint16_t <a href="#a93203bf3f74828336b477ea31fde1a1c">from</a>,uint16_t <a href="#a2def1e14eeb96c08b25e4c906af071b6">to</a>) : <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>(static_cast&lt;uint32_t&gt;(<a href="#a93203bf3f74828336b477ea31fde1a1c">from</a>)&lt;&lt;16 | <a href="#a2def1e14eeb96c08b25e4c906af071b6">to</a>) {}</span></span></div>

</div>


References <a href="#a93203bf3f74828336b477ea31fde1a1c">from</a>, <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a> and <a href="#a2def1e14eeb96c08b25e4c906af071b6">to</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### asciiValue() {#a34589c92a4e8ff59eb14c5536e760929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char reg::PToken::asciiValue ()</td>
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

Returns the value for this token as a ASCII character.

Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a34589c92a4e8ff59eb14c5536e760929">156</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="#a34589c92a4e8ff59eb14c5536e760929">asciiValue</a>()</span><span class="doxyHighlightKeyword"> const       </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>); }</span></span></div>

</div>


Reference <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/reg/ex/private/#a5ae763e5ab5231eae1133e68093c49be">reg::Ex::Private::compile</a>, <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">reg::Ex::match</a> and <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a>.
</div>
</div>

### from() {#a93203bf3f74828336b477ea31fde1a1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t reg::PToken::from ()</td>
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

Returns the 'from' part of the character range.


Only valid if this token represents a range

Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a93203bf3f74828336b477ea31fde1a1c">147</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint16_t <a href="#a93203bf3f74828336b477ea31fde1a1c">from</a>()</span><span class="doxyHighlightKeyword"> const         </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>&gt;&gt;16; }</span></span></div>

</div>


Reference <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a>.

Referenced by <a href="#a4bcf1a48342ff492138d3aff1e0a6fc0">isRange</a>, <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a> and <a href="#af7714d26eaa9913922be030737df02b2">PToken</a>.
</div>
</div>

### isCharClass() {#aef9ece1aec9504adcf4deb03d803c378}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::PToken::isCharClass ()</td>
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

Returns true iff this token is a positive or negative character class.

Definition at line 162 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aef9ece1aec9504adcf4deb03d803c378">162</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aef9ece1aec9504adcf4deb03d803c378">isCharClass</a>()</span><span class="doxyHighlightKeyword"> const      </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ac1033972d40514e4ae13188bd76154a3">Kind::CharClass</a> || <a href="#a5b947291aff91a346d6526074989a9fa">kind</a>()==<a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7751fdcc5884cd61bbf7c0e9ddc4d5b9">Kind::NegCharClass</a>; }</span></span></div>

</div>


References <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ac1033972d40514e4ae13188bd76154a3">CharClass</a>, <a href="#a5b947291aff91a346d6526074989a9fa">kind</a> and <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7751fdcc5884cd61bbf7c0e9ddc4d5b9">NegCharClass</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a>.
</div>
</div>

### isRange() {#a4bcf1a48342ff492138d3aff1e0a6fc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool reg::PToken::isRange ()</td>
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

Returns true iff this token represents a range of characters.

Definition at line 159 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4bcf1a48342ff492138d3aff1e0a6fc0">159</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4bcf1a48342ff492138d3aff1e0a6fc0">isRange</a>()</span><span class="doxyHighlightKeyword"> const          </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>!=0 &amp;&amp; <a href="#a93203bf3f74828336b477ea31fde1a1c">from</a>()&lt;=<a href="#a2def1e14eeb96c08b25e4c906af071b6">to</a>(); }</span></span></div>

</div>


References <a href="#a93203bf3f74828336b477ea31fde1a1c">from</a>, <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a> and <a href="#a2def1e14eeb96c08b25e4c906af071b6">to</a>.
</div>
</div>

### kind() {#a5b947291aff91a346d6526074989a9fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Kind reg::PToken::kind ()</td>
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

Returns the kind of the token.

Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b947291aff91a346d6526074989a9fa">144</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0">Kind</a> <a href="#a5b947291aff91a346d6526074989a9fa">kind</a>()</span><span class="doxyHighlightKeyword"> const             </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0">Kind</a></span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>&gt;&gt;16); }</span></span></div>

</div>


Reference <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/reg/ex/private/#a5ae763e5ab5231eae1133e68093c49be">reg::Ex::Private::compile</a>, <a href="#aef9ece1aec9504adcf4deb03d803c378">isCharClass</a>, <a href="/web-doxygen/docs/api/classes/reg/ex/#a45dcd4878848bcefa4894aa48a2d9b83">reg::Ex::match</a> and <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a>.
</div>
</div>

### kindStr() {#a9648ec9cffa7fc0d1ef165fc5882a552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * reg::PToken::kindStr ()</td>
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

returns a string representation of the tokens kind (useful for debugging).

Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9648ec9cffa7fc0d1ef165fc5882a552">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a9648ec9cffa7fc0d1ef165fc5882a552">kindStr</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>&gt;&gt;16)&gt;=0x1000 || <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0">Kind</a></span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">((<a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>&gt;&gt;16)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a87557f11575c0ad78e4e28abedc13b6e">Kind::End</a>:           </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"End"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6132295fcf5570fb8b0a944ef322a598">Kind::Alpha</a>:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"Alpha"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ace2517d5ebbfbacb523d54ac962ec398">Kind::AlphaNum</a>:      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"AlphaNum"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a1043facb02056549cfa595ce3622fe77">Kind::WhiteSpace</a>:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"WhiteSpace"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a83d25adab16b42ea36124318d7e6f4c1">Kind::Digit</a>:         </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"Digit"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ac1033972d40514e4ae13188bd76154a3">Kind::CharClass</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"CharClass"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7751fdcc5884cd61bbf7c0e9ddc4d5b9">Kind::NegCharClass</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"NegCharClass"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">Kind::Character</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"Character"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153">Kind::BeginOfLine</a>:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"BeginOfLine"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a5d8c95ca9e91a87bd9c90b0f309fd740">Kind::EndOfLine</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"EndOfLine"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ab906a68270604e574f9efe7e4e04fb00">Kind::BeginOfWord</a>:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"BeginOfWord"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a0074dd6a055a769d905f34a741d19511">Kind::EndOfWord</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"EndOfWord"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e">Kind::BeginCapture</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"BeginCapture"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7a8c9c3e0b4b26bfe0ac9f9eb0745666">Kind::EndCapture</a>:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"EndCapture"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0aed36a1ef76a59ee3f15180e0441188ad">Kind::Any</a>:           </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"Any"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a26f93e6e68e28a698377e941cb59f29a">Kind::Star</a>:          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"Star"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0aebb061953c0454b2c8ee7b0ac615ebcd">Kind::Optional</a>:      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"Optional"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"Range"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6132295fcf5570fb8b0a944ef322a598">Alpha</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ace2517d5ebbfbacb523d54ac962ec398">AlphaNum</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0aed36a1ef76a59ee3f15180e0441188ad">Any</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ae3d62aaae3ff1d7c42a73fb4e5c7770e">BeginCapture</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a6ed83ba4fb11c5a677335f0e3e60c153">BeginOfLine</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ab906a68270604e574f9efe7e4e04fb00">BeginOfWord</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a76a40e4f974fd895a0a2598c1cee28b4">Character</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0ac1033972d40514e4ae13188bd76154a3">CharClass</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a83d25adab16b42ea36124318d7e6f4c1">Digit</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a87557f11575c0ad78e4e28abedc13b6e">End</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7a8c9c3e0b4b26bfe0ac9f9eb0745666">EndCapture</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a5d8c95ca9e91a87bd9c90b0f309fd740">EndOfLine</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a0074dd6a055a769d905f34a741d19511">EndOfWord</a>, <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a7751fdcc5884cd61bbf7c0e9ddc4d5b9">NegCharClass</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0aebb061953c0454b2c8ee7b0ac615ebcd">Optional</a>, <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a26f93e6e68e28a698377e941cb59f29a">Star</a> and <a href="#a9649bb8ecf7bd3f7faf60b56c6fa72f0a1043facb02056549cfa595ce3622fe77">WhiteSpace</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a>.
</div>
</div>

### setValue() {#ac3fca62e036f3fa3cc2ce3a6e79e709b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reg::PToken::setValue (uint16_t value)</td>
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

Sets the value for a token.

Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac3fca62e036f3fa3cc2ce3a6e79e709b">141</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac3fca62e036f3fa3cc2ce3a6e79e709b">setValue</a>(uint16_t <a href="#ac897faa4d75c143ca24924a5754aa369">value</a>) { <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a> = (<a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a> &amp; 0xFFFF0000) | <a href="#ac897faa4d75c143ca24924a5754aa369">value</a>; }</span></span></div>

</div>


References <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a> and <a href="#ac897faa4d75c143ca24924a5754aa369">value</a>.
</div>
</div>

### to() {#a2def1e14eeb96c08b25e4c906af071b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t reg::PToken::to ()</td>
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

Returns the 'to' part of the character range.


Only valid if this token represents a range

Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2def1e14eeb96c08b25e4c906af071b6">150</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint16_t <a href="#a2def1e14eeb96c08b25e4c906af071b6">to</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a> &amp; 0xFFFF; }</span></span></div>

</div>


Reference <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a>.

Referenced by <a href="#a4bcf1a48342ff492138d3aff1e0a6fc0">isRange</a>, <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a> and <a href="#af7714d26eaa9913922be030737df02b2">PToken</a>.
</div>
</div>

### value() {#ac897faa4d75c143ca24924a5754aa369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint16_t reg::PToken::value ()</td>
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

Returns the value for this token.

Definition at line 153 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac897faa4d75c143ca24924a5754aa369">153</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint16_t <a href="#ac897faa4d75c143ca24924a5754aa369">value</a>()</span><span class="doxyHighlightKeyword"> const        </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a> &amp; 0xFFFF; }</span></span></div>

</div>


Reference <a href="#aa6204b59dad3115e3fd810bab9d6f255">m\_rep</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/reg/ex/private/#a5ae763e5ab5231eae1133e68093c49be">reg::Ex::Private::compile</a>, <a href="/web-doxygen/docs/api/classes/reg/ex/private/#acb10ddb380fa79ce0a346360feffce11">reg::Ex::Private::matchAt</a> and <a href="#ac3fca62e036f3fa3cc2ce3a6e79e709b">setValue</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_rep {#aa6204b59dad3115e3fd810bab9d6f255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t reg::PToken::m_rep</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 165 of file <a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa6204b59dad3115e3fd810bab9d6f255">165</a></span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t <a href="#aa6204b59dad3115e3fd810bab9d6f255">m_rep</a>;</span></span></div>

</div>


Referenced by <a href="#a34589c92a4e8ff59eb14c5536e760929">asciiValue</a>, <a href="#a93203bf3f74828336b477ea31fde1a1c">from</a>, <a href="#a4bcf1a48342ff492138d3aff1e0a6fc0">isRange</a>, <a href="#a5b947291aff91a346d6526074989a9fa">kind</a>, <a href="#a9648ec9cffa7fc0d1ef165fc5882a552">kindStr</a>, <a href="#a63a09d68f5ded8c563f5a06cdd32db27">PToken</a>, <a href="#a3c769c7cb9e8961e5f52187237f94992">PToken</a>, <a href="#a383d4137455b9fdc268fd0db4b050db0">PToken</a>, <a href="#af7714d26eaa9913922be030737df02b2">PToken</a>, <a href="#aec4f875592b933d86407f7e98bff68ee">PToken</a>, <a href="#ac3fca62e036f3fa3cc2ce3a6e79e709b">setValue</a>, <a href="#a2def1e14eeb96c08b25e4c906af071b6">to</a> and <a href="#ac897faa4d75c143ca24924a5754aa369">value</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/regex-cpp">regex.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
