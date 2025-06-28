---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/htmlhelp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `HtmlHelp` Class Reference

<p>A class that generated the HTML Help specific files. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class HtmlHelp { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/htmlhelp-h">src/htmlhelp.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/indexintf">IndexIntf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for index generators. <a href="/web-doxygen/docs/api/classes/indexintf/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top">ImageNumber { <a href="#a7fa2b031d786cb7a678e88809c2566ca">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d86f84971a446fc8c61c1a64f8eaaf8">HtmlHelp</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53ff23898ba7e49de5ce6dba03675f82">~HtmlHelp</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf6cb7c477c71f2031b5831f979991d5">initialize</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66375adceef242d73c6554bd7fba6cf7">finalize</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca0008f8813f28f23ca5bcaea25a7bec">incContentsDepth</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad76b300748e818d96676f0743738090d">decContentsDepth</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1503b3b4d76049d44a45452d44722d86">addContentsItem</a> (bool isDir, const QCString &amp;name, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, bool separateIndex, bool addToNavIndex, const Definition *def, const QCString &amp;nameAsHtml)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a247f8e8a9f527f64cbd47875876ee62b">addIndexItem</a> (const Definition *context, const MemberDef *md, const QCString &amp;sectionAnchor, const QCString &amp;title)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06d4ceaf4d108051a76d49986f56b8a0">addIndexFile</a> (const QCString &amp;name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a01a6226c4a4e8c587a78af168e5e3938">addImageFile</a> (const QCString &amp;)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6c55156ed17cff5a6cb350df9182d06">addStyleSheetFile</a> (const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d46269e4ff27f042eadf20fa02a776e">recode</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/htmlhelp/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a></td>
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

## Public Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af2b3923cd07004204fb0c542100b28e8">hhcFileName</a> = "index.hhc"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a110521fd634c3c63e47cfe47e210a848">hhkFileName</a> = "index.hhk"</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a314fc3c639cdd9af2fa9969db847a176">hhpFileName</a> = "index.hhp"</td>
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

<p>A class that generated the HTML Help specific files.</p>


<p>These files can be used with the Microsoft HTML Help workshop to generate compressed HTML files (.chm).</p>

<p>Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### ImageNumber {#a7fa2b031d786cb7a678e88809c2566ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum HtmlHelp::ImageNumber </td>
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
<td class="doxyEnumItemName">BOOK_CLOSED<a id="a7fa2b031d786cb7a678e88809c2566caaec1852e9e27b296742d6c36b9c416920"></a></td>
<td class="doxyEnumItemDescription"><p> (=1)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BOOK_OPEN<a id="a7fa2b031d786cb7a678e88809c2566caa7e86e3494127343bd99ad946cfa13d21"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BOOK_CLOSED_NEW<a id="a7fa2b031d786cb7a678e88809c2566caacd0e3ae0fbebc09bd3bbebbd4815472a"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BOOK_OPEN_NEW<a id="a7fa2b031d786cb7a678e88809c2566caac6c5ce4a499ef91164b43958c919123f"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FOLDER_CLOSED<a id="a7fa2b031d786cb7a678e88809c2566caa08208a8aca7a51f8f5b9dc1b695619c1"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FOLDER_OPEN<a id="a7fa2b031d786cb7a678e88809c2566caa3aea4a6d39d36dd2447e2da611623730"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FOLDER_CLOSED_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa6a05e4f90f1ce01c7f60264faab7796f"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FOLDER_OPEN_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa613f98c3ad2d1f8af8acd1fd544102b4"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QUERY<a id="a7fa2b031d786cb7a678e88809c2566caa825238cc73c9011836072b7159cd063c"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">QUERY_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa576707aa2b0d1f23020bf3556240b5ae"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TEXT<a id="a7fa2b031d786cb7a678e88809c2566caa3e9b105181d342b365fe4bdee8acf84b"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TEXT_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa5bd4c350ef03738d931784b2e06f7747"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WEB_DOC<a id="a7fa2b031d786cb7a678e88809c2566caaf3542090c73d8ec35a6ac8331fa77e01"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WEB_DOC_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa01dc344f0d03316ac6123da212b00acd"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WEB_LINK<a id="a7fa2b031d786cb7a678e88809c2566caa5013131ed24fc1a223d1721782c9ef65"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">WEB_LINK_NEW<a id="a7fa2b031d786cb7a678e88809c2566caacbd5cd83209e54f39785b855faad6c6b"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INFO<a id="a7fa2b031d786cb7a678e88809c2566caae6f2e13e6d941648dcb8fa0b33de494b"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INFO_NEW<a id="a7fa2b031d786cb7a678e88809c2566caafecd3e50bd62c15ab1d4d048b5e280c9"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LINK<a id="a7fa2b031d786cb7a678e88809c2566caa81f15f9b760ab6bb2a67c759a072be14"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">LINK_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa5b3c47ac921af0a746c3f24b04956abf"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BOOKLET<a id="a7fa2b031d786cb7a678e88809c2566caac317b4d5947561ac628f05ae7cbf692c"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">BOOKLET_NEW<a id="a7fa2b031d786cb7a678e88809c2566caab73467539bbfd3401ac0f0a4cc852972"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EMAIL<a id="a7fa2b031d786cb7a678e88809c2566caa62ff82964869830f742e4d55dcc5874d"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EMAIL_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa0c5093469414d14509f38856230a6dfa"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EMAIL2<a id="a7fa2b031d786cb7a678e88809c2566caaf1c0f7d8a8932af2157386c8de57f1c6"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EMAIL2_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa9a29099af4c48e62e289c348e2344483"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IMAGE<a id="a7fa2b031d786cb7a678e88809c2566caa650460790b63d21545a3a650e198127d"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IMAGE_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa3b39f2db693a2ea1bead2fd1db0876d8"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUDIO<a id="a7fa2b031d786cb7a678e88809c2566caa45377d49ec2e3fba7e6f51077620d737"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">AUDIO_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa4bf7a99aee350a08999b1ff157e4cc38"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MUSIC<a id="a7fa2b031d786cb7a678e88809c2566caa761720c8f58915a5614f8ee8e87fd73b"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">MUSIC_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa33344e49811ddf6461d0d002de73d1fe"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VIDEO<a id="a7fa2b031d786cb7a678e88809c2566caa19ce2f379767fa5636d99b1624424e27"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">VIDEO_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa6ae16142e9a1bbfb6cf4e0057f88cb84"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INDEX<a id="a7fa2b031d786cb7a678e88809c2566caa7c362e1795a9644efa179ceab270fe61"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">INDEX_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa5ba12150f715f11b11ba5c0c01afc292"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IDEA<a id="a7fa2b031d786cb7a678e88809c2566caacd187fb03abe97b1f1c79c32cfbb9db6"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">IDEA_NEW<a id="a7fa2b031d786cb7a678e88809c2566caadc361e2afcf234f19692cdd976b35614"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NOTE<a id="a7fa2b031d786cb7a678e88809c2566caa8b971585ba93d8009a46a7e0303fefab"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">NOTE_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa36c71b6fceea68ae4d0508af9c5b8fa9"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOOL<a id="a7fa2b031d786cb7a678e88809c2566caaa549ff1567ca21b11ff5a098b4c2aecc"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">TOOL_NEW<a id="a7fa2b031d786cb7a678e88809c2566caa2a48c9704da887c47191bd7ea2d195b4"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>


<p>used in imageNumber param of HTMLHelp::addContentsItem() function to specify document icon in tree view. Writes &lt;param name="ImageNumber" value="xx"&gt; in .HHC file.</p>

<p>Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566ca">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#a7fa2b031d786cb7a678e88809c2566ca">ImageNumber</a> {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caaec1852e9e27b296742d6c36b9c416920">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caaec1852e9e27b296742d6c36b9c416920">BOOK_CLOSED</a>=1,    <a href="#a7fa2b031d786cb7a678e88809c2566caa7e86e3494127343bd99ad946cfa13d21">BOOK_OPEN</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caacd0e3ae0fbebc09bd3bbebbd4815472a">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caacd0e3ae0fbebc09bd3bbebbd4815472a">BOOK_CLOSED_NEW</a>,  <a href="#a7fa2b031d786cb7a678e88809c2566caac6c5ce4a499ef91164b43958c919123f">BOOK_OPEN_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa08208a8aca7a51f8f5b9dc1b695619c1">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa08208a8aca7a51f8f5b9dc1b695619c1">FOLDER_CLOSED</a>,    <a href="#a7fa2b031d786cb7a678e88809c2566caa3aea4a6d39d36dd2447e2da611623730">FOLDER_OPEN</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa6a05e4f90f1ce01c7f60264faab7796f">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa6a05e4f90f1ce01c7f60264faab7796f">FOLDER_CLOSED_NEW</a>,<a href="#a7fa2b031d786cb7a678e88809c2566caa613f98c3ad2d1f8af8acd1fd544102b4">FOLDER_OPEN_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa825238cc73c9011836072b7159cd063c">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa825238cc73c9011836072b7159cd063c">QUERY</a>,            <a href="#a7fa2b031d786cb7a678e88809c2566caa576707aa2b0d1f23020bf3556240b5ae">QUERY_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa3e9b105181d342b365fe4bdee8acf84b">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa3e9b105181d342b365fe4bdee8acf84b">TEXT</a>,             <a href="#a7fa2b031d786cb7a678e88809c2566caa5bd4c350ef03738d931784b2e06f7747">TEXT_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caaf3542090c73d8ec35a6ac8331fa77e01">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caaf3542090c73d8ec35a6ac8331fa77e01">WEB_DOC</a>,          <a href="#a7fa2b031d786cb7a678e88809c2566caa01dc344f0d03316ac6123da212b00acd">WEB_DOC_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa5013131ed24fc1a223d1721782c9ef65">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa5013131ed24fc1a223d1721782c9ef65">WEB_LINK</a>,         <a href="#a7fa2b031d786cb7a678e88809c2566caacbd5cd83209e54f39785b855faad6c6b">WEB_LINK_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caae6f2e13e6d941648dcb8fa0b33de494b">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caae6f2e13e6d941648dcb8fa0b33de494b">INFO</a>,             <a href="#a7fa2b031d786cb7a678e88809c2566caafecd3e50bd62c15ab1d4d048b5e280c9">INFO_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa81f15f9b760ab6bb2a67c759a072be14">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa81f15f9b760ab6bb2a67c759a072be14">LINK</a>,             <a href="#a7fa2b031d786cb7a678e88809c2566caa5b3c47ac921af0a746c3f24b04956abf">LINK_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caac317b4d5947561ac628f05ae7cbf692c">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caac317b4d5947561ac628f05ae7cbf692c">BOOKLET</a>,          <a href="#a7fa2b031d786cb7a678e88809c2566caab73467539bbfd3401ac0f0a4cc852972">BOOKLET_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa62ff82964869830f742e4d55dcc5874d">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa62ff82964869830f742e4d55dcc5874d">EMAIL</a>,            <a href="#a7fa2b031d786cb7a678e88809c2566caa0c5093469414d14509f38856230a6dfa">EMAIL_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caaf1c0f7d8a8932af2157386c8de57f1c6">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caaf1c0f7d8a8932af2157386c8de57f1c6">EMAIL2</a>,           <a href="#a7fa2b031d786cb7a678e88809c2566caa9a29099af4c48e62e289c348e2344483">EMAIL2_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa650460790b63d21545a3a650e198127d">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa650460790b63d21545a3a650e198127d">IMAGE</a>,            <a href="#a7fa2b031d786cb7a678e88809c2566caa3b39f2db693a2ea1bead2fd1db0876d8">IMAGE_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa45377d49ec2e3fba7e6f51077620d737">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa45377d49ec2e3fba7e6f51077620d737">AUDIO</a>,            <a href="#a7fa2b031d786cb7a678e88809c2566caa4bf7a99aee350a08999b1ff157e4cc38">AUDIO_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa761720c8f58915a5614f8ee8e87fd73b">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa761720c8f58915a5614f8ee8e87fd73b">MUSIC</a>,            <a href="#a7fa2b031d786cb7a678e88809c2566caa33344e49811ddf6461d0d002de73d1fe">MUSIC_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa19ce2f379767fa5636d99b1624424e27">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa19ce2f379767fa5636d99b1624424e27">VIDEO</a>,            <a href="#a7fa2b031d786cb7a678e88809c2566caa6ae16142e9a1bbfb6cf4e0057f88cb84">VIDEO_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa7c362e1795a9644efa179ceab270fe61">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa7c362e1795a9644efa179ceab270fe61">INDEX</a>,            <a href="#a7fa2b031d786cb7a678e88809c2566caa5ba12150f715f11b11ba5c0c01afc292">INDEX_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caacd187fb03abe97b1f1c79c32cfbb9db6">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caacd187fb03abe97b1f1c79c32cfbb9db6">IDEA</a>,             <a href="#a7fa2b031d786cb7a678e88809c2566caadc361e2afcf234f19692cdd976b35614">IDEA_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caa8b971585ba93d8009a46a7e0303fefab">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caa8b971585ba93d8009a46a7e0303fefab">NOTE</a>,             <a href="#a7fa2b031d786cb7a678e88809c2566caa36c71b6fceea68ae4d0508af9c5b8fa9">NOTE_NEW</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fa2b031d786cb7a678e88809c2566caaa549ff1567ca21b11ff5a098b4c2aecc">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7fa2b031d786cb7a678e88809c2566caaa549ff1567ca21b11ff5a098b4c2aecc">TOOL</a>,             <a href="#a7fa2b031d786cb7a678e88809c2566caa2a48c9704da887c47191bd7ea2d195b4">TOOL_NEW</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### HtmlHelp() {#a0d86f84971a446fc8c61c1a64f8eaaf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlHelp::HtmlHelp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Constructs an html object. The object has to be <a href="#acf6cb7c477c71f2031b5831f979991d5">initialized</a> before it can be used.</p>

<p>Declaration at line 64 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>, definition at line 361 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0d86f84971a446fc8c61c1a64f8eaaf8">361</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a0d86f84971a446fc8c61c1a64f8eaaf8">HtmlHelp::HtmlHelp</a>() : <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/classes/htmlhelp/private">Private</a>&gt;()) {}</span></span></div>

</div>


Reference <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>.

Referenced by <a href="#a53ff23898ba7e49de5ce6dba03675f82">~HtmlHelp</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### ~HtmlHelp() {#a53ff23898ba7e49de5ce6dba03675f82}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">HtmlHelp::~HtmlHelp ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>.</p>

Reference <a href="#a0d86f84971a446fc8c61c1a64f8eaaf8">HtmlHelp</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addContentsItem() {#a1503b3b4d76049d44a45452d44722d86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelp::addContentsItem (bool isDir, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, bool separateIndex, bool addToNavIndex, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * def, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; nameAsHtml)</td>
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



<p>Add an list item to the contents file.</p>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">isDir</td>
<td class="doxyParamItemDescription"><p>boolean indicating if this is a dir or file entry</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">name</td>
<td class="doxyParamItemDescription"><p>the name of the item.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ref</td>
<td class="doxyParamItemDescription"><p>the URL of to the item.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">file</td>
<td class="doxyParamItemDescription"><p>the file in which the item is defined.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">anchor</td>
<td class="doxyParamItemDescription"><p>the anchor of the item.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">separateIndex</td>
<td class="doxyParamItemDescription"><p>not used.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">addToNavIndex</td>
<td class="doxyParamItemDescription"><p>not used.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">def</td>
<td class="doxyParamItemDescription"><p>not used.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">nameAsHtml</td>
<td class="doxyParamItemDescription"><p>name parameter in HTML format</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 72 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>, definition at line 548 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1503b3b4d76049d44a45452d44722d86">548</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1503b3b4d76049d44a45452d44722d86">HtmlHelp::addContentsItem</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isDir,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* separateIndex */</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">/* addToNavIndex */</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * </span><span class="doxyHighlightComment">/* def */</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; </span><span class="doxyHighlightComment">/* nameAsHtml */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;ctsItemPresent = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0; i&lt;<a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;dc; i++) <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;LI&gt;&lt;OBJECT type=\"text/sitemap\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"Name\" value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(<a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;recoder.recode(name),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())      </span><span class="doxyHighlightComment">// made file optional param - KPW</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (file[0]==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight"> || file[0]==</span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// special markers for user defined URLs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (file[0]==</span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">) <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"URL"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"Local"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" value=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; &amp;file[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> currFile = file;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(currFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> currAnc = anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"Local\" value=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,ref,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; currFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;prevFile == currFile &amp;&amp; <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;prevAnc.isEmpty() &amp;&amp; currAnc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">        currAnc = </span><span class="doxyHighlightStringLiteral">"top"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!currAnc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight"> &lt;&lt; currAnc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;prevFile = currFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;prevAnc = currAnc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"ImageNumber\" value=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isDir)  </span><span class="doxyHighlightComment">// added - KPW</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a7fa2b031d786cb7a678e88809c2566caaec1852e9e27b296742d6c36b9c416920">BOOK_CLOSED</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a7fa2b031d786cb7a678e88809c2566caa3e9b105181d342b365fe4bdee8acf84b">TEXT</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/OBJECT&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="#a7fa2b031d786cb7a678e88809c2566caaec1852e9e27b296742d6c36b9c416920">BOOK&#95;CLOSED</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>, <a href="#a7fa2b031d786cb7a678e88809c2566caa3e9b105181d342b365fe4bdee8acf84b">TEXT</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### addImageFile() {#a01a6226c4a4e8c587a78af168e5e3938}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelp::addImageFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
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


<p>Declaration at line 84 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>, definition at line 629 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a01a6226c4a4e8c587a78af168e5e3938">629</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a01a6226c4a4e8c587a78af168e5e3938">HtmlHelp::addImageFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;imageFiles.insert(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### addIndexFile() {#a06d4ceaf4d108051a76d49986f56b8a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelp::addIndexFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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


<p>Declaration at line 83 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>, definition at line 485 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a06d4ceaf4d108051a76d49986f56b8a0">485</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a06d4ceaf4d108051a76d49986f56b8a0">HtmlHelp::addIndexFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;indexFiles.insert(s.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### addIndexItem() {#a247f8e8a9f527f64cbd47875876ee62b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelp::addIndexItem (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * context, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; sectionAnchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title)</td>
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


<p>Declaration at line 81 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>, definition at line 604 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a247f8e8a9f527f64cbd47875876ee62b">604</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a247f8e8a9f527f64cbd47875876ee62b">HtmlHelp::addIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *context,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;sectionAnchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;word)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (context &amp;&amp; md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> cfname  = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> argStr  = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">argsString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> level1  = context-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> level2  = md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>() + argStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anchor  = !sectionAnchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? sectionAnchor : md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;index.addItem(level1,level2,cfname,anchor,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;index.addItem(level2,level1,cfname,anchor,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (context)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> level1  = !word.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? word : context-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;index.addItem(level1,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),context-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>(),sectionAnchor,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#adfae3b8f49644ba27669daa9412e14a3">MemberDef::argsString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### addStyleSheetFile() {#ac6c55156ed17cff5a6cb350df9182d06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelp::addStyleSheetFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
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


<p>Declaration at line 85 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>, definition at line 624 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac6c55156ed17cff5a6cb350df9182d06">624</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac6c55156ed17cff5a6cb350df9182d06">HtmlHelp::addStyleSheetFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;styleFiles.insert(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### decContentsDepth() {#ad76b300748e818d96676f0743738090d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelp::decContentsDepth ()</td>
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



<p>Decrease the level of the contents hierarchy. This will end the unnumber HTML list.</p>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
<p><a href="#aca0008f8813f28f23ca5bcaea25a7bec">incContentsDepth()</a></p>
</dd>
</dl>


<p>Declaration at line 71 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>, definition at line 530 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad76b300748e818d96676f0743738090d">530</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad76b300748e818d96676f0743738090d">HtmlHelp::decContentsDepth</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0; i&lt;<a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;dc; i++) <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/UL&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">  --<a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;dc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>.
</div>
</div>

### finalize() {#a66375adceef242d73c6554bd7fba6cf7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelp::finalize ()</td>
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



<p>Finalizes the HTML help. This will finish and close the htmlhelp contents file and the htmlhelp index file.</p>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
<p><a href="#acf6cb7c477c71f2031b5831f979991d5">initialize()</a></p>
</dd>
</dl>


<p>Declaration at line 69 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>, definition at line 494 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a66375adceef242d73c6554bd7fba6cf7">494</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a66375adceef242d73c6554bd7fba6cf7">HtmlHelp::finalize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// end the contents file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/UL&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/BODY&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/HTML&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;index.writeFields(<a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;kts);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// end the index file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;kts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/UL&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;kts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/BODY&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;kts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/HTML&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;kts.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;createProjectFile();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;recoder.finalize();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>.
</div>
</div>

### incContentsDepth() {#aca0008f8813f28f23ca5bcaea25a7bec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelp::incContentsDepth ()</td>
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



<p>Increase the level of the contents hierarchy. This will start a new unnumbered HTML list in contents file.</p>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
<p><a href="#ad76b300748e818d96676f0743738090d">decContentsDepth()</a></p>
</dd>
</dl>


<p>Declaration at line 70 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>, definition at line 519 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca0008f8813f28f23ca5bcaea25a7bec">519</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aca0008f8813f28f23ca5bcaea25a7bec">HtmlHelp::incContentsDepth</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0; i&lt;<a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;dc+1; i++) <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;UL&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">  ++<a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;dc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>.
</div>
</div>

### initialize() {#acf6cb7c477c71f2031b5831f979991d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void HtmlHelp::initialize ()</td>
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



<p>This will create a contents file (index.hhc) and a index file (index.hhk) and write the header of those files. It also creates a project file (index.hhp)</p>

<dl class="doxySectionUser">
<dt>See Also</dt>
<dd>
<p><a href="#a66375adceef242d73c6554bd7fba6cf7">finalize()</a></p>
</dd>
</dl>


<p>Declaration at line 68 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>, definition at line 369 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acf6cb7c477c71f2031b5831f979991d5">369</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acf6cb7c477c71f2031b5831f979991d5">HtmlHelp::initialize</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;recoder.initialize();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* open the contents file */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fName = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT) + </span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight"> + <a href="#af2b3923cd07004204fb0c542100b28e8">hhcFileName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,fName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* Write the header of the contents file */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;cts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!DOCTYPE HTML PUBLIC \"-//IETF//DTD HTML//EN\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;HTML&gt;&lt;HEAD&gt;&lt;/HEAD&gt;&lt;BODY&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;OBJECT type=\"text/site properties\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"FrameName\" value=\"right\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;/OBJECT&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;UL&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* open the index file */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">  fName = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_OUTPUT) + </span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight"> + <a href="#a110521fd634c3c63e47cfe47e210a848">hhkFileName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;kts = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;kts.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Could not open file {} for writing\n"</span><span class="doxyHighlight">,fName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* Write the header of the contents file */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>-&gt;kts &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;!DOCTYPE HTML PUBLIC \"-//IETF//DTD HTML//EN\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;HTML&gt;&lt;HEAD&gt;&lt;/HEAD&gt;&lt;BODY&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;OBJECT type=\"text/site properties\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;param name=\"FrameName\" value=\"right\"&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;/OBJECT&gt;\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"&lt;UL&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="#af2b3923cd07004204fb0c542100b28e8">hhcFileName</a>, <a href="#a110521fd634c3c63e47cfe47e210a848">hhkFileName</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### recode() {#a7d46269e4ff27f042eadf20fa02a776e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString HtmlHelp::recode (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 93 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>.</p>
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a6508afcd62c3c90466a5003a52d1fcaa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; HtmlHelp::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6508afcd62c3c90466a5003a52d1fcaa">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a6508afcd62c3c90466a5003a52d1fcaa">p</a>;</span></span></div>

</div>


Referenced by <a href="#a1503b3b4d76049d44a45452d44722d86">addContentsItem</a>, <a href="#a01a6226c4a4e8c587a78af168e5e3938">addImageFile</a>, <a href="#a06d4ceaf4d108051a76d49986f56b8a0">addIndexFile</a>, <a href="#a247f8e8a9f527f64cbd47875876ee62b">addIndexItem</a>, <a href="#ac6c55156ed17cff5a6cb350df9182d06">addStyleSheetFile</a>, <a href="#ad76b300748e818d96676f0743738090d">decContentsDepth</a>, <a href="#a66375adceef242d73c6554bd7fba6cf7">finalize</a>, <a href="#a0d86f84971a446fc8c61c1a64f8eaaf8">HtmlHelp</a>, <a href="#aca0008f8813f28f23ca5bcaea25a7bec">incContentsDepth</a> and <a href="#acf6cb7c477c71f2031b5831f979991d5">initialize</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Attributes

### hhcFileName {#af2b3923cd07004204fb0c542100b28e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const QCString HtmlHelp::hhcFileName = "index.hhc"</td>
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


<p>Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af2b3923cd07004204fb0c542100b28e8">87</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#af2b3923cd07004204fb0c542100b28e8">hhcFileName</a> = </span><span class="doxyHighlightStringLiteral">"index.hhc"</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlhelp/private/#a38e9087180f5ff4adc6bf59d38fa71a2">HtmlHelp::Private::createProjectFile</a> and <a href="#acf6cb7c477c71f2031b5831f979991d5">initialize</a>.
</div>
</div>

### hhkFileName {#a110521fd634c3c63e47cfe47e210a848}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const QCString HtmlHelp::hhkFileName = "index.hhk"</td>
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


<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a110521fd634c3c63e47cfe47e210a848">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a110521fd634c3c63e47cfe47e210a848">hhkFileName</a> = </span><span class="doxyHighlightStringLiteral">"index.hhk"</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlhelp/private/#a38e9087180f5ff4adc6bf59d38fa71a2">HtmlHelp::Private::createProjectFile</a> and <a href="#acf6cb7c477c71f2031b5831f979991d5">initialize</a>.
</div>
</div>

### hhpFileName {#a314fc3c639cdd9af2fa9969db847a176}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const QCString HtmlHelp::hhpFileName = "index.hhp"</td>
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


<p>Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a314fc3c639cdd9af2fa9969db847a176">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a314fc3c639cdd9af2fa9969db847a176">hhpFileName</a> = </span><span class="doxyHighlightStringLiteral">"index.hhp"</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlhelp/private/#a38e9087180f5ff4adc6bf59d38fa71a2">HtmlHelp::Private::createProjectFile</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91768fc1635556eefd2d96ea1751435d">runHtmlHelpCompiler</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/htmlhelp-cpp">htmlhelp.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/htmlhelp-h">htmlhelp.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
