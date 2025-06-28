---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/fmt/formatter-3bc0763cf07398a7c5644ce192ea65ea
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `formatter` Struct Template Reference

<p>adds support for formatting <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a> <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct fmt::formatter&lt;TypeSpecifier&gt; { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/message-h">src/message.h</a>&gt;
</div>

## Base struct

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/fmt/formatter">formatter&lt;T&gt;</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5185feae6dcec945c021b1e40ced47f1">format</a> (TypeSpecifier type, format_context &amp;ctx) const</td>
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

<p>adds support for formatting <a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a></p>

<p>Definition at line 232 of file <a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>.</p>

<div class="doxySectionDef">

## Public Member Functions

### format() {#a5185feae6dcec945c021b1e40ced47f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto fmt::formatter&lt; TypeSpecifier &gt;::format (<a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a> type, format_context &amp; ctx)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/message-h/#l00234">234</a> of file <a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5185feae6dcec945c021b1e40ced47f1">234</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="#a5185feae6dcec945c021b1e40ced47f1">format</a>(<a href="/web-doxygen/docs/api/classes/typespecifier">TypeSpecifier</a> type, format_context&amp; ctx)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/fmt/formatter">formatter&lt;std::string&gt;::format</a>(type.<a href="/web-doxygen/docs/api/classes/typespecifier/#a253f39d5231d613732dc149a1e00bd55">to_string</a>(),ctx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/typespecifier/#a253f39d5231d613732dc149a1e00bd55">TypeSpecifier::to&#95;string</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/message-h">message.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
