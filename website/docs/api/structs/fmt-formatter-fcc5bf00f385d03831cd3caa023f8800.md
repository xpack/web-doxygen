---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/fmt/formatter-fcc5bf00f385d03831cd3caa023f8800
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `formatter` Struct Template Reference

<p>adds support for formatting <a href="/web-doxygen/docs/api/files/src/types-h/#aa370e9ca1d3ff266cab92689bcc37d9e">RelatesType</a> <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct fmt::formatter&lt;RelatesType&gt; { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b4aa1bedcac6584e771fd14b25f0b69">format</a> (RelatesType type, format_context &amp;ctx) const</td>
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

<p>adds support for formatting <a href="/web-doxygen/docs/api/files/src/types-h/#aa370e9ca1d3ff266cab92689bcc37d9e">RelatesType</a></p>

<p>Definition at line 180 of file <a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### format() {#a8b4aa1bedcac6584e771fd14b25f0b69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto fmt::formatter&lt; RelatesType &gt;::format (<a href="/web-doxygen/docs/api/files/src/types-h/#aa370e9ca1d3ff266cab92689bcc37d9e">RelatesType</a> type, format_context &amp; ctx)</td>
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



<p>Definition at line 182 of file <a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8b4aa1bedcac6584e771fd14b25f0b69">182</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="#a8b4aa1bedcac6584e771fd14b25f0b69">format</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#aa370e9ca1d3ff266cab92689bcc37d9e">RelatesType</a> type, format_context&amp; ctx)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/fmt/formatter">formatter&lt;std::string&gt;::format</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a77df23cf91cf59df5e7edf9f887daa7c">to_string</a>(type), ctx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/types-h/#a77df23cf91cf59df5e7edf9f887daa7c">to_string</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/message-h">message.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
