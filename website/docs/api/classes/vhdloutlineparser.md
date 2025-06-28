---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdloutlineparser
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `VHDLOutlineParser` Class Reference

<p>VHDL parser using state-based lexical scanning. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class VHDLOutlineParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">src/vhdljjparser.h</a>&gt;
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
<p>Abstract interface for outline parsers. <a href="/web-doxygen/docs/api/classes/outlineparserinterface/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afed30c38099a7370ae59ee670b7dc5e4">VHDLOutlineParser</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a720bede15c3f3a9bc3b196bd905b3476">~VHDLOutlineParser</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6df9d0420902e8579fb9dbbfa5c1a90">parseInput</a> (const QCString &amp;fileName, const char *fileBuf, const std::shared_ptr&lt; Entry &gt; &amp;root, ClangTUParser *clangParser) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree. <a href="#ad6df9d0420902e8579fb9dbbfa5c1a90">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c2c07d943edd6653badbcb7522b8142">needsPreprocessing</a> (const QCString &amp;) const override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser. <a href="#a3c2c07d943edd6653badbcb7522b8142">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1fa467bd9ba716dc3c2fd34d7ab504e">parsePrototype</a> (const QCString &amp;text) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Callback function called by the comment block scanner. <a href="#ac1fa467bd9ba716dc3c2fd34d7ab504e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4766c5dbf7960f4fa83455c58853bce6">setLineParsed</a> (int tok)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefcc1d2dbf645f02721318d6026855a3">getLine</a> (int tok)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdeb15eb8abda3117c648783e60133fc">getLine</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa00031a2d8766a111e037878b9b2f3ca">lineCount</a> (const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cf53b5cdea9c828c4b676c80d69860d">lineCount</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2d13dc3387c6e7495a02620cd1c1efe">addProto</a> (const QCString &amp;s1, const QCString &amp;s2, const QCString &amp;s3, const QCString &amp;s4, const QCString &amp;s5, const QCString &amp;s6)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae05c8d947347501c75f04b3b3cae49ab">createFunction</a> (const QCString &amp;impure, VhdlSpecifier spec, const QCString &amp;fname)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a591d0ef44da80f3a2f87515755126295">addVhdlType</a> (const QCString &amp;n, int startLine, EntryType section, VhdlSpecifier spec, const QCString &amp;args, const QCString &amp;type, Protection prot)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab277b2256102ea5cba0023d0ccdeca3b">addCompInst</a> (const QCString &amp;n, const QCString &amp;instName, const QCString &amp;comp, int iLine)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3df5816f7dcd092e39a99ebaf9b983cf">handleCommentBlock</a> (const QCString &amp;doc, bool brief)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad52018c3c0f56dc9cfdfad34b45fae26">handleFlowComment</a> (const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ecb445c39b769e5602ca96de2e93323">initEntry</a> (Entry *e)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e2731ccb031a7e2914e7583cc7bdff9">newEntry</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabc6c0e6b285c280ffa531cace06e2e4">isFuncProcProced</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6252fa90e33ae2f5a1a58b1ccf2c2f5">pushLabel</a> (QCString &amp;, QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa32a03da6438377d962da12f57b0f2c0">popLabel</a> (QCString &amp;q)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae48ed44191778c99e285f17b7e14377">addLibUseClause</a> (const QCString &amp;type)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd4e9dc2db18f93819d8fbddf554efa4">mapLibPackage</a> (Entry *root)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab36fc7f90b85f9a369604444f3a6e203">createFlow</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a251d5cfa601b855d867ca28f7c149644">error_skipto</a> (int kind)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7910d0ac9f615f9ce451bd0c71d15da6">oneLineComment</a> (QCString qcs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2256dfdfdf6a1d9be93a881cd4eb526">setMultCommentLine</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3687656c1045cb4c1c5177bbab2c83e">checkMultiComment</a> (QCString &amp;qcs, int line)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a745036e883331351a306bae43e27c1a4">insertEntryAtLine</a> (std::shared_ptr&lt; Entry &gt; ce, int line)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada253943236861987284e1b340603dbd">getNameID</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>returns a unique id for each record member. <a href="#ada253943236861987284e1b340603dbd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18ea453a7fdcb15b665135112de6ff06">checkInlineCode</a> (QCString &amp;doc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/vhdloutlineparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a></td>
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

<p>VHDL parser using state-based lexical scanning.</p>


<p>This is the VHDL language parser for doxygen.</p>

<p>Definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### VHDLOutlineParser() {#afed30c38099a7370ae59ee670b7dc5e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VHDLOutlineParser::VHDLOutlineParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 30 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afed30c38099a7370ae59ee670b7dc5e4">124</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#afed30c38099a7370ae59ee670b7dc5e4">VHDLOutlineParser::VHDLOutlineParser</a>() : <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/vhdloutlineparser/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### ~VHDLOutlineParser() {#a720bede15c3f3a9bc3b196bd905b3476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VHDLOutlineParser::~VHDLOutlineParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 31 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a720bede15c3f3a9bc3b196bd905b3476">128</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a720bede15c3f3a9bc3b196bd905b3476">VHDLOutlineParser::~VHDLOutlineParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCompInst() {#ab277b2256102ea5cba0023d0ccdeca3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::addCompInst (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; n, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; instName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; comp, int iLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 52 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 479 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab277b2256102ea5cba0023d0ccdeca3b">479</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab277b2256102ea5cba0023d0ccdeca3b">VHDLOutlineParser::addCompInst</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;n, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;instName, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;comp,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> iLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> *s = &amp;<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;shared;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;vhdlSpec=<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">VhdlSpecifier::INSTANTIATION</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;section=EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;startLine=iLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;bodyLine=iLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;type=instName;                       </span><span class="doxyHighlightComment">// foo:instname e.g proto or work. proto(ttt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;exception=s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#ae651ad17ada9d06a6b17096dacdda8b2">genLabels</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();         </span><span class="doxyHighlightComment">// |arch|label1:label2...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;name=n;                              </span><span class="doxyHighlightComment">// foo</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;args=s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a>-&gt;name;             </span><span class="doxyHighlightComment">// architecture name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;includeName=comp;                    </span><span class="doxyHighlightComment">// component/entity/configuration</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> u=s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#ae651ad17ada9d06a6b17096dacdda8b2">genLabels</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"|"</span><span class="doxyHighlight">,1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (u&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;write=s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#ae651ad17ada9d06a6b17096dacdda8b2">genLabels</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#ae651ad17ada9d06a6b17096dacdda8b2">genLabels</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-u);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;read=s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#ae651ad17ada9d06a6b17096dacdda8b2">genLabels</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(u);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf  (" \n genlabel: [%s]  inst: [%s]  name: [%s] %d\n",n,instName,comp,iLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;args=s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a>-&gt;name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// !findInstant(current-&gt;type))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9ecb445c39b769e5602ca96de2e93323">initEntry</a>(s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// TODO: protect with mutex</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a61ffdba0efc8d9b6390969cb7fa5d37b">g_instFiles</a>.emplace_back(std::make_shared&lt;Entry&gt;(*s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// TODO: end protect with mutex</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>=std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8e2731ccb031a7e2914e7583cc7bdff9">newEntry</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">vhdl::parser::VhdlParser::SharedState::current</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a61ffdba0efc8d9b6390969cb7fa5d37b">g&#95;instFiles</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#ae651ad17ada9d06a6b17096dacdda8b2">vhdl::parser::VhdlParser::SharedState::genLabels</a>, <a href="#a9ecb445c39b769e5602ca96de2e93323">initEntry</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a738a1b45bfeea63f32029dc677b697d2">INSTANTIATION</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">vhdl::parser::VhdlParser::SharedState::lastCompound</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="#a8e2731ccb031a7e2914e7583cc7bdff9">newEntry</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>.
</div>
</div>

