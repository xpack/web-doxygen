---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/modulemanager/private
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Private` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct ModuleManager::Private { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/modulelinkedmap">ModuleLinkedMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ebf7a998459df796d4ceca3c5d80920">moduleFileMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, <a href="/web-doxygen/docs/api/classes/modulelist">ModuleList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa419cdcb3db7ad73b42022918b2be51e">moduleNameMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/moduledef-h/#ad2e25aa6a36e0c0605e01d8df04203a6">ImportInfoMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a444ee0ad546327ebac9f691950685619">externalImports</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a19ac7e5562ea564ca2b29069e08e7734">HeaderInfoVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61498d935ae514e32be0b08f3544f646">headers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29f444ce269ffce03a5ee00980a20bb4">mutex</a></td>
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


<p>Definition at line 1206 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>

<div class="doxySectionDef">

## Public Member Attributes

### externalImports {#a444ee0ad546327ebac9f691950685619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ImportInfoMap ModuleManager::Private::externalImports</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1210 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a444ee0ad546327ebac9f691950685619">1210</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/moduledef-h/#ad2e25aa6a36e0c0605e01d8df04203a6">ImportInfoMap</a>       <a href="#a444ee0ad546327ebac9f691950685619">externalImports</a>;</span></span></div>

</div>

</div>
</div>

### headers {#a61498d935ae514e32be0b08f3544f646}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HeaderInfoVector ModuleManager::Private::headers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1211 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a61498d935ae514e32be0b08f3544f646">1211</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/moduledef-cpp/#a19ac7e5562ea564ca2b29069e08e7734">HeaderInfoVector</a>    <a href="#a61498d935ae514e32be0b08f3544f646">headers</a>;</span></span></div>

</div>

</div>
</div>

### moduleFileMap {#a0ebf7a998459df796d4ceca3c5d80920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ModuleLinkedMap ModuleManager::Private::moduleFileMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1208 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ebf7a998459df796d4ceca3c5d80920">1208</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/modulelinkedmap">ModuleLinkedMap</a>     <a href="#a0ebf7a998459df796d4ceca3c5d80920">moduleFileMap</a>; </span><span class="doxyHighlightComment">// file-&gt;module mapping</span></span></div>

</div>

</div>
</div>

### moduleNameMap {#aa419cdcb3db7ad73b42022918b2be51e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string,ModuleList&gt; ModuleManager::Private::moduleNameMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1209 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa419cdcb3db7ad73b42022918b2be51e">1209</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::unordered_map&lt;std::string,ModuleList&gt; <a href="#aa419cdcb3db7ad73b42022918b2be51e">moduleNameMap</a>; </span><span class="doxyHighlightComment">// name-&gt;module mapping</span></span></div>

</div>

</div>
</div>

### mutex {#a29f444ce269ffce03a5ee00980a20bb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex ModuleManager::Private::mutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1212 of file <a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a29f444ce269ffce03a5ee00980a20bb4">1212</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::mutex          <a href="#a29f444ce269ffce03a5ee00980a20bb4">mutex</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p>The documentation for this struct was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/moduledef-cpp">moduledef.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
