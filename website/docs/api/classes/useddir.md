---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/useddir
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `UsedDir` Class Reference

<p>Usage information of a directory. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class UsedDir { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dirdef-h">src/dirdef.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab39375942f8340b04bbd3c471e52f6fb">UsedDir</a> (const DirDef *dir)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9944cb27f5ddd2a96b8f0c49bd744e49">addFileDep</a> (const FileDef *srcFd, const FileDef *dstFd, bool srcDirect, bool dstDirect)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Take up dependency between files. <a href="#a9944cb27f5ddd2a96b8f0c49bd744e49">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filepair">FilePair</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add0da96fe9168b96abed52d016b621b2">findFilePair</a> (const QCString &amp;name)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/filepairlinkedmap">FilePairLinkedMap</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae451dc891c59da794d54796d1002bd64">filePairs</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f9871ef38cb735feebfe0b338ca4e2c">dir</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac811027be125869ba23da94b5dd631c2">hasDirectDeps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff any of the dependencies between source and destination files are direct (i.e. <a href="#ac811027be125869ba23da94b5dd631c2">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac799f97624a4a2a3d6698ef82f969591">hasDirectSrcDeps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff any of the dependencies from the source file to the destination file are directly coming from a file in the source directory (i.e. <a href="#ac799f97624a4a2a3d6698ef82f969591">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6620a736948a61103b4281aef2a2d59c">hasDirectDstDeps</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff any of the dependencies from the source file to the destination file are directly targeting a file in the destination directory (i.e. <a href="#a6620a736948a61103b4281aef2a2d59c">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24c2c709540ee61b987ae5b80d0b4ec3">sort</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af03eac45e535a65d1d19ae3472503f31">m_dir</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filepairlinkedmap">FilePairLinkedMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">m_filePairs</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c178a62064746363c8914dc0fff9df9">m_hasDirectDeps</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae6af50543bb0ee6b75d2318c3ad5c17e">m_hasDirectSrcDeps</a> = false</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f3ef45db59856e42bbc150c837e6106">m_hasDirectDstDeps</a> = false</td>
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

<p>Usage information of a directory.</p>

<p>Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### UsedDir() {#ab39375942f8340b04bbd3c471e52f6fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UsedDir::UsedDir (const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> * dir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>, definition at line 815 of file <a href="/web-doxygen/docs/api/files/src/dirdef-cpp">dirdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab39375942f8340b04bbd3c471e52f6fb">815</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ab39375942f8340b04bbd3c471e52f6fb">UsedDir::UsedDir</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *<a href="#a9f9871ef38cb735feebfe0b338ca4e2c">dir</a>) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#af03eac45e535a65d1d19ae3472503f31">m_dir</a>(<a href="#a9f9871ef38cb735feebfe0b338ca4e2c">dir</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a9f9871ef38cb735feebfe0b338ca4e2c">dir</a> and <a href="#af03eac45e535a65d1d19ae3472503f31">m_dir</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addFileDep() {#a9944cb27f5ddd2a96b8f0c49bd744e49}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UsedDir::addFileDep (const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * srcFd, const <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> * dstFd, bool srcDirect, bool dstDirect)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>Take up dependency between files.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] srcFd</td>
<td class="doxyParamItemDescription"><p>dependent file which depends on dstFd</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] dstFd</td>
<td class="doxyParamItemDescription"><p>dependee file on which srcFd depends on</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] srcDirect</td>
<td class="doxyParamItemDescription"><p>true iff the source dependency was the direct (not inherited from a sub dir)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] dstDirect</td>
<td class="doxyParamItemDescription"><p>true iff the destination dependency was direct (not inherited from a sub dir)</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 75 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>, definition at line 820 of file <a href="/web-doxygen/docs/api/files/src/dirdef-cpp">dirdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9944cb27f5ddd2a96b8f0c49bd744e49">820</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9944cb27f5ddd2a96b8f0c49bd744e49">UsedDir::addFileDep</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *srcFd,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filedef">FileDef</a> *dstFd, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> srcDirect, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> dstDirect)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">m_filePairs</a>.add(<a href="/web-doxygen/docs/api/classes/filepair/#a4fa66c88e9e7ecd2ad19da2ee00e7808">FilePair::key</a>(srcFd,dstFd),std::make_unique&lt;FilePair&gt;(srcFd,dstFd));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a6c178a62064746363c8914dc0fff9df9">m_hasDirectDeps</a>    = <a href="#a6c178a62064746363c8914dc0fff9df9">m_hasDirectDeps</a>    || (srcDirect &amp;&amp; dstDirect);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ae6af50543bb0ee6b75d2318c3ad5c17e">m_hasDirectSrcDeps</a> = <a href="#ae6af50543bb0ee6b75d2318c3ad5c17e">m_hasDirectSrcDeps</a> || srcDirect;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0f3ef45db59856e42bbc150c837e6106">m_hasDirectDstDeps</a> = <a href="#a0f3ef45db59856e42bbc150c837e6106">m_hasDirectDstDeps</a> || dstDirect;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/filepair/#a4fa66c88e9e7ecd2ad19da2ee00e7808">FilePair::key</a>, <a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">m_filePairs</a>, <a href="#a6c178a62064746363c8914dc0fff9df9">m_hasDirectDeps</a>, <a href="#a0f3ef45db59856e42bbc150c837e6106">m_hasDirectDstDeps</a> and <a href="#ae6af50543bb0ee6b75d2318c3ad5c17e">m_hasDirectSrcDeps</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aa70e810938568bc5b8825cfb9e367dd4">DirDefImpl::addUsesDependency</a>.</p>

