---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/cmdmapper-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `cmdmapper.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;unordered_map&gt;
#include &lt;string&gt;
#include &lt;memory&gt;
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/namespaces/mappers">Mappers</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Namespace for the doxygen and HTML command mappers. <a href="/web-doxygen/docs/api/namespaces/mappers/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/mapper">Mapper&lt;T&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Class representing a mapping from command names to command IDs. <a href="/web-doxygen/docs/api/classes/mapper/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename T&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a76f30bfa2d9318e64adc918b05039dad">CommandMap</a> = std::unordered_map&lt; std::string, T &gt;</td>
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CommandType { <a href="#a21e038f5b8958e203d28bc4f18472352">...</a> }</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">HtmlTagType { <a href="#a91be16b8342aa3130a4374d78cf42273">...</a> }</td>
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


<div class="doxySectionDef">

## Typedefs

### CommandMap {#a76f30bfa2d9318e64adc918b05039dad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename T&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using CommandMap =  std::unordered_map&lt; std::string, T &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-doxygen/docs/api/files/src/cmdmapper-h">cmdmapper.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a76f30bfa2d9318e64adc918b05039dad">25</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a76f30bfa2d9318e64adc918b05039dad">CommandMap</a> = std::unordered_map&lt; std::string, T &gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Enumerations

### CommandType {#a21e038f5b8958e203d28bc4f18472352}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class CommandType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">SIMPLESECT_BIT<a id="a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNKNOWN<a id="a21e038f5b8958e203d28bc4f18472352a696b031073e74bf2cb98e5ef201d4aa3"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ADDINDEX<a id="a21e038f5b8958e203d28bc4f18472352a6a28a1008ba398c9092acd8943a565c3"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_AMP<a id="a21e038f5b8958e203d28bc4f18472352a6f9f21c0cb1ce6e48a2aac0475e7065d"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ANCHOR<a id="a21e038f5b8958e203d28bc4f18472352aea2d6a1dd2fe7915d34d1932402a5389"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_AT<a id="a21e038f5b8958e203d28bc4f18472352a231334a819076be4d21ffbf9eb3d5fac"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ATTENTION<a id="a21e038f5b8958e203d28bc4f18472352aae34bcb7153edac8378fd4280db2e44c"></a></td>
<td class="doxyEnumItemDescription"> (= 5  | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_AUTHOR<a id="a21e038f5b8958e203d28bc4f18472352af0700e8bd6adf3a36fbd38905bcd399e"></a></td>
<td class="doxyEnumItemDescription"> (= 6  | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_AUTHORS<a id="a21e038f5b8958e203d28bc4f18472352a02da166bedae5175de575f357cac265c"></a></td>
<td class="doxyEnumItemDescription"> (= 7  | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_BOLD<a id="a21e038f5b8958e203d28bc4f18472352aed8e4495d256975e34e0fcaee34ebe3b"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_BSLASH<a id="a21e038f5b8958e203d28bc4f18472352ab41541930cbc3eb72b54d4c6da3c0ae8"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_CODE<a id="a21e038f5b8958e203d28bc4f18472352a8de3af7ff872fa5ad8f22fc5eac6465b"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_COPYDOC<a id="a21e038f5b8958e203d28bc4f18472352ae28a43d56ad7068093118e9e9d80adf5"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_DATE<a id="a21e038f5b8958e203d28bc4f18472352af0443850cff338e6f483e7ed15d12dcf"></a></td>
<td class="doxyEnumItemDescription"> (= 12 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_DOLLAR<a id="a21e038f5b8958e203d28bc4f18472352a036b0b8401bf33b8e70ea757f86bead6"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_DONTINCLUDE<a id="a21e038f5b8958e203d28bc4f18472352a23fe4833e0a54fc766064003db874806"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_DOTFILE<a id="a21e038f5b8958e203d28bc4f18472352a0b1af583174c0fb1932fd4685d80bd0b"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_EMPHASIS<a id="a21e038f5b8958e203d28bc4f18472352a4ea7c7754bb98d8d463a08828e44811e"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDCODE<a id="a21e038f5b8958e203d28bc4f18472352a4ffb780097c3c1177340a16a7a7c1a62"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDHTMLONLY<a id="a21e038f5b8958e203d28bc4f18472352a8c78bc70ef572a2d5767fe08759b866f"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDLATEXONLY<a id="a21e038f5b8958e203d28bc4f18472352a169f22d54d12b12865279ec72666799a"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDLINK<a id="a21e038f5b8958e203d28bc4f18472352a91531d8419b3e6261b793638cd6f8f70"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDSECREFLIST<a id="a21e038f5b8958e203d28bc4f18472352a15578fca2422b89bf32bd85c294b4a26"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDVERBATIM<a id="a21e038f5b8958e203d28bc4f18472352a1d1e116739898a0f2d5c43c0a70f81d7"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDXMLONLY<a id="a21e038f5b8958e203d28bc4f18472352a8639fdd14d2cabd7aef30f1469c7d18c"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_EXCEPTION<a id="a21e038f5b8958e203d28bc4f18472352a996c5bab025550bae11a0748dc9331d7"></a></td>
<td class="doxyEnumItemDescription"> (= 24 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_FORMULA<a id="a21e038f5b8958e203d28bc4f18472352acc81c3d8371cc6a7b01e183a8c9fa04e"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_GREATER<a id="a21e038f5b8958e203d28bc4f18472352a6454f09b46f73d0d141a041314c0b95c"></a></td>
<td class="doxyEnumItemDescription"> (= 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_HASH<a id="a21e038f5b8958e203d28bc4f18472352a602d16174562d50f3cf2f8eda1c6ebb6"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_HTMLINCLUDE<a id="a21e038f5b8958e203d28bc4f18472352ad5344bb3c420c40b5bf1cd46e6d80cc5"></a></td>
<td class="doxyEnumItemDescription"> (= 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_HTMLONLY<a id="a21e038f5b8958e203d28bc4f18472352a02ff5a94f1a879395b00661ec8185dfa"></a></td>
<td class="doxyEnumItemDescription"> (= 29)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_IMAGE<a id="a21e038f5b8958e203d28bc4f18472352a50ef1a2484f87e0e789063b64718f9c6"></a></td>
<td class="doxyEnumItemDescription"> (= 30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_INCLUDE<a id="a21e038f5b8958e203d28bc4f18472352aa477dc9f970da083d8eb3cd9b5f8835c"></a></td>
<td class="doxyEnumItemDescription"> (= 31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_INTERNAL<a id="a21e038f5b8958e203d28bc4f18472352a6de97492df438e4d22002087f483ecf2"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_INTERNALREF<a id="a21e038f5b8958e203d28bc4f18472352a85bc5fc2f86ed5c6b7d7a1b753776372"></a></td>
<td class="doxyEnumItemDescription"> (= 33)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_INVARIANT<a id="a21e038f5b8958e203d28bc4f18472352abadfe37f10dd2a7ef97a95ae0503b0c6"></a></td>
<td class="doxyEnumItemDescription"> (= 34 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_LATEXONLY<a id="a21e038f5b8958e203d28bc4f18472352a873d102356c495a37910b496c4ab1baa"></a></td>
<td class="doxyEnumItemDescription"> (= 35)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_LESS<a id="a21e038f5b8958e203d28bc4f18472352aa76513f8aaef2b7d02c9993b3920fcec"></a></td>
<td class="doxyEnumItemDescription"> (= 36)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_LI<a id="a21e038f5b8958e203d28bc4f18472352ab166f31f6afdd2828434e9681a93390a"></a></td>
<td class="doxyEnumItemDescription"> (= 37)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_LINE<a id="a21e038f5b8958e203d28bc4f18472352a9a639b8b2e64e575a3d063a48b3450a5"></a></td>
<td class="doxyEnumItemDescription"> (= 38)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_LINEBREAK<a id="a21e038f5b8958e203d28bc4f18472352a7a5191a7f81ddc3b67a10a05e467829f"></a></td>
<td class="doxyEnumItemDescription"> (= 39)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_LINK<a id="a21e038f5b8958e203d28bc4f18472352a9308b376abf23762b61f1e71c3dc3201"></a></td>
<td class="doxyEnumItemDescription"> (= 40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_NOTE<a id="a21e038f5b8958e203d28bc4f18472352ae54082d6d8530592497cf241bed3fe59"></a></td>
<td class="doxyEnumItemDescription"> (= 41 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_PAR<a id="a21e038f5b8958e203d28bc4f18472352a1948243b070f58bd97b9877f02d9c29b"></a></td>
<td class="doxyEnumItemDescription"> (= 42 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_PARAM<a id="a21e038f5b8958e203d28bc4f18472352abd01c1081b94961568a7835a6e55818b"></a></td>
<td class="doxyEnumItemDescription"> (= 43 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_PERCENT<a id="a21e038f5b8958e203d28bc4f18472352a71a82fcfdc616129c03fe458496b4906"></a></td>
<td class="doxyEnumItemDescription"> (= 44)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_POST<a id="a21e038f5b8958e203d28bc4f18472352a0341498d2c2a13e06e6498d5d7f0b00e"></a></td>
<td class="doxyEnumItemDescription"> (= 45 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_PRE<a id="a21e038f5b8958e203d28bc4f18472352a33127d73e7d3569f295179dab1d3c868"></a></td>
<td class="doxyEnumItemDescription"> (= 46 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_REF<a id="a21e038f5b8958e203d28bc4f18472352aa9a69c720668a9e5705eef2fdd0938b1"></a></td>
<td class="doxyEnumItemDescription"> (= 47)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SECREFITEM<a id="a21e038f5b8958e203d28bc4f18472352a8fa243222e547a267c94e32c8c8c9c0a"></a></td>
<td class="doxyEnumItemDescription"> (= 48)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_REMARK<a id="a21e038f5b8958e203d28bc4f18472352a86b78f3934f4994a11865685082a4dfc"></a></td>
<td class="doxyEnumItemDescription"> (= 49 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_RETURN<a id="a21e038f5b8958e203d28bc4f18472352a6ba091ac10f7a7cf1ff37262bd57d9d3"></a></td>
<td class="doxyEnumItemDescription"> (= 50 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_RETVAL<a id="a21e038f5b8958e203d28bc4f18472352a6d933a567cc87ce84eb73ca916c75b6e"></a></td>
<td class="doxyEnumItemDescription"> (= 51 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SA<a id="a21e038f5b8958e203d28bc4f18472352ab80aa9991ccbef64c2d3751905610771"></a></td>
<td class="doxyEnumItemDescription"> (= 52 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SECREFLIST<a id="a21e038f5b8958e203d28bc4f18472352a8d15e2d8a126c4504d2c0c3b430cf849"></a></td>
<td class="doxyEnumItemDescription"> (= 53)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SECTION<a id="a21e038f5b8958e203d28bc4f18472352a08bf0e6e909709da24a469cafe0b9d17"></a></td>
<td class="doxyEnumItemDescription"> (= 54)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SUBPAGE<a id="a21e038f5b8958e203d28bc4f18472352a2f98272f2f7c14500cf04726b028e84b"></a></td>
<td class="doxyEnumItemDescription"> (= 55)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SUBSECTION<a id="a21e038f5b8958e203d28bc4f18472352a345882397f6eecbf9a1d907dbac3386e"></a></td>
<td class="doxyEnumItemDescription"> (= 56)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SUBSUBSECTION<a id="a21e038f5b8958e203d28bc4f18472352a35fa554923a8344b726d70fd99b13a58"></a></td>
<td class="doxyEnumItemDescription"> (= 57)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_PARAGRAPH<a id="a21e038f5b8958e203d28bc4f18472352a63c6751678949b9d8f0f9487bbad3a9b"></a></td>
<td class="doxyEnumItemDescription"> (= 58)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SINCE<a id="a21e038f5b8958e203d28bc4f18472352a070deed3dcb1cbf835abd257462056da"></a></td>
<td class="doxyEnumItemDescription"> (= 59 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SKIP<a id="a21e038f5b8958e203d28bc4f18472352a90240fb4b75ec80ef6b8fcb4cbd3f514"></a></td>
<td class="doxyEnumItemDescription"> (= 60)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SKIPLINE<a id="a21e038f5b8958e203d28bc4f18472352aa75989ba1c81b80e24305a0c877db50e"></a></td>
<td class="doxyEnumItemDescription"> (= 61)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_STARTCODE<a id="a21e038f5b8958e203d28bc4f18472352aa9dcbd40545eeac8c540fec299753dd8"></a></td>
<td class="doxyEnumItemDescription"> (= 62)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_JAVALINK<a id="a21e038f5b8958e203d28bc4f18472352adfb24b50d39e530a9e8c5c0fac13f903"></a></td>
<td class="doxyEnumItemDescription"> (= 63)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_UNTIL<a id="a21e038f5b8958e203d28bc4f18472352a7f44aa65af1a362f5f6a312aee67a7f3"></a></td>
<td class="doxyEnumItemDescription"> (= 64)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_VERBATIM<a id="a21e038f5b8958e203d28bc4f18472352a864172f2ef5172c9ae89bf554989e3f0"></a></td>
<td class="doxyEnumItemDescription"> (= 65)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_VERBINCLUDE<a id="a21e038f5b8958e203d28bc4f18472352acd65497e2ee7b42098562637172b7688"></a></td>
<td class="doxyEnumItemDescription"> (= 66)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_VERSION<a id="a21e038f5b8958e203d28bc4f18472352a9433d3f9a647fa0e1011c23cb57b8698"></a></td>
<td class="doxyEnumItemDescription"> (= 67 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_WARNING<a id="a21e038f5b8958e203d28bc4f18472352a9c30e0a66a20b8a6f017e5f520a80fd9"></a></td>
<td class="doxyEnumItemDescription"> (= 68 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_XREFITEM<a id="a21e038f5b8958e203d28bc4f18472352aee7593d73dbf9d219ab4d640ae732cc2"></a></td>
<td class="doxyEnumItemDescription"> (= 69 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_XMLONLY<a id="a21e038f5b8958e203d28bc4f18472352a57e61b352c9fdfb95920473a739e8c93"></a></td>
<td class="doxyEnumItemDescription"> (= 70)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_DOT<a id="a21e038f5b8958e203d28bc4f18472352af02b1d7d8a6be02fd4cfcd60960e18f3"></a></td>
<td class="doxyEnumItemDescription"> (= 71)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDDOT<a id="a21e038f5b8958e203d28bc4f18472352a5dfbb186fac10ac5dbfef6bd024d10e6"></a></td>
<td class="doxyEnumItemDescription"> (= 72)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_MSC<a id="a21e038f5b8958e203d28bc4f18472352a67dc18b4d333838d663ff158dc396dc4"></a></td>
<td class="doxyEnumItemDescription"> (= 73)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDMSC<a id="a21e038f5b8958e203d28bc4f18472352a76ab524b7b43344cb6fae72310cbf151"></a></td>
<td class="doxyEnumItemDescription"> (= 74)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_MANONLY<a id="a21e038f5b8958e203d28bc4f18472352a6f7c17eb953b73f62e88291a95b8f8f1"></a></td>
<td class="doxyEnumItemDescription"> (= 75)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDMANONLY<a id="a21e038f5b8958e203d28bc4f18472352a8f68939f475ac8c43ca713ead53d6cab"></a></td>
<td class="doxyEnumItemDescription"> (= 76)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_INCWITHLINES<a id="a21e038f5b8958e203d28bc4f18472352ad802574e328d535dcb1f7b74920a8d3e"></a></td>
<td class="doxyEnumItemDescription"> (= 77)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_INHERITDOC<a id="a21e038f5b8958e203d28bc4f18472352a79af7f38b71c949f6a74aab87cdcad08"></a></td>
<td class="doxyEnumItemDescription"> (= 78)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_TPARAM<a id="a21e038f5b8958e203d28bc4f18472352ae2cacaa0d0ef46388f69a15f8df6fae3"></a></td>
<td class="doxyEnumItemDescription"> (= 79 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_COPYBRIEF<a id="a21e038f5b8958e203d28bc4f18472352aa5f1b4117decd375d8081ab45ceede09"></a></td>
<td class="doxyEnumItemDescription"> (= 80)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_COPYDETAILS<a id="a21e038f5b8958e203d28bc4f18472352a5dccfe8d61fa9277f8d08ffa8c64b298"></a></td>
<td class="doxyEnumItemDescription"> (= 81)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_QUOTE<a id="a21e038f5b8958e203d28bc4f18472352ab632762af37578d45ecfb0cdaa5ff232"></a></td>
<td class="doxyEnumItemDescription"> (= 82)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_MSCFILE<a id="a21e038f5b8958e203d28bc4f18472352a63398f483e84697f0cf23c0f152d0756"></a></td>
<td class="doxyEnumItemDescription"> (= 83)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_DCOLON<a id="a21e038f5b8958e203d28bc4f18472352a82d29f1aaf679ee418491b7e4f5ea07d"></a></td>
<td class="doxyEnumItemDescription"> (= 84)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_COPYRIGHT<a id="a21e038f5b8958e203d28bc4f18472352ae321a73a6a51f0cfc2807b39d2cc7c43"></a></td>
<td class="doxyEnumItemDescription"> (= 85 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_CITE<a id="a21e038f5b8958e203d28bc4f18472352ae5cd23261659ca0b8788aee3e25ac2c9"></a></td>
<td class="doxyEnumItemDescription"> (= 86)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SNIPPET<a id="a21e038f5b8958e203d28bc4f18472352addd789b088614cf6dcd9ecffefa3c45e"></a></td>
<td class="doxyEnumItemDescription"> (= 87)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_RTFONLY<a id="a21e038f5b8958e203d28bc4f18472352aeda637e085517ac5c985e4bbde534cbf"></a></td>
<td class="doxyEnumItemDescription"> (= 88)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDRTFONLY<a id="a21e038f5b8958e203d28bc4f18472352aff8a599fe412c147e49ce9b7cfb6347e"></a></td>
<td class="doxyEnumItemDescription"> (= 89)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_PIPE<a id="a21e038f5b8958e203d28bc4f18472352a39a2ec9dd7990d49e04fb1f3bb64ad78"></a></td>
<td class="doxyEnumItemDescription"> (= 90)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_VHDLFLOW<a id="a21e038f5b8958e203d28bc4f18472352afe80c46dc9887d93a9d4906dd88ae574"></a></td>
<td class="doxyEnumItemDescription"> (= 91)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_DBONLY<a id="a21e038f5b8958e203d28bc4f18472352a13d8ae4592b82027eaed541ef9f0dbe9"></a></td>
<td class="doxyEnumItemDescription"> (= 92)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDDBONLY<a id="a21e038f5b8958e203d28bc4f18472352a53b3f46b37a53e15d2539272d9d793b1"></a></td>
<td class="doxyEnumItemDescription"> (= 93)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDINTERNAL<a id="a21e038f5b8958e203d28bc4f18472352ad8b7abe1a1730ef26e0bda0caf7085c6"></a></td>
<td class="doxyEnumItemDescription"> (= 94)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_PARBLOCK<a id="a21e038f5b8958e203d28bc4f18472352a964dd1032e70fb6bec5e09d1991beb09"></a></td>
<td class="doxyEnumItemDescription"> (= 95)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDPARBLOCK<a id="a21e038f5b8958e203d28bc4f18472352a88e0b19afffef20da4e671406083af3d"></a></td>
<td class="doxyEnumItemDescription"> (= 96)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_DIAFILE<a id="a21e038f5b8958e203d28bc4f18472352af20bfd51496c7c1da4f15636a44f3f53"></a></td>
<td class="doxyEnumItemDescription"> (= 97)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_LATEXINCLUDE<a id="a21e038f5b8958e203d28bc4f18472352a7572b4273d3a432a72714dc020cf10ca"></a></td>
<td class="doxyEnumItemDescription"> (= 98)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_NDASH<a id="a21e038f5b8958e203d28bc4f18472352ac8a3932bd8a0d7bc9ce2a5deb488aba0"></a></td>
<td class="doxyEnumItemDescription"> (= 99)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_MDASH<a id="a21e038f5b8958e203d28bc4f18472352a8fcff20c756832f83f46d634de1bcb04"></a></td>
<td class="doxyEnumItemDescription"> (= 100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_STARTUML<a id="a21e038f5b8958e203d28bc4f18472352a8b6ffc33505c10c833e28c5e6cdc7fbf"></a></td>
<td class="doxyEnumItemDescription"> (= 101)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDUML<a id="a21e038f5b8958e203d28bc4f18472352a842a2c5e8ba76f8e009f87a5f56a38da"></a></td>
<td class="doxyEnumItemDescription"> (= 102)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SETSCOPE<a id="a21e038f5b8958e203d28bc4f18472352a0c476e6469537815832cd5c98ef1204d"></a></td>
<td class="doxyEnumItemDescription"> (= 103)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_PUNT<a id="a21e038f5b8958e203d28bc4f18472352a327f68a61235c8922c3b4228bc2420c9"></a></td>
<td class="doxyEnumItemDescription"> (= 104)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_PLUS<a id="a21e038f5b8958e203d28bc4f18472352a798425a98992c1b0eaada7bd20e4bf57"></a></td>
<td class="doxyEnumItemDescription"> (= 105)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_MINUS<a id="a21e038f5b8958e203d28bc4f18472352aedbb38e82179db12cec6adb259f83ee4"></a></td>
<td class="doxyEnumItemDescription"> (= 106)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_INCLUDEDOC<a id="a21e038f5b8958e203d28bc4f18472352ae34d6e481b3de7ef687fed2a373156df"></a></td>
<td class="doxyEnumItemDescription"> (= 107)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SNIPPETDOC<a id="a21e038f5b8958e203d28bc4f18472352aecaa42bc29ded33f86291e63c4cfa49d"></a></td>
<td class="doxyEnumItemDescription"> (= 108)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SNIPWITHLINES<a id="a21e038f5b8958e203d28bc4f18472352af1822f27930af0abbb6f9c4cc35bf50d"></a></td>
<td class="doxyEnumItemDescription"> (= 109)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_EMOJI<a id="a21e038f5b8958e203d28bc4f18472352ad84e00d5577d4f53f8273dffa5bb04b1"></a></td>
<td class="doxyEnumItemDescription"> (= 110)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_EQUAL<a id="a21e038f5b8958e203d28bc4f18472352a3a9c7d82f8086ab2b77df8add8d10f7e"></a></td>
<td class="doxyEnumItemDescription"> (= 111)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_RTFINCLUDE<a id="a21e038f5b8958e203d28bc4f18472352af9dfb2bbcfbd10e4537cb44f1bdf77e9"></a></td>
<td class="doxyEnumItemDescription"> (= 112)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_DOCBOOKINCLUDE<a id="a21e038f5b8958e203d28bc4f18472352ad12938c09da1594a3c4c2906f41d0983"></a></td>
<td class="doxyEnumItemDescription"> (= 113)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_MANINCLUDE<a id="a21e038f5b8958e203d28bc4f18472352a6f9dd7e375093df0e7398fb35a49af0d"></a></td>
<td class="doxyEnumItemDescription"> (= 114)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_XMLINCLUDE<a id="a21e038f5b8958e203d28bc4f18472352a29547a4f569049c95f3337cad68a9438"></a></td>
<td class="doxyEnumItemDescription"> (= 115)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ILINE<a id="a21e038f5b8958e203d28bc4f18472352a3966b700ae5102ce64cb9b28b8001195"></a></td>
<td class="doxyEnumItemDescription"> (= 116)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ILITERAL<a id="a21e038f5b8958e203d28bc4f18472352a4ef72f3af8b0ae7bdef68fd0cf397e03"></a></td>
<td class="doxyEnumItemDescription"> (= 117)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDILITERAL<a id="a21e038f5b8958e203d28bc4f18472352a58f5ab665148179e7da0879856b03c14"></a></td>
<td class="doxyEnumItemDescription"> (= 118)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_IFILE<a id="a21e038f5b8958e203d28bc4f18472352a9ce6c869197029284ddc2d3ed0e7d966"></a></td>
<td class="doxyEnumItemDescription"> (= 119)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SHOWDATE<a id="a21e038f5b8958e203d28bc4f18472352a471c6f18470c476dabebc4fc97623879"></a></td>
<td class="doxyEnumItemDescription"> (= 120)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ISTARTCODE<a id="a21e038f5b8958e203d28bc4f18472352ac71dee7b84425f6765fa4805420ed769"></a></td>
<td class="doxyEnumItemDescription"> (= 121)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDICODE<a id="a21e038f5b8958e203d28bc4f18472352ac8a2d601cbeeb69fcdb5273d752a838b"></a></td>
<td class="doxyEnumItemDescription"> (= 122)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_IVERBATIM<a id="a21e038f5b8958e203d28bc4f18472352a25f6add2a9a746704f5704fad4e3d8cb"></a></td>
<td class="doxyEnumItemDescription"> (= 123)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_ENDIVERBATIM<a id="a21e038f5b8958e203d28bc4f18472352a6040d1fc7cc3f1022dd54c566423318d"></a></td>
<td class="doxyEnumItemDescription"> (= 124)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_IANCHOR<a id="a21e038f5b8958e203d28bc4f18472352adf944b4dade3ec860a15f1cf658f0545"></a></td>
<td class="doxyEnumItemDescription"> (= 125)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_DOXYCONFIG<a id="a21e038f5b8958e203d28bc4f18472352a03c960e253e15c7a6972f9b429560525"></a></td>
<td class="doxyEnumItemDescription"> (= 126)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_IMPORTANT<a id="a21e038f5b8958e203d28bc4f18472352a299de12737a830b685466865f4a3ea06"></a></td>
<td class="doxyEnumItemDescription"> (= 127 | SIMPLESECT_BIT)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SUBPARAGRAPH<a id="a21e038f5b8958e203d28bc4f18472352a2c9f6fed8166f4c746540413f1119c75"></a></td>
<td class="doxyEnumItemDescription"> (= 128)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_SUBSUBPARAGRAPH<a id="a21e038f5b8958e203d28bc4f18472352a4944b738e4ac1f8008143404bb070e49"></a></td>
<td class="doxyEnumItemDescription"> (= 129)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_IPREFIX<a id="a21e038f5b8958e203d28bc4f18472352a735e652991dbdfb489d4c8265b3ff64e"></a></td>
<td class="doxyEnumItemDescription"> (= 130)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_PLANTUMLFILE<a id="a21e038f5b8958e203d28bc4f18472352a8e0ea841cb1abdf12857f32524b5f8d3"></a></td>
<td class="doxyEnumItemDescription"> (= 131)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_EXCLAMATION<a id="a21e038f5b8958e203d28bc4f18472352a46b91211a7a50b7d83c96ac514028f2a"></a></td>
<td class="doxyEnumItemDescription"> (= 132)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CMD_QUESTION<a id="a21e038f5b8958e203d28bc4f18472352a9098d932d7292ccdcdbfc7fbfab6035e"></a></td>
<td class="doxyEnumItemDescription"> (= 133)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 28 of file <a href="/web-doxygen/docs/api/files/src/cmdmapper-h">cmdmapper.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">30</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a> = 0x1000,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a696b031073e74bf2cb98e5ef201d4aa3">32</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a696b031073e74bf2cb98e5ef201d4aa3">UNKNOWN</a>          = 0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a6a28a1008ba398c9092acd8943a565c3">33</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a6a28a1008ba398c9092acd8943a565c3">CMD_ADDINDEX</a>     = 1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a6f9f21c0cb1ce6e48a2aac0475e7065d">34</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a6f9f21c0cb1ce6e48a2aac0475e7065d">CMD_AMP</a>          = 2,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aea2d6a1dd2fe7915d34d1932402a5389">35</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aea2d6a1dd2fe7915d34d1932402a5389">CMD_ANCHOR</a>       = 3,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a231334a819076be4d21ffbf9eb3d5fac">36</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a231334a819076be4d21ffbf9eb3d5fac">CMD_AT</a>           = 4,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aae34bcb7153edac8378fd4280db2e44c">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aae34bcb7153edac8378fd4280db2e44c">CMD_ATTENTION</a>    = 5  | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352af0700e8bd6adf3a36fbd38905bcd399e">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352af0700e8bd6adf3a36fbd38905bcd399e">CMD_AUTHOR</a>       = 6  | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a02da166bedae5175de575f357cac265c">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a02da166bedae5175de575f357cac265c">CMD_AUTHORS</a>      = 7  | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aed8e4495d256975e34e0fcaee34ebe3b">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aed8e4495d256975e34e0fcaee34ebe3b">CMD_BOLD</a>         = 8,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ab41541930cbc3eb72b54d4c6da3c0ae8">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ab41541930cbc3eb72b54d4c6da3c0ae8">CMD_BSLASH</a>       = 9,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a8de3af7ff872fa5ad8f22fc5eac6465b">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a8de3af7ff872fa5ad8f22fc5eac6465b">CMD_CODE</a>         = 10,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ae28a43d56ad7068093118e9e9d80adf5">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ae28a43d56ad7068093118e9e9d80adf5">CMD_COPYDOC</a>      = 11,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352af0443850cff338e6f483e7ed15d12dcf">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352af0443850cff338e6f483e7ed15d12dcf">CMD_DATE</a>         = 12 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a036b0b8401bf33b8e70ea757f86bead6">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a036b0b8401bf33b8e70ea757f86bead6">CMD_DOLLAR</a>       = 13,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a23fe4833e0a54fc766064003db874806">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a23fe4833e0a54fc766064003db874806">CMD_DONTINCLUDE</a>  = 14,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a0b1af583174c0fb1932fd4685d80bd0b">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a0b1af583174c0fb1932fd4685d80bd0b">CMD_DOTFILE</a>      = 15,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a4ea7c7754bb98d8d463a08828e44811e">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a4ea7c7754bb98d8d463a08828e44811e">CMD_EMPHASIS</a>     = 16,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a4ffb780097c3c1177340a16a7a7c1a62">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a4ffb780097c3c1177340a16a7a7c1a62">CMD_ENDCODE</a>      = 17,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a8c78bc70ef572a2d5767fe08759b866f">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a8c78bc70ef572a2d5767fe08759b866f">CMD_ENDHTMLONLY</a>  = 18,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a169f22d54d12b12865279ec72666799a">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a169f22d54d12b12865279ec72666799a">CMD_ENDLATEXONLY</a> = 19,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a91531d8419b3e6261b793638cd6f8f70">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a91531d8419b3e6261b793638cd6f8f70">CMD_ENDLINK</a>      = 20,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a15578fca2422b89bf32bd85c294b4a26">53</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a15578fca2422b89bf32bd85c294b4a26">CMD_ENDSECREFLIST</a>= 21,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a1d1e116739898a0f2d5c43c0a70f81d7">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a1d1e116739898a0f2d5c43c0a70f81d7">CMD_ENDVERBATIM</a>  = 22,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a8639fdd14d2cabd7aef30f1469c7d18c">55</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a8639fdd14d2cabd7aef30f1469c7d18c">CMD_ENDXMLONLY</a>   = 23,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a996c5bab025550bae11a0748dc9331d7">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a996c5bab025550bae11a0748dc9331d7">CMD_EXCEPTION</a>    = 24 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352acc81c3d8371cc6a7b01e183a8c9fa04e">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352acc81c3d8371cc6a7b01e183a8c9fa04e">CMD_FORMULA</a>      = 25,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a6454f09b46f73d0d141a041314c0b95c">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a6454f09b46f73d0d141a041314c0b95c">CMD_GREATER</a>      = 26,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a602d16174562d50f3cf2f8eda1c6ebb6">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a602d16174562d50f3cf2f8eda1c6ebb6">CMD_HASH</a>         = 27,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ad5344bb3c420c40b5bf1cd46e6d80cc5">60</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ad5344bb3c420c40b5bf1cd46e6d80cc5">CMD_HTMLINCLUDE</a>  = 28,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a02ff5a94f1a879395b00661ec8185dfa">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a02ff5a94f1a879395b00661ec8185dfa">CMD_HTMLONLY</a>     = 29,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a50ef1a2484f87e0e789063b64718f9c6">62</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a50ef1a2484f87e0e789063b64718f9c6">CMD_IMAGE</a>        = 30,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aa477dc9f970da083d8eb3cd9b5f8835c">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aa477dc9f970da083d8eb3cd9b5f8835c">CMD_INCLUDE</a>      = 31,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a6de97492df438e4d22002087f483ecf2">64</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a6de97492df438e4d22002087f483ecf2">CMD_INTERNAL</a>     = 32,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a85bc5fc2f86ed5c6b7d7a1b753776372">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a85bc5fc2f86ed5c6b7d7a1b753776372">CMD_INTERNALREF</a>  = 33,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352abadfe37f10dd2a7ef97a95ae0503b0c6">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352abadfe37f10dd2a7ef97a95ae0503b0c6">CMD_INVARIANT</a>    = 34 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a> ,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a873d102356c495a37910b496c4ab1baa">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a873d102356c495a37910b496c4ab1baa">CMD_LATEXONLY</a>    = 35,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aa76513f8aaef2b7d02c9993b3920fcec">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aa76513f8aaef2b7d02c9993b3920fcec">CMD_LESS</a>         = 36,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ab166f31f6afdd2828434e9681a93390a">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ab166f31f6afdd2828434e9681a93390a">CMD_LI</a>           = 37,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a9a639b8b2e64e575a3d063a48b3450a5">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a9a639b8b2e64e575a3d063a48b3450a5">CMD_LINE</a>         = 38,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a7a5191a7f81ddc3b67a10a05e467829f">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a7a5191a7f81ddc3b67a10a05e467829f">CMD_LINEBREAK</a>    = 39,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a9308b376abf23762b61f1e71c3dc3201">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a9308b376abf23762b61f1e71c3dc3201">CMD_LINK</a>         = 40,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ae54082d6d8530592497cf241bed3fe59">73</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ae54082d6d8530592497cf241bed3fe59">CMD_NOTE</a>         = 41 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a1948243b070f58bd97b9877f02d9c29b">74</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a1948243b070f58bd97b9877f02d9c29b">CMD_PAR</a>          = 42 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352abd01c1081b94961568a7835a6e55818b">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352abd01c1081b94961568a7835a6e55818b">CMD_PARAM</a>        = 43 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a71a82fcfdc616129c03fe458496b4906">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a71a82fcfdc616129c03fe458496b4906">CMD_PERCENT</a>      = 44,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a0341498d2c2a13e06e6498d5d7f0b00e">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a0341498d2c2a13e06e6498d5d7f0b00e">CMD_POST</a>         = 45 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a33127d73e7d3569f295179dab1d3c868">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a33127d73e7d3569f295179dab1d3c868">CMD_PRE</a>          = 46 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aa9a69c720668a9e5705eef2fdd0938b1">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aa9a69c720668a9e5705eef2fdd0938b1">CMD_REF</a>          = 47,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a8fa243222e547a267c94e32c8c8c9c0a">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a8fa243222e547a267c94e32c8c8c9c0a">CMD_SECREFITEM</a>   = 48,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a86b78f3934f4994a11865685082a4dfc">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a86b78f3934f4994a11865685082a4dfc">CMD_REMARK</a>       = 49 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a> ,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a6ba091ac10f7a7cf1ff37262bd57d9d3">82</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a6ba091ac10f7a7cf1ff37262bd57d9d3">CMD_RETURN</a>       = 50 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a> ,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a6d933a567cc87ce84eb73ca916c75b6e">83</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a6d933a567cc87ce84eb73ca916c75b6e">CMD_RETVAL</a>       = 51 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ab80aa9991ccbef64c2d3751905610771">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ab80aa9991ccbef64c2d3751905610771">CMD_SA</a>           = 52 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a> ,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a8d15e2d8a126c4504d2c0c3b430cf849">85</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a8d15e2d8a126c4504d2c0c3b430cf849">CMD_SECREFLIST</a>   = 53,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a08bf0e6e909709da24a469cafe0b9d17">86</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a08bf0e6e909709da24a469cafe0b9d17">CMD_SECTION</a>      = 54,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a2f98272f2f7c14500cf04726b028e84b">87</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a2f98272f2f7c14500cf04726b028e84b">CMD_SUBPAGE</a>      = 55,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a345882397f6eecbf9a1d907dbac3386e">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a345882397f6eecbf9a1d907dbac3386e">CMD_SUBSECTION</a>   = 56,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a35fa554923a8344b726d70fd99b13a58">89</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a35fa554923a8344b726d70fd99b13a58">CMD_SUBSUBSECTION</a>= 57,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a63c6751678949b9d8f0f9487bbad3a9b">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a63c6751678949b9d8f0f9487bbad3a9b">CMD_PARAGRAPH</a>    = 58,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a070deed3dcb1cbf835abd257462056da">91</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a070deed3dcb1cbf835abd257462056da">CMD_SINCE</a>        = 59 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a90240fb4b75ec80ef6b8fcb4cbd3f514">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a90240fb4b75ec80ef6b8fcb4cbd3f514">CMD_SKIP</a>         = 60,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aa75989ba1c81b80e24305a0c877db50e">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aa75989ba1c81b80e24305a0c877db50e">CMD_SKIPLINE</a>     = 61,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aa9dcbd40545eeac8c540fec299753dd8">94</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aa9dcbd40545eeac8c540fec299753dd8">CMD_STARTCODE</a>    = 62,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352adfb24b50d39e530a9e8c5c0fac13f903">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352adfb24b50d39e530a9e8c5c0fac13f903">CMD_JAVALINK</a>     = 63,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a7f44aa65af1a362f5f6a312aee67a7f3">96</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a7f44aa65af1a362f5f6a312aee67a7f3">CMD_UNTIL</a>        = 64,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a864172f2ef5172c9ae89bf554989e3f0">97</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a864172f2ef5172c9ae89bf554989e3f0">CMD_VERBATIM</a>     = 65,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352acd65497e2ee7b42098562637172b7688">98</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352acd65497e2ee7b42098562637172b7688">CMD_VERBINCLUDE</a>  = 66,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a9433d3f9a647fa0e1011c23cb57b8698">99</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a9433d3f9a647fa0e1011c23cb57b8698">CMD_VERSION</a>      = 67 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a9c30e0a66a20b8a6f017e5f520a80fd9">100</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a9c30e0a66a20b8a6f017e5f520a80fd9">CMD_WARNING</a>      = 68 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aee7593d73dbf9d219ab4d640ae732cc2">101</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aee7593d73dbf9d219ab4d640ae732cc2">CMD_XREFITEM</a>     = 69 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a57e61b352c9fdfb95920473a739e8c93">102</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a57e61b352c9fdfb95920473a739e8c93">CMD_XMLONLY</a>      = 70,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352af02b1d7d8a6be02fd4cfcd60960e18f3">103</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352af02b1d7d8a6be02fd4cfcd60960e18f3">CMD_DOT</a>          = 71,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a5dfbb186fac10ac5dbfef6bd024d10e6">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a5dfbb186fac10ac5dbfef6bd024d10e6">CMD_ENDDOT</a>       = 72,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a67dc18b4d333838d663ff158dc396dc4">105</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a67dc18b4d333838d663ff158dc396dc4">CMD_MSC</a>          = 73,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a76ab524b7b43344cb6fae72310cbf151">106</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a76ab524b7b43344cb6fae72310cbf151">CMD_ENDMSC</a>       = 74,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a6f7c17eb953b73f62e88291a95b8f8f1">107</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a6f7c17eb953b73f62e88291a95b8f8f1">CMD_MANONLY</a>      = 75,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a8f68939f475ac8c43ca713ead53d6cab">108</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a8f68939f475ac8c43ca713ead53d6cab">CMD_ENDMANONLY</a>   = 76,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ad802574e328d535dcb1f7b74920a8d3e">109</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ad802574e328d535dcb1f7b74920a8d3e">CMD_INCWITHLINES</a> = 77,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a79af7f38b71c949f6a74aab87cdcad08">110</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a79af7f38b71c949f6a74aab87cdcad08">CMD_INHERITDOC</a>   = 78,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ae2cacaa0d0ef46388f69a15f8df6fae3">111</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ae2cacaa0d0ef46388f69a15f8df6fae3">CMD_TPARAM</a>       = 79 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aa5f1b4117decd375d8081ab45ceede09">112</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aa5f1b4117decd375d8081ab45ceede09">CMD_COPYBRIEF</a>    = 80,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a5dccfe8d61fa9277f8d08ffa8c64b298">113</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a5dccfe8d61fa9277f8d08ffa8c64b298">CMD_COPYDETAILS</a>  = 81,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ab632762af37578d45ecfb0cdaa5ff232">114</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ab632762af37578d45ecfb0cdaa5ff232">CMD_QUOTE</a>        = 82,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a63398f483e84697f0cf23c0f152d0756">115</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a63398f483e84697f0cf23c0f152d0756">CMD_MSCFILE</a>      = 83,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a82d29f1aaf679ee418491b7e4f5ea07d">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a82d29f1aaf679ee418491b7e4f5ea07d">CMD_DCOLON</a>       = 84,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ae321a73a6a51f0cfc2807b39d2cc7c43">117</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ae321a73a6a51f0cfc2807b39d2cc7c43">CMD_COPYRIGHT</a>    = 85 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ae5cd23261659ca0b8788aee3e25ac2c9">118</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ae5cd23261659ca0b8788aee3e25ac2c9">CMD_CITE</a>         = 86,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352addd789b088614cf6dcd9ecffefa3c45e">119</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352addd789b088614cf6dcd9ecffefa3c45e">CMD_SNIPPET</a>      = 87,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aeda637e085517ac5c985e4bbde534cbf">120</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aeda637e085517ac5c985e4bbde534cbf">CMD_RTFONLY</a>      = 88,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aff8a599fe412c147e49ce9b7cfb6347e">121</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aff8a599fe412c147e49ce9b7cfb6347e">CMD_ENDRTFONLY</a>   = 89,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a39a2ec9dd7990d49e04fb1f3bb64ad78">122</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a39a2ec9dd7990d49e04fb1f3bb64ad78">CMD_PIPE</a>         = 90,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352afe80c46dc9887d93a9d4906dd88ae574">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352afe80c46dc9887d93a9d4906dd88ae574">CMD_VHDLFLOW</a>     = 91,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a13d8ae4592b82027eaed541ef9f0dbe9">124</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a13d8ae4592b82027eaed541ef9f0dbe9">CMD_DBONLY</a>       = 92,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a53b3f46b37a53e15d2539272d9d793b1">125</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a53b3f46b37a53e15d2539272d9d793b1">CMD_ENDDBONLY</a>    = 93,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ad8b7abe1a1730ef26e0bda0caf7085c6">126</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ad8b7abe1a1730ef26e0bda0caf7085c6">CMD_ENDINTERNAL</a>  = 94,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a964dd1032e70fb6bec5e09d1991beb09">127</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a964dd1032e70fb6bec5e09d1991beb09">CMD_PARBLOCK</a>     = 95,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a88e0b19afffef20da4e671406083af3d">128</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a88e0b19afffef20da4e671406083af3d">CMD_ENDPARBLOCK</a>  = 96,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352af20bfd51496c7c1da4f15636a44f3f53">129</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352af20bfd51496c7c1da4f15636a44f3f53">CMD_DIAFILE</a>      = 97,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a7572b4273d3a432a72714dc020cf10ca">130</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a7572b4273d3a432a72714dc020cf10ca">CMD_LATEXINCLUDE</a> = 98,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ac8a3932bd8a0d7bc9ce2a5deb488aba0">131</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ac8a3932bd8a0d7bc9ce2a5deb488aba0">CMD_NDASH</a>        = 99,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a8fcff20c756832f83f46d634de1bcb04">132</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a8fcff20c756832f83f46d634de1bcb04">CMD_MDASH</a>        = 100,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a8b6ffc33505c10c833e28c5e6cdc7fbf">133</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a8b6ffc33505c10c833e28c5e6cdc7fbf">CMD_STARTUML</a>     = 101,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a842a2c5e8ba76f8e009f87a5f56a38da">134</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a842a2c5e8ba76f8e009f87a5f56a38da">CMD_ENDUML</a>       = 102,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a0c476e6469537815832cd5c98ef1204d">135</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a0c476e6469537815832cd5c98ef1204d">CMD_SETSCOPE</a>     = 103,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a327f68a61235c8922c3b4228bc2420c9">136</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a327f68a61235c8922c3b4228bc2420c9">CMD_PUNT</a>         = 104,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a798425a98992c1b0eaada7bd20e4bf57">137</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a798425a98992c1b0eaada7bd20e4bf57">CMD_PLUS</a>         = 105,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aedbb38e82179db12cec6adb259f83ee4">138</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aedbb38e82179db12cec6adb259f83ee4">CMD_MINUS</a>        = 106,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ae34d6e481b3de7ef687fed2a373156df">139</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ae34d6e481b3de7ef687fed2a373156df">CMD_INCLUDEDOC</a>   = 107,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352aecaa42bc29ded33f86291e63c4cfa49d">140</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352aecaa42bc29ded33f86291e63c4cfa49d">CMD_SNIPPETDOC</a>   = 108,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352af1822f27930af0abbb6f9c4cc35bf50d">141</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352af1822f27930af0abbb6f9c4cc35bf50d">CMD_SNIPWITHLINES</a>= 109,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ad84e00d5577d4f53f8273dffa5bb04b1">142</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ad84e00d5577d4f53f8273dffa5bb04b1">CMD_EMOJI</a>        = 110,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a3a9c7d82f8086ab2b77df8add8d10f7e">143</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a3a9c7d82f8086ab2b77df8add8d10f7e">CMD_EQUAL</a>        = 111,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352af9dfb2bbcfbd10e4537cb44f1bdf77e9">144</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352af9dfb2bbcfbd10e4537cb44f1bdf77e9">CMD_RTFINCLUDE</a>   = 112,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ad12938c09da1594a3c4c2906f41d0983">145</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ad12938c09da1594a3c4c2906f41d0983">CMD_DOCBOOKINCLUDE</a>= 113,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a6f9dd7e375093df0e7398fb35a49af0d">146</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a6f9dd7e375093df0e7398fb35a49af0d">CMD_MANINCLUDE</a>   = 114,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a29547a4f569049c95f3337cad68a9438">147</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a29547a4f569049c95f3337cad68a9438">CMD_XMLINCLUDE</a>   = 115,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a3966b700ae5102ce64cb9b28b8001195">148</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a3966b700ae5102ce64cb9b28b8001195">CMD_ILINE</a>        = 116,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a4ef72f3af8b0ae7bdef68fd0cf397e03">149</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a4ef72f3af8b0ae7bdef68fd0cf397e03">CMD_ILITERAL</a>     = 117,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a58f5ab665148179e7da0879856b03c14">150</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a58f5ab665148179e7da0879856b03c14">CMD_ENDILITERAL</a>  = 118,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a9ce6c869197029284ddc2d3ed0e7d966">151</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a9ce6c869197029284ddc2d3ed0e7d966">CMD_IFILE</a>        = 119,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a471c6f18470c476dabebc4fc97623879">152</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a471c6f18470c476dabebc4fc97623879">CMD_SHOWDATE</a>     = 120,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ac71dee7b84425f6765fa4805420ed769">153</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ac71dee7b84425f6765fa4805420ed769">CMD_ISTARTCODE</a>   = 121,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352ac8a2d601cbeeb69fcdb5273d752a838b">154</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352ac8a2d601cbeeb69fcdb5273d752a838b">CMD_ENDICODE</a>     = 122,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a25f6add2a9a746704f5704fad4e3d8cb">155</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a25f6add2a9a746704f5704fad4e3d8cb">CMD_IVERBATIM</a>    = 123,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a6040d1fc7cc3f1022dd54c566423318d">156</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a6040d1fc7cc3f1022dd54c566423318d">CMD_ENDIVERBATIM</a> = 124,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352adf944b4dade3ec860a15f1cf658f0545">157</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352adf944b4dade3ec860a15f1cf658f0545">CMD_IANCHOR</a>      = 125,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a03c960e253e15c7a6972f9b429560525">158</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a03c960e253e15c7a6972f9b429560525">CMD_DOXYCONFIG</a>   = 126,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a299de12737a830b685466865f4a3ea06">159</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a299de12737a830b685466865f4a3ea06">CMD_IMPORTANT</a>    = 127 | <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a2c9f6fed8166f4c746540413f1119c75">160</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a2c9f6fed8166f4c746540413f1119c75">CMD_SUBPARAGRAPH</a> = 128,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a4944b738e4ac1f8008143404bb070e49">161</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a4944b738e4ac1f8008143404bb070e49">CMD_SUBSUBPARAGRAPH</a> = 129,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a735e652991dbdfb489d4c8265b3ff64e">162</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a735e652991dbdfb489d4c8265b3ff64e">CMD_IPREFIX</a>      = 130,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a8e0ea841cb1abdf12857f32524b5f8d3">163</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a8e0ea841cb1abdf12857f32524b5f8d3">CMD_PLANTUMLFILE</a> = 131,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a46b91211a7a50b7d83c96ac514028f2a">164</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a46b91211a7a50b7d83c96ac514028f2a">CMD_EXCLAMATION</a>  = 132,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21e038f5b8958e203d28bc4f18472352a9098d932d7292ccdcdbfc7fbfab6035e">165</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a9098d932d7292ccdcdbfc7fbfab6035e">CMD_QUESTION</a>     = 133</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>

</div>
</div>

### HtmlTagType {#a91be16b8342aa3130a4374d78cf42273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class HtmlTagType </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">SIMPLESECT_BIT<a id="a91be16b8342aa3130a4374d78cf42273a4e134ab9f24378509126a1359ea8df72"></a></td>
<td class="doxyEnumItemDescription"> (= 0x1000)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNKNOWN<a id="a91be16b8342aa3130a4374d78cf42273a696b031073e74bf2cb98e5ef201d4aa3"></a></td>
<td class="doxyEnumItemDescription"> (= 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_CENTER<a id="a91be16b8342aa3130a4374d78cf42273aa98e78abc5a518292bf17a61e90af51e"></a></td>
<td class="doxyEnumItemDescription"> (= 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_TABLE<a id="a91be16b8342aa3130a4374d78cf42273af86f2e136782e591c3a3ecdd9713c5a8"></a></td>
<td class="doxyEnumItemDescription"> (= 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_CAPTION<a id="a91be16b8342aa3130a4374d78cf42273a2861ae6e47c6162fcdfbcbc3e8c23f7e"></a></td>
<td class="doxyEnumItemDescription"> (= 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_SMALL<a id="a91be16b8342aa3130a4374d78cf42273a9f1d616da06520eb5ed69e011e353e70"></a></td>
<td class="doxyEnumItemDescription"> (= 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_CODE<a id="a91be16b8342aa3130a4374d78cf42273a625085c514754f3aff0a372e2d544862"></a></td>
<td class="doxyEnumItemDescription"> (= 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_IMG<a id="a91be16b8342aa3130a4374d78cf42273a03c65afaa75c587603bb62db4a3ab38a"></a></td>
<td class="doxyEnumItemDescription"> (= 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_PRE<a id="a91be16b8342aa3130a4374d78cf42273ad20ebedb0f176150f27c8cc20336d075"></a></td>
<td class="doxyEnumItemDescription"> (= 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_SUB<a id="a91be16b8342aa3130a4374d78cf42273a43905d2b1313969ae2f210df9ef7c3bb"></a></td>
<td class="doxyEnumItemDescription"> (= 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_SUP<a id="a91be16b8342aa3130a4374d78cf42273a7e216fed22259530ae959dd65ffdb7b9"></a></td>
<td class="doxyEnumItemDescription"> (= 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_TR<a id="a91be16b8342aa3130a4374d78cf42273ad7eb396091ab8336abda28f4d30aedaf"></a></td>
<td class="doxyEnumItemDescription"> (= 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_TD<a id="a91be16b8342aa3130a4374d78cf42273a998b3fd2c81e08ab48d7f331e1ceae6e"></a></td>
<td class="doxyEnumItemDescription"> (= 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_TH<a id="a91be16b8342aa3130a4374d78cf42273a66bf29113782294a2328eb64b5092b14"></a></td>
<td class="doxyEnumItemDescription"> (= 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_OL<a id="a91be16b8342aa3130a4374d78cf42273a3c11c68b002a63cea0de69e7454ea4fa"></a></td>
<td class="doxyEnumItemDescription"> (= 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_UL<a id="a91be16b8342aa3130a4374d78cf42273a40416867bee8eeef2c92f924bf7e92b0"></a></td>
<td class="doxyEnumItemDescription"> (= 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_LI<a id="a91be16b8342aa3130a4374d78cf42273a16842ed17075ce583d7dbb041839b71c"></a></td>
<td class="doxyEnumItemDescription"> (= 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_EMPHASIS<a id="a91be16b8342aa3130a4374d78cf42273a980fa4689bd7bea32d8e46d8f07e84b0"></a></td>
<td class="doxyEnumItemDescription"> (= 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_HR<a id="a91be16b8342aa3130a4374d78cf42273a130d367d050aac12136ad7c4d4446031"></a></td>
<td class="doxyEnumItemDescription"> (= 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_DL<a id="a91be16b8342aa3130a4374d78cf42273ad03672e5cae7c6e405d328ae14fef3f1"></a></td>
<td class="doxyEnumItemDescription"> (= 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_DT<a id="a91be16b8342aa3130a4374d78cf42273a040d13605900029d0cb5e167cbf0960f"></a></td>
<td class="doxyEnumItemDescription"> (= 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_DD<a id="a91be16b8342aa3130a4374d78cf42273ae2f20861bc148186e631f6a6c4501da3"></a></td>
<td class="doxyEnumItemDescription"> (= 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_BR<a id="a91be16b8342aa3130a4374d78cf42273a4f8fb36a7660142ed004cb82a93438d8"></a></td>
<td class="doxyEnumItemDescription"> (= 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_A<a id="a91be16b8342aa3130a4374d78cf42273ad7f6725429a6b56d148761e9cb4e910a"></a></td>
<td class="doxyEnumItemDescription"> (= 22)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_BOLD<a id="a91be16b8342aa3130a4374d78cf42273ab4a6927c07490c4883842f1b74c10706"></a></td>
<td class="doxyEnumItemDescription"> (= 23)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_P<a id="a91be16b8342aa3130a4374d78cf42273a8609691fd1c2d1ab5573087757e8176f"></a></td>
<td class="doxyEnumItemDescription"> (= 24)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_H1<a id="a91be16b8342aa3130a4374d78cf42273a479296801803f02038ab03da7c2ad166"></a></td>
<td class="doxyEnumItemDescription"> (= 25)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_H2<a id="a91be16b8342aa3130a4374d78cf42273a5d5d3cb1354c3eb5e716123d381e1cb6"></a></td>
<td class="doxyEnumItemDescription"> (= 26)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_H3<a id="a91be16b8342aa3130a4374d78cf42273afc62db7b668b12b358f7a07fd1281b81"></a></td>
<td class="doxyEnumItemDescription"> (= 27)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_H4<a id="a91be16b8342aa3130a4374d78cf42273a3a83d8472eedade5c9285898725b2ae4"></a></td>
<td class="doxyEnumItemDescription"> (= 28)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_H5<a id="a91be16b8342aa3130a4374d78cf42273a9ccc9adc294e5d51752440d870151645"></a></td>
<td class="doxyEnumItemDescription"> (= 29)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_H6<a id="a91be16b8342aa3130a4374d78cf42273a73dec4eca50d315e033ed391ed9f68c4"></a></td>
<td class="doxyEnumItemDescription"> (= 30)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_SPAN<a id="a91be16b8342aa3130a4374d78cf42273a21f6ee40064060cfd1b5dbf822ac48b5"></a></td>
<td class="doxyEnumItemDescription"> (= 31)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_DIV<a id="a91be16b8342aa3130a4374d78cf42273adf291d923a41e335a409b36d04b056c9"></a></td>
<td class="doxyEnumItemDescription"> (= 32)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_BLOCKQUOTE<a id="a91be16b8342aa3130a4374d78cf42273a32521974f3333518cf6a7591e14038f9"></a></td>
<td class="doxyEnumItemDescription"> (= 33)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_STRIKE<a id="a91be16b8342aa3130a4374d78cf42273a8a532f6aa0ff83feeb6611f7d1dd3b08"></a></td>
<td class="doxyEnumItemDescription"> (= 34)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_UNDERLINE<a id="a91be16b8342aa3130a4374d78cf42273ab06a28f3b1cebabd6fae9d7323acac91"></a></td>
<td class="doxyEnumItemDescription"> (= 35)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_INS<a id="a91be16b8342aa3130a4374d78cf42273a2dac325066ce35bf3c2b36a7e7b80cb9"></a></td>
<td class="doxyEnumItemDescription"> (= 36)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_DEL<a id="a91be16b8342aa3130a4374d78cf42273a3fe7e05e1718e8e6ba5d244e6b4674db"></a></td>
<td class="doxyEnumItemDescription"> (= 37)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_S<a id="a91be16b8342aa3130a4374d78cf42273a06c725d9e48f372affa01fdb8266c5f2"></a></td>
<td class="doxyEnumItemDescription"> (= 38)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_DETAILS<a id="a91be16b8342aa3130a4374d78cf42273a40431fc3149887bf11da81c3251e8376"></a></td>
<td class="doxyEnumItemDescription"> (= 39)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_CITE<a id="a91be16b8342aa3130a4374d78cf42273ac75d65616ed13b8354516ca1f4a3eabe"></a></td>
<td class="doxyEnumItemDescription"> (= 40)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_THEAD<a id="a91be16b8342aa3130a4374d78cf42273af9e3cb3f2f4243b958e1b98226ec4f30"></a></td>
<td class="doxyEnumItemDescription"> (= 41)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_TBODY<a id="a91be16b8342aa3130a4374d78cf42273a20c25807fdf7ad539a764cf1d393464a"></a></td>
<td class="doxyEnumItemDescription"> (= 42)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_TFOOT<a id="a91be16b8342aa3130a4374d78cf42273a14ef64361eae40bbe02179dc7e9bc4b4"></a></td>
<td class="doxyEnumItemDescription"> (= 43)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_KBD<a id="a91be16b8342aa3130a4374d78cf42273a5a3f7649abce807b951b5f54bc169cea"></a></td>
<td class="doxyEnumItemDescription"> (= 44)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">HTML_TT<a id="a91be16b8342aa3130a4374d78cf42273ae69b5e3f7ee92734b47a599b364cb885"></a></td>
<td class="doxyEnumItemDescription"> (= 45)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_CmdMask<a id="a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281"></a></td>
<td class="doxyEnumItemDescription"> (= 0x100)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_C<a id="a91be16b8342aa3130a4374d78cf42273af3ec0555269e1dbf8e1f318b7b889651"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 0)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_CODE<a id="a91be16b8342aa3130a4374d78cf42273a9b3d66fc2a3c4bf710c5076135665a62"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 1)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_DESCRIPTION<a id="a91be16b8342aa3130a4374d78cf42273aa9a60992392a19960f28501fe94fd399"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 2)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_EXAMPLE<a id="a91be16b8342aa3130a4374d78cf42273a54d238ef8877e0312e8c71ba34cc05b1"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 3)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_EXCEPTION<a id="a91be16b8342aa3130a4374d78cf42273a422227202d96b7b5aedcb1b4f3766d03"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 4)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_INCLUDE<a id="a91be16b8342aa3130a4374d78cf42273a42c366aae0ce10fbaf443dbe1c3fba7c"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 5)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_ITEM<a id="a91be16b8342aa3130a4374d78cf42273a198cc56071a53f9ad84bdb88a3e24867"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 6)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_LIST<a id="a91be16b8342aa3130a4374d78cf42273a40f0bcd06b9f44f4d797d244ea660b8b"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 7)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_LISTHEADER<a id="a91be16b8342aa3130a4374d78cf42273a3e97a35f83d8653e00f2ee154d53cadc"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 8)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_PARA<a id="a91be16b8342aa3130a4374d78cf42273a1e4ef7a0fa3e0c2ec6cd9e22e51de7a5"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 9)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_PARAM<a id="a91be16b8342aa3130a4374d78cf42273aad530a000140559dd09d6d3e2d0aa9f2"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 10)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_PARAMREF<a id="a91be16b8342aa3130a4374d78cf42273a810cd6efd62a332a47c06489186b5538"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 11)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_PERMISSION<a id="a91be16b8342aa3130a4374d78cf42273afffdcbbb92cd0218beb289ac9e5294b8"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 12)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_REMARKS<a id="a91be16b8342aa3130a4374d78cf42273a17061a81d4aad2bffa52eba69c30821e"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 13)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_RETURNS<a id="a91be16b8342aa3130a4374d78cf42273aa1608f9ed465fcf53f739a0c083df8a1"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 14)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_SEE<a id="a91be16b8342aa3130a4374d78cf42273aa510df4e20d611f0e7ec3f9674f444b1"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 15)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_SEEALSO<a id="a91be16b8342aa3130a4374d78cf42273a33a1f2f937300bf6b0de85232ebd7f7d"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 16)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_SUMMARY<a id="a91be16b8342aa3130a4374d78cf42273a44f6d7437443755970b6095ab80fee5d"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 17)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_TERM<a id="a91be16b8342aa3130a4374d78cf42273abccb5b9dd2c20c78c3170dd7c1fa456b"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 18)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_TYPEPARAM<a id="a91be16b8342aa3130a4374d78cf42273a1056e17a54837e4e4c9897c32a9290fd"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 19)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_TYPEPARAMREF<a id="a91be16b8342aa3130a4374d78cf42273a3a697097f6ad40042a7c521025d39446"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 20)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_VALUE<a id="a91be16b8342aa3130a4374d78cf42273a3a59f24296bc8eae02ed1a85f1e05c04"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 21)</td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">XML_INHERITDOC<a id="a91be16b8342aa3130a4374d78cf42273afdede65d45b1dfdc8cad241a62d60ee5"></a></td>
<td class="doxyEnumItemDescription"> (= XML_CmdMask + 22)</td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 168 of file <a href="/web-doxygen/docs/api/files/src/cmdmapper-h">cmdmapper.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a4e134ab9f24378509126a1359ea8df72">170</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a4e134ab9f24378509126a1359ea8df72">SIMPLESECT_BIT</a> = 0x1000,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a696b031073e74bf2cb98e5ef201d4aa3">172</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a21e038f5b8958e203d28bc4f18472352a696b031073e74bf2cb98e5ef201d4aa3">UNKNOWN</a>        = 0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273aa98e78abc5a518292bf17a61e90af51e">173</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273aa98e78abc5a518292bf17a61e90af51e">HTML_CENTER</a>    = 1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273af86f2e136782e591c3a3ecdd9713c5a8">174</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273af86f2e136782e591c3a3ecdd9713c5a8">HTML_TABLE</a>     = 2,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a2861ae6e47c6162fcdfbcbc3e8c23f7e">175</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a2861ae6e47c6162fcdfbcbc3e8c23f7e">HTML_CAPTION</a>   = 3,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a9f1d616da06520eb5ed69e011e353e70">176</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a9f1d616da06520eb5ed69e011e353e70">HTML_SMALL</a>     = 4,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a625085c514754f3aff0a372e2d544862">177</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a625085c514754f3aff0a372e2d544862">HTML_CODE</a>      = 5,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a03c65afaa75c587603bb62db4a3ab38a">178</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a03c65afaa75c587603bb62db4a3ab38a">HTML_IMG</a>       = 6,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273ad20ebedb0f176150f27c8cc20336d075">179</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273ad20ebedb0f176150f27c8cc20336d075">HTML_PRE</a>       = 7,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a43905d2b1313969ae2f210df9ef7c3bb">180</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a43905d2b1313969ae2f210df9ef7c3bb">HTML_SUB</a>       = 8,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a7e216fed22259530ae959dd65ffdb7b9">181</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a7e216fed22259530ae959dd65ffdb7b9">HTML_SUP</a>       = 9,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273ad7eb396091ab8336abda28f4d30aedaf">182</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273ad7eb396091ab8336abda28f4d30aedaf">HTML_TR</a>        = 10,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a998b3fd2c81e08ab48d7f331e1ceae6e">183</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a998b3fd2c81e08ab48d7f331e1ceae6e">HTML_TD</a>        = 11,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a66bf29113782294a2328eb64b5092b14">184</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a66bf29113782294a2328eb64b5092b14">HTML_TH</a>        = 12,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a3c11c68b002a63cea0de69e7454ea4fa">185</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a3c11c68b002a63cea0de69e7454ea4fa">HTML_OL</a>        = 13,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a40416867bee8eeef2c92f924bf7e92b0">186</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a40416867bee8eeef2c92f924bf7e92b0">HTML_UL</a>        = 14,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a16842ed17075ce583d7dbb041839b71c">187</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a16842ed17075ce583d7dbb041839b71c">HTML_LI</a>        = 15,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a980fa4689bd7bea32d8e46d8f07e84b0">188</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a980fa4689bd7bea32d8e46d8f07e84b0">HTML_EMPHASIS</a>  = 16,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a130d367d050aac12136ad7c4d4446031">189</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a130d367d050aac12136ad7c4d4446031">HTML_HR</a>        = 17,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273ad03672e5cae7c6e405d328ae14fef3f1">190</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273ad03672e5cae7c6e405d328ae14fef3f1">HTML_DL</a>        = 18,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a040d13605900029d0cb5e167cbf0960f">191</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a040d13605900029d0cb5e167cbf0960f">HTML_DT</a>        = 19,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273ae2f20861bc148186e631f6a6c4501da3">192</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273ae2f20861bc148186e631f6a6c4501da3">HTML_DD</a>        = 20,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a4f8fb36a7660142ed004cb82a93438d8">193</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a4f8fb36a7660142ed004cb82a93438d8">HTML_BR</a>        = 21,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273ad7f6725429a6b56d148761e9cb4e910a">194</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273ad7f6725429a6b56d148761e9cb4e910a">HTML_A</a>         = 22,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273ab4a6927c07490c4883842f1b74c10706">195</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273ab4a6927c07490c4883842f1b74c10706">HTML_BOLD</a>      = 23,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a8609691fd1c2d1ab5573087757e8176f">196</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a8609691fd1c2d1ab5573087757e8176f">HTML_P</a>         = 24,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a479296801803f02038ab03da7c2ad166">197</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a479296801803f02038ab03da7c2ad166">HTML_H1</a>        = 25,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a5d5d3cb1354c3eb5e716123d381e1cb6">198</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a5d5d3cb1354c3eb5e716123d381e1cb6">HTML_H2</a>        = 26,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273afc62db7b668b12b358f7a07fd1281b81">199</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273afc62db7b668b12b358f7a07fd1281b81">HTML_H3</a>        = 27,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a3a83d8472eedade5c9285898725b2ae4">200</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a3a83d8472eedade5c9285898725b2ae4">HTML_H4</a>        = 28,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a9ccc9adc294e5d51752440d870151645">201</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a9ccc9adc294e5d51752440d870151645">HTML_H5</a>        = 29,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a73dec4eca50d315e033ed391ed9f68c4">202</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a73dec4eca50d315e033ed391ed9f68c4">HTML_H6</a>        = 30,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a21f6ee40064060cfd1b5dbf822ac48b5">203</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a21f6ee40064060cfd1b5dbf822ac48b5">HTML_SPAN</a>      = 31,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273adf291d923a41e335a409b36d04b056c9">204</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273adf291d923a41e335a409b36d04b056c9">HTML_DIV</a>       = 32,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a32521974f3333518cf6a7591e14038f9">205</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a32521974f3333518cf6a7591e14038f9">HTML_BLOCKQUOTE</a>= 33,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a8a532f6aa0ff83feeb6611f7d1dd3b08">206</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a8a532f6aa0ff83feeb6611f7d1dd3b08">HTML_STRIKE</a>    = 34,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273ab06a28f3b1cebabd6fae9d7323acac91">207</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273ab06a28f3b1cebabd6fae9d7323acac91">HTML_UNDERLINE</a> = 35,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a2dac325066ce35bf3c2b36a7e7b80cb9">208</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a2dac325066ce35bf3c2b36a7e7b80cb9">HTML_INS</a>       = 36,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a3fe7e05e1718e8e6ba5d244e6b4674db">209</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a3fe7e05e1718e8e6ba5d244e6b4674db">HTML_DEL</a>       = 37,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a06c725d9e48f372affa01fdb8266c5f2">210</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a06c725d9e48f372affa01fdb8266c5f2">HTML_S</a>         = 38,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a40431fc3149887bf11da81c3251e8376">211</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a40431fc3149887bf11da81c3251e8376">HTML_DETAILS</a>   = 39,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273ac75d65616ed13b8354516ca1f4a3eabe">212</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273ac75d65616ed13b8354516ca1f4a3eabe">HTML_CITE</a>      = 40,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273af9e3cb3f2f4243b958e1b98226ec4f30">213</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273af9e3cb3f2f4243b958e1b98226ec4f30">HTML_THEAD</a>     = 41,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a20c25807fdf7ad539a764cf1d393464a">214</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a20c25807fdf7ad539a764cf1d393464a">HTML_TBODY</a>     = 42,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a14ef64361eae40bbe02179dc7e9bc4b4">215</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a14ef64361eae40bbe02179dc7e9bc4b4">HTML_TFOOT</a>     = 43,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a5a3f7649abce807b951b5f54bc169cea">216</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a5a3f7649abce807b951b5f54bc169cea">HTML_KBD</a>       = 44,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273ae69b5e3f7ee92734b47a599b364cb885">217</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273ae69b5e3f7ee92734b47a599b364cb885">HTML_TT</a>        = 45,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">219</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a>    = 0x100,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273af3ec0555269e1dbf8e1f318b7b889651">221</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273af3ec0555269e1dbf8e1f318b7b889651">XML_C</a>            = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a9b3d66fc2a3c4bf710c5076135665a62">222</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a9b3d66fc2a3c4bf710c5076135665a62">XML_CODE</a>         = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273aa9a60992392a19960f28501fe94fd399">223</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273aa9a60992392a19960f28501fe94fd399">XML_DESCRIPTION</a>  = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 2,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a54d238ef8877e0312e8c71ba34cc05b1">224</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a54d238ef8877e0312e8c71ba34cc05b1">XML_EXAMPLE</a>      = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 3,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a422227202d96b7b5aedcb1b4f3766d03">225</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a422227202d96b7b5aedcb1b4f3766d03">XML_EXCEPTION</a>    = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 4,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a42c366aae0ce10fbaf443dbe1c3fba7c">226</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a42c366aae0ce10fbaf443dbe1c3fba7c">XML_INCLUDE</a>      = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 5,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a198cc56071a53f9ad84bdb88a3e24867">227</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a198cc56071a53f9ad84bdb88a3e24867">XML_ITEM</a>         = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 6,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a40f0bcd06b9f44f4d797d244ea660b8b">228</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a40f0bcd06b9f44f4d797d244ea660b8b">XML_LIST</a>         = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 7,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a3e97a35f83d8653e00f2ee154d53cadc">229</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a3e97a35f83d8653e00f2ee154d53cadc">XML_LISTHEADER</a>   = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 8,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a1e4ef7a0fa3e0c2ec6cd9e22e51de7a5">230</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a1e4ef7a0fa3e0c2ec6cd9e22e51de7a5">XML_PARA</a>         = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 9,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273aad530a000140559dd09d6d3e2d0aa9f2">231</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273aad530a000140559dd09d6d3e2d0aa9f2">XML_PARAM</a>        = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 10,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a810cd6efd62a332a47c06489186b5538">232</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a810cd6efd62a332a47c06489186b5538">XML_PARAMREF</a>     = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 11,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273afffdcbbb92cd0218beb289ac9e5294b8">233</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273afffdcbbb92cd0218beb289ac9e5294b8">XML_PERMISSION</a>   = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 12,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a17061a81d4aad2bffa52eba69c30821e">234</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a17061a81d4aad2bffa52eba69c30821e">XML_REMARKS</a>      = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 13,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273aa1608f9ed465fcf53f739a0c083df8a1">235</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273aa1608f9ed465fcf53f739a0c083df8a1">XML_RETURNS</a>      = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 14,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273aa510df4e20d611f0e7ec3f9674f444b1">236</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273aa510df4e20d611f0e7ec3f9674f444b1">XML_SEE</a>          = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 15,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a33a1f2f937300bf6b0de85232ebd7f7d">237</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a33a1f2f937300bf6b0de85232ebd7f7d">XML_SEEALSO</a>      = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 16,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a44f6d7437443755970b6095ab80fee5d">238</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a44f6d7437443755970b6095ab80fee5d">XML_SUMMARY</a>      = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 17,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273abccb5b9dd2c20c78c3170dd7c1fa456b">239</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273abccb5b9dd2c20c78c3170dd7c1fa456b">XML_TERM</a>         = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 18,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a1056e17a54837e4e4c9897c32a9290fd">240</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a1056e17a54837e4e4c9897c32a9290fd">XML_TYPEPARAM</a>    = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 19,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a3a697097f6ad40042a7c521025d39446">241</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a3a697097f6ad40042a7c521025d39446">XML_TYPEPARAMREF</a> = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 20,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273a3a59f24296bc8eae02ed1a85f1e05c04">242</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273a3a59f24296bc8eae02ed1a85f1e05c04">XML_VALUE</a>        = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 21,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91be16b8342aa3130a4374d78cf42273afdede65d45b1dfdc8cad241a62d60ee5">243</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a91be16b8342aa3130a4374d78cf42273afdede65d45b1dfdc8cad241a62d60ee5">XML_INHERITDOC</a>   = <a href="#a91be16b8342aa3130a4374d78cf42273ad7e8a6d12710a52d791f797098540281">XML_CmdMask</a> + 22</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
