---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/reg/submatch
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `SubMatch` Class Reference

<p>Object representing the match results of a capture range. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class reg::SubMatch { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/regex-h">src/regex.h</a>&gt;
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80bbc92cafa9d727e9c5e125a2d21585">Match</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5bfd11a5ea9664dc65c1855949535d0">SubMatch</a> (std::string_view str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Creates a match for a single capture range given a non-owning pointer to the string. <a href="#ac5bfd11a5ea9664dc65c1855949535d0">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad00a531046ed49e938a7bbe86617e9dc">position</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the position in the string at which the match starts. <a href="#ad00a531046ed49e938a7bbe86617e9dc">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e137e41b04ac89a5c66929c0a549725">length</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the length of the matching part. <a href="#a1e137e41b04ac89a5c66929c0a549725">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad63668eae91e3c165b3e123a535331ba">str</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the matching part as a string. <a href="#ad63668eae91e3c165b3e123a535331ba">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3523ab0d0de8fcbbcd6e13cc9e246d1d">setStart</a> (size_t pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a316eb00c39899a5699732e350aae2d2b">setEnd</a> (size_t pos)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a9307c50ec4361b8f81eccc1953d10a">setMatch</a> (size_t pos, size_t len)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7098227bec86f649c193d17418249ed4">m_pos</a> = std::string::npos</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69b439fc63c5b605bbe8a3bfa26bb33d">m_len</a> = std::string::npos</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7125a73104592f727df38104c9d8a409">m_str</a></td>
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

<p>Object representing the match results of a capture range.</p>

<p>Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxySectionDef">

## Friends

### Match {#a80bbc92cafa9d727e9c5e125a2d21585}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-doxygen/docs/api/classes/reg/match">Match</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a80bbc92cafa9d727e9c5e125a2d21585">134</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight"><a href="#a80bbc92cafa9d727e9c5e125a2d21585">Match</a>;</span></span></div>

</div>


Reference <a href="#a80bbc92cafa9d727e9c5e125a2d21585">Match</a>.

Referenced by <a href="#a80bbc92cafa9d727e9c5e125a2d21585">Match</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SubMatch() {#ac5bfd11a5ea9664dc65c1855949535d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">reg::SubMatch::SubMatch (std::string_view str)</td>
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
<p>Creates a match for a single capture range given a non-owning pointer to the string.</p>

<p>Definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5bfd11a5ea9664dc65c1855949535d0">122</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac5bfd11a5ea9664dc65c1855949535d0">SubMatch</a>(std::string_view <a href="#ad63668eae91e3c165b3e123a535331ba">str</a>) : <a href="#a7125a73104592f727df38104c9d8a409">m_str</a>(<a href="#ad63668eae91e3c165b3e123a535331ba">str</a>) {}</span></span></div>

</div>


References <a href="#a7125a73104592f727df38104c9d8a409">m&#95;str</a> and <a href="#ad63668eae91e3c165b3e123a535331ba">str</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### length() {#a1e137e41b04ac89a5c66929c0a549725}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t reg::SubMatch::length ()</td>
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
<p>Returns the length of the matching part.</p>

<p>Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1e137e41b04ac89a5c66929c0a549725">128</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a1e137e41b04ac89a5c66929c0a549725">length</a>()</span><span class="doxyHighlightKeyword">      const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a69b439fc63c5b605bbe8a3bfa26bb33d">m_len</a>; }</span></span></div>

</div>


Reference <a href="#a69b439fc63c5b605bbe8a3bfa26bb33d">m&#95;len</a>.
</div>
</div>

### position() {#ad00a531046ed49e938a7bbe86617e9dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t reg::SubMatch::position ()</td>
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
<p>Returns the position in the string at which the match starts.</p>

<p>Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad00a531046ed49e938a7bbe86617e9dc">125</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#ad00a531046ed49e938a7bbe86617e9dc">position</a>()</span><span class="doxyHighlightKeyword">    const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a7098227bec86f649c193d17418249ed4">m_pos</a>; }</span></span></div>

</div>


Reference <a href="#a7098227bec86f649c193d17418249ed4">m&#95;pos</a>.
</div>
</div>

### str() {#ad63668eae91e3c165b3e123a535331ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string reg::SubMatch::str ()</td>
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
<p>Returns the matching part as a string.</p>

<p>Definition at line 131 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad63668eae91e3c165b3e123a535331ba">131</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="#ad63668eae91e3c165b3e123a535331ba">str</a>()</span><span class="doxyHighlightKeyword">    const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::string{<a href="#a7125a73104592f727df38104c9d8a409">m_str</a>.substr(<a href="#a7098227bec86f649c193d17418249ed4">m_pos</a>,<a href="#a69b439fc63c5b605bbe8a3bfa26bb33d">m_len</a>)}; }</span></span></div>

</div>


References <a href="#a69b439fc63c5b605bbe8a3bfa26bb33d">m&#95;len</a>, <a href="#a7098227bec86f649c193d17418249ed4">m&#95;pos</a> and <a href="#a7125a73104592f727df38104c9d8a409">m&#95;str</a>.

Referenced by <a href="#ac5bfd11a5ea9664dc65c1855949535d0">SubMatch</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### setEnd() {#a316eb00c39899a5699732e350aae2d2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reg::SubMatch::setEnd (size_t pos)</td>
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


<p>Definition at line 136 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a316eb00c39899a5699732e350aae2d2b">136</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a316eb00c39899a5699732e350aae2d2b">setEnd</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos)   { <a href="#a69b439fc63c5b605bbe8a3bfa26bb33d">m_len</a>=pos-<a href="#a7098227bec86f649c193d17418249ed4">m_pos</a>; }</span></span></div>

</div>


References <a href="#a69b439fc63c5b605bbe8a3bfa26bb33d">m&#95;len</a> and <a href="#a7098227bec86f649c193d17418249ed4">m&#95;pos</a>.
</div>
</div>

### setMatch() {#a5a9307c50ec4361b8f81eccc1953d10a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reg::SubMatch::setMatch (size_t pos, size_t len)</td>
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


<p>Definition at line 137 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5a9307c50ec4361b8f81eccc1953d10a">137</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5a9307c50ec4361b8f81eccc1953d10a">setMatch</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len) { <a href="#a7098227bec86f649c193d17418249ed4">m_pos</a>=pos; <a href="#a69b439fc63c5b605bbe8a3bfa26bb33d">m_len</a>=len; }</span></span></div>

</div>


References <a href="#a69b439fc63c5b605bbe8a3bfa26bb33d">m&#95;len</a> and <a href="#a7098227bec86f649c193d17418249ed4">m&#95;pos</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/reg/match/#a8b332adf8f8813fda1d938314c92dfb8">reg::Match::prefix</a> and <a href="/web-doxygen/docs/api/classes/reg/match/#ab2301e49e73b68b27e4825fc38e04d41">reg::Match::suffix</a>.
</div>
</div>

### setStart() {#a3523ab0d0de8fcbbcd6e13cc9e246d1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void reg::SubMatch::setStart (size_t pos)</td>
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


<p>Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3523ab0d0de8fcbbcd6e13cc9e246d1d">135</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3523ab0d0de8fcbbcd6e13cc9e246d1d">setStart</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos) { <a href="#a7098227bec86f649c193d17418249ed4">m_pos</a>=pos; }</span></span></div>

