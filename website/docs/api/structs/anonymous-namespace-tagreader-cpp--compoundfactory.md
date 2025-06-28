---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/anonymous-namespace-tagreader-cpp-/compoundfactory
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `CompoundFactory` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct anonymous_namespace{tagreader.cpp}::CompoundFactory { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af86c30518622c64bad043247a2b5cdc2">CreateFunc</a> = std::function&lt; <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a>()&gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fd9ab19f73b6027e5982e944b84b894">CompoundFactory</a> (TagFileParser::State s, const CreateFunc &amp;f)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a7a2a20ef2fb10c1c35e093f0c3f41f85">TagFileParser::State</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77aecc8d65afef377e620d7d67df94b2">state</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#af86c30518622c64bad043247a2b5cdc2">CreateFunc</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5cec2e1a4a245a468ff72abc31850ca">make_instance</a></td>
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


<p>Definition at line 1087 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>

<div class="doxySectionDef">

## Public Member Typedefs

### CreateFunc {#af86c30518622c64bad043247a2b5cdc2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using anonymous_namespace{tagreader.cpp}::CompoundFactory::CreateFunc =  std::function&lt;TagCompoundVariant()&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1089 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af86c30518622c64bad043247a2b5cdc2">1089</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#af86c30518622c64bad043247a2b5cdc2">CreateFunc</a> = std::function&lt;<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a>()&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### CompoundFactory() {#a1fd9ab19f73b6027e5982e944b84b894}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">anonymous_namespace{tagreader.cpp}::CompoundFactory::CompoundFactory (<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a7a2a20ef2fb10c1c35e093f0c3f41f85">TagFileParser::State</a> s, const <a href="#af86c30518622c64bad043247a2b5cdc2">CreateFunc</a> &amp; f)</td>
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


<p>Definition at line 1090 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1fd9ab19f73b6027e5982e944b84b894">1090</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1fd9ab19f73b6027e5982e944b84b894">CompoundFactory</a>(<a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a7a2a20ef2fb10c1c35e093f0c3f41f85">TagFileParser::State</a> s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#af86c30518622c64bad043247a2b5cdc2">CreateFunc</a> &amp;f) : <a href="#a77aecc8d65afef377e620d7d67df94b2">state</a>(s), <a href="#ae5cec2e1a4a245a468ff72abc31850ca">make_instance</a>(f) {}</span></span></div>

</div>


References <a href="#ae5cec2e1a4a245a468ff72abc31850ca">make&#95;instance</a> and <a href="#a77aecc8d65afef377e620d7d67df94b2">state</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### make&#95;instance {#ae5cec2e1a4a245a468ff72abc31850ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CreateFunc anonymous_namespace{tagreader.cpp}::CompoundFactory::make_instance</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1092 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5cec2e1a4a245a468ff72abc31850ca">1092</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af86c30518622c64bad043247a2b5cdc2">CreateFunc</a> <a href="#ae5cec2e1a4a245a468ff72abc31850ca">make_instance</a>;</span></span></div>

</div>


Referenced by <a href="#a1fd9ab19f73b6027e5982e944b84b894">CompoundFactory</a>.
</div>
</div>

### state {#a77aecc8d65afef377e620d7d67df94b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TagFileParser::State anonymous_namespace{tagreader.cpp}::CompoundFactory::state</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1091 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a77aecc8d65afef377e620d7d67df94b2">1091</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a7a2a20ef2fb10c1c35e093f0c3f41f85">TagFileParser::State</a> <a href="#a77aecc8d65afef377e620d7d67df94b2">state</a>;</span></span></div>

</div>


Referenced by <a href="#a1fd9ab19f73b6027e5982e944b84b894">CompoundFactory</a>.
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
