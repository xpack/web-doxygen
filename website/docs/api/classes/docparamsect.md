---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/docparamsect
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DocParamSect` Class Reference

<p>Node representing a parameter section. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocParamSect { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docnode-h">src/docnode.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/doccompoundnode">DocCompoundNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for nodes with children. <a href="/web-doxygen/docs/api/classes/doccompoundnode/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Type { <a href="#a402e8723e8b9f22c5ffa84046224d51a">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Direction { <a href="#ad5e3f053f03f8c333a69208521075c66">...</a> }</td>
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

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d559bee17ecf9f9dc8f39029d78e567">DocParamList</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8094f46edf9a15bf043f5e096124ce61">DocParamSect</a> (DocParser *parser, DocNodeVariant *parent, Type t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab528e49d6e133ca42c29bb46bdc3cbec">parse</a> (const QCString &amp;cmdName, bool xmlContext, Direction d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a402e8723e8b9f22c5ffa84046224d51a">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcb0666a1b93ac69a56ab22179827d8a">type</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ec7b05c44ebac263741f2983cb4f6b3">hasInOutSpecifier</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae994d0e9cc1d360aaa8d653042c929af">hasTypeSpecifier</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a402e8723e8b9f22c5ffa84046224d51a">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42220dd155f6929c22966f9a96aec98e">m_type</a> = <a href="#a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e">Unknown</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd75ddc903e44ff36d8543f34d8117d6">m_hasInOutSpecifier</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f8e98501e23cfb987ff940194ca745">m_hasTypeSpecifier</a> = false</td>
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

<p>Node representing a parameter section.</p>

<p>Definition at line 1052 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### Direction {#ad5e3f053f03f8c333a69208521075c66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum DocParamSect::Direction </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">In<a id="ad5e3f053f03f8c333a69208521075c66a91340ac3497abe40521ff1032d14f260"></a></td>
<td class="doxyEnumItemDescription"><p> (=1)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Out<a id="ad5e3f053f03f8c333a69208521075c66a6f4ea16fe4731fee90a5ed69933b34e5"></a></td>
<td class="doxyEnumItemDescription"><p> (=2)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">InOut<a id="ad5e3f053f03f8c333a69208521075c66aa67a43fd4af2659272f549f379472ff6"></a></td>
<td class="doxyEnumItemDescription"><p> (=3)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unspecified<a id="ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5"></a></td>
<td class="doxyEnumItemDescription"><p> (=0)</p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1060 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5e3f053f03f8c333a69208521075c66a91340ac3497abe40521ff1032d14f260">1062</a></span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="#ad5e3f053f03f8c333a69208521075c66a91340ac3497abe40521ff1032d14f260">In</a>=1, <a href="#ad5e3f053f03f8c333a69208521075c66a6f4ea16fe4731fee90a5ed69933b34e5">Out</a>=2, <a href="#ad5e3f053f03f8c333a69208521075c66aa67a43fd4af2659272f549f379472ff6">InOut</a>=3, <a href="#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">Unspecified</a>=0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

### Type {#a402e8723e8b9f22c5ffa84046224d51a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum DocParamSect::Type </td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Unknown<a id="a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Param<a id="a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">RetVal<a id="a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Exception<a id="a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TemplateParam<a id="a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1056 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">1058</a></span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="#a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e">Unknown</a>, <a href="#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">Param</a>, <a href="#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">RetVal</a>, <a href="#a402e8723e8b9f22c5ffa84046224d51aab35f5129b2fc6fa21358b0d1f1e8ac48">Exception</a>, <a href="#a402e8723e8b9f22c5ffa84046224d51aa171c52c00ef0e893e8622dcf37db20e0">TemplateParam</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Friends

### DocParamList {#a8d559bee17ecf9f9dc8f39029d78e567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class <a href="/web-doxygen/docs/api/classes/docparamlist">DocParamList</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Definition at line 1054 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8d559bee17ecf9f9dc8f39029d78e567">1054</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight"><a href="#a8d559bee17ecf9f9dc8f39029d78e567">DocParamList</a>;</span></span></div>

</div>


Reference <a href="#a8d559bee17ecf9f9dc8f39029d78e567">DocParamList</a>.

Referenced by <a href="#a8d559bee17ecf9f9dc8f39029d78e567">DocParamList</a> and <a href="#ab528e49d6e133ca42c29bb46bdc3cbec">parse</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DocParamSect() {#a8094f46edf9a15bf043f5e096124ce61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocParamSect::DocParamSect (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="#a402e8723e8b9f22c5ffa84046224d51a">Type</a> t)</td>
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


<p>Definition at line 1064 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8094f46edf9a15bf043f5e096124ce61">1064</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8094f46edf9a15bf043f5e096124ce61">DocParamSect</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,<a href="#a402e8723e8b9f22c5ffa84046224d51a">Type</a> t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#a42220dd155f6929c22966f9a96aec98e">m_type</a>(t), <a href="#abd75ddc903e44ff36d8543f34d8117d6">m_hasInOutSpecifier</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>), <a href="#ab0f8e98501e23cfb987ff940194ca745">m_hasTypeSpecifier</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">    {}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode::DocCompoundNode</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#abd75ddc903e44ff36d8543f34d8117d6">m&#95;hasInOutSpecifier</a>, <a href="#ab0f8e98501e23cfb987ff940194ca745">m&#95;hasTypeSpecifier</a>, <a href="#a42220dd155f6929c22966f9a96aec98e">m&#95;type</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### hasInOutSpecifier() {#a7ec7b05c44ebac263741f2983cb4f6b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParamSect::hasInOutSpecifier ()</td>
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


<p>Definition at line 1069 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7ec7b05c44ebac263741f2983cb4f6b3">1069</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a7ec7b05c44ebac263741f2983cb4f6b3">hasInOutSpecifier</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#abd75ddc903e44ff36d8543f34d8117d6">m_hasInOutSpecifier</a>; }</span></span></div>

</div>


Reference <a href="#abd75ddc903e44ff36d8543f34d8117d6">m&#95;hasInOutSpecifier</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a85d9cb1979f0d09164d205bfd447b494">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#acfb18992e55be4c79b5dad6a8b8ae4b7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a5c64416b51edb6f80d0be604b4cbe0b3">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a806029951b075fcd8c430498bd0f2375">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aca420728eca4e37947593db6a96eadd3">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#adf7a140e70ce68021f8b0acf881e96af">PerlModDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aeb7edc62cad5a541849845d2bfe030e9">RTFDocVisitor::operator()</a>.
</div>
</div>

### hasTypeSpecifier() {#ae994d0e9cc1d360aaa8d653042c929af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParamSect::hasTypeSpecifier ()</td>
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


<p>Definition at line 1070 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae994d0e9cc1d360aaa8d653042c929af">1070</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae994d0e9cc1d360aaa8d653042c929af">hasTypeSpecifier</a>()</span><span class="doxyHighlightKeyword"> const  </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab0f8e98501e23cfb987ff940194ca745">m_hasTypeSpecifier</a>; }</span></span></div>

</div>


Reference <a href="#ab0f8e98501e23cfb987ff940194ca745">m&#95;hasTypeSpecifier</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a85d9cb1979f0d09164d205bfd447b494">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#acfb18992e55be4c79b5dad6a8b8ae4b7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a5c64416b51edb6f80d0be604b4cbe0b3">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a806029951b075fcd8c430498bd0f2375">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aca420728eca4e37947593db6a96eadd3">LatexDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aeb7edc62cad5a541849845d2bfe030e9">RTFDocVisitor::operator()</a>.
</div>
</div>

### parse() {#ab528e49d6e133ca42c29bb46bdc3cbec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocParamSect::parse (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; cmdName, bool xmlContext, <a href="#ad5e3f053f03f8c333a69208521075c66">Direction</a> d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 1067 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 3295 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab528e49d6e133ca42c29bb46bdc3cbec">3295</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#ab528e49d6e133ca42c29bb46bdc3cbec">DocParamSect::parse</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;cmdName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> xmlContext, <a href="#ad5e3f053f03f8c333a69208521075c66">Direction</a> d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3296</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3297</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3298</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> retval = Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3299</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3300</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3301</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d!=<a href="#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">Unspecified</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3302</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3303</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#abd75ddc903e44ff36d8543f34d8117d6">m_hasInOutSpecifier</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3304</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3305</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3306</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().empty() &amp;&amp; std::holds_alternative&lt;DocParamList&gt;(<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().back()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3307</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3308</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8d559bee17ecf9f9dc8f39029d78e567">DocParamList</a> &amp;lastPl = std::get&lt;DocParamList&gt;(<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().back());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3309</span><span class="doxyLineContent"><span class="doxyHighlight">    lastPl.<a href="/web-doxygen/docs/api/classes/docparamlist/#a89fc37af294659364193e14680065668">markLast</a>(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3310</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3311</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> markFirst = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3312</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="#a8d559bee17ecf9f9dc8f39029d78e567">DocParamList</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="#a42220dd155f6929c22966f9a96aec98e">m_type</a>,d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3313</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8d559bee17ecf9f9dc8f39029d78e567">DocParamList</a> *pl = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="#a8d559bee17ecf9f9dc8f39029d78e567">DocParamList</a>&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3314</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (markFirst)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3315</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3316</span><span class="doxyLineContent"><span class="doxyHighlight">    pl-&gt;markFirst();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3317</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3318</span><span class="doxyLineContent"><span class="doxyHighlight">  pl-&gt;markLast();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3319</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (xmlContext)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3320</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3321</span><span class="doxyLineContent"><span class="doxyHighlight">    retval = pl-&gt;parseXml(cmdName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3322</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3323</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3324</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3325</span><span class="doxyLineContent"><span class="doxyHighlight">    retval = pl-&gt;parse(cmdName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3326</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3327</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::RetVal_EndParBlock))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3328</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3329</span><span class="doxyLineContent"><span class="doxyHighlight">    retval = Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3330</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3331</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3332</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"retval={}"</span><span class="doxyHighlight">,retval.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3333</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3334</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO&#95;TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO&#95;TRACE&#95;EXIT</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="#a8d559bee17ecf9f9dc8f39029d78e567">DocParamList</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get&#95;last</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="#abd75ddc903e44ff36d8543f34d8117d6">m&#95;hasInOutSpecifier</a>, <a href="#a42220dd155f6929c22966f9a96aec98e">m&#95;type</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a89fc37af294659364193e14680065668">DocParamList::markLast</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to&#95;string</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">Unspecified</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a474887b8878a41eb2abf8ab378b6e847">DocPara::handleParamSection</a>.
</div>
</div>

### type() {#afcb0666a1b93ac69a56ab22179827d8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type DocParamSect::type ()</td>
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


<p>Definition at line 1068 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afcb0666a1b93ac69a56ab22179827d8a">1068</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a402e8723e8b9f22c5ffa84046224d51a">Type</a> <a href="#afcb0666a1b93ac69a56ab22179827d8a">type</a>()</span><span class="doxyHighlightKeyword"> const          </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a42220dd155f6929c22966f9a96aec98e">m_type</a>; }</span></span></div>

</div>


Reference <a href="#a42220dd155f6929c22966f9a96aec98e">m&#95;type</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a474887b8878a41eb2abf8ab378b6e847">DocPara::handleParamSection</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#acfb18992e55be4c79b5dad6a8b8ae4b7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a68b868964920e8b88745139cec6789d5">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a806029951b075fcd8c430498bd0f2375">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aca420728eca4e37947593db6a96eadd3">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#af21bb817afa0823ea94983a1d86aea4b">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#abd6ed30171b50ea9f86441b3327069e7">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a6a1887d8cac48132d1f0b4db97d4f9e8">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aeb7edc62cad5a541849845d2bfe030e9">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a6f4df2c3160f09e662393e6a23b2add0">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a8613537dce42682e941104234d73477c">XmlDocVisitor::operator()</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;hasInOutSpecifier {#abd75ddc903e44ff36d8543f34d8117d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParamSect::m_hasInOutSpecifier = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1074 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd75ddc903e44ff36d8543f34d8117d6">1074</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">            <a href="#abd75ddc903e44ff36d8543f34d8117d6">m_hasInOutSpecifier</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a8094f46edf9a15bf043f5e096124ce61">DocParamSect</a>, <a href="#a7ec7b05c44ebac263741f2983cb4f6b3">hasInOutSpecifier</a> and <a href="#ab528e49d6e133ca42c29bb46bdc3cbec">parse</a>.
</div>
</div>

### m&#95;hasTypeSpecifier {#ab0f8e98501e23cfb987ff940194ca745}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParamSect::m_hasTypeSpecifier = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1075 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab0f8e98501e23cfb987ff940194ca745">1075</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">            <a href="#ab0f8e98501e23cfb987ff940194ca745">m_hasTypeSpecifier</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a8094f46edf9a15bf043f5e096124ce61">DocParamSect</a> and <a href="#ae994d0e9cc1d360aaa8d653042c929af">hasTypeSpecifier</a>.
</div>
</div>

### m&#95;type {#a42220dd155f6929c22966f9a96aec98e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type DocParamSect::m_type = <a href="#a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e">Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 1073 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a42220dd155f6929c22966f9a96aec98e">1073</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a402e8723e8b9f22c5ffa84046224d51a">Type</a>            <a href="#a42220dd155f6929c22966f9a96aec98e">m_type</a> = <a href="#a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e">Unknown</a>;</span></span></div>

</div>


Referenced by <a href="#a8094f46edf9a15bf043f5e096124ce61">DocParamSect</a>, <a href="#ab528e49d6e133ca42c29bb46bdc3cbec">parse</a> and <a href="#afcb0666a1b93ac69a56ab22179827d8a">type</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
