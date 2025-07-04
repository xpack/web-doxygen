---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/argumentlist
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ArgumentList` Class Reference

<p>This class represents an function or template argument list. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ArgumentList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/arguments-h">src/arguments.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9ef55d3a80837e98fd2143f87b15a66">Vec</a> = std::vector&lt; <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbcd1ba6301b5ee9e9a44c756f7584d0">iterator</a> = typename Vec::iterator</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b618acc2d69252daffc0923c889a061">const_iterator</a> = typename Vec::const_iterator</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3d2726240dff68120149845452e1d1ec">hasDocumentation</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab8454af348e4028ae2f003ef1f082369">hasTemplateDocumentation</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af63051a24ce92667516c4f9a80e08619">reset</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abbcd1ba6301b5ee9e9a44c756f7584d0">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc52d012d093df1adede055164f69dc9">begin</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#abbcd1ba6301b5ee9e9a44c756f7584d0">iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a215181845c0d9f0525806a4165c4f552">end</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5b618acc2d69252daffc0923c889a061">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9b04e3aa2b824b84d3242043c7128fe">begin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5b618acc2d69252daffc0923c889a061">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a18c70e7e30584e7f94635d578c8f767e">end</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5b618acc2d69252daffc0923c889a061">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46a3bc9367f1790feba9500d7c60493a">cbegin</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a5b618acc2d69252daffc0923c889a061">const_iterator</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43bbf946be0bd313a11ccb8f06a88f62">cend</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d651caeb995400fad17d4ab4a020a3a">size</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaea73e4e41b4659443b1b5cdd525dd1f">clear</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa80c14f74871d9274671a9e33ac3c870">push_back</a> (const Argument &amp;a)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a016f5a9b5431ebac34a2697258a1c085">back</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a3cefc0a494e7375c9f072b5728b06f">back</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c86608e0790d8d86314bf4bc24936c2">front</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae85e611936b54f49f6a173c486391c35">front</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc1e900dbe37733434eef1d805ee61ba">at</a> (size_t i)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c47f644dbc3f4fb61e018889a744f81">at</a> (size_t i) const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72440ac7985da3c0c465134bc0ddd2d5">constSpecifier</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad03f25174e81a42a617a15195a8867b0">volatileSpecifier</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20632203b62a0d845730849def34561f">pureSpecifier</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4cb7b4a29cb7e4564014d024f8de9bc5">trailingReturnType</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a483b5375dcb5f02a27c8d5808ab7a7e9">isDeleted</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884">RefQualifierType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10a0f5f25aa7f3c97ac071169c85e4ac">refQualifier</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a17fe630d07d1579382657bde568ee0db">noParameters</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa8cb70709cb79c37f5c9ffdf6ea82d9">setConstSpecifier</a> (bool b)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af15b01fcff4f0be4ed8c40200752c8f3">setVolatileSpecifier</a> (bool b)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4dc90f086eb52e42816d5f2f813ed358">setPureSpecifier</a> (bool b)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a4aee2018dc2a3ca82bd152966949b1">setTrailingReturnType</a> (const QCString &amp;s)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6d26192d62941751a6c0d53163fee4f">setIsDeleted</a> (bool b)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaae8c33d0b5b20d86407af80d4e1c713">setRefQualifier</a> (RefQualifierType t)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add72bfdcd9da1cf65f419c062a16ce6d">setNoParameters</a> (bool b)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a348da6c9775a091fb9ec0468bc154457">m_constSpecifier</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a2f26fdab07c5bf8ac52651fb8e1229">m_volatileSpecifier</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c9feef4874f6313782f791bcf202a13">m_pureSpecifier</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10e8b361749f3d20d000e80955238c2e">m_trailingReturnType</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0deabbcbae6887ffce741eb58f319b16">m_isDeleted</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884">RefQualifierType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e9c07bc193ee177d91a806d3db3aae2">m_refQualifier</a> = <a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884a6adf97f83acf6453d4a6a4b1070f3754">RefQualifierType::None</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a851fc0cb705a74527270303f54e59667">m_noParameters</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
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

<p>This class represents an function or template argument list.</p>


<p>This class also stores some information about member that is typically put after the argument list, such as whether the member is const, volatile or pure virtual.</p>


<p>Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### const\_iterator {#a5b618acc2d69252daffc0923c889a061}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ArgumentList::const_iterator =  typename Vec::const_iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b618acc2d69252daffc0923c889a061">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a5b618acc2d69252daffc0923c889a061">const_iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::const_iterator;</span></span></div>

</div>

</div>
</div>

### iterator {#abbcd1ba6301b5ee9e9a44c756f7584d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ArgumentList::iterator =  typename Vec::iterator</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abbcd1ba6301b5ee9e9a44c756f7584d0">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#abbcd1ba6301b5ee9e9a44c756f7584d0">iterator</a> = </span><span class="doxyHighlightKeyword">typename</span><span class="doxyHighlight"> Vec::iterator;</span></span></div>

</div>

</div>
</div>

### Vec {#aa9ef55d3a80837e98fd2143f87b15a66}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ArgumentList::Vec =  std::vector&lt;Argument&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa9ef55d3a80837e98fd2143f87b15a66">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#aa9ef55d3a80837e98fd2143f87b15a66">Vec</a> = std::vector&lt;Argument&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### at() {#acc1e900dbe37733434eef1d805ee61ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Argument &amp; ArgumentList::at (size_t i)</td>
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



<p>Definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc1e900dbe37733434eef1d805ee61ba">107</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;<a href="#acc1e900dbe37733434eef1d805ee61ba">at</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i)                { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.at(i); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a>.</p>

</div>
</div>

### at() {#a3c47f644dbc3f4fb61e018889a744f81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Argument &amp; ArgumentList::at (size_t i)</td>
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



<p>Definition at line 108 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c47f644dbc3f4fb61e018889a744f81">108</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;<a href="#a3c47f644dbc3f4fb61e018889a744f81">at</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i)</span><span class="doxyHighlightKeyword"> const    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.at(i); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>

</div>
</div>

### back() {#a016f5a9b5431ebac34a2697258a1c085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Argument &amp; ArgumentList::back ()</td>
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



<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a016f5a9b5431ebac34a2697258a1c085">103</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;<a href="#a016f5a9b5431ebac34a2697258a1c085">back</a>()                      { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.back(); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>

</div>
</div>

### back() {#a4a3cefc0a494e7375c9f072b5728b06f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Argument &amp; ArgumentList::back ()</td>
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



<p>Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a3cefc0a494e7375c9f072b5728b06f">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;<a href="#a4a3cefc0a494e7375c9f072b5728b06f">back</a>()</span><span class="doxyHighlightKeyword"> const          </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.back(); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>

</div>
</div>

### begin() {#acc52d012d093df1adede055164f69dc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator ArgumentList::begin ()</td>
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



<p>Definition at line 93 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc52d012d093df1adede055164f69dc9">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#abbcd1ba6301b5ee9e9a44c756f7584d0">iterator</a> <a href="#acc52d012d093df1adede055164f69dc9">begin</a>()                      { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.begin(); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a8a682f90e07bb6a55566b5941239d23a">MemberDefImpl::_writeTemplatePrefix</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ada5b9e6fb75b1e07ba0602b2b40229db">MemberDefImpl::copyArgumentNames</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac0e3122b4e6e26ee38ef45f59aaecf05">MemberDefImpl::detectUndocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a3d2726240dff68120149845452e1d1ec">hasDocumentation</a>, <a href="#ab8454af348e4028ae2f003ef1f082369">hasTemplateDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a294b2f8587b6f511bac156c5e945ff34">matchTemplateArguments</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acbd23ce837bcb562fbf5909c28e3ee06">MemberDefImpl::resolveUnnamedParameters</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6da766398ce7fc4fd2aa252bc2f695b6">substituteTemplatesInString</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.</p>

</div>
</div>

### begin() {#ad9b04e3aa2b824b84d3242043c7128fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator ArgumentList::begin ()</td>
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



<p>Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad9b04e3aa2b824b84d3242043c7128fe">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5b618acc2d69252daffc0923c889a061">const_iterator</a> <a href="#ad9b04e3aa2b824b84d3242043c7128fe">begin</a>()</span><span class="doxyHighlightKeyword"> const          </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.cbegin(); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>

</div>
</div>

### cbegin() {#a46a3bc9367f1790feba9500d7c60493a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator ArgumentList::cbegin ()</td>
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



<p>Definition at line 97 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a46a3bc9367f1790feba9500d7c60493a">97</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5b618acc2d69252daffc0923c889a061">const_iterator</a> <a href="#a46a3bc9367f1790feba9500d7c60493a">cbegin</a>()</span><span class="doxyHighlightKeyword"> const         </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.cbegin(); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>

</div>
</div>

### cend() {#a43bbf946be0bd313a11ccb8f06a88f62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator ArgumentList::cend ()</td>
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



<p>Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a43bbf946be0bd313a11ccb8f06a88f62">98</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5b618acc2d69252daffc0923c889a061">const_iterator</a> <a href="#a43bbf946be0bd313a11ccb8f06a88f62">cend</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.cend();   }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>

</div>
</div>

### clear() {#aaea73e4e41b4659443b1b5cdd525dd1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgumentList::clear ()</td>
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



<p>Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaea73e4e41b4659443b1b5cdd525dd1f">101</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaea73e4e41b4659443b1b5cdd525dd1f">clear</a>()                          { <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.clear(); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>


<p>Referenced by <a href="#af63051a24ce92667516c4f9a80e08619">reset</a>.</p>

</div>
</div>

### constSpecifier() {#a72440ac7985da3c0c465134bc0ddd2d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::constSpecifier ()</td>
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



<p>Definition at line 111 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72440ac7985da3c0c465134bc0ddd2d5">111</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a72440ac7985da3c0c465134bc0ddd2d5">constSpecifier</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a348da6c9775a091fb9ec0468bc154457">m_constSpecifier</a>; }</span></span></div>

</div>


<p>Reference <a href="#a348da6c9775a091fb9ec0468bc154457">m_constSpecifier</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.</p>

</div>
</div>

### empty() {#aaa15ddcfdb06a535a3398f1dc73d336d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::empty ()</td>
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



<p>Definition at line 99 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa15ddcfdb06a535a3398f1dc73d336d">99</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a>()</span><span class="doxyHighlightKeyword"> const                    </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.empty(); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac0e3122b4e6e26ee38ef45f59aaecf05">MemberDefImpl::detectUndocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aa2b4c58062de6e3075936abc6c29dd7e">getTemplateArgumentsFromName</a>, <a href="#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1dc6b9f0a9cc58498da6f8d4ffe120c1">insertTemplateSpecifierInScope</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a0327bf0462f4c2efcdc2103a587e560e">makeQualifiedNameWithTemplateParameters</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ab40d758b9f5159a2d26d0b59efe7e36d">searchTemplateSpecs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5f86911d03ddead5c20dc99ef4828d17">tempArgListToString</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>.</p>

</div>
</div>

### end() {#a215181845c0d9f0525806a4165c4f552}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">iterator ArgumentList::end ()</td>
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



<p>Definition at line 94 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a215181845c0d9f0525806a4165c4f552">94</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#abbcd1ba6301b5ee9e9a44c756f7584d0">iterator</a> <a href="#a215181845c0d9f0525806a4165c4f552">end</a>()                        { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.end();   }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a8a682f90e07bb6a55566b5941239d23a">MemberDefImpl::_writeTemplatePrefix</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ada5b9e6fb75b1e07ba0602b2b40229db">MemberDefImpl::copyArgumentNames</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac0e3122b4e6e26ee38ef45f59aaecf05">MemberDefImpl::detectUndocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="#a3d2726240dff68120149845452e1d1ec">hasDocumentation</a>, <a href="#ab8454af348e4028ae2f003ef1f082369">hasTemplateDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a294b2f8587b6f511bac156c5e945ff34">matchTemplateArguments</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acbd23ce837bcb562fbf5909c28e3ee06">MemberDefImpl::resolveUnnamedParameters</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6da766398ce7fc4fd2aa252bc2f695b6">substituteTemplatesInString</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a916ded3150c496785b98bbd5c2bee442">transferArgumentDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.</p>

</div>
</div>

### end() {#a18c70e7e30584e7f94635d578c8f767e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const_iterator ArgumentList::end ()</td>
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



<p>Definition at line 96 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a18c70e7e30584e7f94635d578c8f767e">96</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5b618acc2d69252daffc0923c889a061">const_iterator</a> <a href="#a18c70e7e30584e7f94635d578c8f767e">end</a>()</span><span class="doxyHighlightKeyword"> const            </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.cend();   }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>

</div>
</div>

### front() {#a3c86608e0790d8d86314bf4bc24936c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Argument &amp; ArgumentList::front ()</td>
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



<p>Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c86608e0790d8d86314bf4bc24936c2">105</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;<a href="#a3c86608e0790d8d86314bf4bc24936c2">front</a>()                     { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.front(); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>.</p>

</div>
</div>

### front() {#ae85e611936b54f49f6a173c486391c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Argument &amp; ArgumentList::front ()</td>
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



<p>Definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae85e611936b54f49f6a173c486391c35">106</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;<a href="#ae85e611936b54f49f6a173c486391c35">front</a>()</span><span class="doxyHighlightKeyword"> const         </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.front(); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>

</div>
</div>

### hasDocumentation() {#a3d2726240dff68120149845452e1d1ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::hasDocumentation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Does any argument of this list have documentation?</p>


<p>the argument list is documented if one of its arguments is documented</p>


<p>Declaration at line 72 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>, definition at line 21 of file <a href="/web-doxygen/docs/api/files/src/arguments-cpp">arguments.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3d2726240dff68120149845452e1d1ec">21</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3d2726240dff68120149845452e1d1ec">ArgumentList::hasDocumentation</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">22</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">23</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::any_of(<a href="#acc52d012d093df1adede055164f69dc9">begin</a>(),<a href="#a215181845c0d9f0525806a4165c4f552">end</a>(),[](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a){ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> a.<a href="/web-doxygen/docs/api/structs/argument/#aca66c2b989361c43f7e1adfe9d7f125d">hasDocumentation</a>(); });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">24</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#acc52d012d093df1adede055164f69dc9">begin</a>, <a href="#a215181845c0d9f0525806a4165c4f552">end</a> and <a href="/web-doxygen/docs/api/structs/argument/#aca66c2b989361c43f7e1adfe9d7f125d">Argument::hasDocumentation</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae53504faf9e304d72ec1f2e38f3c9013">inlineArgListToDoc</a>.</p>

</div>
</div>

### hasParameters() {#a2ed5c45b3909206446aaac4f1ab6d640}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::hasParameters ()</td>
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




<p>Does this list have zero or more parameters</p>


<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ed5c45b3909206446aaac4f1ab6d640">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a>() || <a href="#a851fc0cb705a74527270303f54e59667">m_noParameters</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a> and <a href="#a851fc0cb705a74527270303f54e59667">m_noParameters</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#a0e2b9604ce397bbe6984cf81775f4fda">addTemplateArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac0e3122b4e6e26ee38ef45f59aaecf05">MemberDefImpl::detectUndocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a31b60db653850e1be9084b27153e6758">VhdlDocGen::writeProcessProto</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#ade547304a708b89e5a5f55f7fb9db151">writeTemplateArgumentList</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.</p>

</div>
</div>

### hasTemplateDocumentation() {#ab8454af348e4028ae2f003ef1f082369}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::hasTemplateDocumentation ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Does any template argument of this list have documentation?</p>


<p>the template argument list is documented if one of its template arguments is documented</p>


<p>Declaration at line 74 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>, definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/arguments-cpp">arguments.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab8454af348e4028ae2f003ef1f082369">29</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ab8454af348e4028ae2f003ef1f082369">ArgumentList::hasTemplateDocumentation</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::any_of(<a href="#acc52d012d093df1adede055164f69dc9">begin</a>(),<a href="#a215181845c0d9f0525806a4165c4f552">end</a>(),[](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a){ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> a.<a href="/web-doxygen/docs/api/structs/argument/#ae3866d29516dff9ac0eb3a40b09db5a8">hasTemplateDocumentation</a>(); });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#acc52d012d093df1adede055164f69dc9">begin</a>, <a href="#a215181845c0d9f0525806a4165c4f552">end</a> and <a href="/web-doxygen/docs/api/structs/argument/#ae3866d29516dff9ac0eb3a40b09db5a8">Argument::hasTemplateDocumentation</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7cb019e5059fa4aa866434f8c310c210">inlineTemplateArgListToDoc</a>.</p>

</div>
</div>

### isDeleted() {#a483b5375dcb5f02a27c8d5808ab7a7e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::isDeleted ()</td>
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



<p>Definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a483b5375dcb5f02a27c8d5808ab7a7e9">115</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a483b5375dcb5f02a27c8d5808ab7a7e9">isDeleted</a>()</span><span class="doxyHighlightKeyword"> const                </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0deabbcbae6887ffce741eb58f319b16">m_isDeleted</a>; }</span></span></div>

</div>


<p>Reference <a href="#a0deabbcbae6887ffce741eb58f319b16">m_isDeleted</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>.</p>

</div>
</div>

### noParameters() {#a17fe630d07d1579382657bde568ee0db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::noParameters ()</td>
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



<p>Definition at line 117 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a17fe630d07d1579382657bde568ee0db">117</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a17fe630d07d1579382657bde568ee0db">noParameters</a>()</span><span class="doxyHighlightKeyword"> const             </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a851fc0cb705a74527270303f54e59667">m_noParameters</a>; }</span></span></div>

</div>


<p>Reference <a href="#a851fc0cb705a74527270303f54e59667">m_noParameters</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>.</p>

</div>
</div>

### pureSpecifier() {#a20632203b62a0d845730849def34561f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::pureSpecifier ()</td>
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



<p>Definition at line 113 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a20632203b62a0d845730849def34561f">113</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a20632203b62a0d845730849def34561f">pureSpecifier</a>()</span><span class="doxyHighlightKeyword"> const            </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a9c9feef4874f6313782f791bcf202a13">m_pureSpecifier</a>; }</span></span></div>

</div>


<p>Reference <a href="#a9c9feef4874f6313782f791bcf202a13">m_pureSpecifier</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>.</p>

</div>
</div>

### push\_back() {#aa80c14f74871d9274671a9e33ac3c870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgumentList::push_back (const <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp; a)</td>
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



<p>Definition at line 102 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa80c14f74871d9274671a9e33ac3c870">102</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa80c14f74871d9274671a9e33ac3c870">push_back</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a)     { <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.push_back(a); }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/stlsupport-cpp/#a7137defdca68d716cface04a9b9aa37e">addSTLClass</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#aa9daed7f8f5651e85aaa17885e61134c">anonymous_namespace{tagreader.cpp}::TagFileParser::buildClassEntry</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>.</p>

</div>
</div>

### refQualifier() {#a10a0f5f25aa7f3c97ac071169c85e4ac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefQualifierType ArgumentList::refQualifier ()</td>
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



<p>Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a10a0f5f25aa7f3c97ac071169c85e4ac">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884">RefQualifierType</a> <a href="#a10a0f5f25aa7f3c97ac071169c85e4ac">refQualifier</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a5e9c07bc193ee177d91a806d3db3aae2">m_refQualifier</a>; }</span></span></div>

</div>


<p>Reference <a href="#a5e9c07bc193ee177d91a806d3db3aae2">m_refQualifier</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.</p>

</div>
</div>

### reset() {#af63051a24ce92667516c4f9a80e08619}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgumentList::reset ()</td>
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



<p>Definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af63051a24ce92667516c4f9a80e08619">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af63051a24ce92667516c4f9a80e08619">reset</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aaea73e4e41b4659443b1b5cdd525dd1f">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a348da6c9775a091fb9ec0468bc154457">m_constSpecifier</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a8a2f26fdab07c5bf8ac52651fb8e1229">m_volatileSpecifier</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9c9feef4874f6313782f791bcf202a13">m_pureSpecifier</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a10e8b361749f3d20d000e80955238c2e">m_trailingReturnType</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a0deabbcbae6887ffce741eb58f319b16">m_isDeleted</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a5e9c07bc193ee177d91a806d3db3aae2">m_refQualifier</a> = <a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884a6adf97f83acf6453d4a6a4b1070f3754">RefQualifierType::None</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a851fc0cb705a74527270303f54e59667">m_noParameters</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aaea73e4e41b4659443b1b5cdd525dd1f">clear</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a348da6c9775a091fb9ec0468bc154457">m_constSpecifier</a>, <a href="#a0deabbcbae6887ffce741eb58f319b16">m_isDeleted</a>, <a href="#a851fc0cb705a74527270303f54e59667">m_noParameters</a>, <a href="#a9c9feef4874f6313782f791bcf202a13">m_pureSpecifier</a>, <a href="#a5e9c07bc193ee177d91a806d3db3aae2">m_refQualifier</a>, <a href="#a10e8b361749f3d20d000e80955238c2e">m_trailingReturnType</a>, <a href="#a8a2f26fdab07c5bf8ac52651fb8e1229">m_volatileSpecifier</a> and <a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884a6adf97f83acf6453d4a6a4b1070f3754">None</a>.</p>

</div>
</div>

### setConstSpecifier() {#aaa8cb70709cb79c37f5c9ffdf6ea82d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgumentList::setConstSpecifier (bool b)</td>
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



<p>Definition at line 119 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa8cb70709cb79c37f5c9ffdf6ea82d9">119</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaa8cb70709cb79c37f5c9ffdf6ea82d9">setConstSpecifier</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)        { <a href="#a348da6c9775a091fb9ec0468bc154457">m_constSpecifier</a> = b; }</span></span></div>

</div>


<p>Reference <a href="#a348da6c9775a091fb9ec0468bc154457">m_constSpecifier</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>.</p>

</div>
</div>

### setIsDeleted() {#ab6d26192d62941751a6c0d53163fee4f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgumentList::setIsDeleted (bool b)</td>
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



<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6d26192d62941751a6c0d53163fee4f">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab6d26192d62941751a6c0d53163fee4f">setIsDeleted</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)             { <a href="#a0deabbcbae6887ffce741eb58f319b16">m_isDeleted</a> = b; }</span></span></div>

</div>


<p>Reference <a href="#a0deabbcbae6887ffce741eb58f319b16">m_isDeleted</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>.</p>

</div>
</div>

### setNoParameters() {#add72bfdcd9da1cf65f419c062a16ce6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgumentList::setNoParameters (bool b)</td>
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



<p>Definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add72bfdcd9da1cf65f419c062a16ce6d">125</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#add72bfdcd9da1cf65f419c062a16ce6d">setNoParameters</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)          { <a href="#a851fc0cb705a74527270303f54e59667">m_noParameters</a> = b; }</span></span></div>

</div>


<p>Reference <a href="#a851fc0cb705a74527270303f54e59667">m_noParameters</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>.</p>

</div>
</div>

### setPureSpecifier() {#a4dc90f086eb52e42816d5f2f813ed358}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgumentList::setPureSpecifier (bool b)</td>
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



<p>Definition at line 121 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4dc90f086eb52e42816d5f2f813ed358">121</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4dc90f086eb52e42816d5f2f813ed358">setPureSpecifier</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)         { <a href="#a9c9feef4874f6313782f791bcf202a13">m_pureSpecifier</a> = b; }</span></span></div>

</div>


<p>Reference <a href="#a9c9feef4874f6313782f791bcf202a13">m_pureSpecifier</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>.</p>

</div>
</div>

### setRefQualifier() {#aaae8c33d0b5b20d86407af80d4e1c713}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgumentList::setRefQualifier (<a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884">RefQualifierType</a> t)</td>
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



<p>Definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaae8c33d0b5b20d86407af80d4e1c713">124</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaae8c33d0b5b20d86407af80d4e1c713">setRefQualifier</a>(<a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884">RefQualifierType</a> t) { <a href="#a5e9c07bc193ee177d91a806d3db3aae2">m_refQualifier</a> = t; }</span></span></div>

</div>


<p>Reference <a href="#a5e9c07bc193ee177d91a806d3db3aae2">m_refQualifier</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>.</p>

</div>
</div>

### setTrailingReturnType() {#a2a4aee2018dc2a3ca82bd152966949b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgumentList::setTrailingReturnType (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a4aee2018dc2a3ca82bd152966949b1">122</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2a4aee2018dc2a3ca82bd152966949b1">setTrailingReturnType</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s) { <a href="#a10e8b361749f3d20d000e80955238c2e">m_trailingReturnType</a> = s; }</span></span></div>

</div>


<p>Reference <a href="#a10e8b361749f3d20d000e80955238c2e">m_trailingReturnType</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>.</p>

</div>
</div>

### setVolatileSpecifier() {#af15b01fcff4f0be4ed8c40200752c8f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ArgumentList::setVolatileSpecifier (bool b)</td>
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



<p>Definition at line 120 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af15b01fcff4f0be4ed8c40200752c8f3">120</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af15b01fcff4f0be4ed8c40200752c8f3">setVolatileSpecifier</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)     { <a href="#a8a2f26fdab07c5bf8ac52651fb8e1229">m_volatileSpecifier</a> = b; }</span></span></div>

</div>


<p>Reference <a href="#a8a2f26fdab07c5bf8ac52651fb8e1229">m_volatileSpecifier</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>.</p>

</div>
</div>

### size() {#a4d651caeb995400fad17d4ab4a020a3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t ArgumentList::size ()</td>
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



<p>Definition at line 100 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4d651caeb995400fad17d4ab4a020a3a">100</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a4d651caeb995400fad17d4ab4a020a3a">size</a>()</span><span class="doxyHighlightKeyword"> const                   </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.size();  }</span></span></div>

</div>


<p>Reference <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a33fa889d7e70cd1c2cab56a16790d9b5">FlowChart::alignFuncProc</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a294b2f8587b6f511bac156c5e945ff34">matchTemplateArguments</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a>.</p>

</div>
</div>

### trailingReturnType() {#a4cb7b4a29cb7e4564014d024f8de9bc5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ArgumentList::trailingReturnType ()</td>
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



<p>Definition at line 114 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4cb7b4a29cb7e4564014d024f8de9bc5">114</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4cb7b4a29cb7e4564014d024f8de9bc5">trailingReturnType</a>()</span><span class="doxyHighlightKeyword"> const   </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a10e8b361749f3d20d000e80955238c2e">m_trailingReturnType</a>; }</span></span></div>

</div>


<p>Reference <a href="#a10e8b361749f3d20d000e80955238c2e">m_trailingReturnType</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a31cfb988a49ee5b4f6e0f64dded34507">MemberDefImpl::warnIfUndocumentedParams</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.</p>

</div>
</div>

### volatileSpecifier() {#ad03f25174e81a42a617a15195a8867b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::volatileSpecifier ()</td>
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



<p>Definition at line 112 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad03f25174e81a42a617a15195a8867b0">112</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad03f25174e81a42a617a15195a8867b0">volatileSpecifier</a>()</span><span class="doxyHighlightKeyword"> const        </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8a2f26fdab07c5bf8ac52651fb8e1229">m_volatileSpecifier</a>; }</span></span></div>

</div>


<p>Reference <a href="#a8a2f26fdab07c5bf8ac52651fb8e1229">m_volatileSpecifier</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9d5c2a3aefbda0b0e684f768a380d2db">argListToString</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f7d02622777ba912fcf5896be16c013">substituteTemplatesInArgList</a> and <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_args {#a49823c3de63572710ede8d6a3070ee9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Argument&gt; ArgumentList::m_args</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 128 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49823c3de63572710ede8d6a3070ee9a">128</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;Argument&gt; <a href="#a49823c3de63572710ede8d6a3070ee9a">m_args</a>;</span></span></div>

</div>


<p>Referenced by <a href="#acc1e900dbe37733434eef1d805ee61ba">at</a>, <a href="#a3c47f644dbc3f4fb61e018889a744f81">at</a>, <a href="#a016f5a9b5431ebac34a2697258a1c085">back</a>, <a href="#a4a3cefc0a494e7375c9f072b5728b06f">back</a>, <a href="#acc52d012d093df1adede055164f69dc9">begin</a>, <a href="#ad9b04e3aa2b824b84d3242043c7128fe">begin</a>, <a href="#a46a3bc9367f1790feba9500d7c60493a">cbegin</a>, <a href="#a43bbf946be0bd313a11ccb8f06a88f62">cend</a>, <a href="#aaea73e4e41b4659443b1b5cdd525dd1f">clear</a>, <a href="#aaa15ddcfdb06a535a3398f1dc73d336d">empty</a>, <a href="#a215181845c0d9f0525806a4165c4f552">end</a>, <a href="#a18c70e7e30584e7f94635d578c8f767e">end</a>, <a href="#a3c86608e0790d8d86314bf4bc24936c2">front</a>, <a href="#ae85e611936b54f49f6a173c486391c35">front</a>, <a href="#aa80c14f74871d9274671a9e33ac3c870">push_back</a> and <a href="#a4d651caeb995400fad17d4ab4a020a3a">size</a>.</p>

</div>
</div>

### m\_constSpecifier {#a348da6c9775a091fb9ec0468bc154457}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::m_constSpecifier = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Does the member modify the state of the class?</p>


<p>Definition at line 130 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a348da6c9775a091fb9ec0468bc154457">130</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a348da6c9775a091fb9ec0468bc154457">m_constSpecifier</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a72440ac7985da3c0c465134bc0ddd2d5">constSpecifier</a>, <a href="#af63051a24ce92667516c4f9a80e08619">reset</a> and <a href="#aaa8cb70709cb79c37f5c9ffdf6ea82d9">setConstSpecifier</a>.</p>

</div>
</div>

### m\_isDeleted {#a0deabbcbae6887ffce741eb58f319b16}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::m_isDeleted = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>method with =delete</p>


<p>Definition at line 138 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0deabbcbae6887ffce741eb58f319b16">138</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0deabbcbae6887ffce741eb58f319b16">m_isDeleted</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a483b5375dcb5f02a27c8d5808ab7a7e9">isDeleted</a>, <a href="#af63051a24ce92667516c4f9a80e08619">reset</a> and <a href="#ab6d26192d62941751a6c0d53163fee4f">setIsDeleted</a>.</p>

</div>
</div>

### m\_noParameters {#a851fc0cb705a74527270303f54e59667}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::m_noParameters = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>is it an explicit empty list</p>


<p>Definition at line 142 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a851fc0cb705a74527270303f54e59667">142</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a851fc0cb705a74527270303f54e59667">m_noParameters</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a>, <a href="#a17fe630d07d1579382657bde568ee0db">noParameters</a>, <a href="#af63051a24ce92667516c4f9a80e08619">reset</a> and <a href="#add72bfdcd9da1cf65f419c062a16ce6d">setNoParameters</a>.</p>

</div>
</div>

### m\_pureSpecifier {#a9c9feef4874f6313782f791bcf202a13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::m_pureSpecifier = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Is this a pure virtual member?</p>


<p>Definition at line 134 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c9feef4874f6313782f791bcf202a13">134</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9c9feef4874f6313782f791bcf202a13">m_pureSpecifier</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a20632203b62a0d845730849def34561f">pureSpecifier</a>, <a href="#af63051a24ce92667516c4f9a80e08619">reset</a> and <a href="#a4dc90f086eb52e42816d5f2f813ed358">setPureSpecifier</a>.</p>

</div>
</div>

### m\_refQualifier {#a5e9c07bc193ee177d91a806d3db3aae2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">RefQualifierType ArgumentList::m_refQualifier = <a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884a6adf97f83acf6453d4a6a4b1070f3754">RefQualifierType::None</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>C++11 ref qualifier</p>


<p>Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e9c07bc193ee177d91a806d3db3aae2">140</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884">RefQualifierType</a> <a href="#a5e9c07bc193ee177d91a806d3db3aae2">m_refQualifier</a> = <a href="/web-doxygen/docs/api/files/src/arguments-h/#a4f78d801ad01da94c75f928280228884a6adf97f83acf6453d4a6a4b1070f3754">RefQualifierType::None</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a10a0f5f25aa7f3c97ac071169c85e4ac">refQualifier</a>, <a href="#af63051a24ce92667516c4f9a80e08619">reset</a> and <a href="#aaae8c33d0b5b20d86407af80d4e1c713">setRefQualifier</a>.</p>

</div>
</div>

### m\_trailingReturnType {#a10e8b361749f3d20d000e80955238c2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ArgumentList::m_trailingReturnType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>C++11 style Trailing return type?</p>


<p>Definition at line 136 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a10e8b361749f3d20d000e80955238c2e">136</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a10e8b361749f3d20d000e80955238c2e">m_trailingReturnType</a>;</span></span></div>

</div>


<p>Referenced by <a href="#af63051a24ce92667516c4f9a80e08619">reset</a>, <a href="#a2a4aee2018dc2a3ca82bd152966949b1">setTrailingReturnType</a> and <a href="#a4cb7b4a29cb7e4564014d024f8de9bc5">trailingReturnType</a>.</p>

</div>
</div>

### m\_volatileSpecifier {#a8a2f26fdab07c5bf8ac52651fb8e1229}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ArgumentList::m_volatileSpecifier = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Is the member volatile?</p>


<p>Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8a2f26fdab07c5bf8ac52651fb8e1229">132</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8a2f26fdab07c5bf8ac52651fb8e1229">m_volatileSpecifier</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>

</div>


<p>Referenced by <a href="#af63051a24ce92667516c4f9a80e08619">reset</a>, <a href="#af15b01fcff4f0be4ed8c40200752c8f3">setVolatileSpecifier</a> and <a href="#ad03f25174e81a42a617a15195a8867b0">volatileSpecifier</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/arguments-cpp">arguments.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
