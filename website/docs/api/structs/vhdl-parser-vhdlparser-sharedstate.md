---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/vhdl/parser/vhdlparser/sharedstate
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - struct

---

<div class="doxyPage">

# The `SharedState` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct vhdl::parser::VhdlParser::SharedState { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">vhdlparser/VhdlParser.h</a>&gt;
</div>

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1943eaf985ae6ae0a3316b65f2810ac1">current_root</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c8599a22b37b4e528d5372f2c1ab164">tempEntry</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04773fa91cfdf6d65710f84b2c35417f">lastEntity</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a979f96c7f7352e14296f8d49e701ee47">current</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a739073e1207b9a9ad60a522bd26a9c29">compSpec</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ca1d159da9a4714fc811a3814a04679">currName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2c9cc29b31675daf5873a3c6199f6b7">levelCounter</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b837e4d9a5e4725ce7524242bc2b764">confName</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae651ad17ada9d06a6b17096dacdda8b2">genLabels</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6500c692c2c77da416d6edc943bf324e">lab</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55b">VhdlSection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6603dae57b0613b5d703220ea1154e6c">param_sec</a> = <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55ba696b031073e74bf2cb98e5ef201d4aa3">VhdlSection::UNKNOWN</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55b">VhdlSection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f099ecf9b3c15a81b472b8aa7500f81">parse_sec</a> = <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55ba696b031073e74bf2cb98e5ef201d4aa3">VhdlSection::UNKNOWN</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a978c447b532b5282ce4a6deceb5fc4e3">currP</a> = <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a696b031073e74bf2cb98e5ef201d4aa3">VhdlSpecifier::UNKNOWN</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e5f659c61c3fcb81cde348ad841f316">interf_sec</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afbb5e953c66b487e7455e9c89fde0398">generic_sec</a></td>
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


<p>Definition at line 11174 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxySectionDef">

## Public Member Attributes

### compSpec {#a739073e1207b9a9ad60a522bd26a9c29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString vhdl::parser::VhdlParser::SharedState::compSpec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11181 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a739073e1207b9a9ad60a522bd26a9c29">11181</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a739073e1207b9a9ad60a522bd26a9c29">compSpec</a>;</span></span></div>

</div>

</div>
</div>

### confName {#a5b837e4d9a5e4725ce7524242bc2b764}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString vhdl::parser::VhdlParser::SharedState::confName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11184 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b837e4d9a5e4725ce7524242bc2b764">11184</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a5b837e4d9a5e4725ce7524242bc2b764">confName</a>;</span></span></div>

</div>

</div>
</div>

### current {#a979f96c7f7352e14296f8d49e701ee47}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;Entry&gt; vhdl::parser::VhdlParser::SharedState::current</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11180 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a979f96c7f7352e14296f8d49e701ee47">11180</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; <a href="#a979f96c7f7352e14296f8d49e701ee47">current</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab277b2256102ea5cba0023d0ccdeca3b">VHDLOutlineParser::addCompInst</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#af2d13dc3387c6e7495a02620cd1c1efe">VHDLOutlineParser::addProto</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a591d0ef44da80f3a2f87515755126295">VHDLOutlineParser::addVhdlType</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ae05c8d947347501c75f04b3b3cae49ab">VHDLOutlineParser::createFunction</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a3df5816f7dcd092e39a99ebaf9b983cf">VHDLOutlineParser::handleCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a8e2731ccb031a7e2914e7583cc7bdff9">VHDLOutlineParser::newEntry</a> and <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ad6df9d0420902e8579fb9dbbfa5c1a90">VHDLOutlineParser::parseInput</a>.</p>

</div>
</div>

### current\_root {#a1943eaf985ae6ae0a3316b65f2810ac1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;Entry&gt; vhdl::parser::VhdlParser::SharedState::current_root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11176 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1943eaf985ae6ae0a3316b65f2810ac1">11176</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; <a href="#a1943eaf985ae6ae0a3316b65f2810ac1">current_root</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab3687656c1045cb4c1c5177bbab2c83e">VHDLOutlineParser::checkMultiComment</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a8e2731ccb031a7e2914e7583cc7bdff9">VHDLOutlineParser::newEntry</a> and <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ad6df9d0420902e8579fb9dbbfa5c1a90">VHDLOutlineParser::parseInput</a>.</p>

</div>
</div>

### currName {#a6ca1d159da9a4714fc811a3814a04679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString vhdl::parser::VhdlParser::SharedState::currName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11182 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ca1d159da9a4714fc811a3814a04679">11182</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6ca1d159da9a4714fc811a3814a04679">currName</a>;</span></span></div>

</div>

</div>
</div>

### currP {#a978c447b532b5282ce4a6deceb5fc4e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlSpecifier vhdl::parser::VhdlParser::SharedState::currP = <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a696b031073e74bf2cb98e5ef201d4aa3">VhdlSpecifier::UNKNOWN</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11189 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a978c447b532b5282ce4a6deceb5fc4e3">11189</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91">VhdlSpecifier</a> <a href="#a978c447b532b5282ce4a6deceb5fc4e3">currP</a> = <a href="/web-doxygen/docs/api/files/src/types-h/#abfcc3de81e21aaab7b108c10eec8cc91a696b031073e74bf2cb98e5ef201d4aa3">VhdlSpecifier::UNKNOWN</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab36fc7f90b85f9a369604444f3a6e203">VHDLOutlineParser::createFlow</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ae05c8d947347501c75f04b3b3cae49ab">VHDLOutlineParser::createFunction</a> and <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#aabc6c0e6b285c280ffa531cace06e2e4">VHDLOutlineParser::isFuncProcProced</a>.</p>

