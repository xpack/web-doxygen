---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/docsimplesect
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocSimpleSect` Class Reference

<p>Node representing a simple section. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DocSimpleSect { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top">Type { <a href="#a3b9f9dd4952f3d819b347f74a6769a9b">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a92ee426f46c438e6f9fcba987e7abadb">DocSimpleSect</a> (DocParser *parser, DocNodeVariant *parent, Type t)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3b9f9dd4952f3d819b347f74a6769a9b">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ea4e7672816ad91cf567b2000f1a65c">type</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a151d09b73379f0fcade95af7ce910250">typeString</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4b28664b6fe921f89c934f9d2f4ba0">parse</a> (bool userTitle, bool needsSeparator)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7eb70bb58c30a5dab96c862583503b7e">parseRcs</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae33bb7d70b15676b9244be8de396edc0">parseXml</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae538f74c2d44222c9a45ef304c89e041">appendLinkWord</a> (const QCString &amp;word)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7bb6fa3996348dc1e211e32eb358f83">hasTitle</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbbcd2151b9e3b29fea64118e99b0b61">title</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a3b9f9dd4952f3d819b347f74a6769a9b">Type</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a532216db9ddf4cd760f8aa8a45541818">m_type</a> = <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">Unknown</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a></td>
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

<p>Node representing a simple section.</p>

<p>Definition at line 1016 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxySectionDef">

## Enumerations

### Type {#a3b9f9dd4952f3d819b347f74a6769a9b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum DocSimpleSect::Type </td>
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
<td class="doxyEnumItemName">Unknown<a id="a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">See<a id="a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Return<a id="a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Author<a id="a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Authors<a id="a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Version<a id="a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Since<a id="a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Date<a id="a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Note<a id="a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Warning<a id="a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Copyright<a id="a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Pre<a id="a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Post<a id="a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Invar<a id="a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Remark<a id="a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Attention<a id="a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Important<a id="a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">User<a id="a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Rcs<a id="a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 1019 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">1021</a></span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">Unknown</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">See</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">Return</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">Author</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">Authors</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">Version</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">Since</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">Date</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">1022</a></span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">Note</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">Warning</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">Copyright</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">Pre</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">Post</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">Invar</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">Remark</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">Attention</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">Important</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">1023</a></span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">User</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">Rcs</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### DocSimpleSect() {#a92ee426f46c438e6f9fcba987e7abadb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocSimpleSect::DocSimpleSect (<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> * parser, <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> * parent, <a href="#a3b9f9dd4952f3d819b347f74a6769a9b">Type</a> t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1025 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 2999 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a92ee426f46c438e6f9fcba987e7abadb">2999</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a92ee426f46c438e6f9fcba987e7abadb">DocSimpleSect::DocSimpleSect</a>(<a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>,<a href="#a3b9f9dd4952f3d819b347f74a6769a9b">Type</a> t) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3000</span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>,<a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">parent</a>), <a href="#a532216db9ddf4cd760f8aa8a45541818">m_type</a>(t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3001</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3002</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doccompoundnode/#ae01ca6994447efab51eb155728e4f3f6">DocCompoundNode::DocCompoundNode</a>, <a href="#a532216db9ddf4cd760f8aa8a45541818">m_type</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a9217c40d6d74f2b78928b3d8131dd7f0">DocNode::parent</a> and <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### appendLinkWord() {#ae538f74c2d44222c9a45ef304c89e041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocSimpleSect::appendLinkWord (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; word)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1031 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 3099 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae538f74c2d44222c9a45ef304c89e041">3099</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae538f74c2d44222c9a45ef304c89e041">DocSimpleSect::appendLinkWord</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;word)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3100</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3101</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> *p=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3102</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().empty() || (p=std::get_if&lt;DocPara&gt;(&amp;<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().back()))==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3103</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3104</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3105</span><span class="doxyLineContent"><span class="doxyHighlight">    p = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3106</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3107</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3108</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3109</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Comma-separate &lt;seealso&gt; links.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3110</span><span class="doxyLineContent"><span class="doxyHighlight">    p-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#af9a6952aca6a271fde9a883efd65cc58">injectToken</a>(Token::make_TK_WORD(),</span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3111</span><span class="doxyLineContent"><span class="doxyHighlight">    p-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#af9a6952aca6a271fde9a883efd65cc58">injectToken</a>(Token::make_TK_WHITESPACE(),</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3112</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3113</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3114</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a9e9561c7ec0edba0d50cdcb482942bea">inSeeBlock</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3115</span><span class="doxyLineContent"><span class="doxyHighlight">  p-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#af9a6952aca6a271fde9a883efd65cc58">injectToken</a>(Token::make_TK_LNKWORD(),word);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3116</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a9e9561c7ec0edba0d50cdcb482942bea">inSeeBlock</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3117</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get_last</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af9a6952aca6a271fde9a883efd65cc58">DocPara::injectToken</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a9e9561c7ec0edba0d50cdcb482942bea">DocParserContext::inSeeBlock</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### hasTitle() {#af7bb6fa3996348dc1e211e32eb358f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocSimpleSect::hasTitle ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1032 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 3004 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7bb6fa3996348dc1e211e32eb358f83">3004</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af7bb6fa3996348dc1e211e32eb358f83">DocSimpleSect::hasTitle</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3005</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3006</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a> &amp;&amp; std::get&lt;DocTitle&gt;(*m_title).hasTitle();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3007</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a942b617cd956361afbd314539cab5922">DocbookDocVisitor::operator()</a>.</p>

</div>
</div>

### parse() {#a3e4b28664b6fe921f89c934f9d2f4ba0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocSimpleSect::parse (bool userTitle, bool needsSeparator)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1028 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 3009 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3e4b28664b6fe921f89c934f9d2f4ba0">3009</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#a3e4b28664b6fe921f89c934f9d2f4ba0">DocSimpleSect::parse</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> userTitle,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> needsSeparator)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3010</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3011</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3012</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3013</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3014</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// handle case for user defined title</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3015</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (userTitle)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3016</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3017</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a> = <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa42674aaf44286a4dbbf89f4da21609a">createDocNode&lt;DocTitle&gt;</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3018</span><span class="doxyLineContent"><span class="doxyHighlight">    std::get_if&lt;DocTitle&gt;(<a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a>.get())-&gt;parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3019</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3020</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3021</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// add new paragraph as child</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3022</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().empty() &amp;&amp; std::holds_alternative&lt;DocPara&gt;(<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().back()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3023</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3024</span><span class="doxyLineContent"><span class="doxyHighlight">    std::get&lt;DocPara&gt;(<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().back()).markLast(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3025</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3026</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> markFirst = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3027</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needsSeparator)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3028</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3029</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docsimplesectsep">DocSimpleSectSep</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3030</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3031</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3032</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> *par  = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3033</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (markFirst)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3034</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3035</span><span class="doxyLineContent"><span class="doxyHighlight">    par-&gt;markFirst();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3036</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3037</span><span class="doxyLineContent"><span class="doxyHighlight">  par-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">markLast</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3038</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3039</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// parse the contents of the paragraph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3040</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> retval = par-&gt;parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3041</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3042</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"retval={}"</span><span class="doxyHighlight">,retval.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3043</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retval; </span><span class="doxyHighlightComment">// 0==EOF, TokenRetval::TK_NEWPARA, TokenRetval::TK_LISTITEM, TokenRetval::TK_ENDLIST, TokenRetval::RetVal_SimpleSec</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3044</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa42674aaf44286a4dbbf89f4da21609a">createDocNode</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get_last</a>, <a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">DocPara::markLast</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a> and <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a04534e1c41f2c421346fb9f313e2b737">DocPara::handleSimpleSection</a>.</p>

</div>
</div>

### parseRcs() {#a7eb70bb58c30a5dab96c862583503b7e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocSimpleSect::parseRcs ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1029 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 3046 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7eb70bb58c30a5dab96c862583503b7e">3046</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#a7eb70bb58c30a5dab96c862583503b7e">DocSimpleSect::parseRcs</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3047</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3048</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3049</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3050</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3051</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a> = <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa42674aaf44286a4dbbf89f4da21609a">createDocNode&lt;DocTitle&gt;</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3052</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a> *<a href="#abbbcd2151b9e3b29fea64118e99b0b61">title</a> = &amp;std::get&lt;DocTitle&gt;(*<a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3053</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#abbbcd2151b9e3b29fea64118e99b0b61">title</a>-&gt;parseFromString(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;context.token-&gt;name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3054</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3055</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> text = <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a>-&gt;<a href="/web-doxygen/docs/api/structs/tokeninfo/#a55ddc22fdcbb1121681b831154389e07">text</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3056</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#af278dab51b58124b32a625d709a29d97">pushContext</a>(); </span><span class="doxyHighlightComment">// this will create a new parser-&gt;context.token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3057</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">internalValidatingParseDoc</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>(),<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>(),text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3058</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>()-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#aa05ab8dc59dfa50633146bdba08db5f0">popContext</a>(); </span><span class="doxyHighlightComment">// this will restore the old parser-&gt;context.token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3059</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3060</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3061</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#aa42674aaf44286a4dbbf89f4da21609a">createDocNode</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa05ab8dc59dfa50633146bdba08db5f0">DocParser::popContext</a>, <a href="/web-doxygen/docs/api/classes/docparser/#af278dab51b58124b32a625d709a29d97">DocParser::pushContext</a>, <a href="/web-doxygen/docs/api/structs/tokeninfo/#a55ddc22fdcbb1121681b831154389e07">TokenInfo::text</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a>, <a href="#abbbcd2151b9e3b29fea64118e99b0b61">title</a> and <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>.</p>

</div>
</div>

### parseXml() {#ae33bb7d70b15676b9244be8de396edc0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Token DocSimpleSect::parseXml ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1030 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 3063 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae33bb7d70b15676b9244be8de396edc0">3063</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/token">Token</a> <a href="#ae33bb7d70b15676b9244be8de396edc0">DocSimpleSect::parseXml</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3064</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3065</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3066</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ns = <a href="/web-doxygen/docs/api/classes/autonodestack">AutoNodeStack</a>(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3067</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3068</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/token">Token</a> retval = Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3069</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (;;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3070</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3071</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// add new paragraph as child</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3072</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().empty() &amp;&amp; std::holds_alternative&lt;DocPara&gt;(<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().back()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3073</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3074</span><span class="doxyLineContent"><span class="doxyHighlight">      std::get&lt;DocPara&gt;(<a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().back()).markLast(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3075</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3076</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> markFirst = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">empty</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3077</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">append</a>&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;(<a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">parser</a>(),<a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">thisVariant</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3078</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docpara">DocPara</a> *par  = <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">children</a>().<a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">get_last</a>&lt;<a href="/web-doxygen/docs/api/classes/docpara">DocPara</a>&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3079</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (markFirst)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3080</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3081</span><span class="doxyLineContent"><span class="doxyHighlight">      par-&gt;markFirst();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3082</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3083</span><span class="doxyLineContent"><span class="doxyHighlight">    par-&gt;<a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">markLast</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3084</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3085</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// parse the contents of the paragraph</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3086</span><span class="doxyLineContent"><span class="doxyHighlight">    retval = par-&gt;parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3087</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">is_any_of</a>(TokenRetval::TK_NONE,TokenRetval::TK_EOF)) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3088</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retval.<a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">is</a>(TokenRetval::RetVal_CloseXml))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3089</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3090</span><span class="doxyLineContent"><span class="doxyHighlight">      retval = Token::make_RetVal_OK();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3091</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3092</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3093</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3094</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3095</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"retval={}"</span><span class="doxyHighlight">,retval.<a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">to_string</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3096</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3097</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docnodelist/#a834769ebf2b990228c84981003d7659b">DocNodeList::append</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/doccompoundnode/#aca6bc953ffff9a8773c2b4b0a866442c">DocCompoundNode::children</a>, <a href="/web-doxygen/docs/api/classes/growvector/#a4e81684f665c9a1a38b5e16cfbe31d41">GrowVector&lt; T &gt;::empty</a>, <a href="/web-doxygen/docs/api/structs/docnodelist/#ae3a5d9b77d64e18e642163cceac5fa2e">DocNodeList::get_last</a>, <a href="/web-doxygen/docs/api/classes/token/#a3393121ecbc606537f445296345d8ce6">Token::is</a>, <a href="/web-doxygen/docs/api/classes/token/#ac1d3fe36021841d01e0867a7fbac82a0">Token::is_any_of</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">DocPara::markLast</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a82847109f245ad8e8fe6102cf875fcd1">DocNode::parser</a>, <a href="/web-doxygen/docs/api/classes/docnode/#a748968b3044e70e48fad54a7cda1c57f">DocNode::thisVariant</a> and <a href="/web-doxygen/docs/api/classes/token/#a8ee4f27b53b3d10e00d897e2aca4fb4f">Token::to_string</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a04534e1c41f2c421346fb9f313e2b737">DocPara::handleSimpleSection</a>.</p>

</div>
</div>

### title() {#abbbcd2151b9e3b29fea64118e99b0b61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DocNodeVariant * DocSimpleSect::title ()</td>
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



<p>Definition at line 1033 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abbbcd2151b9e3b29fea64118e99b0b61">1033</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docnode-h/#a15a8494c4d80bb52db036d2fb5e9e9f8">DocNodeVariant</a> *<a href="#abbbcd2151b9e3b29fea64118e99b0b61">title</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a>.get(); }</span></span></div>

</div>


<p>Reference <a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a942b617cd956361afbd314539cab5922">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a9a6e493ac6aef6d638ead4ad62e4580a">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a6f8aff45c8c934cda5be07107de10c77">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a8bf41fa80034e1477e1017f19f89d4de">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#ab34a99c641d75788a05a0eeed41fa411">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a1302af218f73141f01cbc50e9704e8b6">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aa17fa64bc141c519b0b24e0a475ab1e1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a8592f34797e03f25475a23b9ee7f9e29">XmlDocVisitor::operator()</a> and <a href="#a7eb70bb58c30a5dab96c862583503b7e">parseRcs</a>.</p>

</div>
</div>

### type() {#a1ea4e7672816ad91cf567b2000f1a65c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type DocSimpleSect::type ()</td>
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



<p>Definition at line 1026 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ea4e7672816ad91cf567b2000f1a65c">1026</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3b9f9dd4952f3d819b347f74a6769a9b">Type</a> <a href="#a1ea4e7672816ad91cf567b2000f1a65c">type</a>()</span><span class="doxyHighlightKeyword"> const       </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a532216db9ddf4cd760f8aa8a45541818">m_type</a>; }</span></span></div>

</div>


<p>Reference <a href="#a532216db9ddf4cd760f8aa8a45541818">m_type</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a04534e1c41f2c421346fb9f313e2b737">DocPara::handleSimpleSection</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a942b617cd956361afbd314539cab5922">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a9a6e493ac6aef6d638ead4ad62e4580a">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a6f8aff45c8c934cda5be07107de10c77">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a8bf41fa80034e1477e1017f19f89d4de">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#ab34a99c641d75788a05a0eeed41fa411">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a1302af218f73141f01cbc50e9704e8b6">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aa17fa64bc141c519b0b24e0a475ab1e1">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#a8edfee8e77103bfc38b103b93dd4f90e">startSimpleSect</a>.</p>

</div>
</div>

### typeString() {#a151d09b73379f0fcade95af7ce910250}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocSimpleSect::typeString ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 1027 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>, definition at line 3119 of file <a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a151d09b73379f0fcade95af7ce910250">3119</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a151d09b73379f0fcade95af7ce910250">DocSimpleSect::typeString</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3120</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="#a532216db9ddf4cd760f8aa8a45541818">m_type</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3122</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3123</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">Unknown</a>:    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3124</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">See</a>:        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"see"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3125</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">Return</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"return"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3126</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">Author</a>:     </span><span class="doxyHighlightComment">// fall through</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3127</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">Authors</a>:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"author"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3128</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">Version</a>:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"version"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3129</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">Since</a>:      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"since"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3130</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">Date</a>:       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"date"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3131</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">Note</a>:       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"note"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3132</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">Warning</a>:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"warning"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3133</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">Pre</a>:        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"pre"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3134</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">Post</a>:       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"post"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3135</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">Copyright</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"copyright"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3136</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">Invar</a>:      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"invariant"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3137</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">Remark</a>:     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"remark"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3138</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">Attention</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"attention"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3139</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">Important</a>:  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"important"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3140</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">User</a>:       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"user"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3141</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">Rcs</a>:        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"rcs"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3142</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3143</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"unknown"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3144</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a3b9f9dd4952f3d819b347f74a6769a9bae3e95855fe383d4767691416f122bda8">Attention</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba93b679802935bef0edcd5d13787c93d7">Author</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba3e7dc72d1c6e9b0fd204ec7db9c47f6a">Authors</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba2e0c7884fe9de17cc8ec29cc8c445fa1">Copyright</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba7ebb3d39104e4023d8f64d46e9166305">Date</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba41b0b8fb01484d80c09aa19866ab18f5">Important</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9baa5d61ff7b823df12aa9a3895342561b8">Invar</a>, <a href="#a532216db9ddf4cd760f8aa8a45541818">m_type</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9bada884137c8ff6a93503a9c561d5c35d0">Note</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba10f52cafbfab59b29c286ac5d38251c8">Post</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba68b35aae9972a5f2f4b739edb91db575">Pre</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9bae7ac2742a06bed8be1747d68ec4af980">Rcs</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba71e7bd96894c8ce74ca64456d34d3939">Remark</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9bafbc7207cbd14361819ce4f2c8c33595d">Return</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba3bca11381a4eecb0a155993159e1f471">See</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9babede06022ff92538707861de74d9fdb5">Since</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">Unknown</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba0cdc5e6cf3a4156f2e4cb80d267ea87d">User</a>, <a href="#a3b9f9dd4952f3d819b347f74a6769a9baf32673a5f516e2100d41b917f37cfdf1">Version</a> and <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba407aa635cc75a80b3e222e307c43c988">Warning</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a9a6e493ac6aef6d638ead4ad62e4580a">HtmlDocVisitor::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_title {#afa53729b7e53ccdef10822c685ce64b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;DocNodeVariant&gt; DocSimpleSect::m_title</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1037 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa53729b7e53ccdef10822c685ce64b0">1037</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;DocNodeVariant&gt; <a href="#afa53729b7e53ccdef10822c685ce64b0">m_title</a>;</span></span></div>

</div>


<p>Referenced by <a href="#af7bb6fa3996348dc1e211e32eb358f83">hasTitle</a>, <a href="#a3e4b28664b6fe921f89c934f9d2f4ba0">parse</a>, <a href="#a7eb70bb58c30a5dab96c862583503b7e">parseRcs</a> and <a href="#abbbcd2151b9e3b29fea64118e99b0b61">title</a>.</p>

</div>
</div>

### m\_type {#a532216db9ddf4cd760f8aa8a45541818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Type DocSimpleSect::m_type = <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">Unknown</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1036 of file <a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a532216db9ddf4cd760f8aa8a45541818">1036</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3b9f9dd4952f3d819b347f74a6769a9b">Type</a>            <a href="#a532216db9ddf4cd760f8aa8a45541818">m_type</a> = <a href="#a3b9f9dd4952f3d819b347f74a6769a9ba9fea43f94c363209267026e3cf9583c6">Unknown</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a92ee426f46c438e6f9fcba987e7abadb">DocSimpleSect</a>, <a href="#a1ea4e7672816ad91cf567b2000f1a65c">type</a> and <a href="#a151d09b73379f0fcade95af7ce910250">typeString</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docnode-cpp">docnode.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