### addLibUseClause() {#aae48ed44191778c99e285f17b7e14377}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VHDLOutlineParser::addLibUseClause (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 60 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 714 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aae48ed44191778c99e285f17b7e14377">714</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aae48ed44191778c99e285f17b7e14377">VHDLOutlineParser::addLibUseClause</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showIEEESTD=<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FORCE_LOCAL_INCLUDES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (showIEEESTD) </span><span class="doxyHighlightComment">// all standard packages and libraries will not be shown</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"ieee"</span><span class="doxyHighlight">)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"std"</span><span class="doxyHighlight">)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#afd4e9dc2db18f93819d8fbddf554efa4">mapLibPackage</a>.
</div>
</div>

### addProto() {#af2d13dc3387c6e7495a02620cd1c1efe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::addProto (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s3, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s4, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s5, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s6)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 49 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 634 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af2d13dc3387c6e7495a02620cd1c1efe">634</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af2d13dc3387c6e7495a02620cd1c1efe">VHDLOutlineParser::addProto</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s3,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s4,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s5,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s6)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> *s = &amp;<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;shared;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">  (void)s5; </span><span class="doxyHighlightComment">// avoid unused warning</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name=s2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> ql=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;n : ql)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/argument">Argument</a> arg;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">    arg.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>=n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s3.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">      arg.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a>=s3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">    arg.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a>+=</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">    arg.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a>+=s4;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s6.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">      arg.<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a>+=s6;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a4f099ecf9b3c15a81b472b8aa7500f81">parse_sec</a>==<a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55bace9b6b1321f6162e00ed2ae15192733f">VhdlSection::GEN_SEC</a> &amp;&amp; s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a6603dae57b0613b5d703220ea1154e6c">param_sec</a>==<a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55ba696b031073e74bf2cb98e5ef201d4aa3">VhdlSection::UNKNOWN</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">      arg.<a href="/web-doxygen/docs/api/structs/argument/#a4fe1d9319dede52f7551f59297772efa">defval</a>=</span><span class="doxyHighlightStringLiteral">"generic"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a4f099ecf9b3c15a81b472b8aa7500f81">parse_sec</a>==<a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55ba03e3141cc2c3c15cbb2e2e901cb51f51">VhdlSection::PARAM_SEC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//  assert(false);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">    arg.<a href="/web-doxygen/docs/api/structs/argument/#a4fe1d9319dede52f7551f59297772efa">defval</a>+=s1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">    arg.<a href="/web-doxygen/docs/api/structs/argument/#aff930f2a4cb85b5616be79b81db2341f">attrib</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span><span class="doxyHighlightComment">//s6;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;argList.push_back(arg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;args+=s2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;args+=</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/argument/#aff930f2a4cb85b5616be79b81db2341f">Argument::attrib</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">vhdl::parser::VhdlParser::SharedState::current</a>, <a href="/web-doxygen/docs/api/structs/argument/#a4fe1d9319dede52f7551f59297772efa">Argument::defval</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55bace9b6b1321f6162e00ed2ae15192733f">GEN&#95;SEC</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">Argument::name</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55ba03e3141cc2c3c15cbb2e2e901cb51f51">PARAM&#95;SEC</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a6603dae57b0613b5d703220ea1154e6c">vhdl::parser::VhdlParser::SharedState::param&#95;sec</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a4f099ecf9b3c15a81b472b8aa7500f81">vhdl::parser::VhdlParser::SharedState::parse&#95;sec</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">Argument::type</a> and <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55ba696b031073e74bf2cb98e5ef201d4aa3">UNKNOWN</a>.
</div>
</div>

### addVhdlType() {#a591d0ef44da80f3a2f87515755126295}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::addVhdlType (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; n, int startLine, <a href="/web-doxygen/docs/api/classes/entrytype">EntryType</a> section, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> spec, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; args, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type, <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 51 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 521 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a591d0ef44da80f3a2f87515755126295">521</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a591d0ef44da80f3a2f87515755126295">VHDLOutlineParser::addVhdlType</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;n,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine,<a href="/web-doxygen/docs/api/classes/entrytype">EntryType</a> section,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> spec,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;args,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;type,<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> *s = &amp;<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;shared;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aabc6c0e6b285c280ffa531cace06e2e4">isFuncProcProced</a>() || <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a12b2126cfa1cf80aeab17ae40d673d67">VhdlDocGen::getFlowMember</a>())  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a4f099ecf9b3c15a81b472b8aa7500f81">parse_sec</a>==<a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55bace9b6b1321f6162e00ed2ae15192733f">VhdlSection::GEN_SEC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">    spec=<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">VhdlSpecifier::GENERIC</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> ql=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> u=0;u&lt;ql.size();u++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;name=ql[u];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;startLine=startLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;bodyLine=startLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;section=section;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;vhdlSpec=spec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;fileName=<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyFileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;args.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">      s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;args=args;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;type=type;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;protection=prot;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a> &amp;&amp; section.isVariable() &amp;&amp;  (spec == <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">VhdlSpecifier::USE</a> || spec == <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">VhdlSpecifier::LIBRARY</a>) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;libUse.emplace_back(std::make_shared&lt;Entry&gt;(*s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">      s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8e2731ccb031a7e2914e7583cc7bdff9">newEntry</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">vhdl::parser::VhdlParser::SharedState::current</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55bace9b6b1321f6162e00ed2ae15192733f">GEN&#95;SEC</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">GENERIC</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a12b2126cfa1cf80aeab17ae40d673d67">VhdlDocGen::getFlowMember</a>, <a href="#aabc6c0e6b285c280ffa531cace06e2e4">isFuncProcProced</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">vhdl::parser::VhdlParser::SharedState::lastCompound</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91acb0a59495dfabbf78b33afa5ea3aa341">LIBRARY</a>, <a href="#a8e2731ccb031a7e2914e7583cc7bdff9">newEntry</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a4f099ecf9b3c15a81b472b8aa7500f81">vhdl::parser::VhdlParser::SharedState::parse&#95;sec</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a7dc33953b23388ad93a4db20e33d26e4">USE</a>.
</div>
</div>

