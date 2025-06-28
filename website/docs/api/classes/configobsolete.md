---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/configobsolete
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ConfigObsolete` Class Reference

<p>Section marker for obsolete options. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ConfigObsolete { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2af9cb643b1db43c0d51ae973ab870d2">ConfigObsolete</a> (const char *name, OptionType orgType)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44d7277ce16ab24f69f236ad082eb21a">writeTemplate</a> (TextStream &amp;, bool, bool) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afeb980cf4db5fb101eef957cf4b4fb19">compareDoxyfile</a> (TextStream &amp;, Config::CompareMode) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7fab0f71a1fdfd0e2bfa7725244723d">writeXMLDoxyfile</a> (TextStream &amp;) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a007ca48c7279e729107b4cd6d46833df">writeXSDDoxyfile</a> (TextStream &amp;) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfbe392cea3c2abdd7a1afc656bc6b09">substEnvVars</a> () override</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fda">OptionType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7514acb34d8d15c46be2715d63e2680c">orgType</a> () const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a596ef255d6bfee502d9a164538e13742">valueListRef</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b2f5633d6d13cfe0c2873ab683db80e">valueStringRef</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e839595ae2612b8ebec3b0652c6caf6">markAsPresent</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fb91ca94787c2b9767f7010f11571ea">isPresent</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fda">OptionType</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e69691c8ddddedf0d55d2fc83b44f4d">m_orgType</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a398610d9d96559d7987684382453d04c">m_listvalue</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434cc1f3420b4b16a9e329fcaa49e39d">m_valueString</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c07a087cedf8af5fcea86c2ba62bbe9">m_present</a> = false</td>
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

<p>Section marker for obsolete options.</p>

<p>Definition at line 284 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### ConfigObsolete() {#a2af9cb643b1db43c0d51ae973ab870d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigObsolete::ConfigObsolete (const char * name, <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fda">OptionType</a> orgType)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00287">287</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2af9cb643b1db43c0d51ae973ab870d2">287</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2af9cb643b1db43c0d51ae973ab870d2">ConfigObsolete</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>,<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fda">OptionType</a> <a href="#a7514acb34d8d15c46be2715d63e2680c">orgType</a>) : <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption</a>(<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaab60c019594029c214e601ec24988d6ac">O_Obsolete</a>), <a href="#a1e69691c8ddddedf0d55d2fc83b44f4d">m_orgType</a>(<a href="#a7514acb34d8d15c46be2715d63e2680c">orgType</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">    { <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> = <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>; }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption::ConfigOption</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m&#95;name</a>, <a href="#a1e69691c8ddddedf0d55d2fc83b44f4d">m&#95;orgType</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">ConfigOption::name</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaab60c019594029c214e601ec24988d6ac">ConfigOption::O&#95;Obsolete</a> and <a href="#a7514acb34d8d15c46be2715d63e2680c">orgType</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compareDoxyfile() {#afeb980cf4db5fb101eef957cf4b4fb19}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigObsolete::compareDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;, <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a>)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00290">290</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afeb980cf4db5fb101eef957cf4b4fb19">290</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afeb980cf4db5fb101eef957cf4b4fb19">compareDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;,<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a>)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### isPresent() {#a2fb91ca94787c2b9767f7010f11571ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConfigObsolete::isPresent ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00298">298</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2fb91ca94787c2b9767f7010f11571ea">298</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2fb91ca94787c2b9767f7010f11571ea">isPresent</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0c07a087cedf8af5fcea86c2ba62bbe9">m_present</a>; }</span></span></div>

</div>


Reference <a href="#a0c07a087cedf8af5fcea86c2ba62bbe9">m&#95;present</a>.

Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>.
</div>
</div>

### markAsPresent() {#a2e839595ae2612b8ebec3b0652c6caf6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigObsolete::markAsPresent ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00297">297</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e839595ae2612b8ebec3b0652c6caf6">297</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2e839595ae2612b8ebec3b0652c6caf6">markAsPresent</a>() { <a href="#a0c07a087cedf8af5fcea86c2ba62bbe9">m_present</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">; }</span></span></div>

</div>


Reference <a href="#a0c07a087cedf8af5fcea86c2ba62bbe9">m&#95;present</a>.
</div>
</div>

### orgType() {#a7514acb34d8d15c46be2715d63e2680c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptionType ConfigObsolete::orgType ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00294">294</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7514acb34d8d15c46be2715d63e2680c">294</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fda">OptionType</a> <a href="#a7514acb34d8d15c46be2715d63e2680c">orgType</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a1e69691c8ddddedf0d55d2fc83b44f4d">m_orgType</a>; }</span></span></div>

</div>


Reference <a href="#a1e69691c8ddddedf0d55d2fc83b44f4d">m&#95;orgType</a>.

Referenced by <a href="#a2af9cb643b1db43c0d51ae973ab870d2">ConfigObsolete</a> and <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>.
</div>
</div>

### substEnvVars() {#acfbe392cea3c2abdd7a1afc656bc6b09}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigObsolete::substEnvVars ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00293">293</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acfbe392cea3c2abdd7a1afc656bc6b09">293</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acfbe392cea3c2abdd7a1afc656bc6b09">substEnvVars</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### valueListRef() {#a596ef255d6bfee502d9a164538e13742}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringVector * ConfigObsolete::valueListRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00295">295</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a596ef255d6bfee502d9a164538e13742">295</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> *<a href="#a596ef255d6bfee502d9a164538e13742">valueListRef</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#a398610d9d96559d7987684382453d04c">m_listvalue</a>; }</span></span></div>

</div>


Reference <a href="#a398610d9d96559d7987684382453d04c">m&#95;listvalue</a>.
</div>
</div>

### valueStringRef() {#a5b2f5633d6d13cfe0c2873ab683db80e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString * ConfigObsolete::valueStringRef ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00296">296</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5b2f5633d6d13cfe0c2873ab683db80e">296</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *<a href="#a5b2f5633d6d13cfe0c2873ab683db80e">valueStringRef</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#a434cc1f3420b4b16a9e329fcaa49e39d">m_valueString</a>; }</span></span></div>

</div>


Reference <a href="#a434cc1f3420b4b16a9e329fcaa49e39d">m&#95;valueString</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1ab01907c143c95a407993630bdfeba9">updateAttribute</a> and <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>.
</div>
</div>

### writeTemplate() {#a44d7277ce16ab24f69f236ad082eb21a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigObsolete::writeTemplate (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;, bool, bool)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00289">289</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l00619">619</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44d7277ce16ab24f69f236ad082eb21a">619</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a44d7277ce16ab24f69f236ad082eb21a">ConfigObsolete::writeTemplate</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">) {}</span></span></div>

</div>

</div>
</div>

### writeXMLDoxyfile() {#af7fab0f71a1fdfd0e2bfa7725244723d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigObsolete::writeXMLDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00291">291</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7fab0f71a1fdfd0e2bfa7725244723d">291</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af7fab0f71a1fdfd0e2bfa7725244723d">writeXMLDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### writeXSDDoxyfile() {#a007ca48c7279e729107b4cd6d46833df}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigObsolete::writeXSDDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00292">292</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a007ca48c7279e729107b4cd6d46833df">292</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a007ca48c7279e729107b4cd6d46833df">writeXSDDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;listvalue {#a398610d9d96559d7987684382453d04c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringVector ConfigObsolete::m_listvalue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00301">301</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a398610d9d96559d7987684382453d04c">301</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> <a href="#a398610d9d96559d7987684382453d04c">m_listvalue</a>;</span></span></div>

</div>


Referenced by <a href="#a596ef255d6bfee502d9a164538e13742">valueListRef</a>.
</div>
</div>

### m&#95;orgType {#a1e69691c8ddddedf0d55d2fc83b44f4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OptionType ConfigObsolete::m_orgType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00300">300</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1e69691c8ddddedf0d55d2fc83b44f4d">300</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fda">OptionType</a> <a href="#a1e69691c8ddddedf0d55d2fc83b44f4d">m_orgType</a>;</span></span></div>

</div>


Referenced by <a href="#a2af9cb643b1db43c0d51ae973ab870d2">ConfigObsolete</a> and <a href="#a7514acb34d8d15c46be2715d63e2680c">orgType</a>.
</div>
</div>

### m&#95;present {#a0c07a087cedf8af5fcea86c2ba62bbe9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConfigObsolete::m_present = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00303">303</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c07a087cedf8af5fcea86c2ba62bbe9">303</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a0c07a087cedf8af5fcea86c2ba62bbe9">m_present</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a2fb91ca94787c2b9767f7010f11571ea">isPresent</a> and <a href="#a2e839595ae2612b8ebec3b0652c6caf6">markAsPresent</a>.
</div>
</div>

### m&#95;valueString {#a434cc1f3420b4b16a9e329fcaa49e39d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigObsolete::m_valueString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00302">302</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a434cc1f3420b4b16a9e329fcaa49e39d">302</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a434cc1f3420b4b16a9e329fcaa49e39d">m_valueString</a>;</span></span></div>

</div>


Referenced by <a href="#a5b2f5633d6d13cfe0c2873ab683db80e">valueStringRef</a>.
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