</div>


Reference <a href="#a7098227bec86f649c193d17418249ed4">m&#95;pos</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;len {#a69b439fc63c5b605bbe8a3bfa26bb33d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t reg::SubMatch::m_len = std::string::npos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a69b439fc63c5b605bbe8a3bfa26bb33d">139</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a69b439fc63c5b605bbe8a3bfa26bb33d">m_len</a> = std::string::npos;</span></span></div>

</div>


Referenced by <a href="#a1e137e41b04ac89a5c66929c0a549725">length</a>, <a href="#a316eb00c39899a5699732e350aae2d2b">setEnd</a>, <a href="#a5a9307c50ec4361b8f81eccc1953d10a">setMatch</a> and <a href="#ad63668eae91e3c165b3e123a535331ba">str</a>.
</div>
</div>

### m&#95;pos {#a7098227bec86f649c193d17418249ed4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t reg::SubMatch::m_pos = std::string::npos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7098227bec86f649c193d17418249ed4">138</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a7098227bec86f649c193d17418249ed4">m_pos</a> = std::string::npos;</span></span></div>

</div>


Referenced by <a href="#ad00a531046ed49e938a7bbe86617e9dc">position</a>, <a href="#a316eb00c39899a5699732e350aae2d2b">setEnd</a>, <a href="#a5a9307c50ec4361b8f81eccc1953d10a">setMatch</a>, <a href="#a3523ab0d0de8fcbbcd6e13cc9e246d1d">setStart</a> and <a href="#ad63668eae91e3c165b3e123a535331ba">str</a>.
</div>
</div>

### m&#95;str {#a7125a73104592f727df38104c9d8a409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string_view reg::SubMatch::m_str</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7125a73104592f727df38104c9d8a409">140</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::string_view <a href="#a7125a73104592f727df38104c9d8a409">m_str</a>;</span></span></div>

</div>


Referenced by <a href="#ad63668eae91e3c165b3e123a535331ba">str</a> and <a href="#ac5bfd11a5ea9664dc65c1855949535d0">SubMatch</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
