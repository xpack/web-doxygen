---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/outputlist
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `OutputList` Class Reference

Class representing a list of output generators that are written to in parallel. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class OutputList { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/outputlist-h">src/outputlist.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab96ab5436b6d039364d65aa7b05b37d3">OutputGenIntfPtr</a> = std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/outputgenintf">OutputGenIntf</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af39f7d4abc52b7b869bfb783fcac7315">OutputList</a> (const OutputList &amp;ol)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3abb58f0059d4992f261fc45ed4d8af2">OutputList</a> (OutputList &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad42a92df914a5cc6ebb1889760c17660">~OutputList</a> ()=default</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d5653dcc37e333f00ce357d2440fe6e">operator=</a> (const OutputList &amp;ol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add10a6827dd128c3222952ce2b74a233">operator=</a> (OutputList &amp;&amp;)=delete</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class DocGenerator&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2ffd4b500e651b8ec1a47acb46e2456c">add</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a284458e4baf27869eb5bbb9776407e6c">codeGenerators</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4700ac2ba9ae6445eb7f862502472f35">codeGenerators</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38c3477fea42348693927abc9b16d209">size</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad32603ff4c4ba4d39e0bad7ede5924bf">enableAll</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a75284d21a037302ea3d7dc6e1558d4">disableAll</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a192e28bf96098f41db170be0680d5375">disable</a> (OutputType o)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a306f5cfd7c296b5a52160343d9631916">enable</a> (OutputType o)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a046bd3dcc4d8e2cc12821fba1394d818">isEnabled</a> (OutputType o)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91f9afddff1974d7805c3d022b754ddf">disableAllBut</a> (OutputType o)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a885957a64f7d87aefb663c4ec903188f">pushGeneratorState</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94eb1af2ea07425ef1faa539d24adcf8">popGeneratorState</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac371cebadb37ea8ab3ae59502036c427">generateDoc</a> (const QCString &amp;fileName, int startLine, const Definition *ctx, const MemberDef *md, const QCString &amp;docStr, bool indexWords, bool isExample, const QCString &amp;exampleName, bool singleLine, bool linkFromIndex, bool markdownSupport=Config_getBool(MARKDOWN_SUPPORT), bool autolinkSupport=Config_getBool(AUTOLINK_SUPPORT))</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a518814a98f44c11f73dbea3b7b3ed795">startFile</a> (const QCString &amp;name, const QCString &amp;manName, const QCString &amp;title, int hierarchyLevel=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfdcf2ba925f05be8beb8cf43deb168a">parseText</a> (const QCString &amp;textStr)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a475da5dda736fa915aca9fc855b1d2e7">writeDoc</a> (const IDocNodeAST *ast, const Definition *ctx, const MemberDef *md)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae92e8fd973796141115ea4ef0b15cf5b">startIndexSection</a> (IndexSection is)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59226412e1c0b732f16dfbf601c2c388">endIndexSection</a> (IndexSection is)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1ce4ae7803aba4c58764c906e943aab">writePageLink</a> (const QCString &amp;name, bool first)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e35c28c310e74b57645aff8119c1546">startProjectNumber</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6faf5debd750bf3fb143ffc571a0d22">endProjectNumber</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85fc0afe789c21758373df15bcb81cc9">writeStyleInfo</a> (int part)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b776a7ac371d841b15862b074ddd97f">writeSearchInfo</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accf02a25e4bb1593eabc248373f08dd0">writeFooter</a> (const QCString &amp;navPath)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b0f833d3150110151ae6a095a8549a5">endFile</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a218206d83bfa847f783bf2d2346caac6">startTitleHead</a> (const QCString &amp;fileName)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d24b8d36374b773ce723e4b3ae650e7">endTitleHead</a> (const QCString &amp;fileName, const QCString &amp;name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a583c7e58d6b910b7bdf67120ee4e6875">startParagraph</a> (const QCString &amp;classDef=QCString())</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6523eb013a6f759d505650de41855085">endParagraph</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07cac8a8981da35314f77d8f3edb7f76">writeString</a> (const QCString &amp;text)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf2df33c38b53c9b95fe003aed5bc222">startIndexListItem</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac70ec48d9f50b625f757a02a7758712">endIndexListItem</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace955285a164c7f27f0923986a36cff5">startIndexList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5577c7f73e2b8925ba8aedad6c5d1cc9">endIndexList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a193f96c7af956fe9443ffc099fc5cc13">startIndexKey</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68031752ec7526128f5c77b7e18e932e">endIndexKey</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ffa966ddc43f8d39e5a1e74a814ebef">startIndexValue</a> (bool b)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15cba49ad2f72c412b909f4b39098dd0">endIndexValue</a> (const QCString &amp;name, bool b)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1677b65eb8f01a10b1d767758338a212">startItemList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6efca5985597bb6e51427c51d40732f">endItemList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0d0615da54716436c72e53f16b80adfc">startIndexItem</a> (const QCString &amp;ref, const QCString &amp;file)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6abff25168fc20dbbeb1dab35ddbc7">endIndexItem</a> (const QCString &amp;ref, const QCString &amp;file)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5647a62e8819abb6e6b2378a7c115bbd">docify</a> (const QCString &amp;s)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a411807a84d5f9e2fb716a0f66bde56b6">writeObjectLink</a> (const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af084d8a76621939675ae543f47032fa4">startTextLink</a> (const QCString &amp;file, const QCString &amp;anchor)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74e89e9bcca41e9203ca080fc127a004">endTextLink</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4e97c1da93e9caf6a6675f3972ba7750">writeStartAnnoItem</a> (const QCString &amp;type, const QCString &amp;file, const QCString &amp;path, const QCString &amp;name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a848e77a8fd7af578497f7ee1ec163b98">startTypewriter</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad83302c45e73f387c9dc13789df012f7">endTypewriter</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2cf4898386fe73bfd645d4765e713a2b">startGroupHeader</a> (const QCString &amp;id=QCString(), int extraLevels=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa655c0592e136ba962ac45bb69482638">endGroupHeader</a> (int extraLevels=0)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77e30e9a84b48907b886e8231dbbc20b">startItemListItem</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a784d921c1961db570e1b12905fe97c05">endItemListItem</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f8bf0192c18e0ea785c412b23f6fd3f">startMemberSections</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aff8a0fa5afe518609c8e95ae05a57ee6">endMemberSections</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a545dcbbbcdf8aac24e32df2abe0ea22d">startHeaderSection</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a327fd876b42a81d55c668042dc3104d7">endHeaderSection</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af6404ab3a071c87189d8b8dd2f0d2ef1">startMemberHeader</a> (const QCString &amp;anchor, int typ=2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad50904387e56ccb6532385bfe525e9a2">endMemberHeader</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add8c37a5cb21fb366c941cea862b2285">startMemberSubtitle</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7bb1f47d3fe0d2bc473093e405f348e">endMemberSubtitle</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada069f601f0651010bc78b3ccb0f6f11">startMemberDocList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a65672c5fa7d9f56208917e3d4b8e1895">endMemberDocList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7431bc4b23642f75af48f25a415d4ec8">startMemberList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c8d844390c3ab106b675144baa48fc7">endMemberList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e3c4abdce2bc3800e782a435db5437f">startInlineHeader</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38e8c68dc35efa5e22e9152f25d8b4eb">endInlineHeader</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74d52604537a67d666ce88405c23dc49">startAnonTypeScope</a> (int i1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd5534bf6194d070548a92fae1438f71">endAnonTypeScope</a> (int i1)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7e741530682b5707eb04b3f4009523d">startMemberItem</a> (const QCString &amp;anchor, OutputGenerator::MemberItemType type, const QCString &amp;id=QCString())</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bcc956b2ecbc3aed4f265593621dc0d">endMemberItem</a> (OutputGenerator::MemberItemType type)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af5a6611d3aa4b11eafd0a785d1757483">startMemberTemplateParams</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b4540041426548396bf81bff58483ad">endMemberTemplateParams</a> (const QCString &amp;anchor, const QCString &amp;inheritId)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9278fb907b0c4dda297a1acb6738c2d">startCompoundTemplateParams</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a49fa25db298df5eba06f13e6d037da8c">endCompoundTemplateParams</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae7ca8c46242c727aa527ab392db22707">startMemberGroupHeader</a> (const QCString &amp;id, bool b)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac13352584de9c19dd2776d49c1e9bf30">endMemberGroupHeader</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac78054f50bad730b62b3456699d9a350">startMemberGroupDocs</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3cf86cdcd2fb2e853a0bd5be6edb1858">endMemberGroupDocs</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e6c176d640939fce848f044037209c8">startMemberGroup</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac38b30488a0d82de3aa04b7ae30ed48e">endMemberGroup</a> (bool last)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a> (bool templ=FALSE)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d117e436431c6c8976e8e1e3167b20c">insertMemberAlignLeft</a> (OutputGenerator::MemberItemType typ=OutputGenerator::MemberItemType::Normal, bool templ=FALSE)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2203589f0bc276cb3ba01f529b9536a9">writeRuler</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa14aecc6d7bfdeb2cfbd241fa55059a7">writeAnchor</a> (const QCString &amp;fileName, const QCString &amp;name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba5576798309803175cefaedf33b2a28">startEmphasis</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5674d5d9336eb1f7f6cb83c058f5ad8f">endEmphasis</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a188c7a8f0a0dc35ec5ea0f8b4a491d33">writeChar</a> (char c)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a9ce398bc0c3a3ef316e0c97cc33ce5">startMemberDoc</a> (const QCString &amp;clName, const QCString &amp;memName, const QCString &amp;anchor, const QCString &amp;title, int memCount, int memTotal, bool showInline)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fb2fb5d619d66c8653e05a46a18ef48">endMemberDoc</a> (bool hasArgs)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae4920963ec75457cd7e3662aedded3a">startDoxyAnchor</a> (const QCString &amp;fName, const QCString &amp;manName, const QCString &amp;anchor, const QCString &amp;name, const QCString &amp;args)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a554df4a05f695ab67b514a12d9d19f6d">endDoxyAnchor</a> (const QCString &amp;fn, const QCString &amp;anchor)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87a285c01c1913708553746b1f2813f0">addLabel</a> (const QCString &amp;fName, const QCString &amp;anchor)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a7a1bca5871c912848bddde9b7dd3fc">writeLatexSpacing</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ac4a6e52094643a093fcdeedf1ae0bc">startDescForItem</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e1d56ddf6a6238a4e1b8733d057c782">endDescForItem</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc709b251fc97e9e5c7d3d205ffb0a5e">startCenter</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad71b2d5a74052d9539968a25e7d86bb0">endCenter</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf8ce762c6c7838d86ad132f20a2306a">startSmall</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8142de5d17dd16fce39b80c0dfc3dfe2">endSmall</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adfbaf25ba726ceec65db99fec11ec2ef">lineBreak</a> (const QCString &amp;style=QCString())</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a796018ee85949771252f36fea9a288d0">startBold</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4988f821b416a64d12c7fbc0a4273bba">startMemberDescription</a> (const QCString &amp;anchor, const QCString &amp;inheritId=QCString(), bool typ=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3824b9043050bea2202a29c15b4c5344">endMemberDescription</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09a4062cfac0ed8f9d3dec4cd42f1aa7">startMemberDeclaration</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd8c06dad427743e4bf81f94bd450e6f">endMemberDeclaration</a> (const QCString &amp;anchor, const QCString &amp;inheritId)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae60261a39e2cc0d6fa5d78da1ae5caeb">writeInheritedSectionTitle</a> (const QCString &amp;id, const QCString &amp;ref, const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;title, const QCString &amp;name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f81a490c1354748afe7e3b834f1907b">startExamples</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5ee61a2f622e01eb1aa47f22faafd3b9">endExamples</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5805e09c663ccde368463f3c6a767a59">startIndent</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07c0ce4a1d6d962c658f6611e4eeab83">endIndent</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5bcc70f52a38c5c65e7271d18d3e1ed">startSection</a> (const QCString &amp;lab, const QCString &amp;title, SectionType t)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a135844f68859bdb67f2614664ae26f8d">endSection</a> (const QCString &amp;lab, SectionType t)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6a14eebaf70a50055e47c6738c56de13">addIndexItem</a> (const QCString &amp;s1, const QCString &amp;s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d9096a6b81f3183e6f3dc01e4e093f5">writeSynopsis</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10f734424e06f796ca4c962e0017d8b6">startClassDiagram</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa85387b820d582f467d4575f4598b175">endClassDiagram</a> (const ClassDiagram &amp;d, const QCString &amp;f, const QCString &amp;n)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f14fd99b68f6df4f9510dbc627f5a43">startPageRef</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00f61efb96bdef4833ba228f08c7f18e">endPageRef</a> (const QCString &amp;c, const QCString &amp;a)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74849c1452e8884292ed85bf7c22f2bc">startQuickIndices</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1da800b31634af3c518bfa8c0b8323b">endQuickIndices</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abeb86db48415009b3c09b723216fd8f6">writeSplitBar</a> (const QCString &amp;name, const QCString &amp;allMembersFile)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace864e843eca954efb12af825f56bdca">writeNavigationPath</a> (const QCString &amp;s)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a739eb036549fb3787e5daa3d35bc1aff">writeLogo</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afc0312b9a48cae61656b930d878c718e">writeQuickLinks</a> (HighlightedItem hli, const QCString &amp;file, bool extraTabs=false)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a956032c76c8c263139658a08dfe1e07f">writeSummaryLink</a> (const QCString &amp;file, const QCString &amp;anchor, const QCString &amp;title, bool first)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbe1d0534295cfb5717a33e1c1eb5fb4">writePageOutline</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac891ad4a7081e1ab9d42a637596111db">startContents</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a317bae5a753eac709cf776b2ec2fb732">endContents</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba6135c0dcee35b209b1a4996a5763c1">startPageDoc</a> (const QCString &amp;pageTitle)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a58cd93dd010aa638e8b54259bdea9b74">endPageDoc</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6cc078977edd1e2a5ae2cf6ed64ed35">writeNonBreakableSpace</a> (int num)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d6b8dd40e3bded41a971c0144fed3db">startDescTable</a> (const QCString &amp;title, const bool hasInits)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a223fb4453aeeaf8270e8bd5f875ed9c9">endDescTable</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af4b472918891fdf268e7f13ccdc4e88a">startDescTableRow</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b3d38267387585eb41163745d8c364f">endDescTableRow</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b984edbfa21eecfe20b2a7a3ef0fc97">startDescTableTitle</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51b3d439827ec272ecc6e8c2e108eac0">endDescTableTitle</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20199e8a222bcea2abb9a43a52926ea9">startDescTableInit</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec12276dffdde910102f7b2227cf79fc">endDescTableInit</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8823d3ed58554ae3eeb9169ff920ba00">startDescTableData</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a66b7fd1338764cbe47b66d3f9e77bb07">endDescTableData</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6fc93128d92c79a08995457b10f6e1f">startDotGraph</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf5c8af1474707f76b32e631f033903a">endDotGraph</a> (DotClassGraph &amp;g)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d3ded0121b9163ac3b11c0bb8e380c4">startInclDepGraph</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f1710357f5571f2ce129c6bbd7fd88b">endInclDepGraph</a> (DotInclDepGraph &amp;g)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20837aeac45ccb44d354e42e75eb51c9">startCallGraph</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abcfc4105b1d8a3ad0e21d36a3d82aac3">endCallGraph</a> (DotCallGraph &amp;g)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ecc6dca9d8d4bc9720971ffc1c5b788">startDirDepGraph</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a22010864383bf5332fe866e90f21bd2a">endDirDepGraph</a> (DotDirDeps &amp;g)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41473666261dc8b245cb4daee6bc53a0">startGroupCollaboration</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a28746bbb2c399e6478adca394e6caba7">endGroupCollaboration</a> (DotGroupCollaboration &amp;g)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d7e7f24d5fd2e4fc7cb62f992a7f10f">writeGraphicalHierarchy</a> (DotGfxHierarchyTable &amp;g)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e4b1b0039100083a979ff8d90adce58">startTextBlock</a> (bool dense=FALSE)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06ee92661f22a8e270e6b1cc538773b5">endTextBlock</a> (bool paraBreak=FALSE)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9edb8dc61594b5f30bb7f4b004b04f41">lastIndexPage</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc616cc002e406c1c5816f020fb7d60c">startMemberDocPrefixItem</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7119d284c2d0a7d635d103969d9e628e">endMemberDocPrefixItem</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b9d56f0ab609c25ba0b449e4d977f80">startMemberDocName</a> (bool align)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c30d8717346992a8a9c35f2ae92271f">endMemberDocName</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8db9e1278341d4eeb45328fd9967a6b5">startParameterType</a> (bool first, const QCString &amp;key)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb73d83bd4b05b5041de62a7336747e5">endParameterType</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acde2fcc0d42034b7f342d12119957a81">startParameterName</a> (bool one)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a93053950ab9941273ab071bbb0646c35">endParameterName</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a251c67c01e2bcc17814da33c186bd1f9">startParameterExtra</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0da2c95a60c78bda71d5f35d5adeb02f">endParameterExtra</a> (bool last, bool one, bool bracket)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7350c12854789b59595b4ad1d40a651c">startParameterDefVal</a> (const char *separator)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8be0158b8b2a857157cfe92b802e0609">endParameterDefVal</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a297f991eafa9e368a982c936891bb79e">startParameterList</a> (bool openBracket)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7c1be88384dc59f5ca11f8da2113a4d">endParameterList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60a7f30e2f0edb92bd5ce06d1259340f">exceptionEntry</a> (const QCString &amp;prefix, bool closeBracket)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa97f8716fbd06a49dd172b5c65bb2c56">startConstraintList</a> (const QCString &amp;header)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a552198c8c605b7d5bc9cb49885e5cf87">startConstraintParam</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d50347ddbe39ce2328b87913c64bfdb">endConstraintParam</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a711c480e26d4492f5cd83fc4c9947105">startConstraintType</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a3b0e8b9a13d824c67f0ca04c5fed0d">endConstraintType</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e2a94bd45cf237f40a9a0e7eb1386d2">startConstraintDocs</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7f4d066d76f000ebeb4d810521573fdf">endConstraintDocs</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f970355071c4cdb7e2e125b8e235070">endConstraintList</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac9ba52ac9477c974842dacd16aeb4420">startMemberDocSimple</a> (bool b)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adafe6153e5b6d4d5252abce4ccde8147">endMemberDocSimple</a> (bool b)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41ac30b73768699a957c5714e4c347b4">startInlineMemberType</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3545005c4ed9d2e9058dd3baed0ee5a8">endInlineMemberType</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd00519713f4249371669240e568d29d">startInlineMemberName</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8d98f7851b5215e0f810b0cfcc40e91">endInlineMemberName</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4627e1a2c83cf21e9b63b6c9b99e5381">startInlineMemberDoc</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a70aceb24f76c182ccc5f52285aa235e8">endInlineMemberDoc</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8244f86d2d0ccbf7e9b0641f1d3a8f6">startLabels</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac700283b8e771ab0dd515d5f384632ff">writeLabel</a> (const QCString &amp;l, bool isLast)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf53a952591ed98b004311c5570411a0">endLabels</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af987cfff8d8cad1bd500f87ad547d0cc">startLocalToc</a> (int level)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a90e0efde7c8ea06a10471c9e77516648">endLocalToc</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a132bb85c7da750fadfa35352227b8766">startTocEntry</a> (const SectionInfo *si)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab34d0753ec12c656b36dd16cf16b9987">endTocEntry</a> (const SectionInfo *si)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5e2f6ef346a21e513ea4bd3f53616ba">cleanup</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbe23584d1d25c0df38c01be7b431a90">startPlainFile</a> (const QCString &amp;name)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef22d797dc5dae4fcce9984246587932">endPlainFile</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67839ba61ba53161ae6c0ff75029e6ab">newId</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae02018298c4bb64b600a8d0225a31302">refreshCodeGenerators</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;class... Ts, class... As&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#ae46bbb0266c94292eca9408c224f1eb3">foreach</a> (void(OutputGenIntf::*methodPtr)(Ts...), As &amp;&amp;... args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/structs/outputlist/outputgenelem">OutputGenElem</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d563c5f1a2af94aef565f881aefe5f2">m_codeGenList</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81b1124e7c81f2a183262222801460a8">m_id</a></td>
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

Class representing a list of output generators that are written to in parallel.

Definition at line 313 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxySectionDef">

## Public Member Typedefs

### OutputGenIntfPtr {#ab96ab5436b6d039364d65aa7b05b37d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using OutputList::OutputGenIntfPtr =  std::unique_ptr&lt;OutputGenIntf&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 316 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab96ab5436b6d039364d65aa7b05b37d3">316</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ab96ab5436b6d039364d65aa7b05b37d3">OutputGenIntfPtr</a> = std::unique_ptr&lt;OutputGenIntf&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### OutputList() {#a9c57688bca34e8437f691c7c0a6fae3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputList::OutputList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 343 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c57688bca34e8437f691c7c0a6fae3e">38</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList::OutputList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a67839ba61ba53161ae6c0ff75029e6ab">newId</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m_codeGenList</a>.setId(<a href="#a81b1124e7c81f2a183262222801460a8">m_id</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m\_codeGenList</a>, <a href="#a81b1124e7c81f2a183262222801460a8">m\_id</a> and <a href="#a67839ba61ba53161ae6c0ff75029e6ab">newId</a>.

Referenced by <a href="#a4d5653dcc37e333f00ce357d2440fe6e">operator=</a>, <a href="#add10a6827dd128c3222952ce2b74a233">operator=</a>, <a href="#af39f7d4abc52b7b869bfb783fcac7315">OutputList</a> and <a href="#a3abb58f0059d4992f261fc45ed4d8af2">OutputList</a>.
</div>
</div>

### OutputList() {#af39f7d4abc52b7b869bfb783fcac7315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputList::OutputList (const <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 344 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af39f7d4abc52b7b869bfb783fcac7315">44</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList::OutputList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList</a> &amp;ol) : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>(ol.<a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a81b1124e7c81f2a183262222801460a8">m_id</a> = ol.<a href="#a81b1124e7c81f2a183262222801460a8">m_id</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae02018298c4bb64b600a8d0225a31302">refreshCodeGenerators</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a81b1124e7c81f2a183262222801460a8">m\_id</a>, <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a>, <a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList</a> and <a href="#ae02018298c4bb64b600a8d0225a31302">refreshCodeGenerators</a>.
</div>
</div>

### OutputList() {#a3abb58f0059d4992f261fc45ed4d8af2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputList::OutputList (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;&amp;)</td>
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



Definition at line 346 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

Reference <a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~OutputList() {#ad42a92df914a5cc6ebb1889760c17660}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputList::~OutputList ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel default">default</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 348 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a4d5653dcc37e333f00ce357d2440fe6e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputList &amp; OutputList::operator= (const <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 345 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4d5653dcc37e333f00ce357d2440fe6e">50</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList</a> &amp;<a href="#a4d5653dcc37e333f00ce357d2440fe6e">OutputList::operator=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList</a> &amp;ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">!=&amp;ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a81b1124e7c81f2a183262222801460a8">m_id</a> = ol.<a href="#a81b1124e7c81f2a183262222801460a8">m_id</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a> = ol.<a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ae02018298c4bb64b600a8d0225a31302">refreshCodeGenerators</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a81b1124e7c81f2a183262222801460a8">m\_id</a>, <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a>, <a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList</a> and <a href="#ae02018298c4bb64b600a8d0225a31302">refreshCodeGenerators</a>.
</div>
</div>

### operator=() {#add10a6827dd128c3222952ce2b74a233}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputList &amp; OutputList::operator= (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;&amp;)</td>
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



Definition at line 347 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

Reference <a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#a2ffd4b500e651b8ec1a47acb46e2456c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class DocGenerator&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::add ()</td>
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



Definition at line 351 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ffd4b500e651b8ec1a47acb46e2456c">351</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2ffd4b500e651b8ec1a47acb46e2456c">add</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>.emplace_back(std::make_unique&lt;DocGenerator&gt;());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae02018298c4bb64b600a8d0225a31302">refreshCodeGenerators</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a> and <a href="#ae02018298c4bb64b600a8d0225a31302">refreshCodeGenerators</a>.
</div>
</div>

### addIndexItem() {#a6a14eebaf70a50055e47c6738c56de13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::addIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 592 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6a14eebaf70a50055e47c6738c56de13">592</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6a14eebaf70a50055e47c6738c56de13">addIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a25a640422f1a26c32e99bab05d044738">OutputGenIntf::addIndexItem</a>,s1,s2); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a25a640422f1a26c32e99bab05d044738">OutputGenIntf::addIndexItem</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>.
</div>
</div>

### addLabel() {#a87a285c01c1913708553746b1f2813f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::addLabel (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
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



Definition at line 545 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87a285c01c1913708553746b1f2813f0">545</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a87a285c01c1913708553746b1f2813f0">addLabel</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a7045a43d7af51c6afc747cf4fbb83e62">OutputGenIntf::addLabel</a>,fName,anchor); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a7045a43d7af51c6afc747cf4fbb83e62">OutputGenIntf::addLabel</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### cleanup() {#ac5e2f6ef346a21e513ea4bd3f53616ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::cleanup ()</td>
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



Definition at line 754 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5e2f6ef346a21e513ea4bd3f53616ba">754</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac5e2f6ef346a21e513ea4bd3f53616ba">cleanup</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a80b9bba0ea2a5777a3d1a6b5455d6985">OutputGenIntf::cleanup</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a80b9bba0ea2a5777a3d1a6b5455d6985">OutputGenIntf::cleanup</a>.
</div>
</div>

### codeGenerators() {#a284458e4baf27869eb5bbb9776407e6c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const OutputCodeList &amp; OutputList::codeGenerators ()</td>
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



Definition at line 357 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a284458e4baf27869eb5bbb9776407e6c">357</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;<a href="#a284458e4baf27869eb5bbb9776407e6c">codeGenerators</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m_codeGenList</a>; }</span></span></div>

</div>


Reference <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m\_codeGenList</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aa9637e278284bc82564b4515fb600608">MemberDefImpl::\_writeMultiLineInitializer</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a443391a41c8ca5dd93aa555beeb1955d">startFonts</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aaa81776b056239d1cf7f84632a3eb5ae">ConceptDefImpl::writeDefinition</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6bab634f62d558e8d56cb84dee170cd2">DefinitionImpl::writeInlineCode</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac584b41f75fc411a218e9e684fd491d5">FileDefImpl::writeSourceBody</a>.
</div>
</div>

### codeGenerators() {#a4700ac2ba9ae6445eb7f862502472f35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeList &amp; OutputList::codeGenerators ()</td>
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



Definition at line 358 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4700ac2ba9ae6445eb7f862502472f35">358</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;<a href="#a4700ac2ba9ae6445eb7f862502472f35">codeGenerators</a>()             { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m_codeGenList</a>; }</span></span></div>

</div>


Reference <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m\_codeGenList</a>.
</div>
</div>

### disable() {#a192e28bf96098f41db170be0680d5375}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::disable (<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 364 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a192e28bf96098f41db170be0680d5375">115</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a192e28bf96098f41db170be0680d5375">OutputList::disable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("disable(%d)\n",o);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e.intf-&gt;type()==o) e.setEnabled(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a> and <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a0410c3e0f3f2fd5fdb341546e40d4a7d">MemberDefImpl::\_writeCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af8b226a288cd0a1825db1a191d10a760">MemberDefImpl::\_writeCallGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab88143468d99d9fd8f9567699078864b">endIndexHierarchy</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acbf644aa88ec6940aea9d18c28b69ff0">startIndexHierarchy</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#afc96dfbb364a4e075ba52b72af20722b">ClassDefImpl::startMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#acde950d849a45db1654b634d43f68d26">FileDefImpl::startMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a0dd0f75759005600d0f410ee4a20dc45">GroupDefImpl::startMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a604ef99a0d36078577526746d9b5cac4">ModuleDefImpl::startMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a877432b05ee5e7b53fe5431bfcf1f86b">NamespaceDefImpl::startMemberDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0ba684cbe3b0eb9eec5629f9618f06e4">startTitle</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7679fab482cf6175804f959f5425c2b5">writeClassHierarchy</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5d2fed512d3848212da5d9e44d0238a2">ClassDefImpl::writeCollaborationGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a629cd8190893fac7ea39aaf6b9c39c17">ClassDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aaeb27386c274dd8189167e1a12fe8f1d">DirDefImpl::writeDirectoryGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aa8e7acc156d5f99e61cc895d8f8ea54b">writeDirHierarchy</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af3e55e24323797042e532d5ab5cbfce9">writeExamples</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ac6dfccae4079d225ca50634529b384">GroupDefImpl::writeGroupGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a97e085544f2994c4e3b2e1aab0227a62">writeGroupHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a70678e63b94c7d4727db820a7d8793d1">FileDefImpl::writeInlineClasses</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab475ddec4d159a00ecdf12cba6f2e332">writeModuleList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7889cc7de4a08e7cdeeda1e7154604a4">ClassDefImpl::writeMoreLink</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6fbacb46985c69b37200e1302d9f36ef">writePageRef</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac39050ca48c90714a35d99e9bd53c967">FileDefImpl::writeSourceHeader</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### disableAll() {#a6a75284d21a037302ea3d7dc6e1558d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::disableAll ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 363 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6a75284d21a037302ea3d7dc6e1558d4">105</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6a75284d21a037302ea3d7dc6e1558d4">OutputList::disableAll</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("enableAll()\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">    e.setEnabled(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a> and <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>.
</div>
</div>

### disableAllBut() {#a91f9afddff1974d7805c3d022b754ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::disableAllBut (<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 367 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 85 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91f9afddff1974d7805c3d022b754ddf">85</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a91f9afddff1974d7805c3d022b754ddf">OutputList::disableAllBut</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("disableAllBut(%d)\n",o);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e.intf-&gt;type()!=o) e.setEnabled(</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a> and <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1d6990cbb875b40cb9e658b48ce74dd3">ClassDefImpl::addClassAttributes</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a1caf6a3bfcee91df2dbffda0dd819423">ConceptDefImpl::addConceptAttributes</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#abca12f470cfbae374799e3882affac73">NamespaceDefImpl::addNamespaceAttributes</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f65138605aced4e557cefaebba93625">endFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac1850678fe273e83bcda397bc2f1b6ec">endFileWithNavPath</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#aeb63b0db3ac92afc6ef8fd7a34129001">generateDirDocs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a44044c70833211203ece26ccb6c56a5c">recursivelyAddGroupListToTitle</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a626316953a99d3f5e838a27cd5bd0423">ClassDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aec94d27ae7459f75e56fd19c2653b1a7">ConceptDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#aa3b3cc5ea1e4c508ce1a78633590f2fe">FileDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ed74dd39a7fce0737383a5055efbd18">GroupDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a61998df92e21df36b49f2a09e2d868f4">ModuleDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a4c4bfe146ecd653c8d9ed6b93825bc40">NamespaceDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a629cd8190893fac7ea39aaf6b9c39c17">ClassDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirrelation/#a5fa861050993dafb351589f2f1c05326">DirRelation::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a73d8616a53b1c63bbebaba98f89c5c10">ClassDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a80492b3e70f3fbc4c055d9082ed2d14e">FileDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ab401545421c30c932f18d1991db8ecfb">GroupDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a2938548376f9b9b06c24216ce30a207f">NamespaceDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7889cc7de4a08e7cdeeda1e7154604a4">ClassDefImpl::writeMoreLink</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a508df5a7f2de2d0418f81d08b1fb40f7">DefinitionImpl::writeNavigationPath</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac39050ca48c90714a35d99e9bd53c967">FileDefImpl::writeSourceHeader</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a256a7639e9cfa07c921e0ce19f606a12">FileDefImpl::writeSourceLink</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad28ce13d37a783efc856e85b0cdb791c">ClassDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a26fe21b32c7e96c3c50f8cfd2e06e89f">FileDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a1cd6f5eb27ef6ca1ded4532bd38323b0">GroupDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad9a159e7a8e4ed36a862252a284e0d24">ModuleDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#af7fd110aa3bb86ad68c64ff39239d8fd">NamespaceDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f6b3206f3da0ef3b4135d8a9dc41456">writeUserGroupStubPage</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### docify() {#a5647a62e8819abb6e6b2378a7c115bbd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::docify (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



Definition at line 439 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5647a62e8819abb6e6b2378a7c115bbd">439</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5647a62e8819abb6e6b2378a7c115bbd">docify</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aac6eb7a359ed49bbeb245e3e7b0993eb">OutputGenIntf::docify</a>,s); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aac6eb7a359ed49bbeb245e3e7b0993eb">OutputGenIntf::docify</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aed02fe5ded54336952277d72ed72360d">MemberDefImpl::\_writeGroupInclude</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a8a682f90e07bb6a55566b5941239d23a">MemberDefImpl::\_writeTemplatePrefix</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a54cbf7f6b07bc8fe4ce7295e534c844f">generateFileRef</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a6e1ed35b84f6375897482fc8b753affd">ClassDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a25431a65b263de7827454ea81eb8be29">writeExceptionListImpl</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#aa1221bfb5b21c047427a269f0caef930">writeInheritanceSpecifier</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af6f9b93ecb1822874f1e05f448798516">MemberDefImpl::writeLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7889cc7de4a08e7cdeeda1e7154604a4">ClassDefImpl::writeMoreLink</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a9e4ef930abbc7603896a126a7744b6d9">GroupDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6fbacb46985c69b37200e1302d9f36ef">writePageRef</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a50a5ca2a633e8e9e98f1fdb284b96186">writePartialFilePath</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a31b60db653850e1be9084b27153e6758">VhdlDocGen::writeProcessProto</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#abdbd7a613237d2a86532bfe548209a1d">VhdlDocGen::writeStringLink</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a19a78cda05295880aa74873cfbad293b">ClassDefImpl::writeTemplateSpec</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a6e37fa3f47b3d836813a1cf2a7fef036">VhdlDocGen::writeVhdlLink</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>.
</div>
</div>

### enable() {#a306f5cfd7c296b5a52160343d9631916}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::enable (<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 365 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 125 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a306f5cfd7c296b5a52160343d9631916">125</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a306f5cfd7c296b5a52160343d9631916">OutputList::enable</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("enable(%d)\n",o);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e.intf-&gt;type()==o) e.setEnabled(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a> and <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a76c1ddee2e90178aba880cc93842b1b8">ClassDefImpl::endMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#adc55b02954476c4666dd401825916415">FileDefImpl::endMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8d5eeb539fccd86ae00ce50fb88c7493">ModuleDefImpl::endMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a606af6fee22f1a8c6bbb557cbde9e591">NamespaceDefImpl::endMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a70678e63b94c7d4727db820a7d8793d1">FileDefImpl::writeInlineClasses</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### enableAll() {#ad32603ff4c4ba4d39e0bad7ede5924bf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::enableAll ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 362 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad32603ff4c4ba4d39e0bad7ede5924bf">95</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad32603ff4c4ba4d39e0bad7ede5924bf">OutputList::enableAll</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("enableAll()\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">    e.setEnabled(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a> and <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a0410c3e0f3f2fd5fdb341546e40d4a7d">MemberDefImpl::\_writeCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af8b226a288cd0a1825db1a191d10a760">MemberDefImpl::\_writeCallGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aaeb27386c274dd8189167e1a12fe8f1d">DirDefImpl::writeDirectoryGraph</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a80d65bd635fb8953b458d636b27b754c">FileDefImpl::writeSourceFooter</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a256a7639e9cfa07c921e0ce19f606a12">FileDefImpl::writeSourceLink</a> and <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>.
</div>
</div>

### endAnonTypeScope() {#acd5534bf6194d070548a92fae1438f71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endAnonTypeScope (int i1)</td>
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



Definition at line 493 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd5534bf6194d070548a92fae1438f71">493</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acd5534bf6194d070548a92fae1438f71">endAnonTypeScope</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a251e99f1dd3a2ca68601bac19b82e34e">OutputGenIntf::endAnonTypeScope</a>,i1); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a251e99f1dd3a2ca68601bac19b82e34e">OutputGenIntf::endAnonTypeScope</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>.
</div>
</div>

### endBold() {#aa3f855a4e60d2a7c6769b66d43c69b23}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endBold ()</td>
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



Definition at line 565 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa3f855a4e60d2a7c6769b66d43c69b23">565</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa3f855a4e60d2a7c6769b66d43c69b23">endBold</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aeba9dcd8b62329cd89ae44948320ffb7">OutputGenIntf::endBold</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aeba9dcd8b62329cd89ae44948320ffb7">OutputGenIntf::endBold</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aa9637e278284bc82564b4515fb600608">MemberDefImpl::\_writeMultiLineInitializer</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0ac2f4932405d6a1773bea6eb84885ec">VhdlDocGen::writeClassType</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a6e1ed35b84f6375897482fc8b753affd">ClassDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af6f9b93ecb1822874f1e05f448798516">MemberDefImpl::writeLink</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a50a5ca2a633e8e9e98f1fdb284b96186">writePartialFilePath</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a31b60db653850e1be9084b27153e6758">VhdlDocGen::writeProcessProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad197f46fa25960c771c0e8b897ded06d">VhdlDocGen::writeRecordUnit</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#abdbd7a613237d2a86532bfe548209a1d">VhdlDocGen::writeStringLink</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a6e37fa3f47b3d836813a1cf2a7fef036">VhdlDocGen::writeVhdlLink</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>.
</div>
</div>

### endCallGraph() {#abcfc4105b1d8a3ad0e21d36a3d82aac3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endCallGraph (<a href="/web-doxygen/docs/api/classes/dotcallgraph">DotCallGraph</a> &amp; g)</td>
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



Definition at line 660 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abcfc4105b1d8a3ad0e21d36a3d82aac3">660</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abcfc4105b1d8a3ad0e21d36a3d82aac3">endCallGraph</a>(<a href="/web-doxygen/docs/api/classes/dotcallgraph">DotCallGraph</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a14ff59f95f9e1d0378ca4a740b715d84">OutputGenIntf::endCallGraph</a>,g); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a14ff59f95f9e1d0378ca4a740b715d84">OutputGenIntf::endCallGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a0410c3e0f3f2fd5fdb341546e40d4a7d">MemberDefImpl::\_writeCallerGraph</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af8b226a288cd0a1825db1a191d10a760">MemberDefImpl::\_writeCallGraph</a>.
</div>
</div>

### endCenter() {#ad71b2d5a74052d9539968a25e7d86bb0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endCenter ()</td>
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



Definition at line 555 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad71b2d5a74052d9539968a25e7d86bb0">555</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad71b2d5a74052d9539968a25e7d86bb0">endCenter</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#afac6536bc0b0f3702c307df16e33d377">OutputGenIntf::endCenter</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#afac6536bc0b0f3702c307df16e33d377">OutputGenIntf::endCenter</a>.
</div>
</div>

### endClassDiagram() {#aa85387b820d582f467d4575f4598b175}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endClassDiagram (const <a href="/web-doxygen/docs/api/classes/classdiagram">ClassDiagram</a> &amp; d, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; f, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; n)</td>
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



Definition at line 598 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa85387b820d582f467d4575f4598b175">598</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa85387b820d582f467d4575f4598b175">endClassDiagram</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdiagram">ClassDiagram</a> &amp;d,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#abf06294041a469daea14c657e7f8f8a1">OutputGenIntf::endClassDiagram</a>,d,f,n); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#abf06294041a469daea14c657e7f8f8a1">OutputGenIntf::endClassDiagram</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>.
</div>
</div>

### endCompoundTemplateParams() {#a49fa25db298df5eba06f13e6d037da8c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endCompoundTemplateParams ()</td>
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



Definition at line 505 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a49fa25db298df5eba06f13e6d037da8c">505</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a49fa25db298df5eba06f13e6d037da8c">endCompoundTemplateParams</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ae4a763b35a02d7ea5e883a2f20de2dd5">OutputGenIntf::endCompoundTemplateParams</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ae4a763b35a02d7ea5e883a2f20de2dd5">OutputGenIntf::endCompoundTemplateParams</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a19a78cda05295880aa74873cfbad293b">ClassDefImpl::writeTemplateSpec</a>.
</div>
</div>

### endConstraintDocs() {#a7f4d066d76f000ebeb4d810521573fdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endConstraintDocs ()</td>
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



Definition at line 720 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7f4d066d76f000ebeb4d810521573fdf">720</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7f4d066d76f000ebeb4d810521573fdf">endConstraintDocs</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a22a61ff0c02d0f91fcfa7b4f7ac7f405">OutputGenIntf::endConstraintDocs</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a22a61ff0c02d0f91fcfa7b4f7ac7f405">OutputGenIntf::endConstraintDocs</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>.
</div>
</div>

### endConstraintList() {#a1f970355071c4cdb7e2e125b8e235070}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endConstraintList ()</td>
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



Definition at line 722 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f970355071c4cdb7e2e125b8e235070">722</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1f970355071c4cdb7e2e125b8e235070">endConstraintList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a38b9f1b3191f567cf6c95a6c3521e8fb">OutputGenIntf::endConstraintList</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a38b9f1b3191f567cf6c95a6c3521e8fb">OutputGenIntf::endConstraintList</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>.
</div>
</div>

### endConstraintParam() {#a9d50347ddbe39ce2328b87913c64bfdb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endConstraintParam ()</td>
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



Definition at line 712 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9d50347ddbe39ce2328b87913c64bfdb">712</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9d50347ddbe39ce2328b87913c64bfdb">endConstraintParam</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">713</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aa6d996d867bc819fccaf3b6471247469">OutputGenIntf::endConstraintParam</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aa6d996d867bc819fccaf3b6471247469">OutputGenIntf::endConstraintParam</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>.
</div>
</div>

### endConstraintType() {#a0a3b0e8b9a13d824c67f0ca04c5fed0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endConstraintType ()</td>
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



Definition at line 716 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0a3b0e8b9a13d824c67f0ca04c5fed0d">716</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0a3b0e8b9a13d824c67f0ca04c5fed0d">endConstraintType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ab13fa68b965aa0974f29be60dff9db84">OutputGenIntf::endConstraintType</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ab13fa68b965aa0974f29be60dff9db84">OutputGenIntf::endConstraintType</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>.
</div>
</div>

### endContents() {#a317bae5a753eac709cf776b2ec2fb732}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endContents ()</td>
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



Definition at line 622 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a317bae5a753eac709cf776b2ec2fb732">622</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a317bae5a753eac709cf776b2ec2fb732">endContents</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a54cc5e51ef3ce1f73ce8fe5076728ce2">OutputGenIntf::endContents</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a54cc5e51ef3ce1f73ce8fe5076728ce2">OutputGenIntf::endContents</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f65138605aced4e557cefaebba93625">endFile</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a65a60aa7cc7048c9f3b39312b4aba21d">ConceptDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirrelation/#a5fa861050993dafb351589f2f1c05326">DirRelation::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aab158675591976d0b50ca51071b7a761">NamespaceDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae849568cb2c125f1d3a89a41e3ded5d7">ClassDefImpl::writeDocumentationContents</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af29c795d264e74de8cc53f3d5c550d41">MemberList::writeDocumentationPage</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#a80d65bd635fb8953b458d636b27b754c">FileDefImpl::writeSourceFooter</a>.
</div>
</div>

### endDescForItem() {#a5e1d56ddf6a6238a4e1b8733d057c782}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endDescForItem ()</td>
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



Definition at line 551 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e1d56ddf6a6238a4e1b8733d057c782">551</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5e1d56ddf6a6238a4e1b8733d057c782">endDescForItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ac7c4412fd00138e2fc488aadc7f30245">OutputGenIntf::endDescForItem</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ac7c4412fd00138e2fc488aadc7f30245">OutputGenIntf::endDescForItem</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a25ee1d371527387039fff59d1479a9f7">MemberDefImpl::\_writeExamples</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>.
</div>
</div>

### endDescTable() {#a223fb4453aeeaf8270e8bd5f875ed9c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endDescTable ()</td>
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



Definition at line 632 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a223fb4453aeeaf8270e8bd5f875ed9c9">632</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a223fb4453aeeaf8270e8bd5f875ed9c9">endDescTable</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aa739019fb6ba6bf3574124960a0c008d">OutputGenIntf::endDescTable</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aa739019fb6ba6bf3574124960a0c008d">OutputGenIntf::endDescTable</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>.
</div>
</div>

### endDescTableData() {#a66b7fd1338764cbe47b66d3f9e77bb07}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endDescTableData ()</td>
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



Definition at line 648 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a66b7fd1338764cbe47b66d3f9e77bb07">648</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a66b7fd1338764cbe47b66d3f9e77bb07">endDescTableData</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a0da533da32a0c6732034fd20e5a2ac8e">OutputGenIntf::endDescTableData</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a0da533da32a0c6732034fd20e5a2ac8e">OutputGenIntf::endDescTableData</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>.
</div>
</div>

### endDescTableInit() {#aec12276dffdde910102f7b2227cf79fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endDescTableInit ()</td>
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



Definition at line 644 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aec12276dffdde910102f7b2227cf79fc">644</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aec12276dffdde910102f7b2227cf79fc">endDescTableInit</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ad99cfd41eafdc5084b1295c5566952fe">OutputGenIntf::endDescTableInit</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ad99cfd41eafdc5084b1295c5566952fe">OutputGenIntf::endDescTableInit</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>.
</div>
</div>

### endDescTableRow() {#a0b3d38267387585eb41163745d8c364f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endDescTableRow ()</td>
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



Definition at line 636 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b3d38267387585eb41163745d8c364f">636</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0b3d38267387585eb41163745d8c364f">endDescTableRow</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a396567c15638c9a422a2d81f965f961e">OutputGenIntf::endDescTableRow</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a396567c15638c9a422a2d81f965f961e">OutputGenIntf::endDescTableRow</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>.
</div>
</div>

### endDescTableTitle() {#a51b3d439827ec272ecc6e8c2e108eac0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endDescTableTitle ()</td>
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



Definition at line 640 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a51b3d439827ec272ecc6e8c2e108eac0">640</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a51b3d439827ec272ecc6e8c2e108eac0">endDescTableTitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a8eff9a7f506c0f6e778f3e1042a1164c">OutputGenIntf::endDescTableTitle</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a8eff9a7f506c0f6e778f3e1042a1164c">OutputGenIntf::endDescTableTitle</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>.
</div>
</div>

### endDirDepGraph() {#a22010864383bf5332fe866e90f21bd2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endDirDepGraph (<a href="/web-doxygen/docs/api/classes/dotdirdeps">DotDirDeps</a> &amp; g)</td>
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



Definition at line 664 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a22010864383bf5332fe866e90f21bd2a">664</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a22010864383bf5332fe866e90f21bd2a">endDirDepGraph</a>(<a href="/web-doxygen/docs/api/classes/dotdirdeps">DotDirDeps</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3975a13911703f0137c23fcb011f28d6">OutputGenIntf::endDirDepGraph</a>,g); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3975a13911703f0137c23fcb011f28d6">OutputGenIntf::endDirDepGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aaeb27386c274dd8189167e1a12fe8f1d">DirDefImpl::writeDirectoryGraph</a>.
</div>
</div>

### endDotGraph() {#abf5c8af1474707f76b32e631f033903a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endDotGraph (<a href="/web-doxygen/docs/api/classes/dotclassgraph">DotClassGraph</a> &amp; g)</td>
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



Definition at line 652 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf5c8af1474707f76b32e631f033903a">652</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abf5c8af1474707f76b32e631f033903a">endDotGraph</a>(<a href="/web-doxygen/docs/api/classes/dotclassgraph">DotClassGraph</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a85da45c99b7e32ea195bf761badef17e">OutputGenIntf::endDotGraph</a>,g); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a85da45c99b7e32ea195bf761badef17e">OutputGenIntf::endDotGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5d2fed512d3848212da5d9e44d0238a2">ClassDefImpl::writeCollaborationGraph</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>.
</div>
</div>

### endDoxyAnchor() {#a554df4a05f695ab67b514a12d9d19f6d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endDoxyAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fn, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
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



Definition at line 543 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a554df4a05f695ab67b514a12d9d19f6d">543</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a554df4a05f695ab67b514a12d9d19f6d">endDoxyAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fn,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a7468a0ce3722e8bef650142f7156db55">OutputGenIntf::endDoxyAnchor</a>,fn,anchor); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a7468a0ce3722e8bef650142f7156db55">OutputGenIntf::endDoxyAnchor</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### endEmphasis() {#a5674d5d9336eb1f7f6cb83c058f5ad8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endEmphasis ()</td>
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



Definition at line 529 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5674d5d9336eb1f7f6cb83c058f5ad8f">529</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5674d5d9336eb1f7f6cb83c058f5ad8f">endEmphasis</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a37834e6f65935417349d2385634a2c21">OutputGenIntf::endEmphasis</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a37834e6f65935417349d2385634a2c21">OutputGenIntf::endEmphasis</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### endExamples() {#a5ee61a2f622e01eb1aa47f22faafd3b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endExamples ()</td>
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



Definition at line 582 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5ee61a2f622e01eb1aa47f22faafd3b9">582</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5ee61a2f622e01eb1aa47f22faafd3b9">endExamples</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ad2f10d9cc4f4ff526bff1d3898f33934">OutputGenIntf::endExamples</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ad2f10d9cc4f4ff526bff1d3898f33934">OutputGenIntf::endExamples</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a25ee1d371527387039fff59d1479a9f7">MemberDefImpl::\_writeExamples</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>.
</div>
</div>

### endFile() {#a5b0f833d3150110151ae6a095a8549a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endFile ()</td>
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



Definition at line 403 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b0f833d3150110151ae6a095a8549a5">403</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5b0f833d3150110151ae6a095a8549a5">endFile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aec223180ecc276ad0d0382a7de95bfb9">OutputGenIntf::endFile</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aec223180ecc276ad0d0382a7de95bfb9">OutputGenIntf::endFile</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f65138605aced4e557cefaebba93625">endFile</a>.
</div>
</div>

### endGroupCollaboration() {#a28746bbb2c399e6478adca394e6caba7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endGroupCollaboration (<a href="/web-doxygen/docs/api/classes/dotgroupcollaboration">DotGroupCollaboration</a> &amp; g)</td>
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



Definition at line 668 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a28746bbb2c399e6478adca394e6caba7">668</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a28746bbb2c399e6478adca394e6caba7">endGroupCollaboration</a>(<a href="/web-doxygen/docs/api/classes/dotgroupcollaboration">DotGroupCollaboration</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aab20e32028a6c404de530f20a8d08afe">OutputGenIntf::endGroupCollaboration</a>,g); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aab20e32028a6c404de530f20a8d08afe">OutputGenIntf::endGroupCollaboration</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ac6dfccae4079d225ca50634529b384">GroupDefImpl::writeGroupGraph</a>.
</div>
</div>

### endGroupHeader() {#aa655c0592e136ba962ac45bb69482638}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endGroupHeader (int extraLevels=0)</td>
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



Definition at line 457 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa655c0592e136ba962ac45bb69482638">457</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa655c0592e136ba962ac45bb69482638">endGroupHeader</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> extraLevels=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a7c1550c8839cbd8b1ebe15247624502b">OutputGenIntf::endGroupHeader</a>,extraLevels); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a7c1550c8839cbd8b1ebe15247624502b">OutputGenIntf::endGroupHeader</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a626316953a99d3f5e838a27cd5bd0423">ClassDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aec94d27ae7459f75e56fd19c2653b1a7">ConceptDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#aa3b3cc5ea1e4c508ce1a78633590f2fe">FileDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ed74dd39a7fce0737383a5055efbd18">GroupDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a61998df92e21df36b49f2a09e2d868f4">ModuleDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a4c4bfe146ecd653c8d9ed6b93825bc40">NamespaceDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aaa81776b056239d1cf7f84632a3eb5ae">ConceptDefImpl::writeDefinition</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a629cd8190893fac7ea39aaf6b9c39c17">ClassDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classlinkedrefmap/#aa36e57d8b3b8814f56caff17d0562173">ClassLinkedRefMap::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>.
</div>
</div>

### endHeaderSection() {#a327fd876b42a81d55c668042dc3104d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endHeaderSection ()</td>
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



Definition at line 469 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a327fd876b42a81d55c668042dc3104d7">469</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a327fd876b42a81d55c668042dc3104d7">endHeaderSection</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aa0cb366bd225ec3b8637dbf745bb8495">OutputGenIntf::endHeaderSection</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aa0cb366bd225ec3b8637dbf745bb8495">OutputGenIntf::endHeaderSection</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a289057be7abaa91df92db8ac5160aa79">endTitle</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.
</div>
</div>

### endInclDepGraph() {#a6f1710357f5571f2ce129c6bbd7fd88b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endInclDepGraph (<a href="/web-doxygen/docs/api/classes/dotincldepgraph">DotInclDepGraph</a> &amp; g)</td>
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



Definition at line 656 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f1710357f5571f2ce129c6bbd7fd88b">656</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6f1710357f5571f2ce129c6bbd7fd88b">endInclDepGraph</a>(<a href="/web-doxygen/docs/api/classes/dotincldepgraph">DotInclDepGraph</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a7c2ff3af9f3bc519bf30ab81fd72cd75">OutputGenIntf::endInclDepGraph</a>,g); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a7c2ff3af9f3bc519bf30ab81fd72cd75">OutputGenIntf::endInclDepGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>.
</div>
</div>

### endIndent() {#a07c0ce4a1d6d962c658f6611e4eeab83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endIndent ()</td>
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



Definition at line 586 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07c0ce4a1d6d962c658f6611e4eeab83">586</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a07c0ce4a1d6d962c658f6611e4eeab83">endIndent</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#addf2b99b43f4d42da4ff4201ad2daf3d">OutputGenIntf::endIndent</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#addf2b99b43f4d42da4ff4201ad2daf3d">OutputGenIntf::endIndent</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>.
</div>
</div>

### endIndexItem() {#a4a6abff25168fc20dbbeb1dab35ddbc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file)</td>
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



Definition at line 437 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a6abff25168fc20dbbeb1dab35ddbc7">437</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4a6abff25168fc20dbbeb1dab35ddbc7">endIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a499b7e7082ce98ac420b4713a0a4fb0a">OutputGenIntf::endIndexItem</a>,ref,file); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a499b7e7082ce98ac420b4713a0a4fb0a">OutputGenIntf::endIndexItem</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>.
</div>
</div>

### endIndexKey() {#a68031752ec7526128f5c77b7e18e932e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endIndexKey ()</td>
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



Definition at line 425 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a68031752ec7526128f5c77b7e18e932e">425</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a68031752ec7526128f5c77b7e18e932e">endIndexKey</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#af6b5aa596df8637546d29846c07c971e">OutputGenIntf::endIndexKey</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#af6b5aa596df8637546d29846c07c971e">OutputGenIntf::endIndexKey</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>.
</div>
</div>

### endIndexList() {#a5577c7f73e2b8925ba8aedad6c5d1cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endIndexList ()</td>
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



Definition at line 421 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5577c7f73e2b8925ba8aedad6c5d1cc9">421</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5577c7f73e2b8925ba8aedad6c5d1cc9">endIndexList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a7c5b6593573ffe5ab167aa4f3b2ffdb9">OutputGenIntf::endIndexList</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a7c5b6593573ffe5ab167aa4f3b2ffdb9">OutputGenIntf::endIndexList</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab88143468d99d9fd8f9567699078864b">endIndexHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>.
</div>
</div>

### endIndexListItem() {#aac70ec48d9f50b625f757a02a7758712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endIndexListItem ()</td>
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



Definition at line 417 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac70ec48d9f50b625f757a02a7758712">417</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aac70ec48d9f50b625f757a02a7758712">endIndexListItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a157226abc71a5e32f8cb882cc4d943b1">OutputGenIntf::endIndexListItem</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a157226abc71a5e32f8cb882cc4d943b1">OutputGenIntf::endIndexListItem</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>.
</div>
</div>

### endIndexSection() {#a59226412e1c0b732f16dfbf601c2c388}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endIndexSection (<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a> is)</td>
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



Definition at line 389 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a59226412e1c0b732f16dfbf601c2c388">389</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a59226412e1c0b732f16dfbf601c2c388">endIndexSection</a>(<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a> is)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a927f5983fc93c11d18237ca76fb74eb5">OutputGenIntf::endIndexSection</a>,is); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a927f5983fc93c11d18237ca76fb74eb5">OutputGenIntf::endIndexSection</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.
</div>
</div>

### endIndexValue() {#a15cba49ad2f72c412b909f4b39098dd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endIndexValue (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, bool b)</td>
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



Definition at line 429 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15cba49ad2f72c412b909f4b39098dd0">429</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a15cba49ad2f72c412b909f4b39098dd0">endIndexValue</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ae711fa5b116608e306734eec728f6d79">OutputGenIntf::endIndexValue</a>,name,b); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ae711fa5b116608e306734eec728f6d79">OutputGenIntf::endIndexValue</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>.
</div>
</div>

### endInlineHeader() {#a38e8c68dc35efa5e22e9152f25d8b4eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endInlineHeader ()</td>
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



Definition at line 489 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38e8c68dc35efa5e22e9152f25d8b4eb">489</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a38e8c68dc35efa5e22e9152f25d8b4eb">endInlineHeader</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a60ae605fb609b3390e640b46ea9485df">OutputGenIntf::endInlineHeader</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a60ae605fb609b3390e640b46ea9485df">OutputGenIntf::endInlineHeader</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>.
</div>
</div>

### endInlineMemberDoc() {#a70aceb24f76c182ccc5f52285aa235e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endInlineMemberDoc ()</td>
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



Definition at line 738 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a70aceb24f76c182ccc5f52285aa235e8">738</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a70aceb24f76c182ccc5f52285aa235e8">endInlineMemberDoc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a89b792e5046631e4093bcf4a61411eeb">OutputGenIntf::endInlineMemberDoc</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a89b792e5046631e4093bcf4a61411eeb">OutputGenIntf::endInlineMemberDoc</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>.
</div>
</div>

### endInlineMemberName() {#ad8d98f7851b5215e0f810b0cfcc40e91}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endInlineMemberName ()</td>
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



Definition at line 734 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8d98f7851b5215e0f810b0cfcc40e91">734</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad8d98f7851b5215e0f810b0cfcc40e91">endInlineMemberName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3b809e57901e6c2e3cff2a413f2af5de">OutputGenIntf::endInlineMemberName</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3b809e57901e6c2e3cff2a413f2af5de">OutputGenIntf::endInlineMemberName</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>.
</div>
</div>

### endInlineMemberType() {#a3545005c4ed9d2e9058dd3baed0ee5a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endInlineMemberType ()</td>
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



Definition at line 730 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3545005c4ed9d2e9058dd3baed0ee5a8">730</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3545005c4ed9d2e9058dd3baed0ee5a8">endInlineMemberType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a7ca6cba268cc3096f54b1c9d58876d22">OutputGenIntf::endInlineMemberType</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a7ca6cba268cc3096f54b1c9d58876d22">OutputGenIntf::endInlineMemberType</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>.
</div>
</div>

### endItemList() {#ac6efca5985597bb6e51427c51d40732f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endItemList ()</td>
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



Definition at line 433 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac6efca5985597bb6e51427c51d40732f">433</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac6efca5985597bb6e51427c51d40732f">endItemList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a10e1c75aa036fadb2b4914564c1be3ff">OutputGenIntf::endItemList</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a10e1c75aa036fadb2b4914564c1be3ff">OutputGenIntf::endItemList</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab88143468d99d9fd8f9567699078864b">endIndexHierarchy</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a>.
</div>
</div>

### endItemListItem() {#a784d921c1961db570e1b12905fe97c05}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endItemListItem ()</td>
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



Definition at line 461 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a784d921c1961db570e1b12905fe97c05">461</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a784d921c1961db570e1b12905fe97c05">endItemListItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aa3e20dae21d9d6e5b11a94a38b10896a">OutputGenIntf::endItemListItem</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aa3e20dae21d9d6e5b11a94a38b10896a">OutputGenIntf::endItemListItem</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a>.
</div>
</div>

### endLabels() {#aaf53a952591ed98b004311c5570411a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endLabels ()</td>
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



Definition at line 744 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaf53a952591ed98b004311c5570411a0">744</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aaf53a952591ed98b004311c5570411a0">endLabels</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a695f6a7ee5d38ef46da40bc44fca8828">OutputGenIntf::endLabels</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a695f6a7ee5d38ef46da40bc44fca8828">OutputGenIntf::endLabels</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1d6990cbb875b40cb9e658b48ce74dd3">ClassDefImpl::addClassAttributes</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a1caf6a3bfcee91df2dbffda0dd819423">ConceptDefImpl::addConceptAttributes</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#abca12f470cfbae374799e3882affac73">NamespaceDefImpl::addNamespaceAttributes</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### endLocalToc() {#a90e0efde7c8ea06a10471c9e77516648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endLocalToc ()</td>
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



Definition at line 748 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a90e0efde7c8ea06a10471c9e77516648">748</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a90e0efde7c8ea06a10471c9e77516648">endLocalToc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">749</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a7b88cf6885c4ca71693bb3ca988a48b2">OutputGenIntf::endLocalToc</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a7b88cf6885c4ca71693bb3ca988a48b2">OutputGenIntf::endLocalToc</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a>.
</div>
</div>

### endMemberDeclaration() {#acd8c06dad427743e4bf81f94bd450e6f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberDeclaration (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
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



Definition at line 573 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd8c06dad427743e4bf81f94bd450e6f">573</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acd8c06dad427743e4bf81f94bd450e6f">endMemberDeclaration</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inheritId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ad7a6280b740a76252834564a1f4fbce9">OutputGenIntf::endMemberDeclaration</a>,anchor,inheritId); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ad7a6280b740a76252834564a1f4fbce9">OutputGenIntf::endMemberDeclaration</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a6e1ed35b84f6375897482fc8b753affd">ClassDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a> and <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>.
</div>
</div>

### endMemberDescription() {#a3824b9043050bea2202a29c15b4c5344}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberDescription ()</td>
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



Definition at line 569 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3824b9043050bea2202a29c15b4c5344">569</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3824b9043050bea2202a29c15b4c5344">endMemberDescription</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a9ae7d5969b715c6e25b3937179bdfcda">OutputGenIntf::endMemberDescription</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a9ae7d5969b715c6e25b3937179bdfcda">OutputGenIntf::endMemberDescription</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### endMemberDoc() {#a1fb2fb5d619d66c8653e05a46a18ef48}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberDoc (bool hasArgs)</td>
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



Definition at line 537 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1fb2fb5d619d66c8653e05a46a18ef48">537</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1fb2fb5d619d66c8653e05a46a18ef48">endMemberDoc</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasArgs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#afe07b6722ddad023f2a87715be57d02a">OutputGenIntf::endMemberDoc</a>,hasArgs); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#afe07b6722ddad023f2a87715be57d02a">OutputGenIntf::endMemberDoc</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>.
</div>
</div>

### endMemberDocList() {#a65672c5fa7d9f56208917e3d4b8e1895}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberDocList ()</td>
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



Definition at line 481 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a65672c5fa7d9f56208917e3d4b8e1895">481</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a65672c5fa7d9f56208917e3d4b8e1895">endMemberDocList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aa4eb90cc7d89d88a0d2333be8063394f">OutputGenIntf::endMemberDocList</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aa4eb90cc7d89d88a0d2333be8063394f">OutputGenIntf::endMemberDocList</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a>.
</div>
</div>

### endMemberDocName() {#a1c30d8717346992a8a9c35f2ae92271f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberDocName ()</td>
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



Definition at line 684 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c30d8717346992a8a9c35f2ae92271f">684</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1c30d8717346992a8a9c35f2ae92271f">endMemberDocName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a97574716039c8331afbd0295e0cd7dac">OutputGenIntf::endMemberDocName</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a97574716039c8331afbd0295e0cd7dac">OutputGenIntf::endMemberDocName</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>.
</div>
</div>

### endMemberDocPrefixItem() {#a7119d284c2d0a7d635d103969d9e628e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberDocPrefixItem ()</td>
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



Definition at line 680 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7119d284c2d0a7d635d103969d9e628e">680</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7119d284c2d0a7d635d103969d9e628e">endMemberDocPrefixItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aac37e18752d8dac929d084738ea62392">OutputGenIntf::endMemberDocPrefixItem</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aac37e18752d8dac929d084738ea62392">OutputGenIntf::endMemberDocPrefixItem</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### endMemberDocSimple() {#adafe6153e5b6d4d5252abce4ccde8147}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberDocSimple (bool b)</td>
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



Definition at line 726 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adafe6153e5b6d4d5252abce4ccde8147">726</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adafe6153e5b6d4d5252abce4ccde8147">endMemberDocSimple</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a24f794d0e5c68e92203f4ce949d9948a">OutputGenIntf::endMemberDocSimple</a>,b); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a24f794d0e5c68e92203f4ce949d9948a">OutputGenIntf::endMemberDocSimple</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a8cab5da1323054e47ede48e03a1420a2">MemberList::writeSimpleDocumentation</a>.
</div>
</div>

### endMemberGroup() {#ac38b30488a0d82de3aa04b7ae30ed48e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberGroup (bool last)</td>
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



Definition at line 517 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac38b30488a0d82de3aa04b7ae30ed48e">517</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac38b30488a0d82de3aa04b7ae30ed48e">endMemberGroup</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> last)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a595fff4a7d0ae9b9d7642237c28f8901">OutputGenIntf::endMemberGroup</a>,last); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a595fff4a7d0ae9b9d7642237c28f8901">OutputGenIntf::endMemberGroup</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### endMemberGroupDocs() {#a3cf86cdcd2fb2e853a0bd5be6edb1858}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberGroupDocs ()</td>
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



Definition at line 513 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3cf86cdcd2fb2e853a0bd5be6edb1858">513</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3cf86cdcd2fb2e853a0bd5be6edb1858">endMemberGroupDocs</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a0c8b5416218377138621fb34b840b790">OutputGenIntf::endMemberGroupDocs</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a0c8b5416218377138621fb34b840b790">OutputGenIntf::endMemberGroupDocs</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### endMemberGroupHeader() {#ac13352584de9c19dd2776d49c1e9bf30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberGroupHeader ()</td>
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



Definition at line 509 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac13352584de9c19dd2776d49c1e9bf30">509</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac13352584de9c19dd2776d49c1e9bf30">endMemberGroupHeader</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a50e780b2fe3496ff171dbb1e6759b341">OutputGenIntf::endMemberGroupHeader</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a50e780b2fe3496ff171dbb1e6759b341">OutputGenIntf::endMemberGroupHeader</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### endMemberHeader() {#ad50904387e56ccb6532385bfe525e9a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberHeader ()</td>
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



Definition at line 473 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad50904387e56ccb6532385bfe525e9a2">473</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad50904387e56ccb6532385bfe525e9a2">endMemberHeader</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a6a824e30a4173507c3d8b8fc1d391840">OutputGenIntf::endMemberHeader</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a6a824e30a4173507c3d8b8fc1d391840">OutputGenIntf::endMemberHeader</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3e05e32173b1326ae7ef4204bc6557ce">ClassDefImpl::endMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### endMemberItem() {#a7bcc956b2ecbc3aed4f265593621dc0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberItem (<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">OutputGenerator::MemberItemType</a> type)</td>
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



Definition at line 497 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7bcc956b2ecbc3aed4f265593621dc0d">497</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7bcc956b2ecbc3aed4f265593621dc0d">endMemberItem</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">OutputGenerator::MemberItemType</a> type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aa9af48be8371aee3f0d0b65d4fd22015">OutputGenIntf::endMemberItem</a>,type); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aa9af48be8371aee3f0d0b65d4fd22015">OutputGenIntf::endMemberItem</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a6e1ed35b84f6375897482fc8b753affd">ClassDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### endMemberList() {#a7c8d844390c3ab106b675144baa48fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberList ()</td>
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



Definition at line 485 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c8d844390c3ab106b675144baa48fc7">485</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7c8d844390c3ab106b675144baa48fc7">endMemberList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a7f70ed026824c54b80bb9019bb8fd735">OutputGenIntf::endMemberList</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a7f70ed026824c54b80bb9019bb8fd735">OutputGenIntf::endMemberList</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classlinkedrefmap/#a1c99c36b0a60cba930a8a4909e2f72cc">ClassLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/conceptlinkedrefmap/#a0b784a4bcc64f3284b548fdf10a37b88">ConceptLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/modulelinkedrefmap/#aebc005e13bdcb448da76f4b43b2ea72e">ModuleLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a> and <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>.
</div>
</div>

### endMemberSections() {#aff8a0fa5afe518609c8e95ae05a57ee6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberSections ()</td>
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



Definition at line 465 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aff8a0fa5afe518609c8e95ae05a57ee6">465</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aff8a0fa5afe518609c8e95ae05a57ee6">endMemberSections</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a667642e79b9e787ffaaed927431106e7">OutputGenIntf::endMemberSections</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a667642e79b9e787ffaaed927431106e7">OutputGenIntf::endMemberSections</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3e05e32173b1326ae7ef4204bc6557ce">ClassDefImpl::endMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#acb76a01f1c2e7e09c945498155eb6d64">DirDefImpl::endMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a642d4998df5ea71746623b0aee8258b3">FileDefImpl::endMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a0cd5758dfed8b6c4dfbbed4c4332554d">GroupDefImpl::endMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a2010cf3ec23f07530980fd32988724a3">ModuleDefImpl::endMemberDeclarations</a> and <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a9fa90c700a95a73474a55a72de622ec2">NamespaceDefImpl::endMemberDeclarations</a>.
</div>
</div>

### endMemberSubtitle() {#ad7bb1f47d3fe0d2bc473093e405f348e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberSubtitle ()</td>
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



Definition at line 477 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad7bb1f47d3fe0d2bc473093e405f348e">477</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad7bb1f47d3fe0d2bc473093e405f348e">endMemberSubtitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a024f537b0e167928d8fbbd7c83126afe">OutputGenIntf::endMemberSubtitle</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a024f537b0e167928d8fbbd7c83126afe">OutputGenIntf::endMemberSubtitle</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### endMemberTemplateParams() {#a1b4540041426548396bf81bff58483ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endMemberTemplateParams (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId)</td>
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



Definition at line 501 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b4540041426548396bf81bff58483ad">501</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1b4540041426548396bf81bff58483ad">endMemberTemplateParams</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inheritId)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ae5d41dae8e31415f650b52a29eba2817">OutputGenIntf::endMemberTemplateParams</a>,anchor,inheritId); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ae5d41dae8e31415f650b52a29eba2817">OutputGenIntf::endMemberTemplateParams</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>.
</div>
</div>

### endPageDoc() {#a58cd93dd010aa638e8b54259bdea9b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endPageDoc ()</td>
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



Definition at line 626 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a58cd93dd010aa638e8b54259bdea9b74">626</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a58cd93dd010aa638e8b54259bdea9b74">endPageDoc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a39d62301cd87ef0c6e51bc7c55c9982b">OutputGenIntf::endPageDoc</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a39d62301cd87ef0c6e51bc7c55c9982b">OutputGenIntf::endPageDoc</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.
</div>
</div>

### endPageRef() {#a00f61efb96bdef4833ba228f08c7f18e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endPageRef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; c, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; a)</td>
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



Definition at line 602 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a00f61efb96bdef4833ba228f08c7f18e">602</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a00f61efb96bdef4833ba228f08c7f18e">endPageRef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;c,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;a)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ac0916dd878a34ca4c4b65492dc17b3c8">OutputGenIntf::endPageRef</a>,c,a); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ac0916dd878a34ca4c4b65492dc17b3c8">OutputGenIntf::endPageRef</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6fbacb46985c69b37200e1302d9f36ef">writePageRef</a>.
</div>
</div>

### endParagraph() {#a6523eb013a6f759d505650de41855085}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endParagraph ()</td>
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



Definition at line 411 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6523eb013a6f759d505650de41855085">411</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6523eb013a6f759d505650de41855085">endParagraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a8f725c5406981a4aaa9aba38078ffc71">OutputGenIntf::endParagraph</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a8f725c5406981a4aaa9aba38078ffc71">OutputGenIntf::endParagraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9fc4cfd40097fc38d509676f1f060fad">MemberDefImpl::\_writeCategoryRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aed02fe5ded54336952277d72ed72360d">MemberDefImpl::\_writeGroupInclude</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3bd86295355fd18bd7308c9f598a446a">MemberDefImpl::\_writeReimplementedBy</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad2dcf0394d47fc2228362b4cd0d6109e">MemberDefImpl::\_writeReimplements</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad7028f83d76c5512f951bde8f46e7067">DefinitionImpl::writeSourceDef</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#a256a7639e9cfa07c921e0ce19f606a12">FileDefImpl::writeSourceLink</a>.
</div>
</div>

### endParameterDefVal() {#a8be0158b8b2a857157cfe92b802e0609}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endParameterDefVal ()</td>
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



Definition at line 700 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8be0158b8b2a857157cfe92b802e0609">700</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8be0158b8b2a857157cfe92b802e0609">endParameterDefVal</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a35d39fdc7cdaec182baa7fb3d909fab7">OutputGenIntf::endParameterDefVal</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a35d39fdc7cdaec182baa7fb3d909fab7">OutputGenIntf::endParameterDefVal</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.
</div>
</div>

### endParameterExtra() {#a0da2c95a60c78bda71d5f35d5adeb02f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endParameterExtra (bool last, bool one, bool bracket)</td>
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



Definition at line 696 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0da2c95a60c78bda71d5f35d5adeb02f">696</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0da2c95a60c78bda71d5f35d5adeb02f">endParameterExtra</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> last,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> one,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a6cbac7733e17d57b2caccb30e3bf98e2">OutputGenIntf::endParameterExtra</a>,last,one,bracket); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a6cbac7733e17d57b2caccb30e3bf98e2">OutputGenIntf::endParameterExtra</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>.
</div>
</div>

### endParameterList() {#ab7c1be88384dc59f5ca11f8da2113a4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endParameterList ()</td>
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



Definition at line 704 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab7c1be88384dc59f5ca11f8da2113a4d">704</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab7c1be88384dc59f5ca11f8da2113a4d">endParameterList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a514360a2c3c4b46107f244004e6befa5">OutputGenIntf::endParameterList</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a514360a2c3c4b46107f244004e6befa5">OutputGenIntf::endParameterList</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### endParameterName() {#a93053950ab9941273ab071bbb0646c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endParameterName ()</td>
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



Definition at line 692 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a93053950ab9941273ab071bbb0646c35">692</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a93053950ab9941273ab071bbb0646c35">endParameterName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a9958dc52e088a6c840c324f992a61782">OutputGenIntf::endParameterName</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a9958dc52e088a6c840c324f992a61782">OutputGenIntf::endParameterName</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>.
</div>
</div>

### endParameterType() {#acb73d83bd4b05b5041de62a7336747e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endParameterType ()</td>
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



Definition at line 688 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb73d83bd4b05b5041de62a7336747e5">688</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acb73d83bd4b05b5041de62a7336747e5">endParameterType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a436aab094abf10c862af8e86712ac7df">OutputGenIntf::endParameterType</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a436aab094abf10c862af8e86712ac7df">OutputGenIntf::endParameterType</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>.
</div>
</div>

### endPlainFile() {#aef22d797dc5dae4fcce9984246587932}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endPlainFile ()</td>
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



Definition at line 758 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aef22d797dc5dae4fcce9984246587932">758</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aef22d797dc5dae4fcce9984246587932">endPlainFile</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a43b7360d19bc7009a3d6ff1ec1398664">OutputGenIntf::endPlainFile</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a43b7360d19bc7009a3d6ff1ec1398664">OutputGenIntf::endPlainFile</a>.
</div>
</div>

### endProjectNumber() {#ad6faf5debd750bf3fb143ffc571a0d22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endProjectNumber ()</td>
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



Definition at line 395 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6faf5debd750bf3fb143ffc571a0d22">395</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad6faf5debd750bf3fb143ffc571a0d22">endProjectNumber</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ab8f1a4a235cb4e41997f238b2c969d18">OutputGenIntf::endProjectNumber</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ab8f1a4a235cb4e41997f238b2c969d18">OutputGenIntf::endProjectNumber</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.
</div>
</div>

### endQuickIndices() {#ab1da800b31634af3c518bfa8c0b8323b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endQuickIndices ()</td>
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



Definition at line 606 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab1da800b31634af3c518bfa8c0b8323b">606</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab1da800b31634af3c518bfa8c0b8323b">endQuickIndices</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a779e6a499dbba756b5589de4cab1d8a8">OutputGenIntf::endQuickIndices</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a779e6a499dbba756b5589de4cab1d8a8">OutputGenIntf::endQuickIndices</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a8183f7413c2945be8d3a2ca7ee4f237f">startFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a783230ed87aae779b1e405abfe5b9954">ClassDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a65a60aa7cc7048c9f3b39312b4aba21d">ConceptDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirrelation/#a5fa861050993dafb351589f2f1c05326">DirRelation::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aab158675591976d0b50ca51071b7a761">NamespaceDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af29c795d264e74de8cc53f3d5c550d41">MemberList::writeDocumentationPage</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac39050ca48c90714a35d99e9bd53c967">FileDefImpl::writeSourceHeader</a>.
</div>
</div>

### endSection() {#a135844f68859bdb67f2614664ae26f8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endSection (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; lab, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> t)</td>
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



Definition at line 590 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a135844f68859bdb67f2614664ae26f8d">590</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a135844f68859bdb67f2614664ae26f8d">endSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;lab,<a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aaf3c9cb988a0e2d49068465772433409">OutputGenIntf::endSection</a>,lab,t); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aaf3c9cb988a0e2d49068465772433409">OutputGenIntf::endSection</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a> and <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a9e4ef930abbc7603896a126a7744b6d9">GroupDefImpl::writePageDocumentation</a>.
</div>
</div>

### endSmall() {#a8142de5d17dd16fce39b80c0dfc3dfe2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endSmall ()</td>
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



Definition at line 559 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8142de5d17dd16fce39b80c0dfc3dfe2">559</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8142de5d17dd16fce39b80c0dfc3dfe2">endSmall</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a74f9d5740031dd466964edd9c1d8e366">OutputGenIntf::endSmall</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a74f9d5740031dd466964edd9c1d8e366">OutputGenIntf::endSmall</a>.
</div>
</div>

### endTextBlock() {#a06ee92661f22a8e270e6b1cc538773b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endTextBlock (bool paraBreak=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
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



Definition at line 674 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a06ee92661f22a8e270e6b1cc538773b5">674</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a06ee92661f22a8e270e6b1cc538773b5">endTextBlock</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> paraBreak=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aad5585b6af901be0830ae54b693668ce">OutputGenIntf::endTextBlock</a>,paraBreak); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputgenintf/#aad5585b6af901be0830ae54b693668ce">OutputGenIntf::endTextBlock</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a9e4ef930abbc7603896a126a7744b6d9">GroupDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>.
</div>
</div>

### endTextLink() {#a74e89e9bcca41e9203ca080fc127a004}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endTextLink ()</td>
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



Definition at line 446 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74e89e9bcca41e9203ca080fc127a004">446</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a74e89e9bcca41e9203ca080fc127a004">endTextLink</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a578bfc0ee8985ffdf1e141445e3479e4">OutputGenIntf::endTextLink</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a578bfc0ee8985ffdf1e141445e3479e4">OutputGenIntf::endTextLink</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7889cc7de4a08e7cdeeda1e7154604a4">ClassDefImpl::writeMoreLink</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac39050ca48c90714a35d99e9bd53c967">FileDefImpl::writeSourceHeader</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a256a7639e9cfa07c921e0ce19f606a12">FileDefImpl::writeSourceLink</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### endTitleHead() {#a0d24b8d36374b773ce723e4b3ae650e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endTitleHead (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 407 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0d24b8d36374b773ce723e4b3ae650e7">407</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0d24b8d36374b773ce723e4b3ae650e7">endTitleHead</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#abc47b7bf7e7ba0ab1b3a34f4e36e5a37">OutputGenIntf::endTitleHead</a>,fileName,name); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#abc47b7bf7e7ba0ab1b3a34f4e36e5a37">OutputGenIntf::endTitleHead</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a289057be7abaa91df92db8ac5160aa79">endTitle</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.
</div>
</div>

### endTocEntry() {#ab34d0753ec12c656b36dd16cf16b9987}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endTocEntry (const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * si)</td>
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



Definition at line 752 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab34d0753ec12c656b36dd16cf16b9987">752</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab34d0753ec12c656b36dd16cf16b9987">endTocEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a20804e800904af439381fbf9f11be3d3">OutputGenIntf::endTocEntry</a>,si); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a20804e800904af439381fbf9f11be3d3">OutputGenIntf::endTocEntry</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a>.
</div>
</div>

### endTypewriter() {#ad83302c45e73f387c9dc13789df012f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::endTypewriter ()</td>
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



Definition at line 453 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad83302c45e73f387c9dc13789df012f7">453</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad83302c45e73f387c9dc13789df012f7">endTypewriter</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3a10feddac419bcac5c2456710213600">OutputGenIntf::endTypewriter</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3a10feddac419bcac5c2456710213600">OutputGenIntf::endTypewriter</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aed02fe5ded54336952277d72ed72360d">MemberDefImpl::\_writeGroupInclude</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#aa1221bfb5b21c047427a269f0caef930">writeInheritanceSpecifier</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>.
</div>
</div>

### exceptionEntry() {#a60a7f30e2f0edb92bd5ce06d1259340f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::exceptionEntry (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; prefix, bool closeBracket)</td>
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



Definition at line 706 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60a7f30e2f0edb92bd5ce06d1259340f">706</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a60a7f30e2f0edb92bd5ce06d1259340f">exceptionEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> closeBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a41b77727f57a04d415d7acfa77dfcf13">OutputGenIntf::exceptionEntry</a>,<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>,closeBracket); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputgenintf/#a41b77727f57a04d415d7acfa77dfcf13">OutputGenIntf::exceptionEntry</a> and <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a25431a65b263de7827454ea81eb8be29">writeExceptionListImpl</a>.
</div>
</div>

### generateDoc() {#ac371cebadb37ea8ab3ae59502036c427}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::generateDoc (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int startLine, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * ctx, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; docStr, bool indexWords, bool isExample, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; exampleName, bool singleLine, bool linkFromIndex, bool markdownSupport=<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT), bool autolinkSupport=<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(AUTOLINK_SUPPORT))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 371 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 168 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac371cebadb37ea8ab3ae59502036c427">168</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac371cebadb37ea8ab3ae59502036c427">OutputList::generateDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *ctx,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;docStr,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> indexWords,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isExample,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;exampleName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> singleLine,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> linkFromIndex,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> markdownSupport,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> autolinkSupport)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (docStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> count=std::count_if(<a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>.begin(),<a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">                           [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e) { return e.enabled; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// we want to validate irrespective of the number of output formats</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// specified as:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - when only XML format there should be warnings as well (XML has its own write routines)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - no formats there should be warnings as well</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> parser { <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">createDocParser</a>() };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ast    { <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>(*parser.get(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">                                   fileName,startLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">                                   ctx,md,docStr,indexWords,isExample,exampleName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">                                   singleLine,linkFromIndex,markdownSupport,autolinkSupport) };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ast &amp;&amp; count&gt;0) <a href="#a475da5dda736fa915aca9fc855b1d2e7">writeDoc</a>(ast.get(),ctx,md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">createDocParser</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a> and <a href="#a475da5dda736fa915aca9fc855b1d2e7">writeDoc</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a9e4ef930abbc7603896a126a7744b6d9">GroupDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### insertMemberAlign() {#a8a0967d0442047bfe07a5644505c2d68}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::insertMemberAlign (bool templ=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
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



Definition at line 519 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8a0967d0442047bfe07a5644505c2d68">519</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8a0967d0442047bfe07a5644505c2d68">insertMemberAlign</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> templ=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aa837f5a6ce555e11398b3df3ecb3e88f">OutputGenIntf::insertMemberAlign</a>,templ); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="/web-doxygen/docs/api/classes/outputgenintf/#aa837f5a6ce555e11398b3df3ecb3e88f">OutputGenIntf::insertMemberAlign</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad197f46fa25960c771c0e8b897ded06d">VhdlDocGen::writeRecordUnit</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### insertMemberAlignLeft() {#a1d117e436431c6c8976e8e1e3167b20c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::insertMemberAlignLeft (<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">OutputGenerator::MemberItemType</a> typ=<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">OutputGenerator::MemberItemType::Normal</a>, bool templ=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
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



Definition at line 521 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d117e436431c6c8976e8e1e3167b20c">521</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1d117e436431c6c8976e8e1e3167b20c">insertMemberAlignLeft</a>(<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">OutputGenerator::MemberItemType</a> typ=<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">OutputGenerator::MemberItemType::Normal</a>, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> templ=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a2082c126cedbfc6c0491fc8b96ccba7a">OutputGenIntf::insertMemberAlignLeft</a>,typ,templ); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/outputgenintf/#a2082c126cedbfc6c0491fc8b96ccba7a">OutputGenIntf::insertMemberAlignLeft</a> and <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcba960b44c579bc2f6818d2daaf9e4c16f0">OutputGenerator::Normal</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### isEnabled() {#a046bd3dcc4d8e2cc12821fba1394d818}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool OutputList::isEnabled (<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 366 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 135 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a046bd3dcc4d8e2cc12821fba1394d818">135</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a046bd3dcc4d8e2cc12821fba1394d818">OutputList::isEnabled</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3">OutputType</a> o)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e.intf-&gt;type()==o) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> e.enabled; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a70678e63b94c7d4727db820a7d8793d1">FileDefImpl::writeInlineClasses</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### lastIndexPage() {#a9edb8dc61594b5f30bb7f4b004b04f41}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::lastIndexPage ()</td>
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



Definition at line 676 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9edb8dc61594b5f30bb7f4b004b04f41">676</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9edb8dc61594b5f30bb7f4b004b04f41">lastIndexPage</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a707578caad094f7af3f04f1b4a54f052">OutputGenIntf::lastIndexPage</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a707578caad094f7af3f04f1b4a54f052">OutputGenIntf::lastIndexPage</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.
</div>
</div>

### lineBreak() {#adfbaf25ba726ceec65db99fec11ec2ef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::lineBreak (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; style=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
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



Definition at line 561 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adfbaf25ba726ceec65db99fec11ec2ef">561</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adfbaf25ba726ceec65db99fec11ec2ef">lineBreak</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;style=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a5a3b3d5489a1fcb2d885e3544da2a924">OutputGenIntf::lineBreak</a>,style); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a5a3b3d5489a1fcb2d885e3544da2a924">OutputGenIntf::lineBreak</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a8a682f90e07bb6a55566b5941239d23a">MemberDefImpl::\_writeTemplatePrefix</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a19a78cda05295880aa74873cfbad293b">ClassDefImpl::writeTemplateSpec</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a6e37fa3f47b3d836813a1cf2a7fef036">VhdlDocGen::writeVhdlLink</a>.
</div>
</div>

### parseText() {#adfdcf2ba925f05be8beb8cf43deb168a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::parseText (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; textStr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 379 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 199 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adfdcf2ba925f05be8beb8cf43deb168a">199</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adfdcf2ba925f05be8beb8cf43deb168a">OutputList::parseText</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;textStr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> count=std::count_if(<a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>.begin(),<a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">                           [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e) { return e.enabled; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// we want to validate irrespective of the number of output formats</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// specified as:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - when only XML format there should be warnings as well (XML has its own write routines)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - no formats there should be warnings as well</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> parser { <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">createDocParser</a>() };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ast { <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a>(*parser.get(), textStr) };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ast &amp;&amp; count&gt;0) <a href="#a475da5dda736fa915aca9fc855b1d2e7">writeDoc</a>(ast.get(),</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">createDocParser</a>, <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a> and <a href="#a475da5dda736fa915aca9fc855b1d2e7">writeDoc</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a0410c3e0f3f2fd5fdb341546e40d4a7d">MemberDefImpl::\_writeCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af8b226a288cd0a1825db1a191d10a760">MemberDefImpl::\_writeCallGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9fc4cfd40097fc38d509676f1f060fad">MemberDefImpl::\_writeCategoryRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aa9637e278284bc82564b4515fb600608">MemberDefImpl::\_writeMultiLineInitializer</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad2dcf0394d47fc2228362b4cd0d6109e">MemberDefImpl::\_writeReimplements</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3e05e32173b1326ae7ef4204bc6557ce">ClassDefImpl::endMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a626316953a99d3f5e838a27cd5bd0423">ClassDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aec94d27ae7459f75e56fd19c2653b1a7">ConceptDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#aa3b3cc5ea1e4c508ce1a78633590f2fe">FileDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ed74dd39a7fce0737383a5055efbd18">GroupDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a61998df92e21df36b49f2a09e2d868f4">ModuleDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a4c4bfe146ecd653c8d9ed6b93825bc40">NamespaceDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5d2fed512d3848212da5d9e44d0238a2">ClassDefImpl::writeCollaborationGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aaa81776b056239d1cf7f84632a3eb5ae">ConceptDefImpl::writeDefinition</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a629cd8190893fac7ea39aaf6b9c39c17">ClassDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aaeb27386c274dd8189167e1a12fe8f1d">DirDefImpl::writeDirectoryGraph</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a783230ed87aae779b1e405abfe5b9954">ClassDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classlinkedrefmap/#aa36e57d8b3b8814f56caff17d0562173">ClassLinkedRefMap::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a65a60aa7cc7048c9f3b39312b4aba21d">ConceptDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirrelation/#a5fa861050993dafb351589f2f1c05326">DirRelation::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aab158675591976d0b50ca51071b7a761">NamespaceDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ac6dfccae4079d225ca50634529b384">GroupDefImpl::writeGroupGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae241503d7e4252f10ab58d6bacc87973">writeMarkerList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7889cc7de4a08e7cdeeda1e7154604a4">ClassDefImpl::writeMoreLink</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad7028f83d76c5512f951bde8f46e7067">DefinitionImpl::writeSourceDef</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac39050ca48c90714a35d99e9bd53c967">FileDefImpl::writeSourceHeader</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a256a7639e9cfa07c921e0ce19f606a12">FileDefImpl::writeSourceLink</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f6b3206f3da0ef3b4135d8a9dc41456">writeUserGroupStubPage</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### popGeneratorState() {#a94eb1af2ea07425ef1faa539d24adcf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::popGeneratorState ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 369 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 154 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a94eb1af2ea07425ef1faa539d24adcf8">154</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a94eb1af2ea07425ef1faa539d24adcf8">OutputList::popGeneratorState</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("popGeneratorState()\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!e.enabledStack.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">      e.enabled = e.enabledStack.top();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">      e.enabledStack.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a> and <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1d6990cbb875b40cb9e658b48ce74dd3">ClassDefImpl::addClassAttributes</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a1caf6a3bfcee91df2dbffda0dd819423">ConceptDefImpl::addConceptAttributes</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#abca12f470cfbae374799e3882affac73">NamespaceDefImpl::addNamespaceAttributes</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f65138605aced4e557cefaebba93625">endFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac1850678fe273e83bcda397bc2f1b6ec">endFileWithNavPath</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab88143468d99d9fd8f9567699078864b">endIndexHierarchy</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ef887c55bb17b0a8022971fcc716db6">GroupDefImpl::endMemberDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a289057be7abaa91df92db8ac5160aa79">endTitle</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#aeb63b0db3ac92afc6ef8fd7a34129001">generateDirDocs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a44044c70833211203ece26ccb6c56a5c">recursivelyAddGroupListToTitle</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acbf644aa88ec6940aea9d18c28b69ff0">startIndexHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a626316953a99d3f5e838a27cd5bd0423">ClassDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aec94d27ae7459f75e56fd19c2653b1a7">ConceptDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#aa3b3cc5ea1e4c508ce1a78633590f2fe">FileDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ed74dd39a7fce0737383a5055efbd18">GroupDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a61998df92e21df36b49f2a09e2d868f4">ModuleDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a4c4bfe146ecd653c8d9ed6b93825bc40">NamespaceDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7679fab482cf6175804f959f5425c2b5">writeClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5d2fed512d3848212da5d9e44d0238a2">ClassDefImpl::writeCollaborationGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a629cd8190893fac7ea39aaf6b9c39c17">ClassDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aa8e7acc156d5f99e61cc895d8f8ea54b">writeDirHierarchy</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirrelation/#a5fa861050993dafb351589f2f1c05326">DirRelation::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af3e55e24323797042e532d5ab5cbfce9">writeExamples</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ac6dfccae4079d225ca50634529b384">GroupDefImpl::writeGroupGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a97e085544f2994c4e3b2e1aab0227a62">writeGroupHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6bab634f62d558e8d56cb84dee170cd2">DefinitionImpl::writeInlineCode</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a73d8616a53b1c63bbebaba98f89c5c10">ClassDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a80492b3e70f3fbc4c055d9082ed2d14e">FileDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ab401545421c30c932f18d1991db8ecfb">GroupDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a2938548376f9b9b06c24216ce30a207f">NamespaceDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab475ddec4d159a00ecdf12cba6f2e332">writeModuleList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7889cc7de4a08e7cdeeda1e7154604a4">ClassDefImpl::writeMoreLink</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a508df5a7f2de2d0418f81d08b1fb40f7">DefinitionImpl::writeNavigationPath</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6fbacb46985c69b37200e1302d9f36ef">writePageRef</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac39050ca48c90714a35d99e9bd53c967">FileDefImpl::writeSourceHeader</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad28ce13d37a783efc856e85b0cdb791c">ClassDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a26fe21b32c7e96c3c50f8cfd2e06e89f">FileDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a1cd6f5eb27ef6ca1ded4532bd38323b0">GroupDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad9a159e7a8e4ed36a862252a284e0d24">ModuleDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#af7fd110aa3bb86ad68c64ff39239d8fd">NamespaceDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f6b3206f3da0ef3b4135d8a9dc41456">writeUserGroupStubPage</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### pushGeneratorState() {#a885957a64f7d87aefb663c4ec903188f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::pushGeneratorState ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 368 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a885957a64f7d87aefb663c4ec903188f">144</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a885957a64f7d87aefb663c4ec903188f">OutputList::pushGeneratorState</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("pushGeneratorState()\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">    e.enabledStack.push(e.enabled);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a> and <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1d6990cbb875b40cb9e658b48ce74dd3">ClassDefImpl::addClassAttributes</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a1caf6a3bfcee91df2dbffda0dd819423">ConceptDefImpl::addConceptAttributes</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#abca12f470cfbae374799e3882affac73">NamespaceDefImpl::addNamespaceAttributes</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f65138605aced4e557cefaebba93625">endFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac1850678fe273e83bcda397bc2f1b6ec">endFileWithNavPath</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab88143468d99d9fd8f9567699078864b">endIndexHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#aeb63b0db3ac92afc6ef8fd7a34129001">generateDirDocs</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a44044c70833211203ece26ccb6c56a5c">recursivelyAddGroupListToTitle</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acbf644aa88ec6940aea9d18c28b69ff0">startIndexHierarchy</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a0dd0f75759005600d0f410ee4a20dc45">GroupDefImpl::startMemberDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0ba684cbe3b0eb9eec5629f9618f06e4">startTitle</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a626316953a99d3f5e838a27cd5bd0423">ClassDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aec94d27ae7459f75e56fd19c2653b1a7">ConceptDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#aa3b3cc5ea1e4c508ce1a78633590f2fe">FileDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ed74dd39a7fce0737383a5055efbd18">GroupDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a61998df92e21df36b49f2a09e2d868f4">ModuleDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a4c4bfe146ecd653c8d9ed6b93825bc40">NamespaceDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7679fab482cf6175804f959f5425c2b5">writeClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5d2fed512d3848212da5d9e44d0238a2">ClassDefImpl::writeCollaborationGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a629cd8190893fac7ea39aaf6b9c39c17">ClassDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aa8e7acc156d5f99e61cc895d8f8ea54b">writeDirHierarchy</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirrelation/#a5fa861050993dafb351589f2f1c05326">DirRelation::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af3e55e24323797042e532d5ab5cbfce9">writeExamples</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ac6dfccae4079d225ca50634529b384">GroupDefImpl::writeGroupGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a97e085544f2994c4e3b2e1aab0227a62">writeGroupHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6bab634f62d558e8d56cb84dee170cd2">DefinitionImpl::writeInlineCode</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a73d8616a53b1c63bbebaba98f89c5c10">ClassDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a80492b3e70f3fbc4c055d9082ed2d14e">FileDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ab401545421c30c932f18d1991db8ecfb">GroupDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a2938548376f9b9b06c24216ce30a207f">NamespaceDefImpl::writeMemberPages</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab475ddec4d159a00ecdf12cba6f2e332">writeModuleList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7889cc7de4a08e7cdeeda1e7154604a4">ClassDefImpl::writeMoreLink</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a508df5a7f2de2d0418f81d08b1fb40f7">DefinitionImpl::writeNavigationPath</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6fbacb46985c69b37200e1302d9f36ef">writePageRef</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac39050ca48c90714a35d99e9bd53c967">FileDefImpl::writeSourceHeader</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad28ce13d37a783efc856e85b0cdb791c">ClassDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a26fe21b32c7e96c3c50f8cfd2e06e89f">FileDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a1cd6f5eb27ef6ca1ded4532bd38323b0">GroupDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad9a159e7a8e4ed36a862252a284e0d24">ModuleDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#af7fd110aa3bb86ad68c64ff39239d8fd">NamespaceDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f6b3206f3da0ef3b4135d8a9dc41456">writeUserGroupStubPage</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### size() {#a38c3477fea42348693927abc9b16d209}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t OutputList::size ()</td>
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



Definition at line 360 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38c3477fea42348693927abc9b16d209">360</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a38c3477fea42348693927abc9b16d209">size</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>.size(); }</span></span></div>

</div>


Reference <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a>.
</div>
</div>

### startAnonTypeScope() {#a74d52604537a67d666ce88405c23dc49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startAnonTypeScope (int i1)</td>
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



Definition at line 491 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74d52604537a67d666ce88405c23dc49">491</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a74d52604537a67d666ce88405c23dc49">startAnonTypeScope</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a373de27a917a5e5b6421fa26f87c4449">OutputGenIntf::startAnonTypeScope</a>,i1); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a373de27a917a5e5b6421fa26f87c4449">OutputGenIntf::startAnonTypeScope</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>.
</div>
</div>

### startBold() {#a796018ee85949771252f36fea9a288d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startBold ()</td>
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



Definition at line 563 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a796018ee85949771252f36fea9a288d0">563</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a796018ee85949771252f36fea9a288d0">startBold</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3b32f7ed14989d25fd76888ab942e65b">OutputGenIntf::startBold</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3b32f7ed14989d25fd76888ab942e65b">OutputGenIntf::startBold</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aa9637e278284bc82564b4515fb600608">MemberDefImpl::\_writeMultiLineInitializer</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0ac2f4932405d6a1773bea6eb84885ec">VhdlDocGen::writeClassType</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a6e1ed35b84f6375897482fc8b753affd">ClassDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0b58904c2803fe64c007b6c3ddda086e">VhdlDocGen::writeFormatString</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af6f9b93ecb1822874f1e05f448798516">MemberDefImpl::writeLink</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a50a5ca2a633e8e9e98f1fdb284b96186">writePartialFilePath</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a31b60db653850e1be9084b27153e6758">VhdlDocGen::writeProcessProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad197f46fa25960c771c0e8b897ded06d">VhdlDocGen::writeRecordUnit</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#abdbd7a613237d2a86532bfe548209a1d">VhdlDocGen::writeStringLink</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a6e37fa3f47b3d836813a1cf2a7fef036">VhdlDocGen::writeVhdlLink</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>.
</div>
</div>

### startCallGraph() {#a20837aeac45ccb44d354e42e75eb51c9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startCallGraph ()</td>
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



Definition at line 658 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a20837aeac45ccb44d354e42e75eb51c9">658</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a20837aeac45ccb44d354e42e75eb51c9">startCallGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#adb8e5518bbf7f0829f3a2572a1720079">OutputGenIntf::startCallGraph</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#adb8e5518bbf7f0829f3a2572a1720079">OutputGenIntf::startCallGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a0410c3e0f3f2fd5fdb341546e40d4a7d">MemberDefImpl::\_writeCallerGraph</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af8b226a288cd0a1825db1a191d10a760">MemberDefImpl::\_writeCallGraph</a>.
</div>
</div>

### startCenter() {#acc709b251fc97e9e5c7d3d205ffb0a5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startCenter ()</td>
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



Definition at line 553 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc709b251fc97e9e5c7d3d205ffb0a5e">553</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acc709b251fc97e9e5c7d3d205ffb0a5e">startCenter</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a8a4437f40ef79e76ed6aca6e2b6eb4e5">OutputGenIntf::startCenter</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a8a4437f40ef79e76ed6aca6e2b6eb4e5">OutputGenIntf::startCenter</a>.
</div>
</div>

### startClassDiagram() {#a10f734424e06f796ca4c962e0017d8b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startClassDiagram ()</td>
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



Definition at line 596 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a10f734424e06f796ca4c962e0017d8b6">596</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a10f734424e06f796ca4c962e0017d8b6">startClassDiagram</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a9b1cedf05d8efc75853f8e7c7582f322">OutputGenIntf::startClassDiagram</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a9b1cedf05d8efc75853f8e7c7582f322">OutputGenIntf::startClassDiagram</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>.
</div>
</div>

### startCompoundTemplateParams() {#ac9278fb907b0c4dda297a1acb6738c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startCompoundTemplateParams ()</td>
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



Definition at line 503 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac9278fb907b0c4dda297a1acb6738c2d">503</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac9278fb907b0c4dda297a1acb6738c2d">startCompoundTemplateParams</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a94f617fe193172f0f97b27c499de9cfa">OutputGenIntf::startCompoundTemplateParams</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a94f617fe193172f0f97b27c499de9cfa">OutputGenIntf::startCompoundTemplateParams</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a19a78cda05295880aa74873cfbad293b">ClassDefImpl::writeTemplateSpec</a>.
</div>
</div>

### startConstraintDocs() {#a5e2a94bd45cf237f40a9a0e7eb1386d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startConstraintDocs ()</td>
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



Definition at line 718 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e2a94bd45cf237f40a9a0e7eb1386d2">718</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5e2a94bd45cf237f40a9a0e7eb1386d2">startConstraintDocs</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">719</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a7dc709f71d6789db7c3b4443ed448b1a">OutputGenIntf::startConstraintDocs</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a7dc709f71d6789db7c3b4443ed448b1a">OutputGenIntf::startConstraintDocs</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>.
</div>
</div>

### startConstraintList() {#aa97f8716fbd06a49dd172b5c65bb2c56}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startConstraintList (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; header)</td>
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



Definition at line 708 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa97f8716fbd06a49dd172b5c65bb2c56">708</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa97f8716fbd06a49dd172b5c65bb2c56">startConstraintList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;header)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a04817619e41efde49c970d1975151edf">OutputGenIntf::startConstraintList</a>,header); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a04817619e41efde49c970d1975151edf">OutputGenIntf::startConstraintList</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>.
</div>
</div>

### startConstraintParam() {#a552198c8c605b7d5bc9cb49885e5cf87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startConstraintParam ()</td>
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



Definition at line 710 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a552198c8c605b7d5bc9cb49885e5cf87">710</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a552198c8c605b7d5bc9cb49885e5cf87">startConstraintParam</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ae9d43c719e2fccb17737dfebaec0a07c">OutputGenIntf::startConstraintParam</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ae9d43c719e2fccb17737dfebaec0a07c">OutputGenIntf::startConstraintParam</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>.
</div>
</div>

### startConstraintType() {#a711c480e26d4492f5cd83fc4c9947105}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startConstraintType ()</td>
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



Definition at line 714 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a711c480e26d4492f5cd83fc4c9947105">714</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a711c480e26d4492f5cd83fc4c9947105">startConstraintType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a24edd015165887d5e18c316e68c655c4">OutputGenIntf::startConstraintType</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a24edd015165887d5e18c316e68c655c4">OutputGenIntf::startConstraintType</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>.
</div>
</div>

### startContents() {#ac891ad4a7081e1ab9d42a637596111db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startContents ()</td>
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



Definition at line 620 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac891ad4a7081e1ab9d42a637596111db">620</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac891ad4a7081e1ab9d42a637596111db">startContents</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ae686f96a24cb17e204b8d497701d5d62">OutputGenIntf::startContents</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ae686f96a24cb17e204b8d497701d5d62">OutputGenIntf::startContents</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a65a60aa7cc7048c9f3b39312b4aba21d">ConceptDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dirrelation/#a5fa861050993dafb351589f2f1c05326">DirRelation::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aab158675591976d0b50ca51071b7a761">NamespaceDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae849568cb2c125f1d3a89a41e3ded5d7">ClassDefImpl::writeDocumentationContents</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af29c795d264e74de8cc53f3d5c550d41">MemberList::writeDocumentationPage</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac39050ca48c90714a35d99e9bd53c967">FileDefImpl::writeSourceHeader</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f6b3206f3da0ef3b4135d8a9dc41456">writeUserGroupStubPage</a>.
</div>
</div>

### startDescForItem() {#a8ac4a6e52094643a093fcdeedf1ae0bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startDescForItem ()</td>
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



Definition at line 549 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ac4a6e52094643a093fcdeedf1ae0bc">549</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8ac4a6e52094643a093fcdeedf1ae0bc">startDescForItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a62c4d70eded6831c56b01a78ed8de5a9">OutputGenIntf::startDescForItem</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a62c4d70eded6831c56b01a78ed8de5a9">OutputGenIntf::startDescForItem</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a25ee1d371527387039fff59d1479a9f7">MemberDefImpl::\_writeExamples</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>.
</div>
</div>

### startDescTable() {#a7d6b8dd40e3bded41a971c0144fed3db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startDescTable (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const bool hasInits)</td>
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



Definition at line 630 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d6b8dd40e3bded41a971c0144fed3db">630</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7d6b8dd40e3bded41a971c0144fed3db">startDescTable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasInits)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a099593df5a76ae4bb6826aa8be58ca71">OutputGenIntf::startDescTable</a>,title,hasInits); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a099593df5a76ae4bb6826aa8be58ca71">OutputGenIntf::startDescTable</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>.
</div>
</div>

### startDescTableData() {#a8823d3ed58554ae3eeb9169ff920ba00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startDescTableData ()</td>
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



Definition at line 646 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8823d3ed58554ae3eeb9169ff920ba00">646</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8823d3ed58554ae3eeb9169ff920ba00">startDescTableData</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a14febd9e78a190e5e6fc1b0000a86845">OutputGenIntf::startDescTableData</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a14febd9e78a190e5e6fc1b0000a86845">OutputGenIntf::startDescTableData</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>.
</div>
</div>

### startDescTableInit() {#a20199e8a222bcea2abb9a43a52926ea9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startDescTableInit ()</td>
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



Definition at line 642 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a20199e8a222bcea2abb9a43a52926ea9">642</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a20199e8a222bcea2abb9a43a52926ea9">startDescTableInit</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ab38bee163993a50c58b8bd4c79216d1a">OutputGenIntf::startDescTableInit</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ab38bee163993a50c58b8bd4c79216d1a">OutputGenIntf::startDescTableInit</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>.
</div>
</div>

### startDescTableRow() {#af4b472918891fdf268e7f13ccdc4e88a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startDescTableRow ()</td>
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



Definition at line 634 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af4b472918891fdf268e7f13ccdc4e88a">634</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af4b472918891fdf268e7f13ccdc4e88a">startDescTableRow</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a6ee5d670908097c2bc08bedf6e1c32c6">OutputGenIntf::startDescTableRow</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a6ee5d670908097c2bc08bedf6e1c32c6">OutputGenIntf::startDescTableRow</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>.
</div>
</div>

### startDescTableTitle() {#a6b984edbfa21eecfe20b2a7a3ef0fc97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startDescTableTitle ()</td>
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



Definition at line 638 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b984edbfa21eecfe20b2a7a3ef0fc97">638</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6b984edbfa21eecfe20b2a7a3ef0fc97">startDescTableTitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ab1af7866c36c8c7fe2d2375558935b85">OutputGenIntf::startDescTableTitle</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ab1af7866c36c8c7fe2d2375558935b85">OutputGenIntf::startDescTableTitle</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>.
</div>
</div>

### startDirDepGraph() {#a6ecc6dca9d8d4bc9720971ffc1c5b788}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startDirDepGraph ()</td>
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



Definition at line 662 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ecc6dca9d8d4bc9720971ffc1c5b788">662</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6ecc6dca9d8d4bc9720971ffc1c5b788">startDirDepGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aba0e8dca170cca694dc0166fb95aa13e">OutputGenIntf::startDirDepGraph</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aba0e8dca170cca694dc0166fb95aa13e">OutputGenIntf::startDirDepGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aaeb27386c274dd8189167e1a12fe8f1d">DirDefImpl::writeDirectoryGraph</a>.
</div>
</div>

### startDotGraph() {#ac6fc93128d92c79a08995457b10f6e1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startDotGraph ()</td>
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



Definition at line 650 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac6fc93128d92c79a08995457b10f6e1f">650</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac6fc93128d92c79a08995457b10f6e1f">startDotGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ad2819be1125a573d7abdbf5a522b9310">OutputGenIntf::startDotGraph</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ad2819be1125a573d7abdbf5a522b9310">OutputGenIntf::startDotGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5d2fed512d3848212da5d9e44d0238a2">ClassDefImpl::writeCollaborationGraph</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>.
</div>
</div>

### startDoxyAnchor() {#aae4920963ec75457cd7e3662aedded3a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startDoxyAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; manName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; args)</td>
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



Definition at line 539 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aae4920963ec75457cd7e3662aedded3a">539</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aae4920963ec75457cd7e3662aedded3a">startDoxyAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;manName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aecae8460986ee6b91397ae321ce627a1">OutputGenIntf::startDoxyAnchor</a>,fName,manName,anchor,name,args); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aecae8460986ee6b91397ae321ce627a1">OutputGenIntf::startDoxyAnchor</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### startEmphasis() {#aba5576798309803175cefaedf33b2a28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startEmphasis ()</td>
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



Definition at line 527 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aba5576798309803175cefaedf33b2a28">527</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aba5576798309803175cefaedf33b2a28">startEmphasis</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#adcc1b898c2dcc3f6062da795a440da48">OutputGenIntf::startEmphasis</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#adcc1b898c2dcc3f6062da795a440da48">OutputGenIntf::startEmphasis</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### startExamples() {#a6f81a490c1354748afe7e3b834f1907b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startExamples ()</td>
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



Definition at line 580 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f81a490c1354748afe7e3b834f1907b">580</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6f81a490c1354748afe7e3b834f1907b">startExamples</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a8c05d1ccc1a97e87db2eb6ac111ba720">OutputGenIntf::startExamples</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a8c05d1ccc1a97e87db2eb6ac111ba720">OutputGenIntf::startExamples</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a25ee1d371527387039fff59d1479a9f7">MemberDefImpl::\_writeExamples</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>.
</div>
</div>

### startFile() {#a518814a98f44c11f73dbea3b7b3ed795}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; manName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, int hierarchyLevel=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 378 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 192 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a518814a98f44c11f73dbea3b7b3ed795">192</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a518814a98f44c11f73dbea3b7b3ed795">OutputList::startFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;manName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> hierarchyLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a67839ba61ba53161ae6c0ff75029e6ab">newId</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m_codeGenList</a>.setId(<a href="#a81b1124e7c81f2a183262222801460a8">m_id</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a751894ca7271d62e186144bf6ea750b4">OutputGenIntf::startFile</a>,name,manName,title,<a href="#a81b1124e7c81f2a183262222801460a8">m_id</a>,hierarchyLevel);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m\_codeGenList</a>, <a href="#a81b1124e7c81f2a183262222801460a8">m\_id</a>, <a href="#a67839ba61ba53161ae6c0ff75029e6ab">newId</a> and <a href="/web-doxygen/docs/api/classes/outputgenintf/#a751894ca7271d62e186144bf6ea750b4">OutputGenIntf::startFile</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a8183f7413c2945be8d3a2ca7ee4f237f">startFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>.
</div>
</div>

### startGroupCollaboration() {#a41473666261dc8b245cb4daee6bc53a0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startGroupCollaboration ()</td>
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



Definition at line 666 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41473666261dc8b245cb4daee6bc53a0">666</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a41473666261dc8b245cb4daee6bc53a0">startGroupCollaboration</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a695dc048f7688078bff6ba6eae779dea">OutputGenIntf::startGroupCollaboration</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a695dc048f7688078bff6ba6eae779dea">OutputGenIntf::startGroupCollaboration</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ac6dfccae4079d225ca50634529b384">GroupDefImpl::writeGroupGraph</a>.
</div>
</div>

### startGroupHeader() {#a2cf4898386fe73bfd645d4765e713a2b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startGroupHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), int extraLevels=0)</td>
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



Definition at line 455 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2cf4898386fe73bfd645d4765e713a2b">455</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2cf4898386fe73bfd645d4765e713a2b">startGroupHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> extraLevels=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3c25f35ecd9dbcbcd1804513473f8683">OutputGenIntf::startGroupHeader</a>,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,extraLevels); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3c25f35ecd9dbcbcd1804513473f8683">OutputGenIntf::startGroupHeader</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a626316953a99d3f5e838a27cd5bd0423">ClassDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aec94d27ae7459f75e56fd19c2653b1a7">ConceptDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#aa3b3cc5ea1e4c508ce1a78633590f2fe">FileDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ed74dd39a7fce0737383a5055efbd18">GroupDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a61998df92e21df36b49f2a09e2d868f4">ModuleDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a4c4bfe146ecd653c8d9ed6b93825bc40">NamespaceDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aaa81776b056239d1cf7f84632a3eb5ae">ConceptDefImpl::writeDefinition</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a629cd8190893fac7ea39aaf6b9c39c17">ClassDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classlinkedrefmap/#aa36e57d8b3b8814f56caff17d0562173">ClassLinkedRefMap::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>.
</div>
</div>

### startHeaderSection() {#a545dcbbbcdf8aac24e32df2abe0ea22d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startHeaderSection ()</td>
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



Definition at line 467 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a545dcbbbcdf8aac24e32df2abe0ea22d">467</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a545dcbbbcdf8aac24e32df2abe0ea22d">startHeaderSection</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#af915369f4ac0e6faeb3d558de0a5ccea">OutputGenIntf::startHeaderSection</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#af915369f4ac0e6faeb3d558de0a5ccea">OutputGenIntf::startHeaderSection</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0ba684cbe3b0eb9eec5629f9618f06e4">startTitle</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.
</div>
</div>

### startInclDepGraph() {#a1d3ded0121b9163ac3b11c0bb8e380c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startInclDepGraph ()</td>
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



Definition at line 654 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d3ded0121b9163ac3b11c0bb8e380c4">654</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1d3ded0121b9163ac3b11c0bb8e380c4">startInclDepGraph</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a8d87cbaafb593cdcbf9b2b98a7dd1f1b">OutputGenIntf::startInclDepGraph</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a8d87cbaafb593cdcbf9b2b98a7dd1f1b">OutputGenIntf::startInclDepGraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>.
</div>
</div>

### startIndent() {#a5805e09c663ccde368463f3c6a767a59}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startIndent ()</td>
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



Definition at line 584 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5805e09c663ccde368463f3c6a767a59">584</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5805e09c663ccde368463f3c6a767a59">startIndent</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3942248646635d62ce76ff4c58501013">OutputGenIntf::startIndent</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3942248646635d62ce76ff4c58501013">OutputGenIntf::startIndent</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>.
</div>
</div>

### startIndexItem() {#a0d0615da54716436c72e53f16b80adfc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startIndexItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file)</td>
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



Definition at line 435 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0d0615da54716436c72e53f16b80adfc">435</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0d0615da54716436c72e53f16b80adfc">startIndexItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ab4fea7fc7613b609e6b63ebe49e2637f">OutputGenIntf::startIndexItem</a>,ref,file); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ab4fea7fc7613b609e6b63ebe49e2637f">OutputGenIntf::startIndexItem</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>.
</div>
</div>

### startIndexKey() {#a193f96c7af956fe9443ffc099fc5cc13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startIndexKey ()</td>
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



Definition at line 423 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a193f96c7af956fe9443ffc099fc5cc13">423</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a193f96c7af956fe9443ffc099fc5cc13">startIndexKey</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a4a2892a4a593cce615ffce7172eabc42">OutputGenIntf::startIndexKey</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a4a2892a4a593cce615ffce7172eabc42">OutputGenIntf::startIndexKey</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>.
</div>
</div>

### startIndexList() {#ace955285a164c7f27f0923986a36cff5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startIndexList ()</td>
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



Definition at line 419 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ace955285a164c7f27f0923986a36cff5">419</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ace955285a164c7f27f0923986a36cff5">startIndexList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a6b2597524bf7275b5af10536cdf49f31">OutputGenIntf::startIndexList</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a6b2597524bf7275b5af10536cdf49f31">OutputGenIntf::startIndexList</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#acbf644aa88ec6940aea9d18c28b69ff0">startIndexHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>.
</div>
</div>

### startIndexListItem() {#adf2df33c38b53c9b95fe003aed5bc222}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startIndexListItem ()</td>
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



Definition at line 415 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adf2df33c38b53c9b95fe003aed5bc222">415</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adf2df33c38b53c9b95fe003aed5bc222">startIndexListItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aff1ac58d5e1754872e65e7a3db6f2241">OutputGenIntf::startIndexListItem</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aff1ac58d5e1754872e65e7a3db6f2241">OutputGenIntf::startIndexListItem</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>.
</div>
</div>

### startIndexSection() {#ae92e8fd973796141115ea4ef0b15cf5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startIndexSection (<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a> is)</td>
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



Definition at line 387 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae92e8fd973796141115ea4ef0b15cf5b">387</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae92e8fd973796141115ea4ef0b15cf5b">startIndexSection</a>(<a href="/web-doxygen/docs/api/files/src/index-h/#ac9172d3ad8c8d0ffee55a44e76d507f7">IndexSection</a> is)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ae869ad0ddcd664eebbedee81ad94e925">OutputGenIntf::startIndexSection</a>,is); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ae869ad0ddcd664eebbedee81ad94e925">OutputGenIntf::startIndexSection</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.
</div>
</div>

### startIndexValue() {#a9ffa966ddc43f8d39e5a1e74a814ebef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startIndexValue (bool b)</td>
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



Definition at line 427 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ffa966ddc43f8d39e5a1e74a814ebef">427</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9ffa966ddc43f8d39e5a1e74a814ebef">startIndexValue</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a7a7025f965ca3fcf915dbf010a4a416a">OutputGenIntf::startIndexValue</a>,b); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a7a7025f965ca3fcf915dbf010a4a416a">OutputGenIntf::startIndexValue</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>.
</div>
</div>

### startInlineHeader() {#a8e3c4abdce2bc3800e782a435db5437f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startInlineHeader ()</td>
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



Definition at line 487 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e3c4abdce2bc3800e782a435db5437f">487</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8e3c4abdce2bc3800e782a435db5437f">startInlineHeader</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a0ccc69fb60f4b835a7eed748a9fea1a6">OutputGenIntf::startInlineHeader</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a0ccc69fb60f4b835a7eed748a9fea1a6">OutputGenIntf::startInlineHeader</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>.
</div>
</div>

### startInlineMemberDoc() {#a4627e1a2c83cf21e9b63b6c9b99e5381}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startInlineMemberDoc ()</td>
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



Definition at line 736 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4627e1a2c83cf21e9b63b6c9b99e5381">736</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4627e1a2c83cf21e9b63b6c9b99e5381">startInlineMemberDoc</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ab46c5f34ec08151ad23e699ec093e858">OutputGenIntf::startInlineMemberDoc</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ab46c5f34ec08151ad23e699ec093e858">OutputGenIntf::startInlineMemberDoc</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>.
</div>
</div>

### startInlineMemberName() {#abd00519713f4249371669240e568d29d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startInlineMemberName ()</td>
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



Definition at line 732 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd00519713f4249371669240e568d29d">732</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abd00519713f4249371669240e568d29d">startInlineMemberName</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">733</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a0776046486af09020f31ee8f87f8c1d0">OutputGenIntf::startInlineMemberName</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a0776046486af09020f31ee8f87f8c1d0">OutputGenIntf::startInlineMemberName</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>.
</div>
</div>

### startInlineMemberType() {#a41ac30b73768699a957c5714e4c347b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startInlineMemberType ()</td>
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



Definition at line 728 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41ac30b73768699a957c5714e4c347b4">728</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a41ac30b73768699a957c5714e4c347b4">startInlineMemberType</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">729</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a6735e2e800ba3e27cd0fb768e78fd1b2">OutputGenIntf::startInlineMemberType</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a6735e2e800ba3e27cd0fb768e78fd1b2">OutputGenIntf::startInlineMemberType</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>.
</div>
</div>

### startItemList() {#a1677b65eb8f01a10b1d767758338a212}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startItemList ()</td>
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



Definition at line 431 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1677b65eb8f01a10b1d767758338a212">431</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1677b65eb8f01a10b1d767758338a212">startItemList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3f8b6ad1e7e50f7fdeb3c69d8f02b6e7">OutputGenIntf::startItemList</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3f8b6ad1e7e50f7fdeb3c69d8f02b6e7">OutputGenIntf::startItemList</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acbf644aa88ec6940aea9d18c28b69ff0">startIndexHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a>.
</div>
</div>

### startItemListItem() {#a77e30e9a84b48907b886e8231dbbc20b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startItemListItem ()</td>
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



Definition at line 459 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a77e30e9a84b48907b886e8231dbbc20b">459</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a77e30e9a84b48907b886e8231dbbc20b">startItemListItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#af2f528b46750b254f7a799fcd6ed28d7">OutputGenIntf::startItemListItem</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#af2f528b46750b254f7a799fcd6ed28d7">OutputGenIntf::startItemListItem</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a>.
</div>
</div>

### startLabels() {#ac8244f86d2d0ccbf7e9b0641f1d3a8f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startLabels ()</td>
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



Definition at line 740 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8244f86d2d0ccbf7e9b0641f1d3a8f6">740</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac8244f86d2d0ccbf7e9b0641f1d3a8f6">startLabels</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ad79d3695d6eef65e69af540fc5e2187f">OutputGenIntf::startLabels</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ad79d3695d6eef65e69af540fc5e2187f">OutputGenIntf::startLabels</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1d6990cbb875b40cb9e658b48ce74dd3">ClassDefImpl::addClassAttributes</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a1caf6a3bfcee91df2dbffda0dd819423">ConceptDefImpl::addConceptAttributes</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#abca12f470cfbae374799e3882affac73">NamespaceDefImpl::addNamespaceAttributes</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### startLocalToc() {#af987cfff8d8cad1bd500f87ad547d0cc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startLocalToc (int level)</td>
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



Definition at line 746 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af987cfff8d8cad1bd500f87ad547d0cc">746</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af987cfff8d8cad1bd500f87ad547d0cc">startLocalToc</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a6b77f3e740d66edde2819141517d8788">OutputGenIntf::startLocalToc</a>,level); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a6b77f3e740d66edde2819141517d8788">OutputGenIntf::startLocalToc</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a>.
</div>
</div>

### startMemberDeclaration() {#a09a4062cfac0ed8f9d3dec4cd42f1aa7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberDeclaration ()</td>
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



Definition at line 571 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a09a4062cfac0ed8f9d3dec4cd42f1aa7">571</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a09a4062cfac0ed8f9d3dec4cd42f1aa7">startMemberDeclaration</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ac38369ad05d7e5584a64b32576dc95e6">OutputGenIntf::startMemberDeclaration</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ac38369ad05d7e5584a64b32576dc95e6">OutputGenIntf::startMemberDeclaration</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a> and <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>.
</div>
</div>

### startMemberDescription() {#a4988f821b416a64d12c7fbc0a4273bba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberDescription (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inheritId=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), bool typ=false)</td>
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



Definition at line 567 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4988f821b416a64d12c7fbc0a4273bba">567</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4988f821b416a64d12c7fbc0a4273bba">startMemberDescription</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inheritId=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> typ = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aef4e50ba3e911eec35461895c2864b7a">OutputGenIntf::startMemberDescription</a>,anchor,inheritId, typ); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aef4e50ba3e911eec35461895c2864b7a">OutputGenIntf::startMemberDescription</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### startMemberDoc() {#a0a9ce398bc0c3a3ef316e0c97cc33ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberDoc (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; clName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; memName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, int memCount, int memTotal, bool showInline)</td>
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



Definition at line 533 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0a9ce398bc0c3a3ef316e0c97cc33ce5">533</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0a9ce398bc0c3a3ef316e0c97cc33ce5">startMemberDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;clName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;memName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> memCount,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> memTotal,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> showInline)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a116232c9975fe8505bf789dd51eadb56">OutputGenIntf::startMemberDoc</a>,clName,memName,anchor,title,memCount,memTotal,showInline); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a116232c9975fe8505bf789dd51eadb56">OutputGenIntf::startMemberDoc</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>.
</div>
</div>

### startMemberDocList() {#ada069f601f0651010bc78b3ccb0f6f11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberDocList ()</td>
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



Definition at line 479 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ada069f601f0651010bc78b3ccb0f6f11">479</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ada069f601f0651010bc78b3ccb0f6f11">startMemberDocList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3cc64b48e08f8c37ae68c052666e2581">OutputGenIntf::startMemberDocList</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3cc64b48e08f8c37ae68c052666e2581">OutputGenIntf::startMemberDocList</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a>.
</div>
</div>

### startMemberDocName() {#a0b9d56f0ab609c25ba0b449e4d977f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberDocName (bool align)</td>
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



Definition at line 682 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b9d56f0ab609c25ba0b449e4d977f80">682</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0b9d56f0ab609c25ba0b449e4d977f80">startMemberDocName</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a1c683042be29f8f10d539f4a01a03237">align</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a45d8c190fc894d6743423e628c19294b">OutputGenIntf::startMemberDocName</a>,<a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a1c683042be29f8f10d539f4a01a03237">align</a>); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/rtfdocvisitor-cpp/#a1c683042be29f8f10d539f4a01a03237">align</a> and <a href="/web-doxygen/docs/api/classes/outputgenintf/#a45d8c190fc894d6743423e628c19294b">OutputGenIntf::startMemberDocName</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>.
</div>
</div>

### startMemberDocPrefixItem() {#acc616cc002e406c1c5816f020fb7d60c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberDocPrefixItem ()</td>
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



Definition at line 678 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc616cc002e406c1c5816f020fb7d60c">678</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acc616cc002e406c1c5816f020fb7d60c">startMemberDocPrefixItem</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a5995a8429533bd21364530edeb763711">OutputGenIntf::startMemberDocPrefixItem</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a5995a8429533bd21364530edeb763711">OutputGenIntf::startMemberDocPrefixItem</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### startMemberDocSimple() {#ac9ba52ac9477c974842dacd16aeb4420}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberDocSimple (bool b)</td>
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



Definition at line 724 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac9ba52ac9477c974842dacd16aeb4420">724</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac9ba52ac9477c974842dacd16aeb4420">startMemberDocSimple</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a0593059cb1552745f7a97a3040dd5e7c">OutputGenIntf::startMemberDocSimple</a>,b); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a0593059cb1552745f7a97a3040dd5e7c">OutputGenIntf::startMemberDocSimple</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a8cab5da1323054e47ede48e03a1420a2">MemberList::writeSimpleDocumentation</a>.
</div>
</div>

### startMemberGroup() {#a6e6c176d640939fce848f044037209c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberGroup ()</td>
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



Definition at line 515 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e6c176d640939fce848f044037209c8">515</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6e6c176d640939fce848f044037209c8">startMemberGroup</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a36689312cd35c431b1ce66ac3ba35594">OutputGenIntf::startMemberGroup</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a36689312cd35c431b1ce66ac3ba35594">OutputGenIntf::startMemberGroup</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### startMemberGroupDocs() {#ac78054f50bad730b62b3456699d9a350}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberGroupDocs ()</td>
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



Definition at line 511 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac78054f50bad730b62b3456699d9a350">511</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac78054f50bad730b62b3456699d9a350">startMemberGroupDocs</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ac57ae72f8115bbe8ed6b303cffb984f7">OutputGenIntf::startMemberGroupDocs</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ac57ae72f8115bbe8ed6b303cffb984f7">OutputGenIntf::startMemberGroupDocs</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### startMemberGroupHeader() {#ae7ca8c46242c727aa527ab392db22707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberGroupHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, bool b)</td>
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



Definition at line 507 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae7ca8c46242c727aa527ab392db22707">507</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae7ca8c46242c727aa527ab392db22707">startMemberGroupHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3593d54f692a41d566ae01109aeef05e">OutputGenIntf::startMemberGroupHeader</a>,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,b); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3593d54f692a41d566ae01109aeef05e">OutputGenIntf::startMemberGroupHeader</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### startMemberHeader() {#af6404ab3a071c87189d8b8dd2f0d2ef1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberHeader (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, int typ=2)</td>
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



Definition at line 471 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af6404ab3a071c87189d8b8dd2f0d2ef1">471</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af6404ab3a071c87189d8b8dd2f0d2ef1">startMemberHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> typ = 2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a38cce7e6f2c721d28cd581fffc261667">OutputGenIntf::startMemberHeader</a>,anchor,typ); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a38cce7e6f2c721d28cd581fffc261667">OutputGenIntf::startMemberHeader</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3e05e32173b1326ae7ef4204bc6557ce">ClassDefImpl::endMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### startMemberItem() {#ad7e741530682b5707eb04b3f4009523d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, <a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">OutputGenerator::MemberItemType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
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



Definition at line 495 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad7e741530682b5707eb04b3f4009523d">495</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad7e741530682b5707eb04b3f4009523d">startMemberItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,<a href="/web-doxygen/docs/api/classes/outputgenerator/#a94f2e5794dffec4be4d53d644f5e4dcb">OutputGenerator::MemberItemType</a> type,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a859d57760dab81918c1f54667a4b7bb6">OutputGenIntf::startMemberItem</a>,anchor,type,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a859d57760dab81918c1f54667a4b7bb6">OutputGenIntf::startMemberItem</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### startMemberList() {#a7431bc4b23642f75af48f25a415d4ec8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberList ()</td>
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



Definition at line 483 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7431bc4b23642f75af48f25a415d4ec8">483</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7431bc4b23642f75af48f25a415d4ec8">startMemberList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#abc21f85b1ee972d5143aa0e10c12a74c">OutputGenIntf::startMemberList</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#abc21f85b1ee972d5143aa0e10c12a74c">OutputGenIntf::startMemberList</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a> and <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>.
</div>
</div>

### startMemberSections() {#a6f8bf0192c18e0ea785c412b23f6fd3f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberSections ()</td>
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



Definition at line 463 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f8bf0192c18e0ea785c412b23f6fd3f">463</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6f8bf0192c18e0ea785c412b23f6fd3f">startMemberSections</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a479613dbc7e8b8967342736b76a00b59">OutputGenIntf::startMemberSections</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a479613dbc7e8b8967342736b76a00b59">OutputGenIntf::startMemberSections</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f36cf07287e24e21caf79ec7824190">ClassDefImpl::startMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a42cf7b3dbeb4be58540ea2e5485fafaf">DirDefImpl::startMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ad669c651d498a449afd9480180fd5118">FileDefImpl::startMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a1d86309d596102676644595bd958243b">GroupDefImpl::startMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a1092f6f7ad206c0c3dde40aaeccafcdc">ModuleDefImpl::startMemberDeclarations</a> and <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a48a607055d5fd28fc8d9147edb150dad">NamespaceDefImpl::startMemberDeclarations</a>.
</div>
</div>

### startMemberSubtitle() {#add8c37a5cb21fb366c941cea862b2285}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberSubtitle ()</td>
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



Definition at line 475 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add8c37a5cb21fb366c941cea862b2285">475</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#add8c37a5cb21fb366c941cea862b2285">startMemberSubtitle</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a47701af94cd5ea03b74733c9d7926251">OutputGenIntf::startMemberSubtitle</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a47701af94cd5ea03b74733c9d7926251">OutputGenIntf::startMemberSubtitle</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>.
</div>
</div>

### startMemberTemplateParams() {#af5a6611d3aa4b11eafd0a785d1757483}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startMemberTemplateParams ()</td>
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



Definition at line 499 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af5a6611d3aa4b11eafd0a785d1757483">499</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af5a6611d3aa4b11eafd0a785d1757483">startMemberTemplateParams</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a84b6535ee5e38767846bea0e6ba96c8a">OutputGenIntf::startMemberTemplateParams</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a84b6535ee5e38767846bea0e6ba96c8a">OutputGenIntf::startMemberTemplateParams</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>.
</div>
</div>

### startPageDoc() {#aba6135c0dcee35b209b1a4996a5763c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startPageDoc (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; pageTitle)</td>
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



Definition at line 624 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aba6135c0dcee35b209b1a4996a5763c1">624</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aba6135c0dcee35b209b1a4996a5763c1">startPageDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;pageTitle)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a2b784e509b334fac1a75627148761be8">OutputGenIntf::startPageDoc</a>, pageTitle); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a2b784e509b334fac1a75627148761be8">OutputGenIntf::startPageDoc</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.
</div>
</div>

### startPageRef() {#a6f14fd99b68f6df4f9510dbc627f5a43}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startPageRef ()</td>
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



Definition at line 600 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f14fd99b68f6df4f9510dbc627f5a43">600</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6f14fd99b68f6df4f9510dbc627f5a43">startPageRef</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ad700dc5ae546c3e60eaf3a0fc821f626">OutputGenIntf::startPageRef</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ad700dc5ae546c3e60eaf3a0fc821f626">OutputGenIntf::startPageRef</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6fbacb46985c69b37200e1302d9f36ef">writePageRef</a>.
</div>
</div>

### startParagraph() {#a583c7e58d6b910b7bdf67120ee4e6875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startParagraph (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; classDef=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
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



Definition at line 409 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a583c7e58d6b910b7bdf67120ee4e6875">409</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a583c7e58d6b910b7bdf67120ee4e6875">startParagraph</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;classDef=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#af0f23248db3a810e3fa1a22efd6dc810">OutputGenIntf::startParagraph</a>,classDef); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#af0f23248db3a810e3fa1a22efd6dc810">OutputGenIntf::startParagraph</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9fc4cfd40097fc38d509676f1f060fad">MemberDefImpl::\_writeCategoryRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aed02fe5ded54336952277d72ed72360d">MemberDefImpl::\_writeGroupInclude</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3bd86295355fd18bd7308c9f598a446a">MemberDefImpl::\_writeReimplementedBy</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad2dcf0394d47fc2228362b4cd0d6109e">MemberDefImpl::\_writeReimplements</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad7028f83d76c5512f951bde8f46e7067">DefinitionImpl::writeSourceDef</a> and <a href="/web-doxygen/docs/api/classes/filedefimpl/#a256a7639e9cfa07c921e0ce19f606a12">FileDefImpl::writeSourceLink</a>.
</div>
</div>

### startParameterDefVal() {#a7350c12854789b59595b4ad1d40a651c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startParameterDefVal (const char * separator)</td>
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



Definition at line 698 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7350c12854789b59595b4ad1d40a651c">698</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7350c12854789b59595b4ad1d40a651c">startParameterDefVal</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *separator)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ad6785e89293e0a1a656cea7f3a11ce0f">OutputGenIntf::startParameterDefVal</a>,separator); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ad6785e89293e0a1a656cea7f3a11ce0f">OutputGenIntf::startParameterDefVal</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>.
</div>
</div>

### startParameterExtra() {#a251c67c01e2bcc17814da33c186bd1f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startParameterExtra ()</td>
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



Definition at line 694 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a251c67c01e2bcc17814da33c186bd1f9">694</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a251c67c01e2bcc17814da33c186bd1f9">startParameterExtra</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aca6ab24e04280715dbb109c2fff18356">OutputGenIntf::startParameterExtra</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aca6ab24e04280715dbb109c2fff18356">OutputGenIntf::startParameterExtra</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>.
</div>
</div>

### startParameterList() {#a297f991eafa9e368a982c936891bb79e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startParameterList (bool openBracket)</td>
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



Definition at line 702 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a297f991eafa9e368a982c936891bb79e">702</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a297f991eafa9e368a982c936891bb79e">startParameterList</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> openBracket)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a8c23f7c0b2fd4ba55c2e5a262a3e3de7">OutputGenIntf::startParameterList</a>,openBracket); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a8c23f7c0b2fd4ba55c2e5a262a3e3de7">OutputGenIntf::startParameterList</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>.
</div>
</div>