### checkInlineCode() {#a18ea453a7fdcb15b665135112de6ff06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VHDLOutlineParser::checkInlineCode (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; doc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 69 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 277 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a18ea453a7fdcb15b665135112de6ff06">277</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> csRe(R</span><span class="doxyHighlightStringLiteral">"([\\@]code)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> cendRe(R</span><span class="doxyHighlightStringLiteral">"(\s*[\\@]endcode)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> cbriefRe(R</span><span class="doxyHighlightStringLiteral">"([\\@]brief)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">  </span><span class="doxyHighlightComment">// helper to simulate behavior of QString.find(const QRegExp &amp;re,int pos)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> findRe = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> &amp;re,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos=0) -&gt; </span><span class="doxyHighlightKeywordType">int</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)str.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()&lt;pos) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string s = str.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(s,match,re,pos)) </span><span class="doxyHighlightComment">// match found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)match.position();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// not found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> replaceRe = [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> &amp;re,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;replacement) -&gt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/namespaces/reg/#ab6913d787be9fe9992c8804af851fab9">reg::replace</a>(str.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(), re, replacement.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index = findRe(doc,csRe);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (findRe(doc,cendRe)!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (index &lt; 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> index;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> *s = &amp;<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;shared;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;strComment += doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;code = findRe(<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;inputString,csRe, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;code + 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> com = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;inputString.find(<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;strComment.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ref = findRe(<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;inputString,cendRe, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;code + 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;strComment.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ll = com + len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> diff = ref - ll - 3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> code = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;inputString.mid(ll, diff);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> iLine = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">  code = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a>(code, iLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val = code.<a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">contains</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>(<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;strComment);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> ql = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;strComment.str(),</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> co;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> na;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;qcs_ : ql)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qcs(qcs_);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">    qcs = qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">simplifyWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (findRe(qcs,csRe)!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j = qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i &gt; 0 &amp;&amp; j &gt; 0 &amp;&amp; j &gt; i)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">        na = qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i + 1, (j - i - 1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">    qcs = replaceRe(qcs,cbriefRe, </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">    co += qcs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">    co += </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>(co);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/entry">Entry</a> gBlock;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!na.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">    gBlock.<a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">name</a> = na;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">    gBlock.<a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">name</a> = </span><span class="doxyHighlightStringLiteral">"misc"</span><span class="doxyHighlight"> + <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2e65f831a03ff54d13240da96843cd60">VhdlDocGen::getRecordNumber</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">  gBlock.<a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">startLine</a> = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr+iLine-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">  gBlock.<a href="/web-doxygen/docs/api/classes/entry/#a9a2b1e3404f4723d8a6bef5966146ed0">bodyLine</a> = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr+iLine-1 ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">  gBlock.<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a> = code;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">  gBlock.<a href="/web-doxygen/docs/api/classes/entry/#a51e209dbd21d11b0c63d246efa6182f2">inbodyDocs</a> = code;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">  gBlock.<a href="/web-doxygen/docs/api/classes/entry/#ad602ba19af5785515ed81790d843ce4c">brief</a> = co;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">  gBlock.<a href="/web-doxygen/docs/api/classes/entry/#a967db0d8493a46efab87a53d423161eb">section</a> = EntryType::makeVariable();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">  gBlock.<a href="/web-doxygen/docs/api/classes/entry/#a0906aa255ba83045d2d2de1d0d5c8b74">vhdlSpec</a> = <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">VhdlSpecifier::MISCELLANEOUS</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">  gBlock.<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a> = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyFileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">  gBlock.<a href="/web-doxygen/docs/api/classes/entry/#a2db88158279ecfe391ea775f63869fc1">endBodyLine</a> = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr + val +iLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">  gBlock.<a href="/web-doxygen/docs/api/classes/entry/#a4ee5bbd6ac8bdf2f017d93edcefce5e9">lang</a> = SrcLangExt::VHDL;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; compound;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a04773fa91cfdf6d65710f84b2c35417f">lastEntity</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">    compound = s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a04773fa91cfdf6d65710f84b2c35417f">lastEntity</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">    compound = s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">    compound = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (compound)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">    compound-&gt;copyToSubEntry(&amp;gBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">    gBlock.<a href="/web-doxygen/docs/api/classes/entry/#a79a9b5736630c3769e645f71dc357b9f">type</a> = </span><span class="doxyHighlightStringLiteral">"misc"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// global code like library ieee...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1943eaf985ae6ae0a3316b65f2810ac1">current_root</a>-&gt;copyToSubEntry(&amp;gBlock);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;strComment.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/entry/#a9a2b1e3404f4723d8a6bef5966146ed0">Entry::bodyLine</a>, <a href="/web-doxygen/docs/api/classes/entry/#ad602ba19af5785515ed81790d843ce4c">Entry::brief</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aeeedb2810a85c682c2f2a86bcd2355a7">QCString::contains</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1943eaf985ae6ae0a3316b65f2810ac1">vhdl::parser::VhdlParser::SharedState::current&#95;root</a>, <a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">Entry::doc</a>, <a href="/web-doxygen/docs/api/classes/entry/#a2db88158279ecfe391ea775f63869fc1">Entry::endBodyLine</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2e65f831a03ff54d13240da96843cd60">VhdlDocGen::getRecordNumber</a>, <a href="/web-doxygen/docs/api/classes/entry/#a51e209dbd21d11b0c63d246efa6182f2">Entry::inbodyDocs</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/entry/#a4ee5bbd6ac8bdf2f017d93edcefce5e9">Entry::lang</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">vhdl::parser::VhdlParser::SharedState::lastCompound</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a04773fa91cfdf6d65710f84b2c35417f">vhdl::parser::VhdlParser::SharedState::lastEntity</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91aa17d8ffb0b755e300c5df2d818354e8a">MISCELLANEOUS</a>, <a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">Entry::name</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#ab6913d787be9fe9992c8804af851fab9">reg::replace</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>, <a href="/web-doxygen/docs/api/classes/entry/#a967db0d8493a46efab87a53d423161eb">Entry::section</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">QCString::simplifyWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>, <a href="/web-doxygen/docs/api/classes/entry/#a81bf40c0a6646dc1e33097d7e2552c96">Entry::startLine</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a>, <a href="/web-doxygen/docs/api/classes/entry/#a79a9b5736630c3769e645f71dc357b9f">Entry::type</a> and <a href="/web-doxygen/docs/api/classes/entry/#a0906aa255ba83045d2d2de1d0d5c8b74">Entry::vhdlSpec</a>.

