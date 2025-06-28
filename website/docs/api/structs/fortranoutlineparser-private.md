---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/fortranoutlineparser/private
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Private` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct FortranOutlineParser::Private { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a775249ff6240140781b373d7c12de338">Private</a> (FortranFormat fmt)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fceca25b1c7e5269c23ec7b3cbfaef7">yyscanner</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/fortranscanneryy-state">fortranscannerYY_state</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04acd996bd4b1125f80d12669ddfd27b">extra</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266">FortranFormat</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80536a5e3f6b3715553d3c0c108e4c1f">format</a></td>
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


<p>Definition at line 3329 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### Private() {#a775249ff6240140781b373d7c12de338}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FortranOutlineParser::Private::Private (<a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266">FortranFormat</a> fmt)</td>
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


<p>Definition at line 3334 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a775249ff6240140781b373d7c12de338">3334</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a775249ff6240140781b373d7c12de338">Private</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266">FortranFormat</a> <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>) : <a href="#a80536a5e3f6b3715553d3c0c108e4c1f">format</a>(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3335</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3336</span><span class="doxyLineContent"><span class="doxyHighlight">    fortranscannerYYlex_init_extra(&amp;<a href="#a04acd996bd4b1125f80d12669ddfd27b">extra</a>,&amp;<a href="#a9fceca25b1c7e5269c23ec7b3cbfaef7">yyscanner</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3337</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3338</span><span class="doxyLineContent"><span class="doxyHighlight">    fortranscannerYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da091a33c7c46121c2ed6ca91caf90462e">Debug::Lex_fortranscanner</a>) ? 1 : 0,<a href="#a9fceca25b1c7e5269c23ec7b3cbfaef7">yyscanner</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3339</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3340</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a04acd996bd4b1125f80d12669ddfd27b">extra</a>, <a href="#a80536a5e3f6b3715553d3c0c108e4c1f">format</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da091a33c7c46121c2ed6ca91caf90462e">Debug::Lex&#95;fortranscanner</a> and <a href="#a9fceca25b1c7e5269c23ec7b3cbfaef7">yyscanner</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### extra {#a04acd996bd4b1125f80d12669ddfd27b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">fortranscannerYY_state FortranOutlineParser::Private::extra</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 3332 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a04acd996bd4b1125f80d12669ddfd27b">3332</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/fortranscanneryy-state">fortranscannerYY_state</a> <a href="#a04acd996bd4b1125f80d12669ddfd27b">extra</a>;</span></span></div>

</div>


Referenced by <a href="#a775249ff6240140781b373d7c12de338">Private</a>.
</div>
</div>

### format {#a80536a5e3f6b3715553d3c0c108e4c1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FortranFormat FortranOutlineParser::Private::format</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 3333 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a80536a5e3f6b3715553d3c0c108e4c1f">3333</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#ad3f2a8c13ceee9c0aaeabf930dd88266">FortranFormat</a> <a href="#a80536a5e3f6b3715553d3c0c108e4c1f">format</a>;</span></span></div>

</div>


Referenced by <a href="#a775249ff6240140781b373d7c12de338">Private</a>.
</div>
</div>

### yyscanner {#a9fceca25b1c7e5269c23ec7b3cbfaef7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">yyscan_t FortranOutlineParser::Private::yyscanner</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 3331 of file <a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9fceca25b1c7e5269c23ec7b3cbfaef7">3331</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> <a href="#a9fceca25b1c7e5269c23ec7b3cbfaef7">yyscanner</a>;</span></span></div>

</div>


Referenced by <a href="#a775249ff6240140781b373d7c12de338">Private</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/fortranscanner-l">fortranscanner.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
