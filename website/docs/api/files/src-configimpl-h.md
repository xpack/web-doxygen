---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/configimpl-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `configimpl.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;vector&gt;
#include &lt;unordered_map&gt;
#include &lt;string&gt;
#include &lt;memory&gt;
#include &lt;iostream&gt;
#include "<a href="/web-doxygen/docs/api/files/src/containers-h">containers.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Abstract base class for any configuration option. <a href="/web-doxygen/docs/api/classes/configoption/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configinfo">ConfigInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Section marker for grouping the configuration options. <a href="/web-doxygen/docs/api/classes/configinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configlist">ConfigList</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class representing a list type option. <a href="/web-doxygen/docs/api/classes/configlist/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class representing an enum type option. <a href="/web-doxygen/docs/api/classes/configenum/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class representing a string type option. <a href="/web-doxygen/docs/api/classes/configstring/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configint">ConfigInt</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class representing an integer type option. <a href="/web-doxygen/docs/api/classes/configint/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configbool">ConfigBool</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class representing a Boolean type option. <a href="/web-doxygen/docs/api/classes/configbool/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Section marker for obsolete options. <a href="/web-doxygen/docs/api/classes/configobsolete/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configdisabled">ConfigDisabled</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Section marker for compile time optional options. <a href="/web-doxygen/docs/api/classes/configdisabled/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configimpl">ConfigImpl</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Singleton for configuration variables. <a href="/web-doxygen/docs/api/classes/configimpl/#details">More...</a>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa0ece99d9324f0261354e12217c6888f">ConfigOptionList</a> = std::vector&lt; std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> &gt; &gt;</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad500d29f5bc4a52cf7a6b5e4d3c2bf8">ConfigOptionMap</a> = std::unordered_map&lt; std::string, <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> * &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bd161ae0aee486bcb7f2e82081bbc29">ConfigImpl_getString</a>(val)&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;getString(\_\_FILE\_\_,\_\_LINE\_\_,val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13b1e81f31f3f51a4efbe3c8ded57daf">ConfigImpl_getInt</a>(val)&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;getInt(\_\_FILE\_\_,\_\_LINE\_\_,val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52b5269fc72b0ae62828285a049e0ce5">ConfigImpl_getList</a>(val)&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;getList(\_\_FILE\_\_,\_\_LINE\_\_,val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7dd00a211fe14999c78fce030022cc8">ConfigImpl_getEnum</a>(val)&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;getEnum(\_\_FILE\_\_,\_\_LINE\_\_,val)</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aae7186f5d5a06fedba658e712974a9c8">ConfigImpl_getBool</a>(val)&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;getBool(\_\_FILE\_\_,\_\_LINE\_\_,val)</td>
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

### ConfigOptionList {#aa0ece99d9324f0261354e12217c6888f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ConfigOptionList =  std::vector&lt; std::unique_ptr&lt;ConfigOption&gt; &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 328 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa0ece99d9324f0261354e12217c6888f">328</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#aa0ece99d9324f0261354e12217c6888f">ConfigOptionList</a> = std::vector&lt; std::unique_ptr&lt;ConfigOption&gt; &gt;;</span></span></div>

</div>

</div>
</div>

### ConfigOptionMap {#aad500d29f5bc4a52cf7a6b5e4d3c2bf8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using ConfigOptionMap =  std::unordered_map&lt; std::string, ConfigOption* &gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 329 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad500d29f5bc4a52cf7a6b5e4d3c2bf8">329</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#aad500d29f5bc4a52cf7a6b5e4d3c2bf8">ConfigOptionMap</a>  = std::unordered_map&lt; std::string, ConfigOption* &gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### ConfigImpl\_getBool {#aae7186f5d5a06fedba658e712974a9c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ConfigImpl_getBool(val)&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;getBool(\_\_FILE\_\_,\_\_LINE\_\_,val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 325 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aae7186f5d5a06fedba658e712974a9c8">325</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ConfigImpl_getBool(val)    ConfigImpl::instance()-&gt;getBool(__FILE__,__LINE__,val)</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>.
</div>
</div>

### ConfigImpl\_getEnum {#af7dd00a211fe14999c78fce030022cc8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ConfigImpl_getEnum(val)&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;getEnum(\_\_FILE\_\_,\_\_LINE\_\_,val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 324 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7dd00a211fe14999c78fce030022cc8">324</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ConfigImpl_getEnum(val)    ConfigImpl::instance()-&gt;getEnum(__FILE__,__LINE__,val)</span></span></div>

</div>

</div>
</div>

### ConfigImpl\_getInt {#a13b1e81f31f3f51a4efbe3c8ded57daf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ConfigImpl_getInt(val)&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;getInt(\_\_FILE\_\_,\_\_LINE\_\_,val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 322 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a13b1e81f31f3f51a4efbe3c8ded57daf">322</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ConfigImpl_getInt(val)     ConfigImpl::instance()-&gt;getInt(__FILE__,__LINE__,val)</span></span></div>

</div>

</div>
</div>

### ConfigImpl\_getList {#a52b5269fc72b0ae62828285a049e0ce5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ConfigImpl_getList(val)&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;getList(\_\_FILE\_\_,\_\_LINE\_\_,val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 323 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52b5269fc72b0ae62828285a049e0ce5">323</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ConfigImpl_getList(val)    ConfigImpl::instance()-&gt;getList(__FILE__,__LINE__,val)</span></span></div>

</div>

</div>
</div>

### ConfigImpl\_getString {#a0bd161ae0aee486bcb7f2e82081bbc29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define ConfigImpl_getString(val)&nbsp;&nbsp;&nbsp;<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;getString(\_\_FILE\_\_,\_\_LINE\_\_,val)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 321 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0bd161ae0aee486bcb7f2e82081bbc29">321</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define ConfigImpl_getString(val)  ConfigImpl::instance()-&gt;getString(__FILE__,__LINE__,val)</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