### startParameterName() {#acde2fcc0d42034b7f342d12119957a81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startParameterName (bool one)</td>
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



Definition at line 690 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acde2fcc0d42034b7f342d12119957a81">690</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acde2fcc0d42034b7f342d12119957a81">startParameterName</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> one)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a230c27f71a06e4127b602b621f548985">OutputGenIntf::startParameterName</a>,one); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a230c27f71a06e4127b602b621f548985">OutputGenIntf::startParameterName</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>.
</div>
</div>

### startParameterType() {#a8db9e1278341d4eeb45328fd9967a6b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startParameterType (bool first, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
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



Definition at line 686 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8db9e1278341d4eeb45328fd9967a6b5">686</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8db9e1278341d4eeb45328fd9967a6b5">startParameterType</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a1976bdf79e45f6747ef356cae0a95411">OutputGenIntf::startParameterType</a>,first,key); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a1976bdf79e45f6747ef356cae0a95411">OutputGenIntf::startParameterType</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>.
</div>
</div>

### startPlainFile() {#acbe23584d1d25c0df38c01be7b431a90}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startPlainFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 756 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acbe23584d1d25c0df38c01be7b431a90">756</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acbe23584d1d25c0df38c01be7b431a90">startPlainFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a8a3d61c68c3ec0817933b533ced5806a">OutputGenIntf::startPlainFile</a>,name); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a8a3d61c68c3ec0817933b533ced5806a">OutputGenIntf::startPlainFile</a>.
</div>
</div>

