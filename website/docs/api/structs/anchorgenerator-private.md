---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/anchorgenerator/private
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
struct AnchorGenerator::Private { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08d5a5b3420298ba3a62c2d15559ca33">anchorsUsed</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a376c688fde2f862b0021b3ebb27ebb78">anchorCount</a> =0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7055325089de5d64264c46d82d70d68">mutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5bb27b005bbd62cf169be692fa3a0bbd">idCount</a></td>
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


<p>Definition at line 26 of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxySectionDef">

## Public Member Attributes

### anchorCount {#a376c688fde2f862b0021b3ebb27ebb78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int AnchorGenerator::Private::anchorCount =0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#l00029">29</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a376c688fde2f862b0021b3ebb27ebb78">29</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a376c688fde2f862b0021b3ebb27ebb78">anchorCount</a>=0;</span></span></div>

</div>

</div>
</div>

### anchorsUsed {#a08d5a5b3420298ba3a62c2d15559ca33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringUnorderedSet AnchorGenerator::Private::anchorsUsed</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#l00028">28</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a08d5a5b3420298ba3a62c2d15559ca33">28</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a> <a href="#a08d5a5b3420298ba3a62c2d15559ca33">anchorsUsed</a>;</span></span></div>

</div>

</div>
</div>

### idCount {#a5bb27b005bbd62cf169be692fa3a0bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string,int&gt; AnchorGenerator::Private::idCount</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#l00031">31</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5bb27b005bbd62cf169be692fa3a0bbd">31</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::unordered_map&lt;std::string,int&gt; <a href="#a5bb27b005bbd62cf169be692fa3a0bbd">idCount</a>;</span></span></div>

</div>

</div>
</div>

### mutex {#ab7055325089de5d64264c46d82d70d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex AnchorGenerator::Private::mutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#l00030">30</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab7055325089de5d64264c46d82d70d68">30</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::mutex <a href="#ab7055325089de5d64264c46d82d70d68">mutex</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
