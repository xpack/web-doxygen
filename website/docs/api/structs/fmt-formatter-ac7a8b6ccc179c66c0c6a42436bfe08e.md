---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/fmt/formatter-ac7a8b6ccc179c66c0c6a42436bfe08e
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `formatter` Struct Template Reference

<p>adds support for formatting <a href="/web-doxygen/docs/api/classes/entrytype">EntryType</a> <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct fmt::formatter&lt;EntryType&gt; { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0c7dc84a38f6dbbed83c3151dc94fe8">format</a> (EntryType type, format_context &amp;ctx) const</td>
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

<p>adds support for formatting <a href="/web-doxygen/docs/api/classes/entrytype">EntryType</a></p>

<p>Definition at line 240 of file <a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### format() {#ab0c7dc84a38f6dbbed83c3151dc94fe8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto fmt::formatter&lt; EntryType &gt;::format (<a href="/web-doxygen/docs/api/classes/entrytype">EntryType</a> type, format_context &amp; ctx)</td>
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



<p>Definition at line 242 of file <a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab0c7dc84a38f6dbbed83c3151dc94fe8">242</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="#ab0c7dc84a38f6dbbed83c3151dc94fe8">format</a>(<a href="/web-doxygen/docs/api/classes/entrytype">EntryType</a> type, format_context&amp; ctx)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/fmt/formatter">formatter&lt;std::string&gt;::format</a>(type.<a href="/web-doxygen/docs/api/classes/entrytype/#a79fde91d4bd9fbc05e2238b983b8dc18">to_string</a>(),ctx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/entrytype/#a79fde91d4bd9fbc05e2238b983b8dc18">EntryType::to_string</a>.</p>

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
