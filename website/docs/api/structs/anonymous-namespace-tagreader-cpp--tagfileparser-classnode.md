---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ClassNode` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous_namespace{tagreader.cpp}::TagFileParser::ClassNode { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadd9729de53674ee8515c631e5e85b64">ClassNode</a> (const std::string &amp;n)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72183189bbcc12d213e16076a19ba02c">name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aa32a2acb4b87396f2a74ba319c6299">tci</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode">ClassNode</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a694169fa539ad5c675f8d301acb54b2c">children</a></td>
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


<p>Definition at line 1005 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### ClassNode() {#aadd9729de53674ee8515c631e5e85b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous_namespace{tagreader.cpp}::TagFileParser::ClassNode::ClassNode (const std::string &amp; n)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#l01007">1007</a> of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aadd9729de53674ee8515c631e5e85b64">1007</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aadd9729de53674ee8515c631e5e85b64">ClassNode</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;n) : <a href="#a72183189bbcc12d213e16076a19ba02c">name</a>(n) {}</span></span></div>

</div>


Reference <a href="#a72183189bbcc12d213e16076a19ba02c">name</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### children {#a694169fa539ad5c675f8d301acb54b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string,std::unique_ptr&lt;ClassNode&gt; &gt; anonymous_namespace{tagreader.cpp}::TagFileParser::ClassNode::children</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#l01010">1010</a> of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a694169fa539ad5c675f8d301acb54b2c">1010</a></span><span class="doxyLineContent"><span class="doxyHighlight">      std::unordered_map&lt;std::string,std::unique_ptr&lt;ClassNode&gt;&gt; <a href="#a694169fa539ad5c675f8d301acb54b2c">children</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#ab5bfa36a1a89d2e6f35ac34fc6b0af3d">anonymous&#95;namespace{tagreader.cpp}::TagFileParser::buildClassTree</a> and <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a9a2a4b0accaef9069229937226e60b10">anonymous&#95;namespace{tagreader.cpp}::TagFileParser::buildLists</a>.
</div>
</div>

### name {#a72183189bbcc12d213e16076a19ba02c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string anonymous_namespace{tagreader.cpp}::TagFileParser::ClassNode::name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#l01008">1008</a> of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72183189bbcc12d213e16076a19ba02c">1008</a></span><span class="doxyLineContent"><span class="doxyHighlight">      std::string <a href="#a72183189bbcc12d213e16076a19ba02c">name</a>;</span></span></div>

</div>


Referenced by <a href="#aadd9729de53674ee8515c631e5e85b64">ClassNode</a>.
</div>
</div>

### tci {#a6aa32a2acb4b87396f2a74ba319c6299}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const TagClassInfo* anonymous_namespace{tagreader.cpp}::TagFileParser::ClassNode::tci = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#l01009">1009</a> of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6aa32a2acb4b87396f2a74ba319c6299">1009</a></span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a> *<a href="#a6aa32a2acb4b87396f2a74ba319c6299">tci</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#ab5bfa36a1a89d2e6f35ac34fc6b0af3d">anonymous&#95;namespace{tagreader.cpp}::TagFileParser::buildClassTree</a> and <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a9a2a4b0accaef9069229937226e60b10">anonymous&#95;namespace{tagreader.cpp}::TagFileParser::buildLists</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
