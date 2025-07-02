---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/nulloutlineparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `NullOutlineParser` Class Reference

/dev/null outline parser <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class NullOutlineParser { ... }
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outlineparserinterface">OutlineParserInterface</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Abstract interface for outline parsers. <a href="/web-doxygen/docs/api/classes/outlineparserinterface/#details">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38df2f3cd06a4c0c291b6d6d73942bcc">parseInput</a> (const QCString &amp;, const char *, const std::shared_ptr&lt; Entry &gt; &amp;, ClangTUParser *) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree. <a href="#a38df2f3cd06a4c0c291b6d6d73942bcc">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a31b8a88ad4b022d530f92048653ccb96">needsPreprocessing</a> (const QCString &amp;) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser. <a href="#a31b8a88ad4b022d530f92048653ccb96">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf4d08ed3b21fb0cf21313c501ae8962">parsePrototype</a> (const QCString &amp;) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Callback function called by the comment block scanner. <a href="#abf4d08ed3b21fb0cf21313c501ae8962">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

/dev/null outline parser

Definition at line 11290 of file <a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a>.

<div class="doxySectionDef">

## Public Member Functions

### needsPreprocessing() {#a31b8a88ad4b022d530f92048653ccb96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool NullOutlineParser::needsPreprocessing (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser.


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
<a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput()</a>
</dd>
</dl>


Definition at line 11294 of file <a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a31b8a88ad4b022d530f92048653ccb96">11294</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a31b8a88ad4b022d530f92048653ccb96">needsPreprocessing</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.
</div>
</div>

### parseInput() {#a38df2f3cd06a4c0c291b6d6d73942bcc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NullOutlineParser::parseInput (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const char * fileBuf, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> * clangParser)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree.


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileName</td>
<td class="doxyParamItemDescription">The full name of the file.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileBuf</td>
<td class="doxyParamItemDescription">The contents of the file (zero terminated).</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] root</td>
<td class="doxyParamItemDescription">The root of the tree of <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *nodes representing the information extracted from the file.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] clangParser</td>
<td class="doxyParamItemDescription">The clang translation unit parser object or nullptr if disabled.</td>
</tr>
</table>
</dd>
</dl>

Definition at line 11293 of file <a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38df2f3cd06a4c0c291b6d6d73942bcc">11293</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a38df2f3cd06a4c0c291b6d6d73942bcc">parseInput</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/* file */</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> * </span><span class="doxyHighlightComment">/* buf */</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;, <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a>*)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### parsePrototype() {#abf4d08ed3b21fb0cf21313c501ae8962}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void NullOutlineParser::parsePrototype (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Callback function called by the comment block scanner.


It provides a string <em>text</em> containing the prototype of a function or variable. The parser should parse this and store the information in the <a href="/web-doxygen/docs/api/classes/entry">Entry</a> node that corresponds with the node for which the comment block parser was invoked.

Definition at line 11295 of file <a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf4d08ed3b21fb0cf21313c501ae8962">11295</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abf4d08ed3b21fb0cf21313c501ae8962">parsePrototype</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
