---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/outputgenerator
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `OutputGenerator` Class Reference

<p>Base class for shared implementation for all output generators. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class OutputGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/outputgen-h">src/outputgen.h</a>&gt;
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docbookgenerator">DocbookGenerator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/htmlgenerator">HtmlGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for HTML output. <a href="/web-doxygen/docs/api/classes/htmlgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/latexgenerator">LatexGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for LaTeX output. <a href="/web-doxygen/docs/api/classes/latexgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/mangenerator">ManGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for Man page output. <a href="/web-doxygen/docs/api/classes/mangenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/rtfgenerator">RTFGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for RTF output. <a href="/web-doxygen/docs/api/classes/rtfgenerator/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ParamListTypes { <a href="#a4b3d519f1325b61f2abfe2647d6f1b2b">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">MemberItemType { <a href="#a94f2e5794dffec4be4d53d644f5e4dcb">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8716724782730065f43ea240f93917b0">OutputGenerator</a> (const QCString &amp;dir)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8efbb8581dc2f9864a3170912e816370">~OutputGenerator</a> ()=default</td>
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

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a595e39d22e92ac09d24706829b532b00">dir</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d2b81663565fee4440ef02fe9b3a197">startPlainFile</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaacf2b4efc09a2c06b9dd8cc2af69046">endPlainFile</a> ()</td>
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

## Protected Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textstream">TextStream</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aceba8f7a334d2e60297dcc727959796c">m_t</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaaa814308a1fd901771b9b6e4a176d58">m_dir</a></td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3ebfdcdf8c6d12985d69330ca910dcc">m_fileName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">FILE *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74e9a6ba3085c8b710a81d709ea44547">m_file</a> = nullptr</td>
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

<p>Base class for shared implementation for all output generators.</p>

<p>Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### MemberItemType {#a94f2e5794dffec4be4d53d644f5e4dcb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class OutputGenerator::MemberItemType </td>
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
<td class="doxyEnumItemName">Normal<a id="a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AnonymousStart<a id="a94f2e5794dffec4be4d53d644f5e4dcbab6a2a9526e77d22267f5d5568a477041"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AnonymousEnd<a id="a94f2e5794dffec4be4d53d644f5e4dcba8475427fd01aab02bf1bb0f3d280af17"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Templated<a id="a94f2e5794dffec4be4d53d644f5e4dcbaf756dbefd44dd9270c676f74fb8d3708"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00104">104</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a94f2e5794dffec4be4d53d644f5e4dcba8475427fd01aab02bf1bb0f3d280af17">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a> { <a href="#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">Normal</a>, <a href="#a94f2e5794dffec4be4d53d644f5e4dcbab6a2a9526e77d22267f5d5568a477041">AnonymousStart</a>, <a href="#a94f2e5794dffec4be4d53d644f5e4dcba8475427fd01aab02bf1bb0f3d280af17">AnonymousEnd</a>, <a href="#a94f2e5794dffec4be4d53d644f5e4dcbaf756dbefd44dd9270c676f74fb8d3708">Templated</a> };</span></span></div>

</div>

</div>
</div>

### ParamListTypes {#a4b3d519f1325b61f2abfe2647d6f1b2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class OutputGenerator::ParamListTypes </td>
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
<td class="doxyEnumItemName">Param<a id="a4b3d519f1325b61f2abfe2647d6f1b2bab7dccc7d9373cd4717256318909fcebe"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RetVal<a id="a4b3d519f1325b61f2abfe2647d6f1b2ba5d910d027746295d5096b5b1a0e3a401"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Exception<a id="a4b3d519f1325b61f2abfe2647d6f1b2bab0d4998a26f5b5742ad38c4af8817e32"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00103">103</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4b3d519f1325b61f2abfe2647d6f1b2bab0d4998a26f5b5742ad38c4af8817e32">103</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#a4b3d519f1325b61f2abfe2647d6f1b2b">ParamListTypes</a> { <a href="#a4b3d519f1325b61f2abfe2647d6f1b2bab7dccc7d9373cd4717256318909fcebe">Param</a>, <a href="#a4b3d519f1325b61f2abfe2647d6f1b2ba5d910d027746295d5096b5b1a0e3a401">RetVal</a>, <a href="#a4b3d519f1325b61f2abfe2647d6f1b2bab0d4998a26f5b5742ad38c4af8817e32">Exception</a> };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OutputGenerator() {#a6f6f6c92438ea4e7553e317d5bb17660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputGenerator::OutputGenerator ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00101">101</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f6f6c92438ea4e7553e317d5bb17660">101</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator</a>() : <a href="#aceba8f7a334d2e60297dcc727959796c">m_t</a>(40*1024) {}</span></span></div>

</div>


Reference <a href="#aceba8f7a334d2e60297dcc727959796c">m&#95;t</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a59655593be449f9e01ce953a72233de0">DocbookGenerator::DocbookGenerator</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator::DocbookGenerator</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator::HtmlGenerator</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator::HtmlGenerator</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ae145cddfcb7ce9a667be80989bc6f865">LatexGenerator::LatexGenerator</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab2cb30e88fdc934a8f0c664db36e6028">LatexGenerator::LatexGenerator</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ad234c57631aa6f20632d21fbcc300a4c">ManGenerator::ManGenerator</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ad5d7852c208c4c26f344ff3c512a0f87">ManGenerator::ManGenerator</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ad19e0af9634ae061da9492887d9770bd">RTFGenerator::RTFGenerator</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a1d5e3edbb7716cd984a54034039059d5">RTFGenerator::RTFGenerator</a> and <a href="#a8efbb8581dc2f9864a3170912e816370">~OutputGenerator</a>.
</div>
</div>

### OutputGenerator() {#a8716724782730065f43ea240f93917b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputGenerator::OutputGenerator (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; dir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00106">106</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-cpp/#l00027">27</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-cpp">outputgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8716724782730065f43ea240f93917b0">27</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator::OutputGenerator</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a595e39d22e92ac09d24706829b532b00">dir</a>) : <a href="#aceba8f7a334d2e60297dcc727959796c">m_t</a>(nullptr), <a href="#aaaa814308a1fd901771b9b6e4a176d58">m_dir</a>(<a href="#a595e39d22e92ac09d24706829b532b00">dir</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">28</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("OutputGenerator::OutputGenerator()\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a595e39d22e92ac09d24706829b532b00">dir</a>, <a href="#aaaa814308a1fd901771b9b6e4a176d58">m&#95;dir</a> and <a href="#aceba8f7a334d2e60297dcc727959796c">m&#95;t</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### ~OutputGenerator() {#a8efbb8581dc2f9864a3170912e816370}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual OutputGenerator::~OutputGenerator ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00107">107</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

References <a href="#a595e39d22e92ac09d24706829b532b00">dir</a>, <a href="#aaacf2b4efc09a2c06b9dd8cc2af69046">endPlainFile</a>, <a href="#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>, <a href="#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator</a> and <a href="#a6d2b81663565fee4440ef02fe9b3a197">startPlainFile</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### dir() {#a595e39d22e92ac09d24706829b532b00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString OutputGenerator::dir ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00110">110</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-cpp/#l00052">52</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-cpp">outputgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a595e39d22e92ac09d24706829b532b00">52</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aaaa814308a1fd901771b9b6e4a176d58">m_dir</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aaaa814308a1fd901771b9b6e4a176d58">m&#95;dir</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aab1ce69f9718b3c1e05f6c1b697664e4">DocbookGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#add957a1f68cc9b99a4c57caa58b33a9b">HtmlGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#abf21f797d89eb90ceb085c27649df03c">LatexGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adeb275db39d63df2f74c728adaa70849">RTFGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2906dcb02cfd455c0d910c9f9501bfbe">DocbookGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6e132b23d93e17c4e30b815977a5c865">HtmlGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab2b909084907d1b1e629d8af009fe997">LatexGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a0322020ce9d74181bb997b886239ce19">RTFGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa80d2614901e7d7624514fa077cee77c">DocbookGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a603fd2d86e322ea4018747febe523edf">HtmlGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1551a0ac802e77a366331dfc4fd90cc4">LatexGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a1cd78a44f9072b2d24765b07fbd4f01f">RTFGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a4b2e6be7cbbe074a8d2be270a537c454">DocbookGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8bf91873a8da583cfbb47b15806c0ae4">HtmlGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#acc54c8a6e535cf10a1dc96211d07c19f">LatexGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a87f599a42c46d9fce84f456797ff231c">RTFGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a640f85f2e2b3f829d6561aaed542d20b">DocbookGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aabf59d930dff9f6aa46e3e5674678a35">HtmlGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#abfd430d5e5caa0536c58bc174a510cf0">LatexGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afa0db463a17513f4e3ae08e03d6e2615">DocbookGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac78029628ccb4f7aef7ca0c4cbce0ae3">HtmlGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3fd1e2fb8150b2b29985a8031854d4b9">LatexGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa1a701e0ab2c31d782a7faae9e0135e1">RTFGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af4363bcfe3875a66c7f2512feb6be13e">DocbookGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a20ebc13fc3ca037f977dc8144847db73">RTFGenerator::init</a>, <a href="#a8716724782730065f43ea240f93917b0">OutputGenerator</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a5935e8ddff8337f8a43689e2713c8067">ManGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ad05e0b9d1baf567428af8a4e6b96b0ca">HtmlGenerator::writeGraphicalHierarchy</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a11d3c67df991a213ef94780d91367a12">HtmlGenerator::~HtmlGenerator</a> and <a href="#a8efbb8581dc2f9864a3170912e816370">~OutputGenerator</a>.
</div>
</div>

