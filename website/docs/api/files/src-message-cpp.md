---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/message-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `message.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;cstdio&gt;
#include &lt;cstdlib&gt;
#include &lt;mutex&gt;
#include &lt;atomic&gt;
#include &lt;unordered_set&gt;
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
#include "md5.h"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a> (QCString result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad150b78be80374eb1373be71e75a67b0">format_warn</a> (const QCString &amp;file, int line, const QCString &amp;text)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed763574c33aa626cd8209d9d681938a">handle_warn_as_error</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64ba1596ef3046e773e49494e9e25913">do_warn</a> (const QCString &amp;file, int line, const char *prefix, fmt::string_view fmt, fmt::format_args args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aca6c414913e8be769863ed67c1e82141">msg_</a> (fmt::string_view fmt, fmt::format_args args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bb548412cf2bb2cf0d98b653eadaa88">warn_</a> (WarningType type, const QCString &amp;file, int line, fmt::string_view fmt, fmt::format_args args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9860ed9c33a1b2d1842c66e97c2e9eba">warn_uncond_</a> (fmt::string_view fmt, fmt::format_args args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a494fadd4c48c14de490e66d80bb279">err_</a> (fmt::string_view fmt, fmt::format_args args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee081170866fc184d3119f7c24566b74">err_full_</a> (const QCString &amp;file, int line, fmt::string_view fmt, fmt::format_args args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aea5f4b9b7bf7b3f59be94e5e096095ad">term_</a> (fmt::string_view fmt, fmt::format_args args)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4149b6b3cb3e0246eb2e0d47de02538f">warn_line</a> (const QCString &amp;file, int line)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad9799c2a434877f36bc92beb8966567">warn_flush</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0b7262dc94aba9476d8669db4f3920e">initWarningFormat</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae3d3e3fe0dd73eb3fe463e99d2bd4a73">finishWarnExit</a> ()</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad4ae1643bcdbcff1680a322e5bbae8d">g_warnFormat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a6bddc99419347af9c2d3569bada867">g_warnLineFormat</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9d34be93b99045d723b7edc562d10ce4">g_warningStr</a> = "warning: "</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a0504f5cfc80ac9db15736e27d04554">g_errorStr</a> = "error: "</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static FILE *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> = stderr</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static WARN_AS_ERROR_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a> = <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492ac2f3f489a00553e7a01d369c103c7251">WARN&#95;AS&#95;ERROR&#95;t::NO</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74c872d0bf5eb507f454aaa810973144">g_warnlogTemp</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::atomic_bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a807b8e20fe24490244de4bfdaf531bef">g_warnStat</a> = false</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf45c484c585bd82d2d892c29de4a0be">g_mutex</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unordered_set&lt; std::string &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1c5d408176641f644437b6c4b551246">g_warnHash</a></td>
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

## Functions

### checkWarnMessage() {#a158f798fb6e8971c1480747fa7061a96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool checkWarnMessage (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result)</td>
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


<p>Definition at line <a href="#l00046">46</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a158f798fb6e8971c1480747fa7061a96">46</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  uint8_t md5_sig[16];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> sigStr[33];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  MD5Buffer(result.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),result.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>(),md5_sig);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">  MD5SigToString(md5_sig,sigStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab1c5d408176641f644437b6c4b551246">g_warnHash</a>.insert(sigStr).second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="#ab1c5d408176641f644437b6c4b551246">g&#95;warnHash</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>.

Referenced by <a href="#a3a494fadd4c48c14de490e66d80bb279">err&#95;</a>, <a href="#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a>, <a href="#aea5f4b9b7bf7b3f59be94e5e096095ad">term&#95;</a> and <a href="#a9860ed9c33a1b2d1842c66e97c2e9eba">warn&#95;uncond&#95;</a>.
</div>
</div>

### do&#95;warn() {#a64ba1596ef3046e773e49494e9e25913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void do_warn (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, int line, const char * prefix, fmt::string_view fmt, fmt::format_args args)</td>
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


<p>Definition at line <a href="#l00122">122</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64ba1596ef3046e773e49494e9e25913">122</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a64ba1596ef3046e773e49494e9e25913">do_warn</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>, fmt::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, fmt::format_args args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad150b78be80374eb1373be71e75a67b0">format_warn</a>(file,line,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(<a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>+fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aed763574c33aa626cd8209d9d681938a">handle_warn_as_error</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a>, <a href="#aed763574c33aa626cd8209d9d681938a">handle&#95;warn&#95;as&#95;error</a> and <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.

Referenced by <a href="#a7bb548412cf2bb2cf0d98b653eadaa88">warn&#95;</a>.
</div>
</div>

### err&#95;() {#a3a494fadd4c48c14de490e66d80bb279}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void err_ (fmt::string_view fmt, fmt::format_args args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00175">175</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a494fadd4c48c14de490e66d80bb279">175</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3a494fadd4c48c14de490e66d80bb279">err_</a>(fmt::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, fmt::format_args args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_lock&lt;std::mutex&gt; lock(<a href="#abf45c484c585bd82d2d892c29de4a0be">g_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>(<a href="#a8a0504f5cfc80ac9db15736e27d04554">g_errorStr</a>+fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args))) fmt::print(<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>,</span><span class="doxyHighlightStringLiteral">"{}{}"</span><span class="doxyHighlight">,<a href="#a8a0504f5cfc80ac9db15736e27d04554">g_errorStr</a>,fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aed763574c33aa626cd8209d9d681938a">handle_warn_as_error</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>, <a href="#a8a0504f5cfc80ac9db15736e27d04554">g&#95;errorStr</a>, <a href="#abf45c484c585bd82d2d892c29de4a0be">g&#95;mutex</a>, <a href="#abfb684889b2b27eb72e96af8478b5f85">g&#95;warnFile</a> and <a href="#aed763574c33aa626cd8209d9d681938a">handle&#95;warn&#95;as&#95;error</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/message-h/#ae3b8cd624e6c2ec6778469b7821caafd">err&#95;fmt</a>.
</div>
</div>

### err&#95;full&#95;() {#aee081170866fc184d3119f7c24566b74}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void err_full_ (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, int line, fmt::string_view fmt, fmt::format_args args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00186">186</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aee081170866fc184d3119f7c24566b74">186</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aee081170866fc184d3119f7c24566b74">err_full_</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line, fmt::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, fmt::format_args args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad150b78be80374eb1373be71e75a67b0">format_warn</a>(file,line,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(<a href="#a8a0504f5cfc80ac9db15736e27d04554">g_errorStr</a>+fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a> and <a href="#a8a0504f5cfc80ac9db15736e27d04554">g&#95;errorStr</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/message-h/#af6932e5ae88b6ad6b25989caf7fad051">err&#95;full&#95;fmt</a>.
</div>
</div>

### finishWarnExit() {#ae3d3e3fe0dd73eb3fe463e99d2bd4a73}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void finishWarnExit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00295">295</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3d3e3fe0dd73eb3fe463e99d2bd4a73">295</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae3d3e3fe0dd73eb3fe463e99d2bd4a73">finishWarnExit</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  fflush(stdout);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a> == WARN_AS_ERROR_t::FAIL_ON_WARNINGS_PRINT &amp;&amp; <a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a> != </span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/namespaces/portable/#af099fa6239b4961887192d8eadfd2a44">Portable::fclose</a>(<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a807b8e20fe24490244de4bfdaf531bef">g_warnStat</a> &amp;&amp; <a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a> == WARN_AS_ERROR_t::FAIL_ON_WARNINGS_PRINT &amp;&amp; <a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a> != </span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">    std::ifstream warnFile = <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>(<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!warnFile.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> = stderr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Cannot open warnings file '{}' for reading\n"</span><span class="doxyHighlight">,<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (getline(warnFile,line))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">        fmt::print(stderr,</span><span class="doxyHighlightStringLiteral">"{}\n"</span><span class="doxyHighlight">,line);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">      warnFile.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a74c872d0bf5eb507f454aaa810973144">g_warnlogTemp</a>) <a href="/web-doxygen/docs/api/namespaces/portable/#a394e935b6fd1899b26f8987f89a4cbfb">Portable::unlink</a>(<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a807b8e20fe24490244de4bfdaf531bef">g_warnStat</a> &amp;&amp; (<a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a> == WARN_AS_ERROR_t::FAIL_ON_WARNINGS ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">                     <a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a> == WARN_AS_ERROR_t::FAIL_ON_WARNINGS_PRINT))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">    exit(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#af099fa6239b4961887192d8eadfd2a44">Portable::fclose</a>, <a href="#a8e1d65011b82b41029cea922b7b3c298">g&#95;warnBehavior</a>, <a href="#abfb684889b2b27eb72e96af8478b5f85">g&#95;warnFile</a>, <a href="#aef140dc11e587afb68a5b902eef06241">g&#95;warnlogFile</a>, <a href="#a74c872d0bf5eb507f454aaa810973144">g&#95;warnlogTemp</a>, <a href="#a807b8e20fe24490244de4bfdaf531bef">g&#95;warnStat</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a> and <a href="/web-doxygen/docs/api/namespaces/portable/#a394e935b6fd1899b26f8987f89a4cbfb">Portable::unlink</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.
</div>
</div>

### format&#95;warn() {#ad150b78be80374eb1373be71e75a67b0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void format_warn (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, int line, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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


<p>Definition at line <a href="#l00056">56</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad150b78be80374eb1373be71e75a67b0">56</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad150b78be80374eb1373be71e75a67b0">format_warn</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileSubst = file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? </span><span class="doxyHighlightStringLiteral">"&lt;unknown&gt;"</span><span class="doxyHighlight"> : file;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineSubst; lineSubst.<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(line);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> textSubst = text;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> versionSubst;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// substitute markers by actual values</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> msgText =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#aad4ae1643bcdbcff1680a322e5bbae8d">g_warnFormat</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightStringLiteral">"$file"</span><span class="doxyHighlight">,fileSubst</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">            ),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"$line"</span><span class="doxyHighlight">,lineSubst</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">          ),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"$version"</span><span class="doxyHighlight">,versionSubst</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">        ),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightStringLiteral">"$text"</span><span class="doxyHighlight">,textSubst</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a> == WARN_AS_ERROR_t::YES)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">    msgText += </span><span class="doxyHighlightStringLiteral">" (warning treated as error, aborting now)"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  msgText += </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_lock&lt;std::mutex&gt; lock(<a href="#abf45c484c585bd82d2d892c29de4a0be">g_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// print resulting message</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>(msgText)) fwrite(msgText.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),1,msgText.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>(),<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a> == WARN_AS_ERROR_t::YES)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> != stderr &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(QUIET))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"See '{}' for the reason of termination.\n"</span><span class="doxyHighlight">,<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    exit(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a807b8e20fe24490244de4bfdaf531bef">g_warnStat</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="#abf45c484c585bd82d2d892c29de4a0be">g&#95;mutex</a>, <a href="#a8e1d65011b82b41029cea922b7b3c298">g&#95;warnBehavior</a>, <a href="#abfb684889b2b27eb72e96af8478b5f85">g&#95;warnFile</a>, <a href="#aad4ae1643bcdbcff1680a322e5bbae8d">g&#95;warnFormat</a>, <a href="#aef140dc11e587afb68a5b902eef06241">g&#95;warnlogFile</a>, <a href="#a807b8e20fe24490244de4bfdaf531bef">g&#95;warnStat</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.

Referenced by <a href="#a64ba1596ef3046e773e49494e9e25913">do&#95;warn</a> and <a href="#aee081170866fc184d3119f7c24566b74">err&#95;full&#95;</a>.
</div>
</div>

### handle&#95;warn&#95;as&#95;error() {#aed763574c33aa626cd8209d9d681938a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void handle_warn_as_error ()</td>
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


<p>Definition at line <a href="#l00101">101</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed763574c33aa626cd8209d9d681938a">101</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aed763574c33aa626cd8209d9d681938a">handle_warn_as_error</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a> == WARN_AS_ERROR_t::YES)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">      std::unique_lock&lt;std::mutex&gt; lock(<a href="#abf45c484c585bd82d2d892c29de4a0be">g_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> msgText = </span><span class="doxyHighlightStringLiteral">" (warning treated as error, aborting now)\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">      fwrite(msgText.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),1,msgText.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>(),<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> != stderr &amp;&amp; !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(QUIET))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// cannot use `msg` due to the mutex</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">        fprintf(stdout,</span><span class="doxyHighlightStringLiteral">"See '%s' for the reason of termination.\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">    exit(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a807b8e20fe24490244de4bfdaf531bef">g_warnStat</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="#abf45c484c585bd82d2d892c29de4a0be">g&#95;mutex</a>, <a href="#a8e1d65011b82b41029cea922b7b3c298">g&#95;warnBehavior</a>, <a href="#abfb684889b2b27eb72e96af8478b5f85">g&#95;warnFile</a>, <a href="#aef140dc11e587afb68a5b902eef06241">g&#95;warnlogFile</a>, <a href="#a807b8e20fe24490244de4bfdaf531bef">g&#95;warnStat</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>.

Referenced by <a href="#a64ba1596ef3046e773e49494e9e25913">do&#95;warn</a>, <a href="#a3a494fadd4c48c14de490e66d80bb279">err&#95;</a> and <a href="#a9860ed9c33a1b2d1842c66e97c2e9eba">warn&#95;uncond&#95;</a>.
</div>
</div>

### initWarningFormat() {#aa0b7262dc94aba9476d8669db4f3920e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void initWarningFormat ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00237">237</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0b7262dc94aba9476d8669db4f3920e">237</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa0b7262dc94aba9476d8669db4f3920e">initWarningFormat</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aad4ae1643bcdbcff1680a322e5bbae8d">g_warnFormat</a>     = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(WARN_FORMAT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7a6bddc99419347af9c2d3569bada867">g_warnLineFormat</a> = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(WARN_LINE_FORMAT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a>   = <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(WARN_AS_ERROR);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>    = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(WARN_LOGFILE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>.isEmpty() &amp;&amp; <a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a> == WARN_AS_ERROR_t::FAIL_ON_WARNINGS_PRINT)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t pid = <a href="/web-doxygen/docs/api/namespaces/portable/#a4e8eda17264bc9f97c4d106882c8d874">Portable::pid</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>.sprintf(</span><span class="doxyHighlightStringLiteral">"doxygen_warnings_temp_%d.tmp"</span><span class="doxyHighlight">,pid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a74c872d0bf5eb507f454aaa810973144">g_warnlogTemp</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a> == </span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> = stdout;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/dir">Dir</a> d(fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>().c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!d.<a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">exists</a>() &amp;&amp; !d.<a href="/web-doxygen/docs/api/classes/dir/#a286f4b1852b489ffcc8b6837c7e6bd8e">mkdir</a>(fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>().c_str()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// point it to something valid, because warn() relies on it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> = stderr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Cannot create directory for '{}', redirecting 'WARN_LOGFILE' output to 'stderr'\n"</span><span class="doxyHighlight">,<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!(<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> = <a href="/web-doxygen/docs/api/namespaces/portable/#a4dbb08c3de409bd1a73be3da6d93ac57">Portable::fopen</a>(<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>,</span><span class="doxyHighlightStringLiteral">"w"</span><span class="doxyHighlight">)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// point it to something valid, because warn() relies on it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> = stderr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Cannot open '{}' for writing, redirecting 'WARN_LOGFILE' output to 'stderr'\n"</span><span class="doxyHighlight">,<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> = stderr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a> != WARN_AS_ERROR_t::NO)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a9d34be93b99045d723b7edc562d10ce4">g_warningStr</a> = <a href="#a8a0504f5cfc80ac9db15736e27d04554">g_errorStr</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// make sure the g_warnFile is closed in case we call exit and it is still open</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">  std::atexit([](){</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> &amp;&amp; <a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>!=stderr &amp;&amp; <a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>!=stdout)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/namespaces/portable/#af099fa6239b4961887192d8eadfd2a44">Portable::fclose</a>(<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">  });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config&#95;getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config&#95;getString</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">Dir::exists</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#af099fa6239b4961887192d8eadfd2a44">Portable::fclose</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a4dbb08c3de409bd1a73be3da6d93ac57">Portable::fopen</a>, <a href="#a8a0504f5cfc80ac9db15736e27d04554">g&#95;errorStr</a>, <a href="#a8e1d65011b82b41029cea922b7b3c298">g&#95;warnBehavior</a>, <a href="#abfb684889b2b27eb72e96af8478b5f85">g&#95;warnFile</a>, <a href="#aad4ae1643bcdbcff1680a322e5bbae8d">g&#95;warnFormat</a>, <a href="#a9d34be93b99045d723b7edc562d10ce4">g&#95;warningStr</a>, <a href="#a7a6bddc99419347af9c2d3569bada867">g&#95;warnLineFormat</a>, <a href="#aef140dc11e587afb68a5b902eef06241">g&#95;warnlogFile</a>, <a href="#a74c872d0bf5eb507f454aaa810973144">g&#95;warnlogTemp</a>, <a href="/web-doxygen/docs/api/classes/dir/#a286f4b1852b489ffcc8b6837c7e6bd8e">Dir::mkdir</a> and <a href="/web-doxygen/docs/api/namespaces/portable/#a4e8eda17264bc9f97c4d106882c8d874">Portable::pid</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2426bb829c785229969c3052f3e37fb1">checkConfiguration</a>.
</div>
</div>

### msg&#95;() {#aca6c414913e8be769863ed67c1e82141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void msg_ (fmt::string_view fmt, fmt::format_args args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00130">130</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aca6c414913e8be769863ed67c1e82141">130</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aca6c414913e8be769863ed67c1e82141">msg_</a>(fmt::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, fmt::format_args args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(QUIET))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_lock&lt;std::mutex&gt; lock(<a href="#abf45c484c585bd82d2d892c29de4a0be">g_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da9cbd5d3516ffd3fe86238779edb2f7c5">Debug::Time</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">      fmt::print(</span><span class="doxyHighlightStringLiteral">"{:.3f} sec: "</span><span class="doxyHighlight">,(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/debug/#accc1a68a6e51b015caee0ab90ddb6e87">Debug::elapsedTime</a>())));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    fmt::print(</span><span class="doxyHighlightStringLiteral">"{}"</span><span class="doxyHighlight">,fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/debug/#accc1a68a6e51b015caee0ab90ddb6e87">Debug::elapsedTime</a>, <a href="#abf45c484c585bd82d2d892c29de4a0be">g&#95;mutex</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a> and <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da9cbd5d3516ffd3fe86238779edb2f7c5">Debug::Time</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/message-h/#ace632f900cabdba027c4f8034b7c31ef">msg&#95;fmt</a>.
</div>
</div>

### term&#95;() {#aea5f4b9b7bf7b3f59be94e5e096095ad}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void term_ (fmt::string_view fmt, fmt::format_args args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00193">193</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aea5f4b9b7bf7b3f59be94e5e096095ad">193</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aea5f4b9b7bf7b3f59be94e5e096095ad">term_</a>(fmt::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, fmt::format_args args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_lock&lt;std::mutex&gt; lock(<a href="#abf45c484c585bd82d2d892c29de4a0be">g_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>(<a href="#a8a0504f5cfc80ac9db15736e27d04554">g_errorStr</a>+fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args))) fmt::print(<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>, </span><span class="doxyHighlightStringLiteral">"{}{}"</span><span class="doxyHighlight">, <a href="#a8a0504f5cfc80ac9db15736e27d04554">g_errorStr</a>, fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> != stderr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l = strlen(<a href="#a8a0504f5cfc80ac9db15736e27d04554">g_errorStr</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0; i&lt;l; i++) fmt::print(<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>, </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">      fmt::print(<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>, </span><span class="doxyHighlightStringLiteral">"{}\n"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"Exiting..."</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(QUIET))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// cannot use `msg` due to the mutex</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">        fmt::print(</span><span class="doxyHighlightStringLiteral">"See '{}' for the reason of termination.\n"</span><span class="doxyHighlight">,<a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  exit(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="#a8a0504f5cfc80ac9db15736e27d04554">g&#95;errorStr</a>, <a href="#abf45c484c585bd82d2d892c29de4a0be">g&#95;mutex</a>, <a href="#abfb684889b2b27eb72e96af8478b5f85">g&#95;warnFile</a> and <a href="#aef140dc11e587afb68a5b902eef06241">g&#95;warnlogFile</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/message-h/#a470c151e1a1142bf01f5e9be2500d20d">term&#95;fmt</a>.
</div>
</div>

### warn&#95;() {#a7bb548412cf2bb2cf0d98b653eadaa88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void warn_ (<a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312ae">WarningType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, int line, fmt::string_view fmt, fmt::format_args args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00145">145</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7bb548412cf2bb2cf0d98b653eadaa88">145</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7bb548412cf2bb2cf0d98b653eadaa88">warn_</a>(<a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312ae">WarningType</a> type, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line, fmt::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, fmt::format_args args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> enabled = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312aea8045a0a6c688b0635e3caccc408a1446">WarningType::Generic</a>:       enabled = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARNINGS);               </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312aeafcb2132b65cdd119b19be66fbc3622e2">WarningType::Undocumented</a>:  enabled = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARN_IF_UNDOCUMENTED);   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312aead321401b4e59fb2eb89b942818e860bb">WarningType::IncompleteDoc</a>: enabled = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARN_IF_INCOMPLETE_DOC); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312aeafb8427f1dd12e9cfe06017e2d46f6843">WarningType::DocError</a>:      enabled = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARN_IF_DOC_ERROR);      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312aeaebd9bec4d70abc789d439c1f136b0538">WarningType::Layout</a>:        enabled = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(WARN_LAYOUT_FILE);       </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (enabled)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a64ba1596ef3046e773e49494e9e25913">do_warn</a>(file, line, <a href="#a9d34be93b99045d723b7edc562d10ce4">g_warningStr</a>, <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, args);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="#a64ba1596ef3046e773e49494e9e25913">do&#95;warn</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312aeafb8427f1dd12e9cfe06017e2d46f6843">DocError</a>, <a href="#a9d34be93b99045d723b7edc562d10ce4">g&#95;warningStr</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312aea8045a0a6c688b0635e3caccc408a1446">Generic</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312aead321401b4e59fb2eb89b942818e860bb">IncompleteDoc</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312aeaebd9bec4d70abc789d439c1f136b0538">Layout</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#aa278aa207bdeddc8432b560d1e1312aeafcb2132b65cdd119b19be66fbc3622e2">Undocumented</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/message-h/#af459e756f4676a24a106e67723415920">warn&#95;fmt</a>.
</div>
</div>

### warn&#95;flush() {#aad9799c2a434877f36bc92beb8966567}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void warn_flush ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00230">230</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad9799c2a434877f36bc92beb8966567">230</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aad9799c2a434877f36bc92beb8966567">warn_flush</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">  fflush(<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#abfb684889b2b27eb72e96af8478b5f85">g&#95;warnFile</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/statistics/#aa3c0ae123d9f74e170ba1bab16dd8575">Statistics::end</a>.
</div>
</div>

### warn&#95;line() {#a4149b6b3cb3e0246eb2e0d47de02538f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString warn_line (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, int line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00215">215</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4149b6b3cb3e0246eb2e0d47de02538f">215</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a4149b6b3cb3e0246eb2e0d47de02538f">warn_line</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileSubst = file.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? </span><span class="doxyHighlightStringLiteral">"&lt;unknown&gt;"</span><span class="doxyHighlight"> : file;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> lineSubst; lineSubst.<a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">setNum</a>(line);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#a7a6bddc99419347af9c2d3569bada867">g_warnLineFormat</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightStringLiteral">"$file"</span><span class="doxyHighlight">,fileSubst</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">            ),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"$line"</span><span class="doxyHighlight">,lineSubst</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a7a6bddc99419347af9c2d3569bada867">g&#95;warnLineFormat</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a87d2bfa3fcbf407c32fab784df368b2d">QCString::setNum</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3a9544cc7b9cd55b82e9bde25d70f247">addMemberFunction</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab8f6cdb1a0374f49399a31bd2ea0226a">checkPageRelations</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#abc809fca2014e90fe0aee477a1964ed7">computePageRelations</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a5dc8c4afa4009560979330b7c6fb2cb3">findGlobalMember</a>.
</div>
</div>

### warn&#95;uncond&#95;() {#a9860ed9c33a1b2d1842c66e97c2e9eba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void warn_uncond_ (fmt::string_view fmt, fmt::format_args args)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00164">164</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9860ed9c33a1b2d1842c66e97c2e9eba">164</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9860ed9c33a1b2d1842c66e97c2e9eba">warn_uncond_</a>(fmt::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, fmt::format_args args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_lock&lt;std::mutex&gt; lock(<a href="#abf45c484c585bd82d2d892c29de4a0be">g_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>(<a href="#a8a0504f5cfc80ac9db15736e27d04554">g_errorStr</a>+fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args))) fmt::print(<a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a>,</span><span class="doxyHighlightStringLiteral">"{}{}"</span><span class="doxyHighlight">,<a href="#a9d34be93b99045d723b7edc562d10ce4">g_warningStr</a>,vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aed763574c33aa626cd8209d9d681938a">handle_warn_as_error</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>, <a href="#a8a0504f5cfc80ac9db15736e27d04554">g&#95;errorStr</a>, <a href="#abf45c484c585bd82d2d892c29de4a0be">g&#95;mutex</a>, <a href="#abfb684889b2b27eb72e96af8478b5f85">g&#95;warnFile</a>, <a href="#a9d34be93b99045d723b7edc562d10ce4">g&#95;warningStr</a> and <a href="#aed763574c33aa626cd8209d9d681938a">handle&#95;warn&#95;as&#95;error</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/message-h/#a38008a48b77c36b6ab647ba2cc5017b9">warn&#95;uncond&#95;fmt</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### g&#95;errorStr {#a8a0504f5cfc80ac9db15736e27d04554}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* g_errorStr = "error: "</td>
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


<p>Definition at line <a href="#l00035">35</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8a0504f5cfc80ac9db15736e27d04554">35</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *    <a href="#a8a0504f5cfc80ac9db15736e27d04554">g_errorStr</a> = </span><span class="doxyHighlightStringLiteral">"error: "</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a3a494fadd4c48c14de490e66d80bb279">err&#95;</a>, <a href="#aee081170866fc184d3119f7c24566b74">err&#95;full&#95;</a>, <a href="#aa0b7262dc94aba9476d8669db4f3920e">initWarningFormat</a>, <a href="#aea5f4b9b7bf7b3f59be94e5e096095ad">term&#95;</a> and <a href="#a9860ed9c33a1b2d1842c66e97c2e9eba">warn&#95;uncond&#95;</a>.
</div>
</div>

### g&#95;mutex {#abf45c484c585bd82d2d892c29de4a0be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_mutex</td>
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


<p>Definition at line <a href="#l00041">41</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf45c484c585bd82d2d892c29de4a0be">41</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::mutex      <a href="#abf45c484c585bd82d2d892c29de4a0be">g_mutex</a>;</span></span></div>

</div>


Referenced by <a href="#a3a494fadd4c48c14de490e66d80bb279">err&#95;</a>, <a href="#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a>, <a href="#aed763574c33aa626cd8209d9d681938a">handle&#95;warn&#95;as&#95;error</a>, <a href="#aca6c414913e8be769863ed67c1e82141">msg&#95;</a>, <a href="#aea5f4b9b7bf7b3f59be94e5e096095ad">term&#95;</a> and <a href="#a9860ed9c33a1b2d1842c66e97c2e9eba">warn&#95;uncond&#95;</a>.
</div>
</div>

### g&#95;warnBehavior {#a8e1d65011b82b41029cea922b7b3c298}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WARN_AS_ERROR_t g_warnBehavior = <a href="/web-doxygen/docs/api/files/src/latexdocvisitor-h/#ac63cb3ba9a18f02ff6bde1a72b79b492ac2f3f489a00553e7a01d369c103c7251">WARN&#95;AS&#95;ERROR&#95;t::NO</a></td>
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


<p>Definition at line <a href="#l00037">37</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e1d65011b82b41029cea922b7b3c298">37</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> WARN_AS_ERROR_t <a href="#a8e1d65011b82b41029cea922b7b3c298">g_warnBehavior</a> = WARN_AS_ERROR_t::NO;</span></span></div>

</div>


Referenced by <a href="#ae3d3e3fe0dd73eb3fe463e99d2bd4a73">finishWarnExit</a>, <a href="#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a>, <a href="#aed763574c33aa626cd8209d9d681938a">handle&#95;warn&#95;as&#95;error</a> and <a href="#aa0b7262dc94aba9476d8669db4f3920e">initWarningFormat</a>.
</div>
</div>

### g&#95;warnFile {#abfb684889b2b27eb72e96af8478b5f85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FILE* g_warnFile = stderr</td>
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


<p>Definition at line <a href="#l00036">36</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abfb684889b2b27eb72e96af8478b5f85">36</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> FILE *          <a href="#abfb684889b2b27eb72e96af8478b5f85">g_warnFile</a> = stderr;</span></span></div>

</div>


Referenced by <a href="#a3a494fadd4c48c14de490e66d80bb279">err&#95;</a>, <a href="#ae3d3e3fe0dd73eb3fe463e99d2bd4a73">finishWarnExit</a>, <a href="#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a>, <a href="#aed763574c33aa626cd8209d9d681938a">handle&#95;warn&#95;as&#95;error</a>, <a href="#aa0b7262dc94aba9476d8669db4f3920e">initWarningFormat</a>, <a href="#aea5f4b9b7bf7b3f59be94e5e096095ad">term&#95;</a>, <a href="#aad9799c2a434877f36bc92beb8966567">warn&#95;flush</a> and <a href="#a9860ed9c33a1b2d1842c66e97c2e9eba">warn&#95;uncond&#95;</a>.
</div>
</div>

### g&#95;warnFormat {#aad4ae1643bcdbcff1680a322e5bbae8d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_warnFormat</td>
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


<p>Definition at line <a href="#l00032">32</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad4ae1643bcdbcff1680a322e5bbae8d">32</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>        <a href="#aad4ae1643bcdbcff1680a322e5bbae8d">g_warnFormat</a>;</span></span></div>

</div>


Referenced by <a href="#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a> and <a href="#aa0b7262dc94aba9476d8669db4f3920e">initWarningFormat</a>.
</div>
</div>

### g&#95;warnHash {#ab1c5d408176641f644437b6c4b551246}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_set&lt;std::string&gt; g_warnHash</td>
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


<p>Definition at line <a href="#l00042">42</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab1c5d408176641f644437b6c4b551246">42</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::unordered_set&lt;std::string&gt; <a href="#ab1c5d408176641f644437b6c4b551246">g_warnHash</a>;</span></span></div>

</div>


Referenced by <a href="#a158f798fb6e8971c1480747fa7061a96">checkWarnMessage</a>.
</div>
</div>

### g&#95;warningStr {#a9d34be93b99045d723b7edc562d10ce4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char* g_warningStr = "warning: "</td>
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


<p>Definition at line <a href="#l00034">34</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9d34be93b99045d723b7edc562d10ce4">34</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *    <a href="#a9d34be93b99045d723b7edc562d10ce4">g_warningStr</a> = </span><span class="doxyHighlightStringLiteral">"warning: "</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#aa0b7262dc94aba9476d8669db4f3920e">initWarningFormat</a>, <a href="#a7bb548412cf2bb2cf0d98b653eadaa88">warn&#95;</a> and <a href="#a9860ed9c33a1b2d1842c66e97c2e9eba">warn&#95;uncond&#95;</a>.
</div>
</div>

### g&#95;warnLineFormat {#a7a6bddc99419347af9c2d3569bada867}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_warnLineFormat</td>
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


<p>Definition at line <a href="#l00033">33</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a6bddc99419347af9c2d3569bada867">33</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>        <a href="#a7a6bddc99419347af9c2d3569bada867">g_warnLineFormat</a>;</span></span></div>

</div>


Referenced by <a href="#aa0b7262dc94aba9476d8669db4f3920e">initWarningFormat</a> and <a href="#a4149b6b3cb3e0246eb2e0d47de02538f">warn&#95;line</a>.
</div>
</div>

### g&#95;warnlogFile {#aef140dc11e587afb68a5b902eef06241}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString g_warnlogFile</td>
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


<p>Definition at line <a href="#l00038">38</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aef140dc11e587afb68a5b902eef06241">38</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>        <a href="#aef140dc11e587afb68a5b902eef06241">g_warnlogFile</a>;</span></span></div>

</div>


Referenced by <a href="#ae3d3e3fe0dd73eb3fe463e99d2bd4a73">finishWarnExit</a>, <a href="#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a>, <a href="#aed763574c33aa626cd8209d9d681938a">handle&#95;warn&#95;as&#95;error</a>, <a href="#aa0b7262dc94aba9476d8669db4f3920e">initWarningFormat</a> and <a href="#aea5f4b9b7bf7b3f59be94e5e096095ad">term&#95;</a>.
</div>
</div>

### g&#95;warnlogTemp {#a74c872d0bf5eb507f454aaa810973144}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool g_warnlogTemp = false</td>
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


<p>Definition at line <a href="#l00039">39</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74c872d0bf5eb507f454aaa810973144">39</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">            <a href="#a74c872d0bf5eb507f454aaa810973144">g_warnlogTemp</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#ae3d3e3fe0dd73eb3fe463e99d2bd4a73">finishWarnExit</a> and <a href="#aa0b7262dc94aba9476d8669db4f3920e">initWarningFormat</a>.
</div>
</div>

### g&#95;warnStat {#a807b8e20fe24490244de4bfdaf531bef}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::atomic_bool g_warnStat = false</td>
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


<p>Definition at line <a href="#l00040">40</a> of file <a href="/web-doxygen/docs/api/files/src/message-cpp">message.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a807b8e20fe24490244de4bfdaf531bef">40</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::atomic_bool <a href="#a807b8e20fe24490244de4bfdaf531bef">g_warnStat</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#ae3d3e3fe0dd73eb3fe463e99d2bd4a73">finishWarnExit</a>, <a href="#ad150b78be80374eb1373be71e75a67b0">format&#95;warn</a> and <a href="#aed763574c33aa626cd8209d9d681938a">handle&#95;warn&#95;as&#95;error</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