Referenced by <a href="#a3df5816f7dcd092e39a99ebaf9b983cf">handleCommentBlock</a>.
</div>
</div>

### checkMultiComment() {#ab3687656c1045cb4c1c5177bbab2c83e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VHDLOutlineParser::checkMultiComment (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; qcs, int line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 66 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 812 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab3687656c1045cb4c1c5177bbab2c83e">812</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab3687656c1045cb4c1c5177bbab2c83e">VHDLOutlineParser::checkMultiComment</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; qcs,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> *s = &amp;<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;shared;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a745036e883331351a306bae43e27c1a4">insertEntryAtLine</a>(s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1943eaf985ae6ae0a3316b65f2810ac1">current_root</a>,line);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;lineEntry.empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>(qcs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;lineEntry.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">    std::shared_ptr&lt;Entry&gt; e=<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;lineEntry.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">    e-&gt;briefLine=line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">    e-&gt;brief+=qcs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;lineEntry.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1943eaf985ae6ae0a3316b65f2810ac1">vhdl::parser::VhdlParser::SharedState::current&#95;root</a>, <a href="#a745036e883331351a306bae43e27c1a4">insertEntryAtLine</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>.

Referenced by <a href="#a3df5816f7dcd092e39a99ebaf9b983cf">handleCommentBlock</a> and <a href="#a7910d0ac9f615f9ce451bd0c71d15da6">oneLineComment</a>.
</div>
</div>

### createFlow() {#ab36fc7f90b85f9a369604444f3a6e203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::createFlow ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 62 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 746 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab36fc7f90b85f9a369604444f3a6e203">746</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab36fc7f90b85f9a369604444f3a6e203">VHDLOutlineParser::createFlow</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> *s = &amp;<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;shared;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/vhdldocgen/#a12b2126cfa1cf80aeab17ae40d673d67">VhdlDocGen::getFlowMember</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> q,ret;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">currP</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">VhdlSpecifier::FUNCTION</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">    q=</span><span class="doxyHighlightStringLiteral">":function( "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/flowchart/#a33fa889d7e70cd1c2cab56a16790d9b5">FlowChart::alignFuncProc</a>(q,s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a7c8599a22b37b4e528d5372f2c1ab164">tempEntry</a>-&gt;argList,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">    q+=</span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">currP</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">VhdlSpecifier::PROCEDURE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">    q=</span><span class="doxyHighlightStringLiteral">":procedure ("</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/flowchart/#a33fa889d7e70cd1c2cab56a16790d9b5">FlowChart::alignFuncProc</a>(q,s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a7c8599a22b37b4e528d5372f2c1ab164">tempEntry</a>-&gt;argList,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">    q+=</span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">    q=</span><span class="doxyHighlightStringLiteral">":process( "</span><span class="doxyHighlight">+s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a7c8599a22b37b4e528d5372f2c1ab164">tempEntry</a>-&gt;args;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">    q+=</span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">  q.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(<a href="/web-doxygen/docs/api/classes/vhdldocgen/#a12b2126cfa1cf80aeab17ae40d673d67">VhdlDocGen::getFlowMember</a>()-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/flowchart/#a5e2d1232239471126aade777574d9d34">FlowChart::addFlowChart</a>(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca1d1feec1c0b7fc94f2de8265155467ec">FlowChart::START_NO</a>,q,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">currP</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">VhdlSpecifier::FUNCTION</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">    ret=</span><span class="doxyHighlightStringLiteral">"end function "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">currP</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">VhdlSpecifier::PROCEDURE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">    ret=</span><span class="doxyHighlightStringLiteral">"end procedure"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">    ret=</span><span class="doxyHighlightStringLiteral">"end process "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/flowchart/#a5e2d1232239471126aade777574d9d34">FlowChart::addFlowChart</a>(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572cacd28dbdea10a3dc04788bb5b7f93237a">FlowChart::END_NO</a>,ret,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//  FlowChart::printFlowList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/flowchart/#a66989e6892ad6bbb539241dedbfc4f9e">FlowChart::writeFlowChart</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">currP</a>=<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a696b031073e74bf2cb98e5ef201d4aa3">VhdlSpecifier::UNKNOWN</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/flowchart/#a5e2d1232239471126aade777574d9d34">FlowChart::addFlowChart</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a33fa889d7e70cd1c2cab56a16790d9b5">FlowChart::alignFuncProc</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">vhdl::parser::VhdlParser::SharedState::currP</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572cacd28dbdea10a3dc04788bb5b7f93237a">FlowChart::END&#95;NO</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">FUNCTION</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a12b2126cfa1cf80aeab17ae40d673d67">VhdlDocGen::getFlowMember</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">PROCEDURE</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca1d1feec1c0b7fc94f2de8265155467ec">FlowChart::START&#95;NO</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a7c8599a22b37b4e528d5372f2c1ab164">vhdl::parser::VhdlParser::SharedState::tempEntry</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a696b031073e74bf2cb98e5ef201d4aa3">UNKNOWN</a> and <a href="/web-doxygen/docs/api/classes/flowchart/#a66989e6892ad6bbb539241dedbfc4f9e">FlowChart::writeFlowChart</a>.
</div>
</div>