### startProjectNumber() {#a5e35c28c310e74b57645aff8119c1546}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startProjectNumber ()</td>
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



Definition at line 393 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e35c28c310e74b57645aff8119c1546">393</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5e35c28c310e74b57645aff8119c1546">startProjectNumber</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a9aa73996eef9d354eda1aa7bef80a92d">OutputGenIntf::startProjectNumber</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a9aa73996eef9d354eda1aa7bef80a92d">OutputGenIntf::startProjectNumber</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/filedefimpl/#ae6e1b872b3bbe57b824a2ce8983f7038">FileDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.
</div>
</div>

### startQuickIndices() {#a74849c1452e8884292ed85bf7c22f2bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startQuickIndices ()</td>
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



Definition at line 604 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74849c1452e8884292ed85bf7c22f2bc">604</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a74849c1452e8884292ed85bf7c22f2bc">startQuickIndices</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a49399b68dc9d396e2decd25c69fe9c71">OutputGenIntf::startQuickIndices</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a49399b68dc9d396e2decd25c69fe9c71">OutputGenIntf::startQuickIndices</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a8183f7413c2945be8d3a2ca7ee4f237f">startFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>.
</div>
</div>

### startSection() {#ae5bcc70f52a38c5c65e7271d18d3e1ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startSection (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; lab, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, <a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> t)</td>
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