### endPlainFile() {#aaacf2b4efc09a2c06b9dd8cc2af69046}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputGenerator::endPlainFile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00114">114</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-cpp/#l00044">44</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-cpp">outputgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaacf2b4efc09a2c06b9dd8cc2af69046">44</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaacf2b4efc09a2c06b9dd8cc2af69046">OutputGenerator::endPlainFile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aceba8f7a334d2e60297dcc727959796c">m_t</a>.flush();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aceba8f7a334d2e60297dcc727959796c">m_t</a>.setStream(</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/namespaces/portable/#af099fa6239b4961887192d8eadfd2a44">Portable::fclose</a>(<a href="#a74e9a6ba3085c8b710a81d709ea44547">m_file</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae3ebfdcdf8c6d12985d69330ca910dcc">m_fileName</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/portable/#af099fa6239b4961887192d8eadfd2a44">Portable::fclose</a>, <a href="#a74e9a6ba3085c8b710a81d709ea44547">m&#95;file</a>, <a href="#ae3ebfdcdf8c6d12985d69330ca910dcc">m&#95;fileName</a> and <a href="#aceba8f7a334d2e60297dcc727959796c">m&#95;t</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2d188192c029b20f6505b7b79b8f288f">DocbookGenerator::endPlainFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#abb4a012326a0991e0f7cf339b21eafa5">HtmlGenerator::endPlainFile</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a517412d3a169f4b12a6e37b8ff5dd546">LatexGenerator::endPlainFile</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a7fb2c58e4e4d9867222e86f9bf16a398">ManGenerator::endPlainFile</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a2bb6d79258ca358371f6fcb291efd2af">RTFGenerator::endPlainFile</a> and <a href="#a8efbb8581dc2f9864a3170912e816370">~OutputGenerator</a>.
</div>
</div>

### fileName() {#ae347a53e8ee0d9c43c0590134c8e965d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString OutputGenerator::fileName ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00111">111</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-cpp/#l00057">57</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-cpp">outputgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae347a53e8ee0d9c43c0590134c8e965d">57</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae3ebfdcdf8c6d12985d69330ca910dcc">m_fileName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ae3ebfdcdf8c6d12985d69330ca910dcc">m&#95;fileName</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aab1ce69f9718b3c1e05f6c1b697664e4">DocbookGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#add957a1f68cc9b99a4c57caa58b33a9b">HtmlGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#abf21f797d89eb90ceb085c27649df03c">LatexGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adeb275db39d63df2f74c728adaa70849">RTFGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2906dcb02cfd455c0d910c9f9501bfbe">DocbookGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6e132b23d93e17c4e30b815977a5c865">HtmlGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab2b909084907d1b1e629d8af009fe997">LatexGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a0322020ce9d74181bb997b886239ce19">RTFGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa80d2614901e7d7624514fa077cee77c">DocbookGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a603fd2d86e322ea4018747febe523edf">HtmlGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1551a0ac802e77a366331dfc4fd90cc4">LatexGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a1cd78a44f9072b2d24765b07fbd4f01f">RTFGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a4b2e6be7cbbe074a8d2be270a537c454">DocbookGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8bf91873a8da583cfbb47b15806c0ae4">HtmlGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#acc54c8a6e535cf10a1dc96211d07c19f">LatexGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a87f599a42c46d9fce84f456797ff231c">RTFGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aefb08482f742251ae543aeb57983b335">DocbookGenerator::endFile</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a640f85f2e2b3f829d6561aaed542d20b">DocbookGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aabf59d930dff9f6aa46e3e5674678a35">HtmlGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#abfd430d5e5caa0536c58bc174a510cf0">LatexGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afa0db463a17513f4e3ae08e03d6e2615">DocbookGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac78029628ccb4f7aef7ca0c4cbce0ae3">HtmlGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3fd1e2fb8150b2b29985a8031854d4b9">LatexGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa1a701e0ab2c31d782a7faae9e0135e1">RTFGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a6f9db23dee65e962246bc08bec382947">LatexGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac82e6d2bb73a007715d4ccf10552848d">RTFGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a5935e8ddff8337f8a43689e2713c8067">ManGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7a82873f4a7eeacb88ef535768b311f4">DocbookGenerator::startFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab59c183ba1429ec58b88fd83ea686d6c">HtmlGenerator::startFile</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ac651d6a3c75036392f690d32541a8711">LatexGenerator::startFile</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5dd1c3981a67997c42655a95b6a7a7a4">RTFGenerator::startFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1099f1315ce5240b9165563e30471124">HtmlGenerator::startTextLink</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ac8c5de108411c791b04d6501347fd614">LatexGenerator::startTitleHead</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa7ae50a52d4e01f107667b89ead7b3a3">RTFGenerator::writeAnchor</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4baf32d6d76de7c48ea865fe47496612">HtmlGenerator::writeDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ad05e0b9d1baf567428af8a4e6b96b0ca">HtmlGenerator::writeGraphicalHierarchy</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a46e18e094779f6af393deafc4b64d454">HtmlGenerator::writeObjectLink</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1fd6971ba73b744d9ceb90478194d61d">HtmlGenerator::writeSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a86eb94b45459e81c896e184152dd7176">HtmlGenerator::writeStyleInfo</a> and <a href="#a8efbb8581dc2f9864a3170912e816370">~OutputGenerator</a>.
</div>
</div>

### startPlainFile() {#a6d2b81663565fee4440ef02fe9b3a197}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputGenerator::startPlainFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00113">113</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-cpp/#l00032">32</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-cpp">outputgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d2b81663565fee4440ef02fe9b3a197">32</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6d2b81663565fee4440ef02fe9b3a197">OutputGenerator::startPlainFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("startPlainFile(%s)\n",qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae3ebfdcdf8c6d12985d69330ca910dcc">m_fileName</a>=<a href="#aaaa814308a1fd901771b9b6e4a176d58">m_dir</a>+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a74e9a6ba3085c8b710a81d709ea44547">m_file</a> = <a href="/web-doxygen/docs/api/namespaces/portable/#a4dbb08c3de409bd1a73be3da6d93ac57">Portable::fopen</a>(<a href="#ae3ebfdcdf8c6d12985d69330ca910dcc">m_fileName</a>.data(),</span><span class="doxyHighlightStringLiteral">"wb"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a74e9a6ba3085c8b710a81d709ea44547">m_file</a>==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,<a href="#ae3ebfdcdf8c6d12985d69330ca910dcc">m_fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aceba8f7a334d2e60297dcc727959796c">m_t</a>.setFile(<a href="#a74e9a6ba3085c8b710a81d709ea44547">m_file</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/portable/#a4dbb08c3de409bd1a73be3da6d93ac57">Portable::fopen</a>, <a href="#aaaa814308a1fd901771b9b6e4a176d58">m&#95;dir</a>, <a href="#a74e9a6ba3085c8b710a81d709ea44547">m&#95;file</a>, <a href="#ae3ebfdcdf8c6d12985d69330ca910dcc">m&#95;fileName</a>, <a href="#aceba8f7a334d2e60297dcc727959796c">m&#95;t</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af357a86f84b841c7a0d1a8e52d644f69">DocbookGenerator::startPlainFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#afcbb993451628a18541fe8323e2dbf13">HtmlGenerator::startPlainFile</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#abe5c6d8d17cd4ea7147c37b761844fa1">LatexGenerator::startPlainFile</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af4a81052d3aebc9be76c60c871ad9333">ManGenerator::startPlainFile</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a710adef7551b3de0b6ffd5af4796dc63">RTFGenerator::startPlainFile</a> and <a href="#a8efbb8581dc2f9864a3170912e816370">~OutputGenerator</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Protected Member Attributes

### m&#95;dir {#aaaa814308a1fd901771b9b6e4a176d58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString OutputGenerator::m_dir</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00117">117</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaaa814308a1fd901771b9b6e4a176d58">117</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aaaa814308a1fd901771b9b6e4a176d58">m_dir</a>;</span></span></div>

</div>


