---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/perlmodgenerator
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `PerlModGenerator` Class Reference



## Declaration

<div class="doxyDeclaration">
class PerlModGenerator { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7473195622dcb57930bbd08c88dd6504">PerlModGenerator</a> (bool pretty)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d2fc28014f00de3422ac4b7a68b868a">generatePerlModForMember</a> (const MemberDef *md, const Definition *)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a> (const Definition *d, const MemberGroupList &amp;mgl)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a> (const Definition *d, MemberList *ml, const QCString &amp;name, const QCString &amp;header=QCString())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81142c12bb2ef7638500997115bf2f43">addListOfAllMembers</a> (const ClassDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b0a42da35d51f4e7f198975258cf9fd">addIncludeInfo</a> (const IncludeInfo *ii)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44b30742275d27dcfe5eb9ea286af80f">generatePerlModForClass</a> (const ClassDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1f8e6fa454368157eb7cdb564ee6a40">generatePerlModForConcept</a> (const ConceptDef *cd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d95b912616cab9e00075658e0fa09d4">generatePerlModForModule</a> (const ModuleDef *mod)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d79f62a76314d0c65cb976809923d80">generatePerlModForNamespace</a> (const NamespaceDef *nd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4d01cc3ff8a727b38849e8efd171be9">generatePerlModForFile</a> (const FileDef *fd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa29eb86a9962f547f8139ff1cfe40b01">generatePerlModForGroup</a> (const GroupDef *gd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0151a88e0794af12a9e7932de2d7a928">generatePerlModForPage</a> (PageDef *pi)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a> (std::ofstream &amp;f, const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed7475d94b3bc527009ebcc50621004">createOutputDir</a> (Dir &amp;perlModDir)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cb28a6f8bf6b9f155d3929b95acf059">generateDoxyLatexTex</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f0a8822b1895daacce85dd3d93eecac">generateDoxyFormatTex</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9893c2c270028114dec964284676adc7">generateDoxyStructurePM</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a999b190603bbc840657ad470a17465ad">generateDoxyLatexPL</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad03aadb67e05b528cd454bed3bee16b9">generateDoxyLatexStructurePL</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a473b6bd63ac2f9ea9fe6de4f8170194b">generateMakefile</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6bb93beb1eac9b861832d368ffad291">generate</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/perlmodoutput">PerlModOutput</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1570f315b84f678d45d80929fe3af533">m_output</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4139ab7ca413fcf7e9d9c10a6abb13f2">pathDoxyStructurePM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b90bb007822613373e9a65ff35643c4">pathDoxyDocsTex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab3220d2f03ba759c948d8be316d4d2c">pathDoxyFormatTex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2ea9cd9b17663a5b3ff62752031fb2b">pathDoxyLatexTex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b29e2e00432a296288342688354b856">pathDoxyLatexDVI</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab3b623c4824006226ea5195aec1d8ef">pathDoxyLatexPDF</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a240a78f6c0326286469e17febcb3e386">pathDoxyStructureTex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32a35dd412f8e42e1f12b671935da576">pathDoxyDocsPM</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a23cafbc784eadd8d96ea498c07ee1b22">pathDoxyLatexPL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dd402f31f1312093ec503a733a5c691">pathDoxyLatexStructurePL</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b043201cbf4b5840582794d44bdcafb">pathDoxyRules</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a2147107f3c1812beb023cb68a10c55">pathMakefile</a></td>
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


<p>Definition at line 1420 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### PerlModGenerator() {#a7473195622dcb57930bbd08c88dd6504}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerlModGenerator::PerlModGenerator (bool pretty)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01439">1439</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7473195622dcb57930bbd08c88dd6504">1439</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="#a7473195622dcb57930bbd08c88dd6504">PerlModGenerator</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> pretty) : <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>(pretty) { }</span></span></div>

</div>


Reference <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addIncludeInfo() {#a7b0a42da35d51f4e7f198975258cf9fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::addIncludeInfo (const <a href="/web-doxygen/docs/api/structs/includeinfo">IncludeInfo</a> * ii)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01446">1446</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b0a42da35d51f4e7f198975258cf9fd">1717</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7b0a42da35d51f4e7f198975258cf9fd">PerlModGenerator::addIncludeInfo</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/includeinfo">IncludeInfo</a> *ii)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1718</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1719</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ii)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1720</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1721</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> nm = ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#a0f8b77f07d748ea1612db5d4c47c5c37">includeName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1722</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nm.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#ac9ea4d136292663b672a8aeec5944548">fileDef</a>) nm = ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#ac9ea4d136292663b672a8aeec5944548">fileDef</a>-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#ad7d5e7ac753d7247cfaad5be9ea3eaec">docName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1723</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!nm.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1724</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1725</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash(</span><span class="doxyHighlightStringLiteral">"includes"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1726</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldBoolean(</span><span class="doxyHighlightStringLiteral">"local"</span><span class="doxyHighlight">, ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#a17debda9cc01be4435a3cafc64061cc6">kind</a>==<a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeKind::IncludeLocal</a> || ii-&gt;<a href="/web-doxygen/docs/api/structs/includeinfo/#a17debda9cc01be4435a3cafc64061cc6">kind</a>==<a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">IncludeKind::ImportLocal</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1727</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, nm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1728</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1729</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1730</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1731</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/filedef/#ad7d5e7ac753d7247cfaad5be9ea3eaec">FileDef::docName</a>, <a href="/web-doxygen/docs/api/structs/includeinfo/#ac9ea4d136292663b672a8aeec5944548">IncludeInfo::fileDef</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a2dbc22c9108714bfd4417e558b7b82e2">ImportLocal</a>, <a href="/web-doxygen/docs/api/files/src/filedef-h/#a52a98ac8d3b93b98e9371611d4b9dcb8a72f604ea2eef74f27164fe740e67847b">IncludeLocal</a>, <a href="/web-doxygen/docs/api/structs/includeinfo/#a0f8b77f07d748ea1612db5d4c47c5c37">IncludeInfo::includeName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/structs/includeinfo/#a17debda9cc01be4435a3cafc64061cc6">IncludeInfo::kind</a> and <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a>.

Referenced by <a href="#a44b30742275d27dcfe5eb9ea286af80f">generatePerlModForClass</a> and <a href="#ac1f8e6fa454368157eb7cdb564ee6a40">generatePerlModForConcept</a>.
</div>
</div>

### addListOfAllMembers() {#a81142c12bb2ef7638500997115bf2f43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::addListOfAllMembers (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01445">1445</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81142c12bb2ef7638500997115bf2f43">1664</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a81142c12bb2ef7638500997115bf2f43">PerlModGenerator::addListOfAllMembers</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1666</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"all_members"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1667</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mni : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ac8f58a78e8196768f3ddd17e645cf7f9">memberNameInfoLinkedMap</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1668</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1669</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mi : *mni)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1670</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1671</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md=mi-&gt;memberDef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1672</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a>  *mcd=md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">getClassDef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1673</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1674</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1675</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1676</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"virtualness"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a3db996b98d5e76eca750e67f99b4e327">getVirtualnessName</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ae450a2be776cc5d05726bab8354f6d62">virtualness</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1677</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"protection"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a85b31a0b9f4657070d51bb5f61e6316e">getProtectionName</a>(mi-&gt;prot()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1678</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1679</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mi-&gt;ambiguityResolutionScope().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1680</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"ambiguity_scope"</span><span class="doxyHighlight">, mi-&gt;ambiguityResolutionScope());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1681</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1682</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"scope"</span><span class="doxyHighlight">, mcd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1683</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1684</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1685</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1686</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1687</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/memberdef/#a33ff70edee6691aacaeecf40a1146995">MemberDef::getClassDef</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a85b31a0b9f4657070d51bb5f61e6316e">getProtectionName</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a3db996b98d5e76eca750e67f99b4e327">getVirtualnessName</a>, <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ac8f58a78e8196768f3ddd17e645cf7f9">ClassDef::memberNameInfoLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="/web-doxygen/docs/api/classes/memberdef/#ae450a2be776cc5d05726bab8354f6d62">MemberDef::virtualness</a>.

Referenced by <a href="#a44b30742275d27dcfe5eb9ea286af80f">generatePerlModForClass</a>.
</div>
</div>

### createOutputDir() {#a2ed7475d94b3bc527009ebcc50621004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PerlModGenerator::createOutputDir (<a href="/web-doxygen/docs/api/classes/dir">Dir</a> &amp; perlModDir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01456">1456</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ed7475d94b3bc527009ebcc50621004">2246</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2ed7475d94b3bc527009ebcc50621004">PerlModGenerator::createOutputDir</a>(<a href="/web-doxygen/docs/api/classes/dir">Dir</a> &amp;perlModDir)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2247</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2248</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string outputDirectory = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(OUTPUT_DIRECTORY).str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2249</span><span class="doxyLineContent"><span class="doxyHighlight">  perlModDir.<a href="/web-doxygen/docs/api/classes/dir/#a2bb647584a701cb526874a8c0cd68c13">setPath</a>(outputDirectory+</span><span class="doxyHighlightStringLiteral">"/perlmod"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2250</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!perlModDir.<a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">exists</a>() &amp;&amp; !perlModDir.<a href="/web-doxygen/docs/api/classes/dir/#a286f4b1852b489ffcc8b6837c7e6bd8e">mkdir</a>(outputDirectory+</span><span class="doxyHighlightStringLiteral">"/perlmod"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2251</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2252</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Could not create perlmod directory in {}\n"</span><span class="doxyHighlight">,outputDirectory);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2253</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2254</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2255</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2256</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">Dir::exists</a>, <a href="/web-doxygen/docs/api/classes/dir/#a286f4b1852b489ffcc8b6837c7e6bd8e">Dir::mkdir</a> and <a href="/web-doxygen/docs/api/classes/dir/#a2bb647584a701cb526874a8c0cd68c13">Dir::setPath</a>.

Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>.
</div>
</div>

### createOutputFile() {#ac12f2a17915bb4023585afb081f7f39a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PerlModGenerator::createOutputFile (std::ofstream &amp; f, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01455">1455</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac12f2a17915bb4023585afb081f7f39a">2235</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac12f2a17915bb4023585afb081f7f39a">PerlModGenerator::createOutputFile</a>(std::ofstream &amp;f, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2236</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2237</span><span class="doxyLineContent"><span class="doxyHighlight">  f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2238</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2239</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2240</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Cannot open file {} for writing!\n"</span><span class="doxyHighlight">, s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2241</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2242</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2243</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2244</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a> and <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>.

Referenced by <a href="#a1f0a8822b1895daacce85dd3d93eecac">generateDoxyFormatTex</a>, <a href="#a999b190603bbc840657ad470a17465ad">generateDoxyLatexPL</a>, <a href="#ad03aadb67e05b528cd454bed3bee16b9">generateDoxyLatexStructurePL</a>, <a href="#a2cb28a6f8bf6b9f155d3929b95acf059">generateDoxyLatexTex</a>, <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a>, <a href="#a9893c2c270028114dec964284676adc7">generateDoxyStructurePM</a>, <a href="#a473b6bd63ac2f9ea9fe6de4f8170194b">generateMakefile</a> and <a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>.
</div>
</div>

### generate() {#af6bb93beb1eac9b861832d368ffad291}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::generate ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01466">1466</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6bb93beb1eac9b861832d368ffad291">2905</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af6bb93beb1eac9b861832d368ffad291">PerlModGenerator::generate</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2906</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2907</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2908</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + namespaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2909</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2910</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - packages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2911</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2912</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + related pages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2913</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - examples</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2914</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2915</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> perlModDir;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2916</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a2ed7475d94b3bc527009ebcc50621004">createOutputDir</a>(perlModDir))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2917</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2918</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2919</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> perlmodLatex = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PERLMOD_LATEX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2920</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2921</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> perlModAbsPath = perlModDir.<a href="/web-doxygen/docs/api/classes/dir/#a226b0db1117e46393bbb241e545f8609">absPath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2922</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a32a35dd412f8e42e1f12b671935da576">pathDoxyDocsPM</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/DoxyDocs.pm"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2923</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4139ab7ca413fcf7e9d9c10a6abb13f2">pathDoxyStructurePM</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/DoxyStructure.pm"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2924</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2a2147107f3c1812beb023cb68a10c55">pathMakefile</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/Makefile"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2925</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a5b043201cbf4b5840582794d44bdcafb">pathDoxyRules</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/doxyrules.make"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2926</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2927</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (perlmodLatex) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2928</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a240a78f6c0326286469e17febcb3e386">pathDoxyStructureTex</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/doxystructure.tex"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2929</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab3220d2f03ba759c948d8be316d4d2c">pathDoxyFormatTex</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/doxyformat.tex"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2930</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad2ea9cd9b17663a5b3ff62752031fb2b">pathDoxyLatexTex</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/doxylatex.tex"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2931</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4b29e2e00432a296288342688354b856">pathDoxyLatexDVI</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/doxylatex.dvi"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2932</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aab3b623c4824006226ea5195aec1d8ef">pathDoxyLatexPDF</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/doxylatex.pdf"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2933</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6b90bb007822613373e9a65ff35643c4">pathDoxyDocsTex</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/doxydocs.tex"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2934</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a23cafbc784eadd8d96ea498c07ee1b22">pathDoxyLatexPL</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/doxylatex.pl"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2935</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8dd402f31f1312093ec503a733a5c691">pathDoxyLatexStructurePL</a> = perlModAbsPath + </span><span class="doxyHighlightStringLiteral">"/doxylatex-structure.pl"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2936</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2937</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2938</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!(<a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2939</span><span class="doxyLineContent"><span class="doxyHighlight">        &amp;&amp; <a href="#a9893c2c270028114dec964284676adc7">generateDoxyStructurePM</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2940</span><span class="doxyLineContent"><span class="doxyHighlight">        &amp;&amp; <a href="#a473b6bd63ac2f9ea9fe6de4f8170194b">generateMakefile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2941</span><span class="doxyLineContent"><span class="doxyHighlight">        &amp;&amp; <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2942</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2943</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2944</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (perlmodLatex) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2945</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!(<a href="#ad03aadb67e05b528cd454bed3bee16b9">generateDoxyLatexStructurePL</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2946</span><span class="doxyLineContent"><span class="doxyHighlight">          &amp;&amp; <a href="#a999b190603bbc840657ad470a17465ad">generateDoxyLatexPL</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2947</span><span class="doxyLineContent"><span class="doxyHighlight">          &amp;&amp; <a href="#a2cb28a6f8bf6b9f155d3929b95acf059">generateDoxyLatexTex</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2948</span><span class="doxyLineContent"><span class="doxyHighlight">          &amp;&amp; <a href="#a1f0a8822b1895daacce85dd3d93eecac">generateDoxyFormatTex</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2949</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2950</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2951</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dir/#a226b0db1117e46393bbb241e545f8609">Dir::absPath</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="#a2ed7475d94b3bc527009ebcc50621004">createOutputDir</a>, <a href="#a1f0a8822b1895daacce85dd3d93eecac">generateDoxyFormatTex</a>, <a href="#a999b190603bbc840657ad470a17465ad">generateDoxyLatexPL</a>, <a href="#ad03aadb67e05b528cd454bed3bee16b9">generateDoxyLatexStructurePL</a>, <a href="#a2cb28a6f8bf6b9f155d3929b95acf059">generateDoxyLatexTex</a>, <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a>, <a href="#a9893c2c270028114dec964284676adc7">generateDoxyStructurePM</a>, <a href="#a473b6bd63ac2f9ea9fe6de4f8170194b">generateMakefile</a>, <a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>, <a href="#a32a35dd412f8e42e1f12b671935da576">pathDoxyDocsPM</a>, <a href="#a6b90bb007822613373e9a65ff35643c4">pathDoxyDocsTex</a>, <a href="#aab3220d2f03ba759c948d8be316d4d2c">pathDoxyFormatTex</a>, <a href="#a4b29e2e00432a296288342688354b856">pathDoxyLatexDVI</a>, <a href="#aab3b623c4824006226ea5195aec1d8ef">pathDoxyLatexPDF</a>, <a href="#a23cafbc784eadd8d96ea498c07ee1b22">pathDoxyLatexPL</a>, <a href="#a8dd402f31f1312093ec503a733a5c691">pathDoxyLatexStructurePL</a>, <a href="#ad2ea9cd9b17663a5b3ff62752031fb2b">pathDoxyLatexTex</a>, <a href="#a5b043201cbf4b5840582794d44bdcafb">pathDoxyRules</a>, <a href="#a4139ab7ca413fcf7e9d9c10a6abb13f2">pathDoxyStructurePM</a>, <a href="#a240a78f6c0326286469e17febcb3e386">pathDoxyStructureTex</a> and <a href="#a2a2147107f3c1812beb023cb68a10c55">pathMakefile</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a3c604811885fb67cffd44d399931dc15">generatePerlMod</a>.
</div>
</div>

### generateDoxyFormatTex() {#a1f0a8822b1895daacce85dd3d93eecac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PerlModGenerator::generateDoxyFormatTex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01458">1458</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f0a8822b1895daacce85dd3d93eecac">2718</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1f0a8822b1895daacce85dd3d93eecac">PerlModGenerator::generateDoxyFormatTex</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2719</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2720</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream doxyFormatTexStream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2721</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>(doxyFormatTexStream, <a href="#aab3220d2f03ba759c948d8be316d4d2c">pathDoxyFormatTex</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2722</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2723</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2724</span><span class="doxyLineContent"><span class="doxyHighlight">  doxyFormatTexStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2725</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\Defcs#1{\\long\\expandafter\\def\\csname#1\\endcsname}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2726</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{Empty}{}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2727</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\IfEmpty#1{\\expandafter\\ifx\\csname#1\\endcsname\\Empty}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2728</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2729</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\StringNode#1{\\Defcs{#1}##1{##1}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2730</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\DocNode#1{\\Defcs{#1}##1{##1}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2731</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\ListNode#1{\\Defcs{#1}##1{##1}\\Defcs{#1Sep}{}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2732</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\HashNode#1{\\Defcs{#1}{}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2733</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2734</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\input{"</span><span class="doxyHighlight"> &lt;&lt; <a href="#a240a78f6c0326286469e17febcb3e386">pathDoxyStructureTex</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2735</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2736</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\newbox\\BoxA\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2737</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\dimendef\\DimenA=151\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2738</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\dimendef\\DimenB=152\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2739</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\countdef\\ZoneDepth=151\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2740</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2741</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\Cs#1{\\csname#1\\endcsname}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2742</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\Letcs#1{\\expandafter\\let\\csname#1\\endcsname}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2743</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\Heading#1{\\vskip 4mm\\relax\\textbf{#1}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2744</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\See#1{\\begin{flushleft}\\Heading{See also: }#1\\end{flushleft}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2745</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2746</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\Frame#1{\\vskip 3mm\\relax\\fbox{ \\vbox{\\hsize0.95\\hsize\\vskip 1mm\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2747</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\raggedright#1\\vskip 0.5mm\\relax} }}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2748</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2749</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\Zone#1#2#3{%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2750</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{Test#1}{#2}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2751</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{Emit#1}{#3}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2752</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1}{%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2753</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\advance\\ZoneDepth1\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2754</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Letcs{Mode\\number\\ZoneDepth}0\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2755</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Letcs{Present\\number\\ZoneDepth}0\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2756</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Cs{Test#1}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2757</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\expandafter\\if\\Cs{Present\\number\\ZoneDepth}1%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2758</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\advance\\ZoneDepth-1\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2759</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Letcs{Present\\number\\ZoneDepth}1\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2760</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\expandafter\\if\\Cs{Mode\\number\\ZoneDepth}1%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2761</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\advance\\ZoneDepth1\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2762</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Letcs{Mode\\number\\ZoneDepth}1\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2763</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Cs{Emit#1}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2764</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\advance\\ZoneDepth-1\\relax\\fi\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2765</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\advance\\ZoneDepth1\\relax\\fi\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2766</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\advance\\ZoneDepth-1\\relax}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2767</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2768</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\Member#1#2{%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2769</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{Test#1}{\\Cs{field#1Detailed}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2770</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\IfEmpty{field#1DetailedDoc}\\else\\Letcs{Present#1}1\\fi}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2771</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1}{\\Letcs{Present#1}0\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2772</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Cs{Test#1}\\if1\\Cs{Present#1}\\Letcs{Present\\number\\ZoneDepth}1\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2773</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\if1\\Cs{Mode\\number\\ZoneDepth}#2\\fi\\fi}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2774</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2775</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\TypedefMemberList#1#2{%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2776</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1DetailedDoc}##1{\\vskip 5.5mm\\relax##1}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2777</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1Name}##1{\\textbf{##1}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2778</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1See}##1{\\See{##1}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2779</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2780</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Zone{#1s}{\\Cs{field#1List}}{\\subsubsection{#2}\\Cs{field#1List}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2781</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Member{#1}{\\Frame{typedef \\Cs{field#1Type} \\Cs{field#1Name}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2782</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Cs{field#1DetailedDoc}\\Cs{field#1See}\\vskip 5mm\\relax}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2783</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2784</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\VariableMemberList#1#2{%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2785</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1DetailedDoc}##1{\\vskip 5.5mm\\relax##1}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2786</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1Name}##1{\\textbf{##1}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2787</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1See}##1{\\See{##1}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2788</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2789</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Zone{#1s}{\\Cs{field#1List}}{\\subsubsection{#2}\\Cs{field#1List}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2790</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Member{#1}{\\Frame{\\Cs{field#1Type}{} \\Cs{field#1Name}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2791</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Cs{field#1DetailedDoc}\\Cs{field#1See}\\vskip 5mm\\relax}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2792</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2793</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\FunctionMemberList#1#2{%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2794</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1PDParamName}##1{\\textit{##1}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2795</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1PDParam}{\\Cs{field#1PDParamName}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2796</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1PDParamsSep}{, }%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2797</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1PDBlocksSep}{\\vskip 2mm\\relax}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2798</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2799</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1PDBlocks}##1{%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2800</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Heading{Parameters:}\\vskip 1.5mm\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2801</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\DimenA0pt\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2802</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1PDBlock}{\\setbox\\BoxA\\hbox{\\Cs{field#1PDParams}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2803</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\ifdim\\DimenA&lt;\\wd\\BoxA\\DimenA\\wd\\BoxA\\fi}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2804</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"##1%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2805</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\advance\\DimenA3mm\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2806</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\DimenB\\hsize\\advance\\DimenB-\\DimenA\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2807</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1PDBlock}{\\hbox to\\hsize{\\vtop{\\hsize\\DimenA\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2808</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Cs{field#1PDParams}}\\hfill\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2809</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\vtop{\\hsize\\DimenB\\relax\\Cs{field#1PDDoc}}}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2810</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"##1}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2811</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2812</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1ParamName}##1{\\textit{##1}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2813</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1Param}{\\Cs{field#1ParamType}{} \\Cs{field#1ParamName}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2814</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1ParamsSep}{, }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2815</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2816</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1Name}##1{\\textbf{##1}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2817</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1See}##1{\\See{##1}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2818</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{#1Return}##1{\\Heading{Returns: }##1}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2819</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Defcs{field#1Title}{\\Frame{\\Cs{field#1Type}{} \\Cs{field#1Name}(\\Cs{field#1Params})}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2820</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2821</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Zone{#1s}{\\Cs{field#1List}}{\\subsubsection{#2}\\Cs{field#1List}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2822</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Member{#1}{%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2823</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Cs{field#1Title}\\vskip 6mm\\relax\\Cs{field#1DetailedDoc}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2824</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Cs{field#1Return}\\Cs{field#1PDBlocks}\\Cs{field#1See}\\vskip 5mm\\relax}}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2825</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2826</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\FileDetailed{\\fieldFileDetailedDoc\\par}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2827</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\ClassDetailed{\\fieldClassDetailedDoc\\par}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2828</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2829</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\FileSubzones{\\fieldFileTypedefs\\fieldFileVariables\\fieldFileFunctions}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2830</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2831</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\ClassSubzones{%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2832</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\fieldClassPublicTypedefs\\fieldClassPublicMembers\\fieldClassPublicMethods\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2833</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\fieldClassProtectedTypedefs\\fieldClassProtectedMembers\\fieldClassProtectedMethods\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2834</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\fieldClassPrivateTypedefs\\fieldClassPrivateMembers\\fieldClassPrivateMethods}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2835</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2836</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Member{Page}{\\subsection{\\fieldPageName}\\fieldPageDetailedDoc}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2837</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2838</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\TypedefMemberList{FileTypedef}{Typedefs}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2839</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\VariableMemberList{FileVariable}{Variables}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2840</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\FunctionMemberList{FileFunction}{Functions}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2841</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Zone{File}{\\FileSubzones}{\\subsection{\\fieldFileName}\\fieldFileDetailed\\FileSubzones}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2842</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2843</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\TypedefMemberList{ClassPublicTypedef}{Public Typedefs}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2844</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\TypedefMemberList{ClassProtectedTypedef}{Protected Typedefs}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2845</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\TypedefMemberList{ClassPrivateTypedef}{Private Typedefs}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2846</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\VariableMemberList{ClassPublicMember}{Public Members}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2847</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\VariableMemberList{ClassProtectedMember}{Protected Members}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2848</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\VariableMemberList{ClassPrivateMember}{Private Members}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2849</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\FunctionMemberList{ClassPublicMethod}{Public Methods}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2850</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\FunctionMemberList{ClassProtectedMethod}{Protected Methods}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2851</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\FunctionMemberList{ClassPrivateMethod}{Private Methods}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2852</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Zone{Class}{\\ClassSubzones}{\\subsection{\\fieldClassName}\\fieldClassDetailed\\ClassSubzones}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2853</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2854</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Zone{AllPages}{\\fieldPages}{\\section{Pages}\\fieldPages}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2855</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Zone{AllFiles}{\\fieldFiles}{\\section{Files}\\fieldFiles}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2856</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Zone{AllClasses}{\\fieldClasses}{\\section{Classes}\\fieldClasses}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2857</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\newlength{\\oldparskip}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2859</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\newlength{\\oldparindent}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2860</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\newlength{\\oldfboxrule}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2861</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2862</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\ZoneDepth0\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2863</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\Letcs{Mode0}1\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2864</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2865</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\def\\EmitDoxyDocs{%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2866</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\setlength{\\oldparskip}{\\parskip}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2867</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\setlength{\\oldparindent}{\\parindent}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2868</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\setlength{\\oldfboxrule}{\\fboxrule}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2869</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\setlength{\\parskip}{0cm}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2870</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\setlength{\\parindent}{0cm}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2871</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\setlength{\\fboxrule}{1pt}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2872</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\AllPages\\AllFiles\\AllClasses\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2873</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\setlength{\\parskip}{\\oldparskip}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2874</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\setlength{\\parindent}{\\oldparindent}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2875</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\setlength{\\fboxrule}{\\oldfboxrule}}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2876</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2877</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2878</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>, <a href="#aab3220d2f03ba759c948d8be316d4d2c">pathDoxyFormatTex</a> and <a href="#a240a78f6c0326286469e17febcb3e386">pathDoxyStructureTex</a>.

Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>.
</div>
</div>

### generateDoxyLatexPL() {#a999b190603bbc840657ad470a17465ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PerlModGenerator::generateDoxyLatexPL ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01460">1460</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a999b190603bbc840657ad470a17465ad">2596</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a999b190603bbc840657ad470a17465ad">PerlModGenerator::generateDoxyLatexPL</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2597</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2598</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream doxyLatexPLStream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2599</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>(doxyLatexPLStream, <a href="#a23cafbc784eadd8d96ea498c07ee1b22">pathDoxyLatexPL</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2600</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2601</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2602</span><span class="doxyLineContent"><span class="doxyHighlight">  doxyLatexPLStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2603</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"use DoxyStructure;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2604</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"use DoxyDocs;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2605</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2606</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"sub latex_quote($) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2607</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tmy $text = $_[0];\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2608</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t$text =~ s/\\\\/\\\\textbackslash /g;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2609</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t$text =~ s/\\|/\\\\textbar /g;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2610</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t$text =~ s/&lt;/\\\\textless /g;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2611</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t$text =~ s/&gt;/\\\\textgreater /g;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2612</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t$text =~ s/~/\\\\textasciitilde /g;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2613</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t$text =~ s/\\^/\\\\textasciicircum /g;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2614</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t$text =~ s/[\\$&amp;%#_{}]/\\\\$&amp;/g;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2615</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tprint $text;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2616</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2617</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2618</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"sub generate_doc($) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2619</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tmy $doc = $_[0];\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2620</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tfor my $item (@$doc) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2621</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tmy $type = $$item{type};\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2622</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tif ($type eq \"text\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2623</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tlatex_quote($$item{content});\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2624</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t} elsif ($type eq \"parbreak\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2625</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint \"\\n\\n\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2626</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t} elsif ($type eq \"style\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2627</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tmy $style = $$item{style};\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2628</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tif ($$item{enable} eq \"yes\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2629</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\tif ($style eq \"bold\") { print '\\bfseries'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2630</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\tif ($style eq \"italic\") { print '\\itshape'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2631</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\tif ($style eq \"code\") { print '\\ttfamily'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2632</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t} else {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2633</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\tif ($style eq \"bold\") { print '\\mdseries'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2634</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\tif ($style eq \"italic\") { print '\\upshape'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2635</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\tif ($style eq \"code\") { print '\\rmfamily'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2636</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2637</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint '{}';\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2638</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t} elsif ($type eq \"symbol\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2639</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tmy $symbol = $$item{symbol};\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2640</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tif ($symbol eq \"copyright\") { print '\\copyright'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2641</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\telsif ($symbol eq \"szlig\") { print '\\ss'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2642</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint '{}';\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2643</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t} elsif ($type eq \"accent\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2644</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tmy ($accent) = $$item{accent};\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2645</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tif ($accent eq \"umlaut\") { print '\\\"'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2646</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\telsif ($accent eq \"acute\") { print '\\\\\\''; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2647</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\telsif ($accent eq \"grave\") { print '\\`'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2648</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\telsif ($accent eq \"circ\") { print '\\^'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2649</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\telsif ($accent eq \"tilde\") { print '\\~'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2650</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\telsif ($accent eq \"cedilla\") { print '\\c'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2651</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\telsif ($accent eq \"ring\") { print '\\r'; }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2652</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint \"{\" . $$item{letter} . \"}\"; \n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2653</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t} elsif ($type eq \"list\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2654</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tmy $env = ($$item{style} eq \"ordered\") ? \"enumerate\" : \"itemize\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2655</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint \"\\n\\\\begin{\" . $env .\"}\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2656</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  \tfor my $subitem (@{$$item{content}}) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2657</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\tprint \"\\n\\\\item \";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2658</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\tgenerate_doc($subitem);\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2659</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  \t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2660</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint \"\\n\\\\end{\" . $env .\"}\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2661</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t} elsif ($type eq \"url\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2662</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tlatex_quote($$item{content});\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2663</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2664</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2665</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2666</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2667</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"sub generate($$) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2668</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tmy ($item, $node) = @_;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2669</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tmy ($type, $name) = @$node[0, 1];\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2670</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tif ($type eq \"string\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2671</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tprint \"\\\\\" . $name . \"{\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2672</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tlatex_quote($item);\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2673</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tprint \"}\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2674</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t} elsif ($type eq \"doc\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2675</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tif (@$item) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2676</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint \"\\\\\" . $name . \"{\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2677</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tgenerate_doc($item);\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2678</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint \"}%\\n\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2679</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t} else {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2680</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"#\t\t\tprint \"\\\\\" . $name . \"Empty%\\n\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2681</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2682</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t} elsif ($type eq \"hash\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2683</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tmy ($key, $value);\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2684</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\twhile (($key, $subnode) = each %{$$node[2]}) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2685</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tmy $subname = $$subnode[1];\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2686</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint \"\\\\Defcs{field\" . $subname . \"}{\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2687</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tif ($$item{$key}) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2688</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\tgenerate($$item{$key}, $subnode);\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2689</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t} else {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2690</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"#\t\t\t\t\tprint \"\\\\\" . $subname . \"Empty%\\n\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2691</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2692</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint \"}%\\n\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2693</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2694</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tprint \"\\\\\" . $name . \"%\\n\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2695</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t} elsif ($type eq \"list\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2696</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tmy $index = 0;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2697</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tif (@$item) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2698</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint \"\\\\\" . $name . \"{%\\n\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2699</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tfor my $subitem (@$item) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2700</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\tif ($index) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2701</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t\tprint \"\\\\\" . $name . \"Sep%\\n\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2702</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2703</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\tgenerate($subitem, $$node[2]);\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2704</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t$index++;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2705</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2706</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprint \"}%\\n\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2707</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t} else {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2708</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"#\t\t\tprint \"\\\\\" . $name . \"Empty%\\n\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2709</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2710</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2711</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2712</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2713</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"generate($doxydocs, $doxystructure);\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2714</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2715</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2716</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a> and <a href="#a23cafbc784eadd8d96ea498c07ee1b22">pathDoxyLatexPL</a>.

Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>.
</div>
</div>

### generateDoxyLatexStructurePL() {#ad03aadb67e05b528cd454bed3bee16b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PerlModGenerator::generateDoxyLatexStructurePL ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01461">1461</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad03aadb67e05b528cd454bed3bee16b9">2563</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad03aadb67e05b528cd454bed3bee16b9">PerlModGenerator::generateDoxyLatexStructurePL</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2564</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2565</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream doxyLatexStructurePLStream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2566</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>(doxyLatexStructurePLStream, <a href="#a8dd402f31f1312093ec503a733a5c691">pathDoxyLatexStructurePL</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2567</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2568</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2569</span><span class="doxyLineContent"><span class="doxyHighlight">  doxyLatexStructurePLStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2570</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"use DoxyStructure;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2571</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2572</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"sub process($) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2573</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tmy $node = $_[0];\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2574</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tmy ($type, $name) = @$node[0, 1];\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2575</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tmy $command;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2576</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tif ($type eq \"string\") { $command = \"String\" }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2577</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\telsif ($type eq \"doc\") { $command = \"Doc\" }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2578</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\telsif ($type eq \"hash\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2579</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t$command = \"Hash\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2580</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tfor my $subnode (values %{$$node[2]}) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2581</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\tprocess($subnode);\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2582</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2583</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2584</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\telsif ($type eq \"list\") {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2585</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t$command = \"List\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2586</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tprocess($$node[2]);\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2587</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2588</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tprint \"\\\\\" . $command . \"Node{\" . $name . \"}%\\n\";\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2589</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2590</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2591</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"process($doxystructure);\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2592</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2593</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2594</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a> and <a href="#a8dd402f31f1312093ec503a733a5c691">pathDoxyLatexStructurePL</a>.

Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>.
</div>
</div>

### generateDoxyLatexTex() {#a2cb28a6f8bf6b9f155d3929b95acf059}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PerlModGenerator::generateDoxyLatexTex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01457">1457</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2cb28a6f8bf6b9f155d3929b95acf059">2880</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2cb28a6f8bf6b9f155d3929b95acf059">PerlModGenerator::generateDoxyLatexTex</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2881</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2882</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream doxyLatexTexStream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2883</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>(doxyLatexTexStream, <a href="#ad2ea9cd9b17663a5b3ff62752031fb2b">pathDoxyLatexTex</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2884</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2885</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2886</span><span class="doxyLineContent"><span class="doxyHighlight">  doxyLatexTexStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2887</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\documentclass[a4paper,12pt]{article}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2888</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\usepackage[latin1]{inputenc}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2889</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\usepackage[none]{hyphenat}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2890</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\usepackage[T1]{fontenc}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2891</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\usepackage{hyperref}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2892</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\usepackage{times}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2893</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2894</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\input{doxyformat}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2895</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2896</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\begin{document}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2897</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\input{"</span><span class="doxyHighlight"> &lt;&lt; <a href="#a6b90bb007822613373e9a65ff35643c4">pathDoxyDocsTex</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2898</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sloppy\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2899</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\EmitDoxyDocs\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2900</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\end{document}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2901</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2902</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2903</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>, <a href="#a6b90bb007822613373e9a65ff35643c4">pathDoxyDocsTex</a> and <a href="#ad2ea9cd9b17663a5b3ff62752031fb2b">pathDoxyLatexTex</a>.

Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>.
</div>
</div>

### generateDoxyRules() {#a72b6d57151d45a13c60402914aa50831}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PerlModGenerator::generateDoxyRules ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01462">1462</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72b6d57151d45a13c60402914aa50831">2441</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a72b6d57151d45a13c60402914aa50831">PerlModGenerator::generateDoxyRules</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2442</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2443</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream doxyRulesStream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2444</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>(doxyRulesStream, <a href="#a5b043201cbf4b5840582794d44bdcafb">pathDoxyRules</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2445</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2446</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2447</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> perlmodLatex = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PERLMOD_LATEX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2448</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PERLMOD_MAKEVAR_PREFIX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2449</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2450</span><span class="doxyLineContent"><span class="doxyHighlight">  doxyRulesStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2451</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXY_EXEC_PATH = "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af9a07601cdd319c7b07bd7aa46c7e5fb">pathDoxyExec</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2452</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYFILE = "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#afb0371ed59a369486ad1a67b4c2efeab">pathDoxyfile</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2453</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYDOCS_PM = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a32a35dd412f8e42e1f12b671935da576">pathDoxyDocsPM</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2454</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYSTRUCTURE_PM = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a4139ab7ca413fcf7e9d9c10a6abb13f2">pathDoxyStructurePM</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2455</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYRULES = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a5b043201cbf4b5840582794d44bdcafb">pathDoxyRules</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2456</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (perlmodLatex)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2457</span><span class="doxyLineContent"><span class="doxyHighlight">    doxyRulesStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2458</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_PL = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a23cafbc784eadd8d96ea498c07ee1b22">pathDoxyLatexPL</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2459</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEXSTRUCTURE_PL = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a8dd402f31f1312093ec503a733a5c691">pathDoxyLatexStructurePL</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2460</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYSTRUCTURE_TEX = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a240a78f6c0326286469e17febcb3e386">pathDoxyStructureTex</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2461</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYDOCS_TEX = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a6b90bb007822613373e9a65ff35643c4">pathDoxyDocsTex</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2462</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYFORMAT_TEX = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#aab3220d2f03ba759c948d8be316d4d2c">pathDoxyFormatTex</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2463</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_TEX = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#ad2ea9cd9b17663a5b3ff62752031fb2b">pathDoxyLatexTex</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2464</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_DVI = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a4b29e2e00432a296288342688354b856">pathDoxyLatexDVI</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2465</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_PDF = "</span><span class="doxyHighlight"> &lt;&lt; <a href="#aab3b623c4824006226ea5195aec1d8ef">pathDoxyLatexPDF</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2466</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2467</span><span class="doxyLineContent"><span class="doxyHighlight">  doxyRulesStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2468</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2469</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">".PHONY: clean-perlmod\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2470</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"clean-perlmod::\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2471</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\trm -f $("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYSTRUCTURE_PM) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2472</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYDOCS_PM)"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2473</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (perlmodLatex)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2474</span><span class="doxyLineContent"><span class="doxyHighlight">    doxyRulesStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2475</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">" \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2476</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_PL) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2477</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEXSTRUCTURE_PL) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2478</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYDOCS_TEX) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2479</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYSTRUCTURE_TEX) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2480</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYFORMAT_TEX) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2481</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_TEX) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2482</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_PDF) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2483</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_DVI) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2484</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\t$(addprefix $("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_TEX:tex=),out aux log)"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2485</span><span class="doxyLineContent"><span class="doxyHighlight">  doxyRulesStream &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2486</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2487</span><span class="doxyLineContent"><span class="doxyHighlight">  doxyRulesStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2488</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYRULES) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2489</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYMAKEFILE) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2490</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYSTRUCTURE_PM) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2491</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYDOCS_PM)"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2492</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (perlmodLatex) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2493</span><span class="doxyLineContent"><span class="doxyHighlight">    doxyRulesStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2494</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">" \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2495</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_PL) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2496</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEXSTRUCTURE_PL) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2497</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYFORMAT_TEX) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2498</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_TEX)"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2499</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2500</span><span class="doxyLineContent"><span class="doxyHighlight">  doxyRulesStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2501</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">": \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2502</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYFILE)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2503</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tcd $("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXY_EXEC_PATH) ; doxygen \"$&lt;\"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2504</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2505</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (perlmodLatex) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2506</span><span class="doxyLineContent"><span class="doxyHighlight">    doxyRulesStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2507</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2508</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYDOCS_TEX): \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2509</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_PL) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2510</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYDOCS_PM)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2511</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tperl -I\"$(&lt;D)\" \"$&lt;\" &gt;\"$@\"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2512</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2513</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYSTRUCTURE_TEX): \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2514</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEXSTRUCTURE_PL) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2515</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYSTRUCTURE_PM)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2516</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tperl -I\"$(&lt;D)\" \"$&lt;\" &gt;\"$@\"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2517</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2518</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_PDF) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2519</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_DVI): \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2520</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_TEX) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2521</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYFORMAT_TEX) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2522</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYSTRUCTURE_TEX) \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2523</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYDOCS_TEX)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2524</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2525</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_PDF): \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2526</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_TEX)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2527</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tpdflatex -interaction=nonstopmode \"$&lt;\"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2528</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2529</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_DVI): \\\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2530</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"$("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_TEX)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2531</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"\tlatex -interaction=nonstopmode \"$&lt;\"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2532</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2533</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2534</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2535</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>, <a href="#a32a35dd412f8e42e1f12b671935da576">pathDoxyDocsPM</a>, <a href="#a6b90bb007822613373e9a65ff35643c4">pathDoxyDocsTex</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af9a07601cdd319c7b07bd7aa46c7e5fb">pathDoxyExec</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#afb0371ed59a369486ad1a67b4c2efeab">pathDoxyfile</a>, <a href="#aab3220d2f03ba759c948d8be316d4d2c">pathDoxyFormatTex</a>, <a href="#a4b29e2e00432a296288342688354b856">pathDoxyLatexDVI</a>, <a href="#aab3b623c4824006226ea5195aec1d8ef">pathDoxyLatexPDF</a>, <a href="#a23cafbc784eadd8d96ea498c07ee1b22">pathDoxyLatexPL</a>, <a href="#a8dd402f31f1312093ec503a733a5c691">pathDoxyLatexStructurePL</a>, <a href="#ad2ea9cd9b17663a5b3ff62752031fb2b">pathDoxyLatexTex</a>, <a href="#a5b043201cbf4b5840582794d44bdcafb">pathDoxyRules</a>, <a href="#a4139ab7ca413fcf7e9d9c10a6abb13f2">pathDoxyStructurePM</a>, <a href="#a240a78f6c0326286469e17febcb3e386">pathDoxyStructureTex</a> and <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.

Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>.
</div>
</div>

### generateDoxyStructurePM() {#a9893c2c270028114dec964284676adc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PerlModGenerator::generateDoxyStructurePM ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01459">1459</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9893c2c270028114dec964284676adc7">2258</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9893c2c270028114dec964284676adc7">PerlModGenerator::generateDoxyStructurePM</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2259</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2260</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream doxyModelPMStream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2261</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>(doxyModelPMStream, <a href="#a4139ab7ca413fcf7e9d9c10a6abb13f2">pathDoxyStructurePM</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2262</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2263</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2264</span><span class="doxyLineContent"><span class="doxyHighlight">  doxyModelPMStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2265</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"sub memberlist($) {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2266</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"    my $prefix = $_[0];\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2267</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"    return\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2268</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t[ \"hash\", $prefix . \"s\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2269</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t  {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2270</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t    members =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2271</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t      [ \"list\", $prefix . \"List\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2272</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t[ \"hash\", $prefix,\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2273</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2274</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    kind =&gt; [ \"string\", $prefix . \"Kind\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2275</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    name =&gt; [ \"string\", $prefix . \"Name\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2276</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    static =&gt; [ \"string\", $prefix . \"Static\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2277</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    virtualness =&gt; [ \"string\", $prefix . \"Virtualness\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2278</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    protection =&gt; [ \"string\", $prefix . \"Protection\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2279</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    type =&gt; [ \"string\", $prefix . \"Type\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2280</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    parameters =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2281</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      [ \"list\", $prefix . \"Params\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2282</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t[ \"hash\", $prefix . \"Param\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2283</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t  {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2284</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t    declaration_name =&gt; [ \"string\", $prefix . \"ParamName\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2285</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t    type =&gt; [ \"string\", $prefix . \"ParamType\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t  },\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2287</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2288</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2289</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    detailed =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2290</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      [ \"hash\", $prefix . \"Detailed\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2291</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t{\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2292</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t  doc =&gt; [ \"doc\", $prefix . \"DetailedDoc\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2293</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t  return =&gt; [ \"doc\", $prefix . \"Return\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2294</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t  see =&gt; [ \"doc\", $prefix . \"See\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2295</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t  params =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2296</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t    [ \"list\", $prefix . \"PDBlocks\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2297</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t      [ \"hash\", $prefix . \"PDBlock\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2298</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t{\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2299</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t  parameters =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2300</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t    [ \"list\", $prefix . \"PDParams\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2301</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t      [ \"hash\", $prefix . \"PDParam\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2302</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t\t{\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2303</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t\t  name =&gt; [ \"string\", $prefix . \"PDParamName\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2304</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t\t},\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2305</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t      ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2306</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t    ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2307</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t  doc =&gt; [ \"doc\", $prefix . \"PDDoc\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2308</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t\t},\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2309</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t      ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2310</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t    ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2311</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t\t},\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2312</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2313</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  },\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2314</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2315</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t      ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2316</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t  },\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2317</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t];\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2318</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2319</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2320</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"$doxystructure =\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2321</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"    [ \"hash\", \"Root\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2322</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"      {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2323</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tfiles =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2324</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t  [ \"list\", \"Files\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2325</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t    [ \"hash\", \"File\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2326</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t      {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2327</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tname =&gt; [ \"string\", \"FileName\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2328</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\ttypedefs =&gt; memberlist(\"FileTypedef\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2329</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tvariables =&gt; memberlist(\"FileVariable\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2330</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tfunctions =&gt; memberlist(\"FileFunction\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2331</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tdetailed =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2332</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  [ \"hash\", \"FileDetailed\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2333</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2334</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      doc =&gt; [ \"doc\", \"FileDetailedDoc\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2335</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    },\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2336</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2337</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t      },\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2338</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t    ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2339</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2340</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tpages =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2341</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t  [ \"list\", \"Pages\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2342</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t    [ \"hash\", \"Page\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2343</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t      {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2344</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tname =&gt; [ \"string\", \"PageName\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2345</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tdetailed =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2346</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  [ \"hash\", \"PageDetailed\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2347</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2348</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      doc =&gt; [ \"doc\", \"PageDetailedDoc\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2349</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    },\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2350</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2351</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t      },\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2352</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t    ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2353</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2354</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tclasses =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2355</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t  [ \"list\", \"Classes\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2356</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t    [ \"hash\", \"Class\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2357</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t      {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2358</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tname =&gt; [ \"string\", \"ClassName\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2359</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tpublic_typedefs =&gt; memberlist(\"ClassPublicTypedef\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2360</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tpublic_methods =&gt; memberlist(\"ClassPublicMethod\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2361</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tpublic_members =&gt; memberlist(\"ClassPublicMember\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2362</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tprotected_typedefs =&gt; memberlist(\"ClassProtectedTypedef\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2363</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tprotected_methods =&gt; memberlist(\"ClassProtectedMethod\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2364</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tprotected_members =&gt; memberlist(\"ClassProtectedMember\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2365</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tprivate_typedefs =&gt; memberlist(\"ClassPrivateTypedef\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2366</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tprivate_methods =&gt; memberlist(\"ClassPrivateMethod\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2367</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tprivate_members =&gt; memberlist(\"ClassPrivateMember\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2368</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tdetailed =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2369</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  [ \"hash\", \"ClassDetailed\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2370</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2371</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      doc =&gt; [ \"doc\", \"ClassDetailedDoc\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2372</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    },\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2373</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2374</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t      },\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2375</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t    ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2376</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2377</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\tgroups =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2378</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t  [ \"list\", \"Groups\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2379</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t    [ \"hash\", \"Group\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2380</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t      {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2381</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tname =&gt; [ \"string\", \"GroupName\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2382</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\ttitle =&gt; [ \"string\", \"GroupTitle\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2383</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tfiles =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2384</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  [ \"list\", \"Files\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2385</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    [ \"hash\", \"File\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2386</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2387</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t        name =&gt; [ \"string\", \"Filename\" ]\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2388</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2389</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2390</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2391</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tclasses  =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2392</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  [ \"list\", \"Classes\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2393</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    [ \"hash\", \"Class\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2394</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2395</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t        name =&gt; [ \"string\", \"Classname\" ]\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2396</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2397</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2398</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2399</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tnamespaces =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2400</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  [ \"list\", \"Namespaces\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2401</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    [ \"hash\", \"Namespace\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2402</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2403</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t        name =&gt; [ \"string\", \"NamespaceName\" ]\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2404</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2405</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2406</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2407</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tpages =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2408</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  [ \"list\", \"Pages\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2409</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    [ \"hash\", \"Page\","</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2410</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2411</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t        title =&gt; [ \"string\", \"PageName\" ]\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2412</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2413</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2414</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2415</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tgroups =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2416</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  [ \"list\", \"Groups\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2417</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    [ \"hash\", \"Group\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2418</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2419</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t        title =&gt; [ \"string\", \"GroupName\" ]\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2420</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2421</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2422</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2423</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tfunctions =&gt; memberlist(\"GroupFunction\"),\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2424</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\tdetailed =&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2425</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  [ \"hash\", \"GroupDetailed\",\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2426</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    {\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2427</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t      doc =&gt; [ \"doc\", \"GroupDetailedDoc\" ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2428</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t    },\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2429</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2430</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t      }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2431</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t    ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2432</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\t  ],\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2433</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"      },\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2434</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"    ];\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2435</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2436</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"1;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2437</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2438</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2439</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a> and <a href="#a4139ab7ca413fcf7e9d9c10a6abb13f2">pathDoxyStructurePM</a>.

Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>.
</div>
</div>

### generateMakefile() {#a473b6bd63ac2f9ea9fe6de4f8170194b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PerlModGenerator::generateMakefile ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01463">1463</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a473b6bd63ac2f9ea9fe6de4f8170194b">2537</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a473b6bd63ac2f9ea9fe6de4f8170194b">PerlModGenerator::generateMakefile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2538</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2539</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream makefileStream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2540</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>(makefileStream, <a href="#a2a2147107f3c1812beb023cb68a10c55">pathMakefile</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2541</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2542</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2543</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> perlmodLatex = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PERLMOD_LATEX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2544</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PERLMOD_MAKEVAR_PREFIX);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2545</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2546</span><span class="doxyLineContent"><span class="doxyHighlight">  makefileStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2547</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">".PHONY: default clean"</span><span class="doxyHighlight"> &lt;&lt; (perlmodLatex ? </span><span class="doxyHighlightStringLiteral">" pdf"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2548</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"default: "</span><span class="doxyHighlight"> &lt;&lt; (perlmodLatex ? </span><span class="doxyHighlightStringLiteral">"pdf"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"clean"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2549</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2550</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"include "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a5b043201cbf4b5840582794d44bdcafb">pathDoxyRules</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2551</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2552</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"clean: clean-perlmod\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2553</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2554</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (perlmodLatex) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2555</span><span class="doxyLineContent"><span class="doxyHighlight">    makefileStream &lt;&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2556</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"pdf: $("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_PDF)\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2557</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightStringLiteral">"dvi: $("</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"DOXYLATEX_DVI)\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2558</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2559</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2560</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2561</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>, <a href="#a5b043201cbf4b5840582794d44bdcafb">pathDoxyRules</a>, <a href="#a2a2147107f3c1812beb023cb68a10c55">pathMakefile</a> and <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.

Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>.
</div>
</div>

### generatePerlModForClass() {#a44b30742275d27dcfe5eb9ea286af80f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::generatePerlModForClass (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01447">1447</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44b30742275d27dcfe5eb9ea286af80f">1733</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1734</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1735</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1736</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1737</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + template argument list(s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1738</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - include file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1739</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1740</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + inheritance diagram</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1741</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of direct super classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1742</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of direct sub classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1743</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of inner classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1744</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + collaboration diagram</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1745</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + list of all members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1746</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + user defined member sections</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1747</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + standard member sections</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1748</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed member documentation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1749</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - examples using the class</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1750</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1751</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>())        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1752</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">isAnonymous</a>())        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip anonymous compounds.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1753</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#ad03b3f6196640021e3c44d7b1eb9e924">isImplicitTemplateInstance</a>())  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip generated template instances.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* DGA: fix # #7547 Perlmod does not generate "kind" information to discriminate struct/union */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"kind"</span><span class="doxyHighlight">, cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a239fe977638806153345cd2411c28062">compoundTypeString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"base"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">baseClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, bcd.classDef-&gt;displayName())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"virtualness"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a3db996b98d5e76eca750e67f99b4e327">getVirtualnessName</a>(bcd.virt))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"protection"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a85b31a0b9f4657070d51bb5f61e6316e">getProtectionName</a>(bcd.prot))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"derived"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;bcd : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">subClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1778</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, bcd.classDef-&gt;displayName())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"virtualness"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a3db996b98d5e76eca750e67f99b4e327">getVirtualnessName</a>(bcd.virt))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"protection"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a85b31a0b9f4657070d51bb5f61e6316e">getProtectionName</a>(bcd.prot))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"inner"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;icd : cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#aeb64dc8f57c5d07f1b1d55bc560a7004">getClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, icd-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7b0a42da35d51f4e7f198975258cf9fd">addIncludeInfo</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#af0c57a31c5cbef35d12de99e88745f66">includeInfo</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a5375ce03d260026390f88a202e99fe33">addTemplateList</a>(cd,<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a81142c12bb2ef7638500997115bf2f43">addListOfAllMembers</a>(cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a>(cd, cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#add2c3b56273ce664bbaeb0ce1c8f420c">getMemberGroups</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubTypes()),</span><span class="doxyHighlightStringLiteral">"public_typedefs"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubMethods()),</span><span class="doxyHighlightStringLiteral">"public_methods"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubAttribs()),</span><span class="doxyHighlightStringLiteral">"public_members"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubSlots()),</span><span class="doxyHighlightStringLiteral">"public_slots"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::Signals()),</span><span class="doxyHighlightStringLiteral">"signals"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::DcopMethods()),</span><span class="doxyHighlightStringLiteral">"dcop_methods"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::Properties()),</span><span class="doxyHighlightStringLiteral">"properties"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubStaticMethods()),</span><span class="doxyHighlightStringLiteral">"public_static_methods"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PubStaticAttribs()),</span><span class="doxyHighlightStringLiteral">"public_static_members"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProTypes()),</span><span class="doxyHighlightStringLiteral">"protected_typedefs"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProMethods()),</span><span class="doxyHighlightStringLiteral">"protected_methods"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProAttribs()),</span><span class="doxyHighlightStringLiteral">"protected_members"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProSlots()),</span><span class="doxyHighlightStringLiteral">"protected_slots"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProStaticMethods()),</span><span class="doxyHighlightStringLiteral">"protected_static_methods"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::ProStaticAttribs()),</span><span class="doxyHighlightStringLiteral">"protected_static_members"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriTypes()),</span><span class="doxyHighlightStringLiteral">"private_typedefs"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriMethods()),</span><span class="doxyHighlightStringLiteral">"private_methods"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriAttribs()),</span><span class="doxyHighlightStringLiteral">"private_members"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriSlots()),</span><span class="doxyHighlightStringLiteral">"private_slots"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriStaticMethods()),</span><span class="doxyHighlightStringLiteral">"private_static_methods"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::PriStaticAttribs()),</span><span class="doxyHighlightStringLiteral">"private_static_members"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::Friends()),</span><span class="doxyHighlightStringLiteral">"friend_methods"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(cd,cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">getMemberList</a>(MemberListType::Related()),</span><span class="doxyHighlightStringLiteral">"related_methods"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"brief"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),cd,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"detailed"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),cd,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#if 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotclassgraph">DotClassGraph</a> inheritanceGraph(cd,DotClassGraph::Inheritance);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!inheritanceGraph.<a href="/web-doxygen/docs/api/classes/dotclassgraph/#a828e0e888fb52189a320a57a1eb96fe7">isTrivial</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;inheritancegraph&gt;"</span><span class="doxyHighlight"> &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span><span class="doxyLineContent"><span class="doxyHighlight">    inheritanceGraph.writePerlMod(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/inheritancegraph&gt;"</span><span class="doxyHighlight"> &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotclassgraph">DotClassGraph</a> collaborationGraph(cd,DotClassGraph::Implementation);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!collaborationGraph.<a href="/web-doxygen/docs/api/classes/dotclassgraph/#a828e0e888fb52189a320a57a1eb96fe7">isTrivial</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;collaborationgraph&gt;"</span><span class="doxyHighlight"> &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">    collaborationGraph.writePerlMod(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/collaborationgraph&gt;"</span><span class="doxyHighlight"> &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;location file=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" line=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">    &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>()!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" bodystart=\""</span><span class="doxyHighlight"> &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">getStartBodyLine</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" bodyend=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">        &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">getEndBodyLine</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"/&gt;"</span><span class="doxyHighlight"> &lt;&lt; endl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a7b0a42da35d51f4e7f198975258cf9fd">addIncludeInfo</a>, <a href="#a81142c12bb2ef7638500997115bf2f43">addListOfAllMembers</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a5375ce03d260026390f88a202e99fe33">addTemplateList</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a38001a11a297629e363c0db5b1968ab3">ClassDef::baseClasses</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a239fe977638806153345cd2411c28062">ClassDef::compoundTypeString</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>, <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a>, <a href="/web-doxygen/docs/api/classes/classdef/#aeb64dc8f57c5d07f1b1d55bc560a7004">ClassDef::getClasses</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0b5313ad11f50b2d056fc62d81db0433">Definition::getEndBodyLine</a>, <a href="/web-doxygen/docs/api/classes/classdef/#add2c3b56273ce664bbaeb0ce1c8f420c">ClassDef::getMemberGroups</a>, <a href="/web-doxygen/docs/api/classes/classdef/#a7d2f9d08207ecf5b227c11f8b4ea6d9f">ClassDef::getMemberList</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a85b31a0b9f4657070d51bb5f61e6316e">getProtectionName</a>, <a href="/web-doxygen/docs/api/classes/definition/#ad63d39480ae9ec4e71bedbb749d16a4c">Definition::getStartBodyLine</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a3db996b98d5e76eca750e67f99b4e327">getVirtualnessName</a>, <a href="/web-doxygen/docs/api/classes/classdef/#af0c57a31c5cbef35d12de99e88745f66">ClassDef::includeInfo</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">Definition::isAnonymous</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ad03b3f6196640021e3c44d7b1eb9e924">ClassDef::isImplicitTemplateInstance</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a828e0e888fb52189a320a57a1eb96fe7">DotClassGraph::isTrivial</a>, <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="/web-doxygen/docs/api/classes/classdef/#afdeec11149bf831c4c6dd297f7c4e34d">ClassDef::subClasses</a>.

Referenced by <a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>.
</div>
</div>

### generatePerlModForConcept() {#ac1f8e6fa454368157eb7cdb564ee6a40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::generatePerlModForConcept (const <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01448">1448</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac1f8e6fa454368157eb7cdb564ee6a40">1859</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac1f8e6fa454368157eb7cdb564ee6a40">PerlModGenerator::generatePerlModForConcept</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7b0a42da35d51f4e7f198975258cf9fd">addIncludeInfo</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/conceptdef/#a4a1c84ee0b30b5f9ccd3df69135b57b8">includeInfo</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a5375ce03d260026390f88a202e99fe33">addTemplateList</a>(cd,<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"initializer"</span><span class="doxyHighlight">, cd-&gt;<a href="/web-doxygen/docs/api/classes/conceptdef/#a1d3f52dc1f9634dfa1f1c0702f918e81">initializer</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"brief"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"detailed"</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a7b0a42da35d51f4e7f198975258cf9fd">addIncludeInfo</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a5375ce03d260026390f88a202e99fe33">addTemplateList</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/conceptdef/#a4a1c84ee0b30b5f9ccd3df69135b57b8">ConceptDef::includeInfo</a>, <a href="/web-doxygen/docs/api/classes/conceptdef/#a1d3f52dc1f9634dfa1f1c0702f918e81">ConceptDef::initializer</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.

Referenced by <a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>.
</div>
</div>

### generatePerlModForFile() {#aa4d01cc3ff8a727b38849e8efd171be9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::generatePerlModForFile (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * fd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01451">1451</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa4d01cc3ff8a727b38849e8efd171be9">1986</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa4d01cc3ff8a727b38849e8efd171be9">PerlModGenerator::generatePerlModForFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *fd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + includes files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + includedby files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - include graph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - included by graph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - contained class definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - contained namespace definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + normal members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - source code</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - location</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - number of lines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"includes"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;inc: fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aaa1fd01a880dff1fb1724a1dd209693f">includeFileList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span><span class="doxyLineContent"><span class="doxyHighlight">      .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, inc.includeName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inc.fileDef &amp;&amp; !inc.fileDef-&gt;isReference())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"ref"</span><span class="doxyHighlight">, inc.fileDef-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"included_by"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;inc : fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#ae9c6fecec7ff96fded91315943519a25">includedByFileList</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2024</span><span class="doxyLineContent"><span class="doxyHighlight">      .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, inc.includeName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inc.fileDef &amp;&amp; !inc.fileDef-&gt;isReference())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"ref"</span><span class="doxyHighlight">, inc.fileDef-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a>(fd, fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#a11c922f32703c5ddc3e4b9d47cea33a3">getMemberGroups</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(fd,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecDefineMembers()),</span><span class="doxyHighlightStringLiteral">"defines"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(fd,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecProtoMembers()),</span><span class="doxyHighlightStringLiteral">"prototypes"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(fd,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecTypedefMembers()),</span><span class="doxyHighlightStringLiteral">"typedefs"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(fd,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecEnumMembers()),</span><span class="doxyHighlightStringLiteral">"enums"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(fd,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecFuncMembers()),</span><span class="doxyHighlightStringLiteral">"functions"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(fd,fd-&gt;<a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">getMemberList</a>(MemberListType::DecVarMembers()),</span><span class="doxyHighlightStringLiteral">"variables"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"brief"</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"detailed"</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,fd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>, <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/filedef/#a11c922f32703c5ddc3e4b9d47cea33a3">FileDef::getMemberGroups</a>, <a href="/web-doxygen/docs/api/classes/filedef/#aca0861997f31aa265f0c0078c947fdc9">FileDef::getMemberList</a>, <a href="/web-doxygen/docs/api/classes/filedef/#ae9c6fecec7ff96fded91315943519a25">FileDef::includedByFileList</a>, <a href="/web-doxygen/docs/api/classes/filedef/#aaa1fd01a880dff1fb1724a1dd209693f">FileDef::includeFileList</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.

Referenced by <a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>.
</div>
</div>

### generatePerlModForGroup() {#aa29eb86a9962f547f8139ff1cfe40b01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::generatePerlModForGroup (const <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> * gd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01452">1452</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa29eb86a9962f547f8139ff1cfe40b01">2048</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2052</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2053</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + namespaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - packages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + pages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + child groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - examples</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2059</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2060</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed description</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2061</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2062</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"title"</span><span class="doxyHighlight">, gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a2caedefd187d92eb8c4afe01d403456e">groupTitle</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a2cb0a3622503ad4232eabc2b7ff86753">getFiles</a>().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"files"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fd : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a2cb0a3622503ad4232eabc2b7ff86753">getFiles</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, fd-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2076</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2077</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#adc93620cc6002b6e7919565cb32b29ed">getClasses</a>().<a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"classes"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2081</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#adc93620cc6002b6e7919565cb32b29ed">getClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2082</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2083</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, cd-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2087</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2088</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a927445c6f77b990c4b7ea29e93a7837e">getConcepts</a>().<a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"concepts"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2091</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a927445c6f77b990c4b7ea29e93a7837e">getConcepts</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2093</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, cd-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2094</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2095</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2096</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#afae9211266248f6c26c5fabf1c4415b0">getModules</a>().<a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"modules"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#afae9211266248f6c26c5fabf1c4415b0">getModules</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, mod-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2104</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2105</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a9ac892052b696a7c561f7dfa7be68f72">getNamespaces</a>().<a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2109</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2110</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"namespaces"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nd : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a9ac892052b696a7c561f7dfa7be68f72">getNamespaces</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, nd-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a97d9ddba395f4c011a01966dc7a61568">getPages</a>().<a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2119</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"pages"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pd : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a97d9ddba395f4c011a01966dc7a61568">getPages</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"title"</span><span class="doxyHighlight">, pd-&gt;title())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2124</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2125</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2126</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2127</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2128</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a29954976b38072020da6c0c0dbde6520">getSubGroups</a>().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2129</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"groups"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;sgd : gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a29954976b38072020da6c0c0dbde6520">getSubGroups</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2133</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"title"</span><span class="doxyHighlight">, sgd-&gt;groupTitle())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2137</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2138</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a>(gd, gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a8a9fe05d4375b4571d822141ba498bf2">getMemberGroups</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2139</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2140</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(gd,gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#ae1e55ed1172103ac1072cde37b3fd578">getMemberList</a>(MemberListType::DecDefineMembers()),</span><span class="doxyHighlightStringLiteral">"defines"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2141</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(gd,gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#ae1e55ed1172103ac1072cde37b3fd578">getMemberList</a>(MemberListType::DecProtoMembers()),</span><span class="doxyHighlightStringLiteral">"prototypes"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2142</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(gd,gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#ae1e55ed1172103ac1072cde37b3fd578">getMemberList</a>(MemberListType::DecTypedefMembers()),</span><span class="doxyHighlightStringLiteral">"typedefs"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2143</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(gd,gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#ae1e55ed1172103ac1072cde37b3fd578">getMemberList</a>(MemberListType::DecEnumMembers()),</span><span class="doxyHighlightStringLiteral">"enums"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(gd,gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#ae1e55ed1172103ac1072cde37b3fd578">getMemberList</a>(MemberListType::DecFuncMembers()),</span><span class="doxyHighlightStringLiteral">"functions"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(gd,gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#ae1e55ed1172103ac1072cde37b3fd578">getMemberList</a>(MemberListType::DecVarMembers()),</span><span class="doxyHighlightStringLiteral">"variables"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2146</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2147</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"brief"</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2148</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"detailed"</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,gd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2149</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2150</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::empty</a>, <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>, <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#adc93620cc6002b6e7919565cb32b29ed">GroupDef::getClasses</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a927445c6f77b990c4b7ea29e93a7837e">GroupDef::getConcepts</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a2cb0a3622503ad4232eabc2b7ff86753">GroupDef::getFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a8a9fe05d4375b4571d822141ba498bf2">GroupDef::getMemberGroups</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#ae1e55ed1172103ac1072cde37b3fd578">GroupDef::getMemberList</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#afae9211266248f6c26c5fabf1c4415b0">GroupDef::getModules</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a9ac892052b696a7c561f7dfa7be68f72">GroupDef::getNamespaces</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a97d9ddba395f4c011a01966dc7a61568">GroupDef::getPages</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a29954976b38072020da6c0c0dbde6520">GroupDef::getSubGroups</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a2caedefd187d92eb8c4afe01d403456e">GroupDef::groupTitle</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.

Referenced by <a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>.
</div>
</div>

### generatePerlModForMember() {#a1d2fc28014f00de3422ac4b7a68b868a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::generatePerlModForMember (const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01441">1441</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d2fc28014f00de3422ac4b7a68b868a">1469</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + declaration/definition arg lists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + reimplements</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + reimplementedBy</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + exceptions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + const/volatile specifiers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1476</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - examples</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1477</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - source definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1478</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - source references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1479</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - source referenced by</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1480</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - body code</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1481</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - template arguments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1482</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//     (templateArguments(), definitionTemplateParameterLists())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> memType;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">MemberType::Define</a>:      memType=</span><span class="doxyHighlightStringLiteral">"define"</span><span class="doxyHighlight">;     </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">MemberType::EnumValue</a>:   memType=</span><span class="doxyHighlightStringLiteral">"enumvalue"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5ad234cb2cde4266195252a23ca7d84e">MemberType::Property</a>:    memType=</span><span class="doxyHighlightStringLiteral">"property"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">MemberType::Variable</a>:    memType=</span><span class="doxyHighlightStringLiteral">"variable"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5fede51b97a819dedf4f83bc2aacbc6a">MemberType::Typedef</a>:     memType=</span><span class="doxyHighlightStringLiteral">"typedef"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">MemberType::Enumeration</a>: memType=</span><span class="doxyHighlightStringLiteral">"enum"</span><span class="doxyHighlight">;       </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a86408593c34af77fdd90df932f8b5261">MemberType::Function</a>:    memType=</span><span class="doxyHighlightStringLiteral">"function"</span><span class="doxyHighlight">;   isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a085fea7abdc5d904fe69a3081efd7398">MemberType::Signal</a>:      memType=</span><span class="doxyHighlightStringLiteral">"signal"</span><span class="doxyHighlight">;     isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a930a91848917f92cf7e2f8d744fa4177">MemberType::Friend</a>:      memType=</span><span class="doxyHighlightStringLiteral">"friend"</span><span class="doxyHighlight">;     isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ad8be171b26c1f1b456fea317076584ab">MemberType::DCOP</a>:        memType=</span><span class="doxyHighlightStringLiteral">"dcop"</span><span class="doxyHighlight">;       isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9234cc57c43f272b55a94b0069fe62d1">MemberType::Slot</a>:        memType=</span><span class="doxyHighlightStringLiteral">"slot"</span><span class="doxyHighlight">;       isFunc=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41aa4ecfc70574394990cf17bd83df499f7">MemberType::Event</a>:       memType=</span><span class="doxyHighlightStringLiteral">"event"</span><span class="doxyHighlight">;      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3c1aac82863ed9e5a9aca8ce687f711d">MemberType::Interface</a>:   memType=</span><span class="doxyHighlightStringLiteral">"interface"</span><span class="doxyHighlight">;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ac2ba7e785c49050f48da9aacc45c2b85">MemberType::Service</a>:     memType=</span><span class="doxyHighlightStringLiteral">"service"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3ff39d3acb327553070a64ef0cb321d5">MemberType::Sequence</a>:    memType=</span><span class="doxyHighlightStringLiteral">"sequence"</span><span class="doxyHighlight">;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3beb75d1563ebc22253341be4ce57f44">MemberType::Dictionary</a>:  memType=</span><span class="doxyHighlightStringLiteral">"dictionary"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isFortran = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>()==SrcLangExt::Fortran;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">  name = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">isAnonymous</a>()) name = </span><span class="doxyHighlightStringLiteral">"__unnamed"</span><span class="doxyHighlight"> + name.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>() - 1)+</span><span class="doxyHighlightStringLiteral">"__"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"kind"</span><span class="doxyHighlight">, memType)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"virtualness"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a3db996b98d5e76eca750e67f99b4e327">getVirtualnessName</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ae450a2be776cc5d05726bab8354f6d62">virtualness</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"protection"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a85b31a0b9f4657070d51bb5f61e6316e">getProtectionName</a>(md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ab266b88c02dd8d5089b29d501b412c5d">protection</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldBoolean(</span><span class="doxyHighlightStringLiteral">"static"</span><span class="doxyHighlight">, md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a73354ecea5b876ab8d59724b080189b4">isStatic</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"brief"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),md,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"detailed"</span><span class="doxyHighlight">,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>(),md,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()!=<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">MemberType::Define</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">      md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()!=<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">MemberType::Enumeration</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">, md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">typeString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">argumentList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isFunc) </span><span class="doxyHighlightComment">//function</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldBoolean(</span><span class="doxyHighlightStringLiteral">"const"</span><span class="doxyHighlight">,    al.<a href="/web-doxygen/docs/api/classes/argumentlist/#a72440ac7985da3c0c465134bc0ddd2d5">constSpecifier</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">            .addFieldBoolean(</span><span class="doxyHighlightStringLiteral">"volatile"</span><span class="doxyHighlight">, al.<a href="/web-doxygen/docs/api/classes/argumentlist/#ad03f25174e81a42a617a15195a8867b0">volatileSpecifier</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"parameters"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;declAl = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#af0d0461390544ad385a962aefd88c313">declArgumentList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!declAl.<a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> defIt = al.<a href="/web-doxygen/docs/api/classes/argumentlist/#acc52d012d093df1adede055164f69dc9">begin</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a : declAl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> *defArg = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defIt!=al.<a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">end</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">          defArg = &amp;(*defIt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">          ++defIt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.name.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"declaration_name"</span><span class="doxyHighlight">, a.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (defArg &amp;&amp; !defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>!=a.name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"definition_name"</span><span class="doxyHighlight">, defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">name</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isFortran &amp;&amp; defArg &amp;&amp; !defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">, defArg-&gt;<a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">type</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.type.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">, a.type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.array.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"array"</span><span class="doxyHighlight">, a.array);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.defval.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"default_value"</span><span class="doxyHighlight">, a.defval);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.attrib.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"attributes"</span><span class="doxyHighlight">, a.attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">MemberType::Define</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">           md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>()!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// define</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"parameters"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a : al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1576</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1577</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, a.type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1578</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1579</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1580</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1581</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1582</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>()!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1583</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1584</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"arguments"</span><span class="doxyHighlight">, md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1585</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1586</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1587</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afe9302d711e627fdd4e9eb7c393ceeb5">initializer</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1588</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"initializer"</span><span class="doxyHighlight">, md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#afe9302d711e627fdd4e9eb7c393ceeb5">initializer</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1589</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1590</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a2f94a19fd2121d155de4865cf7c2fa81">excpString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1591</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"exceptions"</span><span class="doxyHighlight">, md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a2f94a19fd2121d155de4865cf7c2fa81">excpString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1592</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1593</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>()==<a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">MemberType::Enumeration</a>) </span><span class="doxyHighlightComment">// enum</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1594</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1595</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a> &amp;enumFields = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a4df0bef52b6d1d15a4b12a187c8a90ca">enumFieldList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1596</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">, md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a1e08adab7ea5d97208e8662165d89995">enumBaseType</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1597</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!enumFields.<a href="/web-doxygen/docs/api/classes/membervector/#a8211803ee32d3deef9aafca1cc061101">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1598</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1599</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"values"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1600</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;emd : enumFields)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">          .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, emd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!emd-&gt;initializer().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"initializer"</span><span class="doxyHighlight">, emd-&gt;initializer());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"brief"</span><span class="doxyHighlight">,emd-&gt;getDefFileName(),emd-&gt;getDefLine(),emd-&gt;getOuterScope(),emd,emd-&gt;briefDescription());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"detailed"</span><span class="doxyHighlight">,emd-&gt;getDefFileName(),emd-&gt;getDefLine(),emd-&gt;getOuterScope(),emd,emd-&gt;documentation());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">memberType</a>() == <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">MemberType::Variable</a> &amp;&amp; !md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a79b45e3c4c595bebe2c1e65e965c6d39">bitfieldString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1619</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1620</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> bitfield = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a79b45e3c4c595bebe2c1e65e965c6d39">bitfieldString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (bitfield.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0) == </span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) bitfield = bitfield.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"bitfield"</span><span class="doxyHighlight">, bitfield);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *rmd = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a735862f449c091668f1fc86004aab3a2">reimplements</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (rmd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1627</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash(</span><span class="doxyHighlightStringLiteral">"reimplements"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1628</span><span class="doxyLineContent"><span class="doxyHighlight">      .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, rmd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1629</span><span class="doxyLineContent"><span class="doxyHighlight">      .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1630</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1631</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a> &amp;rbml = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5cdaf0953a164c3e6d7831a39c072e71">reimplementedBy</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1632</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!rbml.<a href="/web-doxygen/docs/api/classes/membervector/#a8211803ee32d3deef9aafca1cc061101">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1633</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1634</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"reimplemented_by"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1635</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;rbmd : rbml)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1636</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1637</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, rbmd-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1638</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1639</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1640</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1641</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1642</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1643</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a515503656a6cffb2d27f60e93c3c780e">MemberDef::argumentList</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#acc52d012d093df1adede055164f69dc9">ArgumentList::begin</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a79b45e3c4c595bebe2c1e65e965c6d39">MemberDef::bitfieldString</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a72440ac7985da3c0c465134bc0ddd2d5">ArgumentList::constSpecifier</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ad8be171b26c1f1b456fea317076584ab">DCOP</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#af0d0461390544ad385a962aefd88c313">MemberDef::declArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9312cc2f02f42764c70c3713f80fe219">Define</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3beb75d1563ebc22253341be4ce57f44">Dictionary</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#aaa15ddcfdb06a535a3398f1dc73d336d">ArgumentList::empty</a>, <a href="/web-doxygen/docs/api/classes/membervector/#a8211803ee32d3deef9aafca1cc061101">MemberVector::empty</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a215181845c0d9f0525806a4165c4f552">ArgumentList::end</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a1e08adab7ea5d97208e8662165d89995">MemberDef::enumBaseType</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a2958e521f3da6b41059c4369a34a2a23">Enumeration</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a4df0bef52b6d1d15a4b12a187c8a90ca">MemberDef::enumFieldList</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a29785ae7827639b31b629cc7f9c150e0">EnumValue</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41aa4ecfc70574394990cf17bd83df499f7">Event</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a2f94a19fd2121d155de4865cf7c2fa81">MemberDef::excpString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a930a91848917f92cf7e2f8d744fa4177">Friend</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a86408593c34af77fdd90df932f8b5261">Function</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a85b31a0b9f4657070d51bb5f61e6316e">getProtectionName</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a3db996b98d5e76eca750e67f99b4e327">getVirtualnessName</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#afe9302d711e627fdd4e9eb7c393ceeb5">MemberDef::initializer</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3c1aac82863ed9e5a9aca8ce687f711d">Interface</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">Definition::isAnonymous</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a73354ecea5b876ab8d59724b080189b4">MemberDef::isStatic</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#abbdaf88716807e7ff82ed7502cde51fc">MemberDef::memberType</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/structs/argument/#a334668ce5d1f650c804e69f1bc941a3b">Argument::name</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5ad234cb2cde4266195252a23ca7d84e">Property</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ab266b88c02dd8d5089b29d501b412c5d">MemberDef::protection</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5cdaf0953a164c3e6d7831a39c072e71">MemberDef::reimplementedBy</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a735862f449c091668f1fc86004aab3a2">MemberDef::reimplements</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a3ff39d3acb327553070a64ef0cb321d5">Sequence</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41ac2ba7e785c49050f48da9aacc45c2b85">Service</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a085fea7abdc5d904fe69a3081efd7398">Signal</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a9234cc57c43f272b55a94b0069fe62d1">Slot</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/structs/argument/#a1ad588d2b3cc71fe3f74c8272b4ec32e">Argument::type</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a5fede51b97a819dedf4f83bc2aacbc6a">Typedef</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a0032c6e040cdec6d9c52dc75a790a884">MemberDef::typeString</a>, <a href="/web-doxygen/docs/api/files/src/types-h/#a63e3de542c5d38de617ab78c8c8f5a41a47c14840d8e15331fa420b9b2f757cd9">Variable</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ae450a2be776cc5d05726bab8354f6d62">MemberDef::virtualness</a> and <a href="/web-doxygen/docs/api/classes/argumentlist/#ad03f25174e81a42a617a15195a8867b0">ArgumentList::volatileSpecifier</a>.

Referenced by <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a> and <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a>.
</div>
</div>

### generatePerlModForModule() {#a4d95b912616cab9e00075658e0fa09d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::generatePerlModForModule (const <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> * mod)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01449">1449</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4d95b912616cab9e00075658e0fa09d4">1875</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4d95b912616cab9e00075658e0fa09d4">PerlModGenerator::generatePerlModForModule</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/moduledef">ModuleDef</a> *mod)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained class definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained concept definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + normal members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + location (file_id, line, column)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - exports</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + used files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a>(mod, mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#a58b6c98c1199174f0cb721735c589d67">getMemberGroups</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#aeb422153b08d7da56d56a96acba60370">getClasses</a>().<a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"classes"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#aeb422153b08d7da56d56a96acba60370">getClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1898</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1899</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, cd-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1900</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#ade149e97f8df65bf64a4833caa43c6de">getConcepts</a>().<a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"concepts"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#ade149e97f8df65bf64a4833caa43c6de">getConcepts</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, cd-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1913</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1914</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(mod,mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#a46d36e2cd44ba84b804f14cec1f079c4">getMemberList</a>(MemberListType::DecTypedefMembers()),</span><span class="doxyHighlightStringLiteral">"typedefs"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(mod,mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#a46d36e2cd44ba84b804f14cec1f079c4">getMemberList</a>(MemberListType::DecEnumMembers()),</span><span class="doxyHighlightStringLiteral">"enums"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(mod,mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#a46d36e2cd44ba84b804f14cec1f079c4">getMemberList</a>(MemberListType::DecFuncMembers()),</span><span class="doxyHighlightStringLiteral">"functions"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(mod,mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#a46d36e2cd44ba84b804f14cec1f079c4">getMemberList</a>(MemberListType::DecVarMembers()),</span><span class="doxyHighlightStringLiteral">"variables"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1919</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"brief"</span><span class="doxyHighlight">,mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1920</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"detailed"</span><span class="doxyHighlight">,mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,mod-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1921</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#ac88969f1e19df5e0444bcef41af2ed79">getUsedFiles</a>().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"files"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fd : mod-&gt;<a href="/web-doxygen/docs/api/classes/moduledef/#ac88969f1e19df5e0444bcef41af2ed79">getUsedFiles</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, fd-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::empty</a>, <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>, <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#aeb422153b08d7da56d56a96acba60370">ModuleDef::getClasses</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#ade149e97f8df65bf64a4833caa43c6de">ModuleDef::getConcepts</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#a58b6c98c1199174f0cb721735c589d67">ModuleDef::getMemberGroups</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#a46d36e2cd44ba84b804f14cec1f079c4">ModuleDef::getMemberList</a>, <a href="/web-doxygen/docs/api/classes/moduledef/#ac88969f1e19df5e0444bcef41af2ed79">ModuleDef::getUsedFiles</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.

Referenced by <a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>.
</div>
</div>

### generatePerlModForNamespace() {#a6d79f62a76314d0c65cb976809923d80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::generatePerlModForNamespace (const <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> * nd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01450">1450</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d79f62a76314d0c65cb976809923d80">1935</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6d79f62a76314d0c65cb976809923d80">PerlModGenerator::generatePerlModForNamespace</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/namespacedef">NamespaceDef</a> *nd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained class definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + contained namespace definitions</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + member groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + normal members</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + brief desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + detailed desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + location</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - files containing (parts of) the namespace definition</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip external references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#ad43237a69f056b45fc87beed091688d5">getClasses</a>().<a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"classes"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#ad43237a69f056b45fc87beed091688d5">getClasses</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, cd-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a948889b7a35fb82ebcdf2598a63e1d8d">getNamespaces</a>().<a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"namespaces"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ind : nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a948889b7a35fb82ebcdf2598a63e1d8d">getNamespaces</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">        .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, ind-&gt;name())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">        .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a>(nd, nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#aedf62c808c557f44997b866855615199">getMemberGroups</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(nd,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecDefineMembers()),</span><span class="doxyHighlightStringLiteral">"defines"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(nd,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecProtoMembers()),</span><span class="doxyHighlightStringLiteral">"prototypes"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(nd,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecTypedefMembers()),</span><span class="doxyHighlightStringLiteral">"typedefs"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(nd,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecEnumMembers()),</span><span class="doxyHighlightStringLiteral">"enums"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(nd,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecFuncMembers()),</span><span class="doxyHighlightStringLiteral">"functions"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>(nd,nd-&gt;<a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">getMemberList</a>(MemberListType::DecVarMembers()),</span><span class="doxyHighlightStringLiteral">"variables"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"brief"</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">briefDescription</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"detailed"</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">getDefFileName</a>(),nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">getDefLine</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,nd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/classes/linkedrefmap/#ad4eea714e29d412612981ac2a8bcab40">LinkedRefMap&lt; T, Hash, KeyEqual, Map &gt;::empty</a>, <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>, <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#ad43237a69f056b45fc87beed091688d5">NamespaceDef::getClasses</a>, <a href="/web-doxygen/docs/api/classes/definition/#a33fee836f24f8205eedbd21dd9d282e6">Definition::getDefFileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a47e34774622704853e238ee2e7ef2334">Definition::getDefLine</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#aedf62c808c557f44997b866855615199">NamespaceDef::getMemberGroups</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a2a67c423c453ef9275729a7e9b5b4b07">NamespaceDef::getMemberList</a>, <a href="/web-doxygen/docs/api/classes/namespacedef/#a948889b7a35fb82ebcdf2598a63e1d8d">NamespaceDef::getNamespaces</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.

Referenced by <a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>.
</div>
</div>

### generatePerlModForPage() {#a0151a88e0794af12a9e7932de2d7a928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::generatePerlModForPage (<a href="/web-doxygen/docs/api/classes/pagedef">PageDef</a> * pi)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01453">1453</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0151a88e0794af12a9e7932de2d7a928">2153</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0151a88e0794af12a9e7932de2d7a928">PerlModGenerator::generatePerlModForPage</a>(<a href="/web-doxygen/docs/api/classes/pagedef">PageDef</a> *pd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2154</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2155</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + title</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + documentation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">isReference</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2162</span><span class="doxyLineContent"><span class="doxyHighlight">    .addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"name"</span><span class="doxyHighlight">, pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2164</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si = <a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>().<a href="/web-doxygen/docs/api/classes/linkedmap/#ad7659775b7de962b4fe0921456baf4f4">find</a>(pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2165</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (si)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2166</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"title4"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a747a6ad366ae4d5d42f0c551079d0bf5">filterTitle</a>(si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#ac6aefd1d628bbdb94dc3b8e176a72f9b">title</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2167</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2168</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>,</span><span class="doxyHighlightStringLiteral">"detailed"</span><span class="doxyHighlight">,pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">docFile</a>(),pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">docLine</a>(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">documentation</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2169</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2170</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/classes/definition/#a00915f52f3b708bec07aab2b44f03d34">Definition::docFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#a26a4a6e3578aa6c81b2d6d77a1ce694f">Definition::docLine</a>, <a href="/web-doxygen/docs/api/classes/definition/#abdafb43ac7208aedc3795b02c9b5125a">Definition::documentation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a747a6ad366ae4d5d42f0c551079d0bf5">filterTitle</a>, <a href="/web-doxygen/docs/api/classes/linkedmap/#ad7659775b7de962b4fe0921456baf4f4">LinkedMap&lt; T, Hash, KeyEqual, Map &gt;::find</a>, <a href="/web-doxygen/docs/api/classes/sectionmanager/#afcf31c2b2bad467541c924342b08773d">SectionManager::instance</a>, <a href="/web-doxygen/docs/api/classes/definition/#ae1c69242fea84675cf9a07b0ba22f52f">Definition::isReference</a>, <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="/web-doxygen/docs/api/classes/sectioninfo/#ac6aefd1d628bbdb94dc3b8e176a72f9b">SectionInfo::title</a>.

Referenced by <a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>.
</div>
</div>

### generatePerlModOutput() {#a4c5977a4e048326d58cabd7d348463ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool PerlModGenerator::generatePerlModOutput ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01464">1464</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4c5977a4e048326d58cabd7d348463ea">2172</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4c5977a4e048326d58cabd7d348463ea">PerlModGenerator::generatePerlModOutput</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2173</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream outputFileStream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2175</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>(outputFileStream, <a href="#a32a35dd412f8e42e1f12b671935da576">pathDoxyDocsPM</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2176</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2177</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2178</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/perlmodoutputstream">PerlModOutputStream</a> outputStream(outputFileStream);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.setPerlModOutputStream(&amp;outputStream);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.add(</span><span class="doxyHighlightStringLiteral">"$doxydocs="</span><span class="doxyHighlight">).openHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2181</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2182</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"classes"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2183</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2184</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a44b30742275d27dcfe5eb9ea286af80f">generatePerlModForClass</a>(cd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2185</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2186</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2187</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"concepts"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2188</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a0de9b52b3098ea1a4bee5e248e8287c8">Doxygen::conceptLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2189</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac1f8e6fa454368157eb7cdb564ee6a40">generatePerlModForConcept</a>(cd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2190</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2191</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2192</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"modules"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2193</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="/web-doxygen/docs/api/classes/modulemanager/#a4f48cf5d05907a6acc4b9c6ddec752b7">ModuleManager::instance</a>().modules())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2194</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4d95b912616cab9e00075658e0fa09d4">generatePerlModForModule</a>(mod.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2195</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2196</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2197</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"namespaces"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2199</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6d79f62a76314d0c65cb976809923d80">generatePerlModForNamespace</a>(nd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"files"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fn : *<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2204</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2205</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fd : *fn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2207</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa4d01cc3ff8a727b38849e8efd171be9">generatePerlModForFile</a>(fd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2208</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2209</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2210</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2211</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2212</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"groups"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2213</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;gd : *<a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2214</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2215</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa29eb86a9962f547f8139ff1cfe40b01">generatePerlModForGroup</a>(gd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2219</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"pages"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2220</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pd : *<a href="/web-doxygen/docs/api/classes/doxygen/#abd2756663a014ee48e1660d32a48cac5">Doxygen::pageLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2221</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2222</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0151a88e0794af12a9e7932de2d7a928">generatePerlModForPage</a>(pd.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2223</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2225</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2226</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0151a88e0794af12a9e7932de2d7a928">generatePerlModForPage</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2227</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2228</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2229</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2230</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash().add(</span><span class="doxyHighlightStringLiteral">";\n1;\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2231</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2232</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2233</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a0de9b52b3098ea1a4bee5e248e8287c8">Doxygen::conceptLinkedMap</a>, <a href="#ac12f2a17915bb4023585afb081f7f39a">createOutputFile</a>, <a href="#a44b30742275d27dcfe5eb9ea286af80f">generatePerlModForClass</a>, <a href="#ac1f8e6fa454368157eb7cdb564ee6a40">generatePerlModForConcept</a>, <a href="#aa4d01cc3ff8a727b38849e8efd171be9">generatePerlModForFile</a>, <a href="#aa29eb86a9962f547f8139ff1cfe40b01">generatePerlModForGroup</a>, <a href="#a4d95b912616cab9e00075658e0fa09d4">generatePerlModForModule</a>, <a href="#a6d79f62a76314d0c65cb976809923d80">generatePerlModForNamespace</a>, <a href="#a0151a88e0794af12a9e7932de2d7a928">generatePerlModForPage</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a4f48cf5d05907a6acc4b9c6ddec752b7">ModuleManager::instance</a>, <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#abd2756663a014ee48e1660d32a48cac5">Doxygen::pageLinkedMap</a> and <a href="#a32a35dd412f8e42e1f12b671935da576">pathDoxyDocsPM</a>.

Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>.
</div>
</div>

### generatePerlModSection() {#a33b4ffef65928cbc0b426e79f93334c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::generatePerlModSection (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> * ml, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; header=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01443">1443</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a33b4ffef65928cbc0b426e79f93334c9">1645</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a33b4ffef65928cbc0b426e79f93334c9">PerlModGenerator::generatePerlModSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1646</span><span class="doxyLineContent"><span class="doxyHighlight">                                              <a href="/web-doxygen/docs/api/classes/memberlist">MemberList</a> *ml,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;header)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1647</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1648</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ml==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// empty list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1649</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1650</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1651</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1652</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!header.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1653</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"header"</span><span class="doxyHighlight">, header);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1654</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1655</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"members"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1656</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : *ml)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1657</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1658</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1d2fc28014f00de3422ac4b7a68b868a">generatePerlModForMember</a>(md,d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1659</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1660</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1661</span><span class="doxyLineContent"><span class="doxyHighlight">    .closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1662</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1d2fc28014f00de3422ac4b7a68b868a">generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a>.

Referenced by <a href="#a44b30742275d27dcfe5eb9ea286af80f">generatePerlModForClass</a>, <a href="#aa4d01cc3ff8a727b38849e8efd171be9">generatePerlModForFile</a>, <a href="#aa29eb86a9962f547f8139ff1cfe40b01">generatePerlModForGroup</a>, <a href="#a4d95b912616cab9e00075658e0fa09d4">generatePerlModForModule</a> and <a href="#a6d79f62a76314d0c65cb976809923d80">generatePerlModForNamespace</a>.
</div>
</div>

### generatePerlUserDefinedSection() {#ad9c4e501bf3f834f7fc70de6893b445d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void PerlModGenerator::generatePerlUserDefinedSection (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, const <a href="/web-doxygen/docs/api/classes/membergrouplist">MemberGroupList</a> &amp; mgl)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01442">1442</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad9c4e501bf3f834f7fc70de6893b445d">1689</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad9c4e501bf3f834f7fc70de6893b445d">PerlModGenerator::generatePerlUserDefinedSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/membergrouplist">MemberGroupList</a> &amp;mgl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1690</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1691</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mgl.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1692</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1693</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"user_defined"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1694</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mg : mgl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1695</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1696</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1697</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mg-&gt;header().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1698</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1699</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.addFieldQuotedString(</span><span class="doxyHighlightStringLiteral">"header"</span><span class="doxyHighlight">, mg-&gt;header());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1700</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1701</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1702</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mg-&gt;members().empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1703</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1704</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.openList(</span><span class="doxyHighlightStringLiteral">"members"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1705</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;md : mg-&gt;members())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1706</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1707</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a1d2fc28014f00de3422ac4b7a68b868a">generatePerlModForMember</a>(md, d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1708</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1709</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1710</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1711</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeHash();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1712</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1713</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>.closeList();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1714</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1715</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1d2fc28014f00de3422ac4b7a68b868a">generatePerlModForMember</a> and <a href="#a1570f315b84f678d45d80929fe3af533">m&#95;output</a>.

Referenced by <a href="#a44b30742275d27dcfe5eb9ea286af80f">generatePerlModForClass</a>, <a href="#aa4d01cc3ff8a727b38849e8efd171be9">generatePerlModForFile</a>, <a href="#aa29eb86a9962f547f8139ff1cfe40b01">generatePerlModForGroup</a>, <a href="#a4d95b912616cab9e00075658e0fa09d4">generatePerlModForModule</a> and <a href="#a6d79f62a76314d0c65cb976809923d80">generatePerlModForNamespace</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### m&#95;output {#a1570f315b84f678d45d80929fe3af533}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">PerlModOutput PerlModGenerator::m_output</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01424">1424</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1570f315b84f678d45d80929fe3af533">1424</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/perlmodoutput">PerlModOutput</a> <a href="#a1570f315b84f678d45d80929fe3af533">m_output</a>;</span></span></div>

</div>


Referenced by <a href="#a7b0a42da35d51f4e7f198975258cf9fd">addIncludeInfo</a>, <a href="#a81142c12bb2ef7638500997115bf2f43">addListOfAllMembers</a>, <a href="#a44b30742275d27dcfe5eb9ea286af80f">generatePerlModForClass</a>, <a href="#ac1f8e6fa454368157eb7cdb564ee6a40">generatePerlModForConcept</a>, <a href="#aa4d01cc3ff8a727b38849e8efd171be9">generatePerlModForFile</a>, <a href="#aa29eb86a9962f547f8139ff1cfe40b01">generatePerlModForGroup</a>, <a href="#a1d2fc28014f00de3422ac4b7a68b868a">generatePerlModForMember</a>, <a href="#a4d95b912616cab9e00075658e0fa09d4">generatePerlModForModule</a>, <a href="#a6d79f62a76314d0c65cb976809923d80">generatePerlModForNamespace</a>, <a href="#a0151a88e0794af12a9e7932de2d7a928">generatePerlModForPage</a>, <a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>, <a href="#a33b4ffef65928cbc0b426e79f93334c9">generatePerlModSection</a>, <a href="#ad9c4e501bf3f834f7fc70de6893b445d">generatePerlUserDefinedSection</a> and <a href="#a7473195622dcb57930bbd08c88dd6504">PerlModGenerator</a>.
</div>
</div>

### pathDoxyDocsPM {#a32a35dd412f8e42e1f12b671935da576}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathDoxyDocsPM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01433">1433</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32a35dd412f8e42e1f12b671935da576">1433</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a32a35dd412f8e42e1f12b671935da576">pathDoxyDocsPM</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>, <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a> and <a href="#a4c5977a4e048326d58cabd7d348463ea">generatePerlModOutput</a>.
</div>
</div>

### pathDoxyDocsTex {#a6b90bb007822613373e9a65ff35643c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathDoxyDocsTex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01427">1427</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b90bb007822613373e9a65ff35643c4">1427</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6b90bb007822613373e9a65ff35643c4">pathDoxyDocsTex</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>, <a href="#a2cb28a6f8bf6b9f155d3929b95acf059">generateDoxyLatexTex</a> and <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a>.
</div>
</div>

### pathDoxyFormatTex {#aab3220d2f03ba759c948d8be316d4d2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathDoxyFormatTex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01428">1428</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aab3220d2f03ba759c948d8be316d4d2c">1428</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aab3220d2f03ba759c948d8be316d4d2c">pathDoxyFormatTex</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>, <a href="#a1f0a8822b1895daacce85dd3d93eecac">generateDoxyFormatTex</a> and <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a>.
</div>
</div>

### pathDoxyLatexDVI {#a4b29e2e00432a296288342688354b856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathDoxyLatexDVI</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01430">1430</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4b29e2e00432a296288342688354b856">1430</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4b29e2e00432a296288342688354b856">pathDoxyLatexDVI</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a> and <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a>.
</div>
</div>

### pathDoxyLatexPDF {#aab3b623c4824006226ea5195aec1d8ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathDoxyLatexPDF</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01431">1431</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aab3b623c4824006226ea5195aec1d8ef">1431</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aab3b623c4824006226ea5195aec1d8ef">pathDoxyLatexPDF</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a> and <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a>.
</div>
</div>

### pathDoxyLatexPL {#a23cafbc784eadd8d96ea498c07ee1b22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathDoxyLatexPL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01434">1434</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a23cafbc784eadd8d96ea498c07ee1b22">1434</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a23cafbc784eadd8d96ea498c07ee1b22">pathDoxyLatexPL</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>, <a href="#a999b190603bbc840657ad470a17465ad">generateDoxyLatexPL</a> and <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a>.
</div>
</div>

### pathDoxyLatexStructurePL {#a8dd402f31f1312093ec503a733a5c691}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathDoxyLatexStructurePL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01435">1435</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8dd402f31f1312093ec503a733a5c691">1435</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a8dd402f31f1312093ec503a733a5c691">pathDoxyLatexStructurePL</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>, <a href="#ad03aadb67e05b528cd454bed3bee16b9">generateDoxyLatexStructurePL</a> and <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a>.
</div>
</div>

### pathDoxyLatexTex {#ad2ea9cd9b17663a5b3ff62752031fb2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathDoxyLatexTex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01429">1429</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad2ea9cd9b17663a5b3ff62752031fb2b">1429</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad2ea9cd9b17663a5b3ff62752031fb2b">pathDoxyLatexTex</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>, <a href="#a2cb28a6f8bf6b9f155d3929b95acf059">generateDoxyLatexTex</a> and <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a>.
</div>
</div>

### pathDoxyRules {#a5b043201cbf4b5840582794d44bdcafb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathDoxyRules</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01436">1436</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b043201cbf4b5840582794d44bdcafb">1436</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a5b043201cbf4b5840582794d44bdcafb">pathDoxyRules</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>, <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a> and <a href="#a473b6bd63ac2f9ea9fe6de4f8170194b">generateMakefile</a>.
</div>
</div>

### pathDoxyStructurePM {#a4139ab7ca413fcf7e9d9c10a6abb13f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathDoxyStructurePM</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01426">1426</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4139ab7ca413fcf7e9d9c10a6abb13f2">1426</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4139ab7ca413fcf7e9d9c10a6abb13f2">pathDoxyStructurePM</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>, <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a> and <a href="#a9893c2c270028114dec964284676adc7">generateDoxyStructurePM</a>.
</div>
</div>

### pathDoxyStructureTex {#a240a78f6c0326286469e17febcb3e386}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathDoxyStructureTex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01432">1432</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a240a78f6c0326286469e17febcb3e386">1432</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a240a78f6c0326286469e17febcb3e386">pathDoxyStructureTex</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a>, <a href="#a1f0a8822b1895daacce85dd3d93eecac">generateDoxyFormatTex</a> and <a href="#a72b6d57151d45a13c60402914aa50831">generateDoxyRules</a>.
</div>
</div>

### pathMakefile {#a2a2147107f3c1812beb023cb68a10c55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString PerlModGenerator::pathMakefile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#l01437">1437</a> of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a2147107f3c1812beb023cb68a10c55">1437</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a2a2147107f3c1812beb023cb68a10c55">pathMakefile</a>;</span></span></div>

</div>


Referenced by <a href="#af6bb93beb1eac9b861832d368ffad291">generate</a> and <a href="#a473b6bd63ac2f9ea9fe6de4f8170194b">generateMakefile</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
