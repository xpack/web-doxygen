---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/outputcoderecorder/callinfo
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `CallInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct OutputCodeRecorder::CallInfo { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1911afcf6a3eeba349c18893034fd0d2">ConditionFunc</a> = std::function&lt; bool()&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad99464689c5cc7195d97f05d5ab05826">OutputFunc</a> = std::function&lt; void(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> *)&gt;</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07bb1463acc12b8408d7416e0849d10c">CallInfo</a> (ConditionFunc &amp;&amp;c, OutputFunc &amp;&amp;f, bool ic)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a1911afcf6a3eeba349c18893034fd0d2">ConditionFunc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae8db15f2928e88b8bffc3dbaa4bacb5a">condition</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad99464689c5cc7195d97f05d5ab05826">OutputFunc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28185bcfa3f04ba1f21914c72b3356ca">function</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85c26ccca6c7d66e2558538af7abaf92">insideSpecialComment</a> = false</td>
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


<p>Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxySectionDef">

## Public Member Typedefs

### ConditionFunc {#a1911afcf6a3eeba349c18893034fd0d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using OutputCodeRecorder::CallInfo::ConditionFunc =  std::function&lt;bool()&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1911afcf6a3eeba349c18893034fd0d2">144</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a1911afcf6a3eeba349c18893034fd0d2">ConditionFunc</a> = std::function&lt;bool()&gt;;</span></span></div>

</div>

</div>
</div>

### OutputFunc {#ad99464689c5cc7195d97f05d5ab05826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using OutputCodeRecorder::CallInfo::OutputFunc =  std::function&lt;void(OutputCodeList*)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad99464689c5cc7195d97f05d5ab05826">145</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ad99464689c5cc7195d97f05d5ab05826">OutputFunc</a>    = std::function&lt;void(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a>*)&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CallInfo() {#a07bb1463acc12b8408d7416e0849d10c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeRecorder::CallInfo::CallInfo (<a href="#a1911afcf6a3eeba349c18893034fd0d2">ConditionFunc</a> &amp;&amp; c, <a href="#ad99464689c5cc7195d97f05d5ab05826">OutputFunc</a> &amp;&amp; f, bool ic)</td>
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


<p>Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07bb1463acc12b8408d7416e0849d10c">146</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a07bb1463acc12b8408d7416e0849d10c">CallInfo</a>(<a href="#a1911afcf6a3eeba349c18893034fd0d2">ConditionFunc</a> &amp;&amp;c,<a href="#ad99464689c5cc7195d97f05d5ab05826">OutputFunc</a> &amp;&amp;f,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ic)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">        : <a href="#ae8db15f2928e88b8bffc3dbaa4bacb5a">condition</a>(std::move(c)), <a href="#a28185bcfa3f04ba1f21914c72b3356ca">function</a>(std::move(f)), <a href="#a85c26ccca6c7d66e2558538af7abaf92">insideSpecialComment</a>(ic) {}</span></span></div>

</div>


References <a href="#ae8db15f2928e88b8bffc3dbaa4bacb5a">condition</a>, <a href="#a28185bcfa3f04ba1f21914c72b3356ca">function</a> and <a href="#a85c26ccca6c7d66e2558538af7abaf92">insideSpecialComment</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### condition {#ae8db15f2928e88b8bffc3dbaa4bacb5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConditionFunc OutputCodeRecorder::CallInfo::condition</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 148 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae8db15f2928e88b8bffc3dbaa4bacb5a">148</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1911afcf6a3eeba349c18893034fd0d2">ConditionFunc</a>  <a href="#ae8db15f2928e88b8bffc3dbaa4bacb5a">condition</a>;</span></span></div>

</div>


Referenced by <a href="#a07bb1463acc12b8408d7416e0849d10c">CallInfo</a>.
</div>
</div>

### function {#a28185bcfa3f04ba1f21914c72b3356ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputFunc OutputCodeRecorder::CallInfo::function</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 149 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28185bcfa3f04ba1f21914c72b3356ca">149</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad99464689c5cc7195d97f05d5ab05826">OutputFunc</a>     <a href="#a28185bcfa3f04ba1f21914c72b3356ca">function</a>;</span></span></div>

</div>


Referenced by <a href="#a07bb1463acc12b8408d7416e0849d10c">CallInfo</a>.
</div>
</div>

### insideSpecialComment {#a85c26ccca6c7d66e2558538af7abaf92}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OutputCodeRecorder::CallInfo::insideSpecialComment = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85c26ccca6c7d66e2558538af7abaf92">150</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">           <a href="#a85c26ccca6c7d66e2558538af7abaf92">insideSpecialComment</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a07bb1463acc12b8408d7416e0849d10c">CallInfo</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
