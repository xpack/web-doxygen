---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/outlineparserinterface
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `OutlineParserInterface` Class Reference

Abstract interface for outline parsers. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class OutlineParserInterface { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/parserintf-h">src/parserintf.h</a>&gt;
</div>

## Derived Classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/coutlineparser">COutlineParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
C-like language parser using state-based lexical scanning. <a href="/web-doxygen/docs/api/classes/coutlineparser/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/fortranoutlineparser">FortranOutlineParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Fortran language parser using state-based lexical scanning. <a href="/web-doxygen/docs/api/classes/fortranoutlineparser/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/lexoutlineparser">LexOutlineParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Lex language parser using state-based lexical scanning. <a href="/web-doxygen/docs/api/classes/lexoutlineparser/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/markdownoutlineparser">MarkdownOutlineParser</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/nulloutlineparser">NullOutlineParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
/dev/null outline parser <a href="/web-doxygen/docs/api/classes/nulloutlineparser/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/pythonoutlineparser">PythonOutlineParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Python Language parser using state-based lexical scanning. <a href="/web-doxygen/docs/api/classes/pythonoutlineparser/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdloutlineparser">VHDLOutlineParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
VHDL parser using state-based lexical scanning. <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#details">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40c002cf93d56d617f3ca92ff9b0a210">parseInput</a> (const QCString &amp;fileName, const char *fileBuf, const std::shared_ptr&lt; Entry &gt; &amp;root, ClangTUParser *clangParser)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree. <a href="#a40c002cf93d56d617f3ca92ff9b0a210">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0df8efc6ad67956cf54b7dec68c932b4">needsPreprocessing</a> (const QCString &amp;extension) const =0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser. <a href="#a0df8efc6ad67956cf54b7dec68c932b4">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a69a5b6af5318cae09594b6a48d6b0d99">parsePrototype</a> (const QCString &amp;text)=0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Callback function called by the comment block scanner. <a href="#a69a5b6af5318cae09594b6a48d6b0d99">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Description {#details}

Abstract interface for outline parsers.


By implementing the methods of this interface one can add a new language parser to doxygen. The parser implementation can make use of the comment block parser to parse the contents of special comment blocks.

Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.

<div class="doxySectionDef">

## Public Member Functions

### needsPreprocessing() {#a0df8efc6ad67956cf54b7dec68c932b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual bool OutlineParserInterface::needsPreprocessing (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
</tr>
</table>
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


Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.

Reference <a href="#a0df8efc6ad67956cf54b7dec68c932b4">needsPreprocessing</a>.

Referenced by <a href="#a0df8efc6ad67956cf54b7dec68c932b4">needsPreprocessing</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a>.
</div>
</div>

### parseInput() {#a40c002cf93d56d617f3ca92ff9b0a210}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutlineParserInterface::parseInput (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const char * fileBuf, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> * clangParser)</td>
</tr>
</table>
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
<td class="doxyParamItemDescription">The root of the tree of <a href="/web-doxygen/docs/api/classes/entry">Entry</a> \*nodes representing the information extracted from the file.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] clangParser</td>
<td class="doxyParamItemDescription">The clang translation unit parser object or nullptr if disabled.</td>
</tr>
</table>
</dd>
</dl>

Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.

Reference <a href="#a40c002cf93d56d617f3ca92ff9b0a210">parseInput</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0de2d0d31a0d8029d99e005537ded33b">parseFile</a> and <a href="#a40c002cf93d56d617f3ca92ff9b0a210">parseInput</a>.
</div>
</div>

### parsePrototype() {#a69a5b6af5318cae09594b6a48d6b0d99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">virtual void OutlineParserInterface::parsePrototype (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Callback function called by the comment block scanner.


It provides a string <em>text</em> containing the prototype of a function or variable. The parser should parse this and store the information in the <a href="/web-doxygen/docs/api/classes/entry">Entry</a> node that corresponds with the node for which the comment block parser was invoked.

Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.

Reference <a href="#a69a5b6af5318cae09594b6a48d6b0d99">parsePrototype</a>.

Referenced by <a href="#a69a5b6af5318cae09594b6a48d6b0d99">parsePrototype</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
