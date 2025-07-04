---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/reflist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `RefList` Class Reference

<p>List of cross-referenced items. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class RefList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/reflist-h">src/reflist.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36b770703f31caac7df3873136d3d747">RefList</a> (const QCString &amp;listName, const QCString &amp;pageTitle, const QCString &amp;secTitle)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe342e088292fdea46c56134d3b43b14">isEnabled</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/refitem">RefItem</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93af6a9f7e50dd639c820d6694471ea8">add</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/refitem">RefItem</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3187e9ba3a99e7867cc70b6d7b45b7c">find</a> (int itemId)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e731cccf3c01e3b8c04c1955e8e0a5e">listName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0bc0a1bdcf5f3a4018a09bc79b6dbb3">fileName</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ed329a8c21b43e174a88a9152fea631">pageTitle</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68687120cabce4bc5e4f2e7ceb37c95d">sectionTitle</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fb6f991a5826241faab676ba08fb5e3">generatePage</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6aff430cc301cd0a0d82f7d108d7c5bd">m_id</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b8f629582102465bc198cb011537408">m_listName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cb45d0ad20a27cf9e595f10bf6c6971">m_fileName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4394f2fd08f1569127584ce356855b76">m_pageTitle</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a256f77e4a8638c72df0883eb07d3dd3f">m_secTitle</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/refitem">RefItem</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3627ab8d4a351f058aa31a2b70440b2f">m_entries</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; int, <a href="/web-doxygen/docs/api/classes/refitem">RefItem</a> * &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17bc1029e261db1d27fc066485b28a4d">m_lookup</a></td>
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

<p>List of cross-referenced items.</p>


<p>This class represents a list of items that are put at a certain point in the documentation by some special command and are collected in a list. The items cross-reference the documentation and the list.</p>


<p>Examples are the todo list, the test list and the bug list, introduced by the \todo, \test, and \bug commands respectively.</p>


<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### RefList() {#a36b770703f31caac7df3873136d3d747}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefList::RefList (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; listName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; pageTitle, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; secTitle)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Create a list of items that are cross referenced with documentation blocks</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">listName</td>
<td class="doxyParamItemDescription"><p>String representing the name of the list.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">pageTitle</td>
<td class="doxyParamItemDescription"><p>String representing the title of the list page.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">secTitle</td>
<td class="doxyParamItemDescription"><p>String representing the title of the section.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 87 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>, definition at line 24 of file <a href="/web-doxygen/docs/api/files/src/reflist-cpp">reflist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a36b770703f31caac7df3873136d3d747">24</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a36b770703f31caac7df3873136d3d747">RefList::RefList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a7e731cccf3c01e3b8c04c1955e8e0a5e">listName</a>, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a3ed329a8c21b43e174a88a9152fea631">pageTitle</a>, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;secTitle) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">25</span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="#a1b8f629582102465bc198cb011537408">m_listName</a>(<a href="#a7e731cccf3c01e3b8c04c1955e8e0a5e">listName</a>), <a href="#a8cb45d0ad20a27cf9e595f10bf6c6971">m_fileName</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>(<a href="#a7e731cccf3c01e3b8c04c1955e8e0a5e">listName</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">26</span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="#a4394f2fd08f1569127584ce356855b76">m_pageTitle</a>(<a href="#a3ed329a8c21b43e174a88a9152fea631">pageTitle</a>), <a href="#a256f77e4a8638c72df0883eb07d3dd3f">m_secTitle</a>(secTitle)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">27</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">28</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8e04495ad97c6aab7960cc989e3f8c67">convertNameToFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a7e731cccf3c01e3b8c04c1955e8e0a5e">listName</a>, <a href="#a8cb45d0ad20a27cf9e595f10bf6c6971">m_fileName</a>, <a href="#a1b8f629582102465bc198cb011537408">m_listName</a>, <a href="#a4394f2fd08f1569127584ce356855b76">m_pageTitle</a>, <a href="#a256f77e4a8638c72df0883eb07d3dd3f">m_secTitle</a>, <a href="#a3ed329a8c21b43e174a88a9152fea631">pageTitle</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a93af6a9f7e50dd639c820d6694471ea8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefItem * RefList::add ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Adds a new item to the list.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A unique id for this item.</p></dd>
</dl>


