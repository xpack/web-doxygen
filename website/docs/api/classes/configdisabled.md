---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/configdisabled
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConfigDisabled` Class Reference

<p>Section marker for compile time optional options. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ConfigDisabled { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82bb5fed35515825e100630d2d974926">ConfigDisabled</a> (const char *name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac6feff8cfcd5aab9bfa92fd727013031">writeTemplate</a> (TextStream &amp;, bool, bool) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1a1b255c28810c25c88c9edff36e977">compareDoxyfile</a> (TextStream &amp;, Config::CompareMode) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73c0e57a92edfb0652252063507317fd">writeXMLDoxyfile</a> (TextStream &amp;) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a415523e041c5f15dea6305dce4308453">writeXSDDoxyfile</a> (TextStream &amp;) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0c52fd870cc6b92bfbc4806084fd2c0">substEnvVars</a> () override</td>
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

<p>Section marker for compile time optional options.</p>

<p>Definition at line 308 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ConfigDisabled() {#a82bb5fed35515825e100630d2d974926}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigDisabled::ConfigDisabled (const char * name)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 311 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a82bb5fed35515825e100630d2d974926">311</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a82bb5fed35515825e100630d2d974926">ConfigDisabled</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>) : <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption</a>(<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa116df5f47c0442ad31ca0193cf540701">O_Disabled</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">    { <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> = <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>; }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption::ConfigOption</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">ConfigOption::name</a> and <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa116df5f47c0442ad31ca0193cf540701">ConfigOption::O_Disabled</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compareDoxyfile() {#ab1a1b255c28810c25c88c9edff36e977}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigDisabled::compareDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;, <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a>)</td>
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



<p>Definition at line 314 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab1a1b255c28810c25c88c9edff36e977">314</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab1a1b255c28810c25c88c9edff36e977">compareDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;,<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a>)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### substEnvVars() {#ae0c52fd870cc6b92bfbc4806084fd2c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigDisabled::substEnvVars ()</td>
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



<p>Definition at line 317 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae0c52fd870cc6b92bfbc4806084fd2c0">317</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae0c52fd870cc6b92bfbc4806084fd2c0">substEnvVars</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### writeTemplate() {#ac6feff8cfcd5aab9bfa92fd727013031}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigDisabled::writeTemplate (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;, bool, bool)</td>
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



<p>Declaration at line 313 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 621 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac6feff8cfcd5aab9bfa92fd727013031">621</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac6feff8cfcd5aab9bfa92fd727013031">ConfigDisabled::writeTemplate</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">) {}</span></span></div>

</div>

</div>
</div>

### writeXMLDoxyfile() {#a73c0e57a92edfb0652252063507317fd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigDisabled::writeXMLDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;)</td>
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



<p>Definition at line 315 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73c0e57a92edfb0652252063507317fd">315</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a73c0e57a92edfb0652252063507317fd">writeXMLDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;)</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{}</span></span></div>

</div>

</div>
</div>

### writeXSDDoxyfile() {#a415523e041c5f15dea6305dce4308453}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigDisabled::writeXSDDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



<p>Declaration at line 316 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 622 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a415523e041c5f15dea6305dce4308453">622</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a415523e041c5f15dea6305dce4308453">ConfigDisabled::writeXSDDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;xsd:enumeration value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>.</p>

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