Referenced by <a href="#a595e39d22e92ac09d24706829b532b00">dir</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator::DocbookGenerator</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator::HtmlGenerator</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab2cb30e88fdc934a8f0c664db36e6028">LatexGenerator::LatexGenerator</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ad5d7852c208c4c26f344ff3c512a0f87">ManGenerator::ManGenerator</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#abfda55e880b3527d256491a2f8e908e1">DocbookGenerator::operator=</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a2a179f3313aad4e67a77b536a25a101b">HtmlGenerator::operator=</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aa6325f38ded9fef72a0b76d228a9e748">LatexGenerator::operator=</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a9075fbe7449b641e8166a2f8d3cf908f">ManGenerator::operator=</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed839fe843b75ecedd4661eed5342fed">RTFGenerator::operator=</a>, <a href="#a8716724782730065f43ea240f93917b0">OutputGenerator</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a1d5e3edbb7716cd984a54034039059d5">RTFGenerator::RTFGenerator</a> and <a href="#a6d2b81663565fee4440ef02fe9b3a197">startPlainFile</a>.
</div>
</div>

### m&#95;t {#aceba8f7a334d2e60297dcc727959796c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextStream OutputGenerator::m_t</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel protected">protected</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00116">116</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aceba8f7a334d2e60297dcc727959796c">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> <a href="#aceba8f7a334d2e60297dcc727959796c">m_t</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aaa8fd7d7ca213ca44cfc5f90aae724e2">DocbookGenerator::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab85e90fb1ce212b54481688febedbc09">LatexGenerator::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac3f637ddb83d1b6005eec5aefe8b84f1">RTFGenerator::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ae17a2241e72a6e7c6f2160f4c6ac8a7a">LatexGenerator::addLabel</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9c567713ffb6a4b9a49400d6dfcb0df1">RTFGenerator::addLabel</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a3a64ef0ca4a6a8f00c6b38e80e9d4545">RTFGenerator::beginRTFChapter</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aaaed62b7c9e0ef2c5ba6133eba8203a1">RTFGenerator::beginRTFDocument</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab1939f0d3e5142f9b77cf8ce807e00a7">RTFGenerator::beginRTFSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afae8cb3fd84db1e998a4f03433c1493b">DocbookGenerator::closeSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a59655593be449f9e01ce953a72233de0">DocbookGenerator::DocbookGenerator</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator::DocbookGenerator</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aea69ff69be259d30ee167aa920746fab">DocbookGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a4c9d7e8efc817dc5bc5a851500171308">LatexGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af41254fa358458e4e1a018477f5107da">ManGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9cd67715e9170630446cb37535f93ac1">RTFGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a894bfecdbda01b83760c93a6a6947b9d">HtmlGenerator::docify&#95;</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a58f1b84412f0f5a3b230b0b13136e922">LatexGenerator::endAnonTypeScope</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac40c97419675e944657df84aa2b944e3">DocbookGenerator::endBold</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#abd13d8dc0cfe6f4167da3ea51041eeaa">HtmlGenerator::endBold</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ae2ff3433f54afbb446d8ca62de458092">LatexGenerator::endBold</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#aa12df6c60b2975f5b105d2c43450f986">ManGenerator::endBold</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a34dc1928c8bb0edc7a4bcc8a36983bde">RTFGenerator::endBold</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a580084abe1d1b6d45421e654fb8d75c1">ManGenerator::endBoldEmphasis</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aab1ce69f9718b3c1e05f6c1b697664e4">DocbookGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#add957a1f68cc9b99a4c57caa58b33a9b">HtmlGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#abf21f797d89eb90ceb085c27649df03c">LatexGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adeb275db39d63df2f74c728adaa70849">RTFGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9a425a35b6459f9e9faef4647e374592">HtmlGenerator::endCenter</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#acb31135798d599db9602293ab0118f13">LatexGenerator::endCenter</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#af4a97499cbe83ba6e3f270c4ba366400">RTFGenerator::endCenter</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2906dcb02cfd455c0d910c9f9501bfbe">DocbookGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6e132b23d93e17c4e30b815977a5c865">HtmlGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab2b909084907d1b1e629d8af009fe997">LatexGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a0322020ce9d74181bb997b886239ce19">RTFGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a56a8e5ad875fcb9b51ce32c5a6fb3fa0">DocbookGenerator::endCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a940ab965d6b42f7a8a8e3f26f926ff42">HtmlGenerator::endCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a163f7f201fccea630ce38ce6158b4784">LatexGenerator::endCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ab02da305950e67b509be9a551711f8d4">ManGenerator::endCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a3050456e14994094727584f66bd253ac">RTFGenerator::endCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6eba93d3b17a8449d5be024af4eb22d4">HtmlGenerator::endConstraintDocs</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a31670fcbb1641b76e26029d9cfda15eb">ManGenerator::endConstraintDocs</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae03eee47f94ec96943747c15069e3c5b">RTFGenerator::endConstraintDocs</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afef965c128d8f6cca32eea3c92c7d1e9">DocbookGenerator::endConstraintList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4a75abb12be07ae3d3ae71ad65fd97f6">HtmlGenerator::endConstraintList</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a6083bcbe3134f32e23f2c6f3b5d18684">LatexGenerator::endConstraintList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a06931a0616d950c5388448188105c4c1">RTFGenerator::endConstraintList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab2448ccd6f13a29e9517e5a0cdb8db73">HtmlGenerator::endConstraintParam</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#aee2419a901ca3a75d64ae56cf387e139">ManGenerator::endConstraintParam</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae7bfacd8071ffd9098ea45614589512a">RTFGenerator::endConstraintParam</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2ff006f1e7375b5d3c6e5a17a3990d68">DocbookGenerator::endConstraintType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae04149859c738f4615b722c17a3c643f">HtmlGenerator::endConstraintType</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a567d6d81c808f553e9464c93bf7b4164">LatexGenerator::endConstraintType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a095b00a37d39558c622e5a6845212b1e">RTFGenerator::endConstraintType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a7c1a1a311c32a34c735413521d117a3e">HtmlGenerator::endContents</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a80e3f7fb6b7c623adb98082a237f28bb">HtmlGenerator::endDescForItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a41d0580039dd59b0489caa356b4ccad5">RTFGenerator::endDescForItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aef5e37d1d6cda8c759cebcd418d91c5d">DocbookGenerator::endDescTable</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a15ca46b12db83276b90fc5e706c24682">HtmlGenerator::endDescTable</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a18b4ecffe40d504106eb05be6a2419d1">LatexGenerator::endDescTable</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a184f64bfd9c98146ba14cb7f990b66fd">RTFGenerator::endDescTable</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a981135dd520efbaa65fabfa865f0ac97">DocbookGenerator::endDescTableData</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a97fcd1422de24ca62489159681167573">HtmlGenerator::endDescTableData</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a65d4af693b189f088805f68fcae4a66c">LatexGenerator::endDescTableData</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a17f06e3f5f32ffba2bd20391454b832f">RTFGenerator::endDescTableData</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0ed12b681f9ef106d1b9a245c720b2d9">HtmlGenerator::endDescTableInit</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#af4494ff8c7b1bfad186fa98542bb6f41">RTFGenerator::endDescTableInit</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a11a9495ef08b1736d472a7245af207b2">DocbookGenerator::endDescTableRow</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a55ba92a674ec09dfd13ff7f6811d78e6">HtmlGenerator::endDescTableRow</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac18fa9a0f9c3de7c8969e1fb1d669c13">HtmlGenerator::endDescTableTitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa38cd77d33e0757270082a234e53c22d">RTFGenerator::endDescTableTitle</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa80d2614901e7d7624514fa077cee77c">DocbookGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a603fd2d86e322ea4018747febe523edf">HtmlGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1551a0ac802e77a366331dfc4fd90cc4">LatexGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a1cd78a44f9072b2d24765b07fbd4f01f">RTFGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a4b2e6be7cbbe074a8d2be270a537c454">DocbookGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8bf91873a8da583cfbb47b15806c0ae4">HtmlGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#acc54c8a6e535cf10a1dc96211d07c19f">LatexGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a87f599a42c46d9fce84f456797ff231c">RTFGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a69e6795499d9f7fb8867f5496c590e26">RTFGenerator::endDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a47ad044610596fe6a022162ca73bd2f3">HtmlGenerator::endEmphasis</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#adbbc234a704564acc5db7e940c63d85b">LatexGenerator::endEmphasis</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#afc4656a772b508e915c40cd1a2bff488">ManGenerator::endEmphasis</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae61684b3eaa81c8fd26dce3c514fdbab">RTFGenerator::endEmphasis</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afd9d65e673f95f980a82bd0bd5518903">DocbookGenerator::endExamples</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a73a0d7bb0cbbb2dd55182ea054b50176">HtmlGenerator::endExamples</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a47a252346ed72cd1706293e2eaa3c4c4">LatexGenerator::endExamples</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afda973c4c7b91577d02465015737763d">RTFGenerator::endExamples</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aefb08482f742251ae543aeb57983b335">DocbookGenerator::endFile</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af8c1acdb6f13aa0da8aaa75ca7f6e562">ManGenerator::endFile</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8f58df9f7518582ab2fc88326d539f1b">RTFGenerator::endFile</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a640f85f2e2b3f829d6561aaed542d20b">DocbookGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aabf59d930dff9f6aa46e3e5674678a35">HtmlGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#abfd430d5e5caa0536c58bc174a510cf0">LatexGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ad91c453f57c7ab68aafb726bceed5807">DocbookGenerator::endGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a44799df53d0705c6a8f1611bf0c686f2">HtmlGenerator::endGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1ea96523b003e1da7efde252e0a20ddf">LatexGenerator::endGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a2a48c9be94459c565ab007f5e342d6f9">ManGenerator::endGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ad4d65d3f43a0ca0ff1e6cc7564a0164c">RTFGenerator::endGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a835dc606cb69304a10a5af081585ff78">HtmlGenerator::endHeaderSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afa0db463a17513f4e3ae08e03d6e2615">DocbookGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac78029628ccb4f7aef7ca0c4cbce0ae3">HtmlGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3fd1e2fb8150b2b29985a8031854d4b9">LatexGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa1a701e0ab2c31d782a7faae9e0135e1">RTFGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a5068d044d959a849cf7fd9743d07c012">HtmlGenerator::endIndent</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#af23f0fc47817bd5fe8c870f6a7c4b6b8">RTFGenerator::endIndent</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aea7b80127d86e6971ff8933e3e8ae42d">HtmlGenerator::endIndexItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a76b121da3731e5fe9c3c68775e5d4152">LatexGenerator::endIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a884c87751b85f4a6cf6e965fbc0bec9c">RTFGenerator::endIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac7cc1ced007f53858bf3f0e45a4db2b2">RTFGenerator::endIndexKey</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a38b18ddbb0822f71d8c56db9f6798fc4">HtmlGenerator::endIndexList</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aec8ced6a045902d50e77304d6478fee9">LatexGenerator::endIndexList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac49acd6dde35e8774990922cad8b953f">RTFGenerator::endIndexList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af2997268cba31448fe3ec43d3e980c78">HtmlGenerator::endIndexListItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#af5e47f880bf9f49092c9bd4da6229803">RTFGenerator::endIndexListItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9a5dbcad360a1ad2a8f9403ae344d638">DocbookGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a33cad27a2b5dce6e2762d5915e554118">LatexGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab9bb81cca57fc3585e7b2e84513a37e3">LatexGenerator::endIndexValue</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae32c0528c173d54061e225bb9ecac3d4">RTFGenerator::endIndexValue</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a64e4b1850daaf19be1cc41dc34e69979">HtmlGenerator::endInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1cd66418d35ea0bb5b7d81c3fd77d753">LatexGenerator::endInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a89c09852a70de4a3a971b02f157d47e1">ManGenerator::endInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac3e7490832bc015173929fd693aa0f74">RTFGenerator::endInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a67b1d012d99a13ef16fcc4ea599b2a06">DocbookGenerator::endInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#adcdb6177d9281921c6d2aa6893b1b5c9">HtmlGenerator::endInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a03d670765e79b1f8a0ddf37a62366b88">LatexGenerator::endInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a6e669645babaaba4691fc5c5f0147ee0">ManGenerator::endInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac4f20b0496b985dc382d29d6a93227cd">RTFGenerator::endInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a01c30e96c02d55000d0c0282cba79924">DocbookGenerator::endInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aed5d2db9d4bdda1b0ae0c6824bfbe415">HtmlGenerator::endInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a86404001740f049878c4507a3f80ab7b">LatexGenerator::endInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a94b91f6c0f3b507bd9b62a8466a9fc0c">ManGenerator::endInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a456b03ed29381d753fa5ca17494b24e1">RTFGenerator::endInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af26580af0994f29308d81034cce3823d">DocbookGenerator::endInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a7de90155aebd5eacbbca903687f8e5f5">HtmlGenerator::endInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3ae33c3f6367df8e82ced6dea2fdc9ad">LatexGenerator::endInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a5c05d280f312457893ee6d3032f770d2">ManGenerator::endInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a3fe406eec950115eb22d5db49f874028">RTFGenerator::endInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#afc7f3aba96e41a1525db5bd833d48067">HtmlGenerator::endItemList</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3d0cacba9f0ff55abaa6c1c15feb3583">LatexGenerator::endItemList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a4d8ad4d2dbb3a431808692d286ad4331">RTFGenerator::endItemList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6432012a68a21dc44897857bb774f76f">HtmlGenerator::endItemListItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aac0b61c1ae1d31008316991d86290451">RTFGenerator::endItemListItem</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aa11aa8c21a8b7eb4af49fc708e43e909">HtmlGenerator::endLabels</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a74c7072c37b0f6ca58f077b0cdd0242e">DocbookGenerator::endLocalToc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aafb64fea3c5e96e1c48b5caba59681fb">HtmlGenerator::endLocalToc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6ca9bf50e7dc80e39b2e9264b3c916ad">HtmlGenerator::endMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a134b6e6274debff649803cb15ddfcc5a">LatexGenerator::endMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#aafe0b4d16ec12528d14a2ff2582bcdac">ManGenerator::endMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a94002731a870c5add8c360dda5f5105d">RTFGenerator::endMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab5c9f6c8cbc6591f1a9763d5c233a8f9">DocbookGenerator::endMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae84d2a7b716a16fa142c0fdb0f8c338c">HtmlGenerator::endMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a55f5680dbc33ebc6b2a88f93f18eb2e5">LatexGenerator::endMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af962b2372c4467e95bc21550d402dedf">ManGenerator::endMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a78507d411bc9c250de2db0d0fe4cd323">RTFGenerator::endMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9300885ee109900582e9a2c8dc298c21">HtmlGenerator::endMemberDocList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a7ad614730d5b184f8d98b4d3ca6e6dcd">HtmlGenerator::endMemberDocName</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7d042582c83c4bf25dba8857f186e56d">DocbookGenerator::endMemberDocPrefixItem</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac007b8ceaed1b6260def8b681ec1e1da">HtmlGenerator::endMemberDocPrefixItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a33e5359a7bfd62bee316d2445659b866">LatexGenerator::endMemberDocPrefixItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a45cd1dbe07a7c47ec3209b9fe1b92c0d">DocbookGenerator::endMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aedce042225aecc4a3d499d675251bd6b">HtmlGenerator::endMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab798f97d18aba07ac88bb0cc23b9b966">LatexGenerator::endMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af921b3fa4cef3239b99c89a4770a748d">ManGenerator::endMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5936c81e07c1d5c6532d42a7ea881296">RTFGenerator::endMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a22265d3dc6b9ae14e0f5db49a0b4f22a">DocbookGenerator::endMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ad01f112ed2fe96a30594cf6aa25eb410">LatexGenerator::endMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a2f0faf7abdfb53dbb1416b1363a172b5">ManGenerator::endMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a52336db808f8c14a307dfe212cb2dccf">RTFGenerator::endMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8a842c61286aea39f627c46ae95210a9">HtmlGenerator::endMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aaf509c279b0b2d61b5cdded55fb1e04a">LatexGenerator::endMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ac330c5f73971dd88eed8e21d98c67ea7">ManGenerator::endMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5520b73ff0e7fd88b3b786a81ff05dbe">RTFGenerator::endMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2f941a481c8539d5ea65daf45d7d694b">DocbookGenerator::endMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a18e033353bdec24873c922894b8a36d4">HtmlGenerator::endMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a4b9a76f03f130ca0728f276d0801538d">LatexGenerator::endMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a4dda2a972bec6b6111b215e94741d8ba">ManGenerator::endMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a01d9e19175b7f2f875be520f1ea105b3">RTFGenerator::endMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a6d97af565fba4f9b4b8df0ee218a7b19">DocbookGenerator::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8d2b7702acdf9b41c6b78cee0177820b">HtmlGenerator::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a73fc0394d91ab6baec0a5bdfa1cdb90c">LatexGenerator::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a639d4d7694e38d646c7b4042f314ca92">ManGenerator::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a29bb57d53d4ef49984943752371d80a9">DocbookGenerator::endMemberItem</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae6ff44b008a49f08afd2347655b3831a">HtmlGenerator::endMemberItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a011b962f233d173e53c61c0380de8b22">LatexGenerator::endMemberItem</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a10c5866fbce79c1a5f3ffbd85eef50bc">ManGenerator::endMemberItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a2aa043554c3f70e4525bc68978ce1fae">RTFGenerator::endMemberItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ae3b1fb5838ed0231423eb95a41173078">DocbookGenerator::endMemberList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3839bea77bec5697144e8fc0d6ebea15">HtmlGenerator::endMemberList</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a98f2ab84c027b90c77e87dd7ed340061">LatexGenerator::endMemberList</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a40a91a3c2f6169232dab1a4ba2133fa2">ManGenerator::endMemberList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a08d35b8ea8ee7a13d1f0b6cbb57d8b0c">RTFGenerator::endMemberList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9261c777bbdaa1882cbd9186c6b08fb6">HtmlGenerator::endMemberSections</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae0f7f3498ff3870052db84b11e20eec4">HtmlGenerator::endMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a6f55850d073b6a3f48452ae91e3ab319">RTFGenerator::endMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa45cce2f709a04a6a5c741b5d2c43f2d">DocbookGenerator::endMemberTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#abb252c9c1a9af617ee975f211f3da598">HtmlGenerator::endMemberTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a2610b1ff4c02600d2907b8c635efdcd4">LatexGenerator::endMemberTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a53a7c461a41d487efe3c90a5ed69caf4">HtmlGenerator::endPageDoc</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a0b59f6064cd7c974823fef0a48c49f37">LatexGenerator::endPageRef</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab12302548e6e1d509ac835b18eab004f">RTFGenerator::endPageRef</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9d5757a3649f96aaaeef61ade2f1b067">DocbookGenerator::endParagraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9b830c30201e8b2ba3a2103acceff7cd">HtmlGenerator::endParagraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#adc12ab66e68f4ef2b1d015a8562a8ec5">LatexGenerator::endParagraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac504083f94cbb2fb24d005200efdd7ee">RTFGenerator::endParagraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a852205da1a99f864d0a1c96143c3b671">DocbookGenerator::endParameterDefVal</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a64513a369c8c8c75dcac36ba1e9341f1">HtmlGenerator::endParameterDefVal</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ae91b64667df54c993df7fef86f2a57c9">DocbookGenerator::endParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0ad8dcc25a41bc905e649e12b0302a3d">HtmlGenerator::endParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a6167d354f20b2003fcbec9d07bed5ffe">LatexGenerator::endParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a44b0bb6001cd84251a58545b7b6e78c2">ManGenerator::endParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab9ba0ac8d9a32480343454dd8152a0c9">RTFGenerator::endParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4a76953ad9eafdccdad1bc536fd9a097">HtmlGenerator::endParameterList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a535f67c3665549f6f93202fd19ec46da">HtmlGenerator::endParameterName</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab88f218de2ffb576f9c5adfa5be36800">LatexGenerator::endParameterName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3462109af2644ffeb87b40975d7fb7bd">HtmlGenerator::endParameterType</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a277956650154871f6abd994abd1ed6cc">LatexGenerator::endParameterType</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#adb906642308c8e41c8f89298d5e8d4df">ManGenerator::endParameterType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae1d2406e88f94dc7d09bb2f339a2ae14">RTFGenerator::endParameterType</a>, <a href="#aaacf2b4efc09a2c06b9dd8cc2af69046">endPlainFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#abc4d79122d4f9001e93365e5274dc5cc">HtmlGenerator::endProjectNumber</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a845289f973bb5776db928e02da765a9b">RTFGenerator::endProjectNumber</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a5d6c0960d638ac86281ecefc1213d8d1">HtmlGenerator::endQuickIndices</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac3c2a2d5f7ee268ca127a30fcaa78fe0">DocbookGenerator::endSection</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aec484816eb09040f49038c4b0a999f23">HtmlGenerator::endSection</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a0db202762b8497c824aa84fb3bf4e9a7">LatexGenerator::endSection</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a2c3eae0a840500bf1a1713cb0c56efd7">ManGenerator::endSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9fd2d69fc49bd907eb78fdd08c8f7f2a">RTFGenerator::endSection</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a60dde525b35f9f620a51070aab5e87f4">HtmlGenerator::endSmall</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a370da80cac13a1cfcce19228d737bb9b">LatexGenerator::endSmall</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a55cea0a5c03e305c104e3cf64c948438">RTFGenerator::endSmall</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a6684626f228c4b3386f33b9d0e1cb000">DocbookGenerator::endTextBlock</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ad907561a88520aac4253dd94cccfb73f">HtmlGenerator::endTextBlock</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a64bae8b15a87dc0384440f8143952b7d">RTFGenerator::endTextBlock</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8eb9a151291ddcd9b1e6eee2b228b754">HtmlGenerator::endTextLink</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aa71e2c5cbef2b584645dabfd715160d0">LatexGenerator::endTextLink</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac5a463eb334d30e8d9ec20f0c0da3a7f">RTFGenerator::endTextLink</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae1337adbb5ad6cea03fcee0d5a7cdfce">HtmlGenerator::endTitle</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a39f79e928a962730a332e6d9dd9b251e">LatexGenerator::endTitle</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a5f10174e0eec5ab53365aad27ad48f22">ManGenerator::endTitle</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aca2bba69055abb8a7a7ea9ce8ce7f11f">DocbookGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aebe66b78ec5e7be56c1d8e4d5c6f2b2e">HtmlGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a6f9db23dee65e962246bc08bec382947">LatexGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a0c856f41b9b3199b3f034a02d7b8309e">ManGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac82e6d2bb73a007715d4ccf10552848d">RTFGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a42a2541faf3a23582c34b87fd29d4f57">DocbookGenerator::endTocEntry</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae5a12bcaed78c969eac8b73cb19d798f">HtmlGenerator::endTocEntry</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2f14bcd9d6629e6ec18be7c82343d852">DocbookGenerator::endTypewriter</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af6ea951201d8b37278044a38c4be9949">HtmlGenerator::endTypewriter</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a6601300639a4c7ecbea41065d721ef96">LatexGenerator::endTypewriter</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ac9bf05f716351613ceac2c0aae060d6e">ManGenerator::endTypewriter</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adf2589cc8ffcd2e42e41bea38afe8a18">RTFGenerator::endTypewriter</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a10ee707ef187621006c30d021aaca34d">DocbookGenerator::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a726c53bd6e118a6ab62e6022c7dd80e6">HtmlGenerator::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#abf013b4910ce277b5817939000707c4d">LatexGenerator::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a55a01085b53c2fdb7176edfa10ebcc7b">RTFGenerator::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0dc05bee31f886b2b5d5318d0c0213a4">HtmlGenerator::HtmlGenerator</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ad04eea6ce6f560d620aa10365466ba44">HtmlGenerator::HtmlGenerator</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9c6116e3f64dcba6a1b4152afdf91fa1">HtmlGenerator::insertMemberAlign</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a2260389b86a386811fc344bb6ec9273d">HtmlGenerator::insertMemberAlignLeft</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a4354834197f45954df7a81d84f70c34d">RTFGenerator::lastIndexPage</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ae145cddfcb7ce9a667be80989bc6f865">LatexGenerator::LatexGenerator</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab2cb30e88fdc934a8f0c664db36e6028">LatexGenerator::LatexGenerator</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a1239152bed92bc91f6a1ddba37671a29">DocbookGenerator::lineBreak</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1afec505ae6d03e654d11f3b6010a36d">HtmlGenerator::lineBreak</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a848b04dcfd026d5fdb0d19f7fff12264">LatexGenerator::lineBreak</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a572b56f603fca632cd9523ef06aed600">ManGenerator::lineBreak</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afc07a6f4ee440625b9fff2890651b092">RTFGenerator::lineBreak</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ad234c57631aa6f20632d21fbcc300a4c">ManGenerator::ManGenerator</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ad5d7852c208c4c26f344ff3c512a0f87">ManGenerator::ManGenerator</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a0242c97cf62889e69e74196b9567e7d0">ManGenerator::newParagraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a19bbf6e08804ee457c7aa9e07b833ba0">RTFGenerator::newParagraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9872f2ebb33a85b7fff7268fee91a977">DocbookGenerator::openSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#abfda55e880b3527d256491a2f8e908e1">DocbookGenerator::operator=</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a2a179f3313aad4e67a77b536a25a101b">HtmlGenerator::operator=</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aa6325f38ded9fef72a0b76d228a9e748">LatexGenerator::operator=</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a9075fbe7449b641e8166a2f8d3cf908f">ManGenerator::operator=</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed839fe843b75ecedd4661eed5342fed">RTFGenerator::operator=</a>, <a href="#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator</a>, <a href="#a8716724782730065f43ea240f93917b0">OutputGenerator</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ad19e0af9634ae061da9492887d9770bd">RTFGenerator::RTFGenerator</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a1d5e3edbb7716cd984a54034039059d5">RTFGenerator::RTFGenerator</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8a5645c1c20ae4026ceb059b942e2635">RTFGenerator::rtfwriteRuler&#95;doubleline</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9bc01f00c980b0cb98c25c0af7f7cea1">RTFGenerator::rtfwriteRuler&#95;emboss</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a32c6af73c41ff6bb6233031279e6ed5d">RTFGenerator::rtfwriteRuler&#95;thick</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#abde344bf39163a6d4d42e4185c545edb">RTFGenerator::rtfwriteRuler&#95;thin</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a509ef7f50fd4872670afc4e24e3a9194">LatexGenerator::startAnonTypeScope</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac90cbd84bc41a572f9f99ca23587847f">DocbookGenerator::startBold</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a41ad780056d93e93a6d630b5f0f025df">HtmlGenerator::startBold</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a8288765dce7d223074c58aa51ca620ae">LatexGenerator::startBold</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a0e4f8662709e4ca7e43e86d1bf4073fd">ManGenerator::startBold</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a6a8ef5460211e55b41e51a9efa4e46e4">RTFGenerator::startBold</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a401f889dc6da64e77da338c6c59d3a67">ManGenerator::startBoldEmphasis</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a34d21b07f7218dcc1161ed797dc8a74a">HtmlGenerator::startCallGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a05a8c27946c7617a908964ccc7887a30">RTFGenerator::startCallGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3bd1c0fe5fa8cc53924bbd8639674840">HtmlGenerator::startCenter</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a26a69daac94a3073583fa0726dd2f5a9">LatexGenerator::startCenter</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a6cc7fe1f4ccffb002edf42f6fed2a8e1">RTFGenerator::startCenter</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9f0bbee1b9f39353827fe1cb34aa6c71">DocbookGenerator::startClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a005f1a46f9808e8a719ba756407259ec">HtmlGenerator::startClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac00a39db660145867a1bc5b82ad1abb8">RTFGenerator::startClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9b3a91c273834c43c7b48e2f0e8712d6">DocbookGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a42347ea9872571c56ab5127514370b8e">HtmlGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3742679498bf79f9bbb89db6caeeb582">LatexGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ae55e63b38a344ce48c2d9157b92d86a2">ManGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aad5bd8b4ea091547b08a00ba70f0aa07">RTFGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab79bdcce95772f1eb1c314a2da602097">HtmlGenerator::startConstraintDocs</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a7db2fcbd4306f608b3218666cffc4752">RTFGenerator::startConstraintDocs</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a57ecb947b9d729a32204364b0be5f712">DocbookGenerator::startConstraintList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6e492ea8c1e1d299d8ab6af19fd52c9a">HtmlGenerator::startConstraintList</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a6900c72da20bc3eddd51c462bb475b08">LatexGenerator::startConstraintList</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a9b07469696e5391928602edc03e16664">ManGenerator::startConstraintList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a29a84d512d59f79ef193e7b0f5010a9d">RTFGenerator::startConstraintList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a51f8405b195722cee84834e0b17f4c6e">DocbookGenerator::startConstraintParam</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4239a94a42b77210e64e042cfee7f726">HtmlGenerator::startConstraintParam</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a840d7d092b35728f878779decb7e4352">LatexGenerator::startConstraintParam</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#af9760387169c66c34e3d3acbb29c03e5">RTFGenerator::startConstraintParam</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a418a7b6baf025267bf10fe0b4a38c367">DocbookGenerator::startConstraintType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab07067c23edb49e8b251e963a480e5c5">HtmlGenerator::startConstraintType</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3670507101d28a7deaa158ae85e70937">LatexGenerator::startConstraintType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac6f532b4c8ab36466d7acdb54d26e55a">RTFGenerator::startConstraintType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3d4a211b9f17df0484bcc2658d5abdaf">HtmlGenerator::startContents</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a062324c12b32fa04ce3ed878590769a7">HtmlGenerator::startDescForItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ad2dcf94bb5b1db2e3fb0cc1df0cac480">LatexGenerator::startDescForItem</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#adf073ca7959a1f7c004bf8c4a79ca151">ManGenerator::startDescForItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a7eb596117c50d366babde83c40af8920">RTFGenerator::startDescForItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afb8929ed5f608c71ef0d67c9bd2713a8">DocbookGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6ea8da6d66244a87fe3141b1165e084c">HtmlGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a7fa96cec20c34d6fecf30cc235fa8d51">LatexGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#abcf93751a8901a09472a39ed04f0c49a">ManGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab4f116084ff07d558fd61db56501e61d">RTFGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a155219c2c52cacd61c75a34b59e16b4e">DocbookGenerator::startDescTableData</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9a58ad6a53095540f4abafb003fc47a1">HtmlGenerator::startDescTableData</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aab5fb51700a9cce35595c4d43163ea0a">LatexGenerator::startDescTableData</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a3e1776ac93e8c66900b56bd8954f6360">ManGenerator::startDescTableData</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a17f0ea04371269d3dccee931c410c3ff">RTFGenerator::startDescTableData</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa64e6f62df30c7d3da3c18c9e311ef96">DocbookGenerator::startDescTableInit</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a578dfeee8598b1dbb0910e7d42e46ee9">HtmlGenerator::startDescTableInit</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab34067f466f119156bd06ca9a83f816b">LatexGenerator::startDescTableInit</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a4e30c4664b1c3cc9a1cb26a2ae98968d">RTFGenerator::startDescTableInit</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab8b9cff7a3e28360c3b659533fccbfda">DocbookGenerator::startDescTableRow</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a401d1ec435f24eb9c4ef50f983e37af7">HtmlGenerator::startDescTableRow</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a56b27cfc8d8b8a8377fc15e19b94efd6">LatexGenerator::startDescTableRow</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a5e2229e11153da2bf67e59928d250783">HtmlGenerator::startDescTableTitle</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3b0908992cecd9fe897f353b740a8bf5">LatexGenerator::startDescTableTitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8454a525177779c9bb183b0ad36fa56b">RTFGenerator::startDescTableTitle</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a41dc42e70634afb2a68fd1c45dd16f91">HtmlGenerator::startDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5e490251eafaf1e6daea2205501855e2">RTFGenerator::startDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4cacd7e83fff3a670a66073686c882a8">HtmlGenerator::startDotGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a60c0df78c97e33cfe069d4bc8bcdfbb7">LatexGenerator::startDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5fd513f89fced258355f7b28f13ec886">RTFGenerator::startDotGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab575d0e0e347d711d242bdc7fd8c7648">DocbookGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a41c7cd661ef071ac37a0fb4efcf31574">HtmlGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a53fd55ec2cf65b5c1843b3e1925f2cad">LatexGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae8d815b1579cfc5304f25b4b3c4bca24">RTFGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a160471f9e3f531fa16ba15bcc467392f">HtmlGenerator::startEmphasis</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#afcbb9579dfb93ef54a1cecf98ea37844">LatexGenerator::startEmphasis</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a1176919950e3fe3324720d45ce10f3f2">ManGenerator::startEmphasis</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a72c313dd5f0ceac813b5c9d5c6ceea90">RTFGenerator::startEmphasis</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aaac726241831c07dc4733f0e63dab3e1">DocbookGenerator::startExamples</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ad122021b54713f1bfb7058d4723af613">HtmlGenerator::startExamples</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a9f79f90d396380841215ba7500f685d3">LatexGenerator::startExamples</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a6b323886b28fc9f4ba5a87981a2b1430">ManGenerator::startExamples</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ad69c3570dc9ede5dd3058791e252c3cc">RTFGenerator::startExamples</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7a82873f4a7eeacb88ef535768b311f4">DocbookGenerator::startFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab59c183ba1429ec58b88fd83ea686d6c">HtmlGenerator::startFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6d892ee256e9a34db8cf761569bb2c9c">HtmlGenerator::startGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac651122c0ac17ea4be13f8a4d71c3efa">DocbookGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac590d2ce8474c9bd7c2abbc9679fb11d">HtmlGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a7f125260c31c05f6171796b108bf3835">LatexGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a49116184047a4d02f25e75788bc539c8">ManGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afc0d8b219f558b257eed6bb523c79fab">RTFGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a5d710dda637c39d769e433ea953bb1b3">HtmlGenerator::startHeaderSection</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a20449975cf6595d7c2cb353f1c26534f">HtmlGenerator::startInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac780414967a7bdbad20d2323d8b7098f">RTFGenerator::startInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a848866b2ca1f5ded259c90a391a7abc4">HtmlGenerator::startIndent</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a434d17937e0e38eb2a631866282cece0">RTFGenerator::startIndent</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a80da85d198868bc3351b1a6a90f32a75">HtmlGenerator::startIndexItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ac5c56d415b19f1c6eb2531cbd238d920">LatexGenerator::startIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9a13eaff7928b82d69f9547aa004d107">RTFGenerator::startIndexItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a80ba16cb517d4473455dacc62b3f2338">LatexGenerator::startIndexKey</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a28728cc8dec08d2a29432ce9b1ddd443">RTFGenerator::startIndexKey</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a642f7c83fd60f3acc6820127e0d0fa9d">HtmlGenerator::startIndexList</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a788bd3bed18bef8f40a4af47ea777a69">LatexGenerator::startIndexList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a969f88aefb693d90e5ced9f91a20b4bc">RTFGenerator::startIndexList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#abb7e7bf073a75a8377e6031d8b798063">HtmlGenerator::startIndexListItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a2fef63d61742f328f7b3a036d367c53f">RTFGenerator::startIndexListItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a19720fb8fa237272681c6328aed372c1">DocbookGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a0de19d805d84ae14aff81334a010c9a1">LatexGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aef5dc3614907f4791da19ad2a1132888">LatexGenerator::startIndexValue</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#abebfc200cb6a3b894069dd00fee75649">RTFGenerator::startIndexValue</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aed122d098bf970698797293cabd09b21">HtmlGenerator::startInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aca2825b298ae76954b78b95987572e98">LatexGenerator::startInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ae7953202c5fa929c78ccf7b2c609cea0">ManGenerator::startInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aedc9cfff56c51ffc2bae28353a319b2e">RTFGenerator::startInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#adaf7ed17f053cb14c26da75c9d7552d4">DocbookGenerator::startInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a719fede306ded713d46b9551eec66cf7">HtmlGenerator::startInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac3f1c345322088ffb63e9075c292ec10">RTFGenerator::startInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af610006b0e0386c4f5762724f30c429c">DocbookGenerator::startInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0d47d7645dc5b280ff77706469a7dd87">HtmlGenerator::startInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af33cf56a2dc1b552aa35c8d74af4bebe">ManGenerator::startInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a131090d6366f73af154c7e59c40bff03">RTFGenerator::startInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac81970c0218bab9e70c805e3fe2d1826">DocbookGenerator::startInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a12aa643326c720f1a8f80610c1bc82fc">HtmlGenerator::startInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab8777ce4032e78dc5a34d5569c09dcc1">RTFGenerator::startInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#afc6ed316d237d1da4b7c3b8d4f822d68">HtmlGenerator::startItemList</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab8e327088a47a8025f8b377cc4626d9e">LatexGenerator::startItemList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa3e5b3dfc4338ba018f1f728d47735f0">RTFGenerator::startItemList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a2e0cac82069348e3bea2d7912feb3d87">HtmlGenerator::startItemListItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ad960879d4212b3f314937577e1c62d01">LatexGenerator::startItemListItem</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a8be5825cc340050d3cfcf29a533a9a4d">ManGenerator::startItemListItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a6847cacb71fc0487655971490b6eb778">RTFGenerator::startItemListItem</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a34bd3e5c72c259091f2546327ac84868">HtmlGenerator::startLabels</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a6dcac8347a5da183d613616915e03800">LatexGenerator::startLabels</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a07b3b950a4edb2d5d1d57125babf3e57">DocbookGenerator::startLocalToc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a5af845a03a3c0c16a3855d88034dfa70">HtmlGenerator::startLocalToc</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a4826c490f9cd4e2caf25fcddfd01150e">LatexGenerator::startLocalToc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a477b9bf180d9c7a57edcd11c408cdb5b">HtmlGenerator::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ad4f48a09b4cb70c380a217f465459714">LatexGenerator::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af88d2023def435e1b31144653a073e84">ManGenerator::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afccb8a5712c326ee5cee2a0caea2bbb1">RTFGenerator::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a8ae15cadac821acb3d6ecfb6c541d6b9">DocbookGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3e27be79946300ecc5d82289192fb691">HtmlGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1f3960465ed8ddd25b9ee0c1bec95622">LatexGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#abab747cba6e0e0fa51ef95655015b9b0">ManGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0db9ec198444ce05559d81134b3696">RTFGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a53aef5bc2dc01700784de5269730cb46">HtmlGenerator::startMemberDocList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a97e2055991080f05a37be7769cf3509c">DocbookGenerator::startMemberDocName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a30b47346a71e1216fb4083c64675bf4e">HtmlGenerator::startMemberDocName</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa59a7da2611e101aa060c3455084255e">DocbookGenerator::startMemberDocPrefixItem</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae2f67237c29b8499dae33d2462cef68a">HtmlGenerator::startMemberDocPrefixItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a49908c3a630786d98fb499887b18d8f3">DocbookGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a7f5dae7d567cd940f9dab8408272e8cd">HtmlGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#abbb3bbd3a74a8161ec48cad9077ba49e">LatexGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a6659f5e934d6346e49dcc2d4cfd28770">ManGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aacbda0698357ec14331ff4ff82f3a2ab">RTFGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ae95e787221dc2879934bb76f7f3951e6">ManGenerator::startMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#abbafc50a4d1a1c021aa659883d40ef45">RTFGenerator::startMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a7e40997271cb08e164b46ad72459d12c">HtmlGenerator::startMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a42b079ef191a47fc0c7f5509a3027c03">LatexGenerator::startMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#acb4071607f13b1efd3de13a9e3e37fdd">RTFGenerator::startMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afdcc8344112747cd65cd80bdb2249933">DocbookGenerator::startMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4ac80db5c4ebf34e1aefa117b542507a">HtmlGenerator::startMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ad3a92e11a8a7e9b2e91f75f28b982c89">LatexGenerator::startMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a1b15bc033e579d19b3f3f9e024b47d7c">ManGenerator::startMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a7ec7eb8980ebddb6c74f2db073e9ab76">RTFGenerator::startMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a10f198594f85e92a681337af184d913d">DocbookGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aea90b1337254e9c10ceaefcff8b9c825">HtmlGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a5e6096c4c5fb47fb771afedea2f64384">LatexGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a61849dd66750168b48e4e4e2db422818">ManGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a82557dc83927e00f34efb901409e04d4">DocbookGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1ec800447787c1eada0c828c6d3bb374">HtmlGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ad68c93528f274100d9909e40690424be">LatexGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a45990f8ba8b86fbb473185345bc34289">ManGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa37f27c3476aa545d3e364b3df70baa8">RTFGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa7454a8fe2d2ceafbc630ea57ce68d0b">DocbookGenerator::startMemberList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a5b26359bf24a0cac681e048110451dda">HtmlGenerator::startMemberList</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aaa54bb7dfa06b2dc31c32bec45d153d8">LatexGenerator::startMemberList</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ae579a6cc157e59fba68fbad15dadf6ac">ManGenerator::startMemberList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#af228acba3f28d35809c7e430b850b821">RTFGenerator::startMemberList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a90e8e67b9d4140660537473a3c98c3d4">HtmlGenerator::startMemberSections</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a287320869b27536a66d09bd7f545507a">HtmlGenerator::startMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5e6c5dd7997b60786df03efbfa3a04f2">RTFGenerator::startMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a870e7da0484cc83d9455903307d03baf">LatexGenerator::startMemberTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aa1e345b8b54d35f3900d6b5a53aad546">HtmlGenerator::startPageDoc</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a280f5faf2cde06b896e5ea7ec857272d">LatexGenerator::startPageRef</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aba5d5c75149b564c4c399776bec65a6e">RTFGenerator::startPageRef</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a22b30d736cc0185909d9b3954a8e3f4e">DocbookGenerator::startParagraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3877e4dc1ec9c0f9e0c0c8ae8c9ec6a9">HtmlGenerator::startParagraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a2bd2c137de54a539928fa5f64a26e879">LatexGenerator::startParagraph</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a4185e0c565c90c08916ee32405623b43">ManGenerator::startParagraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7e3e11ada289af78620b5c6d9733c9">RTFGenerator::startParagraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aedc98fb288995aea0c0b83fc4eca50a2">DocbookGenerator::startParameterDefVal</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a18891cddc72601d23dc617fd045911d8">HtmlGenerator::startParameterDefVal</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac8133798f73d8a88098f57559170a0f0">HtmlGenerator::startParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#acf7c9e0be89dbcc3f5d685576ca2a7a3">LatexGenerator::startParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a05a82a3d67c8acbd8ef73ca8d6d77f1c">DocbookGenerator::startParameterList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af453192b313a5d9bcc31360b15c7feaa">HtmlGenerator::startParameterList</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a558abc082a7d08e5c8363f43a98e29e4">LatexGenerator::startParameterList</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a8444e98efa97c20edcbd24d8029fc6d4">ManGenerator::startParameterList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8575fcb3673750d2349a326e5517b302">RTFGenerator::startParameterList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a83ad153480a66966d9e1121e004b46e4">DocbookGenerator::startParameterName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1cc2066cc3b3716a98dfb95d756fa838">HtmlGenerator::startParameterName</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a2606774b50b4fc888e1a7b62ad4421c3">LatexGenerator::startParameterName</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a566f2060c7d674363ec9f009e47430ac">HtmlGenerator::startParameterType</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a191128ce8eb169f11064b884972f2ec2">LatexGenerator::startParameterType</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a775d9cad2024f07bb3e760e86e6267d4">RTFGenerator::startParameterType</a>, <a href="#a6d2b81663565fee4440ef02fe9b3a197">startPlainFile</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#acce5f3aec5a887f33e47443fbc071d64">HtmlGenerator::startProjectNumber</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a07304e0904923dfea47817fb8438ab59">LatexGenerator::startProjectNumber</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae99a950db4933f16e3df97021e696318">RTFGenerator::startProjectNumber</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa0fe01b830ddb0d899e151aa389087c8">DocbookGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae3bbc191d41c6566b7bafe7a063dd1ac">HtmlGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3d86ad6fe83fea8f3cb45c0e328ab7c8">LatexGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae4e5ba15b96993174f41a6269f233a6a">RTFGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af8fff599224cb05f307e07f60fd06c1d">HtmlGenerator::startSmall</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a7861661aa651d93bd178a1eafe521676">LatexGenerator::startSmall</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a26a707e9f638702c33ff4b6f2bf44dd4">RTFGenerator::startSmall</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aeca4bf8edce633fa3faa7c1e38882363">DocbookGenerator::startTextBlock</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ada8a36f69c16ce253b2fb173f7f36674">HtmlGenerator::startTextBlock</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a012cbbfdb3b792d3d0204004cc7d7772">RTFGenerator::startTextBlock</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1099f1315ce5240b9165563e30471124">HtmlGenerator::startTextLink</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a68725c575a9ec30586e5c67a284712b6">LatexGenerator::startTextLink</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a46e5dfbc859151dfe39ea12ec75a5c13">RTFGenerator::startTextLink</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0fd5a2e848ea16b025b1fb07b4b307fc">HtmlGenerator::startTitle</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a4d1236763a4e5149866e3bae4961b13c">LatexGenerator::startTitle</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ae53c0d4f7905f85069f2e253f97f99a6">ManGenerator::startTitle</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a921181dfbb9226c3eef4536d2f06a242">DocbookGenerator::startTitleHead</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ab529153ad002aa294643ef13adbf351a">HtmlGenerator::startTitleHead</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ac8c5de108411c791b04d6501347fd614">LatexGenerator::startTitleHead</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adf7c83ee8198c326eb4e8efd9f9f1a0a">RTFGenerator::startTitleHead</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a0afd80ec501374a1cdbdf674ec967b79">DocbookGenerator::startTocEntry</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c8a6327e1ce58e1d01bc05a1770e94b">HtmlGenerator::startTocEntry</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a5e66bd3d7d003c6a3205b1febaa19958">DocbookGenerator::startTypewriter</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a455cc2ac7c3f27ea0348c24c2f8a0f62">HtmlGenerator::startTypewriter</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#af6cb5e3aa3229c3e956d7d60963608b1">LatexGenerator::startTypewriter</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#aa63a015c7664c64224acf979cf0a5ef9">ManGenerator::startTypewriter</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a3ee9fc94b9879a89de463bb8f3628458">RTFGenerator::startTypewriter</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac6fc309a5382d6beb8f919fc436709e2">HtmlGenerator::writeAnchor</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a95bca7ae1fd2732e74c0ce749e76916a">LatexGenerator::writeAnchor</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa7ae50a52d4e01f107667b89ead7b3a3">RTFGenerator::writeAnchor</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ada0a91f41d4d1225e3cccd4ee2af6aa3">ManGenerator::writeChar</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2f2d4d689d7e1c05bd243f0b23242064">DocbookGenerator::writeDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4baf32d6d76de7c48ea865fe47496612">HtmlGenerator::writeDoc</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a81554a4af33adef2797ee4d3b663ea4c">LatexGenerator::writeDoc</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a28523fdc2e54ee673f026bd6d46a7224">ManGenerator::writeDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a4f3decc229a0d63c77f2313deee36fb7">RTFGenerator::writeDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a2c585c2b2bb740380ac384da86ae8477">HtmlGenerator::writeFooter</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ad05e0b9d1baf567428af8a4e6b96b0ca">HtmlGenerator::writeGraphicalHierarchy</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af456dab6739ba95632af57ca113f2214">DocbookGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af012e45f04c5da89f11d17770dad1b00">HtmlGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a29a3e4d6eb0dc0f67374c0fc6fbbe1b2">LatexGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ad5999bc38affc6b599217cae57b813d6">ManGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a54e526de8b03280571dc1c0003a14746">RTFGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a3a9126201aae3ba3d2e48a2e7c9b5082">DocbookGenerator::writeLabel</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8ebfa2100dc76714c34b65372f8ce867">HtmlGenerator::writeLabel</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a67d2f0712e57901ddc5b69c8ee7efa00">LatexGenerator::writeLabel</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a7bfd94a9f913641feb0d31531cebd5a1">ManGenerator::writeLabel</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a548d709c03b2c80456d7eb0ee221a8a7">RTFGenerator::writeLabel</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a37a9823b62bdea4132d45eb6e6d94519">LatexGenerator::writeLatexSpacing</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a049734b4a24f5f4c365cc8352a9e9e39">HtmlGenerator::writeLogo</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4546e1dafb6db9b26352c6c0aca8f0dd">HtmlGenerator::writeNavigationPath</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a1a4768269d4a67e9762f388db3ff6842">DocbookGenerator::writeNonBreakableSpace</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a6f723ce20e5ff505a49cac90da7e2d3d">HtmlGenerator::writeNonBreakableSpace</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a401d31ceffd2b4588725351e2dc7767f">LatexGenerator::writeNonBreakableSpace</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#afdaa5989ede189de04e539d440f363e7">ManGenerator::writeNonBreakableSpace</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8fdea0374bb2ef73d9ec48042aacbc70">RTFGenerator::writeNonBreakableSpace</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7c3028f84a8675c8b21ccae5a23e4286">DocbookGenerator::writeObjectLink</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a46e18e094779f6af393deafc4b64d454">HtmlGenerator::writeObjectLink</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab9d6d6bc2c0ce441e4d6dce979e14a0c">LatexGenerator::writeObjectLink</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a87ad1def7058d6ceb4c588b8e2aecfa5">RTFGenerator::writeObjectLink</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a53279dc86a635990c995e61bc3b7104c">DocbookGenerator::writePageLink</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#acd2fbf51acfa991245d009963b01af68">LatexGenerator::writePageLink</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a63e3c07d31875dab02fb233ae5541d23">RTFGenerator::writePageLink</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a715a0d36fadb1999b1e2d0162aa03825">HtmlGenerator::writePageOutline</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a23778fa833bc3d55e61c2cb13d39c090">HtmlGenerator::writeQuickLinks</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a83b81c6e8ba89a61601bef74e92dd594">RTFGenerator::writeRTFReference</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4a3ba3fa4795d6f4130c6430252a099e">HtmlGenerator::writeRuler</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a810e38f4ce210e554ee36c7fb77a9168">LatexGenerator::writeRuler</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a3b34fac2db4cc617332b082a1a087095">HtmlGenerator::writeSearchInfo</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#add51830ca796373d40b216621b6d4b8e">HtmlGenerator::writeSplitBar</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9af437de0126be35d936123ca8eff51a">HtmlGenerator::writeStartAnnoItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#aa9cc3c4f52d431fc6a5d4940c6fc0ea3">LatexGenerator::writeStartAnnoItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a06cb016c789f240eabead87f1a10325a">RTFGenerator::writeStartAnnoItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aac462a27783fedbf5241e95db0a5c66a">DocbookGenerator::writeString</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a77a2e0e20f56eb2256b9b8741ec8b33f">HtmlGenerator::writeString</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3ed4ac5349855a52df7f97875a5ee162">LatexGenerator::writeString</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a664df2b50709ded07b1682e308c9144b">RTFGenerator::writeString</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a86eb94b45459e81c896e184152dd7176">HtmlGenerator::writeStyleInfo</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ae8f3ee4ac698d6d86e7dcaeebfe04fc9">LatexGenerator::writeStyleInfo</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#abf222cd6347aaf899d714dae6ddeb52f">HtmlGenerator::writeSummaryLink</a> and <a href="/web-doxygen/docs/api/classes/mangenerator/#aac22b47b84bdf30579b606f54c36a053">ManGenerator::writeSynopsis</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;file {#a74e9a6ba3085c8b710a81d709ea44547}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FILE* OutputGenerator::m_file = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00120">120</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74e9a6ba3085c8b710a81d709ea44547">120</a></span><span class="doxyLineContent"><span class="doxyHighlight">    FILE *<a href="#a74e9a6ba3085c8b710a81d709ea44547">m_file</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#aaacf2b4efc09a2c06b9dd8cc2af69046">endPlainFile</a> and <a href="#a6d2b81663565fee4440ef02fe9b3a197">startPlainFile</a>.
</div>
</div>

### m&#95;fileName {#ae3ebfdcdf8c6d12985d69330ca910dcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString OutputGenerator::m_fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/outputgen-h/#l00119">119</a> of file <a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3ebfdcdf8c6d12985d69330ca910dcc">119</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae3ebfdcdf8c6d12985d69330ca910dcc">m_fileName</a>;</span></span></div>

</div>


Referenced by <a href="#aaacf2b4efc09a2c06b9dd8cc2af69046">endPlainFile</a>, <a href="#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> and <a href="#a6d2b81663565fee4440ef02fe9b3a197">startPlainFile</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/outputgen-cpp">outputgen.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