</div>
</div>

### dir() {#a9f9871ef38cb735feebfe0b338ca4e2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DirDef * UsedDir::dir ()</td>
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



<p>Definition at line 78 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f9871ef38cb735feebfe0b338ca4e2c">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *<a href="#a9f9871ef38cb735feebfe0b338ca4e2c">dir</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af03eac45e535a65d1d19ae3472503f31">m_dir</a>; }</span></span></div>

</div>


<p>Reference <a href="#af03eac45e535a65d1d19ae3472503f31">m_dir</a>.</p>


<p>Referenced by <a href="#ab39375942f8340b04bbd3c471e52f6fb">UsedDir</a>.</p>

</div>
</div>

### filePairs() {#ae451dc891c59da794d54796d1002bd64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const FilePairLinkedMap &amp; UsedDir::filePairs ()</td>
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



<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae451dc891c59da794d54796d1002bd64">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/filepairlinkedmap">FilePairLinkedMap</a> &amp;<a href="#ae451dc891c59da794d54796d1002bd64">filePairs</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">m_filePairs</a>; }</span></span></div>

</div>


<p>Reference <a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">m_filePairs</a>.</p>

</div>
</div>

### findFilePair() {#add0da96fe9168b96abed52d016b621b2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FilePair * UsedDir::findFilePair (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 76 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>, definition at line 841 of file <a href="/web-doxygen/docs/api/files/src/dirdef-cpp">dirdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add0da96fe9168b96abed52d016b621b2">841</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/filepair">FilePair</a> *<a href="#add0da96fe9168b96abed52d016b621b2">UsedDir::findFilePair</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">m_filePairs</a>.find(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">m_filePairs</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aa70e810938568bc5b8825cfb9e367dd4">DirDefImpl::addUsesDependency</a>.</p>

</div>
</div>

### hasDirectDeps() {#ac811027be125869ba23da94b5dd631c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UsedDir::hasDirectDeps ()</td>
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

<p>Returns true iff any of the dependencies between source and destination files are direct (i.e.</p>


<p>not "inherited" from sub directories)</p>


<p>Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac811027be125869ba23da94b5dd631c2">83</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac811027be125869ba23da94b5dd631c2">hasDirectDeps</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a6c178a62064746363c8914dc0fff9df9">m_hasDirectDeps</a>; }</span></span></div>

</div>


<p>Reference <a href="#a6c178a62064746363c8914dc0fff9df9">m_hasDirectDeps</a>.</p>

</div>
</div>

### hasDirectDstDeps() {#a6620a736948a61103b4281aef2a2d59c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UsedDir::hasDirectDstDeps ()</td>
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

<p>Returns true iff any of the dependencies from the source file to the destination file are directly targeting a file in the destination directory (i.e.</p>


<p>not inherited via sub directories)</p>


<p>Definition at line 93 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6620a736948a61103b4281aef2a2d59c">93</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6620a736948a61103b4281aef2a2d59c">hasDirectDstDeps</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0f3ef45db59856e42bbc150c837e6106">m_hasDirectDstDeps</a>; }</span></span></div>

</div>


<p>Reference <a href="#a0f3ef45db59856e42bbc150c837e6106">m_hasDirectDstDeps</a>.</p>