Definition at line 588 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5bcc70f52a38c5c65e7271d18d3e1ed">588</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae5bcc70f52a38c5c65e7271d18d3e1ed">startSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;lab,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,<a href="/web-doxygen/docs/api/classes/sectiontype">SectionType</a> t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#adcf099495987baa700a91ebd8284efd2">OutputGenIntf::startSection</a>,lab,title,t); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#adcf099495987baa700a91ebd8284efd2">OutputGenIntf::startSection</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a> and <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a9e4ef930abbc7603896a126a7744b6d9">GroupDefImpl::writePageDocumentation</a>.
</div>
</div>

### startSmall() {#acf8ce762c6c7838d86ad132f20a2306a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startSmall ()</td>
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



Definition at line 557 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acf8ce762c6c7838d86ad132f20a2306a">557</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acf8ce762c6c7838d86ad132f20a2306a">startSmall</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aa535ab26ba3724479354f6944e780f39">OutputGenIntf::startSmall</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aa535ab26ba3724479354f6944e780f39">OutputGenIntf::startSmall</a>.
</div>
</div>

### startTextBlock() {#a5e4b1b0039100083a979ff8d90adce58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startTextBlock (bool dense=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
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



Definition at line 672 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e4b1b0039100083a979ff8d90adce58">672</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5e4b1b0039100083a979ff8d90adce58">startTextBlock</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> dense=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#af2409cde2f7961ca5cf4b967335c5f50">OutputGenIntf::startTextBlock</a>,dense); }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="/web-doxygen/docs/api/classes/outputgenintf/#af2409cde2f7961ca5cf4b967335c5f50">OutputGenIntf::startTextBlock</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a9e4ef930abbc7603896a126a7744b6d9">GroupDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>.
</div>
</div>