### createFunction() {#ae05c8d947347501c75f04b3b3cae49ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::createFunction (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; impure, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> spec, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fname)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 50 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 559 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae05c8d947347501c75f04b3b3cae49ab">559</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae05c8d947347501c75f04b3b3cae49ab">VHDLOutlineParser::createFunction</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;impure,<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> spec,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fname)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> *s = &amp;<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;shared;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;vhdlSpec=spec;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;section=EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (impure==</span><span class="doxyHighlightStringLiteral">"impure"</span><span class="doxyHighlight"> || impure==</span><span class="doxyHighlightStringLiteral">"pure"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;exception=impure;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a4f099ecf9b3c15a81b472b8aa7500f81">parse_sec</a>==<a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55bace9b6b1321f6162e00ed2ae15192733f">VhdlSection::GEN_SEC</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;vhdlSpec=<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">VhdlSpecifier::GENERIC</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;section=EntryType::makeFunction();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">currP</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">VhdlSpecifier::PROCEDURE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;name=impure;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;exception=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;name=fname;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (spec==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab93c13848c6490ae962feec15fbdd151">VhdlSpecifier::PROCESS</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;args=fname;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;name=impure;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ae4bf0d0561d8ef807b56c1f29765713e">VhdlDocGen::deleteAllChars</a>(s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;args,</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fname.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> q1=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a>(fname.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;name : q1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/structs/argument">Argument</a> arg;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">        arg.<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>=name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">        s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;argList.push_back(arg);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">vhdl::parser::VhdlParser::SharedState::current</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">vhdl::parser::VhdlParser::SharedState::currP</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ae4bf0d0561d8ef807b56c1f29765713e">VhdlDocGen::deleteAllChars</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55bace9b6b1321f6162e00ed2ae15192733f">GEN&#95;SEC</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ac942dc2a9f958acddc67e11472d3ca0b">GENERIC</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">Argument::name</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a4f099ecf9b3c15a81b472b8aa7500f81">vhdl::parser::VhdlParser::SharedState::parse&#95;sec</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">PROCEDURE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab93c13848c6490ae962feec15fbdd151">PROCESS</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac148c3a57e84a2440c4e5aaa894586d9">split</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### error&#95;skipto() {#a251d5cfa601b855d867ca28f7c149644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::error_skipto (int kind)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 63 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 850 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a251d5cfa601b855d867ca28f7c149644">850</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a251d5cfa601b855d867ca28f7c149644">VHDLOutlineParser::error_skipto</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> kind)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdl/parser/token">Token</a> *op;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">do</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;vhdlParser-&gt;getNextToken();  </span><span class="doxyHighlightComment">// step to next token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">    op=<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;vhdlParser-&gt;getToken(1);  </span><span class="doxyHighlightComment">// get first token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (op==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//fprintf(stderr,"\n %s",qPrint(t-&gt;image));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (op-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a021bfae89b9eec39a87db9577508916c">kind</a> != kind);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;vhdlParser-&gt;clearError();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// The above loop consumes tokens all the way up to a token of</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// "kind".  We use a do-while loop rather than a while because the</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// current token is the one immediately before the erroneous token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// (in our case the token immediately before what should have been</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// "if"/"while".</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/vhdl/parser/token/#a021bfae89b9eec39a87db9577508916c">vhdl::parser::Token::kind</a> and <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>.
</div>
</div>

### getLine() {#aefcc1d2dbf645f02721318d6026855a3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VHDLOutlineParser::getLine (int tok)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 45 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 737 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aefcc1d2dbf645f02721318d6026855a3">737</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#afdeb15eb8abda3117c648783e60133fc">VHDLOutlineParser::getLine</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tok)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val=<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;lineParse[tok];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (val&lt;0) val=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//assert(val&gt;=0 &amp;&amp; val&lt;=yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>.
</div>
</div>

### getLine() {#afdeb15eb8abda3117c648783e60133fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VHDLOutlineParser::getLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 46 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 726 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afdeb15eb8abda3117c648783e60133fc">726</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#afdeb15eb8abda3117c648783e60133fc">VHDLOutlineParser::getLine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>.
</div>
</div>

### getNameID() {#ada253943236861987284e1b340603dbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VHDLOutlineParser::getNameID ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>returns a unique id for each record member.</p>


<p>type first_rec is record RE: data_type; end;</p>

<p>type second_rec is record RE: data_type; end;</p>

