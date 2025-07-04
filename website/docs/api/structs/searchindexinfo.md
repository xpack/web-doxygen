---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/searchindexinfo
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SearchIndexInfo` Struct Reference

<p>Table entry to allow filtering the search results per category. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct SearchIndexInfo { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/searchindex-js-h">src/searchindex_js.h</a>&gt;
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52b5729b3bc658fa7fa77497e95213fd">add</a> (const SearchTerm &amp;term)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad2e21c710b230a1844ed96560bd3659">name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()&gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbcde52048e72323614683e214f2cce8">getText</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/searchindex-js-h/#a6fe653d20eef95da0fd767e131b796b7">SearchIndexMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab250a5688a170b30a64030a2139f529">symbolMap</a></td>
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

<p>Table entry to allow filtering the search results per category.</p>

<p>Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>.</p>


<div class="doxySectionDef">

## Public Member Functions

### add() {#a52b5729b3bc658fa7fa77497e95213fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SearchIndexInfo::add (const <a href="/web-doxygen/docs/api/structs/searchterm">SearchTerm</a> &amp; term)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>, definition at line 857 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp">searchindex_js.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52b5729b3bc658fa7fa77497e95213fd">857</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a52b5729b3bc658fa7fa77497e95213fd">SearchIndexInfo::add</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/searchterm">SearchTerm</a> &amp;<a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string letter = <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>(<a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>(<a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.word.str(),0));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;list = <a href="#aab250a5688a170b30a64030a2139f529">symbolMap</a>[letter]; </span><span class="doxyHighlightComment">// creates a new entry if not found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">  list.push_back(<a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>, <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>, <a href="#aab250a5688a170b30a64030a2139f529">symbolMap</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### getText {#adbcde52048e72323614683e214f2cce8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;QCString()&gt; SearchIndexInfo::getText</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adbcde52048e72323614683e214f2cce8">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::function&lt;<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()&gt; <a href="#adbcde52048e72323614683e214f2cce8">getText</a>;</span></span></div>

</div>

</div>
</div>

### name {#aad2e21c710b230a1844ed96560bd3659}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString SearchIndexInfo::name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad2e21c710b230a1844ed96560bd3659">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aad2e21c710b230a1844ed96560bd3659">name</a>;</span></span></div>

</div>

</div>
</div>

### symbolMap {#aab250a5688a170b30a64030a2139f529}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SearchIndexMap SearchIndexInfo::symbolMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aab250a5688a170b30a64030a2139f529">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/searchindex-js-h/#a6fe653d20eef95da0fd767e131b796b7">SearchIndexMap</a> <a href="#aab250a5688a170b30a64030a2139f529">symbolMap</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a52b5729b3bc658fa7fa77497e95213fd">add</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp">searchindex_js.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
