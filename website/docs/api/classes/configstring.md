---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/configstring
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ConfigString` Class Reference

<p>Class representing a string type option. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ConfigString { ... }
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

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">WidgetType { <a href="#a6d65e61d6dcbd73f014d16ef4b7721d1">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af35e791e48a93c96bdba2df9ca848f28">ConfigString</a> (const char *name, const char *doc)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35abeb5e79ca5812affa17d5ff67f5ee">setWidgetType</a> (WidgetType w)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6d65e61d6dcbd73f014d16ef4b7721d1">WidgetType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cad733ff76bb0fc898c9daffb578fd2">widgetType</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabfc2165fcdafd51ec0668d3fe4f7b35">setDefaultValue</a> (const char *v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a995a4f0d9d2799e285fd454dddb6b0f4">valueRef</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4357ea1ddcbab66cfbe6bd378499065">writeTemplate</a> (TextStream &amp;t, bool sl, bool) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aed83c7c4aad4a7f56e34022cd3810ddf">compareDoxyfile</a> (TextStream &amp;t, Config::CompareMode compareMode) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81e8986fb2d349fc60f26ef5e1f1f203">writeXMLDoxyfile</a> (TextStream &amp;t) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b5e6535f39872a352326dd4757dd27c">writeXSDDoxyfile</a> (TextStream &amp;t) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04e574eb2e0c9b5ac907f193c5909511">substEnvVars</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae2509071329426c4c5749eda585e1409">init</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6c3abad05ffdfc26cd9c16800ff4647">emptyValueToDefault</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b32e3eb111ddfa51fff3e3ef4b3d31e">isDefault</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a041a1d375a16343fb90e23a2b71faed6">m_value</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae12055fe874e925ee032d97b8b746247">m_defValue</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a6d65e61d6dcbd73f014d16ef4b7721d1">WidgetType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51a045dacc635387728409f78f6c8f63">m_widgetType</a></td>
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

<p>Class representing a string type option.</p>

<p>Definition at line 187 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxySectionDef">

## Enumerations

### WidgetType {#a6d65e61d6dcbd73f014d16ef4b7721d1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum ConfigString::WidgetType </td>
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
<td class="doxyEnumItemName">String<a id="a6d65e61d6dcbd73f014d16ef4b7721d1a11c4b738a4bf25daac178bdcafb7ee1d"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">File<a id="a6d65e61d6dcbd73f014d16ef4b7721d1af6654c1bae7f98471bc56277441a6792"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dir<a id="a6d65e61d6dcbd73f014d16ef4b7721d1a49f5b7433b27cfc3141075bb4501bcad"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Image<a id="a6d65e61d6dcbd73f014d16ef4b7721d1a9612c37242b61f3f1b221ceb22be3ad0"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">FileAndDir<a id="a6d65e61d6dcbd73f014d16ef4b7721d1a18caab78eb44d557d100fbffe7e6b882"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00190">190</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d65e61d6dcbd73f014d16ef4b7721d1a49f5b7433b27cfc3141075bb4501bcad">190</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum</span><span class="doxyHighlight"> <a href="#a6d65e61d6dcbd73f014d16ef4b7721d1">WidgetType</a> { <a href="#a6d65e61d6dcbd73f014d16ef4b7721d1a11c4b738a4bf25daac178bdcafb7ee1d">String</a>, <a href="#a6d65e61d6dcbd73f014d16ef4b7721d1af6654c1bae7f98471bc56277441a6792">File</a>, <a href="#a6d65e61d6dcbd73f014d16ef4b7721d1a49f5b7433b27cfc3141075bb4501bcad">Dir</a>, <a href="#a6d65e61d6dcbd73f014d16ef4b7721d1a9612c37242b61f3f1b221ceb22be3ad0">Image</a>, <a href="#a6d65e61d6dcbd73f014d16ef4b7721d1a18caab78eb44d557d100fbffe7e6b882">FileAndDir</a> };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### ConfigString() {#af35e791e48a93c96bdba2df9ca848f28}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigString::ConfigString (const char * name, const char * doc)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00191">191</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af35e791e48a93c96bdba2df9ca848f28">191</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af35e791e48a93c96bdba2df9ca848f28">ConfigString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *doc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption</a>(<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa3aa84b958a247d79889f28f4244a7d7f">O_String</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> = <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">m_doc</a> = doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a51a045dacc635387728409f78f6c8f63">m_widgetType</a> = <a href="#a6d65e61d6dcbd73f014d16ef4b7721d1a11c4b738a4bf25daac178bdcafb7ee1d">String</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption::ConfigOption</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">ConfigOption::m&#95;doc</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m&#95;name</a>, <a href="#a51a045dacc635387728409f78f6c8f63">m&#95;widgetType</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">ConfigOption::name</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa3aa84b958a247d79889f28f4244a7d7f">ConfigOption::O&#95;String</a> and <a href="#a6d65e61d6dcbd73f014d16ef4b7721d1a11c4b738a4bf25daac178bdcafb7ee1d">String</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compareDoxyfile() {#aed83c7c4aad4a7f56e34022cd3810ddf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigString::compareDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00203">203</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l00502">502</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aed83c7c4aad4a7f56e34022cd3810ddf">502</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aed83c7c4aad4a7f56e34022cd3810ddf">ConfigString::compareDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t, <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a1b32e3eb111ddfa51fff3e3ef4b3d31e">isDefault</a>()) <a href="#aa4357ea1ddcbab66cfbe6bd378499065">writeTemplate</a>(t,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1b32e3eb111ddfa51fff3e3ef4b3d31e">isDefault</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#aa4357ea1ddcbab66cfbe6bd378499065">writeTemplate</a>.
</div>
</div>

### emptyValueToDefault() {#ad6c3abad05ffdfc26cd9c16800ff4647}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigString::emptyValueToDefault ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00208">208</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6c3abad05ffdfc26cd9c16800ff4647">208</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad6c3abad05ffdfc26cd9c16800ff4647">emptyValueToDefault</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a041a1d375a16343fb90e23a2b71faed6">m_value</a>.isEmpty()) <a href="#a041a1d375a16343fb90e23a2b71faed6">m_value</a>=<a href="#ae12055fe874e925ee032d97b8b746247">m_defValue</a>; };</span></span></div>

</div>


References <a href="#ae12055fe874e925ee032d97b8b746247">m&#95;defValue</a> and <a href="#a041a1d375a16343fb90e23a2b71faed6">m&#95;value</a>.
</div>
</div>

### init() {#ae2509071329426c4c5749eda585e1409}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigString::init ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00207">207</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae2509071329426c4c5749eda585e1409">207</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae2509071329426c4c5749eda585e1409">init</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="#a041a1d375a16343fb90e23a2b71faed6">m_value</a> = <a href="#ae12055fe874e925ee032d97b8b746247">m_defValue</a>; }</span></span></div>

</div>


References <a href="#ae12055fe874e925ee032d97b8b746247">m&#95;defValue</a> and <a href="#a041a1d375a16343fb90e23a2b71faed6">m&#95;value</a>.

Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a88ed583dc36b1439108163403cc4224f">Config::parse</a>.
</div>
</div>

### isDefault() {#a1b32e3eb111ddfa51fff3e3ef4b3d31e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConfigString::isDefault ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00209">209</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b32e3eb111ddfa51fff3e3ef4b3d31e">209</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1b32e3eb111ddfa51fff3e3ef4b3d31e">isDefault</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a041a1d375a16343fb90e23a2b71faed6">m_value</a>.stripWhiteSpace() == <a href="#ae12055fe874e925ee032d97b8b746247">m_defValue</a>.stripWhiteSpace(); }</span></span></div>

</div>


References <a href="#ae12055fe874e925ee032d97b8b746247">m&#95;defValue</a> and <a href="#a041a1d375a16343fb90e23a2b71faed6">m&#95;value</a>.

Referenced by <a href="#aed83c7c4aad4a7f56e34022cd3810ddf">compareDoxyfile</a> and <a href="#a81e8986fb2d349fc60f26ef5e1f1f203">writeXMLDoxyfile</a>.
</div>
</div>

### setDefaultValue() {#aabfc2165fcdafd51ec0668d3fe4f7b35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigString::setDefaultValue (const char * v)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00200">200</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aabfc2165fcdafd51ec0668d3fe4f7b35">200</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aabfc2165fcdafd51ec0668d3fe4f7b35">setDefaultValue</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *v) { <a href="#ae12055fe874e925ee032d97b8b746247">m_defValue</a> = v; }</span></span></div>

</div>


Reference <a href="#ae12055fe874e925ee032d97b8b746247">m&#95;defValue</a>.
</div>
</div>

### setWidgetType() {#a35abeb5e79ca5812affa17d5ff67f5ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigString::setWidgetType (<a href="#a6d65e61d6dcbd73f014d16ef4b7721d1">WidgetType</a> w)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00198">198</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a35abeb5e79ca5812affa17d5ff67f5ee">198</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a35abeb5e79ca5812affa17d5ff67f5ee">setWidgetType</a>(<a href="#a6d65e61d6dcbd73f014d16ef4b7721d1">WidgetType</a> w) { <a href="#a51a045dacc635387728409f78f6c8f63">m_widgetType</a> = w; }</span></span></div>

</div>


Reference <a href="#a51a045dacc635387728409f78f6c8f63">m&#95;widgetType</a>.
</div>
</div>

### substEnvVars() {#a04e574eb2e0c9b5ac907f193c5909511}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigString::substEnvVars ()</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00206">206</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l01506">1506</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a04e574eb2e0c9b5ac907f193c5909511">1506</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a04e574eb2e0c9b5ac907f193c5909511">ConfigString::substEnvVars</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>(<a href="#a041a1d375a16343fb90e23a2b71faed6">m_value</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a041a1d375a16343fb90e23a2b71faed6">m&#95;value</a> and <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>.
</div>
</div>

### valueRef() {#a995a4f0d9d2799e285fd454dddb6b0f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString * ConfigString::valueRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00201">201</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a995a4f0d9d2799e285fd454dddb6b0f4">201</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *<a href="#a995a4f0d9d2799e285fd454dddb6b0f4">valueRef</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#a041a1d375a16343fb90e23a2b71faed6">m_value</a>; }</span></span></div>

</div>


Reference <a href="#a041a1d375a16343fb90e23a2b71faed6">m&#95;value</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a38bfc7b0b040cc8ceefae240aad38b94">checkEncoding</a> and <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>.
</div>
</div>

### widgetType() {#a7cad733ff76bb0fc898c9daffb578fd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WidgetType ConfigString::widgetType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00199">199</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7cad733ff76bb0fc898c9daffb578fd2">199</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6d65e61d6dcbd73f014d16ef4b7721d1">WidgetType</a> <a href="#a7cad733ff76bb0fc898c9daffb578fd2">widgetType</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a51a045dacc635387728409f78f6c8f63">m_widgetType</a>; }</span></span></div>

</div>


Reference <a href="#a51a045dacc635387728409f78f6c8f63">m&#95;widgetType</a>.
</div>
</div>

### writeTemplate() {#aa4357ea1ddcbab66cfbe6bd378499065}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigString::writeTemplate (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, bool sl, bool)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00202">202</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l00485">485</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa4357ea1ddcbab66cfbe6bd378499065">485</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa4357ea1ddcbab66cfbe6bd378499065">ConfigString::writeTemplate</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sl,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!sl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>(<a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">m_doc</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#aa3ef6fe13a480dad1404aee1bb0f2d11">m_spaces</a>.left(<a href="/web-doxygen/docs/api/classes/configoption/#a641ee9c39bb9c1951b3079073b09d965aa40e4123355dbeb41dc6ca0c68c0d346">MAX_OPTION_LENGTH</a>-<a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a>.length()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">writeStringValue</a>(t,<a href="#a041a1d375a16343fb90e23a2b71faed6">m_value</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">ConfigOption::m&#95;doc</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m&#95;name</a>, <a href="/web-doxygen/docs/api/classes/configoption/#aa3ef6fe13a480dad1404aee1bb0f2d11">ConfigOption::m&#95;spaces</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">ConfigOption::m&#95;userComment</a>, <a href="#a041a1d375a16343fb90e23a2b71faed6">m&#95;value</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a641ee9c39bb9c1951b3079073b09d965aa40e4123355dbeb41dc6ca0c68c0d346">ConfigOption::MAX&#95;OPTION&#95;LENGTH</a> and <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">ConfigOption::writeStringValue</a>.

Referenced by <a href="#aed83c7c4aad4a7f56e34022cd3810ddf">compareDoxyfile</a>.
</div>
</div>

### writeXMLDoxyfile() {#a81e8986fb2d349fc60f26ef5e1f1f203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigString::writeXMLDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00204">204</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l00507">507</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81e8986fb2d349fc60f26ef5e1f1f203">507</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a81e8986fb2d349fc60f26ef5e1f1f203">ConfigString::writeXMLDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;option  id='"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" default='"</span><span class="doxyHighlight"> &lt;&lt; (<a href="#a1b32e3eb111ddfa51fff3e3ef4b3d31e">isDefault</a>() ? </span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"no"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" type='string'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;value&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;![CDATA["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">writeStringValue</a>(t,<a href="#a041a1d375a16343fb90e23a2b71faed6">m_value</a>,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]]&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/value&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/option&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a1b32e3eb111ddfa51fff3e3ef4b3d31e">isDefault</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m&#95;name</a>, <a href="#a041a1d375a16343fb90e23a2b71faed6">m&#95;value</a> and <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">ConfigOption::writeStringValue</a>.
</div>
</div>

### writeXSDDoxyfile() {#a4b5e6535f39872a352326dd4757dd27c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigString::writeXSDDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00205">205</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l00521">521</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4b5e6535f39872a352326dd4757dd27c">521</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4b5e6535f39872a352326dd4757dd27c">ConfigString::writeXSDDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;xsd:enumeration value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m&#95;name</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;defValue {#ae12055fe874e925ee032d97b8b746247}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigString::m_defValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00213">213</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae12055fe874e925ee032d97b8b746247">213</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae12055fe874e925ee032d97b8b746247">m_defValue</a>;</span></span></div>

</div>


Referenced by <a href="#ad6c3abad05ffdfc26cd9c16800ff4647">emptyValueToDefault</a>, <a href="#ae2509071329426c4c5749eda585e1409">init</a>, <a href="#a1b32e3eb111ddfa51fff3e3ef4b3d31e">isDefault</a> and <a href="#aabfc2165fcdafd51ec0668d3fe4f7b35">setDefaultValue</a>.
</div>
</div>

### m&#95;value {#a041a1d375a16343fb90e23a2b71faed6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigString::m_value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00212">212</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a041a1d375a16343fb90e23a2b71faed6">212</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a041a1d375a16343fb90e23a2b71faed6">m_value</a>;</span></span></div>

</div>


Referenced by <a href="#ad6c3abad05ffdfc26cd9c16800ff4647">emptyValueToDefault</a>, <a href="#ae2509071329426c4c5749eda585e1409">init</a>, <a href="#a1b32e3eb111ddfa51fff3e3ef4b3d31e">isDefault</a>, <a href="#a04e574eb2e0c9b5ac907f193c5909511">substEnvVars</a>, <a href="#a995a4f0d9d2799e285fd454dddb6b0f4">valueRef</a>, <a href="#aa4357ea1ddcbab66cfbe6bd378499065">writeTemplate</a> and <a href="#a81e8986fb2d349fc60f26ef5e1f1f203">writeXMLDoxyfile</a>.
</div>
</div>

### m&#95;widgetType {#a51a045dacc635387728409f78f6c8f63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">WidgetType ConfigString::m_widgetType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00214">214</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a51a045dacc635387728409f78f6c8f63">214</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a6d65e61d6dcbd73f014d16ef4b7721d1">WidgetType</a> <a href="#a51a045dacc635387728409f78f6c8f63">m_widgetType</a>;</span></span></div>

</div>


Referenced by <a href="#af35e791e48a93c96bdba2df9ca848f28">ConfigString</a>, <a href="#a35abeb5e79ca5812affa17d5ff67f5ee">setWidgetType</a> and <a href="#a7cad733ff76bb0fc898c9daffb578fd2">widgetType</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