<p>Declaration at line 68 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 259 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada253943236861987284e1b340603dbd">259</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ada253943236861987284e1b340603dbd">VHDLOutlineParser::getNameID</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(<a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a3d194504e944c7d48d1bb8d8223e506e">idCounter</a>++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a3d194504e944c7d48d1bb8d8223e506e">idCounter</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a>.
</div>
</div>

### handleCommentBlock() {#a3df5816f7dcd092e39a99ebaf9b983cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::handleCommentBlock (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; doc, bool brief)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 53 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 387 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3df5816f7dcd092e39a99ebaf9b983cf">387</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3df5816f7dcd092e39a99ebaf9b983cf">VHDLOutlineParser::handleCommentBlock</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc1, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> brief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> position = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> needsEntry = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> *s = &amp;<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;shared;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> doc = doc1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab3687656c1045cb4c1c5177bbab2c83e">checkMultiComment</a>(doc, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;strComment.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a18ea453a7fdcb15b665135112de6ff06">checkInlineCode</a>(doc) &gt; 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> protection = Protection::Public;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>(doc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (doc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;oldEntry == s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>.get())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;str_doc.doc = doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;str_doc.iDocLine = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;iDocLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;str_doc.brief = brief;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;str_doc.pending = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;oldEntry = s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (brief)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;briefLine = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;docLine = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/markdown">Markdown</a> markdown(<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyFileName,<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;iDocLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;iDocLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/commentscan-h/#abae3f4527720c3a0368e313ea4a5e575">GuardedSectionStack</a> guards;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> processedDoc = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT) ? markdown.<a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">process</a>(doc,lineNr) : doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;commentScanner.parseCommentBlock(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;thisParser,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">      s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>.get(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">      processedDoc,  </span><span class="doxyHighlightComment">// text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyFileName, </span><span class="doxyHighlightComment">// file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">      lineNr,       </span><span class="doxyHighlightComment">// line of block start</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">      brief,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">      0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">      protection,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">      position,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">      needsEntry,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">      &amp;guards</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">    ))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needsEntry)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a8e2731ccb031a7e2914e7583cc7bdff9">newEntry</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needsEntry)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;varr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;varr = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">      s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;name = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;varName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">      s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;section = EntryType::makeVariableDoc();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;varName = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8e2731ccb031a7e2914e7583cc7bdff9">newEntry</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;iDocLine = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;strComment.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a18ea453a7fdcb15b665135112de6ff06">checkInlineCode</a>, <a href="#ab3687656c1045cb4c1c5177bbab2c83e">checkMultiComment</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">vhdl::parser::VhdlParser::SharedState::current</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a8e2731ccb031a7e2914e7583cc7bdff9">newEntry</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a9ecb445c39b769e5602ca96de2e93323">initEntry</a> and <a href="#a7910d0ac9f615f9ce451bd0c71d15da6">oneLineComment</a>.
</div>
</div>

### handleFlowComment() {#ad52018c3c0f56dc9cfdfad34b45fae26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::handleFlowComment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; doc)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 54 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 264 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad52018c3c0f56dc9cfdfad34b45fae26">264</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad52018c3c0f56dc9cfdfad34b45fae26">VHDLOutlineParser::handleFlowComment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;doc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6cf53b5cdea9c828c4b676c80d69860d">lineCount</a>(doc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/vhdldocgen/#a12b2126cfa1cf80aeab17ae40d673d67">VhdlDocGen::getFlowMember</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qcs(doc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">    qcs=qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">    qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">stripPrefix</a>(</span><span class="doxyHighlightStringLiteral">"--#"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/flowchart/#a5e2d1232239471126aade777574d9d34">FlowChart::addFlowChart</a>(<a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca4ba88b16997134fe34ee6632fc1eb059">FlowChart::COMMENT_NO</a>,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),qcs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/flowchart/#a5e2d1232239471126aade777574d9d34">FlowChart::addFlowChart</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#acd787d5c3faa541b938e0d58c800572ca4ba88b16997134fe34ee6632fc1eb059">FlowChart::COMMENT&#95;NO</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a12b2126cfa1cf80aeab17ae40d673d67">VhdlDocGen::getFlowMember</a>, <a href="#a6cf53b5cdea9c828c4b676c80d69860d">lineCount</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.
</div>
</div>

### initEntry() {#a9ecb445c39b769e5602ca96de2e93323}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::initEntry (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * e)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 55 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 199 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ecb445c39b769e5602ca96de2e93323">199</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9ecb445c39b769e5602ca96de2e93323">VHDLOutlineParser::initEntry</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *e)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">fileName</a> = <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyFileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a4ee5bbd6ac8bdf2f017d93edcefce5e9">lang</a>     = SrcLangExt::VHDL;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;str_doc.pending)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;str_doc.pending=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;oldEntry=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// prevents endless recursion</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;iDocLine=<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;str_doc.iDocLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3df5816f7dcd092e39a99ebaf9b983cf">handleCommentBlock</a>(<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;str_doc.doc,<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;str_doc.brief);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;iDocLine=-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;commentScanner.initGroupInfo(e);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/entry/#a736f1dfadfe0c0fabb022c533aa27fdc">Entry::fileName</a>, <a href="#a3df5816f7dcd092e39a99ebaf9b983cf">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/entry/#a4ee5bbd6ac8bdf2f017d93edcefce5e9">Entry::lang</a> and <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>.

Referenced by <a href="#ab277b2256102ea5cba0023d0ccdeca3b">addCompInst</a>, <a href="#a8e2731ccb031a7e2914e7583cc7bdff9">newEntry</a> and <a href="#ad6df9d0420902e8579fb9dbbfa5c1a90">parseInput</a>.
</div>
</div>

### insertEntryAtLine() {#a745036e883331351a306bae43e27c1a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::insertEntryAtLine (std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; ce, int line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 67 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 832 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a745036e883331351a306bae43e27c1a4">832</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a745036e883331351a306bae43e27c1a4">VHDLOutlineParser::insertEntryAtLine</a>(std::shared_ptr&lt;Entry&gt; ce,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;rt : ce-&gt;children())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rt-&gt;bodyLine==line)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;lineEntry.push_back(rt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a745036e883331351a306bae43e27c1a4">insertEntryAtLine</a>(rt,line);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a745036e883331351a306bae43e27c1a4">insertEntryAtLine</a> and <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>.

Referenced by <a href="#ab3687656c1045cb4c1c5177bbab2c83e">checkMultiComment</a> and <a href="#a745036e883331351a306bae43e27c1a4">insertEntryAtLine</a>.
</div>
</div>

### isFuncProcProced() {#aabc6c0e6b285c280ffa531cace06e2e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VHDLOutlineParser::isFuncProcProced ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 605 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aabc6c0e6b285c280ffa531cace06e2e4">605</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aabc6c0e6b285c280ffa531cace06e2e4">VHDLOutlineParser::isFuncProcProced</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> *s = &amp;<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;shared;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">currP</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">VhdlSpecifier::FUNCTION</a>  ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">      s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">currP</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">VhdlSpecifier::PROCEDURE</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">      s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">currP</a>==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab93c13848c6490ae962feec15fbdd151">VhdlSpecifier::PROCESS</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a978c447b532b5282ce4a6deceb5fc4e3">vhdl::parser::VhdlParser::SharedState::currP</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6a72a6a776662a244f82d31e9274a07b">FUNCTION</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a6c4d52355c694ee12dcd648562757f52">PROCEDURE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ab93c13848c6490ae962feec15fbdd151">PROCESS</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a591d0ef44da80f3a2f87515755126295">addVhdlType</a>.
</div>
</div>

### lineCount() {#aa00031a2d8766a111e037878b9b2f3ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::lineCount (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 47 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 188 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa00031a2d8766a111e037878b9b2f3ca">188</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6cf53b5cdea9c828c4b676c80d69860d">VHDLOutlineParser::lineCount</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!text.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* c=text.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>() ; *c ; ++c )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*c == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>.
</div>
</div>

### lineCount() {#a6cf53b5cdea9c828c4b676c80d69860d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::lineCount ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 48 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 183 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6cf53b5cdea9c828c4b676c80d69860d">183</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6cf53b5cdea9c828c4b676c80d69860d">VHDLOutlineParser::lineCount</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>.

Referenced by <a href="#ad52018c3c0f56dc9cfdfad34b45fae26">handleFlowComment</a>.
</div>
</div>

### mapLibPackage() {#afd4e9dc2db18f93819d8fbddf554efa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::mapLibPackage (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * root)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 61 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 687 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afd4e9dc2db18f93819d8fbddf554efa4">687</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afd4e9dc2db18f93819d8fbddf554efa4">VHDLOutlineParser::mapLibPackage</a>( <a href="/web-doxygen/docs/api/classes/entry">Entry</a>* root)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;rt : <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;libUse)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aae48ed44191778c99e285f17b7e14377">addLibUseClause</a>(rt-&gt;name))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bFound=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;current : root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a13c49362ea71812935f0399e0f7dcf77">children</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/vhdldocgen/#a7b7df19eb23b1532bc1d05c7ffe6cd76">VhdlDocGen::isVhdlClass</a>(current.get()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (current-&gt;startLine &gt; rt-&gt;startLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">            bFound=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">            current-&gt;copyToSubEntry(rt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span><span class="doxyHighlightComment">//for</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!bFound)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">        root-&gt;<a href="/web-doxygen/docs/api/classes/entry/#aa24b2fca5bb06b62af4f8efdd68ebf25">copyToSubEntry</a>(rt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">    } </span><span class="doxyHighlightComment">//if</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span><span class="doxyHighlightComment">// for</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">}</span><span class="doxyHighlightComment">//MapLib</span></span></div>

</div>


References <a href="#aae48ed44191778c99e285f17b7e14377">addLibUseClause</a>, <a href="/web-doxygen/docs/api/classes/entry/#a13c49362ea71812935f0399e0f7dcf77">Entry::children</a>, <a href="/web-doxygen/docs/api/classes/entry/#aa24b2fca5bb06b62af4f8efdd68ebf25">Entry::copyToSubEntry</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a7b7df19eb23b1532bc1d05c7ffe6cd76">VhdlDocGen::isVhdlClass</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#ad6df9d0420902e8579fb9dbbfa5c1a90">parseInput</a>.
</div>
</div>

### needsPreprocessing() {#a3c2c07d943edd6653badbcb7522b8142}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VHDLOutlineParser::needsPreprocessing (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
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
<p>Returns TRUE if the language identified by <em>extension</em> needs the C preprocessor to be run before feed the result to the input parser.</p>


<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
<p><a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput()</a></p>
</dd>
</dl>


<p>Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c2c07d943edd6653badbcb7522b8142">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3c2c07d943edd6653badbcb7522b8142">needsPreprocessing</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### newEntry() {#a8e2731ccb031a7e2914e7583cc7bdff9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::newEntry ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 56 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 214 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e2731ccb031a7e2914e7583cc7bdff9">214</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8e2731ccb031a7e2914e7583cc7bdff9">VHDLOutlineParser::newEntry</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> *s = &amp;<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;shared;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;previous = s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;vhdlSpec==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a5427d771a8a2cf2dcd1825f9453da92e">VhdlSpecifier::ENTITY</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">      s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;vhdlSpec==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ae83af69d4844921d55507863e9099eb2">VhdlSpecifier::PACKAGE</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">      s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;vhdlSpec==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a29330223e96b4290e236a247aec153fd">VhdlSpecifier::ARCHITECTURE</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>-&gt;vhdlSpec==<a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a47926792add35e040deb8533855d8135">VhdlSpecifier::PACKAGE_BODY</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">    s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1943eaf985ae6ae0a3316b65f2810ac1">current_root</a>-&gt;moveToSubEntryAndRefresh(s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">      s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a>-&gt;moveToSubEntryAndRefresh(s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a04773fa91cfdf6d65710f84b2c35417f">lastEntity</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">        s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a04773fa91cfdf6d65710f84b2c35417f">lastEntity</a>-&gt;moveToSubEntryAndRefresh(s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">        s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1943eaf985ae6ae0a3316b65f2810ac1">current_root</a>-&gt;moveToSubEntryAndRefresh(s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9ecb445c39b769e5602ca96de2e93323">initEntry</a>(s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a29330223e96b4290e236a247aec153fd">ARCHITECTURE</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">vhdl::parser::VhdlParser::SharedState::current</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1943eaf985ae6ae0a3316b65f2810ac1">vhdl::parser::VhdlParser::SharedState::current&#95;root</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a5427d771a8a2cf2dcd1825f9453da92e">ENTITY</a>, <a href="#a9ecb445c39b769e5602ca96de2e93323">initEntry</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">vhdl::parser::VhdlParser::SharedState::lastCompound</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a04773fa91cfdf6d65710f84b2c35417f">vhdl::parser::VhdlParser::SharedState::lastEntity</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91ae83af69d4844921d55507863e9099eb2">PACKAGE</a> and <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a47926792add35e040deb8533855d8135">PACKAGE&#95;BODY</a>.

Referenced by <a href="#ab277b2256102ea5cba0023d0ccdeca3b">addCompInst</a>, <a href="#a591d0ef44da80f3a2f87515755126295">addVhdlType</a> and <a href="#a3df5816f7dcd092e39a99ebaf9b983cf">handleCommentBlock</a>.
</div>
</div>

### oneLineComment() {#a7910d0ac9f615f9ce451bd0c71d15da6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::oneLineComment (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qcs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 64 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 801 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7910d0ac9f615f9ce451bd0c71d15da6">801</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7910d0ac9f615f9ce451bd0c71d15da6">VHDLOutlineParser::oneLineComment</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> qcs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> j=qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"--!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">    qcs=qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(qcs.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-3-j);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ab3687656c1045cb4c1c5177bbab2c83e">checkMultiComment</a>(qcs,<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;iDocLine))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a3df5816f7dcd092e39a99ebaf9b983cf">handleCommentBlock</a>(qcs,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ab3687656c1045cb4c1c5177bbab2c83e">checkMultiComment</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="#a3df5816f7dcd092e39a99ebaf9b983cf">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### parseInput() {#ad6df9d0420902e8579fb9dbbfa5c1a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::parseInput (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const char * fileBuf, const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> * clangParser)</td>
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
<p>Parses a single input file with the goal to build an <a href="/web-doxygen/docs/api/classes/entry">Entry</a> tree.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileName</td>
<td class="doxyParamItemDescription"><p>The full name of the file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] fileBuf</td>
<td class="doxyParamItemDescription"><p>The contents of the file (zero terminated).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[inout] root</td>
<td class="doxyParamItemDescription"><p>The root of the tree of <a href="/web-doxygen/docs/api/classes/entry">Entry</a> *nodes representing the information extracted from the file.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] clangParser</td>
<td class="doxyParamItemDescription"><p>The clang translation unit parser object or nullptr if disabled.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6df9d0420902e8579fb9dbbfa5c1a90">132</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad6df9d0420902e8579fb9dbbfa5c1a90">VHDLOutlineParser::parseInput</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileBuf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;root, <a href="/web-doxygen/docs/api/classes/clangtuparser">ClangTUParser</a> *)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> *s = &amp;<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;shared;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;thisParser=</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;inputString=fileBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// fprintf(stderr,"\n ============= %s\n ==========\n",fileBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inLine = fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inLine) <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Parsing file {}...\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyFileName=fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> xilinx_ucf=<a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a710af507a150913251c3885189b77fb8">isConstraintFile</a>(<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyFileName,</span><span class="doxyHighlightStringLiteral">".ucf"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> altera_qsf=<a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a710af507a150913251c3885189b77fb8">isConstraintFile</a>(<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyFileName,</span><span class="doxyHighlightStringLiteral">".qsf"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// support XILINX(ucf) and ALTERA (qsf) file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (xilinx_ucf)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>(fileBuf,root.get(),<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyFileName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (altera_qsf)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a>(fileBuf,root.get(),<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyFileName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1943eaf985ae6ae0a3316b65f2810ac1">current_root</a>=root;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a>=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a04773fa91cfdf6d65710f84b2c35417f">lastEntity</a>=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;oldEntry = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>=std::make_shared&lt;Entry&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9ecb445c39b769e5602ca96de2e93323">initEntry</a>(s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;commentScanner.enterFile(fileName,<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;lineParse.reserve(200);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;parseVhdlfile(fileName,fileBuf,inLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;commentScanner.leaveFile(fileName,<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">  s-&gt;<a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">current</a>.reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afd4e9dc2db18f93819d8fbddf554efa4">mapLibPackage</a>(root.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyFileName.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;libUse.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a979f96c7f7352e14296f8d49e701ee47">vhdl::parser::VhdlParser::SharedState::current</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1943eaf985ae6ae0a3316b65f2810ac1">vhdl::parser::VhdlParser::SharedState::current&#95;root</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a9ecb445c39b769e5602ca96de2e93323">initEntry</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a710af507a150913251c3885189b77fb8">isConstraintFile</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a1429ecf0ba26773a2dbdb521c3268644">vhdl::parser::VhdlParser::SharedState::lastCompound</a>, <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate/#a04773fa91cfdf6d65710f84b2c35417f">vhdl::parser::VhdlParser::SharedState::lastEntity</a>, <a href="#afd4e9dc2db18f93819d8fbddf554efa4">mapLibPackage</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac5a78fda163916d84fc8067d577f9bf3">VhdlDocGen::parseUCF</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### parsePrototype() {#ac1fa467bd9ba716dc3c2fd34d7ab504e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::parsePrototype (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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
<p>Callback function called by the comment block scanner.</p>