</div>
</div>

### generic\_sec {#afbb5e953c66b487e7455e9c89fde0398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool vhdl::parser::VhdlParser::SharedState::generic_sec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11191 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afbb5e953c66b487e7455e9c89fde0398">11191</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#afbb5e953c66b487e7455e9c89fde0398">generic_sec</a>;</span></span></div>

</div>

</div>
</div>

### genLabels {#ae651ad17ada9d06a6b17096dacdda8b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString vhdl::parser::VhdlParser::SharedState::genLabels</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11185 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae651ad17ada9d06a6b17096dacdda8b2">11185</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae651ad17ada9d06a6b17096dacdda8b2">genLabels</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab277b2256102ea5cba0023d0ccdeca3b">VHDLOutlineParser::addCompInst</a>.</p>

</div>
</div>

### interf\_sec {#a4e5f659c61c3fcb81cde348ad841f316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool vhdl::parser::VhdlParser::SharedState::interf_sec</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11190 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e5f659c61c3fcb81cde348ad841f316">11190</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4e5f659c61c3fcb81cde348ad841f316">interf_sec</a>;</span></span></div>

</div>

</div>
</div>

### lab {#a6500c692c2c77da416d6edc943bf324e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString vhdl::parser::VhdlParser::SharedState::lab</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11186 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6500c692c2c77da416d6edc943bf324e">11186</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6500c692c2c77da416d6edc943bf324e">lab</a>;</span></span></div>

</div>

</div>
</div>

### lastCompound {#a1429ecf0ba26773a2dbdb521c3268644}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;Entry&gt; vhdl::parser::VhdlParser::SharedState::lastCompound</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11179 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1429ecf0ba26773a2dbdb521c3268644">11179</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; <a href="#a1429ecf0ba26773a2dbdb521c3268644">lastCompound</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab277b2256102ea5cba0023d0ccdeca3b">VHDLOutlineParser::addCompInst</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a591d0ef44da80f3a2f87515755126295">VHDLOutlineParser::addVhdlType</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a8e2731ccb031a7e2914e7583cc7bdff9">VHDLOutlineParser::newEntry</a> and <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ad6df9d0420902e8579fb9dbbfa5c1a90">VHDLOutlineParser::parseInput</a>.</p>

</div>
</div>

### lastEntity {#a04773fa91cfdf6d65710f84b2c35417f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;Entry&gt; vhdl::parser::VhdlParser::SharedState::lastEntity</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11178 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a04773fa91cfdf6d65710f84b2c35417f">11178</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; <a href="#a04773fa91cfdf6d65710f84b2c35417f">lastEntity</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a18ea453a7fdcb15b665135112de6ff06">VHDLOutlineParser::checkInlineCode</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a8e2731ccb031a7e2914e7583cc7bdff9">VHDLOutlineParser::newEntry</a> and <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ad6df9d0420902e8579fb9dbbfa5c1a90">VHDLOutlineParser::parseInput</a>.</p>

</div>
</div>

### levelCounter {#af2c9cc29b31675daf5873a3c6199f6b7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int vhdl::parser::VhdlParser::SharedState::levelCounter = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11183 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af2c9cc29b31675daf5873a3c6199f6b7">11183</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#af2c9cc29b31675daf5873a3c6199f6b7">levelCounter</a> = 0;</span></span></div>

</div>

</div>
</div>

### param\_sec {#a6603dae57b0613b5d703220ea1154e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlSection vhdl::parser::VhdlParser::SharedState::param_sec = <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55ba696b031073e74bf2cb98e5ef201d4aa3">VhdlSection::UNKNOWN</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11187 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6603dae57b0613b5d703220ea1154e6c">11187</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55b">VhdlSection</a> <a href="#a6603dae57b0613b5d703220ea1154e6c">param_sec</a> = <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55ba696b031073e74bf2cb98e5ef201d4aa3">VhdlSection::UNKNOWN</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#af2d13dc3387c6e7495a02620cd1c1efe">VHDLOutlineParser::addProto</a>.</p>

</div>
</div>

### parse\_sec {#a4f099ecf9b3c15a81b472b8aa7500f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlSection vhdl::parser::VhdlParser::SharedState::parse_sec = <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55ba696b031073e74bf2cb98e5ef201d4aa3">VhdlSection::UNKNOWN</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11188 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f099ecf9b3c15a81b472b8aa7500f81">11188</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55b">VhdlSection</a> <a href="#a4f099ecf9b3c15a81b472b8aa7500f81">parse_sec</a> = <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h/#a02fbf486f00c210089e02f7153a7e55ba696b031073e74bf2cb98e5ef201d4aa3">VhdlSection::UNKNOWN</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#af2d13dc3387c6e7495a02620cd1c1efe">VHDLOutlineParser::addProto</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a591d0ef44da80f3a2f87515755126295">VHDLOutlineParser::addVhdlType</a> and <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ae05c8d947347501c75f04b3b3cae49ab">VHDLOutlineParser::createFunction</a>.</p>

</div>
</div>

### tempEntry {#a7c8599a22b37b4e528d5372f2c1ab164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::shared_ptr&lt;Entry&gt; vhdl::parser::VhdlParser::SharedState::tempEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 11177 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c8599a22b37b4e528d5372f2c1ab164">11177</a></span><span class="doxyLineContent"><span class="doxyHighlight">  std::shared_ptr&lt;Entry&gt; <a href="#a7c8599a22b37b4e528d5372f2c1ab164">tempEntry</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ab36fc7f90b85f9a369604444f3a6e203">VHDLOutlineParser::createFlow</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/vhdlparser/vhdlparser-h">VhdlParser.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
