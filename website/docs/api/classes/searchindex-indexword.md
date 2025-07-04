---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/searchindex/indexword
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `IndexWord` Class Reference



## Declaration

<div class="doxyDeclaration">
class SearchIndex::IndexWord { ... }
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5a590b232b406ee918cc062164900eb">URLInfoMap</a> = std::unordered_map&lt; int, <a href="/web-doxygen/docs/api/structs/searchindex/urlinfo">URLInfo</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ad0e87a5eab96bff571f01fd2938366">IndexWord</a> (const QCString &amp;word)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1416b4d68d49dfa058d8526d2cd0d095">addUrlIndex</a> (int, bool)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad5a590b232b406ee918cc062164900eb">URLInfoMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8b2ed23198217e24ae084c5a6f04cc6">urls</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab213434fbfa6af2535272a6b5e89429b">word</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c03691139ef33e89603e16901e4a78e">m_word</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#ad5a590b232b406ee918cc062164900eb">URLInfoMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2cbc84aecabf7ff9c76ecd282e49485">m_urls</a></td>
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


<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### URLInfoMap {#ad5a590b232b406ee918cc062164900eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using SearchIndex::IndexWord::URLInfoMap =  std::unordered_map&lt;int,URLInfo&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5a590b232b406ee918cc062164900eb">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ad5a590b232b406ee918cc062164900eb">URLInfoMap</a> = std::unordered_map&lt;int,URLInfo&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### IndexWord() {#a1ad0e87a5eab96bff571f01fd2938366}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SearchIndex::IndexWord::IndexWord (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; word)</td>
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



<p>Definition at line 85 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ad0e87a5eab96bff571f01fd2938366">85</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1ad0e87a5eab96bff571f01fd2938366">IndexWord</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#ab213434fbfa6af2535272a6b5e89429b">word</a>) : <a href="#a0c03691139ef33e89603e16901e4a78e">m_word</a>(<a href="#ab213434fbfa6af2535272a6b5e89429b">word</a>) {}</span></span></div>

</div>


<p>References <a href="#a0c03691139ef33e89603e16901e4a78e">m_word</a> and <a href="#ab213434fbfa6af2535272a6b5e89429b">word</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addUrlIndex() {#a1416b4d68d49dfa058d8526d2cd0d095}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SearchIndex::IndexWord::addUrlIndex (int idx, bool hiPriority)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>, definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/searchindex-cpp">searchindex.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1416b4d68d49dfa058d8526d2cd0d095">54</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1416b4d68d49dfa058d8526d2cd0d095">SearchIndex::IndexWord::addUrlIndex</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> idx,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hiPriority)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("IndexWord::addUrlIndex(%d,%d)\n",idx,hiPriority);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#af2cbc84aecabf7ff9c76ecd282e49485">m_urls</a>.find(idx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#af2cbc84aecabf7ff9c76ecd282e49485">m_urls</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("URLInfo::URLInfo(%d)\n",idx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">    it = <a href="#af2cbc84aecabf7ff9c76ecd282e49485">m_urls</a>.emplace(idx,<a href="/web-doxygen/docs/api/structs/searchindex/urlinfo">URLInfo</a>(idx,0)).first;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  it-&gt;second.freq+=2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hiPriority) it-&gt;second.freq|=1; </span><span class="doxyHighlightComment">// mark as high priority document</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#af2cbc84aecabf7ff9c76ecd282e49485">m_urls</a>.</p>

</div>
</div>

### urls() {#af8b2ed23198217e24ae084c5a6f04cc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">URLInfoMap SearchIndex::IndexWord::urls ()</td>
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



<p>Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af8b2ed23198217e24ae084c5a6f04cc6">87</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad5a590b232b406ee918cc062164900eb">URLInfoMap</a> <a href="#af8b2ed23198217e24ae084c5a6f04cc6">urls</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af2cbc84aecabf7ff9c76ecd282e49485">m_urls</a>; }</span></span></div>

</div>


<p>Reference <a href="#af2cbc84aecabf7ff9c76ecd282e49485">m_urls</a>.</p>

</div>
</div>

### word() {#ab213434fbfa6af2535272a6b5e89429b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString SearchIndex::IndexWord::word ()</td>
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



<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab213434fbfa6af2535272a6b5e89429b">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab213434fbfa6af2535272a6b5e89429b">word</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0c03691139ef33e89603e16901e4a78e">m_word</a>; }</span></span></div>

</div>


<p>Reference <a href="#a0c03691139ef33e89603e16901e4a78e">m_word</a>.</p>


<p>Referenced by <a href="#a1ad0e87a5eab96bff571f01fd2938366">IndexWord</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_urls {#af2cbc84aecabf7ff9c76ecd282e49485}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">URLInfoMap SearchIndex::IndexWord::m_urls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af2cbc84aecabf7ff9c76ecd282e49485">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad5a590b232b406ee918cc062164900eb">URLInfoMap</a>  <a href="#af2cbc84aecabf7ff9c76ecd282e49485">m_urls</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1416b4d68d49dfa058d8526d2cd0d095">addUrlIndex</a> and <a href="#af8b2ed23198217e24ae084c5a6f04cc6">urls</a>.</p>

</div>
</div>

### m\_word {#a0c03691139ef33e89603e16901e4a78e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString SearchIndex::IndexWord::m_word</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 91 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c03691139ef33e89603e16901e4a78e">91</a></span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>    <a href="#a0c03691139ef33e89603e16901e4a78e">m_word</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a1ad0e87a5eab96bff571f01fd2938366">IndexWord</a> and <a href="#ab213434fbfa6af2535272a6b5e89429b">word</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/searchindex-cpp">searchindex.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
