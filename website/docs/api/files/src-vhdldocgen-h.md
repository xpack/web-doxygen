---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/vhdldocgen-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `vhdldocgen.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/layout-h">layout.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/vhdlconfnode">VhdlConfNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdldocgen">VhdlDocGen</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class for generating documentation specific for VHDL. <a href="/web-doxygen/docs/api/classes/vhdldocgen/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/flowchart">FlowChart</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/classes/flowchart">FlowChart</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58b3784e26a172c464443fb55a30364d">flowList</a></td>
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

### flowList {#a58b3784e26a172c464443fb55a30364d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;FlowChart&gt; flowList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 316 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>, definition at line 2547 of file <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp">vhdldocgen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a58b3784e26a172c464443fb55a30364d">2547</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::vector&lt;FlowChart&gt; <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a58b3784e26a172c464443fb55a30364d">flowList</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/flowchart/#a5e2d1232239471126aade777574d9d34">FlowChart::addFlowChart</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#abe5bc298b8ac3b911af947e2b29089f5">FlowChart::buildCommentNodes</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a6fc7dfce3416355a82991f015431b854">FlowChart::colTextNodes</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a64f98636bae1290688ea4bc06d02e86f">FlowChart::delFlowList</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a590a484692d935d4850c7e6bce508d01">FlowChart::findLabel</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a82fc425100d1cf68c08bad05195bf2f3">FlowChart::findNextLoop</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#aba76e82b248e1113568acd458e2b7b21">FlowChart::findNode</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a0305aa29048ee638ab09b4dc4bf28a9f">FlowChart::findPrevLoop</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a948abd6948d3e24f3e9dec7eff2c3a18">FlowChart::getNextIfLink</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a660d99edcee9c4dd556b42b8aa1dd4da">FlowChart::getNextNode</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a25647e6b336425f3f5ccef2ecea0dcf1">FlowChart::printFlowTree</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#acf7119e47c96291250aee1c5c98ac794">FlowChart::printUmlTree</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a66989e6892ad6bbb539241dedbfc4f9e">FlowChart::writeFlowChart</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#ad0135f07f9ef7ebdbef4b5f09a255397">FlowChart::writeFlowLinks</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