<p>It provides a string <em>text</em> containing the prototype of a function or variable. The parser should parse this and store the information in the <a href="/web-doxygen/docs/api/classes/entry">Entry</a> node that corresponds with the node for which the comment block parser was invoked.</p>

<p>Declaration at line 39 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 473 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac1fa467bd9ba716dc3c2fd34d7ab504e">473</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac1fa467bd9ba716dc3c2fd34d7ab504e">VHDLOutlineParser::parsePrototype</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;varName=text;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;varr=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### popLabel() {#aa32a03da6438377d962da12f57b0f2c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VHDLOutlineParser::popLabel (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; q)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 59 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 624 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa32a03da6438377d962da12f57b0f2c0">624</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aa32a03da6438377d962da12f57b0f2c0">VHDLOutlineParser::popLabel</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; q)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=q.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">"|"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">  q = q.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> q;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>.
</div>
</div>

### pushLabel() {#aa6252fa90e33ae2f5a1a58b1ccf2c2f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::pushLabel (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; label, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 58 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 618 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa6252fa90e33ae2f5a1a58b1ccf2c2f5">618</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa6252fa90e33ae2f5a1a58b1ccf2c2f5">VHDLOutlineParser::pushLabel</a>( <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;label,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; val)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">  label+=</span><span class="doxyHighlightStringLiteral">"|"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">  label+=val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### setLineParsed() {#a4766c5dbf7960f4fa83455c58853bce6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::setLineParsed (int tok)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 731 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4766c5dbf7960f4fa83455c58853bce6">731</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4766c5dbf7960f4fa83455c58853bce6">VHDLOutlineParser::setLineParsed</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tok)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;lineParse.size()&lt;=tok) <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;lineParse.resize(tok+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;lineParse[tok]=<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>.
</div>
</div>