</div>
</div>

### hasDirectSrcDeps() {#ac799f97624a4a2a3d6698ef82f969591}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UsedDir::hasDirectSrcDeps ()</td>
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

<p>Returns true iff any of the dependencies from the source file to the destination file are directly coming from a file in the source directory (i.e.</p>


<p>not inherited via sub directories)</p>


<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac799f97624a4a2a3d6698ef82f969591">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac799f97624a4a2a3d6698ef82f969591">hasDirectSrcDeps</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ae6af50543bb0ee6b75d2318c3ad5c17e">m_hasDirectSrcDeps</a>; }</span></span></div>

</div>


<p>Reference <a href="#ae6af50543bb0ee6b75d2318c3ad5c17e">m_hasDirectSrcDeps</a>.</p>

</div>
</div>

### sort() {#a24c2c709540ee61b987ae5b80d0b4ec3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void UsedDir::sort ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 95 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>, definition at line 828 of file <a href="/web-doxygen/docs/api/files/src/dirdef-cpp">dirdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24c2c709540ee61b987ae5b80d0b4ec3">828</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a24c2c709540ee61b987ae5b80d0b4ec3">UsedDir::sort</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">  std::stable_sort(<a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">m_filePairs</a>.begin(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">m_filePairs</a>.end(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">            [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;left,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;right)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">              int orderHi = qstricmp_sort(left-&gt;source()-&gt;name(),right-&gt;source()-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">              if (orderHi!=0) return orderHi&lt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">              int orderLo = qstricmp_sort(left-&gt;destination()-&gt;name(),right-&gt;destination()-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">              return orderLo&lt;0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">            });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">m_filePairs</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_dir {#af03eac45e535a65d1d19ae3472503f31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DirDef* UsedDir::m_dir</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af03eac45e535a65d1d19ae3472503f31">98</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *<a href="#af03eac45e535a65d1d19ae3472503f31">m_dir</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a9f9871ef38cb735feebfe0b338ca4e2c">dir</a> and <a href="#ab39375942f8340b04bbd3c471e52f6fb">UsedDir</a>.</p>

</div>
</div>

### m\_filePairs {#a4f3827076b62dfd2c4ffe56e58e1f59c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FilePairLinkedMap UsedDir::m_filePairs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 99 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">99</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/filepairlinkedmap">FilePairLinkedMap</a> <a href="#a4f3827076b62dfd2c4ffe56e58e1f59c">m_filePairs</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a9944cb27f5ddd2a96b8f0c49bd744e49">addFileDep</a>, <a href="#ae451dc891c59da794d54796d1002bd64">filePairs</a>, <a href="#add0da96fe9168b96abed52d016b621b2">findFilePair</a> and <a href="#a24c2c709540ee61b987ae5b80d0b4ec3">sort</a>.</p>

</div>
</div>

### m\_hasDirectDeps {#a6c178a62064746363c8914dc0fff9df9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UsedDir::m_hasDirectDeps = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 101 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c178a62064746363c8914dc0fff9df9">101</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a6c178a62064746363c8914dc0fff9df9">m_hasDirectDeps</a>    = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a9944cb27f5ddd2a96b8f0c49bd744e49">addFileDep</a> and <a href="#ac811027be125869ba23da94b5dd631c2">hasDirectDeps</a>.</p>

</div>
</div>

### m\_hasDirectDstDeps {#a0f3ef45db59856e42bbc150c837e6106}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UsedDir::m_hasDirectDstDeps = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f3ef45db59856e42bbc150c837e6106">103</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0f3ef45db59856e42bbc150c837e6106">m_hasDirectDstDeps</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a9944cb27f5ddd2a96b8f0c49bd744e49">addFileDep</a> and <a href="#a6620a736948a61103b4281aef2a2d59c">hasDirectDstDeps</a>.</p>

</div>
</div>

### m\_hasDirectSrcDeps {#ae6af50543bb0ee6b75d2318c3ad5c17e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool UsedDir::m_hasDirectSrcDeps = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae6af50543bb0ee6b75d2318c3ad5c17e">102</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae6af50543bb0ee6b75d2318c3ad5c17e">m_hasDirectSrcDeps</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a9944cb27f5ddd2a96b8f0c49bd744e49">addFileDep</a> and <a href="#ac799f97624a4a2a3d6698ef82f969591">hasDirectSrcDeps</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dirdef-cpp">dirdef.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
