---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/anchor-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `anchor.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;mutex&gt;
#include &lt;algorithm&gt;
#include &lt;string&gt;
#include &lt;unordered_map&gt;
#include "<a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/containers-h">containers.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anchorgenerator/private">Private</a></td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">constexpr auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> = "autotoc&#95;md"</td>
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


<div class="doxySectionDef">

## Variables

### prefix {#a85ba602a660bdb3bbeb43cc600de3008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto prefix = "autotoc&#95;md"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00044">44</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85ba602a660bdb3bbeb43cc600de3008">44</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> = </span><span class="doxyHighlightStringLiteral">"autotoc_md"</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a54e3a84d24e7a6e688ebd6b46a566544">AnchorGenerator::addPrefixIfNeeded</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6c177ac509924d60c71b820d39d28b9f">addRefItem</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#a64ba1596ef3046e773e49494e9e25913">do&#95;warn</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a3e9a28f1f5867cc3d2de69b7db30c15f">DotGfxHierarchyTable::DotGfxHierarchyTable</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a10ee707ef187621006c30d021aaca34d">DocbookGenerator::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a726c53bd6e118a6ab62e6022c7dd80e6">HtmlGenerator::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#abf013b4910ce277b5817939000707c4d">LatexGenerator::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/outputgenintf/#a41b77727f57a04d415d7acfa77dfcf13">OutputGenIntf::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a60a7f30e2f0edb92bd5ce06d1259340f">OutputList::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a55a01085b53c2fdb7176edfa10ebcc7b">RTFGenerator::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab57dc156537618baf0946481157bb2ab">generateDiskNames</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a72b6d57151d45a13c60402914aa50831">PerlModGenerator::generateDoxyRules</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a473b6bd63ac2f9ea9fe6de4f8170194b">PerlModGenerator::generateMakefile</a>, <a href="/web-doxygen/docs/api/classes/formulamanager/#a10998c967b5e151acf3dad299deb0bc9">FormulaManager::initFromRepository</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0a8299ea0705cebde431ef0ea600fcb1">DirDefImpl::matchPath</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a39bb7d9a1e431158cb3a423215f044bb">processTagLessClasses</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f8f5d3945f14c61917b96db9ca84980">resolveSymlink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a3524dfec9219699243b6baf0f33bd0f1">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a> and <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