### setMultCommentLine() {#af2256dfdfdf6a1d9be93a881cd4eb526}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::setMultCommentLine ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 65 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line 796 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af2256dfdfdf6a1d9be93a881cd4eb526">796</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af2256dfdfdf6a1d9be93a881cd4eb526">VHDLOutlineParser::setMultCommentLine</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;iDocLine=<a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>-&gt;yyLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a56aca27d40e4179f6c55664f4d9c9c0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; VHDLOutlineParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a56aca27d40e4179f6c55664f4d9c9c0a">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a56aca27d40e4179f6c55664f4d9c9c0a">p</a>;</span></span></div>

</div>


Referenced by <a href="#ab277b2256102ea5cba0023d0ccdeca3b">addCompInst</a>, <a href="#af2d13dc3387c6e7495a02620cd1c1efe">addProto</a>, <a href="#a591d0ef44da80f3a2f87515755126295">addVhdlType</a>, <a href="#a18ea453a7fdcb15b665135112de6ff06">checkInlineCode</a>, <a href="#ab3687656c1045cb4c1c5177bbab2c83e">checkMultiComment</a>, <a href="#ab36fc7f90b85f9a369604444f3a6e203">createFlow</a>, <a href="#ae05c8d947347501c75f04b3b3cae49ab">createFunction</a>, <a href="#a251d5cfa601b855d867ca28f7c149644">error&#95;skipto</a>, <a href="#afdeb15eb8abda3117c648783e60133fc">getLine</a>, <a href="#aefcc1d2dbf645f02721318d6026855a3">getLine</a>, <a href="#a3df5816f7dcd092e39a99ebaf9b983cf">handleCommentBlock</a>, <a href="#a9ecb445c39b769e5602ca96de2e93323">initEntry</a>, <a href="#a745036e883331351a306bae43e27c1a4">insertEntryAtLine</a>, <a href="#aabc6c0e6b285c280ffa531cace06e2e4">isFuncProcProced</a>, <a href="#a6cf53b5cdea9c828c4b676c80d69860d">lineCount</a>, <a href="#aa00031a2d8766a111e037878b9b2f3ca">lineCount</a>, <a href="#afd4e9dc2db18f93819d8fbddf554efa4">mapLibPackage</a>, <a href="#a8e2731ccb031a7e2914e7583cc7bdff9">newEntry</a>, <a href="#a7910d0ac9f615f9ce451bd0c71d15da6">oneLineComment</a>, <a href="#ad6df9d0420902e8579fb9dbbfa5c1a90">parseInput</a>, <a href="#ac1fa467bd9ba716dc3c2fd34d7ab504e">parsePrototype</a>, <a href="#a4766c5dbf7960f4fa83455c58853bce6">setLineParsed</a>, <a href="#af2256dfdfdf6a1d9be93a881cd4eb526">setMultCommentLine</a> and <a href="#afed30c38099a7370ae59ee670b7dc5e4">VHDLOutlineParser</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
