---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/outputlist-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `outputlist.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;utility&gt;
#include &lt;vector&gt;
#include &lt;memory&gt;
#include &lt;variant&gt;
#include &lt;stack&gt;
#include &lt;functional&gt;
#include "<a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmlgen-h">htmlgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/rtfgen-h">rtfgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/mangen-h">mangen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/devnullgen-h">devnullgen.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer&lt;OutputCodeGen&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper template class which defers all methods of <a href="/web-doxygen/docs/api/classes/outputcodeintf">OutputCodeIntf</a> to an existing object of the templated type. <a href="/web-doxygen/docs/api/classes/outputcodedefer/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputcoderecorder">OutputCodeRecorder</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Implementation that allows capturing calls made to the code interface to later invoke them on a <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> via <a href="/web-doxygen/docs/api/classes/outputcoderecorder/#a89166fa9eb6c282a2351da070e85fe63">replay()</a>. <a href="/web-doxygen/docs/api/classes/outputcoderecorder/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/outputcoderecorder/callinfo">CallInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class representing a list of different code generators. <a href="/web-doxygen/docs/api/classes/outputcodelist/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/outputcodelist/outputcodeelem">OutputCodeElem</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class representing a list of output generators that are written to in parallel. <a href="/web-doxygen/docs/api/classes/outputlist/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/outputlist/outputgenelem">OutputGenElem</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6bfa5e817e6c7a7250c6ad815f2e192a">HtmlCodeGeneratorDefer</a> = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer</a>&lt; <a href="/web-doxygen/docs/api/classes/htmlcodegenerator">HtmlCodeGenerator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a680a5c4f5a9f76906bec245403480fe0">LatexCodeGeneratorDefer</a> = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer</a>&lt; <a href="/web-doxygen/docs/api/classes/latexcodegenerator">LatexCodeGenerator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56745c55d69bd82e3e154c66fb576518">RTFCodeGeneratorDefer</a> = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer</a>&lt; <a href="/web-doxygen/docs/api/classes/rtfcodegenerator">RTFCodeGenerator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa20e56dfdf2045583c6ee349f0a3827">ManCodeGeneratorDefer</a> = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer</a>&lt; <a href="/web-doxygen/docs/api/classes/mancodegenerator">ManCodeGenerator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81f21cc2a33cdb152b10f341e2c8e5e7">DocbookCodeGeneratorDefer</a> = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer</a>&lt; <a href="/web-doxygen/docs/api/classes/docbookcodegenerator">DocbookCodeGenerator</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c20e2f254c7b19e484db725425ad8a7">OutputCodeDeferExtension</a> = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer</a>&lt; <a href="/web-doxygen/docs/api/classes/outputcodeintf">OutputCodeIntf</a> &gt;</td>
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

## Typedefs

### DocbookCodeGeneratorDefer {#a81f21cc2a33cdb152b10f341e2c8e5e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DocbookCodeGeneratorDefer =  OutputCodeDefer&lt;DocbookCodeGenerator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81f21cc2a33cdb152b10f341e2c8e5e7">105</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a81f21cc2a33cdb152b10f341e2c8e5e7">DocbookCodeGeneratorDefer</a> = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer&lt;DocbookCodeGenerator&gt;</a>;</span></span></div>

</div>

</div>
</div>

### HtmlCodeGeneratorDefer {#a6bfa5e817e6c7a7250c6ad815f2e192a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using HtmlCodeGeneratorDefer =  OutputCodeDefer&lt;HtmlCodeGenerator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6bfa5e817e6c7a7250c6ad815f2e192a">101</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a6bfa5e817e6c7a7250c6ad815f2e192a">HtmlCodeGeneratorDefer</a>    = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer&lt;HtmlCodeGenerator&gt;</a>;</span></span></div>

</div>

</div>
</div>

### LatexCodeGeneratorDefer {#a680a5c4f5a9f76906bec245403480fe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using LatexCodeGeneratorDefer =  OutputCodeDefer&lt;LatexCodeGenerator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 102 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a680a5c4f5a9f76906bec245403480fe0">102</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a680a5c4f5a9f76906bec245403480fe0">LatexCodeGeneratorDefer</a>   = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer&lt;LatexCodeGenerator&gt;</a>;</span></span></div>

</div>

</div>
</div>

### ManCodeGeneratorDefer {#afa20e56dfdf2045583c6ee349f0a3827}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ManCodeGeneratorDefer =  OutputCodeDefer&lt;ManCodeGenerator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa20e56dfdf2045583c6ee349f0a3827">104</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#afa20e56dfdf2045583c6ee349f0a3827">ManCodeGeneratorDefer</a>     = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer&lt;ManCodeGenerator&gt;</a>;</span></span></div>

</div>

</div>
</div>

### OutputCodeDeferExtension {#a5c20e2f254c7b19e484db725425ad8a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using OutputCodeDeferExtension =  OutputCodeDefer&lt;OutputCodeIntf&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5c20e2f254c7b19e484db725425ad8a7">106</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a5c20e2f254c7b19e484db725425ad8a7">OutputCodeDeferExtension</a>  = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer&lt;OutputCodeIntf&gt;</a>;</span></span></div>

</div>

</div>
</div>

### RTFCodeGeneratorDefer {#a56745c55d69bd82e3e154c66fb576518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using RTFCodeGeneratorDefer =  OutputCodeDefer&lt;RTFCodeGenerator&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a56745c55d69bd82e3e154c66fb576518">103</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a56745c55d69bd82e3e154c66fb576518">RTFCodeGeneratorDefer</a>     = <a href="/web-doxygen/docs/api/classes/outputcodedefer">OutputCodeDefer&lt;RTFCodeGenerator&gt;</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
