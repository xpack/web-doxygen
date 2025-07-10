---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/docbookgenerator
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocbookGenerator` Class Reference



## Declaration

<div class="doxyDeclaration">
class DocbookGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docbookgen-h">src/docbookgen.h</a>&gt;
</div>

## Base classes

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputgenerator">OutputGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Base class for shared implementation for all output generators. <a href="/web-doxygen/docs/api/classes/outputgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputgenintf">OutputGenIntf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for output generators. <a href="/web-doxygen/docs/api/classes/outputgenintf/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a> (const DocbookGenerator &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd55ac09ef27600eb1f6be12c339613f">DocbookGenerator</a> (DocbookGenerator &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd2d9e24cb0f45024d1efbfd59cff910">~DocbookGenerator</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docbookgenerator">DocbookGenerator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a> (const DocbookGenerator &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docbookgenerator">DocbookGenerator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a349d301ad0b14ab1784a059acfc82ad6">operator=</a> (DocbookGenerator &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77480edd4c5054fa1834ff3b2dcd3db5">type</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/outputgenintf">OutputGenIntf</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a534371d784e57657a2d17269ba7e5717">clone</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45427ad8a509ed14c5f6c1ef1a64e5d7">addCodeGen</a> (OutputCodeList &amp;list) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a268cc4c891922e026401a55c6aa0f0e2">cleanup</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f2d4d689d7e1c05bd243f0b23242064">writeDoc</a> (const IDocNodeAST *node, const Definition *ctx, const MemberDef *md, int id) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a82873f4a7eeacb88ef535768b311f4">startFile</a> (const QCString &amp;name, const QCString &amp;manName, const QCString &amp;title, int id, int hierarchyLevel) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefb08482f742251ae543aeb57983b335">endFile</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf1cd7095f2e35a8a08a35b5708d0290">writeSearchInfo</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af59fcb6ef3fc574f346a35719889d4b4">writeFooter</a> (const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19720fb8fa237272681c6328aed372c1">startIndexSection</a> (IndexSection) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a5dbcad360a1ad2a8f9403ae344d638">endIndexSection</a> (IndexSection) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53279dc86a635990c995e61bc3b7104c">writePageLink</a> (const QCString &amp;, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97781f8b5e046d402d50a6a49744acb0">startProjectNumber</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf173307e9344cbbe45d4ccdae94807">endProjectNumber</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a684db300b5edf11b5bfa42ba0dac2da0">writeStyleInfo</a> (int) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a921181dfbb9226c3eef4536d2f06a242">startTitleHead</a> (const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca2bba69055abb8a7a7ea9ce8ce7f11f">endTitleHead</a> (const QCString &amp;fileName, const QCString &amp;name) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af8a68054558e4135bf42a6d444fdb71c">startIndexListItem</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a51602b9f23553d2f742fe7a3f3326e">endIndexListItem</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3154fbaf3e01e59f00c50f3f34c6d3">startIndexList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297162e483491a92715883063295624a">endIndexList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c7a1105dc4b6faa8e81088a35f0a47d">startIndexKey</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3825760a95d9e6034ce0434d09ed398">endIndexKey</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28cb580557bb6f9808d05cc5bcc3b4bf">startIndexValue</a> (bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03eb777494759912f235f33cbcfadadf">endIndexValue</a> (const QCString &amp;, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0410be0719eae1da884ade02d1612af">startItemList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af738e039ccb42d9da57626ff43ede2b5">endItemList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a165b08f7f0cefa958779ddd2faf7e965">startIndexItem</a> (const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04113da78567eeb8144cdc82714c95bf">endIndexItem</a> (const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24d221cf16ecc55edd136306797d289a">startItemListItem</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a950f3ae4aac5c5cd548e64bd81b2e980">endItemListItem</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea69ff69be259d30ee167aa920746fab">docify</a> (const QCString &amp;text) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afba9fe943d8c123f6e40256bdca2f5d3">writeChar</a> (char) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac462a27783fedbf5241e95db0a5c66a">writeString</a> (const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22b30d736cc0185909d9b3954a8e3f4e">startParagraph</a> (const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d5757a3649f96aaaeef61ade2f1b067">endParagraph</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c3028f84a8675c8b21ccae5a23e4286">writeObjectLink</a> (const QCString &amp;, const QCString &amp;, const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac90cbd84bc41a572f9f99ca23587847f">startBold</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac40c97419675e944657df84aa2b944e3">endBold</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e66bd3d7d003c6a3205b1febaa19958">startTypewriter</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f14bcd9d6629e6ec18be7c82343d852">endTypewriter</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d1419af8e3808bc8876a8f7ac9d0b2c">startEmphasis</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e11d900e3d524f1536fd952f8f1f0eb">endEmphasis</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0332a478a833682cf5d2c547a8397973">writeRuler</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50c0a3308c5ae4a4740799c07c8b160f">startDescForItem</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c3bde6063e62666c8937ab1c6ff06b1">endDescForItem</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaea0ab82cc8fde7fb6b7b870fe1f5c61">startCenter</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a150df485d395188cbbee63799370c003">endCenter</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae501cb3410c7ed6e7daefc2c6bff8bab">startSmall</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f0fa2e1d6f9a5c11796e884ae962afc">endSmall</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaac726241831c07dc4733f0e63dab3e1">startExamples</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd9d65e673f95f980a82bd0bd5518903">endExamples</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7134e69943d0a4a7ed1939735417851a">writeAnchor</a> (const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0fe01b830ddb0d899e151aa389087c8">startSection</a> (const QCString &amp;, const QCString &amp;, SectionType) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3c2a2d5f7ee268ca127a30fcaa78fe0">endSection</a> (const QCString &amp;, SectionType) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1239152bed92bc91f6a1ddba37671a29">lineBreak</a> (const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa8fd7d7ca213ca44cfc5f90aae724e2">addIndexItem</a> (const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a4768269d4a67e9762f388db3ff6842">writeNonBreakableSpace</a> (int) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb8929ed5f608c71ef0d67c9bd2713a8">startDescTable</a> (const QCString &amp;title, const bool hasInits) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef5e37d1d6cda8c759cebcd418d91c5d">endDescTable</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8b9cff7a3e28360c3b659533fccbfda">startDescTableRow</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11a9495ef08b1736d472a7245af207b2">endDescTableRow</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6d257b8715c635fbeb2fce4183749c4">startDescTableTitle</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dfd54947422d7782b2634b041086ed8">endDescTableTitle</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa64e6f62df30c7d3da3c18c9e311ef96">startDescTableInit</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeccc502a7bdfb0f61b3bc32e642123ac">endDescTableInit</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a155219c2c52cacd61c75a34b59e16b4e">startDescTableData</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a981135dd520efbaa65fabfa865f0ac97">endDescTableData</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0cf8bbe3120d24b4bc0d254d14268296">startTextLink</a> (const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f7bdbae7f979fc69d532fd791b4fa44">endTextLink</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6ffcbf4bd345ac9afabf49898b5890e">startPageRef</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e98c2ae5445679208c1207c7e8fd650">endPageRef</a> (const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac651122c0ac17ea4be13f8a4d71c3efa">startGroupHeader</a> (const QCString &amp;, int) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad91c453f57c7ab68aafb726bceed5807">endGroupHeader</a> (int) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab76e2ad69e7649f9127d74c06bc93278">startMemberSections</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a576ba898a2b833304ffaee52a9aee2be">endMemberSections</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8859f548070610da1b29fc339d390fd2">startHeaderSection</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a4000026c8f34db3cb7fa38b88068f2">endHeaderSection</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f198594f85e92a681337af184d913d">startMemberHeader</a> (const QCString &amp;anchor, int typ) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d97af565fba4f9b4b8df0ee218a7b19">endMemberHeader</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53f3f2e01a47d65a20615e1fb8e5d245">startMemberSubtitle</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8c63d39214124f23059f9a6f2fb4dd1d">endMemberSubtitle</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70de26cfb00cc50138102556da46e2ce">startMemberDocList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accf1f2e363b93a552fb4d3aeb09e6ff2">endMemberDocList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7454a8fe2d2ceafbc630ea57ce68d0b">startMemberList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3b1fb5838ed0231423eb95a41173078">endMemberList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fdb74bc21106b41053aea156ef99b2c">startInlineHeader</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a221ea4ee3970e79c64e1636f4ae11782">endInlineHeader</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72485dc1f19c70c869b6807d1ce1b8e5">startAnonTypeScope</a> (int) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca505307dec429b7a18add100af59912">endAnonTypeScope</a> (int) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82557dc83927e00f34efb901409e04d4">startMemberItem</a> (const QCString &amp;, MemberItemType, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29bb57d53d4ef49984943752371d80a9">endMemberItem</a> (MemberItemType) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fc122c54d1a0667d645062bed344a6a">startMemberTemplateParams</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa45cce2f709a04a6a5c741b5d2c43f2d">endMemberTemplateParams</a> (const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b3a91c273834c43c7b48e2f0e8712d6">startCompoundTemplateParams</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56a8e5ad875fcb9b51ce32c5a6fb3fa0">endCompoundTemplateParams</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdcc8344112747cd65cd80bdb2249933">startMemberGroupHeader</a> (const QCString &amp;, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2f941a481c8539d5ea65daf45d7d694b">endMemberGroupHeader</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a310be7aaf9518ecf21dec09a0ed3bfd8">startMemberGroupDocs</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab056fe61e03329c403886763b05029f9">endMemberGroupDocs</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9be5e6aee43e8eaadf84e8adbd58a590">startMemberGroup</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22265d3dc6b9ae14e0f5db49a0b4f22a">endMemberGroup</a> (bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc2f215c948518de991a642f6a021635">insertMemberAlign</a> (bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e10e2665a803a6c5c931050172ea4b1">insertMemberAlignLeft</a> (MemberItemType, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ae15cadac821acb3d6ecfb6c541d6b9">startMemberDoc</a> (const QCString &amp;, const QCString &amp;, const QCString &amp;, const QCString &amp;, int, int, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c9f6c8cbc6591f1a9763d5c233a8f9">endMemberDoc</a> (bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab575d0e0e347d711d242bdc7fd8c7648">startDoxyAnchor</a> (const QCString &amp;fName, const QCString &amp;manName, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;args) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabec02eb28588a45888b0c4d977d0a3b">endDoxyAnchor</a> (const QCString &amp;fileName, const QCString &amp;anchor) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac08ff202d3bea4e6e16eceb73d3f2043">addLabel</a> (const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02aacfb4e28b9a83f0cc1ae519525192">writeLatexSpacing</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cf676ad6c4def51f89550c68fe4a064">writeStartAnnoItem</a> (const QCString &amp;, const QCString &amp;, const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bbf1226470e991f2d1aac02fe3b443b">startMemberDescription</a> (const QCString &amp;, const QCString &amp;, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6bcc9d1588d49850a41ae5e2a1899cd">endMemberDescription</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afecf0cbb2b97e57f44fa5df8acd422b1">startMemberDeclaration</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3041625348d5b377dabccf8d7b81782">endMemberDeclaration</a> (const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af456dab6739ba95632af57ca113f2214">writeInheritedSectionTitle</a> (const QCString &amp;, const QCString &amp;, const QCString &amp;, const QCString &amp;, const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f52440d2fe3025eaf9f7853974c44cd">startIndent</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247327c61f5c0cdc9e7f2323d7f978ca">endIndent</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbc5974b7b5e7711e3319c50f23b32c5">writeSynopsis</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f0bbee1b9f39353827fe1cb34aa6c71">startClassDiagram</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2906dcb02cfd455c0d910c9f9501bfbe">endClassDiagram</a> (const ClassDiagram &amp;, const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abc8a470c44572d5b386f47bb53a9d519">startDotGraph</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2e6be7cbbe074a8d2be270a537c454">endDotGraph</a> (DotClassGraph &amp;g) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbd96aa5d90d0337ba3cfcf717052902">startInclDepGraph</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afa0db463a17513f4e3ae08e03d6e2615">endInclDepGraph</a> (DotInclDepGraph &amp;g) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c5271d755874098863c487bfdf49ad8">startGroupCollaboration</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a640f85f2e2b3f829d6561aaed542d20b">endGroupCollaboration</a> (DotGroupCollaboration &amp;g) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f1823b3bff5917f7cc686c747b2e500">startCallGraph</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab1ce69f9718b3c1e05f6c1b697664e4">endCallGraph</a> (DotCallGraph &amp;g) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a987d5becf1294c93b3d7346b07dd51f5">startDirDepGraph</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa80d2614901e7d7624514fa077cee77c">endDirDepGraph</a> (DotDirDeps &amp;g) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b12a50011caf4cb18e36d78a82c636d">writeGraphicalHierarchy</a> (DotGfxHierarchyTable &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa50fb495205963cd96fc92210a406db8">startQuickIndices</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2a279cfe88218bf0526fb0a5c2ca51f">endQuickIndices</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d027d0e3f93bdc7fb18e0744dddc54c">writeSplitBar</a> (const QCString &amp;, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab37bcd37222fea70d11024ed92294636">writeNavigationPath</a> (const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84d793a7a3cfbef2635c31b9b47be6fd">writeLogo</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17247283fb1821451810341e9d0cc3d5">writeQuickLinks</a> (HighlightedItem, const QCString &amp;, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3656cbeda9530a97ef7aca5a93e476dd">writeSummaryLink</a> (const QCString &amp;, const QCString &amp;, const QCString &amp;, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebdedaea9ee0b74162e2f30b5b9d8650">writePageOutline</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad92f550c473ab4d6fc714ed633fd2bbc">startContents</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33a21c7a3169dfc7f8c4c1149dc6f6ed">endContents</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf38a4b2f36d31a465f67498ce919c83">startPageDoc</a> (const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9388e552fa8c8e18d8b03e43de804022">endPageDoc</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeca4bf8edce633fa3faa7c1e38882363">startTextBlock</a> (bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6684626f228c4b3386f33b9d0e1cb000">endTextBlock</a> (bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d3a346fb2272e6241e3b5cd75cf0b0e">lastIndexPage</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa59a7da2611e101aa060c3455084255e">startMemberDocPrefixItem</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d042582c83c4bf25dba8857f186e56d">endMemberDocPrefixItem</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97e2055991080f05a37be7769cf3509c">startMemberDocName</a> (bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a47879780f767bfd2f4ffcfaa105d8866">endMemberDocName</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e94634814ad6933ca72763614845a09">startParameterType</a> (bool, const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0ae9695b1371e245c5e4b458acae99ed">endParameterType</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83ad153480a66966d9e1121e004b46e4">startParameterName</a> (bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa2de284dbf9b27c95a81298ebff29a7d">endParameterName</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a298ee3beaa40d4f406dba0ea7908a473">startParameterExtra</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae91b64667df54c993df7fef86f2a57c9">endParameterExtra</a> (bool, bool, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aedc98fb288995aea0c0b83fc4eca50a2">startParameterDefVal</a> (const char *sep) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a852205da1a99f864d0a1c96143c3b671">endParameterDefVal</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05a82a3d67c8acbd8ef73ca8d6d77f1c">startParameterList</a> (bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae73f06b90526d3d375eafac0ae711af5">endParameterList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10ee707ef187621006c30d021aaca34d">exceptionEntry</a> (const QCString &amp;, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57ecb947b9d729a32204364b0be5f712">startConstraintList</a> (const QCString &amp;) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51f8405b195722cee84834e0b17f4c6e">startConstraintParam</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af1face8672a1118ae0a38fd123f4fe1a">endConstraintParam</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a418a7b6baf025267bf10fe0b4a38c367">startConstraintType</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ff006f1e7375b5d3c6e5a17a3990d68">endConstraintType</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adcaba85a73024c0104286c6480b1aaeb">startConstraintDocs</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cfc71e51ed754737f74095508e19a63">endConstraintDocs</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afef965c128d8f6cca32eea3c92c7d1e9">endConstraintList</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49908c3a630786d98fb499887b18d8f3">startMemberDocSimple</a> (bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a45cd1dbe07a7c47ec3209b9fe1b92c0d">endMemberDocSimple</a> (bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac81970c0218bab9e70c805e3fe2d1826">startInlineMemberType</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af26580af0994f29308d81034cce3823d">endInlineMemberType</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af610006b0e0386c4f5762724f30c429c">startInlineMemberName</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01c30e96c02d55000d0c0282cba79924">endInlineMemberName</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adaf7ed17f053cb14c26da75c9d7552d4">startInlineMemberDoc</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67b1d012d99a13ef16fcc4ea599b2a06">endInlineMemberDoc</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce24c2a590df467e4768a74958e7e22">startLabels</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a9126201aae3ba3d2e48a2e7c9b5082">writeLabel</a> (const QCString &amp;, bool) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b4c585da080af5a62ca30a99c27ba01">endLabels</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b3b950a4edb2d5d1d57125babf3e57">startLocalToc</a> (int level) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c7072c37b0f6ca58f077b0cdd0242e">endLocalToc</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0afd80ec501374a1cdbdf674ec967b79">startTocEntry</a> (const SectionInfo *si) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a42a2541faf3a23582c34b87fd29d4f57">endTocEntry</a> (const SectionInfo *si) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af357a86f84b841c7a0d1a8e52d644f69">startPlainFile</a> (const QCString &amp;name) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d188192c029b20f6505b7b79b8f288f">endPlainFile</a> () override</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9872f2ebb33a85b7fff7268fee91a977">openSection</a> (const QCString &amp;attr=QCString())</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c26ae654351124ba44d61d231fd6836">closeAllSections</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docbookcodegenerator">DocbookCodeGenerator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; bool, 20 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a> = { false, }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::array&lt; bool, 20 &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a> = { false, }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff246cfd65c7cf0982c9b6b39155fc9e">m_pageLinks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/docbookgenerator/tocstate">TocState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4363bcfe3875a66c7f2512feb6be13e">init</a> ()</td>
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


<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocbookGenerator() {#a59655593be449f9e01ce953a72233de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocbookGenerator::DocbookGenerator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 319 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a59655593be449f9e01ce953a72233de0">319</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator::DocbookGenerator</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">  , <a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a> = <a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>-&gt;add&lt;<a href="/web-doxygen/docs/api/classes/docbookcodegenerator">DocbookCodeGenerator</a>&gt;(&amp;<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>, <a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator::OutputGenerator</a>.</p>


<p>Referenced by <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#acd55ac09ef27600eb1f6be12c339613f">DocbookGenerator</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a> and <a href="#a349d301ad0b14ab1784a059acfc82ad6">operator=</a>.</p>

</div>
</div>

### DocbookGenerator() {#a73bc1589590acfa468910e82d66d0a91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocbookGenerator::DocbookGenerator (const <a href="/web-doxygen/docs/api/classes/docbookgenerator">DocbookGenerator</a> &amp; og)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 327 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73bc1589590acfa468910e82d66d0a91">327</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator::DocbookGenerator</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator</a> &amp;og) : <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator</a>(og.<a href="/web-doxygen/docs/api/classes/outputgenerator/#aaaa814308a1fd901771b9b6e4a176d58">m_dir</a>), <a href="/web-doxygen/docs/api/classes/outputgenintf">OutputGenIntf</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>         = std::make_unique&lt;OutputCodeList&gt;(*og.<a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>          = <a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>-&gt;get&lt;<a href="/web-doxygen/docs/api/classes/docbookcodegenerator">DocbookCodeGenerator</a>&gt;(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a680ad2abb703e2cb60fbdddf8423315a">OutputType::Docbook</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>-&gt;setTextStream(&amp;<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>        = og.<a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a>          = og.<a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>    = og.<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>       = og.<a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>     = og.<a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a>        = og.<a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a>      = og.<a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>          = og.<a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a>      = og.<a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a> = og.<a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a680ad2abb703e2cb60fbdddf8423315a">Docbook</a>, <a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator</a>, <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>, <a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>, <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>, <a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aaaa814308a1fd901771b9b6e4a176d58">OutputGenerator::m_dir</a>, <a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a>, <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a>, <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>, <a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>, <a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>, <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>, <a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a>, <a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6f6f6c92438ea4e7553e317d5bb17660">OutputGenerator::OutputGenerator</a>.</p>

</div>
</div>

### DocbookGenerator() {#acd55ac09ef27600eb1f6be12c339613f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocbookGenerator::DocbookGenerator (<a href="/web-doxygen/docs/api/classes/docbookgenerator">DocbookGenerator</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<p>Reference <a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~DocbookGenerator() {#acd2d9e24cb0f45024d1efbfd59cff910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocbookGenerator::~DocbookGenerator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 111 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#abfda55e880b3527d256491a2f8e908e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocbookGenerator &amp; DocbookGenerator::operator= (const <a href="/web-doxygen/docs/api/classes/docbookgenerator">DocbookGenerator</a> &amp; og)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 108 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 344 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abfda55e880b3527d256491a2f8e908e1">344</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator</a> &amp;<a href="#abfda55e880b3527d256491a2f8e908e1">DocbookGenerator::operator=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator</a> &amp;og)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">!=&amp;og)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aaaa814308a1fd901771b9b6e4a176d58">m_dir</a>              = og.<a href="/web-doxygen/docs/api/classes/outputgenerator/#aaaa814308a1fd901771b9b6e4a176d58">m_dir</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>         = std::make_unique&lt;OutputCodeList&gt;(*og.<a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>          = <a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>-&gt;get&lt;<a href="/web-doxygen/docs/api/classes/docbookcodegenerator">DocbookCodeGenerator</a>&gt;(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a680ad2abb703e2cb60fbdddf8423315a">OutputType::Docbook</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>-&gt;setTextStream(&amp;<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>        = og.<a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a>          = og.<a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>    = og.<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>       = og.<a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>     = og.<a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a>        = og.<a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a>      = og.<a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>          = og.<a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a>      = og.<a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a> = og.<a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a680ad2abb703e2cb60fbdddf8423315a">Docbook</a>, <a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator</a>, <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>, <a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>, <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>, <a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aaaa814308a1fd901771b9b6e4a176d58">OutputGenerator::m_dir</a>, <a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a>, <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a>, <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>, <a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>, <a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>, <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>, <a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a>, <a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### operator=() {#a349d301ad0b14ab1784a059acfc82ad6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocbookGenerator &amp; DocbookGenerator::operator= (<a href="/web-doxygen/docs/api/classes/docbookgenerator">DocbookGenerator</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 110 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<p>Reference <a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addCodeGen() {#a45427ad8a509ed14c5f6c1ef1a64e5d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::addCodeGen (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; list)</td>
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



<p>Declaration at line 122 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 368 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a45427ad8a509ed14c5f6c1ef1a64e5d7">368</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a45427ad8a509ed14c5f6c1ef1a64e5d7">DocbookGenerator::addCodeGen</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;list)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">  list.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a60b7d69b02fe400d0111a3321c9f0265">add</a>&lt;<a href="/web-doxygen/docs/api/files/src/outputlist-h/#a81f21cc2a33cdb152b10f341e2c8e5e7">DocbookCodeGeneratorDefer</a>&gt;(<a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/outputcodelist/#a60b7d69b02fe400d0111a3321c9f0265">OutputCodeList::add</a> and <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>.</p>

</div>
</div>

### addIndexItem() {#aaa8fd7d7ca213ca44cfc5f90aae724e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::addIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; prim, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sec)</td>
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



<p>Declaration at line 178 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1144 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa8fd7d7ca213ca44cfc5f90aae724e2">1144</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaa8fd7d7ca213ca44cfc5f90aae724e2">DocbookGenerator::addIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;prim,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;sec)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1145</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1146</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1147</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ac174bf305a6b97803492e067a2f8dd77">addIndexTerm</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>, prim, sec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1148</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ac174bf305a6b97803492e067a2f8dd77">addIndexTerm</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### addLabel() {#ac08ff202d3bea4e6e16eceb73d3f2043}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::addLabel (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 235 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 959 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac08ff202d3bea4e6e16eceb73d3f2043">959</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac08ff202d3bea4e6e16eceb73d3f2043">DocbookGenerator::addLabel</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### cleanup() {#a268cc4c891922e026401a55c6aa0f0e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::cleanup ()</td>
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



<p>Declaration at line 123 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 384 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a268cc4c891922e026401a55c6aa0f0e2">384</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a268cc4c891922e026401a55c6aa0f0e2">DocbookGenerator::cleanup</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> dname = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> d(dname.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a706b1f8eeae91066c7b1d7bb7c0d7ef9">clearSubDirs</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#a706b1f8eeae91066c7b1d7bb7c0d7ef9">clearSubDirs</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### clone() {#a534371d784e57657a2d17269ba7e5717}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; OutputGenIntf &gt; DocbookGenerator::clone ()</td>
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



<p>Definition at line 121 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a534371d784e57657a2d17269ba7e5717">121</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;OutputGenIntf&gt; <a href="#a534371d784e57657a2d17269ba7e5717">clone</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;DocbookGenerator&gt;(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">); }</span></span></div>

</div>

</div>
</div>

### docify() {#aea69ff69be259d30ee167aa920746fab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::docify (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Declaration at line 153 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 766 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aea69ff69be259d30ee167aa920746fab">766</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aea69ff69be259d30ee167aa920746fab">DocbookGenerator::docify</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>(str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>


<p>Referenced by <a href="#a57ecb947b9d729a32204364b0be5f712">startConstraintList</a>, <a href="#aaac726241831c07dc4733f0e63dab3e1">startExamples</a> and <a href="#afba9fe943d8c123f6e40256bdca2f5d3">writeChar</a>.</p>

</div>
</div>

### endAnonTypeScope() {#aca505307dec429b7a18add100af59912}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endAnonTypeScope (int)</td>
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



<p>Definition at line 213 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca505307dec429b7a18add100af59912">213</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aca505307dec429b7a18add100af59912">endAnonTypeScope</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endBold() {#ac40c97419675e944657df84aa2b944e3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endBold ()</td>
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



<p>Declaration at line 160 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 828 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac40c97419675e944657df84aa2b944e3">828</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac40c97419675e944657df84aa2b944e3">DocbookGenerator::endBold</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/emphasis&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endCallGraph() {#aab1ce69f9718b3c1e05f6c1b697664e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endCallGraph (<a href="/web-doxygen/docs/api/classes/dotcallgraph">DotCallGraph</a> &amp; g)</td>
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



<p>Declaration at line 258 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1321 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aab1ce69f9718b3c1e05f6c1b697664e4">1321</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aab1ce69f9718b3c1e05f6c1b697664e4">DocbookGenerator::endCallGraph</a>(<a href="/web-doxygen/docs/api/classes/dotcallgraph">DotCallGraph</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = g.<a href="/web-doxygen/docs/api/classes/dotcallgraph/#ad59c94658b83032817c03c0d59c7e5da">writeGraph</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">EmbeddedOutputFormat::DocBook</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>(),<a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">DocBook</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a> and <a href="/web-doxygen/docs/api/classes/dotcallgraph/#ad59c94658b83032817c03c0d59c7e5da">DotCallGraph::writeGraph</a>.</p>

</div>
</div>

### endCenter() {#a150df485d395188cbbee63799370c003}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endCenter ()</td>
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



<p>Definition at line 169 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a150df485d395188cbbee63799370c003">169</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a150df485d395188cbbee63799370c003">endCenter</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endClassDiagram() {#a2906dcb02cfd455c0d910c9f9501bfbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endClassDiagram (const <a href="/web-doxygen/docs/api/classes/classdiagram">ClassDiagram</a> &amp; d, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 250 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 997 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2906dcb02cfd455c0d910c9f9501bfbe">997</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2906dcb02cfd455c0d910c9f9501bfbe">DocbookGenerator::endClassDiagram</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdiagram">ClassDiagram</a> &amp;d, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">998</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">999</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1000</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;informalfigure&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1001</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;mediaobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1002</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"            &lt;imageobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1003</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"                &lt;imagedata width=\"50%\" align=\"center\" valign=\"middle\" scalefit=\"0\" fileref=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1004</span><span class="doxyLineContent"><span class="doxyHighlight">                         &lt;&lt; <a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a> &lt;&lt; <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">".png\"&gt;"</span><span class="doxyHighlight"> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/imagedata&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1005</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"            &lt;/imageobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1006</span><span class="doxyLineContent"><span class="doxyHighlight">  d.<a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">writeImage</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1007</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/mediaobject&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1008</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/informalfigure&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1009</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1010</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a> and <a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">ClassDiagram::writeImage</a>.</p>

</div>
</div>

### endCompoundTemplateParams() {#a56a8e5ad875fcb9b51ce32c5a6fb3fa0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endCompoundTemplateParams ()</td>
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



<p>Declaration at line 219 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1045 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a56a8e5ad875fcb9b51ce32c5a6fb3fa0">1045</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a56a8e5ad875fcb9b51ce32c5a6fb3fa0">DocbookGenerator::endCompoundTemplateParams</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1046</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1047</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1048</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;&lt;/simplesect&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1049</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endConstraintDocs() {#a4cfc71e51ed754737f74095508e19a63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endConstraintDocs ()</td>
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



<p>Declaration at line 299 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1374 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4cfc71e51ed754737f74095508e19a63">1374</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4cfc71e51ed754737f74095508e19a63">DocbookGenerator::endConstraintDocs</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### endConstraintList() {#afef965c128d8f6cca32eea3c92c7d1e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endConstraintList ()</td>
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



<p>Declaration at line 300 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1378 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afef965c128d8f6cca32eea3c92c7d1e9">1378</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afef965c128d8f6cca32eea3c92c7d1e9">DocbookGenerator::endConstraintList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/simplesect&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endConstraintParam() {#af1face8672a1118ae0a38fd123f4fe1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endConstraintParam ()</td>
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



<p>Declaration at line 295 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1356 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af1face8672a1118ae0a38fd123f4fe1a">1356</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af1face8672a1118ae0a38fd123f4fe1a">DocbookGenerator::endConstraintParam</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### endConstraintType() {#a2ff006f1e7375b5d3c6e5a17a3990d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endConstraintType ()</td>
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



<p>Declaration at line 297 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1365 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ff006f1e7375b5d3c6e5a17a3990d68">1365</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2ff006f1e7375b5d3c6e5a17a3990d68">DocbookGenerator::endConstraintType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/emphasis&gt;&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endContents() {#a33a21c7a3169dfc7f8c4c1149dc6f6ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endContents ()</td>
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



<p>Definition at line 271 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a33a21c7a3169dfc7f8c4c1149dc6f6ed">271</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a33a21c7a3169dfc7f8c4c1149dc6f6ed">endContents</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endDescForItem() {#a7c3bde6063e62666c8937ab1c6ff06b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endDescForItem ()</td>
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



<p>Definition at line 167 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c3bde6063e62666c8937ab1c6ff06b1">167</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7c3bde6063e62666c8937ab1c6ff06b1">endDescForItem</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endDescTable() {#aef5e37d1d6cda8c759cebcd418d91c5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endDescTable ()</td>
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



<p>Declaration at line 182 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1236 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aef5e37d1d6cda8c759cebcd418d91c5d">1236</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aef5e37d1d6cda8c759cebcd418d91c5d">DocbookGenerator::endDescTable</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1237</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1238</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1239</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/tbody&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1240</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/tgroup&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1241</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/informaltable&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1242</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1243</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endDescTableData() {#a981135dd520efbaa65fabfa865f0ac97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endDescTableData ()</td>
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



<p>Declaration at line 190 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1285 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a981135dd520efbaa65fabfa865f0ac97">1285</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a981135dd520efbaa65fabfa865f0ac97">DocbookGenerator::endDescTableData</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1286</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1287</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1288</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1289</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endDescTableInit() {#aeccc502a7bdfb0f61b3bc32e642123ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endDescTableInit ()</td>
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



<p>Declaration at line 188 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1274 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeccc502a7bdfb0f61b3bc32e642123ac">1274</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aeccc502a7bdfb0f61b3bc32e642123ac">DocbookGenerator::endDescTableInit</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1275</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1276</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1277</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### endDescTableRow() {#a11a9495ef08b1736d472a7245af207b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endDescTableRow ()</td>
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



<p>Declaration at line 184 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1252 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a11a9495ef08b1736d472a7245af207b2">1252</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a11a9495ef08b1736d472a7245af207b2">DocbookGenerator::endDescTableRow</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1253</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1254</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1255</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/row&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1256</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endDescTableTitle() {#a4dfd54947422d7782b2634b041086ed8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endDescTableTitle ()</td>
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



<p>Declaration at line 186 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1263 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4dfd54947422d7782b2634b041086ed8">1263</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4dfd54947422d7782b2634b041086ed8">DocbookGenerator::endDescTableTitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1264</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1265</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1266</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### endDirDepGraph() {#aa80d2614901e7d7624514fa077cee77c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endDirDepGraph (<a href="/web-doxygen/docs/api/classes/dotdirdeps">DotDirDeps</a> &amp; g)</td>
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



<p>Declaration at line 260 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1330 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa80d2614901e7d7624514fa077cee77c">1330</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa80d2614901e7d7624514fa077cee77c">DocbookGenerator::endDirDepGraph</a>(<a href="/web-doxygen/docs/api/classes/dotdirdeps">DotDirDeps</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1333</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = g.<a href="/web-doxygen/docs/api/classes/dotdirdeps/#a636d65d1b7097eca39e1dc431e8a7b32">writeGraph</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">EmbeddedOutputFormat::DocBook</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>(),<a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1334</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">DocBook</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a> and <a href="/web-doxygen/docs/api/classes/dotdirdeps/#a636d65d1b7097eca39e1dc431e8a7b32">DotDirDeps::writeGraph</a>.</p>

</div>
</div>

### endDotGraph() {#a4b2e6be7cbbe074a8d2be270a537c454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endDotGraph (<a href="/web-doxygen/docs/api/classes/dotclassgraph">DotClassGraph</a> &amp; g)</td>
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



<p>Declaration at line 252 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1303 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4b2e6be7cbbe074a8d2be270a537c454">1303</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4b2e6be7cbbe074a8d2be270a537c454">DocbookGenerator::endDotGraph</a>(<a href="/web-doxygen/docs/api/classes/dotclassgraph">DotClassGraph</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1304</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1305</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1306</span><span class="doxyLineContent"><span class="doxyHighlight">  g.<a href="/web-doxygen/docs/api/classes/dotclassgraph/#a0273e4e9adfbbe1f601a986636ef79dc">writeGraph</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">EmbeddedOutputFormat::DocBook</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>(),<a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1307</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">DocBook</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a0273e4e9adfbbe1f601a986636ef79dc">DotClassGraph::writeGraph</a>.</p>

</div>
</div>

### endDoxyAnchor() {#aabec02eb28588a45888b0c4d977d0a3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endDoxyAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
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



<p>Declaration at line 234 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 955 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aabec02eb28588a45888b0c4d977d0a3b">955</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aabec02eb28588a45888b0c4d977d0a3b">DocbookGenerator::endDoxyAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### endEmphasis() {#a9e11d900e3d524f1536fd952f8f1f0eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endEmphasis ()</td>
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



<p>Definition at line 164 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e11d900e3d524f1536fd952f8f1f0eb">164</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9e11d900e3d524f1536fd952f8f1f0eb">endEmphasis</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endExamples() {#afd9d65e673f95f980a82bd0bd5518903}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endExamples ()</td>
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



<p>Declaration at line 173 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1035 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afd9d65e673f95f980a82bd0bd5518903">1035</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afd9d65e673f95f980a82bd0bd5518903">DocbookGenerator::endExamples</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1036</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1037</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1038</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/simplesect&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1039</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endFile() {#aefb08482f742251ae543aeb57983b335}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endFile ()</td>
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



<p>Declaration at line 126 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 423 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aefb08482f742251ae543aeb57983b335">423</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aefb08482f742251ae543aeb57983b335">DocbookGenerator::endFile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9c26ae654351124ba44d61d231fd6836">closeAllSections</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a> = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Write page links only after all sections have been closed to avoid bugs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="#aff246cfd65c7cf0982c9b6b39155fc9e">m_pageLinks</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileType=</span><span class="doxyHighlightStringLiteral">"section"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>= <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>-&gt;sourceFileName();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> == </span><span class="doxyHighlightStringLiteral">"index.xml"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">    fileType=</span><span class="doxyHighlightStringLiteral">"book"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> == </span><span class="doxyHighlightStringLiteral">"mainpage.xml"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">    fileType=</span><span class="doxyHighlightStringLiteral">"chapter"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/"</span><span class="doxyHighlight"> &lt;&lt; fileType &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2d188192c029b20f6505b7b79b8f288f">endPlainFile</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>-&gt;setSourceFileName(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a9c26ae654351124ba44d61d231fd6836">closeAllSections</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#a2d188192c029b20f6505b7b79b8f288f">endPlainFile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>, <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a>, <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>, <a href="#aff246cfd65c7cf0982c9b6b39155fc9e">m_pageLinks</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endGroupCollaboration() {#a640f85f2e2b3f829d6561aaed542d20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endGroupCollaboration (<a href="/web-doxygen/docs/api/classes/dotgroupcollaboration">DotGroupCollaboration</a> &amp; g)</td>
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



<p>Declaration at line 256 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1294 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a640f85f2e2b3f829d6561aaed542d20b">1294</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a640f85f2e2b3f829d6561aaed542d20b">DocbookGenerator::endGroupCollaboration</a>(<a href="/web-doxygen/docs/api/classes/dotgroupcollaboration">DotGroupCollaboration</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1295</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1296</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1297</span><span class="doxyLineContent"><span class="doxyHighlight">  g.<a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a1e26ce5a2563ee5144ef66ff9cf88461">writeGraph</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">EmbeddedOutputFormat::DocBook</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>(),<a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1298</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">DocBook</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a> and <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a1e26ce5a2563ee5144ef66ff9cf88461">DotGroupCollaboration::writeGraph</a>.</p>

</div>
</div>

### endGroupHeader() {#ad91c453f57c7ab68aafb726bceed5807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endGroupHeader (int)</td>
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



<p>Declaration at line 197 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 854 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad91c453f57c7ab68aafb726bceed5807">854</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad91c453f57c7ab68aafb726bceed5807">DocbookGenerator::endGroupHeader</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endHeaderSection() {#a6a4000026c8f34db3cb7fa38b88068f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endHeaderSection ()</td>
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



<p>Definition at line 201 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6a4000026c8f34db3cb7fa38b88068f2">201</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6a4000026c8f34db3cb7fa38b88068f2">endHeaderSection</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endInclDepGraph() {#afa0db463a17513f4e3ae08e03d6e2615}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endInclDepGraph (<a href="/web-doxygen/docs/api/classes/dotincldepgraph">DotInclDepGraph</a> &amp; g)</td>
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



<p>Declaration at line 254 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1312 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afa0db463a17513f4e3ae08e03d6e2615">1312</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afa0db463a17513f4e3ae08e03d6e2615">DocbookGenerator::endInclDepGraph</a>(<a href="/web-doxygen/docs/api/classes/dotincldepgraph">DotInclDepGraph</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = g.<a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a197a7b8e9b068d122b062c80b21784e4">writeGraph</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">EmbeddedOutputFormat::DocBook</a>,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>(),<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>(),<a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#a8680135da08a5ef57cebe20060912dcca4a82b0a4711aab28baf901194012e32c">DocBook</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a> and <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a197a7b8e9b068d122b062c80b21784e4">DotInclDepGraph::writeGraph</a>.</p>

</div>
</div>

### endIndent() {#a247327c61f5c0cdc9e7f2323d7f978ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endIndent ()</td>
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



<p>Definition at line 247 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a247327c61f5c0cdc9e7f2323d7f978ca">247</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a247327c61f5c0cdc9e7f2323d7f978ca">endIndent</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endIndexItem() {#a04113da78567eeb8144cdc82714c95bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 150 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a04113da78567eeb8144cdc82714c95bf">150</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a04113da78567eeb8144cdc82714c95bf">endIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endIndexKey() {#ab3825760a95d9e6034ce0434d09ed398}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endIndexKey ()</td>
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



<p>Definition at line 143 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab3825760a95d9e6034ce0434d09ed398">143</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab3825760a95d9e6034ce0434d09ed398">endIndexKey</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endIndexList() {#a297162e483491a92715883063295624a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endIndexList ()</td>
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



<p>Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a297162e483491a92715883063295624a">141</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a297162e483491a92715883063295624a">endIndexList</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endIndexListItem() {#a6a51602b9f23553d2f742fe7a3f3326e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endIndexListItem ()</td>
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



<p>Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6a51602b9f23553d2f742fe7a3f3326e">139</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6a51602b9f23553d2f742fe7a3f3326e">endIndexListItem</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endIndexSection() {#a9a5dbcad360a1ad2a8f9403ae344d638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endIndexSection (<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a> is)</td>
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



<p>Declaration at line 131 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 533 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a5dbcad360a1ad2a8f9403ae344d638">533</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9a5dbcad360a1ad2a8f9403ae344d638">DocbookGenerator::endIndexSection</a>(<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a> is)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>(</span><span class="doxyHighlightStringLiteral">"IndexSection "</span><span class="doxyHighlight"> &lt;&lt; is)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (is)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ad91b65ea5e9c3686b3a0078e32d9133f">IndexSection::isTitlePageStart</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a2d64103a58ee3a5192221119a31dfe28">IndexSection::isTitlePageAuthor</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a01093bf5aa5f29736aab5a03d438d428">IndexSection::isMainPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a53279dc86a635990c995e61bc3b7104c">writePageLink</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"mainpage"</span><span class="doxyHighlight">), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a73fc6dc74e3caab626fcb788e489c006">IndexSection::isModuleIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;/chapter&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a7a9b27e109f6dd8dde1ec3139e9c6636">IndexSection::isTopicIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;/chapter&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7abc266c3a59d8d164fe6e05eb2bbd6a55">IndexSection::isDirIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;xi:include href=\"dirs.xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;/chapter&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ac72f48c94b82bf532b2eb7e9dd1c2345">IndexSection::isNamespaceIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;xi:include href=\"namespaces.xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;/chapter&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a7ed89b8fd01df70d408e1571d145c1c1">IndexSection::isConceptIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;xi:include href=\"concepts.xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;/chapter&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a5dc0feebd328fce66fdf10940d325c13">IndexSection::isClassHierarchyIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;xi:include href=\"hierarchy.xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;/chapter&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a98d9a43fdd6c458d80251cbb6712f7d5">IndexSection::isCompoundIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;/chapter&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a2f028c6e71fd63fb9e23efb217b8c4a7">IndexSection::isFileIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;xi:include href=\"files.xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;/chapter&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a96414d5dc6d8784abb414cf1b04b3218">IndexSection::isPageIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;xi:include href=\"pages.xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "&lt;/chapter&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7aea69f72466bdd3c72c5c6b5bc6ee6cca">IndexSection::isTopicDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;gd : *<a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd-&gt;isReference() &amp;&amp; !gd-&gt;isASubGroup())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a53279dc86a635990c995e61bc3b7104c">writePageLink</a>(gd-&gt;getOutputFileBase(), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a56f0fdd7e2c9390989e1075d48ce7bbd">IndexSection::isModuleDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="/web-doxygen/docs/api/classes/modulemanager/#a4f48cf5d05907a6acc4b9c6ddec752b7">ModuleManager::instance</a>().modules())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!mod-&gt;isReference() &amp;&amp; mod-&gt;isPrimaryInterface())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a53279dc86a635990c995e61bc3b7104c">writePageLink</a>(mod-&gt;getOutputFileBase(), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a55e8f77f5eb1557c27dad33a4ee24165">IndexSection::isDirDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dd : *<a href="/web-doxygen/docs/api/classes/doxygen/#ad179803c33ab064adfd6adf681a0a805">Doxygen::dirLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dd-&gt;isLinkableInProject())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;    xi:include href=\""</span><span class="doxyHighlight"> &lt;&lt; dd-&gt;getOutputFileBase() &lt;&lt; </span><span class="doxyHighlightStringLiteral">".xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ad8796f241437df840983ae62b0ec6bc5">IndexSection::isNamespaceDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nd-&gt;isLinkableInProject() &amp;&amp; !nd-&gt;isAlias())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;xi:include href=\""</span><span class="doxyHighlight"> &lt;&lt; nd-&gt;getOutputFileBase() &lt;&lt; </span><span class="doxyHighlightStringLiteral">".xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7aba356fa1d95f3ad5fe998378562d2968">IndexSection::isConceptDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a0de9b52b3098ea1a4bee5e248e8287c8">Doxygen::conceptLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;isLinkableInProject() &amp;&amp; !cd-&gt;isAlias())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;xi:include href=\""</span><span class="doxyHighlight"> &lt;&lt; cd-&gt;getOutputFileBase() &lt;&lt; </span><span class="doxyHighlightStringLiteral">".xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a8dab680d3e9e897983a1b9e7968c82c7">IndexSection::isClassDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;isLinkableInProject() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">             !cd-&gt;isImplicitTemplateInstance() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">             !cd-&gt;isEmbeddedInOuterScope() &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">             !cd-&gt;isAlias()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">             )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;xi:include href=\""</span><span class="doxyHighlight"> &lt;&lt; cd-&gt;getOutputFileBase() &lt;&lt; </span><span class="doxyHighlightStringLiteral">".xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a3c622c2f13fd1e39bf3b1fdad4a2ae2e">IndexSection::isFileDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fn : *<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fd : *fn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd-&gt;isLinkableInProject())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;xi:include href=\""</span><span class="doxyHighlight"> &lt;&lt; fd-&gt;getOutputFileBase() &lt;&lt; </span><span class="doxyHighlightStringLiteral">".xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fd-&gt;generateSourceFile())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;xi:include href=\""</span><span class="doxyHighlight"> &lt;&lt; fd-&gt;getSourceFileBase() &lt;&lt; </span><span class="doxyHighlightStringLiteral">".xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a87c7dab68957c9a53129b71dc0a90635">IndexSection::isExampleDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a6cfac206c42a62e6e3ba66d5d4e4a471">Doxygen::exampleLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;xi:include href=\""</span><span class="doxyHighlight"> &lt;&lt; pd-&gt;getOutputFileBase() &lt;&lt; </span><span class="doxyHighlightStringLiteral">".xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a41de1f39ac1ee1329a1374b2da6bfc70">IndexSection::isPageDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pd : *<a href="/web-doxygen/docs/api/classes/doxygen/#abd2756663a014ee48e1660d32a48cac5">Doxygen::pageLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!pd-&gt;getGroupDef() &amp;&amp; !pd-&gt;isReference() &amp;&amp; !pd-&gt;hasParentPage()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">            &amp;&amp; <a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>.get() != pd.get())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a53279dc86a635990c995e61bc3b7104c">writePageLink</a>(pd-&gt;getOutputFileBase(), <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">704</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7af311c10a314387cf7b6310240aa89bb0">IndexSection::isPageDocumentation2</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ab520ec9da3284768c754fbbf4e907e08">IndexSection::isEndIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;index/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a0de9b52b3098ea1a4bee5e248e8287c8">Doxygen::conceptLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#ad179803c33ab064adfd6adf681a0a805">Doxygen::dirLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a6cfac206c42a62e6e3ba66d5d4e4a471">Doxygen::exampleLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a4f48cf5d05907a6acc4b9c6ddec752b7">ModuleManager::instance</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a8dab680d3e9e897983a1b9e7968c82c7">isClassDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a5dc0feebd328fce66fdf10940d325c13">isClassHierarchyIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a98d9a43fdd6c458d80251cbb6712f7d5">isCompoundIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7aba356fa1d95f3ad5fe998378562d2968">isConceptDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a7ed89b8fd01df70d408e1571d145c1c1">isConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a55e8f77f5eb1557c27dad33a4ee24165">isDirDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7abc266c3a59d8d164fe6e05eb2bbd6a55">isDirIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ab520ec9da3284768c754fbbf4e907e08">isEndIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a87c7dab68957c9a53129b71dc0a90635">isExampleDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a3c622c2f13fd1e39bf3b1fdad4a2ae2e">isFileDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a2f028c6e71fd63fb9e23efb217b8c4a7">isFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a01093bf5aa5f29736aab5a03d438d428">isMainPage</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a56f0fdd7e2c9390989e1075d48ce7bbd">isModuleDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a73fc6dc74e3caab626fcb788e489c006">isModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ad8796f241437df840983ae62b0ec6bc5">isNamespaceDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ac72f48c94b82bf532b2eb7e9dd1c2345">isNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a41de1f39ac1ee1329a1374b2da6bfc70">isPageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7af311c10a314387cf7b6310240aa89bb0">isPageDocumentation2</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a96414d5dc6d8784abb414cf1b04b3218">isPageIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a2d64103a58ee3a5192221119a31dfe28">isTitlePageAuthor</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ad91b65ea5e9c3686b3a0078e32d9133f">isTitlePageStart</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7aea69f72466bdd3c72c5c6b5bc6ee6cca">isTopicDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a7a9b27e109f6dd8dde1ec3139e9c6636">isTopicIndex</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#abd2756663a014ee48e1660d32a48cac5">Doxygen::pageLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a53279dc86a635990c995e61bc3b7104c">writePageLink</a>.</p>

</div>
</div>

### endIndexValue() {#a03eb777494759912f235f33cbcfadadf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endIndexValue (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, bool)</td>
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



<p>Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a03eb777494759912f235f33cbcfadadf">145</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a03eb777494759912f235f33cbcfadadf">endIndexValue</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endInlineHeader() {#a221ea4ee3970e79c64e1636f4ae11782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endInlineHeader ()</td>
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



<p>Definition at line 211 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a221ea4ee3970e79c64e1636f4ae11782">211</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a221ea4ee3970e79c64e1636f4ae11782">endInlineHeader</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endInlineMemberDoc() {#a67b1d012d99a13ef16fcc4ea599b2a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endInlineMemberDoc ()</td>
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



<p>Declaration at line 309 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1215 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67b1d012d99a13ef16fcc4ea599b2a06">1215</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a67b1d012d99a13ef16fcc4ea599b2a06">DocbookGenerator::endInlineMemberDoc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1216</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1217</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1218</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;&lt;/row&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1219</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endInlineMemberName() {#a01c30e96c02d55000d0c0282cba79924}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endInlineMemberName ()</td>
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



<p>Declaration at line 307 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1203 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01c30e96c02d55000d0c0282cba79924">1203</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a01c30e96c02d55000d0c0282cba79924">DocbookGenerator::endInlineMemberName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1204</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1205</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1206</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1207</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endInlineMemberType() {#af26580af0994f29308d81034cce3823d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endInlineMemberType ()</td>
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



<p>Declaration at line 305 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1191 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af26580af0994f29308d81034cce3823d">1191</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af26580af0994f29308d81034cce3823d">DocbookGenerator::endInlineMemberType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1192</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1193</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1194</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1195</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endItemList() {#af738e039ccb42d9da57626ff43ede2b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endItemList ()</td>
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



<p>Definition at line 147 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af738e039ccb42d9da57626ff43ede2b5">147</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af738e039ccb42d9da57626ff43ede2b5">endItemList</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endItemListItem() {#a950f3ae4aac5c5cd548e64bd81b2e980}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endItemListItem ()</td>
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



<p>Definition at line 152 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a950f3ae4aac5c5cd548e64bd81b2e980">152</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a950f3ae4aac5c5cd548e64bd81b2e980">endItemListItem</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endLabels() {#a2b4c585da080af5a62ca30a99c27ba01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endLabels ()</td>
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



<p>Declaration at line 313 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1023 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b4c585da080af5a62ca30a99c27ba01">1023</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">  <a href="#a2b4c585da080af5a62ca30a99c27ba01">DocbookGenerator::endLabels</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1024</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1025</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1026</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### endLocalToc() {#a74c7072c37b0f6ca58f077b0cdd0242e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endLocalToc ()</td>
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



<p>Declaration at line 316 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1424 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74c7072c37b0f6ca58f077b0cdd0242e">1424</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a74c7072c37b0f6ca58f077b0cdd0242e">DocbookGenerator::endLocalToc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1425</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1426</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.level &gt; <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.maxLevel) <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.level = <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.maxLevel;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1427</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.level&gt;1 &amp;&amp; <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.level &lt;= <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.maxLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1428</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1429</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/tocdiv&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1430</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.level--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1431</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1432</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/toc&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1433</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.</p>

</div>
</div>

### endMemberDeclaration() {#aa3041625348d5b377dabccf8d7b81782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberDeclaration (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 242 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa3041625348d5b377dabccf8d7b81782">242</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa3041625348d5b377dabccf8d7b81782">endMemberDeclaration</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endMemberDescription() {#ad6bcc9d1588d49850a41ae5e2a1899cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberDescription ()</td>
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



<p>Definition at line 240 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6bcc9d1588d49850a41ae5e2a1899cd">240</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad6bcc9d1588d49850a41ae5e2a1899cd">endMemberDescription</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endMemberDoc() {#ab5c9f6c8cbc6591f1a9763d5c233a8f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberDoc (bool)</td>
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



<p>Declaration at line 230 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 924 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5c9f6c8cbc6591f1a9763d5c233a8f9">924</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab5c9f6c8cbc6591f1a9763d5c233a8f9">DocbookGenerator::endMemberDoc</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">925</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">926</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">927</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;&lt;/para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">928</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endMemberDocList() {#accf1f2e363b93a552fb4d3aeb09e6ff2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberDocList ()</td>
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



<p>Declaration at line 207 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1339 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#accf1f2e363b93a552fb4d3aeb09e6ff2">1339</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#accf1f2e363b93a552fb4d3aeb09e6ff2">DocbookGenerator::endMemberDocList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### endMemberDocName() {#a47879780f767bfd2f4ffcfaa105d8866}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberDocName ()</td>
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



<p>Declaration at line 280 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 968 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a47879780f767bfd2f4ffcfaa105d8866">968</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a47879780f767bfd2f4ffcfaa105d8866">DocbookGenerator::endMemberDocName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### endMemberDocPrefixItem() {#a7d042582c83c4bf25dba8857f186e56d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberDocPrefixItem ()</td>
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



<p>Declaration at line 278 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1063 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d042582c83c4bf25dba8857f186e56d">1063</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7d042582c83c4bf25dba8857f186e56d">DocbookGenerator::endMemberDocPrefixItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endMemberDocSimple() {#a45cd1dbe07a7c47ec3209b9fe1b92c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberDocSimple (bool)</td>
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



<p>Declaration at line 303 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1176 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a45cd1dbe07a7c47ec3209b9fe1b92c0d">1176</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a45cd1dbe07a7c47ec3209b9fe1b92c0d">DocbookGenerator::endMemberDocSimple</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* isEnum */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1177</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1178</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1179</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/tbody&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1180</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/tgroup&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1181</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1182</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1183</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endMemberGroup() {#a22265d3dc6b9ae14e0f5db49a0b4f22a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberGroup (bool)</td>
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



<p>Declaration at line 225 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 986 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22265d3dc6b9ae14e0f5db49a0b4f22a">986</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a22265d3dc6b9ae14e0f5db49a0b4f22a">DocbookGenerator::endMemberGroup</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/simplesect&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endMemberGroupDocs() {#ab056fe61e03329c403886763b05029f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberGroupDocs ()</td>
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



<p>Definition at line 223 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab056fe61e03329c403886763b05029f9">223</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab056fe61e03329c403886763b05029f9">endMemberGroupDocs</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endMemberGroupHeader() {#a2f941a481c8539d5ea65daf45d7d694b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberGroupHeader ()</td>
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



<p>Declaration at line 221 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 977 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2f941a481c8539d5ea65daf45d7d694b">977</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2f941a481c8539d5ea65daf45d7d694b">DocbookGenerator::endMemberGroupHeader</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endMemberHeader() {#a6d97af565fba4f9b4b8df0ee218a7b19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberHeader ()</td>
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



<p>Declaration at line 203 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 761 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d97af565fba4f9b4b8df0ee218a7b19">761</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6d97af565fba4f9b4b8df0ee218a7b19">DocbookGenerator::endMemberHeader</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endMemberItem() {#a29bb57d53d4ef49984943752371d80a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberItem (<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a>)</td>
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



<p>Declaration at line 215 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 818 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a29bb57d53d4ef49984943752371d80a9">818</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a29bb57d53d4ef49984943752371d80a9">DocbookGenerator::endMemberItem</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endMemberList() {#ae3b1fb5838ed0231423eb95a41173078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberList ()</td>
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



<p>Declaration at line 209 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 801 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3b1fb5838ed0231423eb95a41173078">801</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae3b1fb5838ed0231423eb95a41173078">DocbookGenerator::endMemberList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>[<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>]) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/listitem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>[<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>] = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;/itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a> = (<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>&gt; 0 ?  <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a> - 1 : 0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>[<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>]) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/simplesect&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>[<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>] = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>, <a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>, <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endMemberSections() {#a576ba898a2b833304ffaee52a9aee2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberSections ()</td>
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



<p>Definition at line 199 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a576ba898a2b833304ffaee52a9aee2be">199</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a576ba898a2b833304ffaee52a9aee2be">endMemberSections</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endMemberSubtitle() {#a8c63d39214124f23059f9a6f2fb4dd1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberSubtitle ()</td>
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



<p>Definition at line 205 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8c63d39214124f23059f9a6f2fb4dd1d">205</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8c63d39214124f23059f9a6f2fb4dd1d">endMemberSubtitle</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endMemberTemplateParams() {#aa45cce2f709a04a6a5c741b5d2c43f2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endMemberTemplateParams (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 217 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1126 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa45cce2f709a04a6a5c741b5d2c43f2d">1126</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa45cce2f709a04a6a5c741b5d2c43f2d">DocbookGenerator::endMemberTemplateParams</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1127</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1128</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1129</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1130</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1131</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endPageDoc() {#a9388e552fa8c8e18d8b03e43de804022}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endPageDoc ()</td>
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



<p>Definition at line 273 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9388e552fa8c8e18d8b03e43de804022">273</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9388e552fa8c8e18d8b03e43de804022">endPageDoc</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endPageRef() {#a0e98c2ae5445679208c1207c7e8fd650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endPageRef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 194 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0e98c2ae5445679208c1207c7e8fd650">194</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e98c2ae5445679208c1207c7e8fd650">endPageRef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endParagraph() {#a9d5757a3649f96aaaeef61ade2f1b067}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endParagraph ()</td>
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



<p>Declaration at line 157 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 743 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9d5757a3649f96aaaeef61ade2f1b067">743</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9d5757a3649f96aaaeef61ade2f1b067">DocbookGenerator::endParagraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endParameterDefVal() {#a852205da1a99f864d0a1c96143c3b671}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endParameterDefVal ()</td>
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



<p>Declaration at line 288 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1115 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a852205da1a99f864d0a1c96143c3b671">1115</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a852205da1a99f864d0a1c96143c3b671">DocbookGenerator::endParameterDefVal</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1116</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1117</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1118</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1119</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endParameterExtra() {#ae91b64667df54c993df7fef86f2a57c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endParameterExtra (bool last, bool, bool closeBracket)</td>
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



<p>Declaration at line 286 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1098 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae91b64667df54c993df7fef86f2a57c9">1098</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae91b64667df54c993df7fef86f2a57c9">DocbookGenerator::endParameterExtra</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> last,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/*emptyList*/</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> closeBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1099</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1100</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1101</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (last &amp;&amp; closeBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1102</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1103</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1104</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1105</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endParameterList() {#ae73f06b90526d3d375eafac0ae711af5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endParameterList ()</td>
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



<p>Declaration at line 290 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 865 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae73f06b90526d3d375eafac0ae711af5">865</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae73f06b90526d3d375eafac0ae711af5">DocbookGenerator::endParameterList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### endParameterName() {#aa2de284dbf9b27c95a81298ebff29a7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endParameterName ()</td>
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



<p>Declaration at line 284 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1088 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa2de284dbf9b27c95a81298ebff29a7d">1088</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa2de284dbf9b27c95a81298ebff29a7d">DocbookGenerator::endParameterName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1089</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1090</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1091</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### endParameterType() {#a0ae9695b1371e245c5e4b458acae99ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endParameterType ()</td>
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



<p>Definition at line 282 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0ae9695b1371e245c5e4b458acae99ed">282</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0ae9695b1371e245c5e4b458acae99ed">endParameterType</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endPlainFile() {#a2d188192c029b20f6505b7b79b8f288f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endPlainFile ()</td>
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



<p>Definition at line 321 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2d188192c029b20f6505b7b79b8f288f">321</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2d188192c029b20f6505b7b79b8f288f">endPlainFile</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#aaacf2b4efc09a2c06b9dd8cc2af69046">OutputGenerator::endPlainFile</a>(); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#aaacf2b4efc09a2c06b9dd8cc2af69046">OutputGenerator::endPlainFile</a>.</p>


<p>Referenced by <a href="#aefb08482f742251ae543aeb57983b335">endFile</a>.</p>

</div>
</div>

### endProjectNumber() {#a2cf173307e9344cbbe45d4ccdae94807}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endProjectNumber ()</td>
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



<p>Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2cf173307e9344cbbe45d4ccdae94807">134</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2cf173307e9344cbbe45d4ccdae94807">endProjectNumber</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endQuickIndices() {#ae2a279cfe88218bf0526fb0a5c2ca51f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endQuickIndices ()</td>
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



<p>Definition at line 263 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae2a279cfe88218bf0526fb0a5c2ca51f">263</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae2a279cfe88218bf0526fb0a5c2ca51f">endQuickIndices</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### endSection() {#ac3c2a2d5f7ee268ca127a30fcaa78fe0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endSection (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a>)</td>
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



<p>Declaration at line 176 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1138 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac3c2a2d5f7ee268ca127a30fcaa78fe0">1138</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac3c2a2d5f7ee268ca127a30fcaa78fe0">DocbookGenerator::endSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,<a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1139</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1140</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1141</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1142</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1143</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endSmall() {#a1f0fa2e1d6f9a5c11796e884ae962afc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endSmall ()</td>
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



<p>Definition at line 171 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f0fa2e1d6f9a5c11796e884ae962afc">171</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1f0fa2e1d6f9a5c11796e884ae962afc">endSmall</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endTextBlock() {#a6684626f228c4b3386f33b9d0e1cb000}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endTextBlock (bool)</td>
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



<p>Declaration at line 275 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 898 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6684626f228c4b3386f33b9d0e1cb000">898</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6684626f228c4b3386f33b9d0e1cb000">DocbookGenerator::endTextBlock</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">901</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">902</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">903</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">904</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/programlisting&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">905</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">906</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endTextLink() {#a8f7bdbae7f979fc69d532fd791b4fa44}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endTextLink ()</td>
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



<p>Definition at line 192 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8f7bdbae7f979fc69d532fd791b4fa44">192</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8f7bdbae7f979fc69d532fd791b4fa44">endTextLink</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### endTitleHead() {#aca2bba69055abb8a7a7ea9ce8ce7f11f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endTitleHead (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Declaration at line 137 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 934 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca2bba69055abb8a7a7ea9ce8ce7f11f">934</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aca2bba69055abb8a7a7ea9ce8ce7f11f">DocbookGenerator::endTitleHead</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">935</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">936</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">937</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">938</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ac174bf305a6b97803492e067a2f8dd77">addIndexTerm</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>, name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">939</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ac174bf305a6b97803492e067a2f8dd77">addIndexTerm</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### endTocEntry() {#a42a2541faf3a23582c34b87fd29d4f57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endTocEntry (const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * si)</td>
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



<p>Declaration at line 318 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1465 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a42a2541faf3a23582c34b87fd29d4f57">1465</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a42a2541faf3a23582c34b87fd29d4f57">DocbookGenerator::endTocEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1466</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1467</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> <a href="#a77480edd4c5054fa1834ff3b2dcd3db5">type</a> = si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#ad3818ca1a9c067d97176dcbaf7022d9e">type</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1468</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nextLevel = <a href="#a77480edd4c5054fa1834ff3b2dcd3db5">type</a>.level();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1469</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a77480edd4c5054fa1834ff3b2dcd3db5">type</a>.isSection() &amp;&amp; nextLevel &lt;= <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.maxLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1470</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1471</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/tocentry&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1472</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.inLi[nextLevel]=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1473</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.level = nextLevel;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1474</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1475</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>, <a href="#a77480edd4c5054fa1834ff3b2dcd3db5">type</a> and <a href="/web-doxygen/docs/api/classes/sectioninfo/#ad3818ca1a9c067d97176dcbaf7022d9e">SectionInfo::type</a>.</p>

</div>
</div>

### endTypewriter() {#a2f14bcd9d6629e6ec18be7c82343d852}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::endTypewriter ()</td>
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



<p>Declaration at line 162 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 884 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2f14bcd9d6629e6ec18be7c82343d852">884</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2f14bcd9d6629e6ec18be7c82343d852">DocbookGenerator::endTypewriter</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/computeroutput&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### exceptionEntry() {#a10ee707ef187621006c30d021aaca34d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::exceptionEntry (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; prefix, bool closeBracket)</td>
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



<p>Declaration at line 291 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1068 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a10ee707ef187621006c30d021aaca34d">1068</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a10ee707ef187621006c30d021aaca34d">DocbookGenerator::exceptionEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> closeBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1075</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (closeBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1076</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1077</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">")"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1078</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1079</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1080</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.</p>

</div>
</div>

### insertMemberAlign() {#afc2f215c948518de991a642f6a021635}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::insertMemberAlign (bool)</td>
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



<p>Definition at line 226 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc2f215c948518de991a642f6a021635">226</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afc2f215c948518de991a642f6a021635">insertMemberAlign</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### insertMemberAlignLeft() {#a5e10e2665a803a6c5c931050172ea4b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::insertMemberAlignLeft (<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a>, bool)</td>
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



<p>Definition at line 227 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e10e2665a803a6c5c931050172ea4b1">227</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5e10e2665a803a6c5c931050172ea4b1">insertMemberAlignLeft</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### lastIndexPage() {#a3d3a346fb2272e6241e3b5cd75cf0b0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::lastIndexPage ()</td>
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



<p>Definition at line 276 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3d3a346fb2272e6241e3b5cd75cf0b0e">276</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3d3a346fb2272e6241e3b5cd75cf0b0e">lastIndexPage</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### lineBreak() {#a1239152bed92bc91f6a1ddba37671a29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::lineBreak (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 177 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 874 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1239152bed92bc91f6a1ddba37671a29">874</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1239152bed92bc91f6a1ddba37671a29">DocbookGenerator::lineBreak</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;?linebreak?&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startAnonTypeScope() {#a72485dc1f19c70c869b6807d1ce1b8e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startAnonTypeScope (int)</td>
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



<p>Definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72485dc1f19c70c869b6807d1ce1b8e5">212</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a72485dc1f19c70c869b6807d1ce1b8e5">startAnonTypeScope</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startBold() {#ac90cbd84bc41a572f9f99ca23587847f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startBold ()</td>
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



<p>Declaration at line 159 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 823 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac90cbd84bc41a572f9f99ca23587847f">823</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac90cbd84bc41a572f9f99ca23587847f">DocbookGenerator::startBold</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;emphasis role=\"strong\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startCallGraph() {#a0f1823b3bff5917f7cc686c747b2e500}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startCallGraph ()</td>
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



<p>Declaration at line 257 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1317 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f1823b3bff5917f7cc686c747b2e500">1317</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0f1823b3bff5917f7cc686c747b2e500">DocbookGenerator::startCallGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startCenter() {#aaea0ab82cc8fde7fb6b7b870fe1f5c61}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startCenter ()</td>
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



<p>Definition at line 168 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaea0ab82cc8fde7fb6b7b870fe1f5c61">168</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaea0ab82cc8fde7fb6b7b870fe1f5c61">startCenter</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startClassDiagram() {#a9f0bbee1b9f39353827fe1cb34aa6c71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startClassDiagram ()</td>
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



<p>Declaration at line 249 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 991 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f0bbee1b9f39353827fe1cb34aa6c71">991</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9f0bbee1b9f39353827fe1cb34aa6c71">DocbookGenerator::startClassDiagram</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">994</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">995</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startCompoundTemplateParams() {#a9b3a91c273834c43c7b48e2f0e8712d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startCompoundTemplateParams ()</td>
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



<p>Declaration at line 218 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1040 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b3a91c273834c43c7b48e2f0e8712d6">1040</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9b3a91c273834c43c7b48e2f0e8712d6">DocbookGenerator::startCompoundTemplateParams</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1041</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1042</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1043</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;simplesect&gt;&lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1044</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startConstraintDocs() {#adcaba85a73024c0104286c6480b1aaeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startConstraintDocs ()</td>
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



<p>Declaration at line 298 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1370 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adcaba85a73024c0104286c6480b1aaeb">1370</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adcaba85a73024c0104286c6480b1aaeb">DocbookGenerator::startConstraintDocs</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startConstraintList() {#a57ecb947b9d729a32204364b0be5f712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startConstraintList (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; header)</td>
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



<p>Declaration at line 293 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1344 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a57ecb947b9d729a32204364b0be5f712">1344</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a57ecb947b9d729a32204364b0be5f712">DocbookGenerator::startConstraintList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;header)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;simplesect&gt;&lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aea69ff69be259d30ee167aa920746fab">docify</a>(header);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#aea69ff69be259d30ee167aa920746fab">docify</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startConstraintParam() {#a51f8405b195722cee84834e0b17f4c6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startConstraintParam ()</td>
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



<p>Declaration at line 294 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1351 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a51f8405b195722cee84834e0b17f4c6e">1351</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a51f8405b195722cee84834e0b17f4c6e">DocbookGenerator::startConstraintParam</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;&lt;emphasis role=\"strong\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startConstraintType() {#a418a7b6baf025267bf10fe0b4a38c367}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startConstraintType ()</td>
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



<p>Declaration at line 296 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1360 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a418a7b6baf025267bf10fe0b4a38c367">1360</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a418a7b6baf025267bf10fe0b4a38c367">DocbookGenerator::startConstraintType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startContents() {#ad92f550c473ab4d6fc714ed633fd2bbc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startContents ()</td>
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



<p>Definition at line 270 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad92f550c473ab4d6fc714ed633fd2bbc">270</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad92f550c473ab4d6fc714ed633fd2bbc">startContents</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startDescForItem() {#a50c0a3308c5ae4a4740799c07c8b160f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startDescForItem ()</td>
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



<p>Definition at line 166 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a50c0a3308c5ae4a4740799c07c8b160f">166</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a50c0a3308c5ae4a4740799c07c8b160f">startDescForItem</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startDescTable() {#afb8929ed5f608c71ef0d67c9bd2713a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startDescTable (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const bool hasInits)</td>
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



<p>Declaration at line 181 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1221 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afb8929ed5f608c71ef0d67c9bd2713a8">1221</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afb8929ed5f608c71ef0d67c9bd2713a8">DocbookGenerator::startDescTable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasInits)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1222</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1223</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1224</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ncols = (hasInits?3:2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1225</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;informaltable frame=\"all\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1226</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>(title) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1227</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;tgroup cols=\""</span><span class="doxyHighlight"> &lt;&lt; ncols &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" align=\"left\" colsep=\"1\" rowsep=\"1\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1228</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1229</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;colspec colname='c"</span><span class="doxyHighlight"> &lt;&lt; i++ &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1230</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hasInits) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;colspec colname='c"</span><span class="doxyHighlight"> &lt;&lt; i++ &lt;&lt; </span><span class="doxyHighlightStringLiteral">"' align='right'/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1231</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;colspec colname='c"</span><span class="doxyHighlight"> &lt;&lt; i++ &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1232</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tbody&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1233</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1234</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### startDescTableData() {#a155219c2c52cacd61c75a34b59e16b4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startDescTableData ()</td>
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



<p>Declaration at line 189 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1279 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a155219c2c52cacd61c75a34b59e16b4e">1279</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a155219c2c52cacd61c75a34b59e16b4e">DocbookGenerator::startDescTableData</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1280</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1281</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1282</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;&lt;entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1283</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startDescTableInit() {#aa64e6f62df30c7d3da3c18c9e311ef96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startDescTableInit ()</td>
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



<p>Declaration at line 187 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1268 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa64e6f62df30c7d3da3c18c9e311ef96">1268</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa64e6f62df30c7d3da3c18c9e311ef96">DocbookGenerator::startDescTableInit</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1269</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1270</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1271</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/entry&gt;&lt;entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1272</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startDescTableRow() {#ab8b9cff7a3e28360c3b659533fccbfda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startDescTableRow ()</td>
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



<p>Declaration at line 183 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1245 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab8b9cff7a3e28360c3b659533fccbfda">1245</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab8b9cff7a3e28360c3b659533fccbfda">DocbookGenerator::startDescTableRow</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1246</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1247</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1248</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;row&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1249</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1250</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startDescTableTitle() {#ad6d257b8715c635fbeb2fce4183749c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startDescTableTitle ()</td>
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



<p>Declaration at line 185 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1258 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6d257b8715c635fbeb2fce4183749c4">1258</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad6d257b8715c635fbeb2fce4183749c4">DocbookGenerator::startDescTableTitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1259</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1260</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1261</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startDirDepGraph() {#a987d5becf1294c93b3d7346b07dd51f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startDirDepGraph ()</td>
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



<p>Declaration at line 259 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1326 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a987d5becf1294c93b3d7346b07dd51f5">1326</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a987d5becf1294c93b3d7346b07dd51f5">DocbookGenerator::startDirDepGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startDotGraph() {#abc8a470c44572d5b386f47bb53a9d519}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startDotGraph ()</td>
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



<p>Declaration at line 251 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1299 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abc8a470c44572d5b386f47bb53a9d519">1299</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abc8a470c44572d5b386f47bb53a9d519">DocbookGenerator::startDotGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1300</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1301</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1302</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startDoxyAnchor() {#ab575d0e0e347d711d242bdc7fd8c7648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startDoxyAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; manName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; args)</td>
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



<p>Declaration at line 231 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 940 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab575d0e0e347d711d242bdc7fd8c7648">940</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab575d0e0e347d711d242bdc7fd8c7648">DocbookGenerator::startDoxyAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">941</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">942</span><span class="doxyLineContent"><span class="doxyHighlight">                                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>[<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>] &amp;&amp; !<a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a> &amp;&amp; !<a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a>) <a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;anchor xml:id=\"_"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(fName) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; anchor &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a>, <a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a>, <a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>, <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>, <a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>.</p>

</div>
</div>

### startEmphasis() {#a4d1419af8e3808bc8876a8f7ac9d0b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startEmphasis ()</td>
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



<p>Definition at line 163 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4d1419af8e3808bc8876a8f7ac9d0b2c">163</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4d1419af8e3808bc8876a8f7ac9d0b2c">startEmphasis</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startExamples() {#aaac726241831c07dc4733f0e63dab3e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startExamples ()</td>
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



<p>Declaration at line 172 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1027 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaac726241831c07dc4733f0e63dab3e1">1027</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaac726241831c07dc4733f0e63dab3e1">DocbookGenerator::startExamples</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1028</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1029</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1030</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;simplesect&gt;&lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1031</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aea69ff69be259d30ee167aa920746fab">docify</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExamples());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1032</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1033</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#aea69ff69be259d30ee167aa920746fab">docify</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.</p>

</div>
</div>

### startFile() {#a7a82873f4a7eeacb88ef535768b311f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; manName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, int id, int hierarchyLevel)</td>
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



<p>Declaration at line 125 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 392 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a82873f4a7eeacb88ef535768b311f4">392</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7a82873f4a7eeacb88ef535768b311f4">DocbookGenerator::startFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>=name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> pageName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileType=</span><span class="doxyHighlightStringLiteral">"section"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> == </span><span class="doxyHighlightStringLiteral">"refman"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>=</span><span class="doxyHighlightStringLiteral">"index"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">    fileType=</span><span class="doxyHighlightStringLiteral">"book"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a> == </span><span class="doxyHighlightStringLiteral">"index"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>=</span><span class="doxyHighlightStringLiteral">"mainpage"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">    fileType=</span><span class="doxyHighlightStringLiteral">"chapter"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">  pageName = <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a> = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6cc78f4946029df8c7135fbf36e625e4">relativePathToRoot</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>.endsWith(</span><span class="doxyHighlightStringLiteral">".xml"</span><span class="doxyHighlight">)) <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>+=</span><span class="doxyHighlightStringLiteral">".xml"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af357a86f84b841c7a0d1a8e52d644f69">startPlainFile</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>-&gt;setRelativePath(<a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>-&gt;setSourceFileName(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">fileName</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aff246cfd65c7cf0982c9b6b39155fc9e">m_pageLinks</a> = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;?xml version='1.0' encoding='UTF-8' standalone='no'?&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;"</span><span class="doxyHighlight"> &lt;&lt; fileType &lt;&lt; </span><span class="doxyHighlightStringLiteral">" xmlns=\"http://docbook.org/ns/docbook\" version=\"5.0\" xmlns:xlink=\"http://www.w3.org/1999/xlink\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!pageName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" xml:id=\"_"</span><span class="doxyHighlight"> &lt;&lt;  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(pageName) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" xml:lang=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trISOLang() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#ae347a53e8ee0d9c43c0590134c8e965d">OutputGenerator::fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a>, <a href="#aff246cfd65c7cf0982c9b6b39155fc9e">m_pageLinks</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6cc78f4946029df8c7135fbf36e625e4">relativePathToRoot</a>, <a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a>, <a href="#af357a86f84b841c7a0d1a8e52d644f69">startPlainFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.</p>

</div>
</div>

### startGroupCollaboration() {#a1c5271d755874098863c487bfdf49ad8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startGroupCollaboration ()</td>
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



<p>Declaration at line 255 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1290 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c5271d755874098863c487bfdf49ad8">1290</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1c5271d755874098863c487bfdf49ad8">DocbookGenerator::startGroupCollaboration</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1291</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1292</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1293</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startGroupHeader() {#ac651122c0ac17ea4be13f8a4d71c3efa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startGroupHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, int extraIndentLevel)</td>
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



<p>Declaration at line 196 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 833 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac651122c0ac17ea4be13f8a4d71c3efa">833</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac651122c0ac17ea4be13f8a4d71c3efa">DocbookGenerator::startGroupHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> extraIndentLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>(</span><span class="doxyHighlightStringLiteral">"m_inLevel "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>(</span><span class="doxyHighlightStringLiteral">"extraIndentLevel "</span><span class="doxyHighlight"> &lt;&lt; extraIndentLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>[<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>]) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/simplesect&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>[<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>] = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a> != -1) <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a> == extraIndentLevel) <a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a> = extraIndentLevel;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9872f2ebb33a85b7fff7268fee91a977">openSection</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a>, <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a>, <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>, <a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>, <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="#a9872f2ebb33a85b7fff7268fee91a977">openSection</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### startHeaderSection() {#a8859f548070610da1b29fc339d390fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startHeaderSection ()</td>
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



<p>Definition at line 200 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8859f548070610da1b29fc339d390fd2">200</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8859f548070610da1b29fc339d390fd2">startHeaderSection</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startInclDepGraph() {#abbd96aa5d90d0337ba3cfcf717052902}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startInclDepGraph ()</td>
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



<p>Declaration at line 253 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1308 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abbd96aa5d90d0337ba3cfcf717052902">1308</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abbd96aa5d90d0337ba3cfcf717052902">DocbookGenerator::startInclDepGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1309</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1310</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startIndent() {#a5f52440d2fe3025eaf9f7853974c44cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startIndent ()</td>
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



<p>Definition at line 246 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5f52440d2fe3025eaf9f7853974c44cd">246</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5f52440d2fe3025eaf9f7853974c44cd">startIndent</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startIndexItem() {#a165b08f7f0cefa958779ddd2faf7e965}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 149 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a165b08f7f0cefa958779ddd2faf7e965">149</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a165b08f7f0cefa958779ddd2faf7e965">startIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startIndexKey() {#a2c7a1105dc4b6faa8e81088a35f0a47d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startIndexKey ()</td>
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



<p>Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2c7a1105dc4b6faa8e81088a35f0a47d">142</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2c7a1105dc4b6faa8e81088a35f0a47d">startIndexKey</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startIndexList() {#a0f3154fbaf3e01e59f00c50f3f34c6d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startIndexList ()</td>
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



<p>Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f3154fbaf3e01e59f00c50f3f34c6d3">140</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0f3154fbaf3e01e59f00c50f3f34c6d3">startIndexList</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startIndexListItem() {#af8a68054558e4135bf42a6d444fdb71c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startIndexListItem ()</td>
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



<p>Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af8a68054558e4135bf42a6d444fdb71c">138</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af8a68054558e4135bf42a6d444fdb71c">startIndexListItem</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startIndexSection() {#a19720fb8fa237272681c6328aed372c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startIndexSection (<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a> is)</td>
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



<p>Declaration at line 130 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 448 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19720fb8fa237272681c6328aed372c1">448</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a19720fb8fa237272681c6328aed372c1">DocbookGenerator::startIndexSection</a>(<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a> is)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>(</span><span class="doxyHighlightStringLiteral">"IndexSection "</span><span class="doxyHighlight"> &lt;&lt; is)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (is)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ad91b65ea5e9c3686b3a0078e32d9133f">IndexSection::isTitlePageStart</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> dbk_projectName = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PROJECT_NAME);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;info&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>(dbk_projectName) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/info&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a2d64103a58ee3a5192221119a31dfe28">IndexSection::isTitlePageAuthor</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a01093bf5aa5f29736aab5a03d438d428">IndexSection::isMainPage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a73fc6dc74e3caab626fcb788e489c006">IndexSection::isModuleIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//Module Index\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a7a9b27e109f6dd8dde1ec3139e9c6636">IndexSection::isTopicIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//Module Index\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7abc266c3a59d8d164fe6e05eb2bbd6a55">IndexSection::isDirIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//Directory Index\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ac72f48c94b82bf532b2eb7e9dd1c2345">IndexSection::isNamespaceIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//Namespace Index\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a7ed89b8fd01df70d408e1571d145c1c1">IndexSection::isConceptIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//Concept Index\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a5dc0feebd328fce66fdf10940d325c13">IndexSection::isClassHierarchyIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//Hierarchical Index\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a98d9a43fdd6c458d80251cbb6712f7d5">IndexSection::isCompoundIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//m_t &lt;&lt; "{"; //Class Index}\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a2f028c6e71fd63fb9e23efb217b8c4a7">IndexSection::isFileIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//Annotated File Index\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a96414d5dc6d8784abb414cf1b04b3218">IndexSection::isPageIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//Annotated Page Index\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a56f0fdd7e2c9390989e1075d48ce7bbd">IndexSection::isModuleDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7aea69f72466bdd3c72c5c6b5bc6ee6cca">IndexSection::isTopicDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a55e8f77f5eb1557c27dad33a4ee24165">IndexSection::isDirDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ad8796f241437df840983ae62b0ec6bc5">IndexSection::isNamespaceDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7aba356fa1d95f3ad5fe998378562d2968">IndexSection::isConceptDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a8dab680d3e9e897983a1b9e7968c82c7">IndexSection::isClassDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a3c622c2f13fd1e39bf3b1fdad4a2ae2e">IndexSection::isFileDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a87c7dab68957c9a53129b71dc0a90635">IndexSection::isExampleDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;chapter&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a41de1f39ac1ee1329a1374b2da6bfc70">IndexSection::isPageDocumentation</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7af311c10a314387cf7b6310240aa89bb0">IndexSection::isPageDocumentation2</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ab520ec9da3284768c754fbbf4e907e08">IndexSection::isEndIndex</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a8dab680d3e9e897983a1b9e7968c82c7">isClassDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a5dc0feebd328fce66fdf10940d325c13">isClassHierarchyIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a98d9a43fdd6c458d80251cbb6712f7d5">isCompoundIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7aba356fa1d95f3ad5fe998378562d2968">isConceptDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a7ed89b8fd01df70d408e1571d145c1c1">isConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a55e8f77f5eb1557c27dad33a4ee24165">isDirDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7abc266c3a59d8d164fe6e05eb2bbd6a55">isDirIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ab520ec9da3284768c754fbbf4e907e08">isEndIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a87c7dab68957c9a53129b71dc0a90635">isExampleDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a3c622c2f13fd1e39bf3b1fdad4a2ae2e">isFileDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a2f028c6e71fd63fb9e23efb217b8c4a7">isFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a01093bf5aa5f29736aab5a03d438d428">isMainPage</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a56f0fdd7e2c9390989e1075d48ce7bbd">isModuleDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a73fc6dc74e3caab626fcb788e489c006">isModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ad8796f241437df840983ae62b0ec6bc5">isNamespaceDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ac72f48c94b82bf532b2eb7e9dd1c2345">isNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a41de1f39ac1ee1329a1374b2da6bfc70">isPageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7af311c10a314387cf7b6310240aa89bb0">isPageDocumentation2</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a96414d5dc6d8784abb414cf1b04b3218">isPageIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a2d64103a58ee3a5192221119a31dfe28">isTitlePageAuthor</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7ad91b65ea5e9c3686b3a0078e32d9133f">isTitlePageStart</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7aea69f72466bdd3c72c5c6b5bc6ee6cca">isTopicDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7a7a9b27e109f6dd8dde1ec3139e9c6636">isTopicIndex</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startIndexValue() {#a28cb580557bb6f9808d05cc5bcc3b4bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startIndexValue (bool)</td>
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



<p>Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28cb580557bb6f9808d05cc5bcc3b4bf">144</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a28cb580557bb6f9808d05cc5bcc3b4bf">startIndexValue</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startInlineHeader() {#a2fdb74bc21106b41053aea156ef99b2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startInlineHeader ()</td>
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



<p>Definition at line 210 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2fdb74bc21106b41053aea156ef99b2c">210</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2fdb74bc21106b41053aea156ef99b2c">startInlineHeader</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startInlineMemberDoc() {#adaf7ed17f053cb14c26da75c9d7552d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startInlineMemberDoc ()</td>
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



<p>Declaration at line 308 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1209 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adaf7ed17f053cb14c26da75c9d7552d4">1209</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adaf7ed17f053cb14c26da75c9d7552d4">DocbookGenerator::startInlineMemberDoc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1210</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1211</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1212</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1213</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startInlineMemberName() {#af610006b0e0386c4f5762724f30c429c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startInlineMemberName ()</td>
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



<p>Declaration at line 306 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1197 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af610006b0e0386c4f5762724f30c429c">1197</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af610006b0e0386c4f5762724f30c429c">DocbookGenerator::startInlineMemberName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1198</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1199</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1200</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1201</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startInlineMemberType() {#ac81970c0218bab9e70c805e3fe2d1826}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startInlineMemberType ()</td>
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



<p>Declaration at line 304 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1185 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac81970c0218bab9e70c805e3fe2d1826">1185</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac81970c0218bab9e70c805e3fe2d1826">DocbookGenerator::startInlineMemberType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1186</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1187</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1188</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;row&gt;&lt;entry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1189</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startItemList() {#ae0410be0719eae1da884ade02d1612af}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startItemList ()</td>
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



<p>Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae0410be0719eae1da884ade02d1612af">146</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae0410be0719eae1da884ade02d1612af">startItemList</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startItemListItem() {#a24d221cf16ecc55edd136306797d289a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startItemListItem ()</td>
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



<p>Definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24d221cf16ecc55edd136306797d289a">151</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a24d221cf16ecc55edd136306797d289a">startItemListItem</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startLabels() {#a7ce24c2a590df467e4768a74958e7e22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startLabels ()</td>
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



<p>Declaration at line 311 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1011 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7ce24c2a590df467e4768a74958e7e22">1011</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">  <a href="#a7ce24c2a590df467e4768a74958e7e22">DocbookGenerator::startLabels</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1012</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1013</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1014</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startLocalToc() {#a07b3b950a4edb2d5d1d57125babf3e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startLocalToc (int level)</td>
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



<p>Declaration at line 315 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1415 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07b3b950a4edb2d5d1d57125babf3e57">1415</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a07b3b950a4edb2d5d1d57125babf3e57">DocbookGenerator::startLocalToc</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.level=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.maxLevel=level;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1419</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.inLi = <a href="/web-doxygen/docs/api/files/src/containers-h/#af473e8b17774fe44ba6746b9e7bff90a">BoolVector</a>(level+1,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1420</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;toc&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1421</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trRTFTableOfContents() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1422</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.</p>

</div>
</div>

### startMemberDeclaration() {#afecf0cbb2b97e57f44fa5df8acd422b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberDeclaration ()</td>
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



<p>Definition at line 241 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afecf0cbb2b97e57f44fa5df8acd422b1">241</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afecf0cbb2b97e57f44fa5df8acd422b1">startMemberDeclaration</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startMemberDescription() {#a4bbf1226470e991f2d1aac02fe3b443b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberDescription (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, bool)</td>
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



<p>Definition at line 239 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4bbf1226470e991f2d1aac02fe3b443b">239</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4bbf1226470e991f2d1aac02fe3b443b">startMemberDescription</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startMemberDoc() {#a8ae15cadac821acb3d6ecfb6c541d6b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberDoc (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; clname, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; memname, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, int memCount, int memTotal, bool)</td>
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



<p>Declaration at line 228 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 907 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ae15cadac821acb3d6ecfb6c541d6b9">907</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8ae15cadac821acb3d6ecfb6c541d6b9">DocbookGenerator::startMemberDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;clname, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;memname, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">908</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> memCount, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> memTotal, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">909</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">910</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>(</span><span class="doxyHighlightStringLiteral">"m_inLevel "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">911</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9872f2ebb33a85b7fff7268fee91a977">openSection</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">912</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>(title);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">913</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (memTotal&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">914</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">915</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;computeroutput&gt;["</span><span class="doxyHighlight"> &lt;&lt; memCount &lt;&lt; </span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight"> &lt;&lt; memTotal &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]&lt;/computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">916</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">917</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">918</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!memname.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; memname[0]!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">919</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">920</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ac174bf305a6b97803492e067a2f8dd77">addIndexTerm</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,memname,clname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">921</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ac174bf305a6b97803492e067a2f8dd77">addIndexTerm</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,clname,memname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">922</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">923</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ac174bf305a6b97803492e067a2f8dd77">addIndexTerm</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="#a9872f2ebb33a85b7fff7268fee91a977">openSection</a>.</p>

</div>
</div>

### startMemberDocList() {#a70de26cfb00cc50138102556da46e2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberDocList ()</td>
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



<p>Declaration at line 206 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1335 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70de26cfb00cc50138102556da46e2ce">1335</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a70de26cfb00cc50138102556da46e2ce">DocbookGenerator::startMemberDocList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startMemberDocName() {#a97e2055991080f05a37be7769cf3509c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberDocName (bool)</td>
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



<p>Declaration at line 279 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 963 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97e2055991080f05a37be7769cf3509c">963</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a97e2055991080f05a37be7769cf3509c">DocbookGenerator::startMemberDocName</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;&lt;computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startMemberDocPrefixItem() {#aa59a7da2611e101aa060c3455084255e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberDocPrefixItem ()</td>
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



<p>Declaration at line 277 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1058 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa59a7da2611e101aa060c3455084255e">1058</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa59a7da2611e101aa060c3455084255e">DocbookGenerator::startMemberDocPrefixItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1059</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1060</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1061</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startMemberDocSimple() {#a49908c3a630786d98fb499887b18d8f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberDocSimple (bool isEnum)</td>
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



<p>Declaration at line 302 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1150 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49908c3a630786d98fb499887b18d8f3">1150</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a49908c3a630786d98fb499887b18d8f3">DocbookGenerator::startMemberDocSimple</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1151</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1152</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1153</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> ncols=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1154</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1155</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isEnum)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1156</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1157</span><span class="doxyLineContent"><span class="doxyHighlight">    ncols = 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1158</span><span class="doxyLineContent"><span class="doxyHighlight">    title = <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trEnumerationValues();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1159</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1160</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1161</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1162</span><span class="doxyLineContent"><span class="doxyHighlight">    ncols = 3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1163</span><span class="doxyLineContent"><span class="doxyHighlight">    title = <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundMembers();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1164</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1165</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;table frame=\"all\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1166</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;title&gt;"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>(title) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/title&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1167</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;tgroup cols=\""</span><span class="doxyHighlight"> &lt;&lt; ncols &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" align=\"left\" colsep=\"1\" rowsep=\"1\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1168</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0; i &lt; ncols; i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1169</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1170</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;colspec colname='c"</span><span class="doxyHighlight"> &lt;&lt; i+1 &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1171</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1172</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;tbody&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1173</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1174</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.</p>

</div>
</div>

### startMemberGroup() {#a9be5e6aee43e8eaadf84e8adbd58a590}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberGroup ()</td>
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



<p>Declaration at line 224 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 982 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9be5e6aee43e8eaadf84e8adbd58a590">982</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9be5e6aee43e8eaadf84e8adbd58a590">DocbookGenerator::startMemberGroup</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startMemberGroupDocs() {#a310be7aaf9518ecf21dec09a0ed3bfd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberGroupDocs ()</td>
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



<p>Definition at line 222 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a310be7aaf9518ecf21dec09a0ed3bfd8">222</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a310be7aaf9518ecf21dec09a0ed3bfd8">startMemberGroupDocs</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startMemberGroupHeader() {#afdcc8344112747cd65cd80bdb2249933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberGroupHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, bool)</td>
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



<p>Declaration at line 220 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 972 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afdcc8344112747cd65cd80bdb2249933">972</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afdcc8344112747cd65cd80bdb2249933">DocbookGenerator::startMemberGroupHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;simplesect&gt;&lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startMemberHeader() {#a10f198594f85e92a681337af184d913d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, int typ)</td>
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



<p>Declaration at line 202 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 753 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a10f198594f85e92a681337af184d913d">753</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a10f198594f85e92a681337af184d913d">DocbookGenerator::startMemberHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;simplesect&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>[<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>] = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a>, <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### startMemberItem() {#a82557dc83927e00f34efb901409e04d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a>, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 214 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 811 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a82557dc83927e00f34efb901409e04d4">811</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a82557dc83927e00f34efb901409e04d4">DocbookGenerator::startMemberItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">MemberItemType</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>[<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>]) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/listitem&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"            &lt;listitem&gt;&lt;para&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>[<a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>] = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a>, <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### startMemberList() {#aa7454a8fe2d2ceafbc630ea57ce68d0b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberList ()</td>
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



<p>Declaration at line 208 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 795 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa7454a8fe2d2ceafbc630ea57ce68d0b">795</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa7454a8fe2d2ceafbc630ea57ce68d0b">DocbookGenerator::startMemberList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"        &lt;itemizedlist&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startMemberSections() {#ab76e2ad69e7649f9127d74c06bc93278}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberSections ()</td>
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



<p>Definition at line 198 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab76e2ad69e7649f9127d74c06bc93278">198</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab76e2ad69e7649f9127d74c06bc93278">startMemberSections</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startMemberSubtitle() {#a53f3f2e01a47d65a20615e1fb8e5d245}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberSubtitle ()</td>
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



<p>Definition at line 204 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53f3f2e01a47d65a20615e1fb8e5d245">204</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a53f3f2e01a47d65a20615e1fb8e5d245">startMemberSubtitle</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startMemberTemplateParams() {#a5fc122c54d1a0667d645062bed344a6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startMemberTemplateParams ()</td>
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



<p>Declaration at line 216 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1121 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fc122c54d1a0667d645062bed344a6a">1121</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5fc122c54d1a0667d645062bed344a6a">DocbookGenerator::startMemberTemplateParams</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1122</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1123</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1124</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startPageDoc() {#abf38a4b2f36d31a465f67498ce919c83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startPageDoc (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 272 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf38a4b2f36d31a465f67498ce919c83">272</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abf38a4b2f36d31a465f67498ce919c83">startPageDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startPageRef() {#ac6ffcbf4bd345ac9afabf49898b5890e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startPageRef ()</td>
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



<p>Definition at line 193 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac6ffcbf4bd345ac9afabf49898b5890e">193</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac6ffcbf4bd345ac9afabf49898b5890e">startPageRef</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startParagraph() {#a22b30d736cc0185909d9b3954a8e3f4e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startParagraph (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 156 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 737 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22b30d736cc0185909d9b3954a8e3f4e">737</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a22b30d736cc0185909d9b3954a8e3f4e">DocbookGenerator::startParagraph</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;para&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startParameterDefVal() {#aedc98fb288995aea0c0b83fc4eca50a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startParameterDefVal (const char * sep)</td>
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



<p>Declaration at line 287 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1108 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aedc98fb288995aea0c0b83fc4eca50a2">1108</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aedc98fb288995aea0c0b83fc4eca50a2">DocbookGenerator::startParameterDefVal</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *sep)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1109</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1110</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1111</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; sep;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1113</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startParameterExtra() {#a298ee3beaa40d4f406dba0ea7908a473}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startParameterExtra ()</td>
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



<p>Declaration at line 285 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1093 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a298ee3beaa40d4f406dba0ea7908a473">1093</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a298ee3beaa40d4f406dba0ea7908a473">DocbookGenerator::startParameterExtra</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1094</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1095</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1096</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>.</p>

</div>
</div>

### startParameterList() {#a05a82a3d67c8acbd8ef73ca8d6d77f1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startParameterList (bool openBracket)</td>
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



<p>Declaration at line 289 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 860 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a05a82a3d67c8acbd8ef73ca8d6d77f1c">860</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a05a82a3d67c8acbd8ef73ca8d6d77f1c">DocbookGenerator::startParameterList</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> openBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (openBracket) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"("</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startParameterName() {#a83ad153480a66966d9e1121e004b46e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startParameterName (bool)</td>
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



<p>Declaration at line 283 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1082 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a83ad153480a66966d9e1121e004b46e4">1082</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a83ad153480a66966d9e1121e004b46e4">DocbookGenerator::startParameterName</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1083</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1084</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1085</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1086</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startParameterType() {#a7e94634814ad6933ca72763614845a09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startParameterType (bool, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 281 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7e94634814ad6933ca72763614845a09">281</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7e94634814ad6933ca72763614845a09">startParameterType</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startPlainFile() {#af357a86f84b841c7a0d1a8e52d644f69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startPlainFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 320 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af357a86f84b841c7a0d1a8e52d644f69">320</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af357a86f84b841c7a0d1a8e52d644f69">startPlainFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6d2b81663565fee4440ef02fe9b3a197">OutputGenerator::startPlainFile</a>(name); }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/outputgenerator/#a6d2b81663565fee4440ef02fe9b3a197">OutputGenerator::startPlainFile</a>.</p>


<p>Referenced by <a href="#a7a82873f4a7eeacb88ef535768b311f4">startFile</a>.</p>

</div>
</div>

### startProjectNumber() {#a97781f8b5e046d402d50a6a49744acb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startProjectNumber ()</td>
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



<p>Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97781f8b5e046d402d50a6a49744acb0">133</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a97781f8b5e046d402d50a6a49744acb0">startProjectNumber</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startQuickIndices() {#aa50fb495205963cd96fc92210a406db8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startQuickIndices ()</td>
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



<p>Definition at line 262 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa50fb495205963cd96fc92210a406db8">262</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa50fb495205963cd96fc92210a406db8">startQuickIndices</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### startSection() {#aa0fe01b830ddb0d899e151aa389087c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startSection (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; lab, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a>)</td>
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



<p>Declaration at line 175 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1132 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0fe01b830ddb0d899e151aa389087c8">1132</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa0fe01b830ddb0d899e151aa389087c8">DocbookGenerator::startSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;lab,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,<a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1133</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1134</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1135</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a9872f2ebb33a85b7fff7268fee91a977">openSection</a>(</span><span class="doxyHighlightStringLiteral">"xml:id=\"_"</span><span class="doxyHighlight"> + <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(lab) + </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1136</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1137</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="#a9872f2ebb33a85b7fff7268fee91a977">openSection</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>.</p>

</div>
</div>

### startSmall() {#ae501cb3410c7ed6e7daefc2c6bff8bab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startSmall ()</td>
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



<p>Definition at line 170 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae501cb3410c7ed6e7daefc2c6bff8bab">170</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae501cb3410c7ed6e7daefc2c6bff8bab">startSmall</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startTextBlock() {#aeca4bf8edce633fa3faa7c1e38882363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startTextBlock (bool dense)</td>
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



<p>Declaration at line 274 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 889 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeca4bf8edce633fa3faa7c1e38882363">889</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aeca4bf8edce633fa3faa7c1e38882363">DocbookGenerator::startTextBlock</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> dense)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dense)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;programlisting linenumbering=\"unnumbered\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### startTextLink() {#a0cf8bbe3120d24b4bc0d254d14268296}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startTextLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 191 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0cf8bbe3120d24b4bc0d254d14268296">191</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0cf8bbe3120d24b4bc0d254d14268296">startTextLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### startTitleHead() {#a921181dfbb9226c3eef4536d2f06a242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startTitleHead (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Declaration at line 136 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 929 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a921181dfbb9226c3eef4536d2f06a242">929</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a921181dfbb9226c3eef4536d2f06a242">DocbookGenerator::startTitleHead</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">930</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">931</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">932</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;title&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">933</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### startTocEntry() {#a0afd80ec501374a1cdbdf674ec967b79}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startTocEntry (const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * si)</td>
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



<p>Declaration at line 317 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1435 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0afd80ec501374a1cdbdf674ec967b79">1435</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0afd80ec501374a1cdbdf674ec967b79">DocbookGenerator::startTocEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1436</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1437</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> <a href="#a77480edd4c5054fa1834ff3b2dcd3db5">type</a> = si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#ad3818ca1a9c067d97176dcbaf7022d9e">type</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1438</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a77480edd4c5054fa1834ff3b2dcd3db5">type</a>.isSection())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1439</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1440</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("  level=%d title=%s\n",level,qPrint(si-&gt;title));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1441</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nextLevel = <a href="#a77480edd4c5054fa1834ff3b2dcd3db5">type</a>.level();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1442</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nextLevel&gt;<a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1443</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1444</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=<a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.level;l&lt;nextLevel;l++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1445</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1446</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l &lt; <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.maxLevel) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;tocdiv&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1447</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1448</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1449</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nextLevel&lt;<a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1450</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1451</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l=<a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.level;l&gt;nextLevel;l--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1452</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1453</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.inLi[l]=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1454</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (l &lt;= <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.maxLevel) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"    &lt;/tocdiv&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1455</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1456</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1457</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (nextLevel &lt;= <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>.maxLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1458</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1459</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> label = <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>(si-&gt;<a href="/web-doxygen/docs/api/classes/sectioninfo/#a3028bd10d3288ef120bd833e0ebc57ab">label</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1460</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;tocentry&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1461</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1462</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1463</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>, <a href="/web-doxygen/docs/api/classes/sectioninfo/#a3028bd10d3288ef120bd833e0ebc57ab">SectionInfo::label</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>, <a href="#a77480edd4c5054fa1834ff3b2dcd3db5">type</a> and <a href="/web-doxygen/docs/api/classes/sectioninfo/#ad3818ca1a9c067d97176dcbaf7022d9e">SectionInfo::type</a>.</p>

</div>
</div>

### startTypewriter() {#a5e66bd3d7d003c6a3205b1febaa19958}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::startTypewriter ()</td>
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



<p>Declaration at line 161 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 879 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e66bd3d7d003c6a3205b1febaa19958">879</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5e66bd3d7d003c6a3205b1febaa19958">DocbookGenerator::startTypewriter</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a>) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### type() {#a77480edd4c5054fa1834ff3b2dcd3db5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputType DocbookGenerator::type ()</td>
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



<p>Definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a77480edd4c5054fa1834ff3b2dcd3db5">120</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> <a href="#a77480edd4c5054fa1834ff3b2dcd3db5">type</a>()</span><span class="doxyHighlightKeyword"> const override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a680ad2abb703e2cb60fbdddf8423315a">OutputType::Docbook</a>; }</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a680ad2abb703e2cb60fbdddf8423315a">Docbook</a>.</p>


<p>Referenced by <a href="#a42a2541faf3a23582c34b87fd29d4f57">endTocEntry</a> and <a href="#a0afd80ec501374a1cdbdf674ec967b79">startTocEntry</a>.</p>

</div>
</div>

### writeAnchor() {#a7134e69943d0a4a7ed1939735417851a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 174 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7134e69943d0a4a7ed1939735417851a">174</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7134e69943d0a4a7ed1939735417851a">writeAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### writeChar() {#afba9fe943d8c123f6e40256bdca2f5d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeChar (char c)</td>
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



<p>Declaration at line 154 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1050 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afba9fe943d8c123f6e40256bdca2f5d3">1050</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afba9fe943d8c123f6e40256bdca2f5d3">DocbookGenerator::writeChar</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1051</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1052</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1053</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> cs[2];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1054</span><span class="doxyLineContent"><span class="doxyHighlight">  cs[0]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1055</span><span class="doxyLineContent"><span class="doxyHighlight">  cs[1]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1056</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aea69ff69be259d30ee167aa920746fab">docify</a>(cs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1057</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="#aea69ff69be259d30ee167aa920746fab">docify</a>.</p>

</div>
</div>

### writeDoc() {#a2f2d4d689d7e1c05bd243f0b23242064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeDoc (const <a href="/web-doxygen/docs/api/classes/idocnodeast">IDocNodeAST</a> * node, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * ctx, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, int id)</td>
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



<p>Declaration at line 124 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 726 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2f2d4d689d7e1c05bd243f0b23242064">726</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2f2d4d689d7e1c05bd243f0b23242064">DocbookGenerator::writeDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/idocnodeast">IDocNodeAST</a> *ast,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *ctx,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">728</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> astImpl = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/docnodeast">DocNodeAST</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(ast);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (astImpl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docbookdocvisitor">DocbookDocVisitor</a> visitor(<a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a>,*<a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>,ctx?ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#adbe53b15923a143881154dd7c0f04f9b">getDefFileExtension</a>():<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(visitor,astImpl-&gt;root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">734</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/definition/#adbe53b15923a143881154dd7c0f04f9b">Definition::getDefFileExtension</a>, <a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### writeFooter() {#af59fcb6ef3fc574f346a35719889d4b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeFooter (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 129 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af59fcb6ef3fc574f346a35719889d4b4">129</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af59fcb6ef3fc574f346a35719889d4b4">writeFooter</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### writeGraphicalHierarchy() {#a0b12a50011caf4cb18e36d78a82c636d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeGraphicalHierarchy (<a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable">DotGfxHierarchyTable</a> &amp;)</td>
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



<p>Definition at line 261 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b12a50011caf4cb18e36d78a82c636d">261</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0b12a50011caf4cb18e36d78a82c636d">writeGraphicalHierarchy</a>(<a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable">DotGfxHierarchyTable</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### writeInheritedSectionTitle() {#af456dab6739ba95632af57ca113f2214}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeInheritedSectionTitle (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Declaration at line 243 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1406 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af456dab6739ba95632af57ca113f2214">1406</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af456dab6739ba95632af57ca113f2214">DocbookGenerator::writeInheritedSectionTitle</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/*id*/</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1410</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1411</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1412</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInheritedFrom(<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>(title), <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a311635f4bd437fd28ab5fe0f0309f15d">objectLinkToString</a>(ref, file, anchor, name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1413</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a311635f4bd437fd28ab5fe0f0309f15d">objectLinkToString</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>.</p>

</div>
</div>

### writeLabel() {#a3a9126201aae3ba3d2e48a2e7c9b5082}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeLabel (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; l, bool isLast)</td>
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



<p>Declaration at line 312 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1016 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a9126201aae3ba3d2e48a2e7c9b5082">1016</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">  <a href="#a3a9126201aae3ba3d2e48a2e7c9b5082">DocbookGenerator::writeLabel</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;l,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isLast)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1017</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1018</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1019</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;computeroutput&gt;["</span><span class="doxyHighlight"> &lt;&lt; l &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]&lt;/computeroutput&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1020</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isLast) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">", "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1021</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### writeLatexSpacing() {#a02aacfb4e28b9a83f0cc1ae519525192}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeLatexSpacing ()</td>
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



<p>Definition at line 236 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02aacfb4e28b9a83f0cc1ae519525192">236</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a02aacfb4e28b9a83f0cc1ae519525192">writeLatexSpacing</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### writeLogo() {#a84d793a7a3cfbef2635c31b9b47be6fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeLogo ()</td>
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



<p>Definition at line 266 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a84d793a7a3cfbef2635c31b9b47be6fd">266</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a84d793a7a3cfbef2635c31b9b47be6fd">writeLogo</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### writeNavigationPath() {#ab37bcd37222fea70d11024ed92294636}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeNavigationPath (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 265 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab37bcd37222fea70d11024ed92294636">265</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab37bcd37222fea70d11024ed92294636">writeNavigationPath</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### writeNonBreakableSpace() {#a1a4768269d4a67e9762f388db3ff6842}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeNonBreakableSpace (int n)</td>
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



<p>Declaration at line 179 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 869 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a4768269d4a67e9762f388db3ff6842">869</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1a4768269d4a67e9762f388db3ff6842">DocbookGenerator::writeNonBreakableSpace</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;i&lt;n;i++) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#160;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### writeObjectLink() {#a7c3028f84a8675c8b21ccae5a23e4286}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeObjectLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; f, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Declaration at line 158 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 789 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c3028f84a8675c8b21ccae5a23e4286">789</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7c3028f84a8675c8b21ccae5a23e4286">DocbookGenerator::writeObjectLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">                                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a311635f4bd437fd28ab5fe0f0309f15d">objectLinkToString</a>(ref,f,anchor,text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a311635f4bd437fd28ab5fe0f0309f15d">objectLinkToString</a>.</p>

</div>
</div>

### writePageLink() {#a53279dc86a635990c995e61bc3b7104c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writePageLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, bool first)</td>
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



<p>Declaration at line 132 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 713 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53279dc86a635990c995e61bc3b7104c">713</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a53279dc86a635990c995e61bc3b7104c">DocbookGenerator::writePageLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">714</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">  link.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"    &lt;xi:include href=\"%s.xml\" xmlns:xi=\"http://www.w3.org/2001/XInclude\"/&gt;\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">718</span><span class="doxyLineContent"><span class="doxyHighlight">               name.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// Buffer page links and write them after all sections are closed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aff246cfd65c7cf0982c9b6b39155fc9e">m_pageLinks</a> += link;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">724</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a>, <a href="#aff246cfd65c7cf0982c9b6b39155fc9e">m_pageLinks</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>.</p>


<p>Referenced by <a href="#a9a5dbcad360a1ad2a8f9403ae344d638">endIndexSection</a>.</p>

</div>
</div>

### writePageOutline() {#aebdedaea9ee0b74162e2f30b5b9d8650}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writePageOutline ()</td>
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



<p>Definition at line 269 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebdedaea9ee0b74162e2f30b5b9d8650">269</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aebdedaea9ee0b74162e2f30b5b9d8650">writePageOutline</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### writeQuickLinks() {#a17247283fb1821451810341e9d0cc3d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeQuickLinks (<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09">HighlightedItem</a>, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, bool)</td>
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



<p>Definition at line 267 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a17247283fb1821451810341e9d0cc3d5">267</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a17247283fb1821451810341e9d0cc3d5">writeQuickLinks</a>(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09">HighlightedItem</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### writeRuler() {#a0332a478a833682cf5d2c547a8397973}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeRuler ()</td>
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



<p>Declaration at line 165 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 846 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0332a478a833682cf5d2c547a8397973">846</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0332a478a833682cf5d2c547a8397973">DocbookGenerator::writeRuler</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>(</span><span class="doxyHighlightStringLiteral">"m_inLevel "</span><span class="doxyHighlight"> &lt;&lt; <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>(</span><span class="doxyHighlightStringLiteral">"m_inGroup "</span><span class="doxyHighlight"> &lt;&lt; <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a>) <a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a> and <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a>.</p>

</div>
</div>

### writeSearchInfo() {#aaf1cd7095f2e35a8a08a35b5708d0290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeSearchInfo ()</td>
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



<p>Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaf1cd7095f2e35a8a08a35b5708d0290">128</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaf1cd7095f2e35a8a08a35b5708d0290">writeSearchInfo</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### writeSplitBar() {#a1d027d0e3f93bdc7fb18e0744dddc54c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeSplitBar (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 264 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d027d0e3f93bdc7fb18e0744dddc54c">264</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1d027d0e3f93bdc7fb18e0744dddc54c">writeSplitBar</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### writeStartAnnoItem() {#a4cf676ad6c4def51f89550c68fe4a064}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeStartAnnoItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 237 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4cf676ad6c4def51f89550c68fe4a064">237</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4cf676ad6c4def51f89550c68fe4a064">writeStartAnnoItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a>.</p>

</div>
</div>

### writeString() {#aac462a27783fedbf5241e95db0a5c66a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Declaration at line 155 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 748 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac462a27783fedbf5241e95db0a5c66a">748</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aac462a27783fedbf5241e95db0a5c66a">DocbookGenerator::writeString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; text;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>

</div>
</div>

### writeStyleInfo() {#a684db300b5edf11b5bfa42ba0dac2da0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeStyleInfo (int)</td>
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



<p>Definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a684db300b5edf11b5bfa42ba0dac2da0">135</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a684db300b5edf11b5bfa42ba0dac2da0">writeStyleInfo</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### writeSummaryLink() {#a3656cbeda9530a97ef7aca5a93e476dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeSummaryLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, bool)</td>
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



<p>Definition at line 268 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3656cbeda9530a97ef7aca5a93e476dd">268</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3656cbeda9530a97ef7aca5a93e476dd">writeSummaryLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

### writeSynopsis() {#abbc5974b7b5e7711e3319c50f23b32c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::writeSynopsis ()</td>
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



<p>Definition at line 248 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abbc5974b7b5e7711e3319c50f23b32c5">248</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abbc5974b7b5e7711e3319c50f23b32c5">writeSynopsis</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{<a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/docbookgen-h/#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### closeAllSections() {#a9c26ae654351124ba44d61d231fd6836}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::closeAllSections ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 326 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1398 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c26ae654351124ba44d61d231fd6836">1398</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9c26ae654351124ba44d61d231fd6836">DocbookGenerator::closeAllSections</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1400</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (<a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a>&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1401</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a> and <a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a>.</p>


<p>Referenced by <a href="#aefb08482f742251ae543aeb57983b335">endFile</a>.</p>

</div>
</div>

### closeSection() {#afae8cb3fd84db1e998a4f03433c1493b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::closeSection ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 325 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1392 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afae8cb3fd84db1e998a4f03433c1493b">1392</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afae8cb3fd84db1e998a4f03433c1493b">DocbookGenerator::closeSection</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/section&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>


<p>Referenced by <a href="#a9c26ae654351124ba44d61d231fd6836">closeAllSections</a>, <a href="#ac3c2a2d5f7ee268ca127a30fcaa78fe0">endSection</a>, <a href="#ab575d0e0e347d711d242bdc7fd8c7648">startDoxyAnchor</a>, <a href="#ac651122c0ac17ea4be13f8a4d71c3efa">startGroupHeader</a> and <a href="#a0332a478a833682cf5d2c547a8397973">writeRuler</a>.</p>

</div>
</div>

### openSection() {#a9872f2ebb33a85b7fff7268fee91a977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::openSection (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; attr=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 324 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1384 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9872f2ebb33a85b7fff7268fee91a977">1384</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9872f2ebb33a85b7fff7268fee91a977">DocbookGenerator::openSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;attr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;section"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!attr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; attr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">m_t</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#aceba8f7a334d2e60297dcc727959796c">OutputGenerator::m_t</a>.</p>


<p>Referenced by <a href="#ac651122c0ac17ea4be13f8a4d71c3efa">startGroupHeader</a>, <a href="#a8ae15cadac821acb3d6ecfb6c541d6b9">startMemberDoc</a> and <a href="#aa0fe01b830ddb0d899e151aa389087c8">startSection</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_codeGen {#a3ab50737477df1d37de25615f4bb4f6a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocbookCodeGenerator* DocbookGenerator::m_codeGen = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 330 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3ab50737477df1d37de25615f4bb4f6a">330</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/docbookcodegenerator">DocbookCodeGenerator</a> *<a href="#a3ab50737477df1d37de25615f4bb4f6a">m_codeGen</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a45427ad8a509ed14c5f6c1ef1a64e5d7">addCodeGen</a>, <a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator</a>, <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#aefb08482f742251ae543aeb57983b335">endFile</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a> and <a href="#a7a82873f4a7eeacb88ef535768b311f4">startFile</a>.</p>

</div>
</div>

### m\_codeList {#a1b13cd581e6888ae2e3819f72902d895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;OutputCodeList&gt; DocbookGenerator::m_codeList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 329 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b13cd581e6888ae2e3819f72902d895">329</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;OutputCodeList&gt;  <a href="#a1b13cd581e6888ae2e3819f72902d895">m_codeList</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a59655593be449f9e01ce953a72233de0">DocbookGenerator</a>, <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a> and <a href="#a2f2d4d689d7e1c05bd243f0b23242064">writeDoc</a>.</p>

</div>
</div>

### m\_denseText {#a25d65c357f9a9cc5cf12912c2c3c301c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocbookGenerator::m_denseText = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 331 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a25d65c357f9a9cc5cf12912c2c3c301c">331</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a25d65c357f9a9cc5cf12912c2c3c301c">m_denseText</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#a852205da1a99f864d0a1c96143c3b671">endParameterDefVal</a>, <a href="#a6684626f228c4b3386f33b9d0e1cb000">endTextBlock</a>, <a href="#a2f14bcd9d6629e6ec18be7c82343d852">endTypewriter</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a>, <a href="#aedc98fb288995aea0c0b83fc4eca50a2">startParameterDefVal</a>, <a href="#aeca4bf8edce633fa3faa7c1e38882363">startTextBlock</a> and <a href="#a5e66bd3d7d003c6a3205b1febaa19958">startTypewriter</a>.</p>

</div>
</div>

### m\_descTable {#a207ad156ddb389309522fc4c6998bc3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocbookGenerator::m_descTable = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 336 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a207ad156ddb389309522fc4c6998bc3f">336</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a207ad156ddb389309522fc4c6998bc3f">m_descTable</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#aef5e37d1d6cda8c759cebcd418d91c5d">endDescTable</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a>, <a href="#afb8929ed5f608c71ef0d67c9bd2713a8">startDescTable</a> and <a href="#ab575d0e0e347d711d242bdc7fd8c7648">startDoxyAnchor</a>.</p>

</div>
</div>

### m\_firstMember {#a81a6b8b5249d6aa1144eb15cd75ea019}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocbookGenerator::m_firstMember = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 339 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81a6b8b5249d6aa1144eb15cd75ea019">339</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a81a6b8b5249d6aa1144eb15cd75ea019">m_firstMember</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a>, <a href="#ab575d0e0e347d711d242bdc7fd8c7648">startDoxyAnchor</a> and <a href="#ac651122c0ac17ea4be13f8a4d71c3efa">startGroupHeader</a>.</p>

</div>
</div>

### m\_inGroup {#adeba147b33df197d9e0f917d7cd6580e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocbookGenerator::m_inGroup = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 332 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adeba147b33df197d9e0f917d7cd6580e">332</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#adeba147b33df197d9e0f917d7cd6580e">m_inGroup</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#aefb08482f742251ae543aeb57983b335">endFile</a>, <a href="#accf1f2e363b93a552fb4d3aeb09e6ff2">endMemberDocList</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a>, <a href="#ac651122c0ac17ea4be13f8a4d71c3efa">startGroupHeader</a> and <a href="#a0332a478a833682cf5d2c547a8397973">writeRuler</a>.</p>

</div>
</div>

### m\_inLevel {#a90162d4829b02efea15aea7aa9d89d91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocbookGenerator::m_inLevel = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 338 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a90162d4829b02efea15aea7aa9d89d91">338</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a90162d4829b02efea15aea7aa9d89d91">m_inLevel</a> = -1;</span></span></div>

</div>


<p>Referenced by <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#aefb08482f742251ae543aeb57983b335">endFile</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a>, <a href="#ac651122c0ac17ea4be13f8a4d71c3efa">startGroupHeader</a>, <a href="#a8ae15cadac821acb3d6ecfb6c541d6b9">startMemberDoc</a> and <a href="#a0332a478a833682cf5d2c547a8397973">writeRuler</a>.</p>

</div>
</div>

### m\_inListItem {#adfc62c799e4573efca9deea8a7b96c31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;bool,20&gt; DocbookGenerator::m_inListItem = { false, }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 334 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adfc62c799e4573efca9deea8a7b96c31">334</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::array&lt;bool,20&gt; <a href="#adfc62c799e4573efca9deea8a7b96c31">m_inListItem</a> = { </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">, };</span></span></div>

</div>


<p>Referenced by <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#ae3b1fb5838ed0231423eb95a41173078">endMemberList</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a>, <a href="#ab575d0e0e347d711d242bdc7fd8c7648">startDoxyAnchor</a> and <a href="#a82557dc83927e00f34efb901409e04d4">startMemberItem</a>.</p>

</div>
</div>

### m\_inSimpleSect {#a854b705e94b366fb3ccf08317bd34b95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::array&lt;bool,20&gt; DocbookGenerator::m_inSimpleSect = { false, }</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 335 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a854b705e94b366fb3ccf08317bd34b95">335</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::array&lt;bool,20&gt; <a href="#a854b705e94b366fb3ccf08317bd34b95">m_inSimpleSect</a> = { </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">, };</span></span></div>

</div>


<p>Referenced by <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#ae3b1fb5838ed0231423eb95a41173078">endMemberList</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a>, <a href="#ac651122c0ac17ea4be13f8a4d71c3efa">startGroupHeader</a> and <a href="#a10f198594f85e92a681337af184d913d">startMemberHeader</a>.</p>

</div>
</div>

### m\_levelListItem {#a100d37eb3a12a19bf9be985657fa5fde}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocbookGenerator::m_levelListItem = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 333 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a100d37eb3a12a19bf9be985657fa5fde">333</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">  <a href="#a100d37eb3a12a19bf9be985657fa5fde">m_levelListItem</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#ae3b1fb5838ed0231423eb95a41173078">endMemberList</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a>, <a href="#ab575d0e0e347d711d242bdc7fd8c7648">startDoxyAnchor</a>, <a href="#ac651122c0ac17ea4be13f8a4d71c3efa">startGroupHeader</a>, <a href="#a10f198594f85e92a681337af184d913d">startMemberHeader</a>, <a href="#a82557dc83927e00f34efb901409e04d4">startMemberItem</a> and <a href="#aa7454a8fe2d2ceafbc630ea57ce68d0b">startMemberList</a>.</p>

</div>
</div>

### m\_openSectionCount {#aee5e536b056fc4c7a6cce79f9175538d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocbookGenerator::m_openSectionCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 340 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aee5e536b056fc4c7a6cce79f9175538d">340</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aee5e536b056fc4c7a6cce79f9175538d">m_openSectionCount</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a9c26ae654351124ba44d61d231fd6836">closeAllSections</a>, <a href="#afae8cb3fd84db1e998a4f03433c1493b">closeSection</a>, <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#a9872f2ebb33a85b7fff7268fee91a977">openSection</a> and <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a>.</p>

</div>
</div>

### m\_pageLinks {#aff246cfd65c7cf0982c9b6b39155fc9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocbookGenerator::m_pageLinks</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 341 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff246cfd65c7cf0982c9b6b39155fc9e">341</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aff246cfd65c7cf0982c9b6b39155fc9e">m_pageLinks</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aefb08482f742251ae543aeb57983b335">endFile</a>, <a href="#a7a82873f4a7eeacb88ef535768b311f4">startFile</a> and <a href="#a53279dc86a635990c995e61bc3b7104c">writePageLink</a>.</p>

</div>
</div>

### m\_simpleTable {#ad884acf9c276fdecf1912bbc594e9fc6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocbookGenerator::m_simpleTable = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 337 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad884acf9c276fdecf1912bbc594e9fc6">337</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad884acf9c276fdecf1912bbc594e9fc6">m_simpleTable</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a73bc1589590acfa468910e82d66d0a91">DocbookGenerator</a>, <a href="#a45cd1dbe07a7c47ec3209b9fe1b92c0d">endMemberDocSimple</a>, <a href="#abfda55e880b3527d256491a2f8e908e1">operator=</a>, <a href="#ab575d0e0e347d711d242bdc7fd8c7648">startDoxyAnchor</a> and <a href="#a49908c3a630786d98fb499887b18d8f3">startMemberDocSimple</a>.</p>

</div>
</div>

### m\_tocState {#a635b3b16aee9c0fda65d5b21a8ed262f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TocState DocbookGenerator::m_tocState</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 349 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a635b3b16aee9c0fda65d5b21a8ed262f">349</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/docbookgenerator/tocstate">TocState</a> <a href="#a635b3b16aee9c0fda65d5b21a8ed262f">m_tocState</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a74c7072c37b0f6ca58f077b0cdd0242e">endLocalToc</a>, <a href="#a42a2541faf3a23582c34b87fd29d4f57">endTocEntry</a>, <a href="#a07b3b950a4edb2d5d1d57125babf3e57">startLocalToc</a> and <a href="#a0afd80ec501374a1cdbdf674ec967b79">startTocEntry</a>.</p>

</div>
</div>

### relPath {#acc4b3e766937d32df7466312a4e6db40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocbookGenerator::relPath</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 328 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc4b3e766937d32df7466312a4e6db40">328</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#acc4b3e766937d32df7466312a4e6db40">relPath</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aab1ce69f9718b3c1e05f6c1b697664e4">endCallGraph</a>, <a href="#a2906dcb02cfd455c0d910c9f9501bfbe">endClassDiagram</a>, <a href="#aa80d2614901e7d7624514fa077cee77c">endDirDepGraph</a>, <a href="#a4b2e6be7cbbe074a8d2be270a537c454">endDotGraph</a>, <a href="#a640f85f2e2b3f829d6561aaed542d20b">endGroupCollaboration</a>, <a href="#afa0db463a17513f4e3ae08e03d6e2615">endInclDepGraph</a> and <a href="#a7a82873f4a7eeacb88ef535768b311f4">startFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### init() {#af4363bcfe3875a66c7f2512feb6be13e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocbookGenerator::init ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 113 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 373 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af4363bcfe3875a66c7f2512feb6be13e">373</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af4363bcfe3875a66c7f2512feb6be13e">DocbookGenerator::init</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>=<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DOCBOOK_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> d(<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!d.<a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">exists</a>() &amp;&amp; !d.<a href="/web-doxygen/docs/api/classes/dir/#a286f4b1852b489ffcc8b6837c7e6bd8e">mkdir</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>.str()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Could not create output directory {}\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">dir</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a77685956f8517f3a6e062e66925fc93c">createSubDirs</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a77685956f8517f3a6e062e66925fc93c">createSubDirs</a>, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a595e39d22e92ac09d24706829b532b00">OutputGenerator::dir</a>, <a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">Dir::exists</a>, <a href="/web-doxygen/docs/api/classes/dir/#a286f4b1852b489ffcc8b6837c7e6bd8e">Dir::mkdir</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
