---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/outputcodelist/outputcodeelem
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `OutputCodeElem` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct OutputCodeList::OutputCodeElem { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae25e5eeaa9320f9082f466e2e0ab0daf">OutputCodeElem</a> (OutputCodeIntfPtr &amp;&amp;p)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc2756e4e03804164c920379798c3e2b">OutputCodeElem</a> (const OutputCodeElem &amp;other)</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/outputcodelist/outputcodeelem">OutputCodeElem</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85f8012fd68ae35d80bfdd65bfb1d094">operator=</a> (const OutputCodeElem &amp;other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputcodelist/#ad0248da81685b845dbcb3be28f243fe6">OutputCodeIntfPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad032e376e9294df84ec5401adec06440">intf</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cd9c732bcea08f905d348362bf772ed">enabled</a> = true</td>
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


Definition at line 169 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxySectionDef">

## Public Constructors

### OutputCodeElem() {#ae25e5eeaa9320f9082f466e2e0ab0daf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeList::OutputCodeElem::OutputCodeElem (<a href="/web-doxygen/docs/api/classes/outputcodelist/#ad0248da81685b845dbcb3be28f243fe6">OutputCodeIntfPtr</a> &amp;&amp; p)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 171 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae25e5eeaa9320f9082f466e2e0ab0daf">171</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#ae25e5eeaa9320f9082f466e2e0ab0daf">OutputCodeElem</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist/#ad0248da81685b845dbcb3be28f243fe6">OutputCodeIntfPtr</a> &amp;&amp;p) : <a href="#ad032e376e9294df84ec5401adec06440">intf</a>(std::move(p)) {}</span></span></div>

</div>


Reference <a href="#ad032e376e9294df84ec5401adec06440">intf</a>.

Referenced by <a href="#a85f8012fd68ae35d80bfdd65bfb1d094">operator=</a> and <a href="#abc2756e4e03804164c920379798c3e2b">OutputCodeElem</a>.
</div>
</div>

### OutputCodeElem() {#abc2756e4e03804164c920379798c3e2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeList::OutputCodeElem::OutputCodeElem (const <a href="/web-doxygen/docs/api/structs/outputcodelist/outputcodeelem">OutputCodeElem</a> &amp; other)</td>
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



Definition at line 172 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abc2756e4e03804164c920379798c3e2b">172</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abc2756e4e03804164c920379798c3e2b">OutputCodeElem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ae25e5eeaa9320f9082f466e2e0ab0daf">OutputCodeElem</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad032e376e9294df84ec5401adec06440">intf</a> = other.<a href="#ad032e376e9294df84ec5401adec06440">intf</a>-&gt;clone();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a9cd9c732bcea08f905d348362bf772ed">enabled</a> = other.<a href="#a9cd9c732bcea08f905d348362bf772ed">enabled</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


References <a href="#a9cd9c732bcea08f905d348362bf772ed">enabled</a>, <a href="#ad032e376e9294df84ec5401adec06440">intf</a> and <a href="#ae25e5eeaa9320f9082f466e2e0ab0daf">OutputCodeElem</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a85f8012fd68ae35d80bfdd65bfb1d094}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeElem &amp; OutputCodeList::OutputCodeElem::operator= (const <a href="/web-doxygen/docs/api/structs/outputcodelist/outputcodeelem">OutputCodeElem</a> &amp; other)</td>
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



Definition at line 177 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85f8012fd68ae35d80bfdd65bfb1d094">177</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae25e5eeaa9320f9082f466e2e0ab0daf">OutputCodeElem</a> &amp;<a href="#a85f8012fd68ae35d80bfdd65bfb1d094">operator=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ae25e5eeaa9320f9082f466e2e0ab0daf">OutputCodeElem</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (&amp;other!=</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad032e376e9294df84ec5401adec06440">intf</a> = other.<a href="#ad032e376e9294df84ec5401adec06440">intf</a>-&gt;clone();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a9cd9c732bcea08f905d348362bf772ed">enabled</a> = other.<a href="#a9cd9c732bcea08f905d348362bf772ed">enabled</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>

</div>


References <a href="#a9cd9c732bcea08f905d348362bf772ed">enabled</a>, <a href="#ad032e376e9294df84ec5401adec06440">intf</a> and <a href="#ae25e5eeaa9320f9082f466e2e0ab0daf">OutputCodeElem</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### enabled {#a9cd9c732bcea08f905d348362bf772ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OutputCodeList::OutputCodeElem::enabled = true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 187 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9cd9c732bcea08f905d348362bf772ed">187</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9cd9c732bcea08f905d348362bf772ed">enabled</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a85f8012fd68ae35d80bfdd65bfb1d094">operator=</a> and <a href="#abc2756e4e03804164c920379798c3e2b">OutputCodeElem</a>.
</div>
</div>

### intf {#ad032e376e9294df84ec5401adec06440}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeIntfPtr OutputCodeList::OutputCodeElem::intf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 186 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad032e376e9294df84ec5401adec06440">186</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputcodelist/#ad0248da81685b845dbcb3be28f243fe6">OutputCodeIntfPtr</a> <a href="#ad032e376e9294df84ec5401adec06440">intf</a>;</span></span></div>

</div>


Referenced by <a href="#a85f8012fd68ae35d80bfdd65bfb1d094">operator=</a>, <a href="#abc2756e4e03804164c920379798c3e2b">OutputCodeElem</a> and <a href="#ae25e5eeaa9320f9082f466e2e0ab0daf">OutputCodeElem</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
