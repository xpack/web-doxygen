---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/clangtuparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ClangTUParser` Class Reference

<p>Clang parser object for a single translation unit, which consists of a source file and the directly or indirectly included headers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ClangTUParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/clangparser-h">src/clangparser.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ae7d7d6cd684002b29fe2e71832fb59">ClangTUParser</a> (const ClangParser &amp;parser, const FileDef *fd)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a916b7d9bae60790c26067bb9da3fc3b3">~ClangTUParser</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83aab5c9a3514bd9fdcc7f811f76f3b6">parse</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parse the file given at construction time as a translation unit This file should already be preprocessed by doxygen preprocessor at the time of calling. <a href="#a83aab5c9a3514bd9fdcc7f811f76f3b6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc2a92490b9356caccec16a1691d6f6">switchToFile</a> (const FileDef *fd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Switches to another file within the translation unit started with start(). <a href="#a6cc2a92490b9356caccec16a1691d6f6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08401778d9cffa32a18d6fa4d386c52b">filesInSameTU</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the list of files for this translation unit. <a href="#a08401778d9cffa32a18d6fa4d386c52b">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5e5630ee377b7bb6e2ceaac0b7fe14">lookup</a> (uint32_t line, const char *symbol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Looks for <em>symbol</em> which should be found at <em>line</em>. <a href="#a9a5e5630ee377b7bb6e2ceaac0b7fe14">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebffec25b380d1270e50d9de4b19ff29">writeSources</a> (OutputCodeList &amp;ol, const FileDef *fd)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>writes the syntax highlighted source code for a file <a href="#aebffec25b380d1270e50d9de4b19ff29">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3c280c7fcbe5dbcea58544c5005d50b">detectFunctionBody</a> (const char *s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f520ad0568cd8f55dbb14e02b4fa176">writeLineNumber</a> (OutputCodeList &amp;ol, const FileDef *fd, uint32_t line, bool writeLineAnchor)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92b333e66a19929fc883a3797db88930">codifyLines</a> (OutputCodeList &amp;ol, const FileDef *fd, const char *text, uint32_t &amp;line, uint32_t &amp;column, const char *fontClass=nullptr)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba815688470df6ffcc1d24130b4c4149">writeMultiLineCodeLink</a> (OutputCodeList &amp;ol, const FileDef *fd, uint32_t &amp;line, uint32_t &amp;column, const Definition *d, const char *text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cdcc7b03678ab6a44a31537776fb2d4">linkIdentifier</a> (OutputCodeList &amp;ol, const FileDef *fd, uint32_t &amp;line, uint32_t &amp;column, const char *text, int tokenIndex)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a95cbb7d2b22b9e5e601845002a35745e">linkMacro</a> (OutputCodeList &amp;ol, const FileDef *fd, uint32_t &amp;line, uint32_t &amp;column, const char *text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44068ff5053c7df17f82c6f5845418ad">linkInclude</a> (OutputCodeList &amp;ol, const FileDef *fd, uint32_t &amp;line, uint32_t &amp;column, const char *text)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c031ec328395ac240afdfab06535abd">codeFolding</a> (OutputCodeList &amp;ol, const Definition *d, uint32_t line)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a267c6d6afdc0910f3366e8f7d94c70">endCodeFold</a> (OutputCodeList &amp;ol, uint32_t line)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/clangtuparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1ca582d8d93f77af4b42c8b6b47bbb2">p</a></td>
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

<p>Clang parser object for a single translation unit, which consists of a source file and the directly or indirectly included headers.</p>

<p>Definition at line 24 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ClangTUParser() {#a2ae7d7d6cd684002b29fe2e71832fb59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClangTUParser::ClangTUParser (const <a href="/web-doxygen/docs/api/classes/clangparser">ClangParser</a> &amp; parser, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 27 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>, definition at line 978 of file <a href="/web-doxygen/docs/api/files/src/clangparser-cpp">clangparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ae7d7d6cd684002b29fe2e71832fb59">978</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a2ae7d7d6cd684002b29fe2e71832fb59">ClangTUParser::ClangTUParser</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/clangparser">ClangParser</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *) : <a href="#aa1ca582d8d93f77af4b42c8b6b47bbb2">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/classes/clangtuparser/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#aa1ca582d8d93f77af4b42c8b6b47bbb2">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ClangTUParser() {#a916b7d9bae60790c26067bb9da3fc3b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ClangTUParser::~ClangTUParser ()</td>
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



<p>Declaration at line 29 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>, definition at line 982 of file <a href="/web-doxygen/docs/api/files/src/clangparser-cpp">clangparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a916b7d9bae60790c26067bb9da3fc3b3">982</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a916b7d9bae60790c26067bb9da3fc3b3">ClangTUParser::~ClangTUParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### filesInSameTU() {#a08401778d9cffa32a18d6fa4d386c52b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringVector ClangTUParser::filesInSameTU ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Returns the list of files for this translation unit.</p>

<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

### lookup() {#a9a5e5630ee377b7bb6e2ceaac0b7fe14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string ClangTUParser::lookup (uint32_t line, const char * symbol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Looks for <em>symbol</em> which should be found at <em>line</em>.</p>


<p>returns a clang unique reference to the symbol.</p>


<p>Declaration at line 47 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>, definition at line 986 of file <a href="/web-doxygen/docs/api/files/src/clangparser-cpp">clangparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a5e5630ee377b7bb6e2ceaac0b7fe14">986</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="#a9a5e5630ee377b7bb6e2ceaac0b7fe14">ClangTUParser::lookup</a>(uint32_t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::string();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### parse() {#a83aab5c9a3514bd9fdcc7f811f76f3b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Parse the file given at construction time as a translation unit This file should already be preprocessed by doxygen preprocessor at the time of calling.</p>

<p>Declaration at line 34 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>, definition at line 974 of file <a href="/web-doxygen/docs/api/files/src/clangparser-cpp">clangparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a83aab5c9a3514bd9fdcc7f811f76f3b6">974</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a83aab5c9a3514bd9fdcc7f811f76f3b6">ClangTUParser::parse</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>.</p>

</div>
</div>

### switchToFile() {#a6cc2a92490b9356caccec16a1691d6f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::switchToFile (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Switches to another file within the translation unit started with start().</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fd</td>
<td class="doxyParamItemDescription"><p>The file definition with the name of the file to switch to.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 39 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>, definition at line 970 of file <a href="/web-doxygen/docs/api/files/src/clangparser-cpp">clangparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6cc2a92490b9356caccec16a1691d6f6">970</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6cc2a92490b9356caccec16a1691d6f6">ClangTUParser::switchToFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>.</p>

</div>
</div>

### writeSources() {#aebffec25b380d1270e50d9de4b19ff29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::writeSources (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>writes the syntax highlighted source code for a file</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] ol</td>
<td class="doxyParamItemDescription"><p>The output generator list to write to.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fd</td>
<td class="doxyParamItemDescription"><p>The file to write sources for.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 53 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### codeFolding() {#a6c031ec328395ac240afdfab06535abd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::codeFolding (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, uint32_t line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

### codifyLines() {#a92b333e66a19929fc883a3797db88930}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::codifyLines (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, const char * text, uint32_t &amp; line, uint32_t &amp; column, const char * fontClass=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

### detectFunctionBody() {#ae3c280c7fcbe5dbcea58544c5005d50b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::detectFunctionBody (const char * s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

### endCodeFold() {#a5a267c6d6afdc0910f3366e8f7d94c70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::endCodeFold (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, uint32_t line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

### linkIdentifier() {#a3cdcc7b03678ab6a44a31537776fb2d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::linkIdentifier (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, uint32_t &amp; line, uint32_t &amp; column, const char * text, int tokenIndex)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

### linkInclude() {#a44068ff5053c7df17f82c6f5845418ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::linkInclude (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, uint32_t &amp; line, uint32_t &amp; column, const char * text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

### linkMacro() {#a95cbb7d2b22b9e5e601845002a35745e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::linkMacro (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, uint32_t &amp; line, uint32_t &amp; column, const char * text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

### writeLineNumber() {#a5f520ad0568cd8f55dbb14e02b4fa176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::writeLineNumber (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, uint32_t line, bool writeLineAnchor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

### writeMultiLineCodeLink() {#aba815688470df6ffcc1d24130b4c4149}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ClangTUParser::writeMultiLineCodeLink (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd, uint32_t &amp; line, uint32_t &amp; column, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, const char * text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#aa1ca582d8d93f77af4b42c8b6b47bbb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; ClangTUParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/clangparser-h">clangparser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa1ca582d8d93f77af4b42c8b6b47bbb2">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#aa1ca582d8d93f77af4b42c8b6b47bbb2">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a2ae7d7d6cd684002b29fe2e71832fb59">ClangTUParser</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
