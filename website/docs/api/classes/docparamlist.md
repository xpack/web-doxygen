---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/docparamlist
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DocParamList` Class Reference

<p>Node representing a parameter list. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocParamList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docnode-h">src/docnode.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docnode">DocNode</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract node interface with type information. <a href="/web-doxygen/docs/api/classes/docnode/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c7cdfadcf9d06435cd7979423f3c0bf">DocParamList</a> (DocParser *parser, DocNodeVariant *parent, DocParamSect::Type t, DocParamSect::Direction d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a543cac8da19b4edaa5eb0c7deeba2455">parameters</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66138e258fb9547bd85e0b9227c48ebf">paramTypes</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea61e6129350589c862ceb0f75d5f9a9">paragraphs</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51a">DocParamSect::Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c795a79c11468fb1d8ce3dab41534f3">type</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66">DocParamSect::Direction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac45275b55efab9d6a60049f6d6dc7679">direction</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b3e3e25859cc2d76b312b988c018d08">markFirst</a> (bool b=TRUE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a89fc37af294659364193e14680065668">markLast</a> (bool b=TRUE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60ad28c13ad20d76776a6bacd3b3a412">isFirst</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96270035f29eb07f50ed8c0c2acda9d3">isLast</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98345755b6311bcc4129bd7ee14759f1">parse</a> (const QCString &amp;cmdName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/token">Token</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79bb36905dd1401288d55e12ee52ce03">parseXml</a> (const QCString &amp;paramName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbc8c94fc05d08e05dd38f339f0a18dd">m_params</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04a43c0f053845ea8769259804b670d1">m_paramTypes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51a">DocParamSect::Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab173b0e7740af58cde5390629aa93851">m_type</a> = <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e">DocParamSect::Unknown</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66">DocParamSect::Direction</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1501c1d30e2e09f8740c6050b0206451">m_dir</a> = <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">DocParamSect::Unspecified</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a117da8d395edd77c1cfcf9840c77603c">m_isFirst</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9884c71ca8b75cec15a9cc4b2fe525ae">m_isLast</a> = false</td>
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

<p>Node representing a parameter list.</p>

<p>Definition at line 1124 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### DocParamList() {#a9c7cdfadcf9d06435cd7979423f3c0bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocParamList::DocParamList (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51a">DocParamSect::Type</a> t, <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66">DocParamSect::Direction</a> d)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01127">1127</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c7cdfadcf9d06435cd7979423f3c0bf">1127</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9c7cdfadcf9d06435cd7979423f3c0bf">DocParamList</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51a">DocParamSect::Type</a> t,<a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66">DocParamSect::Direction</a> d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#ab173b0e7740af58cde5390629aa93851">m_type</a>(t), <a href="#a1501c1d30e2e09f8740c6050b0206451">m_dir</a>(d) {}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/docnode/#a12e0244788c1b56cb307517cb8d9d96f">DocNode::DocNode</a>, <a href="#a1501c1d30e2e09f8740c6050b0206451">m&#95;dir</a>, <a href="#ab173b0e7740af58cde5390629aa93851">m&#95;type</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### direction() {#ac45275b55efab9d6a60049f6d6dc7679}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocParamSect::Direction DocParamList::direction ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01133">1133</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac45275b55efab9d6a60049f6d6dc7679">1133</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66">DocParamSect::Direction</a> <a href="#ac45275b55efab9d6a60049f6d6dc7679">direction</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1501c1d30e2e09f8740c6050b0206451">m_dir</a>; }</span></span></div>

</div>


Reference <a href="#a1501c1d30e2e09f8740c6050b0206451">m&#95;dir</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a85d9cb1979f0d09164d205bfd447b494">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a5c64416b51edb6f80d0be604b4cbe0b3">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a806029951b075fcd8c430498bd0f2375">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#adf7a140e70ce68021f8b0acf881e96af">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aeb7edc62cad5a541849845d2bfe030e9">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a4ff7d5a66db3412ce103eeb44fee565c">XmlDocVisitor::operator()</a>.
</div>
</div>

### isFirst() {#a60ad28c13ad20d76776a6bacd3b3a412}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParamList::isFirst ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01136">1136</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60ad28c13ad20d76776a6bacd3b3a412">1136</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a60ad28c13ad20d76776a6bacd3b3a412">isFirst</a>()</span><span class="doxyHighlightKeyword"> const            </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a117da8d395edd77c1cfcf9840c77603c">m_isFirst</a>; }</span></span></div>

</div>


Reference <a href="#a117da8d395edd77c1cfcf9840c77603c">m&#95;isFirst</a>.
</div>
</div>

### isLast() {#a96270035f29eb07f50ed8c0c2acda9d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParamList::isLast ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01137">1137</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a96270035f29eb07f50ed8c0c2acda9d3">1137</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a96270035f29eb07f50ed8c0c2acda9d3">isLast</a>()</span><span class="doxyHighlightKeyword"> const             </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a9884c71ca8b75cec15a9cc4b2fe525ae">m_isLast</a>; }</span></span></div>

</div>


Reference <a href="#a9884c71ca8b75cec15a9cc4b2fe525ae">m&#95;isLast</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a9becdb1d4b3096f9081710f0c6c14e80">ManDocVisitor::operator()</a>.
</div>
</div>

### markFirst() {#a6b3e3e25859cc2d76b312b988c018d08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParamList::markFirst (bool b=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01134">1134</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b3e3e25859cc2d76b312b988c018d08">1134</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6b3e3e25859cc2d76b312b988c018d08">markFirst</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)     { <a href="#a117da8d395edd77c1cfcf9840c77603c">m_isFirst</a>=b; }</span></span></div>

</div>


References <a href="#a117da8d395edd77c1cfcf9840c77603c">m&#95;isFirst</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a79bb36905dd1401288d55e12ee52ce03">parseXml</a>.
</div>
</div>

### markLast() {#a89fc37af294659364193e14680065668}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocParamList::markLast (bool b=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01135">1135</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a89fc37af294659364193e14680065668">1135</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a89fc37af294659364193e14680065668">markLast</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)      { <a href="#a9884c71ca8b75cec15a9cc4b2fe525ae">m_isLast</a>=b; }</span></span></div>

</div>


References <a href="#a9884c71ca8b75cec15a9cc4b2fe525ae">m&#95;isLast</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docparamsect/#ab528e49d6e133ca42c29bb46bdc3cbec">DocParamSect::parse</a> and <a href="#a79bb36905dd1401288d55e12ee52ce03">parseXml</a>.
</div>
</div>

### paragraphs() {#aea61e6129350589c862ceb0f75d5f9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DocNodeList &amp; DocParamList::paragraphs ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01131">1131</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aea61e6129350589c862ceb0f75d5f9a9">1131</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;<a href="#aea61e6129350589c862ceb0f75d5f9a9">paragraphs</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a>; }</span></span></div>

</div>


Reference <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m&#95;paragraphs</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a85d9cb1979f0d09164d205bfd447b494">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a5c64416b51edb6f80d0be604b4cbe0b3">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a806029951b075fcd8c430498bd0f2375">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a9becdb1d4b3096f9081710f0c6c14e80">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#adf7a140e70ce68021f8b0acf881e96af">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aeb7edc62cad5a541849845d2bfe030e9">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a4ff7d5a66db3412ce103eeb44fee565c">XmlDocVisitor::operator()</a>.
</div>
</div>

### parameters() {#a543cac8da19b4edaa5eb0c7deeba2455}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DocNodeList &amp; DocParamList::parameters ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01129">1129</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a543cac8da19b4edaa5eb0c7deeba2455">1129</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;<a href="#a543cac8da19b4edaa5eb0c7deeba2455">parameters</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acbc8c94fc05d08e05dd38f339f0a18dd">m_params</a>; }</span></span></div>

</div>


Reference <a href="#acbc8c94fc05d08e05dd38f339f0a18dd">m&#95;params</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a85d9cb1979f0d09164d205bfd447b494">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a5c64416b51edb6f80d0be604b4cbe0b3">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a806029951b075fcd8c430498bd0f2375">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a9becdb1d4b3096f9081710f0c6c14e80">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#adf7a140e70ce68021f8b0acf881e96af">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a3ad488448307ccde3303915e92c56a69">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aeb7edc62cad5a541849845d2bfe030e9">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a4ff7d5a66db3412ce103eeb44fee565c">XmlDocVisitor::operator()</a>.
</div>
</div>

### paramTypes() {#a66138e258fb9547bd85e0b9227c48ebf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DocNodeList &amp; DocParamList::paramTypes ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01130">1130</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a66138e258fb9547bd85e0b9227c48ebf">1130</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a> &amp;<a href="#a66138e258fb9547bd85e0b9227c48ebf">paramTypes</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a04a43c0f053845ea8769259804b670d1">m_paramTypes</a>; }</span></span></div>

</div>


Reference <a href="#a04a43c0f053845ea8769259804b670d1">m&#95;paramTypes</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a85d9cb1979f0d09164d205bfd447b494">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a5c64416b51edb6f80d0be604b4cbe0b3">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a806029951b075fcd8c430498bd0f2375">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aeb7edc62cad5a541849845d2bfe030e9">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a4ff7d5a66db3412ce103eeb44fee565c">XmlDocVisitor::operator()</a>.
</div>
</div>

### parse() {#a98345755b6311bcc4129bd7ee14759f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocParamList::parse (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; cmdName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01138">1138</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#l03148">3148</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a98345755b6311bcc4129bd7ee14759f1">3148</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;cmdName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3149</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3150</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3151</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> retval = Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3152</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3153</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> *par=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3154</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> saveCmdName = cmdName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3155</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3156</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> tok=<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WHITESPACE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3158</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3159</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"expected whitespace after \\{} command"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3160</span><span class="doxyLineContent"><span class="doxyHighlight">        saveCmdName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3161</span><span class="doxyLineContent"><span class="doxyHighlight">    retval = Token::make_RetVal_EndParBlock();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3162</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> endparamlist;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3163</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3164</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a5b84c53eb58ffa4536429f435af7dc7e">setStateParam</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3165</span><span class="doxyLineContent"><span class="doxyHighlight">  tok=<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3166</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WORD)) </span><span class="doxyHighlightComment">/* there is a parameter name */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3167</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3168</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab173b0e7740af58cde5390629aa93851">m_type</a>==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3169</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3170</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> typeSeparator = <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#ad01df4cf228c63091fd14007b7331b8e">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// explicit type position</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3171</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (typeSeparator!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3172</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3173</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a367fe5ccd7e0378c2e5c94df6e60dd0d">handleParameterType</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="#a04a43c0f053845ea8769259804b670d1">m_paramTypes</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name.left(typeSeparator));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3174</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#ad01df4cf228c63091fd14007b7331b8e">name</a> = <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#ad01df4cf228c63091fd14007b7331b8e">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(typeSeparator+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3175</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">hasParamCommand</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3176</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">checkArgumentName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3177</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>() &amp;&amp; std::holds_alternative&lt;DocParamSect&gt;(*<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3178</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3179</span><span class="doxyLineContent"><span class="doxyHighlight">          std::get&lt;DocParamSect&gt;(*<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>()).m_hasTypeSpecifier=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3180</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3181</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3182</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3183</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3184</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">hasParamCommand</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3185</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">checkArgumentName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3186</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3187</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3188</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab173b0e7740af58cde5390629aa93851">m_type</a>==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3189</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3190</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ae20ce1c3e50ef1b4399b50f29f61607f">hasReturnCommand</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3191</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a3fce1509c4bb1494537fe53ea294fa8c">checkRetvalName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3192</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3193</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//m_params.append(parser()-&gt;context.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3194</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="#acbc8c94fc05d08e05dd38f339f0a18dd">m_params</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3195</span><span class="doxyLineContent"><span class="doxyHighlight">    tok=<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">lex</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3196</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3197</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#ae3c97a1c50f2345ed8a821b064752e4c">setStatePara</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (tok.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF)) </span><span class="doxyHighlightComment">// premature end of comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3199</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3200</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"unexpected end of comment block while parsing the "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3201</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"argument of command {}"</span><span class="doxyHighlight">,saveCmdName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3202</span><span class="doxyLineContent"><span class="doxyHighlight">    retval = Token::make_RetVal_EndParBlock();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3203</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> endparamlist;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3204</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_WHITESPACE)) </span><span class="doxyHighlightComment">/* premature end of comment block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3206</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3207</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tok.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::TK_NEWPARA)) </span><span class="doxyHighlightComment">/* empty param description */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3208</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3209</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"unexpected token {} in comment block while parsing the "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3210</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"argument of command {}"</span><span class="doxyHighlight">,tok.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>(),saveCmdName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3211</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3212</span><span class="doxyLineContent"><span class="doxyHighlight">    retval = Token::make_RetVal_EndParBlock();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3213</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">goto</span><span class="doxyHighlight"> endparamlist;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3214</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3215</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3216</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a>.append&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3217</span><span class="doxyLineContent"><span class="doxyHighlight">  par = <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a>.get_last&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3218</span><span class="doxyLineContent"><span class="doxyHighlight">  retval = par-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">parse</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3219</span><span class="doxyLineContent"><span class="doxyHighlight">  par-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#a849868e81af1e2ae0da511fa3e5a91b8">markFirst</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3220</span><span class="doxyLineContent"><span class="doxyHighlight">  par-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">markLast</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3221</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3222</span><span class="doxyLineContent"><span class="doxyHighlight">endparamlist:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3223</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"retval={}"</span><span class="doxyHighlight">,retval.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3225</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO&#95;TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO&#95;TRACE&#95;EXIT</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3fce1509c4bb1494537fe53ea294fa8c">DocParser::checkRetvalName</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a367fe5ccd7e0378c2e5c94df6e60dd0d">DocParser::handleParameterType</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">DocParserContext::hasParamCommand</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ae20ce1c3e50ef1b4399b50f29f61607f">DocParserContext::hasReturnCommand</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is&#95;any&#95;of</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a286239d4401fbbfb8b183a7e9c521866">DocTokenizer::lex</a>, <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m&#95;paragraphs</a>, <a href="#acbc8c94fc05d08e05dd38f339f0a18dd">m&#95;params</a>, <a href="#a04a43c0f053845ea8769259804b670d1">m&#95;paramTypes</a>, <a href="#ab173b0e7740af58cde5390629aa93851">m&#95;type</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a849868e81af1e2ae0da511fa3e5a91b8">DocPara::markFirst</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">DocPara::markLast</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/structs/tokeninfo/#ad01df4cf228c63091fd14007b7331b8e">TokenInfo::name</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aafc94d2ed7856e4a11e404e2ee05fb40">DocPara::parse</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#ae3c97a1c50f2345ed8a821b064752e4c">DocTokenizer::setStatePara</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a5b84c53eb58ffa4536429f435af7dc7e">DocTokenizer::setStateParam</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to&#95;string</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn&#95;doc&#95;error</a>.
</div>
</div>

### parseXml() {#a79bb36905dd1401288d55e12ee52ce03}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocParamList::parseXml (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; paramName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01139">1139</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#l03227">3227</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a79bb36905dd1401288d55e12ee52ce03">3227</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;paramName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3228</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3229</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3230</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> retval = Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3231</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3232</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3233</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#ad01df4cf228c63091fd14007b7331b8e">name</a> = paramName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3234</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab173b0e7740af58cde5390629aa93851">m_type</a>==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3235</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3236</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">hasParamCommand</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3237</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">checkArgumentName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3238</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3239</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab173b0e7740af58cde5390629aa93851">m_type</a>==<a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3240</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3241</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ae20ce1c3e50ef1b4399b50f29f61607f">hasReturnCommand</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3242</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a3fce1509c4bb1494537fe53ea294fa8c">checkRetvalName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3243</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3244</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3245</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">handleLinkedWord</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="#acbc8c94fc05d08e05dd38f339f0a18dd">m_params</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3246</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3247</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">do</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3248</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3249</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a>.append&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3250</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> *par =  <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a>.get_last&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3251</span><span class="doxyLineContent"><span class="doxyHighlight">    retval = par-&gt;parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (par-&gt;isEmpty()) </span><span class="doxyHighlightComment">// avoid adding an empty paragraph for the whitespace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3253</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightComment">// after &lt;/para&gt; and before &lt;/param&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3254</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3255</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a>.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3256</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3257</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3258</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// append the paragraph to the list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3259</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3260</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3261</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3262</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a>.get_last&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;()-&gt;<a href="#a89fc37af294659364193e14680065668">markLast</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3263</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3264</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6b3e3e25859cc2d76b312b988c018d08">markFirst</a> = <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a>.empty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3265</span><span class="doxyLineContent"><span class="doxyHighlight">      par = &amp;std::get&lt;DocPara&gt;(<a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a>.back());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3266</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6b3e3e25859cc2d76b312b988c018d08">markFirst</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3267</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3268</span><span class="doxyLineContent"><span class="doxyHighlight">        par-&gt;markFirst();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3269</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3270</span><span class="doxyLineContent"><span class="doxyHighlight">      par-&gt;markLast();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3271</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3272</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3273</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retval.is_any_of(TokenRetval::TK_NONE,TokenRetval::TK_EOF)) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3274</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3275</span><span class="doxyLineContent"><span class="doxyHighlight">  } </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::RetVal_CloseXml) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3276</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>-&gt;map(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name)!=<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273aad530a000140559dd09d6d3e2d0aa9f2">HtmlTagType::XML_PARAM</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3277</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>-&gt;map(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name)!=<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a1056e17a54837e4e4c9897c32a9290fd">HtmlTagType::XML_TYPEPARAM</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3278</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>-&gt;map(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name)!=<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a422227202d96b7b5aedcb1b4f3766d03">HtmlTagType::XML_EXCEPTION</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3279</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3280</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF)) </span><span class="doxyHighlightComment">/* premature end of comment block */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3281</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3282</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn_doc_error</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.fileName,<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;tokenizer.getLineNr(),</span><span class="doxyHighlightStringLiteral">"unterminated param or exception tag"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3283</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3284</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3285</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3286</span><span class="doxyLineContent"><span class="doxyHighlight">    retval = Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3287</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3288</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3289</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"retval={}"</span><span class="doxyHighlight">,retval.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3290</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3291</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO&#95;TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO&#95;TRACE&#95;EXIT</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3fce1509c4bb1494537fe53ea294fa8c">DocParser::checkRetvalName</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">DocParserContext::hasParamCommand</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ae20ce1c3e50ef1b4399b50f29f61607f">DocParserContext::hasReturnCommand</a>, <a href="/web-doxygen/docs/api/namespaces/mappers/#a8390ce8e78c02d974d515d560a551958">Mappers::htmlTagMapper</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is&#95;any&#95;of</a>, <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m&#95;paragraphs</a>, <a href="#acbc8c94fc05d08e05dd38f339f0a18dd">m&#95;params</a>, <a href="#ab173b0e7740af58cde5390629aa93851">m&#95;type</a>, <a href="#a6b3e3e25859cc2d76b312b988c018d08">markFirst</a>, <a href="#a89fc37af294659364193e14680065668">markLast</a>, <a href="/web-doxygen/docs/api/structs/tokeninfo/#ad01df4cf228c63091fd14007b7331b8e">TokenInfo::name</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aadd6d8ac7d3bbca9c02eeaf0667dc898d">DocParamSect::Param</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aad057fa7d7e908eb6f2aab26e1c9cd7ca">DocParamSect::RetVal</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>, <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to&#95;string</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#affeb66895cdcfb6b1eb0eba2daafba89">warn&#95;doc&#95;error</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a422227202d96b7b5aedcb1b4f3766d03">XML&#95;EXCEPTION</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273aad530a000140559dd09d6d3e2d0aa9f2">XML&#95;PARAM</a> and <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a91be16b8342aa3130a4374d78cf42273a1056e17a54837e4e4c9897c32a9290fd">XML&#95;TYPEPARAM</a>.
</div>
</div>

### type() {#a6c795a79c11468fb1d8ce3dab41534f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocParamSect::Type DocParamList::type ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01132">1132</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c795a79c11468fb1d8ce3dab41534f3">1132</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51a">DocParamSect::Type</a> <a href="#a6c795a79c11468fb1d8ce3dab41534f3">type</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab173b0e7740af58cde5390629aa93851">m_type</a>; }</span></span></div>

</div>


Reference <a href="#ab173b0e7740af58cde5390629aa93851">m&#95;type</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;dir {#a1501c1d30e2e09f8740c6050b0206451}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocParamSect::Direction DocParamList::m_dir = <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">DocParamSect::Unspecified</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01146">1146</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1501c1d30e2e09f8740c6050b0206451">1146</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66">DocParamSect::Direction</a> <a href="#a1501c1d30e2e09f8740c6050b0206451">m_dir</a> = <a href="/web-doxygen/docs/api/classes/docparamsect/#ad5e3f053f03f8c333a69208521075c66ab10385814739b43cf57af1d841b821c5">DocParamSect::Unspecified</a>;</span></span></div>

</div>


Referenced by <a href="#ac45275b55efab9d6a60049f6d6dc7679">direction</a> and <a href="#a9c7cdfadcf9d06435cd7979423f3c0bf">DocParamList</a>.
</div>
</div>

### m&#95;isFirst {#a117da8d395edd77c1cfcf9840c77603c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParamList::m_isFirst = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01147">1147</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a117da8d395edd77c1cfcf9840c77603c">1147</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">                    <a href="#a117da8d395edd77c1cfcf9840c77603c">m_isFirst</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a60ad28c13ad20d76776a6bacd3b3a412">isFirst</a> and <a href="#a6b3e3e25859cc2d76b312b988c018d08">markFirst</a>.
</div>
</div>

### m&#95;isLast {#a9884c71ca8b75cec15a9cc4b2fe525ae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocParamList::m_isLast = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01148">1148</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9884c71ca8b75cec15a9cc4b2fe525ae">1148</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">                    <a href="#a9884c71ca8b75cec15a9cc4b2fe525ae">m_isLast</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a96270035f29eb07f50ed8c0c2acda9d3">isLast</a> and <a href="#a89fc37af294659364193e14680065668">markLast</a>.
</div>
</div>

### m&#95;paragraphs {#a0c6a541e9cf5b513a82b5ff0607794cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNodeList DocParamList::m_paragraphs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01142">1142</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c6a541e9cf5b513a82b5ff0607794cf">1142</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a>             <a href="#a0c6a541e9cf5b513a82b5ff0607794cf">m_paragraphs</a>;</span></span></div>

</div>


Referenced by <a href="#aea61e6129350589c862ceb0f75d5f9a9">paragraphs</a>, <a href="#a98345755b6311bcc4129bd7ee14759f1">parse</a> and <a href="#a79bb36905dd1401288d55e12ee52ce03">parseXml</a>.
</div>
</div>

### m&#95;params {#acbc8c94fc05d08e05dd38f339f0a18dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNodeList DocParamList::m_params</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01143">1143</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acbc8c94fc05d08e05dd38f339f0a18dd">1143</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a>             <a href="#acbc8c94fc05d08e05dd38f339f0a18dd">m_params</a>;</span></span></div>

</div>


Referenced by <a href="#a543cac8da19b4edaa5eb0c7deeba2455">parameters</a>, <a href="#a98345755b6311bcc4129bd7ee14759f1">parse</a> and <a href="#a79bb36905dd1401288d55e12ee52ce03">parseXml</a>.
</div>
</div>

### m&#95;paramTypes {#a04a43c0f053845ea8769259804b670d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocNodeList DocParamList::m_paramTypes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01144">1144</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a04a43c0f053845ea8769259804b670d1">1144</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/docnodelist">DocNodeList</a>             <a href="#a04a43c0f053845ea8769259804b670d1">m_paramTypes</a>;</span></span></div>

</div>


Referenced by <a href="#a66138e258fb9547bd85e0b9227c48ebf">paramTypes</a> and <a href="#a98345755b6311bcc4129bd7ee14759f1">parse</a>.
</div>
</div>

### m&#95;type {#ab173b0e7740af58cde5390629aa93851}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocParamSect::Type DocParamList::m_type = <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e">DocParamSect::Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l01145">1145</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab173b0e7740af58cde5390629aa93851">1145</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51a">DocParamSect::Type</a>      <a href="#ab173b0e7740af58cde5390629aa93851">m_type</a> = <a href="/web-doxygen/docs/api/classes/docparamsect/#a402e8723e8b9f22c5ffa84046224d51aaceeaf36c7f8e7c3a4e47a68453fd130e">DocParamSect::Unknown</a>;</span></span></div>

</div>


Referenced by <a href="#a9c7cdfadcf9d06435cd7979423f3c0bf">DocParamList</a>, <a href="#a98345755b6311bcc4129bd7ee14759f1">parse</a>, <a href="#a79bb36905dd1401288d55e12ee52ce03">parseXml</a> and <a href="#a6c795a79c11468fb1d8ce3dab41534f3">type</a>.
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