### startTextLink() {#af084d8a76621939675ae543f47032fa4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startTextLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
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



Definition at line 444 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af084d8a76621939675ae543f47032fa4">444</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af084d8a76621939675ae543f47032fa4">startTextLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a075de9b4d65864892a5a4bea2ae751dd">OutputGenIntf::startTextLink</a>,file,anchor); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a075de9b4d65864892a5a4bea2ae751dd">OutputGenIntf::startTextLink</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7889cc7de4a08e7cdeeda1e7154604a4">ClassDefImpl::writeMoreLink</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac39050ca48c90714a35d99e9bd53c967">FileDefImpl::writeSourceHeader</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a256a7639e9cfa07c921e0ce19f606a12">FileDefImpl::writeSourceLink</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>.
</div>
</div>

### startTitleHead() {#a218206d83bfa847f783bf2d2346caac6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startTitleHead (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
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



Definition at line 405 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a218206d83bfa847f783bf2d2346caac6">405</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a218206d83bfa847f783bf2d2346caac6">startTitleHead</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a39e6e6ec7f39f8847632b75dfa5490a9">OutputGenIntf::startTitleHead</a>,fileName); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a39e6e6ec7f39f8847632b75dfa5490a9">OutputGenIntf::startTitleHead</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0ba684cbe3b0eb9eec5629f9618f06e4">startTitle</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>.
</div>
</div>

