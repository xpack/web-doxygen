---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/configint
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConfigInt` Class Reference

<p>Class representing an integer type option. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ConfigInt { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/configimpl-h">src/configimpl.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract base class for any configuration option. <a href="/web-doxygen/docs/api/classes/configoption/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07aa951c7f1a25bc0eec264b74015fb9">ConfigInt</a> (const char *name, const char *doc, int minVal, int maxVal, int defVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f025760eadf112578d6451710286929">valueStringRef</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26b63e65bd4757c0501700371b9ef4c4">valueRef</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae9fc76f1f588da6c5e4867b1943167fe">minVal</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a491b02657945f80a7ffb5cb9b3562ab7">maxVal</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0d01345ae582a8ba26a294c6e1b890">convertStrToVal</a> (Config::CompareMode compareMode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af38d914b18d3ac4fb9da0180de95901d">substEnvVars</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adac9662550d30efe51112c6f97485c60">writeTemplate</a> (TextStream &amp;t, bool sl, bool upd) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa9ef08f8142fa34f77f5351ce0f219cf">compareDoxyfile</a> (TextStream &amp;t, Config::CompareMode compareMode) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a493485085f602ae7bc5d959189533b1c">writeXMLDoxyfile</a> (TextStream &amp;t) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fab34082187b857a0633311c40f9e29">writeXSDDoxyfile</a> (TextStream &amp;t) override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c0badc91c243cac1ad49ddc290c78b3">init</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2886d897633e8aacb59f7530b736ebac">isDefault</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7de94b39eaeae44adf454fc0cfc4948">m_defValue</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a049b50af51f97be4d016f0024d0fc83c">m_minVal</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a915eccce79f281db89e960354a20d162">m_maxVal</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a></td>
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

<p>Class representing an integer type option.</p>

<p>Definition at line 219 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ConfigInt() {#a07aa951c7f1a25bc0eec264b74015fb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigInt::ConfigInt (const char * name, const char * doc, int minVal, int maxVal, int defVal)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 222 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07aa951c7f1a25bc0eec264b74015fb9">222</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a07aa951c7f1a25bc0eec264b74015fb9">ConfigInt</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *doc,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ae9fc76f1f588da6c5e4867b1943167fe">minVal</a>,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a491b02657945f80a7ffb5cb9b3562ab7">maxVal</a>,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defVal)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption</a>(<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaac029c8062b88308de12914e88e12dcd8">O_Int</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> = <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">m_doc</a> = doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a> = defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac7de94b39eaeae44adf454fc0cfc4948">m_defValue</a> = defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a049b50af51f97be4d016f0024d0fc83c">m_minVal</a> = <a href="#ae9fc76f1f588da6c5e4867b1943167fe">minVal</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a915eccce79f281db89e960354a20d162">m_maxVal</a> = <a href="#a491b02657945f80a7ffb5cb9b3562ab7">maxVal</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption::ConfigOption</a>, <a href="#ac7de94b39eaeae44adf454fc0cfc4948">m_defValue</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">ConfigOption::m_doc</a>, <a href="#a915eccce79f281db89e960354a20d162">m_maxVal</a>, <a href="#a049b50af51f97be4d016f0024d0fc83c">m_minVal</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>, <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a>, <a href="#a491b02657945f80a7ffb5cb9b3562ab7">maxVal</a>, <a href="#ae9fc76f1f588da6c5e4867b1943167fe">minVal</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">ConfigOption::name</a> and <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaac029c8062b88308de12914e88e12dcd8">ConfigOption::O_Int</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compareDoxyfile() {#aa9ef08f8142fa34f77f5351ce0f219cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigInt::compareDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</td>
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



<p>Declaration at line 239 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 550 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa9ef08f8142fa34f77f5351ce0f219cf">550</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa9ef08f8142fa34f77f5351ce0f219cf">ConfigInt::compareDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a2886d897633e8aacb59f7530b736ebac">isDefault</a>() || ((compareMode == <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompareMode::CompressedNoEnv</a>) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>(<a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>))) <a href="#adac9662550d30efe51112c6f97485c60">writeTemplate</a>(t,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompressedNoEnv</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>, <a href="#a2886d897633e8aacb59f7530b736ebac">isDefault</a>, <a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#adac9662550d30efe51112c6f97485c60">writeTemplate</a>.</p>

</div>
</div>

### convertStrToVal() {#a6b0d01345ae582a8ba26a294c6e1b890}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigInt::convertStrToVal (<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</td>
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



<p>Declaration at line 236 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 195 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b0d01345ae582a8ba26a294c6e1b890">195</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6b0d01345ae582a8ba26a294c6e1b890">ConfigInt::convertStrToVal</a>(<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (compareMode == <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompareMode::CompressedNoEnv</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>(<a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> val = <a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>.toInt(&amp;ok);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ok || val&lt;m_minVal || val&gt;<a href="#a915eccce79f281db89e960354a20d162">m_maxVal</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"argument '{}' for option {} is not a valid number in the range [{}..{}]!\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">                </span><span class="doxyHighlightStringLiteral">"Using the default: {}!\n"</span><span class="doxyHighlight">,<a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>,<a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a>,<a href="#a049b50af51f97be4d016f0024d0fc83c">m_minVal</a>,<a href="#a915eccce79f281db89e960354a20d162">m_maxVal</a>,<a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a>=val;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompressedNoEnv</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>, <a href="#a915eccce79f281db89e960354a20d162">m_maxVal</a>, <a href="#a049b50af51f97be4d016f0024d0fc83c">m_minVal</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>, <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a> and <a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>.</p>

</div>
</div>

### init() {#a1c0badc91c243cac1ad49ddc290c78b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigInt::init ()</td>
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



<p>Definition at line 242 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c0badc91c243cac1ad49ddc290c78b3">242</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1c0badc91c243cac1ad49ddc290c78b3">init</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a> = <a href="#ac7de94b39eaeae44adf454fc0cfc4948">m_defValue</a>; }</span></span></div>

</div>


<p>References <a href="#ac7de94b39eaeae44adf454fc0cfc4948">m_defValue</a> and <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a>.</p>

</div>
</div>

### isDefault() {#a2886d897633e8aacb59f7530b736ebac}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConfigInt::isDefault ()</td>
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



<p>Definition at line 243 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2886d897633e8aacb59f7530b736ebac">243</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2886d897633e8aacb59f7530b736ebac">isDefault</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a> == <a href="#ac7de94b39eaeae44adf454fc0cfc4948">m_defValue</a>; }</span></span></div>

</div>


<p>References <a href="#ac7de94b39eaeae44adf454fc0cfc4948">m_defValue</a> and <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a>.</p>


<p>Referenced by <a href="#aa9ef08f8142fa34f77f5351ce0f219cf">compareDoxyfile</a> and <a href="#a493485085f602ae7bc5d959189533b1c">writeXMLDoxyfile</a>.</p>

</div>
</div>

### maxVal() {#a491b02657945f80a7ffb5cb9b3562ab7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ConfigInt::maxVal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 235 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a491b02657945f80a7ffb5cb9b3562ab7">235</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a491b02657945f80a7ffb5cb9b3562ab7">maxVal</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a915eccce79f281db89e960354a20d162">m_maxVal</a>; }</span></span></div>

</div>


<p>Reference <a href="#a915eccce79f281db89e960354a20d162">m_maxVal</a>.</p>


<p>Referenced by <a href="#a07aa951c7f1a25bc0eec264b74015fb9">ConfigInt</a>.</p>

</div>
</div>

### minVal() {#ae9fc76f1f588da6c5e4867b1943167fe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ConfigInt::minVal ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 234 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae9fc76f1f588da6c5e4867b1943167fe">234</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ae9fc76f1f588da6c5e4867b1943167fe">minVal</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a049b50af51f97be4d016f0024d0fc83c">m_minVal</a>; }</span></span></div>

</div>


<p>Reference <a href="#a049b50af51f97be4d016f0024d0fc83c">m_minVal</a>.</p>


<p>Referenced by <a href="#a07aa951c7f1a25bc0eec264b74015fb9">ConfigInt</a>.</p>

</div>
</div>

### substEnvVars() {#af38d914b18d3ac4fb9da0180de95901d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigInt::substEnvVars ()</td>
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



<p>Declaration at line 237 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1521 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af38d914b18d3ac4fb9da0180de95901d">1521</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af38d914b18d3ac4fb9da0180de95901d">ConfigInt::substEnvVars</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>(<a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a> and <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>.</p>

</div>
</div>

### valueRef() {#a26b63e65bd4757c0501700371b9ef4c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int * ConfigInt::valueRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 233 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a26b63e65bd4757c0501700371b9ef4c4">233</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> *<a href="#a26b63e65bd4757c0501700371b9ef4c4">valueRef</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a>; }</span></span></div>

</div>


<p>Reference <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a>.</p>

</div>
</div>

### valueStringRef() {#a1f025760eadf112578d6451710286929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString * ConfigInt::valueStringRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 232 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f025760eadf112578d6451710286929">232</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *<a href="#a1f025760eadf112578d6451710286929">valueStringRef</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>; }</span></span></div>

</div>


<p>Reference <a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>.</p>

</div>
</div>

### writeTemplate() {#adac9662550d30efe51112c6f97485c60}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigInt::writeTemplate (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, bool sl, bool upd)</td>
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



<p>Declaration at line 238 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 526 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adac9662550d30efe51112c6f97485c60">526</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adac9662550d30efe51112c6f97485c60">ConfigInt::writeTemplate</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sl,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> upd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!sl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>(<a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">m_doc</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#aa3ef6fe13a480dad1404aee1bb0f2d11">m_spaces</a>.left(<a href="/web-doxygen/docs/api/classes/configoption/#a641ee9c39bb9c1951b3079073b09d965aa40e4123355dbeb41dc6ca0c68c0d346">MAX_OPTION_LENGTH</a>-<a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a>.length()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (upd &amp;&amp; !<a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">writeStringValue</a>(t,<a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configoption/#a71ca02feacb0119f2130c0b07c2fe755">writeIntValue</a>(t,<a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">ConfigOption::m_doc</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>, <a href="/web-doxygen/docs/api/classes/configoption/#aa3ef6fe13a480dad1404aee1bb0f2d11">ConfigOption::m_spaces</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">ConfigOption::m_userComment</a>, <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a>, <a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a641ee9c39bb9c1951b3079073b09d965aa40e4123355dbeb41dc6ca0c68c0d346">ConfigOption::MAX_OPTION_LENGTH</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a71ca02feacb0119f2130c0b07c2fe755">ConfigOption::writeIntValue</a> and <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">ConfigOption::writeStringValue</a>.</p>


<p>Referenced by <a href="#aa9ef08f8142fa34f77f5351ce0f219cf">compareDoxyfile</a>.</p>

</div>
</div>

### writeXMLDoxyfile() {#a493485085f602ae7bc5d959189533b1c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigInt::writeXMLDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



<p>Declaration at line 240 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 555 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a493485085f602ae7bc5d959189533b1c">555</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a493485085f602ae7bc5d959189533b1c">ConfigInt::writeXMLDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;option  id='"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" default='"</span><span class="doxyHighlight"> &lt;&lt; (<a href="#a2886d897633e8aacb59f7530b736ebac">isDefault</a>() ? </span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"no"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" type='int'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;value&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption/#a71ca02feacb0119f2130c0b07c2fe755">writeIntValue</a>(t,<a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a>,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/value&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/option&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a2886d897633e8aacb59f7530b736ebac">isDefault</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>, <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a> and <a href="/web-doxygen/docs/api/classes/configoption/#a71ca02feacb0119f2130c0b07c2fe755">ConfigOption::writeIntValue</a>.</p>

</div>
</div>

### writeXSDDoxyfile() {#a8fab34082187b857a0633311c40f9e29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigInt::writeXSDDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



<p>Declaration at line 241 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 567 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8fab34082187b857a0633311c40f9e29">567</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8fab34082187b857a0633311c40f9e29">ConfigInt::writeXSDDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;xsd:enumeration value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_defValue {#ac7de94b39eaeae44adf454fc0cfc4948}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ConfigInt::m_defValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 246 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7de94b39eaeae44adf454fc0cfc4948">246</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ac7de94b39eaeae44adf454fc0cfc4948">m_defValue</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a07aa951c7f1a25bc0eec264b74015fb9">ConfigInt</a>, <a href="#a1c0badc91c243cac1ad49ddc290c78b3">init</a> and <a href="#a2886d897633e8aacb59f7530b736ebac">isDefault</a>.</p>

</div>
</div>

### m\_maxVal {#a915eccce79f281db89e960354a20d162}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ConfigInt::m_maxVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 248 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a915eccce79f281db89e960354a20d162">248</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a915eccce79f281db89e960354a20d162">m_maxVal</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a07aa951c7f1a25bc0eec264b74015fb9">ConfigInt</a>, <a href="#a6b0d01345ae582a8ba26a294c6e1b890">convertStrToVal</a> and <a href="#a491b02657945f80a7ffb5cb9b3562ab7">maxVal</a>.</p>

</div>
</div>

### m\_minVal {#a049b50af51f97be4d016f0024d0fc83c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ConfigInt::m_minVal</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 247 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a049b50af51f97be4d016f0024d0fc83c">247</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a049b50af51f97be4d016f0024d0fc83c">m_minVal</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a07aa951c7f1a25bc0eec264b74015fb9">ConfigInt</a>, <a href="#a6b0d01345ae582a8ba26a294c6e1b890">convertStrToVal</a> and <a href="#ae9fc76f1f588da6c5e4867b1943167fe">minVal</a>.</p>

</div>
</div>

### m\_value {#aa7e6a8356e9e10bda43ab145605f6f1d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int ConfigInt::m_value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa7e6a8356e9e10bda43ab145605f6f1d">245</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#aa7e6a8356e9e10bda43ab145605f6f1d">m_value</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a07aa951c7f1a25bc0eec264b74015fb9">ConfigInt</a>, <a href="#a6b0d01345ae582a8ba26a294c6e1b890">convertStrToVal</a>, <a href="#a1c0badc91c243cac1ad49ddc290c78b3">init</a>, <a href="#a2886d897633e8aacb59f7530b736ebac">isDefault</a>, <a href="#a26b63e65bd4757c0501700371b9ef4c4">valueRef</a>, <a href="#adac9662550d30efe51112c6f97485c60">writeTemplate</a> and <a href="#a493485085f602ae7bc5d959189533b1c">writeXMLDoxyfile</a>.</p>

</div>
</div>

### m\_valueString {#ad8bb315421ab52bb9afd38bf41c6be5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigInt::m_valueString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 249 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8bb315421ab52bb9afd38bf41c6be5a">249</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad8bb315421ab52bb9afd38bf41c6be5a">m_valueString</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aa9ef08f8142fa34f77f5351ce0f219cf">compareDoxyfile</a>, <a href="#a6b0d01345ae582a8ba26a294c6e1b890">convertStrToVal</a>, <a href="#af38d914b18d3ac4fb9da0180de95901d">substEnvVars</a>, <a href="#a1f025760eadf112578d6451710286929">valueStringRef</a> and <a href="#adac9662550d30efe51112c6f97485c60">writeTemplate</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
