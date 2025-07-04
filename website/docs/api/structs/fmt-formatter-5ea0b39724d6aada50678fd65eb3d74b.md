---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/fmt/formatter-5ea0b39724d6aada50678fd65eb3d74b
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `formatter` Struct Template Reference

<p>adds support for formatting <a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct fmt::formatter&lt;Specifier&gt; { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc03d0df4913a8a83e707232e68ad9c8">format</a> (Specifier spec, format_context &amp;ctx) const</td>
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

<p>adds support for formatting <a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a></p>

<p>Definition at line 164 of file <a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### format() {#afc03d0df4913a8a83e707232e68ad9c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto fmt::formatter&lt; Specifier &gt;::format (<a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> spec, format_context &amp; ctx)</td>
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



<p>Definition at line 166 of file <a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc03d0df4913a8a83e707232e68ad9c8">166</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="#afc03d0df4913a8a83e707232e68ad9c8">format</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> spec, format_context&amp; ctx)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/fmt/formatter">formatter&lt;std::string&gt;::format</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a77df23cf91cf59df5e7edf9f887daa7c">to_string</a>(spec), ctx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

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
