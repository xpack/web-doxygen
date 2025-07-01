---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/anonymous-namespace-tagreader-cpp-/elementcallbacks
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ElementCallbacks` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous_namespace{tagreader.cpp}::ElementCallbacks { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dd5242d5e2509eb270b58919379fef3">StartCallback</a> = std::function&lt; void(<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser">TagFileParser</a> &amp;, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb943e72c067c8983cb0601130e27bdc">EndCallback</a> = std::function&lt; void(<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser">TagFileParser</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6dd5242d5e2509eb270b58919379fef3">StartCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a669d82e377b203323c02551c88a37567">startCb</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#afb943e72c067c8983cb0601130e27bdc">EndCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a570759ea6e73b4fcff0293db4bc0c259">endCb</a></td>
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


Definition at line 1035 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.

<div class="doxySectionDef">

## Public Member Typedefs

### EndCallback {#afb943e72c067c8983cb0601130e27bdc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous_namespace{tagreader.cpp}::ElementCallbacks::EndCallback =  std::function&lt;void(TagFileParser&amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1038 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afb943e72c067c8983cb0601130e27bdc">1038</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#afb943e72c067c8983cb0601130e27bdc">EndCallback</a>   = std::function&lt;void(<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser">TagFileParser</a>&amp;)&gt;;</span></span></div>

</div>

</div>
</div>

### StartCallback {#a6dd5242d5e2509eb270b58919379fef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous_namespace{tagreader.cpp}::ElementCallbacks::StartCallback =  std::function&lt;void(TagFileParser&amp;,const XMLHandlers::Attributes&amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1037 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6dd5242d5e2509eb270b58919379fef3">1037</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a6dd5242d5e2509eb270b58919379fef3">StartCallback</a> = std::function&lt;void(<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser">TagFileParser</a>&amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp;)&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### endCb {#a570759ea6e73b4fcff0293db4bc0c259}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EndCallback anonymous_namespace{tagreader.cpp}::ElementCallbacks::endCb</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1041 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a570759ea6e73b4fcff0293db4bc0c259">1041</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afb943e72c067c8983cb0601130e27bdc">EndCallback</a>   <a href="#a570759ea6e73b4fcff0293db4bc0c259">endCb</a>;</span></span></div>

</div>

</div>
</div>

### startCb {#a669d82e377b203323c02551c88a37567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StartCallback anonymous_namespace{tagreader.cpp}::ElementCallbacks::startCb</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1040 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a669d82e377b203323c02551c88a37567">1040</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6dd5242d5e2509eb270b58919379fef3">StartCallback</a> <a href="#a669d82e377b203323c02551c88a37567">startCb</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
