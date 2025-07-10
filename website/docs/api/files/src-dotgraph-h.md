---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/dotgraph-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `dotgraph.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;iostream&gt;
#include &lt;map&gt;
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dotgraph">DotGraph</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>A dot graph. <a href="/web-doxygen/docs/api/classes/dotgraph/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">GraphOutputFormat { <a href="#ac60ef98d62b78366a17c9f1bda96523f">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">EmbeddedOutputFormat { <a href="#a8680135da08a5ef57cebe20060912dcc">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">GraphType { <a href="#a0c7c85309652245e03563b127f451f72">...</a> }</td>
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

## Enumerations

### EmbeddedOutputFormat {#a8680135da08a5ef57cebe20060912dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class EmbeddedOutputFormat </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Html<a id="a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LaTeX<a id="a8680135da08a5ef57cebe20060912dcca5766dea037e9097ac6869424b65fe7b6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Rtf<a id="a8680135da08a5ef57cebe20060912dccaca9a0e8f64d43d81dd7b0225ea1b19c5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DocBook<a id="a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 30 of file <a href="/web-doxygen/docs/api/files/src/dotgraph-h">dotgraph.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">30</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#a8680135da08a5ef57cebe20060912dcc">EmbeddedOutputFormat</a> { <a href="#a8680135da08a5ef57cebe20060912dcca3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="#a8680135da08a5ef57cebe20060912dcca5766dea037e9097ac6869424b65fe7b6">LaTeX</a>, <a href="#a8680135da08a5ef57cebe20060912dccaca9a0e8f64d43d81dd7b0225ea1b19c5">Rtf</a>, <a href="#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">DocBook</a> };</span></span></div>

</div>

</div>
</div>

### GraphOutputFormat {#ac60ef98d62b78366a17c9f1bda96523f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class GraphOutputFormat </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BITMAP<a id="ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EPS<a id="ac60ef98d62b78366a17c9f1bda96523fac2c027d8c62500300145c3043546d4c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/dotgraph-h">dotgraph.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">29</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a>    { <a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35a75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35ac2c027d8c62500300145c3043546d4c6">EPS</a> };</span></span></div>

</div>

</div>
</div>

### GraphType {#a0c7c85309652245e03563b127f451f72}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class GraphType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dependency<a id="a0c7c85309652245e03563b127f451f72a90a95d6639a7bbbeff7f36a7ec8f3b10"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Inheritance<a id="a0c7c85309652245e03563b127f451f72ae40489cd1e7102e35469c937e05c8bba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Collaboration<a id="a0c7c85309652245e03563b127f451f72a337e8f4aa741ef97ec3ed8fd7b1accb7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Hierarchy<a id="a0c7c85309652245e03563b127f451f72a0748856bca50f42e2abd5b36ca083bae"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CallGraph<a id="a0c7c85309652245e03563b127f451f72a9d0f6d0fe9c95c9cb09769b9879db1ff"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/dotgraph-h">dotgraph.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c7c85309652245e03563b127f451f72a9d0f6d0fe9c95c9cb09769b9879db1ff">31</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#a0c7c85309652245e03563b127f451f72">GraphType</a>            { <a href="#a0c7c85309652245e03563b127f451f72a90a95d6639a7bbbeff7f36a7ec8f3b10">Dependency</a>, <a href="#a0c7c85309652245e03563b127f451f72ae40489cd1e7102e35469c937e05c8bba">Inheritance</a>, <a href="#a0c7c85309652245e03563b127f451f72a337e8f4aa741ef97ec3ed8fd7b1accb7">Collaboration</a>, <a href="#a0c7c85309652245e03563b127f451f72a0748856bca50f42e2abd5b36ca083bae">Hierarchy</a>, <a href="#a0c7c85309652245e03563b127f451f72a9d0f6d0fe9c95c9cb09769b9879db1ff">CallGraph</a> };</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
