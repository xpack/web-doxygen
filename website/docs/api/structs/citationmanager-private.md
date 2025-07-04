---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/citationmanager/private
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `Private` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct CitationManager::Private { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/citeinfoimpl">CiteInfoImpl</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b060e55fdd945e3f802942708c36c4b">entries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; int, std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebb64cb55fe9bfcc582ee70a1378f7d9">formulaCite</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, <a href="/web-doxygen/docs/api/classes/citeposition">CitePosition</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79e7b55996157d6e93eba85988aeda40">citePosition</a></td>
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


<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### citePosition {#a79e7b55996157d6e93eba85988aeda40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt; std::string, CitePosition &gt; CitationManager::Private::citePosition</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a79e7b55996157d6e93eba85988aeda40">83</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::unordered_map&lt; std::string, CitePosition &gt; <a href="#a79e7b55996157d6e93eba85988aeda40">citePosition</a>;</span></span></div>

</div>

</div>
</div>

### entries {#a1b060e55fdd945e3f802942708c36c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt; std::string,std::unique_ptr&lt;CiteInfoImpl&gt; &gt; CitationManager::Private::entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b060e55fdd945e3f802942708c36c4b">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::map&lt; std::string,std::unique_ptr&lt;CiteInfoImpl&gt; &gt; <a href="#a1b060e55fdd945e3f802942708c36c4b">entries</a>;</span></span></div>

</div>

</div>
</div>

### formulaCite {#aebb64cb55fe9bfcc582ee70a1378f7d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt; int,std::string &gt; CitationManager::Private::formulaCite</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebb64cb55fe9bfcc582ee70a1378f7d9">82</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::unordered_map&lt; int,std::string &gt; <a href="#aebb64cb55fe9bfcc582ee70a1378f7d9">formulaCite</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