### startTocEntry() {#a132bb85c7da750fadfa35352227b8766}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startTocEntry (const <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> * si)</td>
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



Definition at line 750 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a132bb85c7da750fadfa35352227b8766">750</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a132bb85c7da750fadfa35352227b8766">startTocEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/sectioninfo">SectionInfo</a> *si)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#af1602bf413b97f22052cf036643f3f1c">OutputGenIntf::startTocEntry</a>,si); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#af1602bf413b97f22052cf036643f3f1c">OutputGenIntf::startTocEntry</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a>.
</div>
</div>

### startTypewriter() {#a848e77a8fd7af578497f7ee1ec163b98}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::startTypewriter ()</td>
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



Definition at line 451 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a848e77a8fd7af578497f7ee1ec163b98">451</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a848e77a8fd7af578497f7ee1ec163b98">startTypewriter</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a8d12471e1fa0455d4957b72f25c64302">OutputGenIntf::startTypewriter</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a8d12471e1fa0455d4957b72f25c64302">OutputGenIntf::startTypewriter</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aed02fe5ded54336952277d72ed72360d">MemberDefImpl::\_writeGroupInclude</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#aa1221bfb5b21c047427a269f0caef930">writeInheritanceSpecifier</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>.
</div>
</div>

### writeAnchor() {#aa14aecc6d7bfdeb2cfbd241fa55059a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeAnchor (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 525 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa14aecc6d7bfdeb2cfbd241fa55059a7">525</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa14aecc6d7bfdeb2cfbd241fa55059a7">writeAnchor</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#afda0d70c12b2ac6fc6e66a4543b19a44">OutputGenIntf::writeAnchor</a>,fileName,name); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#afda0d70c12b2ac6fc6e66a4543b19a44">OutputGenIntf::writeAnchor</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a629cd8190893fac7ea39aaf6b9c39c17">ClassDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>.
</div>
</div>

