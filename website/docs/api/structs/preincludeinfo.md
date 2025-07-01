---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/preincludeinfo
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `PreIncludeInfo` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct PreIncludeInfo { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ef659db864f11ef7574f65f737a30b4">PreIncludeInfo</a> (const QCString &amp;fn, FileDef *srcFd, FileDef *dstFd, const QCString &amp;iName, bool loc, bool imp)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15f1159eaf981c7035b440feb08c9097">fileName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93cde6f5e2447df45c8991ad86373331">fromFileDef</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19fae3f028e545eaa6e9b79e376188b8">toFileDef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb77d5cf199cdeea923b57db4fbdb9c0">includeName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ccb1f370e869617fe3faafdf943edf5">local</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7abe6b0ce0ef0e7b6e87eba42d487000">imported</a></td>
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


Definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.

<div class="doxySectionDef">

## Public Constructors

### PreIncludeInfo() {#a8ef659db864f11ef7574f65f737a30b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PreIncludeInfo::PreIncludeInfo (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fn, <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * srcFd, <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * dstFd, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; iName, bool loc, bool imp)</td>
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



Definition at line 96 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ef659db864f11ef7574f65f737a30b4">96</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8ef659db864f11ef7574f65f737a30b4">PreIncludeInfo</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fn,<a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *srcFd, <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *dstFd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;iName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> loc, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> imp)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    : <a href="#a15f1159eaf981c7035b440feb08c9097">fileName</a>(fn), <a href="#a93cde6f5e2447df45c8991ad86373331">fromFileDef</a>(srcFd), <a href="#a19fae3f028e545eaa6e9b79e376188b8">toFileDef</a>(dstFd), <a href="#acb77d5cf199cdeea923b57db4fbdb9c0">includeName</a>(iName), <a href="#a4ccb1f370e869617fe3faafdf943edf5">local</a>(loc), <a href="#a7abe6b0ce0ef0e7b6e87eba42d487000">imported</a>(imp)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="#a15f1159eaf981c7035b440feb08c9097">fileName</a>, <a href="#a93cde6f5e2447df45c8991ad86373331">fromFileDef</a>, <a href="#a7abe6b0ce0ef0e7b6e87eba42d487000">imported</a>, <a href="#acb77d5cf199cdeea923b57db4fbdb9c0">includeName</a>, <a href="#a4ccb1f370e869617fe3faafdf943edf5">local</a> and <a href="#a19fae3f028e545eaa6e9b79e376188b8">toFileDef</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### fileName {#a15f1159eaf981c7035b440feb08c9097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PreIncludeInfo::fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 100 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15f1159eaf981c7035b440feb08c9097">100</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a15f1159eaf981c7035b440feb08c9097">fileName</a>;    </span><span class="doxyHighlightComment">// file name in which the include statement was found</span></span></div>

</div>


Referenced by <a href="#a8ef659db864f11ef7574f65f737a30b4">PreIncludeInfo</a>.
</div>
</div>

### fromFileDef {#a93cde6f5e2447df45c8991ad86373331}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileDef* PreIncludeInfo::fromFileDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a93cde6f5e2447df45c8991ad86373331">101</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *<a href="#a93cde6f5e2447df45c8991ad86373331">fromFileDef</a>; </span><span class="doxyHighlightComment">// filedef in which the include statement was found</span></span></div>

</div>


Referenced by <a href="#a8ef659db864f11ef7574f65f737a30b4">PreIncludeInfo</a>.
</div>
</div>

### imported {#a7abe6b0ce0ef0e7b6e87eba42d487000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PreIncludeInfo::imported</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7abe6b0ce0ef0e7b6e87eba42d487000">105</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a7abe6b0ce0ef0e7b6e87eba42d487000">imported</a>;        </span><span class="doxyHighlightComment">// include via "import" keyword (Objective-C)</span></span></div>

</div>


Referenced by <a href="#a8ef659db864f11ef7574f65f737a30b4">PreIncludeInfo</a>.
</div>
</div>

### includeName {#acb77d5cf199cdeea923b57db4fbdb9c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PreIncludeInfo::includeName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb77d5cf199cdeea923b57db4fbdb9c0">103</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#acb77d5cf199cdeea923b57db4fbdb9c0">includeName</a>; </span><span class="doxyHighlightComment">// name used in the #include statement</span></span></div>

</div>


Referenced by <a href="#a8ef659db864f11ef7574f65f737a30b4">PreIncludeInfo</a>.
</div>
</div>

### local {#a4ccb1f370e869617fe3faafdf943edf5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PreIncludeInfo::local</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4ccb1f370e869617fe3faafdf943edf5">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4ccb1f370e869617fe3faafdf943edf5">local</a>;           </span><span class="doxyHighlightComment">// is it a "local" or &lt;global&gt; include</span></span></div>

</div>


Referenced by <a href="#a8ef659db864f11ef7574f65f737a30b4">PreIncludeInfo</a>.
</div>
</div>

### toFileDef {#a19fae3f028e545eaa6e9b79e376188b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FileDef* PreIncludeInfo::toFileDef</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 102 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19fae3f028e545eaa6e9b79e376188b8">102</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *<a href="#a19fae3f028e545eaa6e9b79e376188b8">toFileDef</a>;   </span><span class="doxyHighlightComment">// filedef to which the include is pointing</span></span></div>

</div>


Referenced by <a href="#a8ef659db864f11ef7574f65f737a30b4">PreIncludeInfo</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
