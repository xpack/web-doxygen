---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/docvisitor/private
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
struct DocVisitor::Private { ... }
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee46f6a6f4de845aef2260f52fc3092b">id</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/codeparserinterface">CodeParserInterface</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c8b6711cb9e8c445ba748a43b80b24d">parserFactoryMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::stack&lt; bool &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4e3ee6237c07d9b001f3728fbd9962">hidden</a></td>
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


<p>Definition at line 25 of file <a href="/web-doxygen/docs/api/files/src/docvisitor-cpp">docvisitor.cpp</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### hidden {#aae4e3ee6237c07d9b001f3728fbd9962}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::stack&lt;bool&gt; DocVisitor::Private::hidden</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/docvisitor-cpp">docvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aae4e3ee6237c07d9b001f3728fbd9962">29</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::stack&lt;bool&gt; <a href="#aae4e3ee6237c07d9b001f3728fbd9962">hidden</a>;</span></span></div>

</div>

</div>
</div>

### id {#aee46f6a6f4de845aef2260f52fc3092b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocVisitor::Private::id</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/docvisitor-cpp">docvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aee46f6a6f4de845aef2260f52fc3092b">27</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aee46f6a6f4de845aef2260f52fc3092b">id</a>;</span></span></div>

</div>

</div>
</div>

### parserFactoryMap {#a9c8b6711cb9e8c445ba748a43b80b24d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt; std::string, std::unique_ptr&lt;CodeParserInterface&gt; &gt; DocVisitor::Private::parserFactoryMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-doxygen/docs/api/files/src/docvisitor-cpp">docvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c8b6711cb9e8c445ba748a43b80b24d">28</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::unordered_map&lt; std::string, std::unique_ptr&lt;CodeParserInterface&gt; &gt; <a href="#a9c8b6711cb9e8c445ba748a43b80b24d">parserFactoryMap</a>;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docvisitor-cpp">docvisitor.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
