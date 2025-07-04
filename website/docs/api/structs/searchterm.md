---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/searchterm
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SearchTerm` Struct Reference

<p>Searchable term. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
struct SearchTerm { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/searchindex-js-h">src/searchindex_js.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bc3a5bd44881edc885b23560325eb5f">LinkInfo</a> = std::variant&lt; std::monostate, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *, const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b3d5eea3265628d4e969e52ed6dbf1d">SearchTerm</a> (const QCString &amp;w, const Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a75fbfc914389965cda8a95e6a5709">SearchTerm</a> (const QCString &amp;w, const SectionInfo *s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec66f0d2f6bb7fb2905bc14546af792b">termEncoded</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>encoded version of the search term <a href="#aec66f0d2f6bb7fb2905bc14546af792b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac882a4444faaec272c4a80c69bc40035">makeTitle</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a806ba2eda79b8dc1de6be3177de1b9d9">word</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>lower case word that is indexed (e.g. name of a symbol, or word from a title) <a href="#a806ba2eda79b8dc1de6be3177de1b9d9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7425c2f78a5d28163452433a2a0c64a4">title</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>title to show in the output for this search result <a href="#a7425c2f78a5d28163452433a2a0c64a4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a7bc3a5bd44881edc885b23560325eb5f">LinkInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9294691914e9c1d8e59a1400c5972466">info</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>definition to link to <a href="#a9294691914e9c1d8e59a1400c5972466">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

<p>Searchable term.</p>

<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### LinkInfo {#a7bc3a5bd44881edc885b23560325eb5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SearchTerm::LinkInfo =  std::variant&lt;std::monostate,const Definition *,const SectionInfo *&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7bc3a5bd44881edc885b23560325eb5f">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a7bc3a5bd44881edc885b23560325eb5f">LinkInfo</a> = std::variant&lt;std::monostate,const Definition *,const SectionInfo *&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### SearchTerm() {#a1b3d5eea3265628d4e969e52ed6dbf1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SearchTerm::SearchTerm (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; w, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
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



<p>Definition at line 45 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b3d5eea3265628d4e969e52ed6dbf1d">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1b3d5eea3265628d4e969e52ed6dbf1d">SearchTerm</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;w,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)  : <a href="#a806ba2eda79b8dc1de6be3177de1b9d9">word</a>(w.str()), <a href="#a9294691914e9c1d8e59a1400c5972466">info</a>(d)  { <a href="#ac882a4444faaec272c4a80c69bc40035">makeTitle</a>(); }</span></span></div>

</div>


<p>References <a href="#a9294691914e9c1d8e59a1400c5972466">info</a>, <a href="#ac882a4444faaec272c4a80c69bc40035">makeTitle</a> and <a href="#a806ba2eda79b8dc1de6be3177de1b9d9">word</a>.</p>

</div>
</div>

### SearchTerm() {#a05a75fbfc914389965cda8a95e6a5709}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SearchTerm::SearchTerm (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; w, const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * s)</td>
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



<p>Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a05a75fbfc914389965cda8a95e6a5709">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a05a75fbfc914389965cda8a95e6a5709">SearchTerm</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;w,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *s) : <a href="#a806ba2eda79b8dc1de6be3177de1b9d9">word</a>(w.str()), <a href="#a9294691914e9c1d8e59a1400c5972466">info</a>(s)  { <a href="#ac882a4444faaec272c4a80c69bc40035">makeTitle</a>(); }</span></span></div>

</div>


<p>References <a href="#a9294691914e9c1d8e59a1400c5972466">info</a>, <a href="#ac882a4444faaec272c4a80c69bc40035">makeTitle</a> and <a href="#a806ba2eda79b8dc1de6be3177de1b9d9">word</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### termEncoded() {#aec66f0d2f6bb7fb2905bc14546af792b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString SearchTerm::termEncoded ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>encoded version of the search term</p>

<p>Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>, definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp">searchindex_js.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aec66f0d2f6bb7fb2905bc14546af792b">62</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aec66f0d2f6bb7fb2905bc14546af792b">SearchTerm::termEncoded</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;<a href="#a806ba2eda79b8dc1de6be3177de1b9d9">word</a>.length();i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-h/#ad7d3f4af351080b6dd9f0188fab09fb6">isIdJS</a>(<a href="#a806ba2eda79b8dc1de6be3177de1b9d9">word</a>.at(i)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="#a806ba2eda79b8dc1de6be3177de1b9d9">word</a>.at(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// escape non-identifier characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a> = </span><span class="doxyHighlightStringLiteral">"0123456789ABCDEF"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> uc = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a806ba2eda79b8dc1de6be3177de1b9d9">word</a>.at(i));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; hex[uc&gt;&gt;4];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[uc&amp;0xF];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>(t.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#ad7d3f4af351080b6dd9f0188fab09fb6">isIdJS</a>, <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a> and <a href="#a806ba2eda79b8dc1de6be3177de1b9d9">word</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### makeTitle() {#ac882a4444faaec272c4a80c69bc40035}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SearchTerm::makeTitle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>, definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp">searchindex_js.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac882a4444faaec272c4a80c69bc40035">41</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac882a4444faaec272c4a80c69bc40035">SearchTerm::makeTitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::holds_alternative&lt;const Definition *&gt;(<a href="#a9294691914e9c1d8e59a1400c5972466">info</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *def = std::get&lt;const Definition *&gt;(<a href="#a9294691914e9c1d8e59a1400c5972466">info</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8e">Definition::DefType</a> type = def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7425c2f78a5d28163452433a2a0c64a4">title</a> = type==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eade4f51e436ce466a886244c7a4c373eb">Definition::TypeGroup</a> ?  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a24141a97ca3b089d108db4129d4047f6">parseCommentAsHtml</a>(def,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a>(def)-&gt;groupTitle(),def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>()) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">            type==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eaabb46c37c736d27a367f4ea582a667ca">Definition::TypePage</a>  ?  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a24141a97ca3b089d108db4129d4047f6">parseCommentAsHtml</a>(def,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/pagedef-cpp/#a7697e578ee832ee5d8e992bf6dc93617">toPageDef</a>(def)-&gt;<a href="#a7425c2f78a5d28163452433a2a0c64a4">title</a>(),def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>()) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">                                           def-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a089d345e288212dc9ceb08ca1d80b4db">localName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (std::holds_alternative&lt;const SectionInfo *&gt;(<a href="#a9294691914e9c1d8e59a1400c5972466">info</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si = std::get&lt;const SectionInfo *&gt;(<a href="#a9294691914e9c1d8e59a1400c5972466">info</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7425c2f78a5d28163452433a2a0c64a4">title</a> = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a24141a97ca3b089d108db4129d4047f6">parseCommentAsHtml</a>(si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#a544a0639c73042b305889ab13476fb24">definition</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#ac6aefd1d628bbdb94dc3b8e176a72f9b">title</a>(),si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#a84093d8cc48b4734f6e603de33d398d5">fileName</a>(),si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#a913ddc11cbf4d2e8433da4974c54543b">lineNr</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">    assert(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/sectioninfo/#a544a0639c73042b305889ab13476fb24">SectionInfo::definition</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#a84093d8cc48b4734f6e603de33d398d5">SectionInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="#a9294691914e9c1d8e59a1400c5972466">info</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#a913ddc11cbf4d2e8433da4974c54543b">SectionInfo::lineNr</a>, <a href="/web-doxygen/docs/api/classes/definition/#a089d345e288212dc9ceb08ca1d80b4db">Definition::localName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a24141a97ca3b089d108db4129d4047f6">parseCommentAsHtml</a>, <a href="#a7425c2f78a5d28163452433a2a0c64a4">title</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#ac6aefd1d628bbdb94dc3b8e176a72f9b">SectionInfo::title</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a>, <a href="/web-doxygen/docs/api/files/src/pagedef-cpp/#a7697e578ee832ee5d8e992bf6dc93617">toPageDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eade4f51e436ce466a886244c7a4c373eb">Definition::TypeGroup</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eaabb46c37c736d27a367f4ea582a667ca">Definition::TypePage</a>.</p>


<p>Referenced by <a href="#a1b3d5eea3265628d4e969e52ed6dbf1d">SearchTerm</a> and <a href="#a05a75fbfc914389965cda8a95e6a5709">SearchTerm</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### info {#a9294691914e9c1d8e59a1400c5972466}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LinkInfo SearchTerm::info</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>definition to link to</p>

<p>Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9294691914e9c1d8e59a1400c5972466">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7bc3a5bd44881edc885b23560325eb5f">LinkInfo</a> <a href="#a9294691914e9c1d8e59a1400c5972466">info</a>;                 </span><span class="doxyHighlightComment">//!&lt; definition to link to</span></span></div>

</div>


<p>Referenced by <a href="#ac882a4444faaec272c4a80c69bc40035">makeTitle</a>, <a href="#a1b3d5eea3265628d4e969e52ed6dbf1d">SearchTerm</a> and <a href="#a05a75fbfc914389965cda8a95e6a5709">SearchTerm</a>.</p>

</div>
</div>

### title {#a7425c2f78a5d28163452433a2a0c64a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString SearchTerm::title</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>title to show in the output for this search result</p>

<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7425c2f78a5d28163452433a2a0c64a4">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a7425c2f78a5d28163452433a2a0c64a4">title</a>;                </span><span class="doxyHighlightComment">//!&lt; title to show in the output for this search result</span></span></div>

</div>


<p>Referenced by <a href="#ac882a4444faaec272c4a80c69bc40035">makeTitle</a>.</p>

</div>
</div>

### word {#a806ba2eda79b8dc1de6be3177de1b9d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString SearchTerm::word</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>lower case word that is indexed (e.g. name of a symbol, or word from a title)</p>

<p>Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a806ba2eda79b8dc1de6be3177de1b9d9">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a806ba2eda79b8dc1de6be3177de1b9d9">word</a>;                 </span><span class="doxyHighlightComment">//!&lt; lower case word that is indexed (e.g. name of a symbol, or word from a title)</span></span></div>

</div>


<p>Referenced by <a href="#a1b3d5eea3265628d4e969e52ed6dbf1d">SearchTerm</a>, <a href="#a05a75fbfc914389965cda8a95e6a5709">SearchTerm</a> and <a href="#aec66f0d2f6bb7fb2905bc14546af792b">termEncoded</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp">searchindex_js.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/searchindex-js-h">searchindex_js.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