<p>Declaration at line 93 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>, definition at line 30 of file <a href="/web-doxygen/docs/api/files/src/reflist-cpp">reflist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a93af6a9f7e50dd639c820d6694471ea8">30</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/refitem">RefItem</a> *<a href="#a93af6a9f7e50dd639c820d6694471ea8">RefList::add</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6aff430cc301cd0a0d82f7d108d7c5bd">m_id</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">  std::unique_ptr&lt;RefItem&gt; item = std::make_unique&lt;RefItem&gt;(<a href="#a6aff430cc301cd0a0d82f7d108d7c5bd">m_id</a>,</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/refitem">RefItem</a> *result = item.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3627ab8d4a351f058aa31a2b70440b2f">m_entries</a>.push_back(std::move(item));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a17bc1029e261db1d27fc066485b28a4d">m_lookup</a>.emplace(<a href="#a6aff430cc301cd0a0d82f7d108d7c5bd">m_id</a>,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a3627ab8d4a351f058aa31a2b70440b2f">m_entries</a>, <a href="#a6aff430cc301cd0a0d82f7d108d7c5bd">m_id</a> and <a href="#a17bc1029e261db1d27fc066485b28a4d">m_lookup</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad14a1e786887639d5383cbcd8427bba8">addXRefItem</a>.</p>

</div>
</div>

### fileName() {#ae0bc0a1bdcf5f3a4018a09bc79b6dbb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString RefList::fileName ()</td>
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



<p>Definition at line 102 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae0bc0a1bdcf5f3a4018a09bc79b6dbb3">102</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae0bc0a1bdcf5f3a4018a09bc79b6dbb3">fileName</a>()</span><span class="doxyHighlightKeyword"> const      </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8cb45d0ad20a27cf9e595f10bf6c6971">m_fileName</a>;  }</span></span></div>

</div>


<p>Reference <a href="#a8cb45d0ad20a27cf9e595f10bf6c6971">m_fileName</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>.</p>

</div>
</div>

### find() {#ae3187e9ba3a99e7867cc70b6d7b45b7c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefItem * RefList::find (int itemId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Returns an item given it's id that is obtained with <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6c177ac509924d60c71b820d39d28b9f">addRefItem()</a></p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">itemId</td>
<td class="doxyParamItemDescription"><p>item's identifier.</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>A pointer to the todo item's structure.</p></dd>
</dl>


<p>Declaration at line 99 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>, definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/reflist-cpp">reflist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3187e9ba3a99e7867cc70b6d7b45b7c">40</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/refitem">RefItem</a> *<a href="#ae3187e9ba3a99e7867cc70b6d7b45b7c">RefList::find</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> itemId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a17bc1029e261db1d27fc066485b28a4d">m_lookup</a>.find(itemId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#a17bc1029e261db1d27fc066485b28a4d">m_lookup</a>.end() ? it-&gt;second : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a17bc1029e261db1d27fc066485b28a4d">m_lookup</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>.</p>

</div>
</div>

### generatePage() {#a1fb6f991a5826241faab676ba08fb5e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void RefList::generatePage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>, definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/reflist-cpp">reflist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1fb6f991a5826241faab676ba08fb5e3">55</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1fb6f991a5826241faab676ba08fb5e3">RefList::generatePage</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#afe342e088292fdea46c56134d3b43b14">isEnabled</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  std::stable_sort(<a href="#a3627ab8d4a351f058aa31a2b70440b2f">m_entries</a>.begin(),<a href="#a3627ab8d4a351f058aa31a2b70440b2f">m_entries</a>.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">            [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unique_ptr&lt;RefItem&gt; &amp;left,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unique_ptr&lt;RefItem&gt; &amp;right)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">            { return qstricmp_sort(left-&gt;title(),right-&gt;title()) &lt; 0; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//RefItem *item;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cnt = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  doc += </span><span class="doxyHighlightStringLiteral">"&lt;dl class=\"reflist\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lastGroup;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unique_ptr&lt;RefItem&gt; &amp;item : <a href="#a3627ab8d4a351f058aa31a2b70440b2f">m_entries</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (item-&gt;name().isEmpty()) </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">    cnt++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> startNewGroup = item-&gt;group()!=lastGroup;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (startNewGroup)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">        doc += </span><span class="doxyHighlightStringLiteral">"&lt;/dd&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">      doc += </span><span class="doxyHighlightStringLiteral">" &lt;dt&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">      doc += </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (item-&gt;scope())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (item-&gt;scope()-&gt;name() != </span><span class="doxyHighlightStringLiteral">"&lt;globalScope&gt;"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">          doc += </span><span class="doxyHighlightStringLiteral">"\\_setscope "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">          doc += item-&gt;scope()-&gt;name();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">          doc += </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">      doc += item-&gt;prefix();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">      doc += </span><span class="doxyHighlightStringLiteral">" \\_internalref "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      doc += item-&gt;name();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// escape \'s in title, see issue #5901</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> escapedTitle = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(item-&gt;title(),</span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"\\\\"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">      doc += </span><span class="doxyHighlightStringLiteral">" \""</span><span class="doxyHighlight">+escapedTitle+</span><span class="doxyHighlightStringLiteral">"\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// write declaration in case a function with arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!item-&gt;args().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// escape @'s in argument list, needed for Java annotations (see issue #6208)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// escape \'s in argument list (see issue #6533)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">        doc += <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(item-&gt;args(),</span><span class="doxyHighlightStringLiteral">"@"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"@@"</span><span class="doxyHighlight">),</span><span class="doxyHighlightStringLiteral">"\\"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"\\\\"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">      doc += </span><span class="doxyHighlightStringLiteral">"&lt;/dt&gt;&lt;dd&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">      doc += </span><span class="doxyHighlightStringLiteral">"&lt;p&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">    doc += </span><span class="doxyHighlightStringLiteral">" \\anchor "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">    doc += item-&gt;anchor();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">    doc += </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    doc += item-&gt;text();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">    lastGroup = item-&gt;group();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">    first = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">    doc += </span><span class="doxyHighlightStringLiteral">"&lt;/dd&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  doc += </span><span class="doxyHighlightStringLiteral">"&lt;/dl&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("generatePage('%s')\n",doc.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cnt&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a118dacc3a4f140d0321d4fb170c8e8f6">addRelatedPage</a>(<a href="#a1b8f629582102465bc198cb011537408">m_listName</a>,<a href="#a4394f2fd08f1569127584ce356855b76">m_pageTitle</a>,doc,<a href="#a8cb45d0ad20a27cf9e595f10bf6c6971">m_fileName</a>,1,1,<a href="/web-doxygen/docs/api/files/src/reflist-h/#a51b03784d48079baab06a4d5c8b08c42">RefItemVector</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a118dacc3a4f140d0321d4fb170c8e8f6">addRelatedPage</a>, <a href="#afe342e088292fdea46c56134d3b43b14">isEnabled</a>, <a href="#a3627ab8d4a351f058aa31a2b70440b2f">m_entries</a>, <a href="#a8cb45d0ad20a27cf9e595f10bf6c6971">m_fileName</a>, <a href="#a1b8f629582102465bc198cb011537408">m_listName</a>, <a href="#a4394f2fd08f1569127584ce356855b76">m_pageTitle</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### isEnabled() {#afe342e088292fdea46c56134d3b43b14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool RefList::isEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>, definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/reflist-cpp">reflist.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afe342e088292fdea46c56134d3b43b14">46</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#afe342e088292fdea46c56134d3b43b14">RefList::isEnabled</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">      (<a href="#a1b8f629582102465bc198cb011537408">m_listName</a>==</span><span class="doxyHighlightStringLiteral">"todo"</span><span class="doxyHighlight">       &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TODOLIST))       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1b8f629582102465bc198cb011537408">m_listName</a>==</span><span class="doxyHighlightStringLiteral">"test"</span><span class="doxyHighlight">       &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TESTLIST))       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1b8f629582102465bc198cb011537408">m_listName</a>==</span><span class="doxyHighlightStringLiteral">"bug"</span><span class="doxyHighlight">        &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_BUGLIST))        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a1b8f629582102465bc198cb011537408">m_listName</a>==</span><span class="doxyHighlightStringLiteral">"deprecated"</span><span class="doxyHighlight"> &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_DEPRECATEDLIST)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a> and <a href="#a1b8f629582102465bc198cb011537408">m_listName</a>.</p>


<p>Referenced by <a href="#a1fb6f991a5826241faab676ba08fb5e3">generatePage</a> and <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>.</p>

</div>
</div>

### listName() {#a7e731cccf3c01e3b8c04c1955e8e0a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString RefList::listName ()</td>
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



<p>Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7e731cccf3c01e3b8c04c1955e8e0a5e">101</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a7e731cccf3c01e3b8c04c1955e8e0a5e">listName</a>()</span><span class="doxyHighlightKeyword"> const      </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1b8f629582102465bc198cb011537408">m_listName</a>;  }</span></span></div>

</div>


<p>Reference <a href="#a1b8f629582102465bc198cb011537408">m_listName</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a8106ebd1a3b46c0d7f00310d3836f058">DefinitionImpl::_getXRefListId</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad14a1e786887639d5383cbcd8427bba8">addXRefItem</a> and <a href="#a36b770703f31caac7df3873136d3d747">RefList</a>.</p>

</div>
</div>

### pageTitle() {#a3ed329a8c21b43e174a88a9152fea631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString RefList::pageTitle ()</td>
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



<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3ed329a8c21b43e174a88a9152fea631">103</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a3ed329a8c21b43e174a88a9152fea631">pageTitle</a>()</span><span class="doxyHighlightKeyword"> const     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a4394f2fd08f1569127584ce356855b76">m_pageTitle</a>; }</span></span></div>

</div>


<p>Reference <a href="#a4394f2fd08f1569127584ce356855b76">m_pageTitle</a>.</p>


<p>Referenced by <a href="#a36b770703f31caac7df3873136d3d747">RefList</a>.</p>

</div>
</div>

### sectionTitle() {#a68687120cabce4bc5e4f2e7ceb37c95d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString RefList::sectionTitle ()</td>
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



<p>Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a68687120cabce4bc5e4f2e7ceb37c95d">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a68687120cabce4bc5e4f2e7ceb37c95d">sectionTitle</a>()</span><span class="doxyHighlightKeyword"> const  </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a256f77e4a8638c72df0883eb07d3dd3f">m_secTitle</a>;  }</span></span></div>

</div>


<p>Reference <a href="#a256f77e4a8638c72df0883eb07d3dd3f">m_secTitle</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_entries {#a3627ab8d4a351f058aa31a2b70440b2f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::unique_ptr&lt; RefItem &gt; &gt; RefList::m_entries</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 114 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3627ab8d4a351f058aa31a2b70440b2f">114</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt; std::unique_ptr&lt; RefItem &gt; &gt; <a href="#a3627ab8d4a351f058aa31a2b70440b2f">m_entries</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a93af6a9f7e50dd639c820d6694471ea8">add</a> and <a href="#a1fb6f991a5826241faab676ba08fb5e3">generatePage</a>.</p>

</div>
</div>

### m\_fileName {#a8cb45d0ad20a27cf9e595f10bf6c6971}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString RefList::m_fileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8cb45d0ad20a27cf9e595f10bf6c6971">111</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a8cb45d0ad20a27cf9e595f10bf6c6971">m_fileName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ae0bc0a1bdcf5f3a4018a09bc79b6dbb3">fileName</a>, <a href="#a1fb6f991a5826241faab676ba08fb5e3">generatePage</a> and <a href="#a36b770703f31caac7df3873136d3d747">RefList</a>.</p>

</div>
</div>

### m\_id {#a6aff430cc301cd0a0d82f7d108d7c5bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int RefList::m_id = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6aff430cc301cd0a0d82f7d108d7c5bd">109</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a6aff430cc301cd0a0d82f7d108d7c5bd">m_id</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a93af6a9f7e50dd639c820d6694471ea8">add</a>.</p>

</div>
</div>

### m\_listName {#a1b8f629582102465bc198cb011537408}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString RefList::m_listName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b8f629582102465bc198cb011537408">110</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a1b8f629582102465bc198cb011537408">m_listName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1fb6f991a5826241faab676ba08fb5e3">generatePage</a>, <a href="#afe342e088292fdea46c56134d3b43b14">isEnabled</a>, <a href="#a7e731cccf3c01e3b8c04c1955e8e0a5e">listName</a> and <a href="#a36b770703f31caac7df3873136d3d747">RefList</a>.</p>

</div>
</div>

### m\_lookup {#a17bc1029e261db1d27fc066485b28a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt; int, RefItem* &gt; RefList::m_lookup</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a17bc1029e261db1d27fc066485b28a4d">115</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unordered_map&lt; int, RefItem* &gt; <a href="#a17bc1029e261db1d27fc066485b28a4d">m_lookup</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a93af6a9f7e50dd639c820d6694471ea8">add</a> and <a href="#ae3187e9ba3a99e7867cc70b6d7b45b7c">find</a>.</p>

</div>
</div>

### m\_pageTitle {#a4394f2fd08f1569127584ce356855b76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString RefList::m_pageTitle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 112 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4394f2fd08f1569127584ce356855b76">112</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4394f2fd08f1569127584ce356855b76">m_pageTitle</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1fb6f991a5826241faab676ba08fb5e3">generatePage</a>, <a href="#a3ed329a8c21b43e174a88a9152fea631">pageTitle</a> and <a href="#a36b770703f31caac7df3873136d3d747">RefList</a>.</p>

</div>
</div>

### m\_secTitle {#a256f77e4a8638c72df0883eb07d3dd3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString RefList::m_secTitle</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a256f77e4a8638c72df0883eb07d3dd3f">113</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a256f77e4a8638c72df0883eb07d3dd3f">m_secTitle</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a36b770703f31caac7df3873136d3d747">RefList</a> and <a href="#a68687120cabce4bc5e4f2e7ceb37c95d">sectionTitle</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/reflist-cpp">reflist.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
