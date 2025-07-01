---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/stlsupport-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `stlsupport.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;memory&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e8cfe5b2cd5bf238c936a13169f7e76">addSTLSupport</a> (std::shared_ptr&lt; Entry &gt; &amp;root)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Add stub entries for the most used classes in the standard template library. <a href="#a9e8cfe5b2cd5bf238c936a13169f7e76">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>


<div class="doxySectionDef">

## Functions

### addSTLSupport() {#a9e8cfe5b2cd5bf238c936a13169f7e76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addSTLSupport (std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Add stub entries for the most used classes in the standard template library.


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">root</td>
<td class="doxyParamItemDescription">Root of the entry tree to add the entries to.</td>
</tr>
</table>
</dd>
</dl>

Declaration at line 27 of file <a href="/web-doxygen/docs/api/files/src/stlsupport-h">stlsupport.h</a>, definition at line 266 of file <a href="/web-doxygen/docs/api/files/src/stlsupport-cpp">stlsupport.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/stlsupport-cpp/#a9e8cfe5b2cd5bf238c936a13169f7e76">266</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/stlsupport-cpp/#a9e8cfe5b2cd5bf238c936a13169f7e76">addSTLSupport</a>(std::shared_ptr&lt;Entry&gt; &amp;root)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(BUILTIN_STL_SUPPORT))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/stlsupport-cpp/#a95efd6a7d367cd542aa4949c0e5bcdff">addSTLClasses</a>(root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/stlsupport-cpp/#a95efd6a7d367cd542aa4949c0e5bcdff">addSTLClasses</a> and <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
