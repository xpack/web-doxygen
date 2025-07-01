---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/dotdirproperty
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DotDirProperty` Struct Reference

Properties are used to format the directories in the graph distinctively. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
struct DotDirProperty { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa37640375733ea38413a589b3f90718">isIncomplete</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
true if not all successors of a cluster are drawn <a href="#afa37640375733ea38413a589b3f90718">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a725a202c71456e1caf086cdd20a9baf9">isOrphaned</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
true if parent is not drawn <a href="#a725a202c71456e1caf086cdd20a9baf9">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13d7c0ae8df6a6a0d7d1298ce5b2fbd5">isTruncated</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
true has successors, none is drawn <a href="#a13d7c0ae8df6a6a0d7d1298ce5b2fbd5">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ed0c0d9a9e5638b80ba4d96b1f7b7b">isOriginal</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
true if is the directory for which the graph is drawn <a href="#ac8ed0c0d9a9e5638b80ba4d96b1f7b7b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae497ee1efde3231d5f26bd05a05480e1">isPeripheral</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
true if no successor of parent of original directory <a href="#ae497ee1efde3231d5f26bd05a05480e1">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

Properties are used to format the directories in the graph distinctively.

Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxySectionDef">

## Public Member Attributes

### isIncomplete {#afa37640375733ea38413a589b3f90718}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotDirProperty::isIncomplete = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

true if not all successors of a cluster are drawn

Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa37640375733ea38413a589b3f90718">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#afa37640375733ea38413a589b3f90718">isIncomplete</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">//!&lt; true if not all successors of a cluster are drawn</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a6aa3fa8ed5c1cb6cfe4a5f821d1c776f">getDirectoryBorderStyle</a>.
</div>
</div>

### isOriginal {#ac8ed0c0d9a9e5638b80ba4d96b1f7b7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotDirProperty::isOriginal = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

true if is the directory for which the graph is drawn

Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8ed0c0d9a9e5638b80ba4d96b1f7b7b">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac8ed0c0d9a9e5638b80ba4d96b1f7b7b">isOriginal</a>   = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">//!&lt; true if is the directory for which the graph is drawn</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a6aa3fa8ed5c1cb6cfe4a5f821d1c776f">getDirectoryBorderStyle</a>.
</div>
</div>

### isOrphaned {#a725a202c71456e1caf086cdd20a9baf9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotDirProperty::isOrphaned = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

true if parent is not drawn

Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a725a202c71456e1caf086cdd20a9baf9">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a725a202c71456e1caf086cdd20a9baf9">isOrphaned</a>   = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">//!&lt; true if parent is not drawn</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#aed9febe225f49a478f1ac4ab8c92786d">getDirectoryBorderColor</a> and <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a6aa3fa8ed5c1cb6cfe4a5f821d1c776f">getDirectoryBorderStyle</a>.
</div>
</div>

### isPeripheral {#ae497ee1efde3231d5f26bd05a05480e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotDirProperty::isPeripheral = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

true if no successor of parent of original directory

Definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae497ee1efde3231d5f26bd05a05480e1">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae497ee1efde3231d5f26bd05a05480e1">isPeripheral</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">//!&lt; true if no successor of parent of original directory</span></span></div>

</div>

</div>
</div>

### isTruncated {#a13d7c0ae8df6a6a0d7d1298ce5b2fbd5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DotDirProperty::isTruncated = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

true has successors, none is drawn

Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a13d7c0ae8df6a6a0d7d1298ce5b2fbd5">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a13d7c0ae8df6a6a0d7d1298ce5b2fbd5">isTruncated</a>  = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">//!&lt; true has successors, none is drawn</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#aed9febe225f49a478f1ac4ab8c92786d">getDirectoryBorderColor</a> and <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a6aa3fa8ed5c1cb6cfe4a5f821d1c776f">getDirectoryBorderStyle</a>.
</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp">dotdirdeps.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
