---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/docimage
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DocImage` Class Reference

<p>Node representing an image. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocImage { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Type { <a href="#aaa49d1dad195745ff9d470c5335be93e">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a888ccf3ed611278566a04614fc48f12a">DocImage</a> (DocParser *parser, DocNodeVariant *parent, const HtmlAttribList &amp;attribs, const QCString &amp;name, Type t, const QCString &amp;url=QCString(), bool inlineImage=TRUE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#aaa49d1dad195745ff9d470c5335be93e">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a7abc635cfbbb0824b1a482b6cb42e9">type</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c62b3e12569fac905243b891a62d81a">name</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af627e9312a4cc758736ebaff6619990e">hasCaption</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a79d36f165096668a3d6631efb6e0b4f0">width</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434782653279e9f1d823656d48fe3e26">height</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07a0f3e6897e73d26b36ad4430b885e5">relPath</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e32f1e888da6279104a2fb515c620de">url</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae52199cbb5da4e10ccb3a9b53c4978ac">isInlineImage</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae604f9461d7685908488ead7a6d72ca0">isSVG</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05ea2b5c8166be879cc96e30fa487fb7">attribs</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbcccdba0822fb5c0776ca318cbfd631">parse</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/docimage/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a></td>
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

<p>Node representing an image.</p>

<p>Definition at line 641 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### Type {#aaa49d1dad195745ff9d470c5335be93e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum DocImage::Type </td>
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
<td class="doxyEnumItemName">Html<a id="aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Latex<a id="aaa49d1dad195745ff9d470c5335be93eaa40720221c0f30f373e9b3a9ec9711e5"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Rtf<a id="aaa49d1dad195745ff9d470c5335be93eaf742255bd9dc963b18e768c2b7fb7d70"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">DocBook<a id="aaa49d1dad195745ff9d470c5335be93ea725d162f5603b60f365bad17013c5d5a"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Xml<a id="aaa49d1dad195745ff9d470c5335be93ead2e9647950376dfa87071aa9913b703f"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00644">644</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa49d1dad195745ff9d470c5335be93ea725d162f5603b60f365bad17013c5d5a">644</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#aaa49d1dad195745ff9d470c5335be93e">Type</a> { <a href="#aaa49d1dad195745ff9d470c5335be93ea11831c0ddc505e031751197b1bab0623">Html</a>, <a href="#aaa49d1dad195745ff9d470c5335be93eaa40720221c0f30f373e9b3a9ec9711e5">Latex</a>, <a href="#aaa49d1dad195745ff9d470c5335be93eaf742255bd9dc963b18e768c2b7fb7d70">Rtf</a>, <a href="#aaa49d1dad195745ff9d470c5335be93ea725d162f5603b60f365bad17013c5d5a">DocBook</a>, <a href="#aaa49d1dad195745ff9d470c5335be93ead2e9647950376dfa87071aa9913b703f">Xml</a> };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DocImage() {#a888ccf3ed611278566a04614fc48f12a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocImage::DocImage (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, const <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp; attribs, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, <a href="#aaa49d1dad195745ff9d470c5335be93e">Type</a> t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; url=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), bool inlineImage=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00645">645</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#l01281">1281</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a888ccf3ed611278566a04614fc48f12a">1281</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a888ccf3ed611278566a04614fc48f12a">DocImage::DocImage</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;<a href="#a05ea2b5c8166be879cc96e30fa487fb7">attribs</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a0c62b3e12569fac905243b891a62d81a">name</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">                   <a href="#aaa49d1dad195745ff9d470c5335be93e">Type</a> t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a0e32f1e888da6279104a2fb515c620de">url</a>, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inlineImage) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/docimage/private">Private</a>&gt;(<a href="#a05ea2b5c8166be879cc96e30fa487fb7">attribs</a>, <a href="#a0c62b3e12569fac905243b891a62d81a">name</a>, t, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>-&gt;context.<a href="#a07a0f3e6897e73d26b36ad4430b885e5">relPath</a>, <a href="#a0e32f1e888da6279104a2fb515c620de">url</a>, inlineImage))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1284</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1285</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a05ea2b5c8166be879cc96e30fa487fb7">attribs</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode::DocCompoundNode</a>, <a href="#a0c62b3e12569fac905243b891a62d81a">name</a>, <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="#a07a0f3e6897e73d26b36ad4430b885e5">relPath</a> and <a href="#a0e32f1e888da6279104a2fb515c620de">url</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### attribs() {#a05ea2b5c8166be879cc96e30fa487fb7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const HtmlAttribList &amp; DocImage::attribs ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00656">656</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a05ea2b5c8166be879cc96e30fa487fb7">656</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/htmlattriblist">HtmlAttribList</a> &amp;<a href="#a05ea2b5c8166be879cc96e30fa487fb7">attribs</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;attribs; }</span></span></div>

</div>


Reference <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>.

Referenced by <a href="#a888ccf3ed611278566a04614fc48f12a">DocImage</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a608907da6a8263ac7cff6caae01673c9">XmlDocVisitor::operator()</a>.
</div>
</div>

### hasCaption() {#af627e9312a4cc758736ebaff6619990e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocImage::hasCaption ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00649">649</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af627e9312a4cc758736ebaff6619990e">649</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af627e9312a4cc758736ebaff6619990e">hasCaption</a>()</span><span class="doxyHighlightKeyword"> const     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>(); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a> and <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aab82ef451cf5eff26b1d097aefd8d421">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a28b453c4eabdf03f5d1b690a307d9c4e">LatexDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a247c4506996a3a6d71827322614efb30">RTFDocVisitor::operator()</a>.
</div>
</div>

### height() {#a434782653279e9f1d823656d48fe3e26}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocImage::height ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00651">651</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a434782653279e9f1d823656d48fe3e26">651</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a434782653279e9f1d823656d48fe3e26">height</a>()</span><span class="doxyHighlightKeyword"> const     </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;height; }</span></span></div>

</div>


Reference <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aab82ef451cf5eff26b1d097aefd8d421">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a28b453c4eabdf03f5d1b690a307d9c4e">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a4eefaf70c00c1c7ab252098e8599eff2">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#ad4c0764dcc811dec5e635dbd8b3d441f">PrintDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a608907da6a8263ac7cff6caae01673c9">XmlDocVisitor::operator()</a>.
</div>
</div>

### isInlineImage() {#ae52199cbb5da4e10ccb3a9b53c4978ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocImage::isInlineImage ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00654">654</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae52199cbb5da4e10ccb3a9b53c4978ac">654</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae52199cbb5da4e10ccb3a9b53c4978ac">isInlineImage</a>()</span><span class="doxyHighlightKeyword"> const  </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;inlineImage; }</span></span></div>

</div>


Reference <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a86acf8b4839daaae86b0a90ca98767b8">mustBeOutsideParagraph</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aab82ef451cf5eff26b1d097aefd8d421">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a28b453c4eabdf03f5d1b690a307d9c4e">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#ad4c0764dcc811dec5e635dbd8b3d441f">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a247c4506996a3a6d71827322614efb30">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a608907da6a8263ac7cff6caae01673c9">XmlDocVisitor::operator()</a>.
</div>
</div>

### isSVG() {#ae604f9461d7685908488ead7a6d72ca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocImage::isSVG ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00655">655</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#l01287">1287</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae604f9461d7685908488ead7a6d72ca0">1287</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae604f9461d7685908488ead7a6d72ca0">DocImage::isSVG</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>  locName = <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;url.isEmpty() ? <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;name : <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;url;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1290</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(locName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> fnd = locName.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'?'</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// ignore part from ? until end</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fnd==-1) fnd=len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> fnd&gt;=4 &amp;&amp; locName.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(fnd-4,4)==</span><span class="doxyHighlightStringLiteral">".svg"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1294</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a> and <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>.
</div>
</div>

### name() {#a0c62b3e12569fac905243b891a62d81a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocImage::name ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00648">648</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c62b3e12569fac905243b891a62d81a">648</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0c62b3e12569fac905243b891a62d81a">name</a>()</span><span class="doxyHighlightKeyword"> const       </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;name; }</span></span></div>

</div>


Reference <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>.

Referenced by <a href="#a888ccf3ed611278566a04614fc48f12a">DocImage</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aab82ef451cf5eff26b1d097aefd8d421">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a28b453c4eabdf03f5d1b690a307d9c4e">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a4eefaf70c00c1c7ab252098e8599eff2">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#ad4c0764dcc811dec5e635dbd8b3d441f">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a247c4506996a3a6d71827322614efb30">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a608907da6a8263ac7cff6caae01673c9">XmlDocVisitor::operator()</a>.
</div>
</div>

### parse() {#acbcccdba0822fb5c0776ca318cbfd631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocImage::parse ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00657">657</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#l01296">1296</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acbcccdba0822fb5c0776ca318cbfd631">1296</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acbcccdba0822fb5c0776ca318cbfd631">DocImage::parse</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ae88d59b299df415c0c2028d863288599">defaultHandleTitleAndSize</a>(<a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a50ef1a2484f87e0e789063b64718f9c6">CommandType::CMD_IMAGE</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(),<a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;width,<a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1299</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a50ef1a2484f87e0e789063b64718f9c6">CMD&#95;IMAGE</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ae88d59b299df415c0c2028d863288599">DocParser::defaultHandleTitleAndSize</a>, <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>.
</div>
</div>

### relPath() {#a07a0f3e6897e73d26b36ad4430b885e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocImage::relPath ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00652">652</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07a0f3e6897e73d26b36ad4430b885e5">652</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a07a0f3e6897e73d26b36ad4430b885e5">relPath</a>()</span><span class="doxyHighlightKeyword"> const    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;relPath; }</span></span></div>

</div>


Reference <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>.

Referenced by <a href="#a888ccf3ed611278566a04614fc48f12a">DocImage</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aab82ef451cf5eff26b1d097aefd8d421">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a608907da6a8263ac7cff6caae01673c9">XmlDocVisitor::operator()</a>.
</div>
</div>

### type() {#a4a7abc635cfbbb0824b1a482b6cb42e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type DocImage::type ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00647">647</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a7abc635cfbbb0824b1a482b6cb42e9">647</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaa49d1dad195745ff9d470c5335be93e">Type</a> <a href="#a4a7abc635cfbbb0824b1a482b6cb42e9">type</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;type; }</span></span></div>

</div>


Reference <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a021de5017c6965ebf393d509ded08502">isInvisibleNode</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aab82ef451cf5eff26b1d097aefd8d421">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a28b453c4eabdf03f5d1b690a307d9c4e">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a4eefaf70c00c1c7ab252098e8599eff2">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#ad4c0764dcc811dec5e635dbd8b3d441f">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a247c4506996a3a6d71827322614efb30">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a608907da6a8263ac7cff6caae01673c9">XmlDocVisitor::operator()</a>.
</div>
</div>

### url() {#a0e32f1e888da6279104a2fb515c620de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocImage::url ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00653">653</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0e32f1e888da6279104a2fb515c620de">653</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0e32f1e888da6279104a2fb515c620de">url</a>()</span><span class="doxyHighlightKeyword"> const        </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;url; }</span></span></div>

</div>


Reference <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>.

Referenced by <a href="#a888ccf3ed611278566a04614fc48f12a">DocImage</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a608907da6a8263ac7cff6caae01673c9">XmlDocVisitor::operator()</a>.
</div>
</div>

### width() {#a79d36f165096668a3d6631efb6e0b4f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocImage::width ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00650">650</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a79d36f165096668a3d6631efb6e0b4f0">650</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a79d36f165096668a3d6631efb6e0b4f0">width</a>()</span><span class="doxyHighlightKeyword"> const      </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>-&gt;width; }</span></span></div>

</div>


Reference <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aab82ef451cf5eff26b1d097aefd8d421">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a28b453c4eabdf03f5d1b690a307d9c4e">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a4eefaf70c00c1c7ab252098e8599eff2">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#ad4c0764dcc811dec5e635dbd8b3d441f">PrintDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a608907da6a8263ac7cff6caae01673c9">XmlDocVisitor::operator()</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#ac6667b30be9bbd1e5428a743b4f850ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; DocImage::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/docnode-h/#l00675">675</a> of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac6667b30be9bbd1e5428a743b4f850ec">675</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#ac6667b30be9bbd1e5428a743b4f850ec">p</a>;</span></span></div>

</div>


Referenced by <a href="#a05ea2b5c8166be879cc96e30fa487fb7">attribs</a>, <a href="#a888ccf3ed611278566a04614fc48f12a">DocImage</a>, <a href="#a434782653279e9f1d823656d48fe3e26">height</a>, <a href="#ae52199cbb5da4e10ccb3a9b53c4978ac">isInlineImage</a>, <a href="#ae604f9461d7685908488ead7a6d72ca0">isSVG</a>, <a href="#a0c62b3e12569fac905243b891a62d81a">name</a>, <a href="#acbcccdba0822fb5c0776ca318cbfd631">parse</a>, <a href="#a07a0f3e6897e73d26b36ad4430b885e5">relPath</a>, <a href="#a4a7abc635cfbbb0824b1a482b6cb42e9">type</a>, <a href="#a0e32f1e888da6279104a2fb515c620de">url</a> and <a href="#a79d36f165096668a3d6631efb6e0b4f0">width</a>.
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