### writeChar() {#a188c7a8f0a0dc35ec5ea0f8b4a491d33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeChar (char c)</td>
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



Definition at line 531 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a188c7a8f0a0dc35ec5ea0f8b4a491d33">531</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a188c7a8f0a0dc35ec5ea0f8b4a491d33">writeChar</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ab3b1f57669e3d916ca995a880935a6df">OutputGenIntf::writeChar</a>,c); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ab3b1f57669e3d916ca995a880935a6df">OutputGenIntf::writeChar</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a>.
</div>
</div>

### writeDoc() {#a475da5dda736fa915aca9fc855b1d2e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeDoc (const <a href="/web-doxygen/docs/api/classes/idocnodeast">IDocNodeAST</a> * ast, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * ctx, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md)</td>
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



Definition at line 385 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a475da5dda736fa915aca9fc855b1d2e7">385</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a475da5dda736fa915aca9fc855b1d2e7">writeDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/idocnodeast">IDocNodeAST</a> *ast,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *ctx,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#abbad8b45e48b0d0dd8139c9c5ce5e74d">OutputGenIntf::writeDoc</a>,ast,ctx,md,<a href="#a81b1124e7c81f2a183262222801460a8">m_id</a>); }</span></span></div>

</div>


References <a href="#a81b1124e7c81f2a183262222801460a8">m\_id</a> and <a href="/web-doxygen/docs/api/classes/outputgenintf/#abbad8b45e48b0d0dd8139c9c5ce5e74d">OutputGenIntf::writeDoc</a>.

Referenced by <a href="#ac371cebadb37ea8ab3ae59502036c427">generateDoc</a>, <a href="#adfdcf2ba925f05be8beb8cf43deb168a">parseText</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>.
</div>
</div>

### writeFooter() {#accf02a25e4bb1593eabc248373f08dd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeFooter (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; navPath)</td>
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



Definition at line 401 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#accf02a25e4bb1593eabc248373f08dd0">401</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#accf02a25e4bb1593eabc248373f08dd0">writeFooter</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;navPath)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ae06d07286c1a5e0e8dd4dcb413eea3ee">OutputGenIntf::writeFooter</a>,navPath); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ae06d07286c1a5e0e8dd4dcb413eea3ee">OutputGenIntf::writeFooter</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f65138605aced4e557cefaebba93625">endFile</a>.
</div>
</div>

### writeGraphicalHierarchy() {#a4d7e7f24d5fd2e4fc7cb62f992a7f10f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeGraphicalHierarchy (<a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable">DotGfxHierarchyTable</a> &amp; g)</td>
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



Definition at line 670 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4d7e7f24d5fd2e4fc7cb62f992a7f10f">670</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4d7e7f24d5fd2e4fc7cb62f992a7f10f">writeGraphicalHierarchy</a>(<a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable">DotGfxHierarchyTable</a> &amp;g)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3eac8c3de9fb5faac26a15e461441ac5">OutputGenIntf::writeGraphicalHierarchy</a>,g); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3eac8c3de9fb5faac26a15e461441ac5">OutputGenIntf::writeGraphicalHierarchy</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>.
</div>
</div>

### writeInheritedSectionTitle() {#ae60261a39e2cc0d6fa5d78da1ae5caeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeInheritedSectionTitle (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 575 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae60261a39e2cc0d6fa5d78da1ae5caeb">575</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae60261a39e2cc0d6fa5d78da1ae5caeb">writeInheritedSectionTitle</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aec93094d1142185397b89f683e3f805c">OutputGenIntf::writeInheritedSectionTitle</a>,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,ref,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">                                    file,anchor,title,name); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aec93094d1142185397b89f683e3f805c">OutputGenIntf::writeInheritedSectionTitle</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>.
</div>
</div>

### writeLabel() {#ac700283b8e771ab0dd515d5f384632ff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeLabel (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; l, bool isLast)</td>
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



Definition at line 742 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac700283b8e771ab0dd515d5f384632ff">742</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac700283b8e771ab0dd515d5f384632ff">writeLabel</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;l,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isLast)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a272adadd57275dc0ffe350691531eca4">OutputGenIntf::writeLabel</a>,l,isLast); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a272adadd57275dc0ffe350691531eca4">OutputGenIntf::writeLabel</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1d6990cbb875b40cb9e658b48ce74dd3">ClassDefImpl::addClassAttributes</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a1caf6a3bfcee91df2dbffda0dd819423">ConceptDefImpl::addConceptAttributes</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#abca12f470cfbae374799e3882affac73">NamespaceDefImpl::addNamespaceAttributes</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### writeLatexSpacing() {#a2a7a1bca5871c912848bddde9b7dd3fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeLatexSpacing ()</td>
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



Definition at line 547 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a7a1bca5871c912848bddde9b7dd3fc">547</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2a7a1bca5871c912848bddde9b7dd3fc">writeLatexSpacing</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a6ffbea116a5c5bf0c54b43ba3f6a4132">OutputGenIntf::writeLatexSpacing</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a6ffbea116a5c5bf0c54b43ba3f6a4132">OutputGenIntf::writeLatexSpacing</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>.
</div>
</div>

