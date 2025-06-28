---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/configenum
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ConfigEnum` Class Reference

<p>Class representing an enum type option. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ConfigEnum { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a96e17cf6e6f6e69461f8a19e3f29b421">ConfigEnum</a> (const char *name, const char *doc, const char *defVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6131fd01c26d5adbe380a9a6832c3ff1">addValue</a> (const char *v)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">const std::vector&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &gt; &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74f5bf4c5a11458bf09fadc23ec36780">values</a> () const</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63af270856c22528eaa62970056d583f">valueRef</a> ()</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa71d0a927aa4726a7cb12afd35c343eb">substEnvVars</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a07b5a073cf6bd30f934635b0c4d6a8d7">writeTemplate</a> (TextStream &amp;t, bool sl, bool) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae34a7c55e7f889b4f676bcd4b763965c">convertStrToVal</a> (Config::CompareMode compareMode) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32c4cf777ea94b43002fd442fa741854">compareDoxyfile</a> (TextStream &amp;t, Config::CompareMode compareMode) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a437c656bd0270e9b0124aa49fdf33ffc">writeXMLDoxyfile</a> (TextStream &amp;t) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2890e2f66b9f584bee6f9afac38e7255">writeXSDDoxyfile</a> (TextStream &amp;t) override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a514e379f03e9a2a965aa22c9c7f10c4b">init</a> () override</td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a353a98c0faa91e2de2b2cce5d28420ec">isDefault</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a71993c1f0ef3d31fd181d3f6b180692c">m_valueRange</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a></td>
</tr>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a26774b3873e0956a434095927c31f237">m_defValue</a></td>
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

<p>Class representing an enum type option.</p>

<p>Definition at line 156 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### ConfigEnum() {#a96e17cf6e6f6e69461f8a19e3f29b421}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigEnum::ConfigEnum (const char * name, const char * doc, const char * defVal)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00159">159</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a96e17cf6e6f6e69461f8a19e3f29b421">159</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a96e17cf6e6f6e69461f8a19e3f29b421">ConfigEnum</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *doc,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *defVal)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption</a>(<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa1ba2565ddffed94550a83a5b537e6a31">O_Enum</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> = <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">m_doc</a> = doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a> = defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a26774b3873e0956a434095927c31f237">m_defValue</a> = defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption::ConfigOption</a>, <a href="#a26774b3873e0956a434095927c31f237">m&#95;defValue</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">ConfigOption::m&#95;doc</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m&#95;name</a>, <a href="#aecc9cd0cfbdb9945459231d28604666e">m&#95;value</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">ConfigOption::name</a> and <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa1ba2565ddffed94550a83a5b537e6a31">ConfigOption::O&#95;Enum</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addValue() {#a6131fd01c26d5adbe380a9a6832c3ff1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigEnum::addValue (const char * v)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00167">167</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6131fd01c26d5adbe380a9a6832c3ff1">167</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6131fd01c26d5adbe380a9a6832c3ff1">addValue</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *v) { <a href="#a71993c1f0ef3d31fd181d3f6b180692c">m_valueRange</a>.emplace_back(v); }</span></span></div>

</div>


Reference <a href="#a71993c1f0ef3d31fd181d3f6b180692c">m&#95;valueRange</a>.
</div>
</div>

### compareDoxyfile() {#a32c4cf777ea94b43002fd442fa741854}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigEnum::compareDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00173">173</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l00463">463</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32c4cf777ea94b43002fd442fa741854">463</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a32c4cf777ea94b43002fd442fa741854">ConfigEnum::compareDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t, <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a353a98c0faa91e2de2b2cce5d28420ec">isDefault</a>()) <a href="#a07b5a073cf6bd30f934635b0c4d6a8d7">writeTemplate</a>(t,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a353a98c0faa91e2de2b2cce5d28420ec">isDefault</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a07b5a073cf6bd30f934635b0c4d6a8d7">writeTemplate</a>.
</div>
</div>

### convertStrToVal() {#ae34a7c55e7f889b4f676bcd4b763965c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigEnum::convertStrToVal (<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00172">172</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l00259">259</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae34a7c55e7f889b4f676bcd4b763965c">259</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae34a7c55e7f889b4f676bcd4b763965c">ConfigEnum::convertStrToVal</a>(<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a> = <a href="#a26774b3873e0956a434095927c31f237">m_defValue</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (compareMode == <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompareMode::CompressedNoEnv</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>(<a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a>)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> val = <a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a>.stripWhiteSpace().lower();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : <a href="#a71993c1f0ef3d31fd181d3f6b180692c">m_valueRange</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.lower() == val)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">       <a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a> = s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"argument '{}' for option {} is not a valid enum value\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightStringLiteral">"Using the default: {}!\n"</span><span class="doxyHighlight">,<a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a>,<a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a>,<a href="#a26774b3873e0956a434095927c31f237">m_defValue</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a> = <a href="#a26774b3873e0956a434095927c31f237">m_defValue</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompressedNoEnv</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config&#95;warn</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>, <a href="#a26774b3873e0956a434095927c31f237">m&#95;defValue</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m&#95;name</a>, <a href="#aecc9cd0cfbdb9945459231d28604666e">m&#95;value</a> and <a href="#a71993c1f0ef3d31fd181d3f6b180692c">m&#95;valueRange</a>.
</div>
</div>

### init() {#a514e379f03e9a2a965aa22c9c7f10c4b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigEnum::init ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00176">176</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a514e379f03e9a2a965aa22c9c7f10c4b">176</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a514e379f03e9a2a965aa22c9c7f10c4b">init</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a> = <a href="#a26774b3873e0956a434095927c31f237">m_defValue</a>; }</span></span></div>

</div>


References <a href="#a26774b3873e0956a434095927c31f237">m&#95;defValue</a> and <a href="#aecc9cd0cfbdb9945459231d28604666e">m&#95;value</a>.
</div>
</div>

### isDefault() {#a353a98c0faa91e2de2b2cce5d28420ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConfigEnum::isDefault ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00177">177</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a353a98c0faa91e2de2b2cce5d28420ec">177</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a353a98c0faa91e2de2b2cce5d28420ec">isDefault</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a> == <a href="#a26774b3873e0956a434095927c31f237">m_defValue</a>; }</span></span></div>

</div>


References <a href="#a26774b3873e0956a434095927c31f237">m&#95;defValue</a> and <a href="#aecc9cd0cfbdb9945459231d28604666e">m&#95;value</a>.

Referenced by <a href="#a32c4cf777ea94b43002fd442fa741854">compareDoxyfile</a> and <a href="#a437c656bd0270e9b0124aa49fdf33ffc">writeXMLDoxyfile</a>.
</div>
</div>

### substEnvVars() {#aa71d0a927aa4726a7cb12afd35c343eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigEnum::substEnvVars ()</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00170">170</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l01526">1526</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa71d0a927aa4726a7cb12afd35c343eb">1526</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa71d0a927aa4726a7cb12afd35c343eb">ConfigEnum::substEnvVars</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>(<a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#aecc9cd0cfbdb9945459231d28604666e">m&#95;value</a> and <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>.
</div>
</div>

### valueRef() {#a63af270856c22528eaa62970056d583f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString * ConfigEnum::valueRef ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00169">169</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a63af270856c22528eaa62970056d583f">169</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *<a href="#a63af270856c22528eaa62970056d583f">valueRef</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a>; }</span></span></div>

</div>


Reference <a href="#aecc9cd0cfbdb9945459231d28604666e">m&#95;value</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a> and <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>.
</div>
</div>

### values() {#a74f5bf4c5a11458bf09fadc23ec36780}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const std::vector&lt; QCString &gt; &amp; ConfigEnum::values ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00168">168</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74f5bf4c5a11458bf09fadc23ec36780">168</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::vector&lt;QCString&gt; &amp;<a href="#a74f5bf4c5a11458bf09fadc23ec36780">values</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a71993c1f0ef3d31fd181d3f6b180692c">m_valueRange</a>; }</span></span></div>

</div>


Reference <a href="#a71993c1f0ef3d31fd181d3f6b180692c">m&#95;valueRange</a>.
</div>
</div>

### writeTemplate() {#a07b5a073cf6bd30f934635b0c4d6a8d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigEnum::writeTemplate (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, bool sl, bool)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00171">171</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l00446">446</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a07b5a073cf6bd30f934635b0c4d6a8d7">446</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a07b5a073cf6bd30f934635b0c4d6a8d7">ConfigEnum::writeTemplate</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sl,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!sl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>(<a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">m_doc</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#aa3ef6fe13a480dad1404aee1bb0f2d11">m_spaces</a>.left(<a href="/web-doxygen/docs/api/classes/configoption/#a641ee9c39bb9c1951b3079073b09d965aa40e4123355dbeb41dc6ca0c68c0d346">MAX_OPTION_LENGTH</a>-<a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a>.length()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">writeStringValue</a>(t,<a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">ConfigOption::m&#95;doc</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m&#95;name</a>, <a href="/web-doxygen/docs/api/classes/configoption/#aa3ef6fe13a480dad1404aee1bb0f2d11">ConfigOption::m&#95;spaces</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">ConfigOption::m&#95;userComment</a>, <a href="#aecc9cd0cfbdb9945459231d28604666e">m&#95;value</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a641ee9c39bb9c1951b3079073b09d965aa40e4123355dbeb41dc6ca0c68c0d346">ConfigOption::MAX&#95;OPTION&#95;LENGTH</a> and <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">ConfigOption::writeStringValue</a>.

Referenced by <a href="#a32c4cf777ea94b43002fd442fa741854">compareDoxyfile</a>.
</div>
</div>

### writeXMLDoxyfile() {#a437c656bd0270e9b0124aa49fdf33ffc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigEnum::writeXMLDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00174">174</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l00468">468</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a437c656bd0270e9b0124aa49fdf33ffc">468</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a437c656bd0270e9b0124aa49fdf33ffc">ConfigEnum::writeXMLDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;option  id='"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" default='"</span><span class="doxyHighlight"> &lt;&lt; (<a href="#a353a98c0faa91e2de2b2cce5d28420ec">isDefault</a>() ? </span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"no"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" type='string'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;value&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">writeStringValue</a>(t,<a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a>,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/value&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/option&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a353a98c0faa91e2de2b2cce5d28420ec">isDefault</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m&#95;name</a>, <a href="#aecc9cd0cfbdb9945459231d28604666e">m&#95;value</a> and <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">ConfigOption::writeStringValue</a>.
</div>
</div>

### writeXSDDoxyfile() {#a2890e2f66b9f584bee6f9afac38e7255}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigEnum::writeXSDDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00175">175</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-l/#l00480">480</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2890e2f66b9f584bee6f9afac38e7255">480</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2890e2f66b9f584bee6f9afac38e7255">ConfigEnum::writeXSDDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;xsd:enumeration value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m&#95;name</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;defValue {#a26774b3873e0956a434095927c31f237}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigEnum::m_defValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00182">182</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a26774b3873e0956a434095927c31f237">182</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a26774b3873e0956a434095927c31f237">m_defValue</a>;</span></span></div>

</div>


Referenced by <a href="#a96e17cf6e6f6e69461f8a19e3f29b421">ConfigEnum</a>, <a href="#ae34a7c55e7f889b4f676bcd4b763965c">convertStrToVal</a>, <a href="#a514e379f03e9a2a965aa22c9c7f10c4b">init</a> and <a href="#a353a98c0faa91e2de2b2cce5d28420ec">isDefault</a>.
</div>
</div>

### m&#95;value {#aecc9cd0cfbdb9945459231d28604666e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigEnum::m_value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00181">181</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aecc9cd0cfbdb9945459231d28604666e">181</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aecc9cd0cfbdb9945459231d28604666e">m_value</a>;</span></span></div>

</div>


Referenced by <a href="#a96e17cf6e6f6e69461f8a19e3f29b421">ConfigEnum</a>, <a href="#ae34a7c55e7f889b4f676bcd4b763965c">convertStrToVal</a>, <a href="#a514e379f03e9a2a965aa22c9c7f10c4b">init</a>, <a href="#a353a98c0faa91e2de2b2cce5d28420ec">isDefault</a>, <a href="#aa71d0a927aa4726a7cb12afd35c343eb">substEnvVars</a>, <a href="#a63af270856c22528eaa62970056d583f">valueRef</a>, <a href="#a07b5a073cf6bd30f934635b0c4d6a8d7">writeTemplate</a> and <a href="#a437c656bd0270e9b0124aa49fdf33ffc">writeXMLDoxyfile</a>.
</div>
</div>

### m&#95;valueRange {#a71993c1f0ef3d31fd181d3f6b180692c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;QCString&gt; ConfigEnum::m_valueRange</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/configimpl-h/#l00180">180</a> of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a71993c1f0ef3d31fd181d3f6b180692c">180</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;QCString&gt; <a href="#a71993c1f0ef3d31fd181d3f6b180692c">m_valueRange</a>;</span></span></div>

</div>


Referenced by <a href="#a6131fd01c26d5adbe380a9a6832c3ff1">addValue</a>, <a href="#ae34a7c55e7f889b4f676bcd4b763965c">convertStrToVal</a> and <a href="#a74f5bf4c5a11458bf09fadc23ec36780">values</a>.
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
