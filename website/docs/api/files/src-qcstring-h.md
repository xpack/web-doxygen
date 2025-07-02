---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/qcstring-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `qcstring.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;string&gt;
#include &lt;string_view&gt;
#include &lt;algorithm&gt;
#include &lt;cctype&gt;
#include &lt;cstring&gt;
#include &lt;cstdio&gt;
#include &lt;cstdlib&gt;
#include &lt;cstdint&gt;
#include &lt;ostream&gt;
#include "<a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
This is an alternative implementation of <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>. <a href="/web-doxygen/docs/api/classes/qcstring/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae78c14980a90c0decb7a5bf4c4a6815e">JavaCCString</a> = std::basic_string&lt; <a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#a401fffd20e03e2993f9588187b65afc3">JAVACC_CHAR_TYPE</a> &gt;</td>
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

## Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad13e4c478edbecac20fcbce2b86f1c35">operator==</a> (const QCString &amp;s1, const QCString &amp;s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad63779242f7ec7f1f63973d13a545b85">operator==</a> (const QCString &amp;s1, const char *s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a632cd3a80fcab139f461a41f3cc60e8d">operator==</a> (const char *s1, const QCString &amp;s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5703d567f3b2538d3832276940fd734">operator!=</a> (const QCString &amp;s1, const QCString &amp;s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a827bfa735bd7a4e0d7cb16c81d1c42f1">operator!=</a> (const QCString &amp;s1, const char *s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51ba7ef8a69ba1d6ced3d30136697f00">operator!=</a> (const char *s1, const QCString &amp;s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4b5026dbfb3a563bf69c94c70f954f0">operator&lt;</a> (const QCString &amp;s1, const QCString &amp;s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad88e4295035e7cf362d7f55b06f73ba6">operator&lt;</a> (const QCString &amp;s1, const char *s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96d361413f4d2fd8850d999e060ff870">operator&lt;</a> (const char *s1, const QCString &amp;s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf859be3755b7aff5639142161bc7606">operator&lt;=</a> (const QCString &amp;s1, const char *s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07a42b0818f0d832aebe8df9195580fa">operator&lt;=</a> (const char *s1, const QCString &amp;s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a21042d2bb0fb0aefd0afef200ff68648">operator&gt;</a> (const QCString &amp;s1, const char *s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aebf87e7db11cc3a6034475a7bbf4a63d">operator&gt;</a> (const char *s1, const QCString &amp;s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37897e7d8cd6ae9139071d10556b80a2">operator&gt;=</a> (const QCString &amp;s1, const char *s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c05a9f1060373e7b8cdcd50da7502de">operator&gt;=</a> (const char *s1, const QCString &amp;s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad3bf496cd5400f4d0149b5e4a627735c">operator+</a> (const QCString &amp;s1, const QCString &amp;s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f5d7b1a37d084b7229b8fcc0dd0151d">operator+</a> (const QCString &amp;s1, const char *s2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f81275d1115ffda9759c5bd96fa9986">operator+</a> (const char *s1, const QCString &amp;s2)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::ostream &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f1fac62cd55edb5dcfc30b7fe24c48d">operator&lt;&lt;</a> (std::ostream &amp;os, const QCString &amp;s)</td>
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

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad44bc2f81d70fe50067f691cbae5075b">qmemmove</a> (void *dst, const void *src, size_t len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee3d51fb3748d75495209a6997f4f09d">qstrdup</a> (const char *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac05568e4f637e1bcfdddb29aaadfd944">qstrfree</a> (const char *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Frees the memory allocated using <a href="#aee3d51fb3748d75495209a6997f4f09d">qstrdup()</a>. <a href="#ac05568e4f637e1bcfdddb29aaadfd944">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a> (const char *str)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Returns the length of string <em>str</em>, or 0 if a null pointer is passed. <a href="#abbf37d4aef6d2148223fb259a360a4dc">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac32a77e081e980d3a32c45578b7be389">qstrcpy</a> (char *dst, const char *src)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c79403319144d439393ae9be9488c95">qstrncpy</a> (char *dst, const char *src, size_t len)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca1b05428632dc155c2f19349302c055">qisempty</a> (const char *s)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a> (const char *str1, const char *str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a> (const char *str1, const char *str2, size_t len)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77c877f20c7388af72f6a936072b5109">qisspace</a> (char c)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a> (const char *str1, const char *str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a> (const char *str1, const char *str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a> (const char *str1, const char *str2, size_t len)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a> (const char *s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cbb9db483a1cd53acc3671d25399cda">qPrint</a> (const QCString &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad45a3e6d90d19a09562fdd3cd9fa401a">qPrint</a> (const std::string &amp;s)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a> (const QCString &amp;s)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d1063a4c1d2c36a05f8e79bf5265de0">qstrcmp</a> (const QCString &amp;str1, const char *str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adbc3f136c91cf966d67fa45dc66d7872">qstrcmp</a> (const char *str1, const QCString &amp;str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a06565348139db73f6fe50d33d3fb4c2d">qstrcmp</a> (const QCString &amp;str1, const QCString &amp;str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a97be1dda81236d5b70232705817f55f5">qstricmp</a> (const QCString &amp;str1, const char *str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33f4db19d3805a1cf2de3560155442fd">qstricmp</a> (const char *str1, const QCString &amp;str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c210fdf334f6a6aacec23bae6afda8">qstricmp</a> (const QCString &amp;str1, const QCString &amp;str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32ac0dd364b2ad4233c2e64dedb40e97">qstricmp_sort</a> (const QCString &amp;str1, const char *str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56fea00f875a74ba5c3fff176ca908d9">qstricmp_sort</a> (const char *str1, const QCString &amp;str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af84700f1e6f0e39b5fe2e2f0653a943a">qstricmp_sort</a> (const QCString &amp;str1, const QCString &amp;str2)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c125e95623108226932004a5e061d1">qstrnicmp</a> (const QCString &amp;str1, const char *str2, size_t len)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc7c52aee841813f28c7e9227b5bea57">qstrnicmp</a> (const char *str1, const QCString &amp;str2, size_t len)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232d1f8a5b76f765dec1cf7ce2ad1cd0">qstrnicmp</a> (const QCString &amp;str1, const QCString &amp;str2, size_t len)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a606914bff961461e7ff377c2c07713d4">substitute</a> (const QCString &amp;str, const QCString &amp;find, const QCString &amp;replace)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
substitute all occurrences of <em>src</em> in <em>s</em> by <em>dst</em> <a href="#a606914bff961461e7ff377c2c07713d4">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a55053c8ff88afe6d960df1eeb49d517f">substitute</a> (const QCString &amp;str, const char *find, const char *replace)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abae2b8bda3ecfa394b9c8befdd1608ce">substitute</a> (const QCString &amp;s, const QCString &amp;src, const QCString &amp;dst, int skip_seq)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
substitute all occurrences of <em>src</em> in <em>s</em> by <em>dst</em>, but skip each consecutive sequence of <em>src</em> where the number consecutive <em>src</em> matches <em>skip\_seq</em>; if <em>skip\_seq</em> is negative, skip any number of consecutive <em>src</em> <a href="#abae2b8bda3ecfa394b9c8befdd1608ce">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a84c295f784c9b8da3706ee857ba2c70d">substitute</a> (const QCString &amp;s, char srcChar, char dstChar)</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>&nbsp;&nbsp;&nbsp;false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>&nbsp;&nbsp;&nbsp;true</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca68c0d4ac8df0838e209fb5300f7be3">ASSERT</a>(x)&nbsp;&nbsp;&nbsp;...</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a307ffe8cbc4a4aa695900441d1df49f3">qsnprintf</a>&nbsp;&nbsp;&nbsp;snprintf</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa138e851b3b64211ce294927a4669b40">HAS_IMPLICIT_CAST_TO_PLAIN_C_STRING</a>&nbsp;&nbsp;&nbsp;0</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d8116d29bf5dad9161f0e7309c0a46e">HAS_CHARACTER_APPEND_OPERATOR</a>&nbsp;&nbsp;&nbsp;1</td>
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

### JavaCCString {#ae78c14980a90c0decb7a5bf4c4a6815e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using JavaCCString =  std::basic_string&lt;JAVACC_CHAR_TYPE&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae78c14980a90c0decb7a5bf4c4a6815e">95</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#ae78c14980a90c0decb7a5bf4c4a6815e">JavaCCString</a> = std::basic_string&lt;JAVACC_CHAR_TYPE&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Operators

### operator!=() {#ae5703d567f3b2538d3832276940fd734}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator!= (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 616 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5703d567f3b2538d3832276940fd734">616</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae5703d567f3b2538d3832276940fd734">operator!=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() != s2.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### operator!=() {#a827bfa735bd7a4e0d7cb16c81d1c42f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator!= (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const char * s2)</td>
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



Definition at line 619 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a827bfa735bd7a4e0d7cb16c81d1c42f1">619</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae5703d567f3b2538d3832276940fd734">operator!=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),s2) != 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator!=() {#a51ba7ef8a69ba1d6ced3d30136697f00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator!= (const char * s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 622 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a51ba7ef8a69ba1d6ced3d30136697f00">622</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae5703d567f3b2538d3832276940fd734">operator!=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1,s2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()) != 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator+() {#ad3bf496cd5400f4d0149b5e4a627735c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString operator+ (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 652 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad3bf496cd5400f4d0149b5e4a627735c">652</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad3bf496cd5400f4d0149b5e4a627735c">operator+</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()+s2.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### operator+() {#a0f5d7b1a37d084b7229b8fcc0dd0151d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString operator+ (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const char * s2)</td>
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



Definition at line 658 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f5d7b1a37d084b7229b8fcc0dd0151d">658</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad3bf496cd5400f4d0149b5e4a627735c">operator+</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp(s1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">    tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(s2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> tmp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>.
</div>
</div>

### operator+() {#a1f81275d1115ffda9759c5bd96fa9986}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString operator+ (const char * s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 665 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f81275d1115ffda9759c5bd96fa9986">665</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad3bf496cd5400f4d0149b5e4a627735c">operator+</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp(s1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">    tmp.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">append</a>(s2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> tmp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/qcstring/#a8f0a381fdae1427b1182baf0abde21e7">QCString::append</a>.
</div>
</div>

### operator&lt;() {#ad4b5026dbfb3a563bf69c94c70f954f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&lt; (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 625 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad4b5026dbfb3a563bf69c94c70f954f0">625</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad4b5026dbfb3a563bf69c94c70f954f0">operator&lt;</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),s2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()) &lt; 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator&lt;() {#ad88e4295035e7cf362d7f55b06f73ba6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&lt; (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const char * s2)</td>
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



Definition at line 628 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad88e4295035e7cf362d7f55b06f73ba6">628</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad4b5026dbfb3a563bf69c94c70f954f0">operator&lt;</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),s2) &lt; 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator&lt;() {#a96d361413f4d2fd8850d999e060ff870}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&lt; (const char * s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 631 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a96d361413f4d2fd8850d999e060ff870">631</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad4b5026dbfb3a563bf69c94c70f954f0">operator&lt;</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1,s2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()) &lt; 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator&lt;&lt;() {#a4f1fac62cd55edb5dcfc30b7fe24c48d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::ostream &amp; operator&lt;&lt; (std::ostream &amp; os, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



Definition at line 770 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f1fac62cd55edb5dcfc30b7fe24c48d">770</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> std::ostream&amp; <a href="#a4f1fac62cd55edb5dcfc30b7fe24c48d">operator&lt;&lt;</a>(std::ostream&amp; os, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">    os &lt;&lt; s.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> os;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### operator&lt;=() {#aaf859be3755b7aff5639142161bc7606}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&lt;= (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const char * s2)</td>
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



Definition at line 634 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaf859be3755b7aff5639142161bc7606">634</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aaf859be3755b7aff5639142161bc7606">operator&lt;=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),s2) &lt;= 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator&lt;=() {#a07a42b0818f0d832aebe8df9195580fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&lt;= (const char * s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 637 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07a42b0818f0d832aebe8df9195580fa">637</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aaf859be3755b7aff5639142161bc7606">operator&lt;=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1,s2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()) &lt;= 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator==() {#ad13e4c478edbecac20fcbce2b86f1c35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator== (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 607 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad13e4c478edbecac20fcbce2b86f1c35">607</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad13e4c478edbecac20fcbce2b86f1c35">operator==</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s1.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() == s2.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(); }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### operator==() {#ad63779242f7ec7f1f63973d13a545b85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator== (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const char * s2)</td>
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



Definition at line 610 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad63779242f7ec7f1f63973d13a545b85">610</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad13e4c478edbecac20fcbce2b86f1c35">operator==</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),s2) == 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator==() {#a632cd3a80fcab139f461a41f3cc60e8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator== (const char * s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 613 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a632cd3a80fcab139f461a41f3cc60e8d">613</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ad13e4c478edbecac20fcbce2b86f1c35">operator==</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1,s2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()) == 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator&gt;() {#a21042d2bb0fb0aefd0afef200ff68648}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&gt; (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const char * s2)</td>
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



Definition at line 640 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a21042d2bb0fb0aefd0afef200ff68648">640</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a21042d2bb0fb0aefd0afef200ff68648">operator&gt;</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),s2) &gt; 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator&gt;() {#aebf87e7db11cc3a6034475a7bbf4a63d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&gt; (const char * s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 643 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aebf87e7db11cc3a6034475a7bbf4a63d">643</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a21042d2bb0fb0aefd0afef200ff68648">operator&gt;</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1,s2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()) &gt; 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator&gt;=() {#a37897e7d8cd6ae9139071d10556b80a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&gt;= (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s1, const char * s2)</td>
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



Definition at line 646 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a37897e7d8cd6ae9139071d10556b80a2">646</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a37897e7d8cd6ae9139071d10556b80a2">operator&gt;=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),s2) &gt;= 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### operator&gt;=() {#a5c05a9f1060373e7b8cdcd50da7502de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool operator&gt;= (const char * s1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s2)</td>
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



Definition at line 649 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5c05a9f1060373e7b8cdcd50da7502de">649</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a37897e7d8cd6ae9139071d10556b80a2">operator&gt;=</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(s1,s2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()) &gt;= 0; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### qisempty() {#aca1b05428632dc155c2f19349302c055}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool qisempty (const char * s)</td>
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



Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca1b05428632dc155c2f19349302c055">66</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aca1b05428632dc155c2f19349302c055">qisempty</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || *s==</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">; }</span></span></div>

</div>


Referenced by <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a> and <a href="#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>.
</div>
</div>

### qisspace() {#a77c877f20c7388af72f6a936072b5109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool qisspace (char c)</td>
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



Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a77c877f20c7388af72f6a936072b5109">81</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a77c877f20c7388af72f6a936072b5109">qisspace</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> || c==</span><span class="doxyHighlightCharLiteral">'\r'</span><span class="doxyHighlight">; }</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/anchorgenerator/#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af428b9307683dc2c090f7d837138b438">QCString::quoted</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0940360aa6d41fd2496603fc565e3996">removeRedundantWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ae5612f003ab58972eb5769811876c5e3">QCString::removeWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">QCString::simplifyWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa4a9dec36c09c8c131a0e5e9bb71d98e">QCString::toLong</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a524e1cd9e1c24e91d57b1cb91513fa67">QCString::toUInt64</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a592f86f3d758cb9285967c195f2f1824">QCString::toULong</a> and <a href="/web-doxygen/docs/api/classes/dotattributes/#a379cba80b5c667d8d41d85426c4f5376">DotAttributes::updateValue</a>.
</div>
</div>

### qmemmove() {#ad44bc2f81d70fe50067f691cbae5075b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void * qmemmove (void * dst, const void * src, size_t len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 47 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 402 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#ad44bc2f81d70fe50067f691cbae5075b">402</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#ad44bc2f81d70fe50067f691cbae5075b">qmemmove</a>( </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *dst, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> *src, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( dst &gt; src ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *d = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(dst) + len - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(src) + len - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( len-- )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">      *d-- = *s--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( dst &lt; src ) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *d = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(dst);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(src);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ( len-- )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">      *d++ = *s++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> dst;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### qPrint() {#a9851ebb5ae2f65b4d2b1d08421edbfd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * qPrint (const char * s)</td>
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



Definition at line 672 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9851ebb5ae2f65b4d2b1d08421edbfd2">672</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a13a18d70232db6c9889f7f473a5cf3d3">addIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3ac0043018354a90b2ce4cba4413f606">ModuleDefImpl::addMemberToModule</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#abed27cdfdbc0b2f7e850aff746420010">addSubprogram</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aa70e810938568bc5b8825cfb9e367dd4">DirDefImpl::addUsesDependency</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ac9fd711b7dd6cbbefb87ab903e540b31">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad14a1e786887639d5383cbcd8427bba8">addXRefItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad31622c7a3471af7d6bb17cc8fb29579">buildFileList</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/classes/xmlcodegenerator/#a17dd450e496129d67a0208dc421cfd1c">XMLCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a322962831f30dce16a3323a67d6e2c44">createCroppedEPS</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a751decfa83144bf64f1cd1cb492db3fe">createCroppedPDF</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a704ccf2352fafe16ddf093abbaa6f7b4">createDVIFile</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a92954fc40f0e05879c1726f8d8207b1f">createEPSbboxFile</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a0cc00317e5a4482a2e7df401bd480f38">createPNG</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a57b6802045cb92594d1f65e5b8821456">createPostscriptFile</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#ad88d54d53a499dad6fda6617d2dc952e">createSVGFromPDF</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a0c843eafd8ef0511d939fa5c6efc863f">createSVGFromPDFviaInkscape</a>, <a href="/web-doxygen/docs/api/classes/debuglex/#a105ca89098d00f847fef80e40fa4d3b0">DebugLex::DebugLex</a>, <a href="/web-doxygen/docs/api/files/src/docnode-h/#ae06df9ac205468d82301870dbe23905c">dumpDocNodeList</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad2df37d9e386ae992a5aa98ab9a0515c">encodeForOutput</a>, <a href="/web-doxygen/docs/api/classes/docparser/#afa9541b35f25f2f63a6f5ff338967f22">DocParser::errorHandleDefaultToken</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a3d46e03d176edeb9ec7044f80ffe3a81">DocParser::findAndCopyImage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a767fe9c8dd14640cc99a6f1c9e0981c7">findMemberLink</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a640bce791d53e83dcbd47f7ab01620e8">DocTokenizer::findSections</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a34f3686f7bccb7f7d9ef304724198661">VhdlDocGen::findVhdlClass</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa723e85238b66b5916c25989013e52b8">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#abc8184d316956569fe02279fba78ab92">generateFunctionLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a908c99ff67d83138ed1f871dab4d4c12">generateMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af86247b60aae3c8229391fbece0cb1a7">generatePHPVariableLink</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ac7b3f73c86e8a751ed2fd61e9d0cc2e3">generateSqlite3ForClass</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#ae3d49e892872b87e8c5d19fc190b6512">DotGfxHierarchyTable::getBaseName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab5d70bf9e42fcc2766efb0655ff317e0">getDefs</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa48141b866dee2454e4290a3c34d36bb">getLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#aed763574c33aa626cd8209d9d681938a">handle\_warn\_as\_error</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a8541b3718d4e34888ecfcfc218f5c331">DocPara::handleRef</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a635a7915c47893c3aa1f40fbb9d288ac">handleToc</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abfa0499109cd76100ecdad2fa752ed3b">mergeArguments</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4931bb0ccd2eb4d8aede2a9afb7058d6">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a595de00e640ff570870b8ed05a492e35">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a729fe6d8301bb25f3785b4e4466fccd5">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#abc9316f6d36cef5484dfbd79c7eccff1">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#ab2f6c9c71d1059e75eda24522ab1d494">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a14a6612be847086cb768fefabb79991f">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#afe433f28083f19e3e5d52d79f47cda34">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a3d0936ff077c5a7bec4ac06a7d1ee763">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#aae01a9e39e11d84ea627568988bd2754">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a8b0c3df81502ad08c0887a26b78061c2">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#ad7ff8cee58044fc117f9dea3be38d4c7">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a1ac1a7a6905624908ed5af405589ced4">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#aced90253c233a0d8f62b5466429408f0">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a98adb13be89d3cf7a38d437f0651e757">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#afca508aaeaec816fd6bd99e2c9c1211a">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a9c72fa42dfa620a7e76e87796cc796f8">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#ad4c0764dcc811dec5e635dbd8b3d441f">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a193a00ab964a64974f8207a0da1f51d3">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a7dee669b470d18608669baf684a2e707">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a4f6c2fb7c0ced2e00742581755c53255">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a6ba2a392ae9bdd19b4bc6f54b7b4aeff">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a64fdcaf512e042702ba950eccb8a515c">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a2d5e3028b9cb94fd52e873e5c4a04411">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a8f86d589ca4a487d829014e0c4e2f260">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a8aae96f31793267582a0ad596592b27e">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#acb70232f5bd9c569609750457e242832">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a8af211f97fb664a7e78e6916d9475b66">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a74df130d679f1d46a7896f8400ac51b6">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a2deab2ec9a790301cf75ade1ec9bf02a">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#aed18dc85fa4e2c986036d240902b70cc">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a1189a4bc09f26b09b5809fb5382b0a0c">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a8ada83e970e62ab6d53cf20aaa658a8d">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a5d06627b2afb76668e8315613a76b9d3">ConfigImpl::parse</a>, <a href="/web-doxygen/docs/api/classes/docmscfile/#ae8a3e4c248768b7438a264aaa5114813">DocMscFile::parse</a>, <a href="/web-doxygen/docs/api/classes/docsecreflist/#a9b279250711bb61d12bff4c34e70d2f3">DocSecRefList::parse</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a>, <a href="/web-doxygen/docs/api/classes/ccodeparser/#a106ea78aa6382f5b06dbd2563d5b99e4">CCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/fortrancodeparser/#ab7216957ad8abace8578d47edd8b578d">FortranCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/lexcodeparser/#a907e618c99ef07aa00fc0604062e3929">LexCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/pythoncodeparser/#a7f8b5638c6d0424a1de9bc6905041ab2">PythonCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/sqlcodeparser/#ad4cfac05d7a0c2354cdb90992b1e0248">SQLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/vhdlcodeparser/#a49ff704e68bb7562a054bd1c7f8bba09">VHDLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/xmlcodeparser/#a1e7283cd50a9220c8381cbdf953702ca">XMLCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/commentscanner/#a2e48aae075e2f44ddd785428b4099f4a">CommentScanner::parseCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/coutlineparser/#a5bf5190ffb4fc52b45fc6b22895a6fbf">COutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/classes/fortranoutlineparser/#af3e1c6efa3eba5f4d30934eac0cd0aa3">FortranOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/classes/lexoutlineparser/#ac842abb13f0168eeec20c4a6de1d79b8">LexOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/classes/pythonoutlineparser/#a5a3b64521d1851e39a58043826b11a95">PythonOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a400e3217ee852f725c4cec415bd13292">popScope</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a9b95266661529a9ec041d5e91f4c302f">FlowChart::printNode</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#ab536b3c2ec35df931a4fce0dbf2e1420">pushBuffer</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a0e434c11b15cc30b8ef9a4ea89b6f99b">pushScope</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a4e9da1f53e500d73aa8997ead79093fb">DotNode::renumberNodes</a>, <a href="/web-doxygen/docs/api/classes/symbolresolver/#a739c707d2150c5b2115fa731694eaeec">SymbolResolver::resolveSymbol</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91768fc1635556eefd2d96ea1751435d">runHtmlHelpCompiler</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aef9d8a33c82dbef016b68d619f0b2856">saveObjCContext</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a7b2ca28396c488d5a08ead21731ed2c2">scanner\_abort</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ab3604b365f2d78c31db8a2fae321b6a8">setCallContextForVar</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ad0f8b1a32f797c259274123f7baa18f4">setClassScope</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a1035c7c56bdac87a032ba8a18a58eb38">setTranslator</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a897bf45c84c487532045b33d50d94741">stripClassName</a>, <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a00308995c9081283f53dd39f95906a9c">DirDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdiagram/#acb331a908252968ca8ba371ee560aa51">ClassDiagram::writeFigure</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a> and <a href="/web-doxygen/docs/api/classes/debuglex/#a258923c83f68a5a6d599519b9750d826">DebugLex::\~DebugLex</a>.
</div>
</div>

### qPrint() {#a1cbb9db483a1cd53acc3671d25399cda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * qPrint (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



Definition at line 677 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1cbb9db483a1cd53acc3671d25399cda">677</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(); </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>.
</div>
</div>

### qPrint() {#ad45a3e6d90d19a09562fdd3cd9fa401a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * qPrint (const std::string &amp; s)</td>
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



Definition at line 682 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad45a3e6d90d19a09562fdd3cd9fa401a">682</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s.c_str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### qstrcmp() {#acd9682a0a00b8d6f0c8c1e4c23153126}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstrcmp (const char * str1, const char * str2)</td>
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



Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acd9682a0a00b8d6f0c8c1e4c23153126">69</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (str1 &amp;&amp; str2) ? strcmp(str1,str2) :     </span><span class="doxyHighlightComment">// both non-empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">         (<a href="#aca1b05428632dc155c2f19349302c055">qisempty</a>(str1) &amp;&amp; <a href="#aca1b05428632dc155c2f19349302c055">qisempty</a>(str2)) ? 0 : </span><span class="doxyHighlightComment">// both empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#aca1b05428632dc155c2f19349302c055">qisempty</a>(str1) ? -1 : 1;                 </span><span class="doxyHighlightComment">// one empty, other non-empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aca1b05428632dc155c2f19349302c055">qisempty</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/msc-cpp/#aa8d9375638b4b082c242439fa6be97a0">convertMapFile</a>, <a href="/web-doxygen/docs/api/classes/keywordhash/#ad9e74a09c57e4891e741ecf7ee23919e">KeywordHash::find</a>, <a href="#a51ba7ef8a69ba1d6ced3d30136697f00">operator!=</a>, <a href="#a827bfa735bd7a4e0d7cb16c81d1c42f1">operator!=</a>, <a href="#a96d361413f4d2fd8850d999e060ff870">operator&lt;</a>, <a href="#ad88e4295035e7cf362d7f55b06f73ba6">operator&lt;</a>, <a href="#ad4b5026dbfb3a563bf69c94c70f954f0">operator&lt;</a>, <a href="#a07a42b0818f0d832aebe8df9195580fa">operator&lt;=</a>, <a href="#aaf859be3755b7aff5639142161bc7606">operator&lt;=</a>, <a href="#a632cd3a80fcab139f461a41f3cc60e8d">operator==</a>, <a href="#ad63779242f7ec7f1f63973d13a545b85">operator==</a>, <a href="#aebf87e7db11cc3a6034475a7bbf4a63d">operator&gt;</a>, <a href="#a21042d2bb0fb0aefd0afef200ff68648">operator&gt;</a>, <a href="#a5c05a9f1060373e7b8cdcd50da7502de">operator&gt;=</a>, <a href="#a37897e7d8cd6ae9139071d10556b80a2">operator&gt;=</a>, <a href="#adbc3f136c91cf966d67fa45dc66d7872">qstrcmp</a>, <a href="#a2d1063a4c1d2c36a05f8e79bf5265de0">qstrcmp</a>, <a href="#a06565348139db73f6fe50d33d3fb4c2d">qstrcmp</a>, <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp\_sort</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a> and <a href="/web-doxygen/docs/api/files/src/vhdlcode-l/#aacdc305fbdfbc50f742f71a1ec5c708a">startFontClass</a>.
</div>
</div>

### qstrcmp() {#a2d1063a4c1d2c36a05f8e79bf5265de0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstrcmp (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str1, const char * str2)</td>
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



Definition at line 694 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2d1063a4c1d2c36a05f8e79bf5265de0">694</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(str1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),str2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### qstrcmp() {#adbc3f136c91cf966d67fa45dc66d7872}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstrcmp (const char * str1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str2)</td>
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



Definition at line 699 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adbc3f136c91cf966d67fa45dc66d7872">699</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(str1,str2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### qstrcmp() {#a06565348139db73f6fe50d33d3fb4c2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstrcmp (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str2)</td>
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



Definition at line 704 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a06565348139db73f6fe50d33d3fb4c2d">704</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">705</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(str1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),str2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>.
</div>
</div>

### qstrcpy() {#ac32a77e081e980d3a32c45578b7be389}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * qstrcpy (char * dst, const char * src)</td>
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



Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac32a77e081e980d3a32c45578b7be389">61</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#ac32a77e081e980d3a32c45578b7be389">qstrcpy</a>( </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *dst, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *src )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> src ? strcpy(dst, src) : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; }</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#abae2b8bda3ecfa394b9c8befdd1608ce">substitute</a>.
</div>
</div>

### qstrdup() {#aee3d51fb3748d75495209a6997f4f09d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * qstrdup (const char * s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Returns a copy of a string <em>s</em>. Note that memory is passed to the caller, use <a href="#ac05568e4f637e1bcfdddb29aaadfd944">qstrfree()</a> to release.

Declaration at line 53 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 419 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a0ba4946210d9b7880aaafe7b713d6865">419</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a0ba4946210d9b7880aaafe7b713d6865">qstrdup</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !str )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *dst = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">[<a href="#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>(str)+1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> strcpy( dst, str );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>.
</div>
</div>

### qstrfree() {#ac05568e4f637e1bcfdddb29aaadfd944}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void qstrfree (const char * s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Frees the memory allocated using <a href="#aee3d51fb3748d75495209a6997f4f09d">qstrdup()</a>.

Declaration at line 55 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 427 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#abded38c05cd6d8e9d3941cbf62ee7d52">427</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#abded38c05cd6d8e9d3941cbf62ee7d52">qstrfree</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">delete</span><span class="doxyHighlight">[](str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### qstricmp() {#a3fcf9e9f5dafe61787ad66adae5a1e85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstricmp (const char * str1, const char * str2)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 84 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 442 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">442</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !s1 || !s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s1 == s2 ? 0 : </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(s2 - s1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> res = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> ( ; !(res = ((c=<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>(*s1)) - <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>(*s2))); s1++, s2++ )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !c ) </span><span class="doxyHighlightComment">// strings are equal</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#ac853f7c85a98e5ef7040604706c7b80c">compareString</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9e5659d6cb4369b41809c279d006b44c">VhdlDocGen::findAllArchitectures</a>, <a href="/web-doxygen/docs/api/classes/docgroup/#a75ac79ba2e9fa9b9feeaadf6f8567931">DocGroup::findExistingGroup</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a590a484692d935d4850c7e6bce508d01">FlowChart::findLabel</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a34f3686f7bccb7f7d9ef304724198661">VhdlDocGen::findVhdlClass</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6278992808df867a22fb9a6d41516fd2">mainPageHasOwnTitle</a>, <a href="#a33f4db19d3805a1cf2de3560155442fd">qstricmp</a>, <a href="#a97be1dda81236d5b70232705817f55f5">qstricmp</a>, <a href="#a74c210fdf334f6a6aacec23bae6afda8">qstricmp</a>, <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp\_sort</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a70c91a538e4038f2157b046a1157acac">transcodeCharacterBuffer</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#ad0135f07f9ef7ebdbef4b5f09a255397">FlowChart::writeFlowLinks</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a02de81220c8c130bc7c8f56dc5ecf55d">ClassDefImpl::writeIncludeFilesForSlice</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a>.
</div>
</div>

### qstricmp() {#a97be1dda81236d5b70232705817f55f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstricmp (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str1, const char * str2)</td>
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



Definition at line 709 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a97be1dda81236d5b70232705817f55f5">709</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">710</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">711</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a>(str1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),str2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">712</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a>.
</div>
</div>

### qstricmp() {#a33f4db19d3805a1cf2de3560155442fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstricmp (const char * str1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str2)</td>
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



Definition at line 714 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a33f4db19d3805a1cf2de3560155442fd">714</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">715</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">716</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a>(str1,str2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">717</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a>.
</div>
</div>

### qstricmp() {#a74c210fdf334f6a6aacec23bae6afda8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstricmp (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str2)</td>
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



Definition at line 719 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74c210fdf334f6a6aacec23bae6afda8">719</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">720</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a>(str1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),str2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a>.
</div>
</div>

### qstricmp\_sort() {#a07e4a8b28f58e46b010e22651c87eb3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstricmp_sort (const char * str1, const char * str2)</td>
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



Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07e4a8b28f58e46b010e22651c87eb3c">86</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> result = <a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a>(str1,str2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result==0 ? <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a>(str1,str2) : result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#acd9682a0a00b8d6f0c8c1e4c23153126">qstrcmp</a> and <a href="#a3fcf9e9f5dafe61787ad66adae5a1e85">qstricmp</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a9d5caa3df18ab19e549d3b603a716780">buildDirectories</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a868969982c8fee16854bcc7735cd977e">compareDirDefs</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3fc838fe6dfe16aaf92455e8cb066d59">compareFileDefs</a>, <a href="/web-doxygen/docs/api/files/src/memberlist-cpp/#a167ee264b79050f2a7adc66a8c0e999d">genericCompareMembers</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0a8299ea0705cebde431ef0ea600fcb1">DirDefImpl::matchPath</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="#a56fea00f875a74ba5c3fff176ca908d9">qstricmp\_sort</a>, <a href="#a32ac0dd364b2ad4233c2e64dedb40e97">qstricmp\_sort</a>, <a href="#af84700f1e6f0e39b5fe2e2f0653a943a">qstricmp\_sort</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ed1fdd15e6ed566c33a63fcd30d53c4">searchInputFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a38dfbb5daa66a820f49167beecae6e90">FileDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a2a3b6387c4b99adde50e0751493d4990">GroupDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a16de9b0536cf33e6b6380cf55ecb3ca5">ModuleDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ade0ababe591c242aa32049874d07e298">NamespaceDefImpl::sortMemberLists</a> and <a href="/web-doxygen/docs/api/classes/htmlhelpindex/#a90f49f18773a8f5949d7908575996e71">HtmlHelpIndex::writeFields</a>.
</div>
</div>

### qstricmp\_sort() {#a32ac0dd364b2ad4233c2e64dedb40e97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstricmp_sort (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str1, const char * str2)</td>
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



Definition at line 724 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32ac0dd364b2ad4233c2e64dedb40e97">724</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">725</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">726</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>(str1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),str2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">727</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp\_sort</a>.
</div>
</div>

### qstricmp\_sort() {#a56fea00f875a74ba5c3fff176ca908d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstricmp_sort (const char * str1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str2)</td>
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



Definition at line 729 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a56fea00f875a74ba5c3fff176ca908d9">729</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">730</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">731</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>(str1,str2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">732</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp\_sort</a>.
</div>
</div>

### qstricmp\_sort() {#af84700f1e6f0e39b5fe2e2f0653a943a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstricmp_sort (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str2)</td>
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



Definition at line 734 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af84700f1e6f0e39b5fe2e2f0653a943a">734</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">735</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">736</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp_sort</a>(str1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),str2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">737</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#a07e4a8b28f58e46b010e22651c87eb3c">qstricmp\_sort</a>.
</div>
</div>

### qstrlen() {#abbf37d4aef6d2148223fb259a360a4dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t qstrlen (const char * str)</td>
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

Returns the length of string <em>str</em>, or 0 if a null pointer is passed.

Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abbf37d4aef6d2148223fb259a360a4dc">58</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> uint32_t <a href="#abbf37d4aef6d2148223fb259a360a4dc">qstrlen</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> str ? </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint32_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(strlen(str)) : 0; }</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/qcstring/#ab2617e8fdb6c52fb762a52f7252d61ed">QCString::contains</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a5381d8547e101adef3ee87f8d54c9925">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab6cbf7f8b8943606766d6e3d2e26fc70">QCString::findRev</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aec32365751b5a3b7a7382d4dea866800">getArg</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0acc09ca029c0a255063a7dc610be340">QCString::insert</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a802a7b8116fa1b8b46895c25a32c5677">VhdlDocGen::prepareComment</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a0ba4946210d9b7880aaafe7b713d6865">qstrdup</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a558bfa6d487cad0977c6d706cd638a6c">selectBlocks</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c85e13964c82e9aa4cef183a767651e">substituteKeywords</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a> and <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a>.
</div>
</div>

### qstrncmp() {#a19faae287d13ccea75b1d5a0eb110d97}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstrncmp (const char * str1, const char * str2, size_t len)</td>
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



Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19faae287d13ccea75b1d5a0eb110d97">75</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str2, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (str1 &amp;&amp; str2) ? strncmp(str1,str2,len) :  </span><span class="doxyHighlightComment">// both non-empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">         (<a href="#aca1b05428632dc155c2f19349302c055">qisempty</a>(str1) &amp;&amp; <a href="#aca1b05428632dc155c2f19349302c055">qisempty</a>(str2)) ? 0 :   </span><span class="doxyHighlightComment">// both empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="#aca1b05428632dc155c2f19349302c055">qisempty</a>(str1) ? -1 : 1;                   </span><span class="doxyHighlightComment">// one empty other non-empty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aca1b05428632dc155c2f19349302c055">qisempty</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3618467e48bbb77e01562b327fa65f20">checkBlocks</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab2617e8fdb6c52fb762a52f7252d61ed">QCString::contains</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a5b661698b94e4b37748ee38025784690">Markdown::Private::findEmphasisChar</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aad2fb530e3d19a77de38a8c1b633b786">Markdown::Private::findEndOfLine</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab6cbf7f8b8943606766d6e3d2e26fc70">QCString::findRev</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal\_at</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#af7c977e857cdf4c6e3a2e320a0dbdedf">literal\_at</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a43b1695a69a83037471e5445c7c940ce">Markdown::Private::processSpecialCommand</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a558bfa6d487cad0977c6d706cd638a6c">selectBlocks</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a45928a3aa04b29c259685a5d3f6cbf4d">skipToEndMarker</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#abae2b8bda3ecfa394b9c8befdd1608ce">substitute</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c85e13964c82e9aa4cef183a767651e">substituteKeywords</a>.
</div>
</div>

### qstrncpy() {#a0c79403319144d439393ae9be9488c95}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * qstrncpy (char * dst, const char * src, size_t len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 64 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 432 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a0c79403319144d439393ae9be9488c95">432</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a0c79403319144d439393ae9be9488c95">qstrncpy</a>( </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *dst, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *src, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !src )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">  strncpy( dst, src, len );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( len &gt; 0 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">    dst[len-1] = </span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> dst;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### qstrnicmp() {#a8f98a1f201256d5d9ba6c20252dc3e22}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstrnicmp (const char * str1, const char * str2, size_t len)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 93 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 458 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#ad9614f1bf0cb919b631ac2cf5025964c">458</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#ad9614f1bf0cb919b631ac2cf5025964c">qstrnicmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s2, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( !s1 || !s2 )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(s2 - s1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> ( ; len--; s1++, s2++ )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>(*s1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> res = c-<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>(*s2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( res!=0 ) </span><span class="doxyHighlightComment">// strings are not equal</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> res;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( c==0 ) </span><span class="doxyHighlightComment">// strings are equal</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a4e545641f98651d4fb8299b407721f9b">toLowerChar</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/qcstring/#ab2617e8fdb6c52fb762a52f7252d61ed">QCString::contains</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a5381d8547e101adef3ee87f8d54c9925">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab6cbf7f8b8943606766d6e3d2e26fc70">QCString::findRev</a>, <a href="#acc7c52aee841813f28c7e9227b5bea57">qstrnicmp</a>, <a href="#a87c125e95623108226932004a5e061d1">qstrnicmp</a> and <a href="#a232d1f8a5b76f765dec1cf7ce2ad1cd0">qstrnicmp</a>.
</div>
</div>

### qstrnicmp() {#a87c125e95623108226932004a5e061d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstrnicmp (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str1, const char * str2, size_t len)</td>
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



Definition at line 740 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87c125e95623108226932004a5e061d1">740</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str2, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>(str1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),str2,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>.
</div>
</div>

### qstrnicmp() {#acc7c52aee841813f28c7e9227b5bea57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstrnicmp (const char * str1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str2, size_t len)</td>
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



Definition at line 745 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc7c52aee841813f28c7e9227b5bea57">745</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str2, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>(str1,str2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">748</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>.
</div>
</div>

### qstrnicmp() {#a232d1f8a5b76f765dec1cf7ce2ad1cd0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int qstrnicmp (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str2, size_t len)</td>
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



Definition at line 750 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a232d1f8a5b76f765dec1cf7ce2ad1cd0">750</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str1, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str2, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>(str1.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),str2.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a> and <a href="#a8f98a1f201256d5d9ba6c20252dc3e22">qstrnicmp</a>.
</div>
</div>

### substitute() {#a606914bff961461e7ff377c2c07713d4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString substitute (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; find, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; replace)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

substitute all occurrences of <em>src</em> in <em>s</em> by <em>dst</em>

Declaration at line 756 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 477 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">477</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;src,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;dst)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || src.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *q = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, *p = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> srcLen = src.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> dstLen = dst.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> resLen = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (srcLen!=dstLen)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (p = s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(); (q=strstr(p,src.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()))!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; p=q+srcLen) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">    resLen = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()+count*(dstLen-srcLen);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// result has same size as s</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">    resLen = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result(resLen, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *r = result.<a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (p = s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(); (q=strstr(p,src.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()))!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; p=q+srcLen)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(q-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">    memcpy(r,p,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">    r+=l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dstLen&gt;0) memcpy(r,dst.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),dstLen);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">    r+=dstLen;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (r)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac32a77e081e980d3a32c45578b7be389">qstrcpy</a>(r,p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("substitute(%s,%s,%s)-&gt;%s\n",s,src,dst,result.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#ac32a77e081e980d3a32c45578b7be389">qstrcpy</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">QCString::rawData</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a5e2d1232239471126aade777574d9d34">FlowChart::addFlowChart</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a3b2171b8a9cdc055bd41d0181094f27a">addFrom</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a95106cfe8d0c8504016e0714ae0e10f7">addGlobalFunction</a>, <a href="/web-doxygen/docs/api/classes/htmlhelpindex/#a70d9d3885e2b3e6a8587e6c59e02afa0">HtmlHelpIndex::addItem</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a92e0ed943a60680559a637016d45b14f">MemberDefImpl::addListReference</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad736f00784a47fe1c1bf6317f9a1b51b">addMethodToClass</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4ad5866bbc8d144423fe0e3f54ecb0cf">addModule</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6757f2bac4ad1e755a3b5b41d0fbdf49">addPageToContext</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a681582d0e894782b9509baa541931151">Markdown::Private::addStrEscapeUtf8Nbsp</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ac9fd711b7dd6cbbefb87ab903e540b31">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afe5f7e6498fa0fb5d155c4c0a86e46de">buildListOfUsingDecls</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aefb94fa4d5f207d7a1aa6c7fb5ab54b5">convertFileId2Var</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a08216fc437af3c55e1b7ac51430744f9">Portable::correctPath</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a22fc3a59333345115c87ef3474369ba4">findDirDocumentation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5799cbe90654271460f7384c5c6f1a69">findGroupScope</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a043364950b2274c362fdd7e6b48d6ef6">findUsingDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#a3eea3729e8c341a13f1976a0ffea49be">fixSpaces</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#ad150b78be80374eb1373be71e75a67b0">format\_warn</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a080345cfde4ece732f42ded5413ea957">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a>, <a href="/web-doxygen/docs/api/classes/reflist/#a1fb6f991a5826241faab676ba08fb5e3">RefList::generatePage</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2c4458b0e27e9b97db254d082d1487d2">VhdlDocGen::getClassName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a0c4c6cd48e43f74bf258851f8b109faf">HtmlGenerator::init</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1193619fc22f8093dc4096b092165b96">linkToText</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a5893e87386908aa95d70f866f340b8a8">makeDisplayName</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#ac849416c926bc0f8cd8bbb1f76c22833">makeDisplayName</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a39bb7d9a1e431158cb3a423215f044bb">processTagLessClasses</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2c01679fba857523a2ffe9007352e3bf">stripIndentation</a>, <a href="#a55053c8ff88afe6d960df1eeb49d517f">substitute</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad17beb87ce167c3b4203b5260ff7b2a9">substituteLatexKeywords</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a6e909c1b38e02a4536e16a33790ddca0">ConfigImpl::takeStartComment</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a081f10e7e8dd317e08b1596950abdb17">ConfigImpl::takeStoreRepl</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a998060bb7c8a5948956b7ccf192d62da">ConfigImpl::takeUserComment</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a2769e7f4b078110dae0ca454481d5e41">unescapeCRef</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/message-cpp/#a4149b6b3cb3e0246eb2e0d47de02538f">warn\_line</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1d51f3aad1177695f1c4a6c1340bfa0b">MemberDefImpl::warnIfUndocumented</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af38aa297b15715ebca7acecf3144d839">writeAlphabeticalClassList</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a8ccb483586d18bd75a15720be22f90cb">writeDefaultLayoutFile</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#ae8e105816d60cf56b75c2d13f9d85048">writeJavaScriptSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a4546e1dafb6db9b26352c6c0aca8f0dd">HtmlGenerator::writeNavigationPath</a>, <a href="/web-doxygen/docs/api/classes/plantumlmanager/#a536c4c6840f0660a5084d7bb1e32ff18">PlantumlManager::writePlantUMLSource</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9114c68d96141e80c08efdd497fc010e">HtmlGenerator::writeSearchData</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1fd6971ba73b744d9ceb90478194d61d">HtmlGenerator::writeSearchPage</a> and <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>.
</div>
</div>

### substitute() {#a55053c8ff88afe6d960df1eeb49d517f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString substitute (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, const char * find, const char * replace)</td>
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



Definition at line 757 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a55053c8ff88afe6d960df1eeb49d517f">757</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a606914bff961461e7ff377c2c07713d4">substitute</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *find,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *replace)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a606914bff961461e7ff377c2c07713d4">substitute</a>(str,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(find),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(replace));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a606914bff961461e7ff377c2c07713d4">substitute</a>.
</div>
</div>

### substitute() {#abae2b8bda3ecfa394b9c8befdd1608ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString substitute (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; src, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; dst, int skip_seq)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

substitute all occurrences of <em>src</em> in <em>s</em> by <em>dst</em>, but skip each consecutive sequence of <em>src</em> where the number consecutive <em>src</em> matches <em>skip\_seq</em>; if <em>skip\_seq</em> is negative, skip any number of consecutive <em>src</em>

Declaration at line 761 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>, definition at line 518 of file <a href="/web-doxygen/docs/api/files/src/qcstring-cpp">qcstring.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#abae2b8bda3ecfa394b9c8befdd1608ce">518</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;src,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;dst,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> skip_seq)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || src.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, *q = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> srcLen = src.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> dstLen = dst.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> resLen = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (srcLen!=dstLen)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(); (q=strstr(p,src.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()))!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; p=q+srcLen) count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">    resLen = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()+count*(dstLen-srcLen);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// result has same size as s</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">    resLen = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result(resLen, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *r = result.<a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">rawData</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (p = s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(); (q=strstr(p,src.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()))!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">; p=q+srcLen)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// search a consecutive sequence of src</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> seq = 0, skip = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (skip_seq)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *n=q+srcLen; <a href="#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>(n,src.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),srcLen)==0; seq=1+skip, n+=srcLen)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">        ++skip; </span><span class="doxyHighlightComment">// number of consecutive src after the current one</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// verify the allowed number of consecutive src to skip</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (skip_seq &gt; 0 &amp;&amp; skip_seq != seq)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">        seq = skip = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// skip a consecutive sequence of src when necessary</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> l = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">((q + seq * srcLen)-p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">    memcpy(r,p,l);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">    r+=l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (skip)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// skip only the consecutive src found after the current one</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">      q += skip * srcLen;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// the next loop will skip the current src, aka (p=q+srcLen)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dstLen&gt;0) memcpy(r,dst.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),dstLen);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">    r+=dstLen;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac32a77e081e980d3a32c45578b7be389">qstrcpy</a>(r,p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">  result.<a href="/web-doxygen/docs/api/classes/qcstring/#a747c587f5fee7b891e52909aa309323e">resize</a>(strlen(result.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("substitute(%s,%s,%s)-&gt;%s\n",s,src,dst,result.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#ac32a77e081e980d3a32c45578b7be389">qstrcpy</a>, <a href="#a19faae287d13ccea75b1d5a0eb110d97">qstrncmp</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a5f5c9dc172d638c8d7b07010d100117a">QCString::rawData</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a747c587f5fee7b891e52909aa309323e">QCString::resize</a>.
</div>
</div>

### substitute() {#a84c295f784c9b8da3706ee857ba2c70d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString substitute (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, char srcChar, char dstChar)</td>
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



Definition at line 763 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a84c295f784c9b8da3706ee857ba2c70d">763</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a606914bff961461e7ff377c2c07713d4">substitute</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> srcChar,</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> dstChar)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string ss = s.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">  std::replace(ss.begin(),ss.end(),srcChar,dstChar);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(ss);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

### toStdString() {#ac7e12ef0c11e1acc583d1d66404c2557}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string toStdString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



Definition at line 687 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7e12ef0c11e1acc583d1d66404c2557">687</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> std::string <a href="#ac7e12ef0c11e1acc583d1d66404c2557">toStdString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/sectionrefs/#a916946003ecac73c064487bace9e4bde">SectionRefs::add</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a> and <a href="/web-doxygen/docs/api/files/src/pre-l/#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ASSERT {#aca68c0d4ac8df0838e209fb5300f7be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ASSERT(x)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">	if ( !(x) )\
	fprintf(stderr,"ASSERT: \"%s\" in %s (%d)\n",#x,__FILE__,__LINE__)
</div>
</dd>
</dl>

Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca68c0d4ac8df0838e209fb5300f7be3">39</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ASSERT(x)  if ( !(x) )\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">        fprintf(stderr,"ASSERT: \"%s\" in %s (%d)\n",#x,__FILE__,__LINE__)</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#afbafb9f58aa69f3ea191211d77ffccae">anonymous\_namespace{tagreader.cpp}::TagFileParser::addIncludes</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a629f6fc7b319c74df28381ca2e009d0b">addMembersToMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aaaed62b7c9e0ef2c5ba6133eba8203a1">RTFGenerator::beginRTFDocument</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a08a51ed53b0b61d7839aa40d04080f9d">DirDefImpl::createNewDir</a>, <a href="/web-doxygen/docs/api/classes/ftvhelp/#a5949816300bc9d6a104dfd8305aa4e6f">FTVHelp::decContentsDepth</a>, <a href="/web-doxygen/docs/api/classes/doccite/#ac4ad900c3524f1e1451d26329e285acf">DocCite::DocCite</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph::DotInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aec484816eb09040f49038c4b0a999f23">HtmlGenerator::endSection</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a2c3eae0a840500bf1a1713cb0c56efd7">ManGenerator::endSection</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a418d77e54b8be50ca56ec833d4fc3661">DotClassGraph::getBaseName</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#ad566c78a089a671f8b71039f9d00056e">DotClassGraph::getImgAltText</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac9b164379ca75fc12d225af36eac95aa">RTFDocVisitor::getListTable</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a7b82a0f51cdf59c80fb0603b934fa19f">DotClassGraph::getMapLabel</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a2fed991c960ec4565efdeee0fb9b5dbc">DefinitionImpl::getSourceFileBase</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aef70041ddeb0e5767c66089ba24f0afe">DocPara::handleHtmlEndTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#ae14027652a29ff9eda818d4ba6098329">DocPara::handleXRefItem</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a81a742e99f7f1b852d5d77a107ada92f">MemberDefImpl::isConstructor</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a22e3d21cbc976d161981870607dfcdac">MemberDefImpl::isDestructor</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a5f015fb2518181b8efd48daa8426045c">MemberDefImpl::isLinkableInProject</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a44322cca2b89d97eac0bbb4ac2f734ab">MemberList::numDecMembers</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a1717fc701b294ec348fcfb8385418bf7">MemberList::numDocMembers</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#acfb18992e55be4c79b5dad6a8b8ae4b7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a68b868964920e8b88745139cec6789d5">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aca420728eca4e37947593db6a96eadd3">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#af21bb817afa0823ea94983a1d86aea4b">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a6f4df2c3160f09e662393e6a23b2add0">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a8613537dce42682e941104234d73477c">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af69cff788100ddb682f88658018d3969">parseFilesMultiThreading</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae28f1a48382c964843997257b8d171f9">parseFilesSingleThreading</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/dot-cpp/#a3d9eb667db4f11f9bd15cfc0b8fe45b4">setDotFontPath</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a3de3cea0489d29101ce232bbc41789da">setOutput</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ae3bbc191d41c6566b7bafe7a063dd1ac">HtmlGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a3d86ad6fe83fea8f3cb45c0e328ab7c8">LatexGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a4a1ddd2756e83bdc8f6c22c9d46dc01a">ManGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae4e5ba15b96993174f41a6269f233a6a">RTFGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a0332e2befe926de95b367c391a0ac70c">DotNode::writeDEF</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a4be56bbbeefd5d44b58d28f05c446725">DotNode::writeDocbook</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#af2995da196faa8940cca40cfc158b9aa">writeObjCMethodCall</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a> and <a href="/web-doxygen/docs/api/classes/dotnode/#aed2051e58bce93b9250b99108a77ae00">DotNode::writeXML</a>.
</div>
</div>

### FALSE {#aa93f0eb578d23995850d61f7d61c55c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define FALSE&nbsp;&nbsp;&nbsp;false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa93f0eb578d23995850d61f7d61c55c1">34</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define FALSE false</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a5605c0856436662d235515e302510049">DefinitionImpl::\_docsAlreadyAdded</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a00514e707a17d68b52b60218ae7c1dfd">MemberDefImpl::\_hasVisibleCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a32cd3e688d0489c3b35a362162fe7acf">MemberDefImpl::\_hasVisibleCallGraph</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6186d18c10f70c306f913cc9de81a441">DefinitionImpl::\_setBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af8b226a288cd0a1825db1a191d10a760">MemberDefImpl::\_writeCallGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aa9637e278284bc82564b4515fb600608">MemberDefImpl::\_writeMultiLineInitializer</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a8a682f90e07bb6a55566b5941239d23a">MemberDefImpl::\_writeTemplatePrefix</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#aab4159501d3dc8a968c4db08dcfc1863">DotClassGraph::addClass</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a801815bbc24640f7a3cde99b95fb80a6">GroupDefImpl::addClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#accde49592c56f532b9f6b8a45e297788">GroupDefImpl::addConcept</a>, <a href="/web-doxygen/docs/api/classes/ftvhelp/#a8840ba8f98a6049dbe14bf1c9a236b54">FTVHelp::addContentsItem</a>, <a href="/web-doxygen/docs/api/classes/indexlist/#a67dc4e5b8c648a8bd0636a54841c79f4">IndexList::addContentsItem</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a13a18d70232db6c9889f7f473a5cf3d3">addIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/htmlhelp/#a247f8e8a9f527f64cbd47875876ee62b">HtmlHelp::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#aae48ed44191778c99e285f17b7e14377">VHDLOutlineParser::addLibUseClause</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f5e5eea90b425337d1ce80a48c7fe59">addMembersToIndex</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a118dacc3a4f140d0321d4fb170c8e8f6">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab60f2f0badb4e5ea7ab8257b599dc267">addToIndices</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a63736112eb4c63a80176566049bbea24">addToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a63736112eb4c63a80176566049bbea24">addToSearchIndex</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a63736112eb4c63a80176566049bbea24">addToSearchIndex</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7dc5cd0d72ed411b93780d54c8885684">ClassDefImpl::addUsedInterfaceClasses</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aa70e810938568bc5b8825cfb9e367dd4">DirDefImpl::addUsesDependency</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f2a35ddd84e986afdbc14dcba2bcf3c">addVariableToClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a704656a4d637d9f99c1adef34aafe856">addVariableToFile</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#a3682b0b970d4422622723a8abe4d35ca">SearchIndex::addWord</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#a32913d63f72fe21010e49b4f77bc5cfd">SearchIndex::addWordRec</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#ae538f74c2d44222c9a45ef304c89e041">DocSimpleSect::appendLinkWord</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#ae275169a9c2d3322467308254d1a4d0a">DefinitionAliasMixin&lt; Base &gt;::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definitionmixin/#a7dc1bbded3ac0ed218fff164f1da0504">DefinitionMixin&lt; Base &gt;::briefDescription</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afb0da87d7d3ab2047204073d584974ad">buildDefineList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aad0c3ffb33cd6ae914d3e4013f2f142a">buildExampleList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad31622c7a3471af7d6bb17cc8fb29579">buildFileList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a0fe67fd46cab2683e2d10271f90bfb2a">DotCallGraph::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#acda218b5772f482d137ab17020b96431">DotClassGraph::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#ad88aa8095a13ae269eb1a17631909f06">DotInclDepGraph::buildGraph</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a027c847c094e7036e803e3d5e6419136">buildGroupList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a91506ed6aa0fb8cb5d20e9ed27f05509">buildGroupListFiltered</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a>, <a href="/web-doxygen/docs/api/structs/chararoundspace/#a87993e7a5f9850b46ea77092fe036468">CharAroundSpace::CharAroundSpace</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2426bb829c785229969c3052f3e37fb1">checkConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4bd83121097f770a187192b054f59364">checkForKnRstyleC</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4ca7796c0d1fc682a180bc156f3a3514">checkIfTypedef</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3912ae85ed2a97ca1f524ac56a4cff10">ClassDefImpl::ClassDefImpl</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#af0c88e52d4d7424c0840a23a522dc330">classHasVisibleChildren</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a27692f33c86a577ad85ab7176539d4de">DotNode::clearWriteFlag</a>, <a href="/web-doxygen/docs/api/structs/eclipsehelp/private/#a12221dca31acf111429fa7fba8620cc5">EclipseHelp::Private::closedTag</a>, <a href="/web-doxygen/docs/api/classes/xmlcodegenerator/#a17dd450e496129d67a0208dc421cfd1c">XMLCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a6fc7dfce3416355a82991f015431b854">FlowChart::colTextNodes</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a6cc61dde8935f986295262513d2feb2d">Config::compareDoxyfile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab6c1ebf5d50811e57eee6f8d2e201744">computeClassRelations</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#ad85444ffee4818fe7415a7158385f3d1">computeCommonDirPrefix</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#ae3133546e20fd36ac3b7568349ce5285">computeExpression</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#acf058c8bdaf9bc5f58e3b3a2097c4faa">TreeDiagram::computeExtremes</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">DotGraph::computeGraph</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a0c6b9b0bc77f8dd62648d9a7b47aeb9f">DotCallGraph::computeTheGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a75c5c04dae25cb36a4715d0c49a4b196">DotGfxHierarchyTable::computeTheGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a33f8dac0366f837a5880dc420d7c914d">DotGroupCollaboration::computeTheGraph</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a0eb34c13a6a603939648310908c1b6b2">DotInclDepGraph::computeTheGraph</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1876213c101b31a44336d48b6b33e9ec">VhdlDocGen::convertArgumentListToString</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-h/#a4706ae57556b5cab395e8d2c8ec666b9">convertCppComments</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#ad396917a059d354b1ff240b9af3a006c">ResourceMgr::copyResourceAs</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a4a1478cb4a1ba9d12204b6061241a6ec">ClassDefImpl::countAdditionalInheritedMembers</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a8635f06556c6af82953ab2e0797db8a6">ClassDefImpl::countInheritedDecMembers</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a7a98b48366bc0fc41ee0d43eb425087a">DotGfxHierarchyTable::createGraph</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af3e9802567a6e2df20e4714a7aed3807">MemberList::declVisible</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a105e51dc946d1daa2914afd2bc3e72af">DocParser::defaultHandleToken</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#afa510f0e0d64789d3b98a0cf4968d494">DefinitionImpl::DefinitionImpl</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ae4bf0d0561d8ef807b56c1f29765713e">VhdlDocGen::deleteAllChars</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a82a05cf7bd081febd19a0065eed17098">VhdlDocGen::deleteCharRev</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a0f227199a40c25549528bd2f6a721483">determineIfNeedsTag</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#aebbdfe5eff5c5f7d8ed348daed0e44dc">DotCallGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a94ed71ea8772865ed1f494bcedbb9b9f">DotClassGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a8aa3c90f1ef0858e708cb5636e9ed73b">DotInclDepGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a71cb7cce72603b64606e7897c3b90e0b">DotClassGraph::determineVisibleNodes</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab4880c04672f3a3dbf9e7d5f519b845f">dirHasVisibleChildren</a>, <a href="/web-doxygen/docs/api/classes/indexlist/#ae7334e24bfdf93caf3db9d61ae62caf6">IndexList::disable</a>, <a href="/web-doxygen/docs/api/classes/docanchor/#a7dbcc0b3d8792f7eb24a5586609bd020">DocAnchor::DocAnchor</a>, <a href="/web-doxygen/docs/api/classes/doccite/#ac4ad900c3524f1e1451d26329e285acf">DocCite::DocCite</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#a26024c34c8fc5cbe9ba0d57218e17f1f">DocHtmlCaption::DocHtmlCaption</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ad8c12afa5b7d84e2e403af4c3ed30cbb">HtmlGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af41254fa358458e4e1a018477f5107da">ManGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9cd67715e9170630446cb37535f93ac1">RTFGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#ae10270f8c5d7e86d963ef06de1cf958a">DocIncOperator::DocIncOperator</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a15dfb6da7980aee48dc930020b5f00c3">DocPara::DocPara</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#a8094f46edf9a15bf043f5e096124ce61">DocParamSect::DocParamSect</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a027224fbb504c5436845bb85a7c511a0">DotCallGraph::DotCallGraph</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a53601818c690d945d05a971b506bb5df">DotClassGraph::DotClassGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a3e9a28f1f5867cc3d2de69b7db30c15f">DotGfxHierarchyTable::DotGfxHierarchyTable</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a418216c836cb63ef4a243bfb3bc5a81c">DotGraph::DotGraph</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a7916cd8dbb3b48d335e036c9717ac00d">TreeDiagram::drawBoxes</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a24d81fe9c93c2e315bd713aed99379c4">dupOfParent</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad2df37d9e386ae992a5aa98ab9a0515c">encodeForOutput</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a26bdd6b18877aaf31661173ee959b9a7">ManGenerator::endAnonTypeScope</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#aa12df6c60b2975f5b105d2c43450f986">ManGenerator::endBold</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a580084abe1d1b6d45421e654fb8d75c1">ManGenerator::endBoldEmphasis</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#abc7e7b10db0467ec67569096d637bf01">endBrief</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aab1ce69f9718b3c1e05f6c1b697664e4">DocbookGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adeb275db39d63df2f74c728adaa70849">RTFGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2906dcb02cfd455c0d910c9f9501bfbe">DocbookGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a0322020ce9d74181bb997b886239ce19">RTFGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#acca93adef4af10baa753afe68846138a">DocbookCodeGenerator::endCodeLine</a>, <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a2e5d792a6c236db33c8317ace6c4626f">HtmlCodeGenerator::endCodeLine</a>, <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#ad6a36878e0fde7d9d23711fd7487edb8">LatexCodeGenerator::endCodeLine</a>, <a href="/web-doxygen/docs/api/classes/xmlcodegenerator/#a1ae221fa179fd6cb57ffc68bbefaee49">XMLCodeGenerator::endCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a34860cedec3675010f3293403abd9bd3">endCondSection</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a34860cedec3675010f3293403abd9bd3">endCondSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aef5e37d1d6cda8c759cebcd418d91c5d">DocbookGenerator::endDescTable</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa80d2614901e7d7624514fa077cee77c">DocbookGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a1cd78a44f9072b2d24765b07fbd4f01f">RTFGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a4b2e6be7cbbe074a8d2be270a537c454">DocbookGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a87f599a42c46d9fce84f456797ff231c">RTFGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#afc4656a772b508e915c40cd1a2bff488">ManGenerator::endEmphasis</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afda973c4c7b91577d02465015737763d">RTFGenerator::endExamples</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aefb08482f742251ae543aeb57983b335">DocbookGenerator::endFile</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#a1d035c6d2cb17becc47cf8a25764e1a8">DocbookCodeGenerator::endFontClass</a>, <a href="/web-doxygen/docs/api/classes/xmlcodegenerator/#ae73db4a6021fb7e1a49ffed5931bead5">XMLCodeGenerator::endFontClass</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a640f85f2e2b3f829d6561aaed542d20b">DocbookGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1ea96523b003e1da7efde252e0a20ddf">LatexGenerator::endGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a2a48c9be94459c565ab007f5e342d6f9">ManGenerator::endGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afa0db463a17513f4e3ae08e03d6e2615">DocbookGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa1a701e0ab2c31d782a7faae9e0135e1">RTFGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a33cad27a2b5dce6e2762d5915e554118">LatexGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae32c0528c173d54061e225bb9ecac3d4">RTFGenerator::endIndexValue</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a89c09852a70de4a3a971b02f157d47e1">ManGenerator::endInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adc9cf36e3e61b81df2b0ada024366806">RTFDocVisitor::endLink</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#aafe0b4d16ec12528d14a2ff2582bcdac">ManGenerator::endMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a55f5680dbc33ebc6b2a88f93f18eb2e5">LatexGenerator::endMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a76c1ddee2e90178aba880cc93842b1b8">ClassDefImpl::endMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#adc55b02954476c4666dd401825916415">FileDefImpl::endMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ef887c55bb17b0a8022971fcc716db6">GroupDefImpl::endMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8d5eeb539fccd86ae00ce50fb88c7493">ModuleDefImpl::endMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a606af6fee22f1a8c6bbb557cbde9e591">NamespaceDefImpl::endMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a2f0faf7abdfb53dbb1416b1363a172b5">ManGenerator::endMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a73fc0394d91ab6baec0a5bdfa1cdb90c">LatexGenerator::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a639d4d7694e38d646c7b4042f314ca92">ManGenerator::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa2b035a6a0c5223a8108257b88ec47e5">RTFGenerator::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a011b962f233d173e53c61c0380de8b22">LatexGenerator::endMemberItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ae3b1fb5838ed0231423eb95a41173078">DocbookGenerator::endMemberList</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a40a91a3c2f6169232dab1a4ba2133fa2">ManGenerator::endMemberList</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a9f6db63ad970b43690ec22a4558aaea7">LayoutParser::endNavEntry</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a5c191151631efdf0d25fc7967f6b0434">endScope</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a2c3eae0a840500bf1a1713cb0c56efd7">ManGenerator::endSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9fd2d69fc49bd907eb78fdd08c8f7f2a">RTFGenerator::endSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a6684626f228c4b3386f33b9d0e1cb000">DocbookGenerator::endTextBlock</a>, <a href="/web-doxygen/docs/api/classes/outputgenintf/#aad5585b6af901be0830ae54b693668ce">OutputGenIntf::endTextBlock</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a06ee92661f22a8e270e6b1cc538773b5">OutputList::endTextBlock</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a0c856f41b9b3199b3f034a02d7b8309e">ManGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ac9bf05f716351613ceac2c0aae060d6e">ManGenerator::endTypewriter</a>, <a href="/web-doxygen/docs/api/classes/entry/#a8283ac849b1f02ff82ca2ff28253db98">Entry::Entry</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a5ba50f3a46a2d635f06fbc600356ee4a">escapeSpecialChars</a>, <a href="/web-doxygen/docs/api/classes/condparser/#ad4fcf0ce5b9644fb6ff130cf7e335730">CondParser::evalOperator</a>, <a href="/web-doxygen/docs/api/structs/htags/#a459ba4c5a4e6d3308cee25b93448f0cf">Htags::execute</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a21f1fbe9d036424f63e72aad296ccfdc">extractBlock</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a3e870f07917a178b708537e85177a6d0">extractCopyDocId</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ac2acb2b59eeab5ffb2405f30b3c56476">Markdown::extractPageTitle</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a8c6ba49e769f2990693fa40528d3c50e">Portable::fileSystemIsCaseSensitive</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abf6738772e1f2bf741b5fb0868847b8c">filterMemberDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a68f2fb9c7c23aa0812e4e66ee782baee">findArgument</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a89a9f35c62c2ef88e116f4edea12c038">findAttribute</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a589e3e52c7dc0599e7342171a7531064">findDefineDocumentation</a>, <a href="/web-doxygen/docs/api/classes/docparser/#aa75d3dc0424c6b364222f7f357406e62">DocParser::findDocsForMemberOrCompound</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a019e4dfdc4fe1a34460b8f7bb8dfe0fa">findEndOfTemplate</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a2660af8b42d7358b222bac43669eff30">GroupDefImpl::findGroup</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a000332499c2ed82b4b4e2f0318bc98fa">findInheritedTemplateInstances</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a767fe9c8dd14640cc99a6f1c9e0981c7">findMemberLink</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a23431ea304445dd70df98e4c0a367ec8">FlowChart::findNode</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a52d28be272ce56e336d53cec31a62c18">findObjCMethodDefinitions</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8cb9252694dc27b52bd30efe903f9654">findScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f26028922a120817dd5292aad1bcef4">findTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a3781c16868efac71398e5436f519ee39">LatexDocVisitor::firstRow</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a96730086e79b6790b6269d07152a1735">forceEndCondSection</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a53124fcb14c157228188e339625da475">generateBriefDoc</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa723e85238b66b5916c25989013e52b8">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a456518c674e7ae8f45d4eea8935bdc38">DotGraph::generateCode</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a41448de2244811dc71fc91a111c2012a">generateConfigFile</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3eb9720ae877e5d2ae987bce9c91f6a2">generateExampleDocs</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a2945edc16c199a62e84ee85d81b9c854">generateJSTree</a>, <a href="/web-doxygen/docs/api/structs/ftvhelp/private/#a2ffca7a7650eddd1fc37799566ba38f5">FTVHelp::Private::generateLink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a541a7f1681d4e6c18ba0fb4902f2b9d3">generateXMLForFile</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0ab63cb2f20e16fa82b9b687d2b4b00">genericPatternMatch</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab2ea86daea5714c6e35d4ddc62777790">getCanonicalTypeForIdentifier</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad4426e053bb11589c58bd5c6828817e2">getFileFilter</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad8f45edef0c9f7b3b0468e6fdb7cef71">getFilterFromList</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a504e4bc3498a0866fed7ca24f0b6140c">getFortranNamespaceDefs</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a22ca0992a85719c162c23eb696be6608">getFortranTypeDefs</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a2111383c92568a7b28fe96bf69a9f4d2">getGenericProcedureLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aea75bbe69de2d8ff75d41a40df878894">getLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa48141b866dee2454e4290a3c34d36bb">getLink</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#ac240a5eb77b55528937ec68a24cf4f46">getLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aa3a78394ea3d7dee51703f8f0c1e3984">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a7b82a0f51cdf59c80fb0603b934fa19f">DotClassGraph::getMapLabel</a>, <a href="/web-doxygen/docs/api/classes/dotdirdeps/#a58cb594d19e399addcb0280b54f3282d">DotDirDeps::getMapLabel</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a20d5e5fc185059e80b4c080a28ba550a">DotGfxHierarchyTable::getMapLabel</a>, <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a247386ccd7fb55bc0c2e9a6f8e9c54f5">DotGroupCollaboration::getMapLabel</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#ae40c9c4198c440c72aaa52f8f1ada8eb">DotInclDepGraph::getMapLabel</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a64abc1e2247e925f2abbdd81045b8e08">getParagraphContext</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4612a718016bc1025654d36cb9c463e">getScopeDefs</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ac822c6b48f2ab655bbcce33fa1ecb08c">handleAddIndex</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6a6c955c9001d67e4b722038bfc5f16b">DocParser::handleAHref</a>, <a href="/web-doxygen/docs/api/classes/docparser/#adf24a6cf025048b8a3235ca2c897dc06">DocParser::handleAnchor</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a968755490a830e175e145c7086125eca">handleAnchor</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a422a34226cb25bf49c86ab53179982f0">handleBrief</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a580caf57dbfc986a4cdffaa3917d08af">handleBug</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a9c6187ac1215e06d9ef6aaf8d89a5d1e">handleCallergraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a33a7bf2a8da2f085cb6960f34b148b0f">handleCallgraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a26e275caf8c4c3d525ce78b8bd18198c">handleCite</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#aae0be669a4a011f38a4c48074230171b">handleCollaborationgraph</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a3df5816f7dcd092e39a99ebaf9b983cf">VHDLOutlineParser::handleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ade88a4c61e8a4531bd463e282b920db8">handleCopyBrief</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a0fa9d351b497ea662b98090d97fe3ac3">handleCopyDetails</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a8124a429f838fb13cfa3819cbcb5ad5d">handleCopyDoc</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ab3c79a9b99aab35904be7d153ab383d4">handleDeprecated</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a07ceab8f5ec647391e3baf319babba5f">handleDetails</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a755f5d4de658f6156ce72172d3e24542">handleDirectoryGraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ada75e9a5f667868c728b9bc27b4a40b0">handleElse</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a5e077fb2a80dbb11a1acdc0a6cda4fbc">handleElseIf</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a742aeafcb6cf5861b225a23f9b55281e">handleEndIf</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ada657b4767e050871f11c68def40acb5">handleEndParBlock</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a3f2ea29cba64181dd958f2acc131423c">handleExtends</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a8ede19e44f3156ac248ff9d8b9cf04e9">handleFormatBlock</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a2091fb8cdb54f6e43678c5d4ce532469">handleGroupgraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#adcab016dfa7de6a54277bfe6aff9ddf3">handleHeaderFile</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#af1e9df10f186bddb5d9888efc81ba818">handleHideCallergraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a2b88a7a4f541d6d5a808e301bac2a380">handleHideCallgraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#abc733a7086c2df0022aafe09678de960">handleHideCollaborationgraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a51ab05a2e19ace2e0233dd90ecd3a640">handleHideDirectoryGraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#aaaebea058d7bb6caa103a18fa2e05171">handleHideEnumValues</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#aae9163047583cba37cf1f70ca2ce8e0e">handleHideGroupgraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a5958d48ce6f8d355f7cd8630647c4de5">handleHideIncludedBygraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a06521895600caf6a84ef12871b26365a">handleHideIncludegraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a9e9d3f7f6e1f1fbdbac9e6a8b790289c">handleHideInheritanceGraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a98e73ef64aa8182a8543f67d8ebe73cc">handleHideInitializer</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a91e04586c245c83adf086ac35506dc01">handleHideInlineSource</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ac24d93012eedb781b01d189e253f2651">handleHideReferencedByRelation</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ae8de787e270e335e74801c5ca8e96952">handleHideReferencesRelation</a>, <a href="/web-doxygen/docs/api/classes/docpara/#aef70041ddeb0e5767c66089ba24f0afe">DocPara::handleHtmlEndTag</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a9b60e3bdd311d784431944cfc85f19c9">handleHtmlTag</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#aa0c8605aa52c4b08d3989c43368091b8">handleIf</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ab1d205c94977af7b661858d2345a6c06">handleIFile</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a8df09ed2f1060ed76a4e2987cfb5e04d">handleIfNot</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#afb23a285916fb6a46b49aef3dc567ecf">handleILine</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a0ca04f9cfa633f92d16cdab66a3635db">handleImage</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ae3321ce556544cc7281b783f2b250be4">DocParser::handleImg</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a42ae063196428f3d092eaeb9ac31c5d7">handleIncludedBygraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ab4b9cb11fce1c4b192a2d1ffaeac474e">handleIncludegraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a33e08dfa6cf4adde44a2c886677e45b4">handleIngroup</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a71d48fb389a4f80284ba3a08448188f4">handleInherit</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ac6f2811c13f5afdc6966f8985ff9908c">handleInheritanceGraph</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a1caeb5337611ff5e3be1e08b919bc5e1">handleInternal</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a7847b1ebabecaa07000de24502380aee">handleIPrefix</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a2b36e66819497a4d6a99d1e8307a2ebe">handleIRaise</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a20da57a8aeff33be71ae5c46daeb659f">handleLineInfo</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a603bd3eb125dd0477fbb6a52a1dea540">handleMemberOf</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a95d9407b2895ac9ae0d5fbd634021386">handleNoop</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a227b28f553a288cf1925c2efbdf4ccde">handleNoSubGrouping</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a17fdaa3c2d1cc3d4e3def1cb20116125">handleOverload</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a9da26fca3129c98c71b5248d8e292034">handleParam</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aae0b93eceac30fcc7b8bbb6795b588a2">handleParametersCommentBlocks</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a474887b8878a41eb2abf8ab378b6e847">DocPara::handleParamSection</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a644f36935a906ed5fe52451f4768420e">handleParBlock</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a94f06b2f61c71069d46589a7cd4f7b6b">DocParser::handlePendingStyleCommands</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a031587be1e35053a1fa93b75e6ad0d0a">handlePrivate</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a6718ab856136f18aa500d2a518561af0">handlePrivateSection</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad61a4940867df9247ba1edc9b8e92e00">handleProtected</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a16166d777055b65abf64c9df225f0c67">handleProtectedSection</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ac2ef32c42f2cc892d78fd0a2d64b3b6b">handlePublic</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#afbaafa1a9195f81a1a82d19004aa32d0">handlePublicSection</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#aba140d18ad5652de452cd29781026e43">handlePure</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a20d9b6e52302972dea85a3003cb39b2f">handleQualifier</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a5a5d993fe3c3559fbd40d63a771cfe7c">handleRaiseWarning</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a849eff1ea5580b8881c98fb56adc383e">handleReferencedByRelation</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a58825afc0e75a21c2219b2db384a318f">handleReferencesRelation</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a4232dbf936275889906e65aae252d243">handleRefItem</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a524777b747acb0d347996d73538b5703">handleRelated</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ac3dbf128433ccc2955d65ac9401fd537">handleRelatedAlso</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ae9ff87e31efcc5b93a5c2e3078eccf0e">handleRetval</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#aaba9d904cd1dd75b4778cc6c86ae27bb">handleSection</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ae29ee0d740902d01fdce8fe26d7c2b09">handleShowEnumValues</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a1d35dad8bf661b981bda19a39722ac0f">handleShowInitializer</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a38a10c0269af20d21f4422db0c125591">handleShowInlineSource</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a04534e1c41f2c421346fb9f313e2b737">DocPara::handleSimpleSection</a>, <a href="/web-doxygen/docs/api/classes/docpara/#af621e2f0d576fff189b3d94552edec15">DocPara::handleStartCode</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a0cd5ccdcbeb1c5a7cf7dad5d1a9cafc0">handleStatic</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a92d044475f815e09877c88ce15399802">DocParser::handleStyleLeave</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad010a22f512818ee157ce84151286d22">handleSubpage</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a27caba3a7e8672402a1359a04bdc7020">handleTest</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a635a7915c47893c3aa1f40fbb9d288ac">handleToc</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a7757fdd62fd640f3f400ab01881bf121">handleTodo</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a18c4e96349c8a284ab238f9dc94b4bb1">handleXRefItem</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a566364d58b27f9c2324d9caeda697818">hasNonReferenceSuperClassRec</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#aea3a811bebf636bd4cd8abfa2c50d655">DefinitionImpl::hasSections</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac8b51a59c563eeb4756d181947a53260">haveEqualFileNames</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#abdf9b003ba87f85ee86bddb73602d302">LatexDocVisitor::inColSpan</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a845dbd3ae2411806af834800ba1c0c5d">PrintDocVisitor::indent</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/private/#a7e6622cb09d8dd82606e9ab5262802d5">DefinitionImpl::Private::init</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a27ef42f7f738e8eef6801d5f701b4b8f">DocTokenizer::init</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a2dd347b6be51aa404a4e6bc679736606">MemberDefImpl::init</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#affe329b2bcd94b04290e03afad9c97c5">initEntry</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a9ecb445c39b769e5602ca96de2e93323">VHDLOutlineParser::initEntry</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a451cff71879d11897907cc8c2102bdcb">initParser</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a451cff71879d11897907cc8c2102bdcb">initParser</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a451cff71879d11897907cc8c2102bdcb">initParser</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a22addf63e54e56357d7a2691022828e1">initSpecialBlock</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#aa1fd664818291e7a90ed2ba46a0f44a7">initTriDoubleQuoteBlock</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a2aa292ec6b6ea81860b3d9b00405d1cb">initTriSingleQuoteBlock</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a9168d2796d2b37ba82cc27bb4918c6a1">LatexDocVisitor::inRowSpan</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ac0459c77618d5abc77955af74d8fbcb6">ClassDefImpl::insertBaseClass</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#aae7c161ee9febb2cb5ea6ed3dc74176e">GroupDef::insertMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#ad7b02bac5d0ed254d5c979b19cf4ae1e">MemberGroup::insertMember</a>, <a href="/web-doxygen/docs/api/classes/outputgenintf/#aa837f5a6ce555e11398b3df3ecb3e88f">OutputGenIntf::insertMemberAlign</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a8a0967d0442047bfe07a5644505c2d68">OutputList::insertMemberAlign</a>, <a href="/web-doxygen/docs/api/classes/outputgenintf/#a2082c126cedbfc6c0491fc8b96ccba7a">OutputGenIntf::insertMemberAlignLeft</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a1d117e436431c6c8976e8e1e3167b20c">OutputList::insertMemberAlignLeft</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a4ddceeda3319a2ba878acc54cca4e70e">ClassDefImpl::insertSubClass</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af3eab25ba334db0ed299983b354a89cb">ClassDefImpl::insertTemplateInstance</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#ab5e581e18e98e7d8c3394a28791d7680">insideBlockQuote</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#af5482286b814ee04eea804a9a3261cf4">insideDetails</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a8ab563dcf6c027ecdc4b8df7c79cd166">insideDL</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a786afe8925235dea586eb23046acaf41">insideLI</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#af8c289300738a7353cb8e47d343e7998">insideOL</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a66b237bbac35526d7fa7b944ca815088">insidePRE</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a9daef16ea8fc3793c36c55f3657c6d29">insideStyleChangeThatIsOutsideParagraph</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a2515a32b6dfcda676ef65dd34fad5abf">insideTable</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a1f32f1e06f22781ceb8f7295ea6fca01">insideUL</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1134e2b743d328fd1dae53c2f229ae42">MemberDefImpl::invalidateTypedefValCache</a>, <a href="/web-doxygen/docs/api/classes/definitionmixin/#acc207912ee434d4be81444f20f758c42">DefinitionMixin&lt; Base &gt;::isAlias</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a01336ef49f88d4dd7f574c3db13ad774">isCastKeyword</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8a5218dcda2be9cbc949b95713dad49b">isClassSection</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ae291c1cbee2c4f673156c84666e768f7">isCopyBriefOrDetailsCmd</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a5020cd234edf836bc332c91d073b3a75">MemberDefImpl::isCSharpProperty</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#aef2b269b13f233bd8773f2b7b8365443">isDocIncludeVisible</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#ab101b8a2d6b5ea85218704fb93f5f079">isDocIncOperatorVisible</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a9c6cff6722985f4f25adf4b7daa99b30">isDocVerbatimVisible</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acea395582e617dd69781da74f320161e">isFencedCodeBlock</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#aabc6c0e6b285c280ffa531cace06e2e4">VHDLOutlineParser::isFuncProcProced</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac231c8ffe50ea474d33cacd7c3d14b77">DocHtmlRow::isHeading</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8f467781860833d1c098d3e80e52c04a">FileDefImpl::isIncluded</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a453c41aa80dbd5bc968846b8c012eee1">MemberDefImpl::isObjCMethod</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae74d134ea251e91ac8ea3e2f1774f434">MemberDefImpl::isObjCProperty</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a66144b339b4b4744d7d7ab092ed16e34">DirDefImpl::isParentOf</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a738d45232dc0fca703f9e9042acae9c0">MemberDefImpl::isReimplementedBy</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#ab6b89b7570220507ecccee5aa2872f30">isSeparatedParagraph</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e75c43e09005a52234052e684a5f7f6">isSpecialization</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a00883ff38c8750298ceb59e13823e52b">ClassDefImpl::isSubClass</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ac7d0f125a2bffca08e8c52644bf8c6f2">VhdlDocGen::isSubClass</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#aefadebc5df285d25ef8121a87639323e">isTableBlock</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a4f66d82e77635c3fdd4ccd92effea216">DotCallGraph::isTrivial</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a7c1f6b996a142fa44583e8f115a00d3e">LatexDocVisitor::LatexDocVisitor</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a37b661752d147469cfe557cd651763c9">TreeDiagram::layoutTree</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#ae196a1929c47ffea2e32ab8d321943d5">ManDocVisitor::ManDocVisitor</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#afd4e9dc2db18f93819d8fbddf554efa4">VHDLOutlineParser::mapLibPackage</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf988c072b1ab9b4934fc04e430f9925">matchArgument2</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0a8299ea0705cebde431ef0ea600fcb1">DirDefImpl::matchPath</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a3e36f184f58e200b6913d383d5ec1a46">MemberList::MemberList</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a9b31309c5cf2471cbe9622a64f969473">membersHaveSpecificType</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0baa021dae80e22593292b12ef2f721f">mergeScopes</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a86acf8b4839daaae86b0a90ca98767b8">mustBeOutsideParagraph</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#acca4ea7f41c631ad64fc467e7bb24615">nameIsOperator</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a69493ea3c18566cbc3813c1b7a787321">MarkdownOutlineParser::needsPreprocessing</a>, <a href="/web-doxygen/docs/api/classes/nulloutlineparser/#a31b8a88ad4b022d530f92048653ccb96">NullOutlineParser::needsPreprocessing</a>, <a href="/web-doxygen/docs/api/classes/pythonoutlineparser/#a10ad0ad24a8f0fd0e8cb537c63c6254f">PythonOutlineParser::needsPreprocessing</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a19bbf6e08804ee457c7aa9e07b833ba0">RTFGenerator::newParagraph</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a551a021a6f4d4732e5181f8041375066">SymbolResolver::Private::newResolveTypedef</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a4e52d619e02e6a48b41aa65affcac398">node2URL</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a11601f7b8b08cb9600482e5dc3bc51c5">normalizeNonTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/structs/eclipsehelp/private/#acc4a667c06a06048f0c8aaabe5a6ad66">EclipseHelp::Private::openedTag</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c6662051d765cb0a355382ab05c14a1">openOutputFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a1abe1e85619493e4e99240d290c3bdd2">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a942b617cd956361afbd314539cab5922">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aa5dd013610540bba019aaef10157b416">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa9e3a7cf34aceba68750ff3ff94acf34">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a104c3ca52ddda7596a073155996e8214">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a5c64416b51edb6f80d0be604b4cbe0b3">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a9a6e493ac6aef6d638ead4ad62e4580a">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a1c6b1244f9d0fc6df4f0d66e505e5437">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ac11bc06b22732d6e550dc8382badd38f">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a4336aa37be77360c412335358cd88b46">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a678591cbca0c1070b7a8803d3c5541c7">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a41c844f5b9078d32e11a14b45b6f5c2d">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a806029951b075fcd8c430498bd0f2375">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a6f8aff45c8c934cda5be07107de10c77">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a41aaa90a6a3c9ec728048cbdb927c7ae">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a330c52431e7c540fcea7901e74c70da7">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#ae151cc7686cf768f2e7e91002bac8dcc">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a9dc07bea7c5f6f69559f84793b9193a9">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a611ec420e06726e8061f4fe83c3f8a6f">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a1385e8fb9c9effec554143178bd5f5ac">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a9becdb1d4b3096f9081710f0c6c14e80">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a8bf41fa80034e1477e1017f19f89d4de">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a3135258f772ad9dcb6c936b55f913543">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#afb7a0185345e8311efd7d18827dbe43b">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aff22dba562419dc8b2498e0a3864df37">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a315f64205ff8e9d75ddd63e31f068269">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a717055210b0bdcd869a71a36a62690cc">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a9a33176bb13fc255cd7d8c062d113578">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a6a9734f16f6d5b0ab24039d710af84cd">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a2993bfecac33a60da6408f79586b7da2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a74283afcc3656534bef009b917a9f525">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adc374c79a2895d83e349ffc76358209e">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a4af0a6415a019a1051dda0dd4d56dbef">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af199af5695c344c4730378ecfce43079">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a70c61ff58fa9f747fc2b971c689a09ff">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ae0c5c194fc2579df52204eb00134c6bf">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adae81723bf98cc11856ec916852cf089">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a2851bbf082cd6f2a85d6c9fc7a1050c0">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a63f63207a160e4e99a4c2dd5b55734c8">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7a5ce880ef222be6eeb6eea7e12b78b8">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a75e708a4ea1b27587678f424211b8b62">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aed6822c7504330f96cc764e333589e7a">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a23778040c53c76ac927398e0e728ffb5">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aeb7edc62cad5a541849845d2bfe030e9">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a9bc7acec72efe2239cb6c798855ed08a">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#add264d5a56e09e76ec274af99af747d2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aa17fa64bc141c519b0b24e0a475ab1e1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af3beab942bf46b1f903ac30ac39a10d2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8123582499bf0458dc938ff66c4724e7">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a74f1097897a6deaeffd0ca3ca9e5c811">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af154c4b8688beaef882211c40763fec3">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af039aed5400d69cb1776431f44f90360">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7f10a43fc0a35475e9078305d745951f">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ad59ea834b25f5117addb171ba0ec6259">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac9c8677143c5ae39bcfedcdac6b518a4">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a608907da6a8263ac7cff6caae01673c9">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac219ce4773970158e118d1d3b57ebd78">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a3a2acf19e70d566ecbaec05b214a437d">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a71b99c9086e5c3e82c7947cd9f256eb9">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#aac3356483b754f0dab670ad4a1407f98">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ae2f1f49b8496f09377c4e7de91e2f3d6">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6006a1443e18366206b8485ee2d7b8a3">DefinitionImpl::operator=</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7c2f6b00d96563acaa44afcacb217b9b">organizeSubGroups</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a3b619a4fc6ed1af839392d59ec20b0e2">PageDefImpl::PageDefImpl</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a88f642289a7ff2d625c726cc4777b989">DocAutoListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlblockquote/#aa64ab14e969b672324338c1be6b607e1">DocHtmlBlockQuote::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#af23dec8c6549a7a73bb69037f5324c70">DocHtmlCell::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldescdata/#ab176f44cd7bc955df0c352bd714e4e1c">DocHtmlDescData::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#a12b425f8cc20de1ed4183ea8a9a454f8">DocHtmlDetails::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a7c0ac2e655d8a3cf7deb76cdd23e95e5">DocHtmlListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#afbeab8f03e2ef431c05b8d3bcb6291aa">DocHtmlRow::parse</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternal/#ad783a8507dd1e64ad38a889d9fa7a851">DocInternal::parse</a>, <a href="/web-doxygen/docs/api/classes/doclink/#aeb676914fb893fa31c99b39c1f7bb6d3">DocLink::parse</a>, <a href="/web-doxygen/docs/api/classes/docparblock/#aa0283029f3578c44cd54c93d648bd909">DocParBlock::parse</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#a3e4b28664b6fe921f89c934f9d2f4ba0">DocSimpleSect::parse</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/ccodeparser/#a106ea78aa6382f5b06dbd2563d5b99e4">CCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/fortrancodeparser/#ab7216957ad8abace8578d47edd8b578d">FortranCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/pythoncodeparser/#a7f8b5638c6d0424a1de9bc6905041ab2">PythonCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a336a6313626a3a3931e2086fd507bedc">parseCommentAsText</a>, <a href="/web-doxygen/docs/api/classes/commentscanner/#a2e48aae075e2f44ddd785428b4099f4a">CommentScanner::parseCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a3383c871b9fd5e4b1cf4a549de88a1f3">parseCompounds</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a410946c3855fd51f18485d6e3dcce59b">DocTitle::parseFromString</a>, <a href="/web-doxygen/docs/api/files/src/declinfo-h/#a4d239b57da0bda3d616434d8a2250546">parseFuncDecl</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9f4758858cac73d07721ea31f42bea8e">VhdlDocGen::parseFuncProto</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ad6df9d0420902e8579fb9dbbfa5c1a90">VHDLOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/classes/condparser/#af63a661f43a32b9343e6b222661bf206">CondParser::parseLevel3</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a434a1f775b7fe0a37ad69ba2499cfdfb">parseMain</a>, <a href="/web-doxygen/docs/api/classes/fortranoutlineparser/#abbe1b29c5797729e3aa2dcd693e46755">FortranOutlineParser::parsePrototype</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a3931b4604b8a76ac26b7380a585ef543">FileDefImpl::parseSource</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a>, <a href="/web-doxygen/docs/api/classes/condparser/#ae984d41f533dbf4306ddbffe725e272e">CondParser::parseVar</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a48640c52ba4009264ee01b0761663756">DocHtmlCell::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#ae1c82a584506da65bd320d481f774854">DocHtmlListItem::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a10bb2141d4a0d7867a97d829794184e3">DocHtmlRow::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a2a913b8204fc7637dea2f3783da7b1a2">DocHtmlTable::parseXml</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a147c750cdb85c41305baf5ccb8dca305">PerlModDocVisitor::PerlModDocVisitor</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#ae2407880f57f0b80f4f803d369776189">DocTokenizer::popContext</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a45d99cae5ecb12b8735454b57c505e42">DotGraph::prepareDotFile</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-h/#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a772414bc571e725007f1c8bc15ebb355">preProcessFile</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a33f1f9f82bc9683769a6be6cdfc76270">RTFGenerator::preProcessFileInplace</a>, <a href="/web-doxygen/docs/api/classes/statistics/#a681d86ad7e9121de36d517420e135415">Statistics::print</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a67435323587e5a301e8839b42c2112f2">PrintDocVisitor::PrintDocVisitor</a>, <a href="/web-doxygen/docs/api/classes/preprocessor/#ab3f6062c1f94727e3d51963720d13417">Preprocessor::processFile</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa4f4085dfd3e73ae354c7cfd6fa69faf">Markdown::Private::processHtmlTagWrite</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4d2f69fa42eae96d0b7ca66f9f0673ae">readInputFile</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a1ee465ed3ecc9e198028ac98d6536546">readSVGSize</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#a11f1e398e07986ff1b2977f361e9eea0">recodeString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c3775d3cb6b3776c441a4451d49bb2c">recognizeFixedForm</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a44044c70833211203ece26ccb6c56a5c">recursivelyAddGroupListToTitle</a>, <a href="/web-doxygen/docs/api/classes/reflist/#a36b770703f31caac7df3873136d3d747">RefList::RefList</a>, <a href="/web-doxygen/docs/api/classes/parsermanager/#a150d4d51073cb46cdf38a236cc120d0a">ParserManager::registerExtension</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a50828408023d08f28ef9b6071fd8ac52">renderMemberIndicesAsJs</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a191edf3c31405fc032d0277a553cea99">renderQuickLinksAsJs</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a43d00492ecd78767dd0bf065cc3b8f9a">replaceComment</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#af63051a24ce92667516c4f9a80e08619">ArgumentList::reset</a>, <a href="/web-doxygen/docs/api/classes/fortrancodeparser/#a1c7c3401c6526dab5642b59a7c27ebc1">FortranCodeParser::resetCodeParserState</a>, <a href="/web-doxygen/docs/api/classes/pythoncodeparser/#a002de33958d1845af3182ee568649781">PythonCodeParser::resetCodeParserState</a>, <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#af2aa6035c4917cd2d139f59850c5a008">resetPDFSize</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a34157df0fe53d6d10cc4560ca942f488">resolveClassNestingRelations</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>, <a href="/web-doxygen/docs/api/classes/dotmanager/#a3b34d4c3e0ab9e9debe6c7fa45a129bb">DotManager::run</a>, <a href="/web-doxygen/docs/api/classes/dotrunner/#ac1afaee16ddd8bf0bc6b18aaed6b44fd">DotRunner::run</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10e8f1fbd720c602f867aa536e450462">runQHelpGenerator</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a7b2ca28396c488d5a08ead21731ed2c2">scanner\_abort</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad1f69f6dd5f57e967a880988a49aa56e">scopeIsTemplate</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a601173b4a0fe4bb62a0e4749429ee062">searchFoundClass</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#ab61319bebda3e72e8fbde5a911cccc95">searchFoundDef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ed1fdd15e6ed566c33a63fcd30d53c4">searchInputFiles</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ac5533bd798e00c23bb4b0532b036ea8b">DefinitionImpl::setDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#a516a3565cbd64716f4dccc6a8e00bf86">MemberDefMutable::setEnumScope</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a38a736137370a011fe71a0fd9102d151">GroupDefImpl::setGroupTitleLocal</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#ad3f331c1d12e6f5256e749173835b2b8">ClassDefMutable::sortAllMembersList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3f70f1839b2009262b36b6f28c26654b">ClassDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a38dfbb5daa66a820f49167beecae6e90">FileDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a2a3b6387c4b99adde50e0751493d4990">GroupDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a16de9b0536cf33e6b6380cf55ecb3ca5">ModuleDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ade0ababe591c242aa32049874d07e298">NamespaceDefImpl::sortMemberLists</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a0e4f8662709e4ca7e43e86d1bf4073fd">ManGenerator::startBold</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a401f889dc6da64e77da338c6c59d3a67">ManGenerator::startBoldEmphasis</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ae55e63b38a344ce48c2d9157b92d86a2">ManGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a9b07469696e5391928602edc03e16664">ManGenerator::startConstraintList</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#adf073ca7959a1f7c004bf8c4a79ca151">ManGenerator::startDescForItem</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#abcf93751a8901a09472a39ed04f0c49a">ManGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab575d0e0e347d711d242bdc7fd8c7648">DocbookGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a1176919950e3fe3324720d45ce10f3f2">ManGenerator::startEmphasis</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a6b323886b28fc9f4ba5a87981a2b1430">ManGenerator::startExamples</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac651122c0ac17ea4be13f8a4d71c3efa">DocbookGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a49116184047a4d02f25e75788bc539c8">ManGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a0de19d805d84ae14aff81334a010c9a1">LatexGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aed122d098bf970698797293cabd09b21">HtmlGenerator::startInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a8be5825cc340050d3cfcf29a533a9a4d">ManGenerator::startItemListItem</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a02328f0a76dfca6a9e0d24167905289e">RTFDocVisitor::startLink</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a477b9bf180d9c7a57edcd11c408cdb5b">HtmlGenerator::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af88d2023def435e1b31144653a073e84">ManGenerator::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#abab747cba6e0e0fa51ef95655015b9b0">ManGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aea90b1337254e9c10ceaefcff8b9c825">HtmlGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a1ec800447787c1eada0c828c6d3bb374">HtmlGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a45990f8ba8b86fbb473185345bc34289">ManGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ae579a6cc157e59fba68fbad15dadf6ac">ManGenerator::startMemberList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a287320869b27536a66d09bd7f545507a">HtmlGenerator::startMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#aba3b3876764867eeb32b9dcce3d4b63b">LayoutParser::startNavEntry</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3f2bca76c821f2cde122ebb419a84cce">startQuickIndexItem</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af8bc25cc45d1e7d47e21293e99142fbf">startQuickIndexList</a>, <a href="/web-doxygen/docs/api/classes/outputgenintf/#af2409cde2f7961ca5cf4b967335c5f50">OutputGenIntf::startTextBlock</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a5e4b1b0039100083a979ff8d90adce58">OutputList::startTextBlock</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ae53c0d4f7905f85069f2e253f97f99a6">ManGenerator::startTitle</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#aa63a015c7664c64224acf979cf0a5ef9">ManGenerator::startTypewriter</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a6458e40b3ca285dc65cd5df59d63e5a5">stateToString</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a6458e40b3ca285dc65cd5df59d63e5a5">stateToString</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#aaba2817dbf5f4afbbba5998976dbdab4">step</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a085c52ce4351470497b03309e77228cc">stringize</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a28ac6dbcdb288699accc1a8db6f56cd5">stripIrrelevantString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a8acb7287be03115c56196dd1a1085225">stripQualifiers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78d33655f54cd45e22070b58a6dce6b6">stripScope</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#af14d495cc8aa43bd9a23c357e56b4454">stripWord</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#ac61bfc9dccd1552c036f2a3aabcd6b2c">substituteHtmlKeywords</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6da766398ce7fc4fd2aa252bc2f695b6">substituteTemplatesInString</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#a49316e7efc80b5ea90df2ad2941359f8">SymbolModifiers::SymbolModifiers</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa4a9dec36c09c8c131a0e5e9bb71d98e">QCString::toLong</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#afcfb73b0f862461d60da84504fa4d4cd">QCString::toShort</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a524e1cd9e1c24e91d57b1cb91513fa67">QCString::toUInt64</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a592f86f3d758cb9285967c195f2f1824">QCString::toULong</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8d31136b4f5f614640bd277d49182135">QCString::toUShort</a>, <a href="/web-doxygen/docs/api/classes/translatorcroatian/#a9927bc8269d7047270e3145f9cf26a62">TranslatorCroatian::trGeneratedFromFiles</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4299844cb805de324387ae0072ea6e9d">tryAddEnumDocsToGroupMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4f8196aff5be2c0b8046c45e3830fab">updateLanguageMapping</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#af4fe687f1edd1806dd591c0f165062cd">visitPostEnd</a>, <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-cpp/#ab7f123603afcea6abded6e73da61055c">visitPreStart</a>, <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#ad2b918f141b60e444314ae661cf02162">visitPreStart</a>, <a href="/web-doxygen/docs/api/structs/dotgroupcollaboration/edge/#a1f4c832d9b0e56ecdf8f164784623354">DotGroupCollaboration::Edge::write</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a261123fa5550fbc2dd3b146e18f9f221">DotNode::write</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad9ade8c43232b499c51f41859454a664">ClassDefImpl::writeAdditionalInheritedMembers</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a4a6853a6b7f98f30da5d61d680d86041">writeBitmapBox</a>, <a href="/web-doxygen/docs/api/files/src/dotnode-cpp/#ad9725fc182452b9ca7142e0c7c896bf9">writeBoxMemberList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a64d65000b297d313a09e4c1cca1f17e0">ResourceMgr::writeCategory</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ada0a91f41d4d1225e3cccd4ee2af6aa3">ManGenerator::writeChar</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a56ac172f1d20c008f1c961b76b511099">FileDefImpl::writeClassDeclarations</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a719e711fca31e09277b188749b533b87">ModuleDefImpl::writeClassDeclarations</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#aff9d3f3ca6af9d0f502399bcebf4ef54">GroupDefImpl::writeClasses</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7679fab482cf6175804f959f5425c2b5">writeClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0ac2f4932405d6a1773bea6eb84885ec">VhdlDocGen::writeClassType</a>, <a href="/web-doxygen/docs/api/classes/xmlcodegenerator/#a22f6ad09446c1965714f48e8cbf8459a">XMLCodeGenerator::writeCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aacf6d04a8d8013c15ecc64baa71b6a2f">writeConceptList</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8371bd6939f20291071c410cf7abc1bf">FileDefImpl::writeConcepts</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#acc4bfba39e222cb40c6e1dcc575d0d02">GroupDefImpl::writeConcepts</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#af3bdd9c66370ba1d78612b6d428cb17c">ModuleDefImpl::writeConcepts</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9f3b04775e88a72b563fdd34c6f2646c">writeConceptTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a6e1ed35b84f6375897482fc8b753affd">ClassDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classlinkedrefmap/#a1c99c36b0a60cba930a8a4909e2f72cc">ClassLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/conceptlinkedrefmap/#a0b784a4bcc64f3284b548fdf10a37b88">ConceptLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/modulelinkedrefmap/#aebc005e13bdcb448da76f4b43b2ea72e">ModuleLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#a340fc8ac627f2f84ae3110d5f42480a1">MemberGroup::writeDeclarations</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a202ad1f62e6c27cf1dd83b6355fad73b">MemberList::writeDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>, <a href="/web-doxygen/docs/api/files/src/dia-cpp/#a6791d60c7183801a8dcbdd7e9fc7a896">writeDiaGraphFromFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aa8e7acc156d5f99e61cc895d8f8ea54b">writeDirHierarchy</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a28523fdc2e54ee673f026bd6d46a7224">ManGenerator::writeDoc</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a8c2162d40ea8f7ab188a37247b5b2bb5">DotInclDepGraph::writeDocbook</a>, <a href="/web-doxygen/docs/api/classes/classlinkedrefmap/#aa36e57d8b3b8814f56caff17d0562173">ClassLinkedRefMap::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefmutable/#a4b9b09c4abf89f8cf3f7fdc89a7d1cc0">MemberDefMutable::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlhelpindex/#a90f49f18773a8f5949d7908575996e71">HtmlHelpIndex::writeFields</a>, <a href="/web-doxygen/docs/api/classes/classdiagram/#acb331a908252968ca8ba371ee560aa51">ClassDiagram::writeFigure</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/classes/dotlegendgraph/#a3c9836cd65db658dbf7eb0c6ecf7b40c">DotLegendGraph::writeGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1a22a60346d49b295ceb2b6548a775b0">writeGraphicalClassHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6eeea63b666ee5e1d4ed8c94c9cd4a48">writeGraphicalExceptionHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a3404d9f2140d5db9350105eb28d85034">writeGraphicalInterfaceHierarchy</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a256c275d3b654245e85d7c04e8f417b9">writeGraphInfo</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>, <a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">ClassDiagram::writeImage</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0d8342dd518223a45f160f8b2f081c32">writeIndexHierarchyEntries</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7fb5141ea8877090d564026636d81a14">ClassDefImpl::writeInheritedMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af012e45f04c5da89f11d17770dad1b00">HtmlGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ad5999bc38affc6b599217cae57b813d6">ManGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6bab634f62d558e8d56cb84dee170cd2">DefinitionImpl::writeInlineCode</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#ae7a5c86a2927e880a7c8413e57275811">DotNode::writeLabel</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#acbb488146339ce401624a13e908c95ab">MemberDef::writeLink</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#a631a6b4069c839eeb964ceaba0c012ed">MemberDefAliasImpl::writeLink</a>, <a href="/web-doxygen/docs/api/classes/classdef/#ac598c1ecb31cdb19524cc60cfe312667">ClassDef::writeMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#ab287ccfb0386977fce96aa616e9be50e">ClassDefAliasImpl::writeMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2ee9959a879f505d8e3296acd74f4758">ClassDefImpl::writeMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ade6964f92cfbbf3f65d74d7e1c077069">ClassDefImpl::writeMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae515e3c5baf8a9c7b818a3f492d576a1">writeMemberToIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a419b521d07380b4bd45b61aad7ddb12d">GroupDefImpl::writeModules</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#aefd632b8f888c312d4d67dffa15f5669">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a6273279cbb942fdbf1988a7f5a336404">writeNamespaceTreeElement</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a9e4ef930abbc7603896a126a7744b6d9">GroupDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a31b60db653850e1be9084b27153e6758">VhdlDocGen::writeProcessProto</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac17987f390e01a05dd8a3c12feae991a">writeQuickMemberIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a0332a478a833682cf5d2c547a8397973">DocbookGenerator::writeRuler</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac584b41f75fc411a218e9e684fd491d5">FileDefImpl::writeSourceBody</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a54453287cdbf2f165e6030be1e00b64b">DefinitionImpl::writeSourceReffedBy</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a84a2aa61638b8af08560219e2a5140f1">ConfigOption::writeStringList</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad28ce13d37a783efc856e85b0cdb791c">ClassDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a26fe21b32c7e96c3c50f8cfd2e06e89f">FileDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a1cd6f5eb27ef6ca1ded4532bd38323b0">GroupDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad9a159e7a8e4ed36a862252a284e0d24">ModuleDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#af7fd110aa3bb86ad68c64ff39239d8fd">NamespaceDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#ae41b4e8b1817e1d1de1732e4c4f9069c">DotFilePatcher::writeSVGFigureLink</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#aac22b47b84bdf30579b606f54c36a053">ManGenerator::writeSynopsis</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a21b82aade2e5a369ec438f0cd49f8107">Markdown::Private::writeTableBlock</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a76fe2943fccabc70c52ad3b6e31f4fa5">VhdlDocGen::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a19a78cda05295880aa74873cfbad293b">ClassDefImpl::writeTemplateSpec</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a1e56aa086c8135c76d84de764845c20e">DotFilePatcher::writeVecGfxFigure</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ac45380e90067e3138b21af2a68dc19f3">writeVectorBox</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aa99c6269bf6155f83a12ab796edd4acf">VhdlDocGen::writeVhdlDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0218e5158efa51df8490073c645c9a79">VhdlDocGen::writeVHDLTypeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a28fef240bd687173e6e9184e82bcf391">DotInclDepGraph::writeXML</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a6d391007591f277cd73420b77403666d">writeXMLCodeBlock</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a1f234d06f4ded36681d8976f055d5929">writeXMLDocBlock</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a7c793fb726834b10d3a13071c6279374">XmlDocVisitor::XmlDocVisitor</a>.
</div>
</div>

### HAS\_CHARACTER\_APPEND\_OPERATOR {#a5d8116d29bf5dad9161f0e7309c0a46e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HAS_CHARACTER_APPEND_OPERATOR&nbsp;&nbsp;&nbsp;1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 567 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d8116d29bf5dad9161f0e7309c0a46e">567</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define HAS_CHARACTER_APPEND_OPERATOR 1</span></span></div>

</div>

</div>
</div>

### HAS\_IMPLICIT\_CAST\_TO\_PLAIN\_C\_STRING {#aa138e851b3b64211ce294927a4669b40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define HAS_IMPLICIT_CAST_TO_PLAIN_C_STRING&nbsp;&nbsp;&nbsp;0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 528 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa138e851b3b64211ce294927a4669b40">528</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define HAS_IMPLICIT_CAST_TO_PLAIN_C_STRING 0</span></span></div>

</div>

</div>
</div>

### qsnprintf {#a307ffe8cbc4a4aa695900441d1df49f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define qsnprintf&nbsp;&nbsp;&nbsp;snprintf</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a307ffe8cbc4a4aa695900441d1df49f3">49</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define qsnprintf snprintf</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#af2998873ea2f67f5127f7efd25e947df">addIline</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#af31163d2301e663ef9e750f050184abd">addIlineBreak</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a322962831f30dce16a3323a67d6e2c44">createCroppedEPS</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a751decfa83144bf64f1cd1cb492db3fe">createCroppedPDF</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a704ccf2352fafe16ddf093abbaa6f7b4">createDVIFile</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a92954fc40f0e05879c1726f8d8207b1f">createEPSbboxFile</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a0cc00317e5a4482a2e7df401bd480f38">createPNG</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a57b6802045cb92594d1f65e5b8821456">createPostscriptFile</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#ad88d54d53a499dad6fda6617d2dc952e">createSVGFromPDF</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a0c843eafd8ef0511d939fa5c6efc863f">createSVGFromPDFviaInkscape</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad2df37d9e386ae992a5aa98ab9a0515c">encodeForOutput</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af891990268daeb8713d18d154b84ffdb">findFileDef</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5530a73bd518581ac62e4eee5bc2f6db">generateMarker</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#af1366ac568f1a1620961826edd2e88e7">CitationManager::getFormulas</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a6524e8718f3f956610df4dfc71be204c">VhdlDocGen::getProcessNumber</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2e65f831a03ff54d13240da96843cd60">VhdlDocGen::getRecordNumber</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a8d97a542b3b830868e0cdc39aac6c98c">DefinitionImpl::getSourceAnchor</a>, <a href="/web-doxygen/docs/api/classes/dochtmlheader/#a5f57a370972a9ce3f7aa769973c5d2e8">DocHtmlHeader::parse</a>, <a href="/web-doxygen/docs/api/classes/commentscanner/#a2e48aae075e2f44ddd785428b4099f4a">CommentScanner::parseCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a931044da5493c1d83ca77898996140c4">MemberDefImpl::setAnchor</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aac9ad7a212ab079ff3ac8860577a3132">stackTrace</a>, <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a844e206331cbfc112bffb3470cf77cc7">HtmlCodeGenerator::startFold</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a763d03603a7b427c9f02719fb95b2c30">SymbolResolver::Private::substTypedef</a> and <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a87bd505cf0e4598b8e8ae320087166f3">HtmlCodeGenerator::writeLineNumber</a>.
</div>
</div>

### TRUE {#aa8cecfc5c5c054d2875c03e77b7be15d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define TRUE&nbsp;&nbsp;&nbsp;true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 37 of file <a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa8cecfc5c5c054d2875c03e77b7be15d">37</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define TRUE true</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a5605c0856436662d235515e302510049">DefinitionImpl::\_docsAlreadyAdded</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a00514e707a17d68b52b60218ae7c1dfd">MemberDefImpl::\_hasVisibleCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6186d18c10f70c306f913cc9de81a441">DefinitionImpl::\_setBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a0410c3e0f3f2fd5fdb341546e40d4a7d">MemberDefImpl::\_writeCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1943d02385b57a699cd57587cc68283c">MemberDefImpl::\_writeEnumValues</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#aa9637e278284bc82564b4515fb600608">MemberDefImpl::\_writeMultiLineInitializer</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a801815bbc24640f7a3cde99b95fb80a6">GroupDefImpl::addClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#accde49592c56f532b9f6b8a45e297788">GroupDefImpl::addConcept</a>, <a href="/web-doxygen/docs/api/classes/eclipsehelp/#a9ea6d0cffe6ede5208e4d4079f54ea5e">EclipseHelp::addContentsItem</a>, <a href="/web-doxygen/docs/api/classes/htmlhelp/#a1503b3b4d76049d44a45452d44722d86">HtmlHelp::addContentsItem</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a207d66f561747d53a0df54a5019cc45b">addDefine</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a636b9cfb60b78163bb29dbb6f21def29">addEnumValuesToEnums</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6c4285f255bbb17f7c3d308d222334cf">addGroupListToTitle</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a13a18d70232db6c9889f7f473a5cf3d3">addIncludeFile</a>, <a href="/web-doxygen/docs/api/classes/htmlhelp/#a247f8e8a9f527f64cbd47875876ee62b">HtmlHelp::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#aae48ed44191778c99e285f17b7e14377">VHDLOutlineParser::addLibUseClause</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a92e0ed943a60680559a637016d45b14f">MemberDefImpl::addListReference</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a855be67fd81a52fbfc822a4e4b41cc7e">addListReferences</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a6532b5f6d81ac59549243775ce575b61">FileDefImpl::addListReferences</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ae17a959731dd3bb1a66e7ae827e645d5">GroupDefImpl::addListReferences</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#af8b51e8153660a718610d9b6d45c5ece">ModuleDefImpl::addListReferences</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aee54f1460d363c93a984382365372013">NamespaceDefImpl::addListReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7584c927ee1a6c7747b5e3263fe4e6b5">addMemberDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae11c2fb2e5b6cbe3dcd1a1b594406e93">addMemberSpecialization</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a5f5e5eea90b425337d1ce80a48c7fe59">addMembersToIndex</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#affd271e102af38c14812ccc21a86401c">addMemberToGroups</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf3cf996188e39e9eba3a381563cc8aa">addRelatedPage</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab60f2f0badb4e5ea7ab8257b599dc267">addToIndices</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa48018d80bff3d0e37cd1ff67c5972f8">ClassDefImpl::addTypeConstraint</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aa70e810938568bc5b8825cfb9e367dd4">DirDefImpl::addUsesDependency</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adfcc4c0f77f941956529fe4b579e0475">addVariable</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#af6ecf9ac01a23dc21259b408a314f54a">addVariable</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#a32913d63f72fe21010e49b4f77bc5cfd">SearchIndex::addWordRec</a>, <a href="/web-doxygen/docs/api/classes/docsimplesect/#ae538f74c2d44222c9a45ef304c89e041">DocSimpleSect::appendLinkWord</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#ae88a4d2b7afc5a1c3def9d800cc5863e">applyModifiers</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#aa9daed7f8f5651e85aaa17885e61134c">anonymous\_namespace{tagreader.cpp}::TagFileParser::buildClassEntry</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#aad0c3ffb33cd6ae914d3e4013f2f142a">buildExampleList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#acda218b5772f482d137ab17020b96431">DotClassGraph::buildGraph</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#ad88aa8095a13ae269eb1a17631909f06">DotInclDepGraph::buildGraph</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a027c847c094e7036e803e3d5e6419136">buildGroupList</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a9a2a4b0accaef9069229937226e60b10">anonymous\_namespace{tagreader.cpp}::TagFileParser::buildLists</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#aa5dd16fd497d034a55fdca37a3c17804">anonymous\_namespace{tagreader.cpp}::TagFileParser::buildMemberList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acc3d9699d44f100227430700d7c62a68">buildScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd7144a02373819277466685085d257c">MemberDefImpl::cacheTypedefVal</a>, <a href="/web-doxygen/docs/api/structs/chararoundspace/charelem/#ab01c6ae03f06920e324860d571aab740">CharAroundSpace::CharElem::CharElem</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#abac7d9e657d1d9ac8ccfa460710de204">checkAndOpenFile</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad426893f12b2bc919bc61b3d95e8f471">DocParser::checkArgumentName</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4bd83121097f770a187192b054f59364">checkForKnRstyleC</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a4ca7796c0d1fc682a180bc156f3a3514">checkIfTypedef</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a3912ae85ed2a97ca1f524ac56a4cff10">ClassDefImpl::ClassDefImpl</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#af0c88e52d4d7424c0840a23a522dc330">classHasVisibleChildren</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a48a235cba4770aa3c63e252304f8b10f">codifyLines</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a6fc7dfce3416355a82991f015431b854">FlowChart::colTextNodes</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/classes/configbool/#a6d566ed793c0f4f3e3832f46954dbc86">ConfigBool::compareDoxyfile</a>, <a href="/web-doxygen/docs/api/classes/configenum/#a32c4cf777ea94b43002fd442fa741854">ConfigEnum::compareDoxyfile</a>, <a href="/web-doxygen/docs/api/classes/configint/#aa9ef08f8142fa34f77f5351ce0f219cf">ConfigInt::compareDoxyfile</a>, <a href="/web-doxygen/docs/api/classes/configlist/#af760483c1f5e1dc59378e9ae20e96c6d">ConfigList::compareDoxyfile</a>, <a href="/web-doxygen/docs/api/classes/configstring/#aed83c7c4aad4a7f56e34022cd3810ddf">ConfigString::compareDoxyfile</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a19ff8cd8130e662be4112bc914f7b50b">compounddefExists</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#ad85444ffee4818fe7415a7158385f3d1">computeCommonDirPrefix</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#acf058c8bdaf9bc5f58e3b3a2097c4faa">TreeDiagram::computeExtremes</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a15f2b9e1a8eeea607edeac8805528446">DotGraph::computeGraph</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a940a3aaf1985a9f2ff19dc95aa91716b">TreeDiagram::computeLayout</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afee2d528ad3660fd6ab8de9e42ac6752">computeMemberRelationsForBaseClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a8df15e58576ecab3905a06fd1fc5de34">DotClassGraph::computeTheGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a75c5c04dae25cb36a4715d0c49a4b196">DotGfxHierarchyTable::computeTheGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a33f8dac0366f837a5880dc420d7c914d">DotGroupCollaboration::computeTheGraph</a>, <a href="/web-doxygen/docs/api/classes/dotlegendgraph/#af02bfaa220696e0722080995d191d001">DotLegendGraph::computeTheGraph</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1876213c101b31a44336d48b6b33e9ec">VhdlDocGen::convertArgumentListToString</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#aa8d9375638b4b082c242439fa6be97a0">convertMapFile</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#ad396917a059d354b1ff240b9af3a006c">ResourceMgr::copyResourceAs</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a4a1478cb4a1ba9d12204b6061241a6ec">ClassDefImpl::countAdditionalInheritedMembers</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a8635f06556c6af82953ab2e0797db8a6">ClassDefImpl::countInheritedDecMembers</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a7a98b48366bc0fc41ee0d43eb425087a">DotGfxHierarchyTable::createGraph</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#af3e9802567a6e2df20e4714a7aed3807">MemberList::declVisible</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a105e51dc946d1daa2914afd2bc3e72af">DocParser::defaultHandleToken</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#afa510f0e0d64789d3b98a0cf4968d494">DefinitionImpl::DefinitionImpl</a>, <a href="/web-doxygen/docs/api/classes/definitionmixin/#aa314c6a73e812b62d5e991ebd695cdd1">DefinitionMixin&lt; Base &gt;::DefinitionMixin</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a82a05cf7bd081febd19a0065eed17098">VhdlDocGen::deleteCharRev</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#ae2c044edad92d6008b036ae6c1f97551">DotNode::deleteNode</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ac0e3122b4e6e26ee38ef45f59aaecf05">MemberDefImpl::detectUndocumentedParams</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a97fa1635ca734b061444c678b7525475">determineAbsoluteIncludeName</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a0f227199a40c25549528bd2f6a721483">determineIfNeedsTag</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#aebbdfe5eff5c5f7d8ed348daed0e44dc">DotCallGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a94ed71ea8772865ed1f494bcedbb9b9f">DotClassGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#a8aa3c90f1ef0858e708cb5636e9ed73b">DotInclDepGraph::determineTruncatedNodes</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a71cb7cce72603b64606e7897c3b90e0b">DotClassGraph::determineVisibleNodes</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ab4880c04672f3a3dbf9e7d5f519b845f">dirHasVisibleChildren</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#afe264a9e05a22242d446830b72b203da">MemberDefImpl::displayDefinition</a>, <a href="/web-doxygen/docs/api/classes/classdefaliasimpl/#a9e0a300a44e814de013db11434e9568c">ClassDefAliasImpl::displayName</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac4741f70f06baac174cf71b3e11d06ac">Definition::displayName</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#aee4c0aa0c9ca312ac5c4f7ea9475758a">DirDefImpl::displayName</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#abe23ed044d3dde6bf8b7f6e719644905">FileDefImpl::displayName</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a29f03d38a8c3a17ed8bfd7c7b45aedf0">GroupDefImpl::displayName</a>, <a href="/web-doxygen/docs/api/classes/memberdefaliasimpl/#af537f8de444f8775612f8fadea0b152b">MemberDefAliasImpl::displayName</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#acca5eb761669f07efc01a3d990a63dea">ModuleDefImpl::displayName</a>, <a href="/web-doxygen/docs/api/classes/namespacedefaliasimpl/#a435278bdb5f7af2a2c6cd2e5e9f84a5c">NamespaceDefAliasImpl::displayName</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#aa97380304b365c704f3198fc66efa73d">PageDefImpl::displayName</a>, <a href="/web-doxygen/docs/api/classes/docanchor/#a7dbcc0b3d8792f7eb24a5586609bd020">DocAnchor::DocAnchor</a>, <a href="/web-doxygen/docs/api/classes/doccite/#ac4ad900c3524f1e1451d26329e285acf">DocCite::DocCite</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcaption/#a26024c34c8fc5cbe9ba0d57218e17f1f">DocHtmlCaption::DocHtmlCaption</a>, <a href="/web-doxygen/docs/api/classes/docref/#acb234cd7235b7c61a4c6f9dfd0cd586b">DocRef::DocRef</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a027224fbb504c5436845bb85a7c511a0">DotCallGraph::DotCallGraph</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a53601818c690d945d05a971b506bb5df">DotClassGraph::DotClassGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgfxhierarchytable/#a3e9a28f1f5867cc3d2de69b7db30c15f">DotGfxHierarchyTable::DotGfxHierarchyTable</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a418216c836cb63ef4a243bfb3bc5a81c">DotGraph::DotGraph</a>, <a href="/web-doxygen/docs/api/classes/dotgroupcollaboration/#a20ec74da8ed6727681b3ba3c61fffb42">DotGroupCollaboration::DotGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/dotincldepgraph/#aa6f427f748bd461630a7656583fc729e">DotInclDepGraph::DotInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a7916cd8dbb3b48d335e036c9717ac00d">TreeDiagram::drawBoxes</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a24d81fe9c93c2e315bd713aed99379c4">dupOfParent</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/classes/indexlist/#aabffffbc2e50eeb9437640c369dfd6b7">IndexList::enable</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#ad2df37d9e386ae992a5aa98ab9a0515c">encodeForOutput</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#add957a1f68cc9b99a4c57caa58b33a9b">HtmlGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/xmlcodegenerator/#a1ae221fa179fd6cb57ffc68bbefaee49">XMLCodeGenerator::endCodeLine</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a31670fcbb1641b76e26029d9cfda15eb">ManGenerator::endConstraintDocs</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a06931a0616d950c5388448188105c4c1">RTFGenerator::endConstraintList</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a603fd2d86e322ea4018747febe523edf">HtmlGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a4b2e6be7cbbe074a8d2be270a537c454">DocbookGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a8bf91873a8da583cfbb47b15806c0ae4">HtmlGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a87f599a42c46d9fce84f456797ff231c">RTFGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afda973c4c7b91577d02465015737763d">RTFGenerator::endExamples</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac1850678fe273e83bcda397bc2f1b6ec">endFileWithNavPath</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aabf59d930dff9f6aa46e3e5674678a35">HtmlGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a2a48c9be94459c565ab007f5e342d6f9">ManGenerator::endGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#ac78029628ccb4f7aef7ca0c4cbce0ae3">HtmlGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a884c87751b85f4a6cf6e965fbc0bec9c">RTFGenerator::endIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac49acd6dde35e8774990922cad8b953f">RTFGenerator::endIndexList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9a5dbcad360a1ad2a8f9403ae344d638">DocbookGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a33cad27a2b5dce6e2762d5915e554118">LatexGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a6e669645babaaba4691fc5c5f0147ee0">ManGenerator::endInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a4d8ad4d2dbb3a431808692d286ad4331">RTFGenerator::endItemList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a94002731a870c5add8c360dda5f5105d">RTFGenerator::endMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#accf1f2e363b93a552fb4d3aeb09e6ff2">DocbookGenerator::endMemberDocList</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#af921b3fa4cef3239b99c89a4770a748d">ManGenerator::endMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a4dda2a972bec6b6111b215e94741d8ba">ManGenerator::endMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a639d4d7694e38d646c7b4042f314ca92">ManGenerator::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a245cae7606ecd9bd4ee135b802b030d2">LayoutParser::endNavIndex</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac504083f94cbb2fb24d005200efdd7ee">RTFGenerator::endParagraph</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a5c191151631efdf0d25fc7967f6b0434">endScope</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a2c3eae0a840500bf1a1713cb0c56efd7">ManGenerator::endSection</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a0c856f41b9b3199b3f034a02d7b8309e">ManGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a1bc8b7f200b9267b0c7b842ecd1f25b0">expandExpression</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a3e870f07917a178b708537e85177a6d0">extractCopyDocId</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a8c6ba49e769f2990693fa40528d3c50e">Portable::fileSystemIsCaseSensitive</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abf6738772e1f2bf741b5fb0868847b8c">filterMemberDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a89a9f35c62c2ef88e116f4edea12c038">findAttribute</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae13abaf328534f92b57bb6af8208f31d">findBaseClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2855c4f3905bf9bd629622f65075b558">findClassRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10e11a9d8c5f3fc3b78bc02ebe04380c">findDEV</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a019e4dfdc4fe1a34460b8f7bb8dfe0fa">findEndOfTemplate</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab97b7f9be435590df65d9bb0d31fba06">findEnumDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a82770a95f2aebec7ffee2162e3a67215">findEnums</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a44966d15bb9a0624cead77c6e3c89f94">findFile</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a825f829ad3f2e4e1a52d8959b0ff3fb9">findFriends</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a2660af8b42d7358b222bac43669eff30">GroupDefImpl::findGroup</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3572f62a602ab473a38ae5ae27e66611">findMember</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a767fe9c8dd14640cc99a6f1c9e0981c7">findMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa266ab08127667eabf8093a23e37ff9a">findMembersWithSpecificName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a52d28be272ce56e336d53cec31a62c18">findObjCMethodDefinitions</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f26028922a120817dd5292aad1bcef4">findTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a595b7d13e1597947419c621de298acad">findUsedClassesForClass</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad9ce767127c1fe73995ebae8badaab75">findUsedTemplateInstances</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a043364950b2274c362fdd7e6b48d6ef6">findUsingDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a9e88b70863796306c5f0070d263ab4c8">findUsingDirectives</a>, <a href="/web-doxygen/docs/api/structs/ftvnode/#a0bd6fff389cf03714d8b6e43bdd65a33">FTVNode::FTVNode</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a53124fcb14c157228188e339625da475">generateBriefDoc</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa723e85238b66b5916c25989013e52b8">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#ada294ec0d3d5d40d4bb74d5624c886d4">generateClassMemberLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3eb9720ae877e5d2ae987bce9c91f6a2">generateExampleDocs</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a3ec1633fe7ff4f8ae5374bff88c55b81">generateJSLink</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#aeeac5a3fc4ec080a5831f362ddee33f6">generateJSNavTree</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a2945edc16c199a62e84ee85d81b9c854">generateJSTree</a>, <a href="/web-doxygen/docs/api/structs/ftvhelp/private/#a2ffca7a7650eddd1fc37799566ba38f5">FTVHelp::Private::generateLink</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#aeea4b3347215e1eb97b639c96a1dcadd">CitationManager::generatePage</a>, <a href="/web-doxygen/docs/api/classes/reflist/#a1fb6f991a5826241faab676ba08fb5e3">RefList::generatePage</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae5b36a2f93dadba9f8c7d762564154e1">generateSqlite3</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a96d60ce1da0cc36d049c1a2bbc174178">generateSqlite3ForDir</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae7139b08c0c942d65c6bcb8402a8b142">generateSqlite3ForFile</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#ae37a1510e5c7b3f007b41d8f8c152e9f">generateSqlite3ForMember</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a541a7f1681d4e6c18ba0fb4902f2b9d3">generateXMLForFile</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#abb22b874f40605b95d50a182262feddb">generateXMLForMember</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ad5d4c791af3f2943467c7c7af558d83a">VhdlDocGen::getClassTitle</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#aad46a931d39d3d99fc5d2ad2ecd5e0bf">getCurrentDateTime</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/classes/filtercache/#aa5d001d30e4d16855d3656989947df29">FilterCache::getFileContents</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad8f45edef0c9f7b3b0468e6fdb7cef71">getFilterFromList</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a504e4bc3498a0866fed7ca24f0b6140c">getFortranNamespaceDefs</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#a22ca0992a85719c162c23eb696be6608">getFortranTypeDefs</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a73d0704877dfb2814b3ad52b94475f89">MemberDefImpl::getLabels</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aea75bbe69de2d8ff75d41a40df878894">getLink</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#aa48141b866dee2454e4290a3c34d36bb">getLink</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#ac240a5eb77b55528937ec68a24cf4f46">getLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#aa3a78394ea3d7dee51703f8f0c1e3984">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a7c3e45cceb9eb4446d360eb8620eef8c">getLinkInScope</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a64abc1e2247e925f2abbdd81045b8e08">getParagraphContext</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4612a718016bc1025654d36cb9c463e">getScopeDefs</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6a6c955c9001d67e4b722038bfc5f16b">DocParser::handleAHref</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a3df5816f7dcd092e39a99ebaf9b983cf">VHDLOutlineParser::handleCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a6a11ee69fcc75e0c8ce4fddd8cd15d16">DocPara::handleHtmlStartTag</a>, <a href="/web-doxygen/docs/api/files/src/doctokenizer-l/#a9b60e3bdd311d784431944cfc85f19c9">handleHtmlTag</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ae3321ce556544cc7281b783f2b250be4">DocParser::handleImg</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a1caeb5337611ff5e3be1e08b919bc5e1">handleInternal</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a0bff680b96bc9c76b2228affeaa90bbb">DocPara::handleLink</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a2b2971ad53e50d90ca4affca6a6e1d67">DocParser::handleLinkedWord</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a07efd9277b1b76985a99b4fe638277c3">handleName</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a644f36935a906ed5fe52451f4768420e">handleParBlock</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a04534e1c41f2c421346fb9f313e2b737">DocPara::handleSimpleSection</a>, <a href="/web-doxygen/docs/api/files/src/commentscan-l/#a0cd5ccdcbeb1c5a7cf7dad5d1a9cafc0">handleStatic</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ab004ed65c6ab11f6ca2a4caee610bb49">DocParser::handleStyleEnter</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a566364d58b27f9c2324d9caeda697818">hasNonReferenceSuperClassRec</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#aea3a811bebf636bd4cd8abfa2c50d655">DefinitionImpl::hasSections</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a2e791b200dd11ec24ff27a9aab0f8940">RTFDocVisitor::includePicturePreRTF</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a08f938ae14c9102bb86ad51eab58a2b4">PrintDocVisitor::indent\_leaf</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a2dd347b6be51aa404a4e6bc679736606">MemberDefImpl::init</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a451cff71879d11897907cc8c2102bdcb">initParser</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a35e7ee6baadfec49f7e85a2cf14d5deb">initPredefined</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a22addf63e54e56357d7a2691022828e1">initSpecialBlock</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#aa1fd664818291e7a90ed2ba46a0f44a7">initTriDoubleQuoteBlock</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a2aa292ec6b6ea81860b3d9b00405d1cb">initTriSingleQuoteBlock</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a85a426e31ddcde4eb6a417cc0a939d6a">ClassDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8741a4a807c8e1808f82c08f00152a2f">GroupDefImpl::insertMember</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a6ff307313c1b28d89ef63fef3590ad36">insertMemberDefineParams</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a3a9064a0bd3f19c550c68c5839dec5a6">insertMemberFunctionParams</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a5335bb36c398920d8075493f1aedc119">insertPath</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a9557f25eb205a966e712f8a709d73b5f">insertRefid</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af3eab25ba334db0ed299983b354a89cb">ClassDefImpl::insertTemplateInstance</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#ab5e581e18e98e7d8c3394a28791d7680">insideBlockQuote</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#af5482286b814ee04eea804a9a3261cf4">insideDetails</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a8ab563dcf6c027ecdc4b8df7c79cd166">insideDL</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a786afe8925235dea586eb23046acaf41">insideLI</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#af8c289300738a7353cb8e47d343e7998">insideOL</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a66b237bbac35526d7fa7b944ca815088">insidePRE</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a9daef16ea8fc3793c36c55f3657c6d29">insideStyleChangeThatIsOutsideParagraph</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a2515a32b6dfcda676ef65dd34fad5abf">insideTable</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a1f32f1e06f22781ceb8f7295ea6fca01">insideUL</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ae4f02bc658b7c03423fb568c7410f23d">ClassDefImpl::internalInsertMember</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a6d276e7995db319294ea1fb2bc76459e">DocParser::internalValidatingParseDoc</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a60ffd0b23680e5318865a367b0d26871">SymbolResolver::Private::isAccessibleFrom</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a01a031ffd0a93eb06668c1e93fb57f69">SymbolResolver::Private::isAccessibleFromWithExpScope</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af93f11710bda96d773cf74795ae210e8">ClassDefImpl::isAccessibleMember</a>, <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#adac55ee66f80b7a34778517c50eb4ae8">DefinitionAliasMixin&lt; Base &gt;::isAlias</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8a5218dcda2be9cbc949b95713dad49b">isClassSection</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ae291c1cbee2c4f673156c84666e768f7">isCopyBriefOrDetailsCmd</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a5020cd234edf836bc332c91d073b3a75">MemberDefImpl::isCSharpProperty</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#aef2b269b13f233bd8773f2b7b8365443">isDocIncludeVisible</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#ab101b8a2d6b5ea85218704fb93f5f079">isDocIncOperatorVisible</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a9c6cff6722985f4f25adf4b7daa99b30">isDocVerbatimVisible</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#aabc6c0e6b285c280ffa531cace06e2e4">VHDLOutlineParser::isFuncProcProced</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#ac231c8ffe50ea474d33cacd7c3d14b77">DocHtmlRow::isHeading</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aae351e4e8775385568dd3d77f52707e8">NamespaceDefImpl::isLinkableInProject</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a453c41aa80dbd5bc968846b8c012eee1">MemberDefImpl::isObjCMethod</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae74d134ea251e91ac8ea3e2f1774f434">MemberDefImpl::isObjCProperty</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a66144b339b4b4744d7d7ab092ed16e34">DirDefImpl::isParentOf</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a738d45232dc0fca703f9e9042acae9c0">MemberDefImpl::isReimplementedBy</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0e75c43e09005a52234052e684a5f7f6">isSpecialization</a>, <a href="/web-doxygen/docs/api/classes/dotcallgraph/#a4f66d82e77635c3fdd4ccd92effea216">DotCallGraph::isTrivial</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ac5a5776af3b729d35a46d06054bc84da">isVarWithConstructor</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a37b661752d147469cfe557cd651763c9">TreeDiagram::layoutTree</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afc07a6f4ee440625b9fff2890651b092">RTFGenerator::lineBreak</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#abc7afd6afa8e7eb42dfd6b442635c593">MemberDefImpl::makeImplementationDetail</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#a2612e395bff76cdb264d5e2a2165ddd2">ClassDefMutable::makeTemplateArgument</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#afd4e9dc2db18f93819d8fbddf554efa4">VHDLOutlineParser::mapLibPackage</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a543c8aa7d944877ff050dbdb9bbfd7db">DotNode::markAsTruncated</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a2592b8669b2aba1c2f0476e1011d48cd">DotNode::markAsVisible</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#ab472d7aee599717c94c69ab137310d2c">DocHtmlCell::markFirst</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a7a6913221a98fd408a288ae5af86cda7">DocIncOperator::markFirst</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a849868e81af1e2ae0da511fa3e5a91b8">DocPara::markFirst</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a6b3e3e25859cc2d76b312b988c018d08">DocParamList::markFirst</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a50c10a42581d4ae558776aa2d7528cd2">DocHtmlCell::markLast</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#aec9d5ea066da5f168f5447c67ccc700d">DocIncOperator::markLast</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a569bc5841973bac45491c977814f62e0">DocPara::markLast</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a89fc37af294659364193e14680065668">DocParamList::markLast</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#abf988c072b1ab9b4934fc04e430f9925">matchArgument2</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78739b1ab728bbecd4d3e54ae90bbbce">matchArguments2</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0a8299ea0705cebde431ef0ea600fcb1">DirDefImpl::matchPath</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a06d5fa6f8acbfef6705314884b6e6800">memberdefExists</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a2a696974b4a7902e4137be55d5337d20">memberdefIncomplete</a>, <a href="/web-doxygen/docs/api/files/src/vhdldocgen-cpp/#a9b31309c5cf2471cbe9622a64f969473">membersHaveSpecificType</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a443122a21e609582f590173accd789a1">ClassDefImpl::mergeCategory</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad1f7e120d2a503b8b15e6a68002d0dd5">ClassDefImpl::mergeMembers</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a9945c9dd42aff903b779e932452a1765">ClassDefImpl::mergeMembersFromBaseClasses</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a0baa021dae80e22593292b12ef2f721f">mergeScopes</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a86acf8b4839daaae86b0a90ca98767b8">mustBeOutsideParagraph</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#acca4ea7f41c631ad64fc467e7bb24615">nameIsOperator</a>, <a href="/web-doxygen/docs/api/classes/lexoutlineparser/#a6fc7decd92206d3b66f49d1b8eb077db">LexOutlineParser::needsPreprocessing</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a3c2c07d943edd6653badbcb7522b8142">VHDLOutlineParser::needsPreprocessing</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a0242c97cf62889e69e74196b9567e7d0">ManGenerator::newParagraph</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a851aa07f7276b7e8f4b12d2592d2eb39">newVariable</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a11601f7b8b08cb9600482e5dc3bc51c5">normalizeNonTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a7910d0ac9f615f9ce451bd0c71d15da6">VHDLOutlineParser::oneLineComment</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a1abe1e85619493e4e99240d290c3bdd2">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a942b617cd956361afbd314539cab5922">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aa5dd013610540bba019aaef10157b416">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#af30a5c4fe2669a2bdb78dd0c964af909">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa9e3a7cf34aceba68750ff3ff94acf34">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#af32530eae2ce36e648a925f28f1ca781">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a5c64416b51edb6f80d0be604b4cbe0b3">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a9a6e493ac6aef6d638ead4ad62e4580a">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a1c6b1244f9d0fc6df4f0d66e505e5437">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a942ef73e03ae4a8e306dd6e1e98fcd99">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ac11bc06b22732d6e550dc8382badd38f">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a4336aa37be77360c412335358cd88b46">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a678591cbca0c1070b7a8803d3c5541c7">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a41c844f5b9078d32e11a14b45b6f5c2d">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a806029951b075fcd8c430498bd0f2375">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a6f8aff45c8c934cda5be07107de10c77">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a41aaa90a6a3c9ec728048cbdb927c7ae">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#abfe122c272f139d98332b7630945da0f">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a330c52431e7c540fcea7901e74c70da7">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a4c5beb634b87459054e96cfa6e07717a">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aa2df84b2d5419625e00bd41061f2444d">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#ae2f911cbb8030ff42a96e838476e249f">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#ae9f3fdd3602427ba34e23a0e79ffcf64">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#abe102e24c2324f00273af856a3577c60">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#ade7989c5d873c1601edf487ddd90daec">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aa515f7b48fa75a22c9e1173511e8cb88">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a4ce763b29a44b5b477602993c33842b9">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a611ec420e06726e8061f4fe83c3f8a6f">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a2e1ae1428205bcf6e4cdebb9ae20ede4">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a541113c556c1afc2e6107999d3e18bd4">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a9becdb1d4b3096f9081710f0c6c14e80">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#af21bb817afa0823ea94983a1d86aea4b">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aad6d88a7940699bbb17fa4648d6007a9">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aaa1c588d1549ecec64db696b44247951">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aad902c41e3df81277b2bf6f1e95f466d">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a8bf41fa80034e1477e1017f19f89d4de">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a3135258f772ad9dcb6c936b55f913543">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#aff3cb0ea5dd2ee90d238e8689a34e0da">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a70abcda93ed50a2ffbdacf0f1d973c39">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#abcc43541a23f6c0e0bc5c3a25950493b">PerlModDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/printdocvisitor/#a16438c4825791e03c8103b1ffd167c22">PrintDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a74283afcc3656534bef009b917a9f525">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a485c2a5796bb5e12497c7ab9d65d1f8c">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a022f6eb89bc55b752aeff008e9c9037d">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a85db1985a82081ef9ab2e5a25c450f28">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ae0c5c194fc2579df52204eb00134c6bf">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#acc6c497f52cf55d67723f21ec2a97c6b">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adae81723bf98cc11856ec916852cf089">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a2851bbf082cd6f2a85d6c9fc7a1050c0">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a3c72fc623be48174c003bb47c523d6c1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a75e708a4ea1b27587678f424211b8b62">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a561b27cc775aaa5f6db73f1d33099176">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af6ff0afe39093628cd96d42dfce7515f">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aeb7edc62cad5a541849845d2bfe030e9">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a6f4df2c3160f09e662393e6a23b2add0">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a07acb7803948c3811f88d4efa00587a4">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a4fcb960f7e5b593e8e6c51ea43f66a9a">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a89b1ef4b308483fcf725cef8081e5849">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a9bc7acec72efe2239cb6c798855ed08a">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aa17fa64bc141c519b0b24e0a475ab1e1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af3beab942bf46b1f903ac30ac39a10d2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8123582499bf0458dc938ff66c4724e7">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7f10a43fc0a35475e9078305d745951f">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/textdocvisitor/#a3af6b81e834fce376849077c0fa6b565">TextDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#af9d445166ed91d40a7ff249c8f262d21">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a608907da6a8263ac7cff6caae01673c9">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ac219ce4773970158e118d1d3b57ebd78">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#aac3356483b754f0dab670ad4a1407f98">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#ad9f36acc2f17b5a95a12d047ed0f4d08">XmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6006a1443e18366206b8485ee2d7b8a3">DefinitionImpl::operator=</a>, <a href="/web-doxygen/docs/api/structs/symbolmodifiers/#aaca9d411d0392efd25510ca3209178d0">SymbolModifiers::operator|=</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7c2f6b00d96563acaa44afcacb217b9b">organizeSubGroups</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#abec6a57b1258c5230a0dde8cf6e2c91f">otherCaseDone</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#ae4f48b0fbaa3ba2d1e3caeb4ca86d9b8">MemberDefImpl::overrideCallerGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a4b3c4bb79a604a09380684741a8d941a">MemberDefImpl::overrideCallGraph</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a9b2270b86e43935bd12d0cf4572d823b">MemberDefImpl::overrideReferencedByRelation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a08ef1a59f373a742aeff6ab8053452cc">MemberDefImpl::overrideReferencesRelation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a3b619a4fc6ed1af839392d59ec20b0e2">PageDefImpl::PageDefImpl</a>, <a href="/web-doxygen/docs/api/classes/docautolistitem/#a88f642289a7ff2d625c726cc4777b989">DocAutoListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlblockquote/#aa64ab14e969b672324338c1be6b607e1">DocHtmlBlockQuote::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#af23dec8c6549a7a73bb69037f5324c70">DocHtmlCell::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldescdata/#ab176f44cd7bc955df0c352bd714e4e1c">DocHtmlDescData::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldesctitle/#a92b042aef732d7da8cc71182810e76c5">DocHtmlDescTitle::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmldetails/#a12b425f8cc20de1ed4183ea8a9a454f8">DocHtmlDetails::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#a7c0ac2e655d8a3cf7deb76cdd23e95e5">DocHtmlListItem::parse</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#afbeab8f03e2ef431c05b8d3bcb6291aa">DocHtmlRow::parse</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>, <a href="/web-doxygen/docs/api/classes/docinternal/#ad783a8507dd1e64ad38a889d9fa7a851">DocInternal::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a98345755b6311bcc4129bd7ee14759f1">DocParamList::parse</a>, <a href="/web-doxygen/docs/api/classes/docparamsect/#ab528e49d6e133ca42c29bb46bdc3cbec">DocParamSect::parse</a>, <a href="/web-doxygen/docs/api/classes/docparblock/#aa0283029f3578c44cd54c93d648bd909">DocParBlock::parse</a>, <a href="/web-doxygen/docs/api/classes/docref/#a6004b78783411b8c5752371572afa3ef">DocRef::parse</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/docxrefitem/#acfb3aacf4b559a4b9fb4fb5b2dc960bc">DocXRefItem::parse</a>, <a href="/web-doxygen/docs/api/classes/ccodeparser/#a106ea78aa6382f5b06dbd2563d5b99e4">CCodeParser::parseCode</a>, <a href="/web-doxygen/docs/api/classes/codeparserinterface/#a250f197dbdf763805425256ed96f37d8">CodeParserInterface::parseCode</a>, <a href="/web-doxygen/docs/api/classes/codefragmentmanager/#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a3383c871b9fd5e4b1cf4a549de88a1f3">parseCompounds</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#af3d71282d72dd7136124a4c7405f6b28">parseCompounds</a>, <a href="/web-doxygen/docs/api/classes/doctitle/#a410946c3855fd51f18485d6e3dcce59b">DocTitle::parseFromString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ad6df9d0420902e8579fb9dbbfa5c1a90">VHDLOutlineParser::parseInput</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a8a8ff9e246514b6146a187f9648c2736">parseMain</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a434a1f775b7fe0a37ad69ba2499cfdfb">parseMain</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a4481d3eae9a04af883d868f23c4cbffc">parseMain</a>, <a href="/web-doxygen/docs/api/classes/fortranoutlineparser/#abbe1b29c5797729e3aa2dcd693e46755">FortranOutlineParser::parsePrototype</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#ac1fa467bd9ba716dc3c2fd34d7ab504e">VHDLOutlineParser::parsePrototype</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a3931b4604b8a76ac26b7380a585ef543">FileDefImpl::parseSource</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a>, <a href="/web-doxygen/docs/api/classes/dochtmlcell/#a48640c52ba4009264ee01b0761663756">DocHtmlCell::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmllistitem/#ae1c82a584506da65bd320d481f774854">DocHtmlListItem::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmlrow/#a10bb2141d4a0d7867a97d829794184e3">DocHtmlRow::parseXml</a>, <a href="/web-doxygen/docs/api/classes/dochtmltable/#a2a913b8204fc7637dea2f3783da7b1a2">DocHtmlTable::parseXml</a>, <a href="/web-doxygen/docs/api/classes/docparamlist/#a79bb36905dd1401288d55e12ee52ce03">DocParamList::parseXml</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#ae2407880f57f0b80f4f803d369776189">DocTokenizer::popContext</a>, <a href="/web-doxygen/docs/api/classes/dotgraph/#a45d99cae5ecb12b8735454b57c505e42">DotGraph::prepareDotFile</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-h/#a3318a36567de3b1f36059e387a801863">prepassFixedForm</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a772414bc571e725007f1c8bc15ebb355">preProcessFile</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a33f1f9f82bc9683769a6be6cdfc76270">RTFGenerator::preProcessFileInplace</a>, <a href="/web-doxygen/docs/api/classes/statistics/#a681d86ad7e9121de36d517420e135415">Statistics::print</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa4f4085dfd3e73ae354c7cfd6fa69faf">Markdown::Private::processHtmlTagWrite</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ad27e4ec4bbcf59eb0c8bf33571fec70d">DiagramItem::putInList</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acd84b4b4ce1b0ba6b03bc8d8e84e4c8c">quickLinkVisible</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a9af0795be28dcf4551e57a2a3650a552">readIncludeFile</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#a11f1e398e07986ff1b2977f361e9eea0">recodeString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5c3775d3cb6b3776c441a4451d49bb2c">recognizeFixedForm</a>, <a href="/web-doxygen/docs/api/classes/reflist/#a36b770703f31caac7df3873136d3d747">RefList::RefList</a>, <a href="/web-doxygen/docs/api/classes/parsermanager/#a150d4d51073cb46cdf38a236cc120d0a">ParserManager::registerExtension</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a2bbb2d9191d513b9cbfb864ee2043a3c">removeIdsAndMarkers</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a50828408023d08f28ef9b6071fd8ac52">renderMemberIndicesAsJs</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a191edf3c31405fc032d0277a553cea99">renderQuickLinksAsJs</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a6d45214fe7f759039bfd8cc7b37abbf5">renderQuickLinksAsTabs</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#af18da14aec7b354ada7376e24ca5e6ec">replaceFunctionMacro</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>, <a href="/web-doxygen/docs/api/files/src/dotrunner-cpp/#af2aa6035c4917cd2d139f59850c5a008">resetPDFSize</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a34157df0fe53d6d10cc4560ca942f488">resolveClassNestingRelations</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2bb57904806cf057f0d38374a63209ea">resolveRef</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a653335defbae0c2b319413c2d9376458">resolveUserReferences</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>, <a href="/web-doxygen/docs/api/classes/dotmanager/#a3b34d4c3e0ab9e9debe6c7fa45a129bb">DotManager::run</a>, <a href="/web-doxygen/docs/api/classes/dotrunner/#ac1afaee16ddd8bf0bc6b18aaed6b44fd">DotRunner::run</a>, <a href="/web-doxygen/docs/api/files/src/plantuml-cpp/#a309f3f6f3c75a77b4ce5b9760f319d62">runPlantumlContent</a>, <a href="/web-doxygen/docs/api/classes/coloredimage/#ae4a3366368b665b83c8b821fd9bdeae7">ColoredImage::save</a>, <a href="/web-doxygen/docs/api/classes/image/#aa60b6e62896aa1fbd62d7df3f02aaf7e">Image::save</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#a7b2ca28396c488d5a08ead21731ed2c2">scanner\_abort</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7ed1fdd15e6ed566c33a63fcd30d53c4">searchInputFiles</a>, <a href="/web-doxygen/docs/api/classes/searchindex/#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#adbfcafb48c794e6885763cd94da51375">setCurrentDoc</a>, <a href="/web-doxygen/docs/api/classes/definitionmixin/#a57049ae0a543644fa13d44472098f7ae">DefinitionMixin&lt; Base &gt;::setDocumentation</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a5115744bf4595f9a08a193dd41d4f4c3">DefinitionMutable::setDocumentation</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#aa8cd9bab78377e9d6719c0b77ff07120">ClassDefImpl::setGroupDefForAllMembers</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a38a736137370a011fe71a0fd9102d151">GroupDefImpl::setGroupTitleLocal</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af21af80199783680a6a6d6e83fff0a39">ClassDefImpl::showUsedFiles</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8d6ace0deb439b916b9f97f54a6c9cc2">QCString::simplifyWhiteSpace</a>, <a href="/web-doxygen/docs/api/classes/classdefmutable/#ad3f331c1d12e6f5256e749173835b2b8">ClassDefMutable::sortAllMembersList</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a09686597743294f1f44f5c604a81dbaf">ManGenerator::startAnonTypeScope</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#adaaaa54a0aec67674d41d61bef0f2a2b">DocbookCodeGenerator::startCodeLine</a>, <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a899976eb9aee4bb9bd881e9b204cc069">HtmlCodeGenerator::startCodeLine</a>, <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#a8dfd2b046a17459f69b7d08e49349240">LatexCodeGenerator::startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a47b0cd13a509f44e1a1032cbf4ad69ed">startCodeLine</a>, <a href="/web-doxygen/docs/api/classes/xmlcodegenerator/#a2e1224334cbe5cfe794c31eeaf4bbc57">XMLCodeGenerator::startCodeLine</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#ab17fadda7f7d30dce3d68f186aaed55d">anonymous\_namespace{tagreader.cpp}::TagFileParser::startCompound</a>, <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a0ec58197ab496c7ea5a9be5edb5d6073">startCondSection</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a9b07469696e5391928602edc03e16664">ManGenerator::startConstraintList</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#adf073ca7959a1f7c004bf8c4a79ca151">ManGenerator::startDescForItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afb8929ed5f608c71ef0d67c9bd2713a8">DocbookGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#abcf93751a8901a09472a39ed04f0c49a">ManGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a3e1776ac93e8c66900b56bd8954f6360">ManGenerator::startDescTableData</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a6b323886b28fc9f4ba5a87981a2b1430">ManGenerator::startExamples</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#aa7bb1a49097ab94f2d73f0fe02f4c5ad">ManGenerator::startFile</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#adcd8cfddee95768c329a3c284c4ede9f">DocbookCodeGenerator::startFontClass</a>, <a href="/web-doxygen/docs/api/classes/xmlcodegenerator/#aa0280b79aa3d02cc6958d6a30ea31fc3">XMLCodeGenerator::startFontClass</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac651122c0ac17ea4be13f8a4d71c3efa">DocbookGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a7f125260c31c05f6171796b108bf3835">LatexGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a49116184047a4d02f25e75788bc539c8">ManGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a80da85d198868bc3351b1a6a90f32a75">HtmlGenerator::startIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9a13eaff7928b82d69f9547aa004d107">RTFGenerator::startIndexItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a969f88aefb693d90e5ced9f91a20b4bc">RTFGenerator::startIndexList</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a0de19d805d84ae14aff81334a010c9a1">LatexGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a8be5825cc340050d3cfcf29a533a9a4d">ManGenerator::startItemListItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a6847cacb71fc0487655971490b6eb778">RTFGenerator::startItemListItem</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#aa4db9510d59066b8d7f847bda9fb9574">anonymous\_namespace{tagreader.cpp}::TagFileParser::startMember</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#afc96dfbb364a4e075ba52b72af20722b">ClassDefImpl::startMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#acde950d849a45db1654b634d43f68d26">FileDefImpl::startMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a0dd0f75759005600d0f410ee4a20dc45">GroupDefImpl::startMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a604ef99a0d36078577526746d9b5cac4">ModuleDefImpl::startMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a877432b05ee5e7b53fe5431bfcf1f86b">NamespaceDefImpl::startMemberDocumentation</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a10f198594f85e92a681337af184d913d">DocbookGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#aea90b1337254e9c10ceaefcff8b9c825">HtmlGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a5e6096c4c5fb47fb771afedea2f64384">LatexGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a82557dc83927e00f34efb901409e04d4">DocbookGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a90e8e67b9d4140660537473a3c98c3d4">HtmlGenerator::startMemberSections</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#aba3b3876764867eeb32b9dcce3d4b63b">LayoutParser::startNavEntry</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#a4185e0c565c90c08916ee32405623b43">ManGenerator::startParagraph</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a5cd9e00e6fd36cfbc6a66324910eb618">startQuickIndexList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aeca4bf8edce633fa3faa7c1e38882363">DocbookGenerator::startTextBlock</a>, <a href="/web-doxygen/docs/api/files/src/pre-l/#a085c52ce4351470497b03309e77228cc">stringize</a>, <a href="/web-doxygen/docs/api/files/src/defargs-h/#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a28ac6dbcdb288699accc1a8db6f56cd5">stripIrrelevantString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af363dfe85e56f873aa3a373c70a33b24">QCString::stripPrefix</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a8acb7287be03115c56196dd1a1085225">stripQualifiers</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a8acb7287be03115c56196dd1a1085225">stripQualifiers</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a78d33655f54cd45e22070b58a6dce6b6">stripScope</a>, <a href="/web-doxygen/docs/api/files/src/definition-cpp/#af14d495cc8aa43bd9a23c357e56b4454">stripWord</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a8974bb194ed8b33e8f81653c8aacf6">substituteTemplateArgumentsInString</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a6da766398ce7fc4fd2aa252bc2f695b6">substituteTemplatesInString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa4a9dec36c09c8c131a0e5e9bb71d98e">QCString::toLong</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a524e1cd9e1c24e91d57b1cb91513fa67">QCString::toUInt64</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a592f86f3d758cb9285967c195f2f1824">QCString::toULong</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#af9f9567b822b1cbc46ff46b5a310ceab">transferFunctionReferences</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a42120760d9d3f1ffe7d1561ef7b50a49">transferRelatedFunctionDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4299844cb805de324387ae0072ea6e9d">tryAddEnumDocsToGroupMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae4f8196aff5be2c0b8046c45e3830fab">updateLanguageMapping</a>, <a href="/web-doxygen/docs/api/structs/layoutnaventry/#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">LayoutNavEntry::url</a>, <a href="/web-doxygen/docs/api/files/src/xmldocvisitor-cpp/#ad2b918f141b60e444314ae661cf02162">visitPreStart</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a1d51f3aad1177695f1c4a6c1340bfa0b">MemberDefImpl::warnIfUndocumented</a>, <a href="/web-doxygen/docs/api/structs/dotgroupcollaboration/edge/#a1f4c832d9b0e56ecdf8f164784623354">DotGroupCollaboration::Edge::write</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#a261123fa5550fbc2dd3b146e18f9f221">DotNode::write</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad9ade8c43232b499c51f41859454a664">ClassDefImpl::writeAdditionalInheritedMembers</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a1e3a4afd351b7003fabe09becaec1544">writeAlphabeticalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a37bc7623366b73fb763a0158bfad81e6">writeAlphabeticalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a82de35e3b84d856dc4fdbc0d3aea1a53">writeAlphabeticalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9436fc784740d05ff033ac903b4af65e">writeAlphabeticalStructIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2f043c11e45084b10c69bcf1953d8869">writeAnnotatedClassList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a84317d2528b42fa86569b03c749c4d67">writeAnnotatedIndexGeneric</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a626316953a99d3f5e838a27cd5bd0423">ClassDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#aec94d27ae7459f75e56fd19c2653b1a7">ConceptDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#aa3b3cc5ea1e4c508ce1a78633590f2fe">FileDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a6ed74dd39a7fce0737383a5055efbd18">GroupDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a61998df92e21df36b49f2a09e2d868f4">ModuleDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a4c4bfe146ecd653c8d9ed6b93825bc40">NamespaceDefImpl::writeAuthorSection</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2f4c817969397028ff1d7093822f1697">ClassDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a64d65000b297d313a09e4c1cca1f17e0">ResourceMgr::writeCategory</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a52184dbf57cd588aa1e21f4cd3267abe">NamespaceDefImpl::writeClassDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2508b8df6ae56345ed2dae0061d1a0df">writeClassMemberIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a2e8df3451e4caa059509cd97ad102188">writeClassMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a648559aac6805a9ccfb2edd9e6c39717">writeClassTree</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aef50eec2d0b854998b9565c97ccab8f0">writeClassTreeForList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0a4d1d807b56446946886c0c6c7450cf">writeClassTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0f56a60d5ebb164be2467e27c8975642">writeClassTreeToOutput</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a0ac2f4932405d6a1773bea6eb84885ec">VhdlDocGen::writeClassType</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac39a58bd916b4935b01c455139e5b7ad">writeConceptIndex</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ab10c8e8acad1e66ab7f850e867589c09">NamespaceDefImpl::writeConcepts</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a9f3b04775e88a72b563fdd34c6f2646c">writeConceptTreeInsideNamespaceElement</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/namespacelinkedrefmap/#a5d9013801184ee3d3a93868770656ba2">NamespaceLinkedRefMap::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#a5109f6f8128e0b9169ac9b8ebe29ba64">writeDefArgumentList</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a891e19196667b0ff8421e74ccf682140">writeDefaultQuickLinks</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a723d6e54b5897589bf4c923d080ea7f5">ConceptDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a5a1cf6ae19c36d295d442f950386b7e8">DirDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7c694a762bc9b8989af9e12a0c072e24">FileDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad25697fdd0818627cd818c3dee5ca950">GroupDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa10ad737654f40f71fb94fae3d8213ca">ModuleDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac9ee7b31183e05abe950505e53b97dc5">NamespaceDefImpl::writeDetailedDescription</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a36436ea13493cfddafdb6a41aad430dc">ClassDefImpl::writeDetailedDocumentationBody</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aa8e7acc156d5f99e61cc895d8f8ea54b">writeDirHierarchy</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a26b64af15b43057fdc32324eeaed0372">GroupDefImpl::writeDirs</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#acb884e6e6f8ac5068b23a6f7e9512441">writeDirTreeNode</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a4f3decc229a0d63c77f2313deee36fb7">RTFGenerator::writeDoc</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a1f8508dffa4eb73470c7ab609e72ccd2">DotClassGraph::writeDocbook</a>, <a href="/web-doxygen/docs/api/classes/classlinkedrefmap/#aa36e57d8b3b8814f56caff17d0562173">ClassLinkedRefMap::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#af9ce6d925ff37249d1a59874ac14fc49">GroupDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a02dbcdb9b0f5e4fc26ff2e2700f6aa4f">MemberDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a1db6a60af2158f45fe57f1b9369f32ea">PageDefImpl::writeDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/dot-cpp/#ada988a5303d67622cb43bd75c247fec2">writeDotImageMapFromFile</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7c5a3ca960f83aab24f36a9adf0a1e43">writeExampleIndex</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a7d87631eb3f39a931521cda5ac2ee95a">ModuleDefImpl::writeExports</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#a9588784ebebaad9cb24e153c07aeb662">HtmlGenerator::writeExternalSearchPage</a>, <a href="/web-doxygen/docs/api/classes/htmlhelpindex/#a90f49f18773a8f5949d7908575996e71">HtmlHelpIndex::writeFields</a>, <a href="/web-doxygen/docs/api/classes/classdiagram/#acb331a908252968ca8ba371ee560aa51">ClassDiagram::writeFigure</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a32155fdad3f4843c5d8743c037bf4846">writeFileIndex</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ac0b6303f4a873a4efca173ed6b432418">DirDefImpl::writeFileList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a16cb7ba36021e5d728680f053e86a5e4">writeFileMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ac1e34a9cf62aa5a9c1fc5a799f35f53f">GroupDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a8343077d25879c0c250f32138569e691">ModuleDefImpl::writeFiles</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aee87f24daab068f794ea908f33a86c3f">VhdlDocGen::writeFuncProcDocu</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a9ca249e8052f477d893edfc767948fcf">VhdlDocGen::writeFunctionProto</a>, <a href="/web-doxygen/docs/api/classes/dotdirdeps/#a636d65d1b7097eca39e1dc431e8a7b32">DotDirDeps::writeGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae2c24526468232c3a2c4f93669225392">writeGroupTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad5e4237f97bd24dd695fe17757fd4894">writeHierarchicalExceptionIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad9ecde0657aa507c6867661b32867227">writeHierarchicalIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a54644bd1b33abadc0dde902ffb1a3823">writeHierarchicalInterfaceIndex</a>, <a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">ClassDiagram::writeImage</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a8598b3b432f7ab0571d567f0232f1722">FileDefImpl::writeIncludedByGraph</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a7274693641d802ed217bdc46b91db227">FileDefImpl::writeIncludeFiles</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac6c6a9672dd8b23a1971a7ac17278bfd">FileDefImpl::writeIncludeGraph</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#aca433ebd5f69c326bd8740d55c2b4d66">writeIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a0d8342dd518223a45f160f8b2f081c32">writeIndexHierarchyEntries</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a24a546c83a0d35d0f034b822def5e2d7">ClassDefImpl::writeInheritanceGraph</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a7fb5141ea8877090d564026636d81a14">ClassDefImpl::writeInheritedMemberDeclarations</a>, <a href="/web-doxygen/docs/api/classes/htmlgenerator/#af012e45f04c5da89f11d17770dad1b00">HtmlGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a67f47b8dc11d967ee47e9bda86fff7e0">VhdlDocGen::writeInlineClassLink</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6bab634f62d558e8d56cb84dee170cd2">DefinitionImpl::writeInlineCode</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a568422fd73419e4985d3782a874439d0">ClassDefImpl::writeInlineDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-js-cpp/#a83984e7adf06e5e5006d61c0634d8a54">writeJavasScriptSearchDataPage</a>, <a href="/web-doxygen/docs/api/classes/dotnode/#ae7a5c86a2927e880a7c8413e57275811">DotNode::writeLabel</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ae3e188b81cd05fbb4e12621850e7d5e4">DocbookCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a87bd505cf0e4598b8e8ae320087166f3">HtmlCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#a41b0a17952879ed6de614c8bd4ff6c9f">LatexCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#af6f9b93ecb1822874f1e05f448798516">MemberDefImpl::writeLink</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#a2e8ce3b3d8bd736fca765b669093772c">writeMapArea</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#acd658cf89468f9f0e8d884c53dba3e17">MemberDefImpl::writeMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a2e17a6acd90199653e458efae6018927">ClassDefImpl::writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ae911568c61ac4bb685022ae85bed4433">writeMemberList</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#add40a3a8212464c4914efbeba3d529a1">writeMenuData</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac799d77dfd71217b69bd642a39f5b0bb">writeModuleIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#af0d34712a4f6f94057d27b80fb4f6acc">writeModuleMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ad34f8b6da0aece071f38e255943f463e">writeModuleTreeNode</a>, <a href="/web-doxygen/docs/api/files/src/code-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/pycode-l/#a211386867df5b0f5b03dabbec2c18a6a">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/files/src/fortrancode-l/#aefd632b8f888c312d4d67dffa15f5669">writeMultiLineCodeLink</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#ac36fa0b0736527f4f9b6887bc4daccbc">NamespaceDefImpl::writeNamespaceDeclarations</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a4dc24ace0cd7831ca5accf9c98fb8812">writeNamespaceIndex</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a600376a1b261fa6d498ce37b1037bcb6">writeNamespaceMemberIndexFiltered</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#adb7f1cd54d672376e34b61e0a4a0f6ea">ClassDefImpl::writeNestedClasses</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#ad1f0e53da1ff675b21bcedb88c1eccc9">GroupDefImpl::writeNestedGroups</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#af7ceebe6b90c368816a6d9bd0ca501c0">Markdown::Private::writeOneLineHeaderOrRuler</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a9e4ef930abbc7603896a126a7744b6d9">GroupDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#ac9923048ee56e605928a91436085ced1">PageDefImpl::writePageDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a73a2e150da46789d843be976b42f6394">writePages</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#afc394d10d64e221682e9619eef74fde5">VhdlDocGen::writePlainVHDLDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a4ab757dead7796d93d5a534ae1c11e69">VhdlDocGen::writeProcedureProto</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a31b60db653850e1be9084b27153e6758">VhdlDocGen::writeProcessProto</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac17987f390e01a05dd8a3c12feae991a">writeQuickMemberIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a81b6f99e6d3882e29a2a4ff830741c77">VhdlDocGen::writeRecUnitDocu</a>, <a href="/web-doxygen/docs/api/classes/flowchart/#a8dce4c5ff38314428145e71a788e5331">FlowChart::writeShape</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a7aba23a0c522274ecb4fb76f8d40afb3">writeSingleFileIndex</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a1c145b8082cd9865b477141ab58dcb20">VhdlDocGen::writeSource</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#ac584b41f75fc411a218e9e684fd491d5">FileDefImpl::writeSourceBody</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#ab8d961c920b3e704cd1304290be8352d">DefinitionImpl::writeSourceRefs</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a84a2aa61638b8af08560219e2a5140f1">ConfigOption::writeStringList</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#a0228273971fc5ae42adeaf17a61f3fca">DirDefImpl::writeSubDirList</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#ad28ce13d37a783efc856e85b0cdb791c">ClassDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a26fe21b32c7e96c3c50f8cfd2e06e89f">FileDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a1cd6f5eb27ef6ca1ded4532bd38323b0">GroupDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ad9a159e7a8e4ed36a862252a284e0d24">ModuleDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#af7fd110aa3bb86ad68c64ff39239d8fd">NamespaceDefImpl::writeSummaryLinks</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#ae41b4e8b1817e1d1de1732e4c4f9069c">DotFilePatcher::writeSVGFigureLink</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#aac22b47b84bdf30579b606f54c36a053">ManGenerator::writeSynopsis</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a21b82aade2e5a369ec438f0cd49f8107">Markdown::Private::writeTableBlock</a>, <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a596634e1a701c0497742900db2b34f57">PageDefImpl::writeTagFile</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a76fe2943fccabc70c52ad3b6e31f4fa5">VhdlDocGen::writeTagFile</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a8f2bd54985a7da4e6c800829305bece1">writeTemplateArgumentList</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#acff1068065be6bd3a5526d291555c7a6">DefinitionImpl::writeToc</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a63db498aa23f4f344c482162bf88a93b">writeTopicIndex</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a368ff211eb2074462c875f024ed1c3e3">writeTypeConstraints</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a1e56aa086c8135c76d84de764845c20e">DotFilePatcher::writeVecGfxFigure</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a99c857205029d5e52c0a7c26f18ef3ed">VhdlDocGen::writeVHDLDeclaration</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2b65f506a9133e6bbc8e8665e2901625">VhdlDocGen::writeVHDLDeclarations</a>, <a href="/web-doxygen/docs/api/classes/vhdldocgen/#aa99c6269bf6155f83a12ab796edd4acf">VhdlDocGen::writeVhdlDeclarations</a>, <a href="/web-doxygen/docs/api/classes/dotclassgraph/#a38f13c4316472bf09660511bc8fea3fa">DotClassGraph::writeXML</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a6d391007591f277cd73420b77403666d">writeXMLCodeBlock</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
