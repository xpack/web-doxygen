---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/indexlist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IndexList` Class Reference

<p>A list of index interfaces. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class IndexList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/indexlist-h">src/indexlist.h</a>&gt;
</div>

## Private Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a361c1d1735358c3142088340bc7bf513">IndexPtr</a> = std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/indexintf">IndexIntf</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7334e24bfdf93caf3db9d61ae62caf6">disable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>disable the indices <a href="#ae7334e24bfdf93caf3db9d61ae62caf6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabffffbc2e50eeb9437640c369dfd6b7">enable</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>enable the indices <a href="#aabffffbc2e50eeb9437640c369dfd6b7">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab255d94f91cba673bf82de1edc3737ec">isEnabled</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns true iff the indices are enabled <a href="#ab255d94f91cba673bf82de1edc3737ec">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class T, class... As&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a4dca6a37ca55f967119e1301ed976aee">addIndex</a> (As &amp;&amp;... args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Add an index generator to the list, using a syntax similar to std::make_unique&lt;T&gt;() <a href="#a4dca6a37ca55f967119e1301ed976aee">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a104b016afa73759d65b08f6c1cced210">initialize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af04e11231983acb4dbf381e809bfa178">finalize</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6af95293030206c0224260e9b1d7aca">incContentsDepth</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bad65cd2fadab4529bbfe5df78cc019">decContentsDepth</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67dc4e5b8c648a8bd0636a54841c79f4">addContentsItem</a> (bool isDir, const QCString &amp;name, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, bool separateIndex=FALSE, bool addToNavIndex=FALSE, const Definition *def=nullptr, const QCString &amp;nameAsHtml=QCString())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdb8f0434f6e648c6836872121f61917">addIndexItem</a> (const Definition *context, const MemberDef *md, const QCString &amp;sectionAnchor=QCString(), const QCString &amp;title=QCString())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85b310bcd8bd41aa67eba20c39210a0f">addIndexFile</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac3c1b70be363f488269cd9054cc7621">addImageFile</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18b2beeb1826949562e6fd25edd5228f">addStyleSheetFile</a> (const QCString &amp;name)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Ts, class... As&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a71cdaf72e67d7a62166c91cca7fd3937">foreach</a> (void(IndexIntf::*methodPtr)(Ts...), As &amp;&amp;... args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Ts, class... As&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a> (void(IndexIntf::*methodPtr)(Ts...), As &amp;&amp;... args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a> = true</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab5c840991583c98dcf06417cf243be9">m_mutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="#a361c1d1735358c3142088340bc7bf513">IndexPtr</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a455a0ddf0d4ecf1b7b12569169aff51c">m_indices</a></td>
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

<p>A list of index interfaces.</p>


<p>This class itself implements all methods of <a href="/web-doxygen/docs/api/classes/indexintf">IndexIntf</a> and just forwards the calls to all items in the list (composite design pattern).</p>


<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxySectionDef">

## Private Member Typedefs

### IndexPtr {#a361c1d1735358c3142088340bc7bf513}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using IndexList::IndexPtr =  std::unique_ptr&lt;IndexIntf&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a361c1d1735358c3142088340bc7bf513">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a361c1d1735358c3142088340bc7bf513">IndexPtr</a> = std::unique_ptr&lt;IndexIntf&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addContentsItem() {#a67dc4e5b8c648a8bd0636a54841c79f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::addContentsItem (bool isDir, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, bool separateIndex=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, bool addToNavIndex=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def=nullptr, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; nameAsHtml=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
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



<p>Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67dc4e5b8c648a8bd0636a54841c79f4">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a67dc4e5b8c648a8bd0636a54841c79f4">addContentsItem</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isDir, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> separateIndex=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> addToNavIndex=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;nameAsHtml = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>) <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a>(&amp;<a href="/web-doxygen/docs/api/classes/indexintf/#af3a85835b196e67c4e674fbf53bee806">IndexIntf::addContentsItem</a>,isDir,name,ref,file,anchor,separateIndex,addToNavIndex,def,nameAsHtml); }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/indexintf/#af3a85835b196e67c4e674fbf53bee806">IndexIntf::addContentsItem</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a> and <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>.</p>

</div>
</div>

### addImageFile() {#aac3c1b70be363f488269cd9054cc7621}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::addImageFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac3c1b70be363f488269cd9054cc7621">127</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aac3c1b70be363f488269cd9054cc7621">addImageFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>) <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a>(&amp;<a href="/web-doxygen/docs/api/classes/indexintf/#a2b3132671a4c688f5f687a69258936b2">IndexIntf::addImageFile</a>,name); }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/indexintf/#a2b3132671a4c688f5f687a69258936b2">IndexIntf::addImageFile</a>, <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a> and <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>.</p>

</div>
</div>

### addIndex() {#a4dca6a37ca55f967119e1301ed976aee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class T, class... As&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::addIndex (As &amp;&amp;... args)</td>
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

<p>Add an index generator to the list, using a syntax similar to std::make_unique&lt;T&gt;()</p>

<p>Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4dca6a37ca55f967119e1301ed976aee">101</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4dca6a37ca55f967119e1301ed976aee">addIndex</a>(As&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    { <a href="#a455a0ddf0d4ecf1b7b12569169aff51c">m_indices</a>.push_back(std::make_unique&lt;T&gt;(std::forward&lt;As&gt;(args)...)); }</span></span></div>

</div>


<p>Reference <a href="#a455a0ddf0d4ecf1b7b12569169aff51c">m_indices</a>.</p>

</div>
</div>

### addIndexFile() {#a85b310bcd8bd41aa67eba20c39210a0f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::addIndexFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85b310bcd8bd41aa67eba20c39210a0f">124</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a85b310bcd8bd41aa67eba20c39210a0f">addIndexFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>) <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a>(&amp;<a href="/web-doxygen/docs/api/classes/indexintf/#ad3e0b2c34ae7993147c8ba2230197a52">IndexIntf::addIndexFile</a>,name); }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/indexintf/#ad3e0b2c34ae7993147c8ba2230197a52">IndexIntf::addIndexFile</a>, <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a> and <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>.</p>

</div>
</div>

### addIndexItem() {#afdb8f0434f6e648c6836872121f61917}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::addIndexItem (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * context, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sectionAnchor=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
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



<p>Definition at line 121 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afdb8f0434f6e648c6836872121f61917">121</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afdb8f0434f6e648c6836872121f61917">addIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *context,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;sectionAnchor=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>) <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a>(&amp;<a href="/web-doxygen/docs/api/classes/indexintf/#a9d173d7ac4c6f979d95f7b0dc1231415">IndexIntf::addIndexItem</a>,context,md,sectionAnchor,title); }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/indexintf/#a9d173d7ac4c6f979d95f7b0dc1231415">IndexIntf::addIndexItem</a>, <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a> and <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>.</p>

</div>
</div>

### addStyleSheetFile() {#a18b2beeb1826949562e6fd25edd5228f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::addStyleSheetFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 130 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a18b2beeb1826949562e6fd25edd5228f">130</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a18b2beeb1826949562e6fd25edd5228f">addStyleSheetFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>) <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a>(&amp;<a href="/web-doxygen/docs/api/classes/indexintf/#adf6128baf1a24ab479c6541724e0ac2f">IndexIntf::addStyleSheetFile</a>,name); }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/indexintf/#adf6128baf1a24ab479c6541724e0ac2f">IndexIntf::addStyleSheetFile</a>, <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a> and <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>.</p>

</div>
</div>

### decContentsDepth() {#a4bad65cd2fadab4529bbfe5df78cc019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::decContentsDepth ()</td>
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



<p>Definition at line 113 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4bad65cd2fadab4529bbfe5df78cc019">113</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4bad65cd2fadab4529bbfe5df78cc019">decContentsDepth</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>) <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a>(&amp;<a href="/web-doxygen/docs/api/classes/indexintf/#a920918399556e9afd4d927de3d1f4247">IndexIntf::decContentsDepth</a>); }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/indexintf/#a920918399556e9afd4d927de3d1f4247">IndexIntf::decContentsDepth</a>, <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a> and <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>.</p>

</div>
</div>

### disable() {#ae7334e24bfdf93caf3db9d61ae62caf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::disable ()</td>
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

<p>disable the indices</p>

<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae7334e24bfdf93caf3db9d61ae62caf6">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae7334e24bfdf93caf3db9d61ae62caf6">disable</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">    { <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>.</p>

</div>
</div>

### enable() {#aabffffbc2e50eeb9437640c369dfd6b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::enable ()</td>
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

<p>enable the indices</p>

<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aabffffbc2e50eeb9437640c369dfd6b7">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aabffffbc2e50eeb9437640c369dfd6b7">enable</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">    { <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; }</span></span></div>

</div>


<p>References <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### finalize() {#af04e11231983acb4dbf381e809bfa178}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::finalize ()</td>
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



<p>Definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af04e11231983acb4dbf381e809bfa178">107</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af04e11231983acb4dbf381e809bfa178">finalize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/indexintf/#aa5532a767c4ac41167d014209b2ea8d7">IndexIntf::finalize</a>); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/indexintf/#aa5532a767c4ac41167d014209b2ea8d7">IndexIntf::finalize</a>.</p>

</div>
</div>

### incContentsDepth() {#ac6af95293030206c0224260e9b1d7aca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::incContentsDepth ()</td>
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



<p>Definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac6af95293030206c0224260e9b1d7aca">110</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac6af95293030206c0224260e9b1d7aca">incContentsDepth</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>) <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a>(&amp;<a href="/web-doxygen/docs/api/classes/indexintf/#ac5ff1647bcf1cc65543258df162a0a7c">IndexIntf::incContentsDepth</a>); }</span></span></div>

</div>


<p>References <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a>, <a href="/web-doxygen/docs/api/classes/indexintf/#ac5ff1647bcf1cc65543258df162a0a7c">IndexIntf::incContentsDepth</a> and <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>.</p>

</div>
</div>

### initialize() {#a104b016afa73759d65b08f6c1cced210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::initialize ()</td>
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



<p>Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a104b016afa73759d65b08f6c1cced210">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a104b016afa73759d65b08f6c1cced210">initialize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/indexintf/#a0e46b4afa0ed269e2d089c8444590515">IndexIntf::initialize</a>); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/indexintf/#a0e46b4afa0ed269e2d089c8444590515">IndexIntf::initialize</a>.</p>

</div>
</div>

### isEnabled() {#ab255d94f91cba673bf82de1edc3737ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexList::isEnabled ()</td>
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

<p>returns true iff the indices are enabled</p>

<p>Definition at line 96 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab255d94f91cba673bf82de1edc3737ec">96</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab255d94f91cba673bf82de1edc3737ec">isEnabled</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>; }</span></span></div>

</div>


<p>Reference <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### foreach() {#a71cdaf72e67d7a62166c91cca7fd3937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Ts, class... As&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::foreach (void(IndexIntf::*)(Ts...) methodPtr, As &amp;&amp;... args)</td>
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



<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a71cdaf72e67d7a62166c91cca7fd3937">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/indexintf">IndexIntf</a>::*methodPtr)(Ts...),As&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">      for (const auto &amp;intf : m_indices)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">        (intf.get()-&gt;*methodPtr)(std::forward&lt;As&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>

</div>
</div>

### foreach\_locked() {#abdb3ca756e96e27580c7dfd330ad52ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Ts, class... As&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void IndexList::foreach_locked (void(IndexIntf::*)(Ts...) methodPtr, As &amp;&amp;... args)</td>
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



<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abdb3ca756e96e27580c7dfd330ad52ce">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a>(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/indexintf">IndexIntf</a>::*methodPtr)(Ts...),As&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">      std::lock_guard&lt;std::mutex&gt; lock(<a href="#aab5c840991583c98dcf06417cf243be9">m_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;intf : <a href="#a455a0ddf0d4ecf1b7b12569169aff51c">m_indices</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">        (intf.get()-&gt;*methodPtr)(std::forward&lt;As&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a455a0ddf0d4ecf1b7b12569169aff51c">m_indices</a> and <a href="#aab5c840991583c98dcf06417cf243be9">m_mutex</a>.</p>


<p>Referenced by <a href="#a67dc4e5b8c648a8bd0636a54841c79f4">addContentsItem</a>, <a href="#aac3c1b70be363f488269cd9054cc7621">addImageFile</a>, <a href="#a85b310bcd8bd41aa67eba20c39210a0f">addIndexFile</a>, <a href="#afdb8f0434f6e648c6836872121f61917">addIndexItem</a>, <a href="#a18b2beeb1826949562e6fd25edd5228f">addStyleSheetFile</a>, <a href="#a4bad65cd2fadab4529bbfe5df78cc019">decContentsDepth</a> and <a href="#ac6af95293030206c0224260e9b1d7aca">incContentsDepth</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_enabled {#a2ae70269ec6d9a598eadf0f49570b039}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool IndexList::m_enabled = true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ae70269ec6d9a598eadf0f49570b039">134</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2ae70269ec6d9a598eadf0f49570b039">m_enabled</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a67dc4e5b8c648a8bd0636a54841c79f4">addContentsItem</a>, <a href="#aac3c1b70be363f488269cd9054cc7621">addImageFile</a>, <a href="#a85b310bcd8bd41aa67eba20c39210a0f">addIndexFile</a>, <a href="#afdb8f0434f6e648c6836872121f61917">addIndexItem</a>, <a href="#a18b2beeb1826949562e6fd25edd5228f">addStyleSheetFile</a>, <a href="#a4bad65cd2fadab4529bbfe5df78cc019">decContentsDepth</a>, <a href="#ae7334e24bfdf93caf3db9d61ae62caf6">disable</a>, <a href="#aabffffbc2e50eeb9437640c369dfd6b7">enable</a>, <a href="#ac6af95293030206c0224260e9b1d7aca">incContentsDepth</a> and <a href="#ab255d94f91cba673bf82de1edc3737ec">isEnabled</a>.</p>

</div>
</div>

### m\_indices {#a455a0ddf0d4ecf1b7b12569169aff51c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;IndexPtr&gt; IndexList::m_indices</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 136 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a455a0ddf0d4ecf1b7b12569169aff51c">136</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;IndexPtr&gt; <a href="#a455a0ddf0d4ecf1b7b12569169aff51c">m_indices</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a4dca6a37ca55f967119e1301ed976aee">addIndex</a> and <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a>.</p>

</div>
</div>

### m\_mutex {#aab5c840991583c98dcf06417cf243be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex IndexList::m_mutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aab5c840991583c98dcf06417cf243be9">135</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::mutex <a href="#aab5c840991583c98dcf06417cf243be9">m_mutex</a>;</span></span></div>

</div>


<p>Referenced by <a href="#abdb3ca756e96e27580c7dfd330ad52ce">foreach_locked</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
