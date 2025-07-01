---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/cite-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `cite.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/cite-h">cite.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/resourcemgr-h">resourcemgr.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/commentscan-h">commentscan.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/linkedmap-h">linkedmap.h</a>"
#include &lt;map&gt;
#include &lt;unordered_map&gt;
#include &lt;string&gt;
#include &lt;fstream&gt;
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/citeposition">CitePosition</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
class that provide information about the p\[osition of a citation name <a href="/web-doxygen/docs/api/classes/citeposition/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/citeinfoimpl">CiteInfoImpl</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/citationmanager/private">Private</a></td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a883e572433098a2f3714d29ddc109fc8">getBibFile</a> (const QCString &amp;inFile)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcc2fda3b5de9ceebd210f6faaa349ec">bibTmpFile</a> = "bibTmpFile\_"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acec8b941b54c02ca0bff82944d34cb5a">bibTmpDir</a> = "bibTmpDir/"</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98402aa01b6229891b70c079b6ce7b59">g_formulaMarker</a> = "CITE\_FORMULA\_"</td>
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


<div class="doxySectionDef">

## Functions

### getBibFile() {#a883e572433098a2f3714d29ddc109fc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString getBibFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inFile)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a883e572433098a2f3714d29ddc109fc8">50</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a883e572433098a2f3714d29ddc109fc8">getBibFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name = inFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; !name.<a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">endsWith</a>(</span><span class="doxyHighlightStringLiteral">".bib"</span><span class="doxyHighlight">)) name+=</span><span class="doxyHighlightStringLiteral">".bib"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a419394d9b5a9a18d4465ce4017f646d0">QCString::endsWith</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a> and <a href="/web-doxygen/docs/api/classes/citationmanager/#a37a4055f986c73a8de48cd5d19bdd2dc">CitationManager::latexBibFiles</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### bibTmpDir {#acec8b941b54c02ca0bff82944d34cb5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* bibTmpDir = "bibTmpDir/"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acec8b941b54c02ca0bff82944d34cb5a">38</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#acec8b941b54c02ca0bff82944d34cb5a">bibTmpDir</a>  = </span><span class="doxyHighlightStringLiteral">"bibTmpDir/"</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>.
</div>
</div>

### bibTmpFile {#abcc2fda3b5de9ceebd210f6faaa349ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* bibTmpFile = "bibTmpFile\_"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abcc2fda3b5de9ceebd210f6faaa349ec">37</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#abcc2fda3b5de9ceebd210f6faaa349ec">bibTmpFile</a> = </span><span class="doxyHighlightStringLiteral">"bibTmpFile_"</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a> and <a href="/web-doxygen/docs/api/classes/citationmanager/#a37a4055f986c73a8de48cd5d19bdd2dc">CitationManager::latexBibFiles</a>.
</div>
</div>

### g\_formulaMarker {#a98402aa01b6229891b70c079b6ce7b59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::string g_formulaMarker = "CITE\_FORMULA\_"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 236 of file <a href="/web-doxygen/docs/api/files/src/cite-cpp">cite.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a98402aa01b6229891b70c079b6ce7b59">236</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string <a href="#a98402aa01b6229891b70c079b6ce7b59">g_formulaMarker</a> = </span><span class="doxyHighlightStringLiteral">"CITE_FORMULA_"</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/citationmanager/#af1366ac568f1a1620961826edd2e88e7">CitationManager::getFormulas</a> and <a href="/web-doxygen/docs/api/classes/citationmanager/#a5f5bce72519f9278f849a2c4cf936393">CitationManager::replaceFormulas</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
