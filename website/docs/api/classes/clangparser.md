---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/clangparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ClangParser` Class Reference

<p>Wrapper for to let libclang assisted parsing. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ClangParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/clangparser-h">src/clangparser.h</a>&gt;
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeda45c0fa8d3bd57ead3c5827552bb8">ClangTUParser</a></td>
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

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbfff98bae20ac65c370e5f418fc271c">ClangParser</a> ()</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a668d79df27923e9625fdb60ff9c49e86">~ClangParser</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2aa7186d8f16b07b3496e5769d46b077">createTUParser</a> (const FileDef *fd) const</td>
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

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const clang::tooling::CompilationDatabase *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a891f7ea10dc213bf41bdd457674763d6">database</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/clangparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af94d490423fc12f9c4f35e1debc323f4">p</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/clangparser">ClangParser</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add1060dd5febd4664f6038a87d87b8cd">instance</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the one and only instance of the class. <a href="#add1060dd5febd4664f6038a87d87b8cd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/clangparser">ClangParser</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a214d0c479ca3c5cad1ab31881a93e697">s_instance</a> = nullptr</td>
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

<p>Wrapper for to let libclang assisted parsing.</p>

<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>


<div class="doxySectionDef">

## Friends

### ClangTUParser {#afeda45c0fa8d3bd57ead3c5827552bb8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afeda45c0fa8d3bd57ead3c5827552bb8">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight"><a href="#afeda45c0fa8d3bd57ead3c5827552bb8">ClangTUParser</a>;</span></span></div>

</div>


<p>References <a href="#acbfff98bae20ac65c370e5f418fc271c">ClangParser</a> and <a href="#afeda45c0fa8d3bd57ead3c5827552bb8">ClangTUParser</a>.</p>


<p>Referenced by <a href="#afeda45c0fa8d3bd57ead3c5827552bb8">ClangTUParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Constructors

### ClangParser() {#acbfff98bae20ac65c370e5f418fc271c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClangParser::ClangParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 91 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>, definition at line 995 of file <a href="/web-doxygen/docs/api/files/src/clangparser-cpp">clangparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acbfff98bae20ac65c370e5f418fc271c">995</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#acbfff98bae20ac65c370e5f418fc271c">ClangParser::ClangParser</a>() : <a href="#af94d490423fc12f9c4f35e1debc323f4">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/classes/clangparser/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">996</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">997</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#af94d490423fc12f9c4f35e1debc323f4">p</a>.</p>


<p>Referenced by <a href="#afeda45c0fa8d3bd57ead3c5827552bb8">ClangTUParser</a> and <a href="#add1060dd5febd4664f6038a87d87b8cd">instance</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~ClangParser() {#a668d79df27923e9625fdb60ff9c49e86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClangParser::~ClangParser ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 93 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>, definition at line 999 of file <a href="/web-doxygen/docs/api/files/src/clangparser-cpp">clangparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a668d79df27923e9625fdb60ff9c49e86">999</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a668d79df27923e9625fdb60ff9c49e86">ClangParser::~ClangParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### createTUParser() {#a2aa7186d8f16b07b3496e5769d46b077}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ClangTUParser &gt; ClangParser::createTUParser (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>, definition at line 1003 of file <a href="/web-doxygen/docs/api/files/src/clangparser-cpp">clangparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2aa7186d8f16b07b3496e5769d46b077">1003</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;ClangTUParser&gt; <a href="#a2aa7186d8f16b07b3496e5769d46b077">ClangParser::createTUParser</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6d0fb628b1fc96844bb2836317a3ce5a">generateFileSources</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af69cff788100ddb682f88658018d3969">parseFilesMultiThreading</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae28f1a48382c964843997257b8d171f9">parseFilesSingleThreading</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### database() {#a891f7ea10dc213bf41bdd457674763d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const clang::tooling::CompilationDatabase * ClangParser::database ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#af94d490423fc12f9c4f35e1debc323f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; ClangParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af94d490423fc12f9c4f35e1debc323f4">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#af94d490423fc12f9c4f35e1debc323f4">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#acbfff98bae20ac65c370e5f418fc271c">ClangParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#add1060dd5febd4664f6038a87d87b8cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClangParser * ClangParser::instance ()</td>
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

<p>Returns the one and only instance of the class.</p>

<p>Declaration at line 84 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>, definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/clangparser-cpp">clangparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add1060dd5febd4664f6038a87d87b8cd">34</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#acbfff98bae20ac65c370e5f418fc271c">ClangParser</a> *<a href="#add1060dd5febd4664f6038a87d87b8cd">ClangParser::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/clangparser-cpp/#a2d3ea1645a5e51e8da5f98432bb06cb8">g_clangMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a214d0c479ca3c5cad1ab31881a93e697">s_instance</a>==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) <a href="#a214d0c479ca3c5cad1ab31881a93e697">s_instance</a> = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="#acbfff98bae20ac65c370e5f418fc271c">ClangParser</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a214d0c479ca3c5cad1ab31881a93e697">s_instance</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#acbfff98bae20ac65c370e5f418fc271c">ClangParser</a>, <a href="/web-doxygen/docs/api/files/src/clangparser-cpp/#a2d3ea1645a5e51e8da5f98432bb06cb8">g_clangMutex</a> and <a href="#a214d0c479ca3c5cad1ab31881a93e697">s_instance</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6d0fb628b1fc96844bb2836317a3ce5a">generateFileSources</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af69cff788100ddb682f88658018d3969">parseFilesMultiThreading</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae28f1a48382c964843997257b8d171f9">parseFilesSingleThreading</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### s\_instance {#a214d0c479ca3c5cad1ab31881a93e697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClangParser * ClangParser::s_instance = nullptr</td>
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



<p>Definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a214d0c479ca3c5cad1ab31881a93e697">94</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#acbfff98bae20ac65c370e5f418fc271c">ClangParser</a> *<a href="#a214d0c479ca3c5cad1ab31881a93e697">s_instance</a>;</span></span></div>

</div>


<p>Referenced by <a href="#add1060dd5febd4664f6038a87d87b8cd">instance</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/clangparser-cpp">clangparser.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
