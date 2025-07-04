---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/anonymous-layout-cpp-/elementcallbacks
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `ElementCallbacks` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous{layout.cpp}::ElementCallbacks { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f35c633427b9030c09d9abf997c4742">StartCallback</a> = std::function&lt; void(<a href="/web-doxygen/docs/api/classes/layoutparser">LayoutParser</a> &amp;, const std::string &amp;, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a290bacf7e342d8041b3cf704a7f8df09">EndCallback</a> = std::function&lt; void(<a href="/web-doxygen/docs/api/classes/layoutparser">LayoutParser</a> &amp;, const std::string &amp;)&gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a2f35c633427b9030c09d9abf997c4742">StartCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b87d1df5eb372f2e2273dfde47037a">startCb</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a290bacf7e342d8041b3cf704a7f8df09">EndCallback</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9235a1109f8836d4dfe7a856a98c21f4">endCb</a> = [](<a href="/web-doxygen/docs/api/classes/layoutparser">LayoutParser</a> &amp;,const std::string &amp;){}</td>
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


<p>Definition at line 723 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### EndCallback {#a290bacf7e342d8041b3cf704a7f8df09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous_namespace{layout.cpp}::ElementCallbacks::EndCallback =  std::function&lt;void(LayoutParser&amp;,const std::string &amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 726 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a290bacf7e342d8041b3cf704a7f8df09">726</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a290bacf7e342d8041b3cf704a7f8df09">EndCallback</a>   = std::function&lt;void(<a href="/web-doxygen/docs/api/classes/layoutparser">LayoutParser</a>&amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;)&gt;;</span></span></div>

</div>

</div>
</div>

### StartCallback {#a2f35c633427b9030c09d9abf997c4742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous_namespace{layout.cpp}::ElementCallbacks::StartCallback =  std::function&lt;void(LayoutParser&amp;,const std::string &amp;,const XMLHandlers::Attributes&amp;)&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 725 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2f35c633427b9030c09d9abf997c4742">725</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a2f35c633427b9030c09d9abf997c4742">StartCallback</a> = std::function&lt;void(<a href="/web-doxygen/docs/api/classes/layoutparser">LayoutParser</a>&amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp;)&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### endCb {#a9235a1109f8836d4dfe7a856a98c21f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EndCallback anonymous_namespace{layout.cpp}::ElementCallbacks::endCb = [](<a href="/web-doxygen/docs/api/classes/layoutparser">LayoutParser</a> &amp;,const std::string &amp;){}</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 729 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9235a1109f8836d4dfe7a856a98c21f4">729</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a290bacf7e342d8041b3cf704a7f8df09">EndCallback</a>   <a href="#a9235a1109f8836d4dfe7a856a98c21f4">endCb</a> = [](<a href="/web-doxygen/docs/api/classes/layoutparser">LayoutParser</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;){};</span></span></div>

</div>

</div>
</div>

### startCb {#a13b87d1df5eb372f2e2273dfde47037a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StartCallback anonymous_namespace{layout.cpp}::ElementCallbacks::startCb</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 728 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a13b87d1df5eb372f2e2273dfde47037a">728</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2f35c633427b9030c09d9abf997c4742">StartCallback</a> <a href="#a13b87d1df5eb372f2e2273dfde47037a">startCb</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
