---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/htags-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `htags.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdio.h&gt;
#include &lt;unordered_map&gt;
#include &lt;string&gt;
#include "<a href="/web-doxygen/docs/api/files/src/htags-h">htags.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
</div>

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/dir">Dir</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a53bce1924b5270f5df59deec61520d3e">g_inputDir</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unordered_map&lt; std::string, std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a110e1111d13ddd15b3f7f436edbc33b1">g_symbolMap</a></td>
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

## Variables

### g\_inputDir {#a53bce1924b5270f5df59deec61520d3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Dir g_inputDir</td>
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



<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/htags-cpp">htags.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a53bce1924b5270f5df59deec61520d3e">31</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dir">Dir</a> <a href="#a53bce1924b5270f5df59deec61520d3e">g_inputDir</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/htags/#a459ba4c5a4e6d3308cee25b93448f0cf">Htags::execute</a> and <a href="/web-doxygen/docs/api/structs/htags/#a0ce955dfddd8473bce6373e92532f12e">Htags::path2URL</a>.</p>

</div>
</div>

### g\_symbolMap {#a110e1111d13ddd15b3f7f436edbc33b1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string,std::string&gt; g_symbolMap</td>
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



<p>Definition at line 32 of file <a href="/web-doxygen/docs/api/files/src/htags-cpp">htags.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a110e1111d13ddd15b3f7f436edbc33b1">32</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::unordered_map&lt;std::string,std::string&gt; <a href="#a110e1111d13ddd15b3f7f436edbc33b1">g_symbolMap</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/htags/#a91a5a1322fbff8f8ad136a3372964512">Htags::loadFilemap</a> and <a href="/web-doxygen/docs/api/structs/htags/#a0ce955dfddd8473bce6373e92532f12e">Htags::path2URL</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