### writeLogo() {#a739eb036549fb3787e5daa3d35bc1aff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeLogo ()</td>
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



Definition at line 612 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a739eb036549fb3787e5daa3d35bc1aff">612</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a739eb036549fb3787e5daa3d35bc1aff">writeLogo</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ac9673da2d9860875be433aa9885da80d">OutputGenIntf::writeLogo</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ac9673da2d9860875be433aa9885da80d">OutputGenIntf::writeLogo</a>.
</div>
</div>

### writeNavigationPath() {#ace864e843eca954efb12af825f56bdca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeNavigationPath (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



Definition at line 610 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ace864e843eca954efb12af825f56bdca">610</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ace864e843eca954efb12af825f56bdca">writeNavigationPath</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ab93da7f6e4680d6426a444871a0dd272">OutputGenIntf::writeNavigationPath</a>,s); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ab93da7f6e4680d6426a444871a0dd272">OutputGenIntf::writeNavigationPath</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a508df5a7f2de2d0418f81d08b1fb40f7">DefinitionImpl::writeNavigationPath</a>.
</div>
</div>

### writeNonBreakableSpace() {#ae6cc078977edd1e2a5ae2cf6ed64ed35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeNonBreakableSpace (int num)</td>
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



Definition at line 628 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6cc078977edd1e2a5ae2cf6ed64ed35">628</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae6cc078977edd1e2a5ae2cf6ed64ed35">writeNonBreakableSpace</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> num)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#ac7523bc031627d3ffec3a61be2183983">OutputGenIntf::writeNonBreakableSpace</a>,num); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#ac7523bc031627d3ffec3a61be2183983">OutputGenIntf::writeNonBreakableSpace</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a> and <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>.
</div>
</div>

### writeObjectLink() {#a411807a84d5f9e2fb716a0f66bde56b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeObjectLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 441 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a411807a84d5f9e2fb716a0f66bde56b6">441</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a411807a84d5f9e2fb716a0f66bde56b6">writeObjectLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a53380f84190045f14ef3c6ae2f5dd275">OutputGenIntf::writeObjectLink</a>,ref,file,anchor,name); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a53380f84190045f14ef3c6ae2f5dd275">OutputGenIntf::writeObjectLink</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9fc4cfd40097fc38d509676f1f060fad">MemberDefImpl::\_writeCategoryRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aed02fe5ded54336952277d72ed72360d">MemberDefImpl::\_writeGroupInclude</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3bd86295355fd18bd7308c9f598a446a">MemberDefImpl::\_writeReimplementedBy</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ad2dcf0394d47fc2228362b4cd0d6109e">MemberDefImpl::\_writeReimplements</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a54cbf7f6b07bc8fe4ce7295e534c844f">generateFileRef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a44044c70833211203ece26ccb6c56a5c">recursivelyAddGroupListToTitle</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab1ec5ab1220e68ad6313166e9ac79378">writeClassLinkForMember</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a6e1ed35b84f6375897482fc8b753affd">ClassDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af3e55e24323797042e532d5ab5cbfce9">writeExamples</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a720a2761163764ce53aff1186ad9bfb3">writeFileLinkForMember</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#acb75f1220490ed9d0cce2344fc25bc96">ClassDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a13b863cddb2d53345fcc53835249bad9">ConceptDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af6f9b93ecb1822874f1e05f448798516">MemberDefImpl::writeLink</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a5e22c140f692291551eb95a7e1867b8f">writeLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac6b9d1199e7d38e674f28253098abc0e">writeModuleLinkForMember</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c10dc89e478b9f6f343c8def01c5238">writeNamespaceLinkForMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a8bb54d0765a6b45bf091337783b4680a">writePartialDirPath</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a50a5ca2a633e8e9e98f1fdb284b96186">writePartialFilePath</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ad7028f83d76c5512f951bde8f46e7067">DefinitionImpl::writeSourceDef</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a6e37fa3f47b3d836813a1cf2a7fef036">VhdlDocGen::writeVhdlLink</a>.
</div>
</div>

### writePageLink() {#ad1ce4ae7803aba4c58764c906e943aab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writePageLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, bool first)</td>
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



Definition at line 391 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad1ce4ae7803aba4c58764c906e943aab">391</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad1ce4ae7803aba4c58764c906e943aab">writePageLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a85839f2257cc6632c3307df7f1c48cd4">OutputGenIntf::writePageLink</a>,name,first); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a85839f2257cc6632c3307df7f1c48cd4">OutputGenIntf::writePageLink</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>.
</div>
</div>

### writePageOutline() {#abbe1d0534295cfb5717a33e1c1eb5fb4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writePageOutline ()</td>
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



Definition at line 618 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abbe1d0534295cfb5717a33e1c1eb5fb4">618</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abbe1d0534295cfb5717a33e1c1eb5fb4">writePageOutline</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3253ebaf15e52566edf6b5804ed0e930">OutputGenIntf::writePageOutline</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3253ebaf15e52566edf6b5804ed0e930">OutputGenIntf::writePageOutline</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a063fd8050d2a77ed7bf2362300d8a68a">ClassDefImpl::writePageNavigation</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a592796c472569289a982526d61306572">DirDefImpl::writePageNavigation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#abcf29bb1fb99c67c1420ccaf5c108766">FileDefImpl::writePageNavigation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#abe9c6695d3352937fc93f04fd6ae7030">GroupDefImpl::writePageNavigation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ae240ade7e621441943e08e3f1175e873">ModuleDefImpl::writePageNavigation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ad9cdf00aff85c0e208d37619b20ca0f8">NamespaceDefImpl::writePageNavigation</a> and <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a927e0b1480148a8a6a1c7d7e6a987682">PageDefImpl::writePageNavigation</a>.
</div>
</div>

### writeQuickLinks() {#afc0312b9a48cae61656b930d878c718e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeQuickLinks (<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09">HighlightedItem</a> hli, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, bool extraTabs=false)</td>
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



Definition at line 614 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afc0312b9a48cae61656b930d878c718e">614</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afc0312b9a48cae61656b930d878c718e">writeQuickLinks</a>(<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09">HighlightedItem</a> hli,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> extraTabs=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#abeaa883814a4981f89c3383a1dac404b">OutputGenIntf::writeQuickLinks</a>,hli,file,extraTabs); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#abeaa883814a4981f89c3383a1dac404b">OutputGenIntf::writeQuickLinks</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a8183f7413c2945be8d3a2ca7ee4f237f">startFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>.
</div>
</div>

### writeRuler() {#a2203589f0bc276cb3ba01f529b9536a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeRuler ()</td>
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



Definition at line 523 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2203589f0bc276cb3ba01f529b9536a9">523</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2203589f0bc276cb3ba01f529b9536a9">writeRuler</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a3e67a4680207146c0717f53e778ad83e">OutputGenIntf::writeRuler</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a3e67a4680207146c0717f53e778ad83e">OutputGenIntf::writeRuler</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a629cd8190893fac7ea39aaf6b9c39c17">ClassDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classlinkedrefmap/#aa36e57d8b3b8814f56caff17d0562173">ClassLinkedRefMap::writeDocumentation</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#aa86fa71c504d7676073931dcca08f3dc">MemberList::writeDocumentation</a>.
</div>
</div>

### writeSearchInfo() {#a0b776a7ac371d841b15862b074ddd97f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeSearchInfo ()</td>
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



Definition at line 399 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b776a7ac371d841b15862b074ddd97f">399</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0b776a7ac371d841b15862b074ddd97f">writeSearchInfo</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a06d7c1c55247348a93966711afbb983f">OutputGenIntf::writeSearchInfo</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a06d7c1c55247348a93966711afbb983f">OutputGenIntf::writeSearchInfo</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a8183f7413c2945be8d3a2ca7ee4f237f">startFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>.
</div>
</div>

### writeSplitBar() {#abeb86db48415009b3c09b723216fd8f6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeSplitBar (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; allMembersFile)</td>
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



Definition at line 608 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abeb86db48415009b3c09b723216fd8f6">608</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abeb86db48415009b3c09b723216fd8f6">writeSplitBar</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;allMembersFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#aaa7b661bcbc35895bd704e48999c3849">OutputGenIntf::writeSplitBar</a>,name,allMembersFile); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#aaa7b661bcbc35895bd704e48999c3849">OutputGenIntf::writeSplitBar</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/index-cpp/#a8183f7413c2945be8d3a2ca7ee4f237f">startFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>.
</div>
</div>

### writeStartAnnoItem() {#a4e97c1da93e9caf6a6675f3972ba7750}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeStartAnnoItem (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; path, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 448 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4e97c1da93e9caf6a6675f3972ba7750">448</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4e97c1da93e9caf6a6675f3972ba7750">writeStartAnnoItem</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;type,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#afd391f13f33ee9163d495756f978447b">OutputGenIntf::writeStartAnnoItem</a>,type,file,path,name); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#afd391f13f33ee9163d495756f978447b">OutputGenIntf::writeStartAnnoItem</a>.
</div>
</div>

### writeString() {#a07cac8a8981da35314f77d8f3edb7f76}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



Definition at line 413 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07cac8a8981da35314f77d8f3edb7f76">413</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a9425335496ccadd1a9c8235cf31280e1">OutputGenIntf::writeString</a>,text); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a9425335496ccadd1a9c8235cf31280e1">OutputGenIntf::writeString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f65138605aced4e557cefaebba93625">endFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac1850678fe273e83bcda397bc2f1b6ec">endFileWithNavPath</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a83614d4e01cc805780c657669fbcadc2">endQuickIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a358dfd1bd00b33031d7316660055c845">endQuickIndexList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a44044c70833211203ece26ccb6c56a5c">recursivelyAddGroupListToTitle</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3f2bca76c821f2cde122ebb419a84cce">startQuickIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af8bc25cc45d1e7d47e21293e99142fbf">startQuickIndexList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a626316953a99d3f5e838a27cd5bd0423">ClassDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab1ec5ab1220e68ad6313166e9ac79378">writeClassLinkForMember</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0ac2f4932405d6a1773bea6eb84885ec">VhdlDocGen::writeClassType</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>, <a href="/web-doxygen/docs/api/classes/dirrelation/#a5fa861050993dafb351589f2f1c05326">DirRelation::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a301d6ac11841a0bf0b420e8c47d402a5">ModuleDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af29c795d264e74de8cc53f3d5c550d41">MemberList::writeDocumentationPage</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae05ef36cc6c568d03ba57257a7b45f34">MemberDefImpl::writeEnumDeclaration</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af3e55e24323797042e532d5ab5cbfce9">writeExamples</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a720a2761163764ce53aff1186ad9bfb3">writeFileLinkForMember</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac6b9d1199e7d38e674f28253098abc0e">writeModuleLinkForMember</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7889cc7de4a08e7cdeeda1e7154604a4">ClassDefImpl::writeMoreLink</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c10dc89e478b9f6f343c8def01c5238">writeNamespaceLinkForMember</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4358eda73696cdd5f09ea53b317f4eee">writePageIndex</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a8bb54d0765a6b45bf091337783b4680a">writePartialDirPath</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a50a5ca2a633e8e9e98f1fdb284b96186">writePartialFilePath</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac17987f390e01a05dd8a3c12feae991a">writeQuickMemberIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7fc4c3be9e48561ac4ee240aad2ef9d7">ClassDefImpl::writeQuickMemberLinks</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a1a445a6846a5e319177416889de34b22">FileDefImpl::writeQuickMemberLinks</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#adaef3a5a029e5c72d9ef735d95c706ce">GroupDefImpl::writeQuickMemberLinks</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a0828a0da96f45ed4b4ba3103121e5134">NamespaceDefImpl::writeQuickMemberLinks</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac39050ca48c90714a35d99e9bd53c967">FileDefImpl::writeSourceHeader</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad28ce13d37a783efc856e85b0cdb791c">ClassDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a26fe21b32c7e96c3c50f8cfd2e06e89f">FileDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a1cd6f5eb27ef6ca1ded4532bd38323b0">GroupDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad9a159e7a8e4ed36a862252a284e0d24">ModuleDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#af7fd110aa3bb86ad68c64ff39239d8fd">NamespaceDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a1f76f36afd77f874d16385ffbe83e1c8">writeUCFLink</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f6b3206f3da0ef3b4135d8a9dc41456">writeUserGroupStubPage</a>.
</div>
</div>

### writeStyleInfo() {#a85fc0afe789c21758373df15bcb81cc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeStyleInfo (int part)</td>
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



Definition at line 397 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85fc0afe789c21758373df15bcb81cc9">397</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a85fc0afe789c21758373df15bcb81cc9">writeStyleInfo</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> part)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a2711a39698d7169932b7e24b9223ef06">OutputGenIntf::writeStyleInfo</a>,part); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a2711a39698d7169932b7e24b9223ef06">OutputGenIntf::writeStyleInfo</a>.
</div>
</div>

### writeSummaryLink() {#a956032c76c8c263139658a08dfe1e07f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeSummaryLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, bool first)</td>
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



Definition at line 616 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a956032c76c8c263139658a08dfe1e07f">616</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a956032c76c8c263139658a08dfe1e07f">writeSummaryLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> first)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a08a84ef9ad423d5893da62114366f71b">OutputGenIntf::writeSummaryLink</a>,file,anchor,title,first); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a08a84ef9ad423d5893da62114366f71b">OutputGenIntf::writeSummaryLink</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad28ce13d37a783efc856e85b0cdb791c">ClassDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a26fe21b32c7e96c3c50f8cfd2e06e89f">FileDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a1cd6f5eb27ef6ca1ded4532bd38323b0">GroupDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad9a159e7a8e4ed36a862252a284e0d24">ModuleDefImpl::writeSummaryLinks</a> and <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#af7fd110aa3bb86ad68c64ff39239d8fd">NamespaceDefImpl::writeSummaryLinks</a>.
</div>
</div>

### writeSynopsis() {#a7d9096a6b81f3183e6f3dc01e4e093f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::writeSynopsis ()</td>
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



Definition at line 594 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d9096a6b81f3183e6f3dc01e4e093f5">594</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7d9096a6b81f3183e6f3dc01e4e093f5">writeSynopsis</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">    { </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(&amp;<a href="/web-doxygen/docs/api/classes/outputgenintf/#a6dc8d2bf34bb5f53b758cbcac0074e3c">OutputGenIntf::writeSynopsis</a>); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/outputgenintf/#a6dc8d2bf34bb5f53b758cbcac0074e3c">OutputGenIntf::writeSynopsis</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a> and <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### foreach() {#ae46bbb0266c94292eca9408c224f1eb3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;class... Ts, class... As&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::foreach (void(OutputGenIntf::*)(Ts...) methodPtr, As &amp;&amp;... args)</td>
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



Definition at line 767 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae46bbb0266c94292eca9408c224f1eb3">767</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">foreach</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/outputgenintf">OutputGenIntf</a>::*methodPtr)(Ts...),As&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e.enabled)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">          (e.intf.get()-&gt;*methodPtr)(std::forward&lt;As&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a>.
</div>
</div>

### newId() {#a67839ba61ba53161ae6c0ff75029e6ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::newId ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 762 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67839ba61ba53161ae6c0ff75029e6ab">71</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a67839ba61ba53161ae6c0ff75029e6ab">OutputList::newId</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a81b1124e7c81f2a183262222801460a8">m_id</a> = ++<a href="/web-doxygen/docs/api/files/src/outputlist-cpp/#af6d0e999d586b2601df53817d960fbd2">g_outId</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/outputlist-cpp/#af6d0e999d586b2601df53817d960fbd2">g\_outId</a> and <a href="#a81b1124e7c81f2a183262222801460a8">m\_id</a>.

Referenced by <a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList</a> and <a href="#a518814a98f44c11f73dbea3b7b3ed795">startFile</a>.
</div>
</div>

### refreshCodeGenerators() {#ae02018298c4bb64b600a8d0225a31302}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::refreshCodeGenerators ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 764 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae02018298c4bb64b600a8d0225a31302">61</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae02018298c4bb64b600a8d0225a31302">OutputList::refreshCodeGenerators</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m_codeGenList</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">    e.intf-&gt;addCodeGen(<a href="#a1d563c5f1a2af94aef565f881aefe5f2">m_codeGenList</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m_codeGenList</a>.setId(<a href="#a81b1124e7c81f2a183262222801460a8">m_id</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m\_codeGenList</a>, <a href="#a81b1124e7c81f2a183262222801460a8">m\_id</a> and <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a>.

Referenced by <a href="#a2ffd4b500e651b8ec1a47acb46e2456c">add</a>, <a href="#a4d5653dcc37e333f00ce357d2440fe6e">operator=</a> and <a href="#af39f7d4abc52b7b869bfb783fcac7315">OutputList</a>.
</div>
</div>

### syncEnabled() {#a7e64f80c1f7666a7dae398841d7eb03a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void OutputList::syncEnabled ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 763 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>, definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7e64f80c1f7666a7dae398841d7eb03a">76</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7e64f80c1f7666a7dae398841d7eb03a">OutputList::syncEnabled</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;e : <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("output %d isEnabled=%d\n",og-&gt;type(),og-&gt;isEnabled());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m_codeGenList</a>.setEnabledFiltered(e.intf-&gt;type(),e.enabled);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m\_codeGenList</a> and <a href="#a364810832675cec0a041288594b2251e">m\_outputGenList</a>.

Referenced by <a href="#a192e28bf96098f41db170be0680d5375">disable</a>, <a href="#a6a75284d21a037302ea3d7dc6e1558d4">disableAll</a>, <a href="#a91f9afddff1974d7805c3d022b754ddf">disableAllBut</a>, <a href="#a306f5cfd7c296b5a52160343d9631916">enable</a>, <a href="#ad32603ff4c4ba4d39e0bad7ede5924bf">enableAll</a>, <a href="#a94eb1af2ea07425ef1faa539d24adcf8">popGeneratorState</a> and <a href="#a885957a64f7d87aefb663c4ec903188f">pushGeneratorState</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_codeGenList {#a1d563c5f1a2af94aef565f881aefe5f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputCodeList OutputList::m_codeGenList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 779 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d563c5f1a2af94aef565f881aefe5f2">779</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> <a href="#a1d563c5f1a2af94aef565f881aefe5f2">m_codeGenList</a>;</span></span></div>

</div>


Referenced by <a href="#a4700ac2ba9ae6445eb7f862502472f35">codeGenerators</a>, <a href="#a284458e4baf27869eb5bbb9776407e6c">codeGenerators</a>, <a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList</a>, <a href="#ae02018298c4bb64b600a8d0225a31302">refreshCodeGenerators</a>, <a href="#a518814a98f44c11f73dbea3b7b3ed795">startFile</a> and <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>.
</div>
</div>

### m\_id {#a81b1124e7c81f2a183262222801460a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int OutputList::m_id</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 780 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81b1124e7c81f2a183262222801460a8">780</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a81b1124e7c81f2a183262222801460a8">m_id</a>;</span></span></div>

</div>


Referenced by <a href="#a67839ba61ba53161ae6c0ff75029e6ab">newId</a>, <a href="#a4d5653dcc37e333f00ce357d2440fe6e">operator=</a>, <a href="#a9c57688bca34e8437f691c7c0a6fae3e">OutputList</a>, <a href="#af39f7d4abc52b7b869bfb783fcac7315">OutputList</a>, <a href="#ae02018298c4bb64b600a8d0225a31302">refreshCodeGenerators</a>, <a href="#a518814a98f44c11f73dbea3b7b3ed795">startFile</a> and <a href="#a475da5dda736fa915aca9fc855b1d2e7">writeDoc</a>.
</div>
</div>

### m\_outputGenList {#a364810832675cec0a041288594b2251e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;OutputGenElem&gt; OutputList::m_outputGenList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 778 of file <a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a364810832675cec0a041288594b2251e">778</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;OutputGenElem&gt; <a href="#a364810832675cec0a041288594b2251e">m_outputGenList</a>;</span></span></div>

</div>


Referenced by <a href="#a2ffd4b500e651b8ec1a47acb46e2456c">add</a>, <a href="#a192e28bf96098f41db170be0680d5375">disable</a>, <a href="#a6a75284d21a037302ea3d7dc6e1558d4">disableAll</a>, <a href="#a91f9afddff1974d7805c3d022b754ddf">disableAllBut</a>, <a href="#a306f5cfd7c296b5a52160343d9631916">enable</a>, <a href="#ad32603ff4c4ba4d39e0bad7ede5924bf">enableAll</a>, <a href="#ae46bbb0266c94292eca9408c224f1eb3">foreach</a>, <a href="#ac371cebadb37ea8ab3ae59502036c427">generateDoc</a>, <a href="#a046bd3dcc4d8e2cc12821fba1394d818">isEnabled</a>, <a href="#a4d5653dcc37e333f00ce357d2440fe6e">operator=</a>, <a href="#af39f7d4abc52b7b869bfb783fcac7315">OutputList</a>, <a href="#adfdcf2ba925f05be8beb8cf43deb168a">parseText</a>, <a href="#a94eb1af2ea07425ef1faa539d24adcf8">popGeneratorState</a>, <a href="#a885957a64f7d87aefb663c4ec903188f">pushGeneratorState</a>, <a href="#ae02018298c4bb64b600a8d0225a31302">refreshCodeGenerators</a>, <a href="#a38c3477fea42348693927abc9b16d209">size</a> and <a href="#a7e64f80c1f7666a7dae398841d7eb03a">syncEnabled</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/outputlist-cpp">outputlist.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
