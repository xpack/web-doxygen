---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/configbool
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConfigBool` Class Reference

<p>Class representing a Boolean type option. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ConfigBool { ... }
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0250b41f09141944729a556c4d5f8146">ConfigBool</a> (const char *name, const char *doc, bool defVal)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a68ac670d16fb28e4dd4df321457c7b29">valueStringRef</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46d53a46ed6d14a02838a901a9deed3b">valueRef</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78783b044295f537c27c052ce85eeeed">convertStrToVal</a> (Config::CompareMode compareMode) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5682d107b4ebf92ae60ea0ba5ece3c5c">substEnvVars</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfabddfc8b65f1850cb7b1bdfcfb6ae1">setValueString</a> (const QCString &amp;v)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a05d11e6e431f77eca9a55cc8d161ff9d">writeTemplate</a> (TextStream &amp;t, bool sl, bool upd) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6d566ed793c0f4f3e3832f46954dbc86">compareDoxyfile</a> (TextStream &amp;t, Config::CompareMode compareMode) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a2a4df7089b3688fe9ee14669600bd8">writeXMLDoxyfile</a> (TextStream &amp;t) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4edb4fd3c7037c825e935765acb76273">writeXSDDoxyfile</a> (TextStream &amp;t) override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0563964fe558e9f907368a5a374b688e">init</a> () override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a12389bdfc8de565bf4bdbff0c94832">isDefault</a> () override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac71d10f13c0188d844d5cdac50239b64">m_defValue</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf2434135022696b299873aad44a2b86">m_valueString</a></td>
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

<p>Class representing a Boolean type option.</p>

<p>Definition at line 254 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ConfigBool() {#a0250b41f09141944729a556c4d5f8146}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigBool::ConfigBool (const char * name, const char * doc, bool defVal)</td>
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



<p>Definition at line 257 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0250b41f09141944729a556c4d5f8146">257</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0250b41f09141944729a556c4d5f8146">ConfigBool</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *doc,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> defVal)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption</a>(<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">O_Bool</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> = <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">m_doc</a> = doc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a> = defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac71d10f13c0188d844d5cdac50239b64">m_defValue</a> = defVal;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/configoption/#a3ce6753bba05ab1ee7e5eaaec6d8f1ac">ConfigOption::ConfigOption</a>, <a href="#ac71d10f13c0188d844d5cdac50239b64">m_defValue</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">ConfigOption::m_doc</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>, <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">ConfigOption::name</a> and <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O_Bool</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### compareDoxyfile() {#a6d566ed793c0f4f3e3832f46954dbc86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigBool::compareDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</td>
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



<p>Declaration at line 271 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 597 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6d566ed793c0f4f3e3832f46954dbc86">597</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6d566ed793c0f4f3e3832f46954dbc86">ConfigBool::compareDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a2a12389bdfc8de565bf4bdbff0c94832">isDefault</a>() || ((compareMode == <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompareMode::CompressedNoEnv</a>) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>(<a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>))) <a href="#a05d11e6e431f77eca9a55cc8d161ff9d">writeTemplate</a>(t,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompressedNoEnv</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>, <a href="#a2a12389bdfc8de565bf4bdbff0c94832">isDefault</a>, <a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="#a05d11e6e431f77eca9a55cc8d161ff9d">writeTemplate</a>.</p>

</div>
</div>

### convertStrToVal() {#a78783b044295f537c27c052ce85eeeed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigBool::convertStrToVal (<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</td>
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



<p>Declaration at line 267 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 237 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a78783b044295f537c27c052ce85eeeed">237</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a78783b044295f537c27c052ce85eeeed">ConfigBool::convertStrToVal</a>(<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>.stripWhiteSpace().isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (compareMode == <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompareMode::CompressedNoEnv</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>(<a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isValid=</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> b = <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a>(<a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>,isValid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isValid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a>=b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>(</span><span class="doxyHighlightStringLiteral">"argument '{}' for option {} is not a valid boolean value\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"Using the default: {}!\n"</span><span class="doxyHighlight">,<a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>,<a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a>,<a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a>?</span><span class="doxyHighlightStringLiteral">"YES"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"NO"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">Config::CompressedNoEnv</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#aa631fde6f0b7e94b180b07252096ec12">ConfigImpl::config_warn</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4c20e33d84d7477620edc8cdf3e3333b">containsEnvVar</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>, <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a> and <a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>.</p>

</div>
</div>

### init() {#a0563964fe558e9f907368a5a374b688e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigBool::init ()</td>
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



<p>Definition at line 274 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0563964fe558e9f907368a5a374b688e">274</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0563964fe558e9f907368a5a374b688e">init</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a> = <a href="#ac71d10f13c0188d844d5cdac50239b64">m_defValue</a>; }</span></span></div>

</div>


<p>References <a href="#ac71d10f13c0188d844d5cdac50239b64">m_defValue</a> and <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a>.</p>

</div>
</div>

### isDefault() {#a2a12389bdfc8de565bf4bdbff0c94832}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConfigBool::isDefault ()</td>
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



<p>Definition at line 275 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a12389bdfc8de565bf4bdbff0c94832">275</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a2a12389bdfc8de565bf4bdbff0c94832">isDefault</a>()</span><span class="doxyHighlightKeyword"> override </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a> == <a href="#ac71d10f13c0188d844d5cdac50239b64">m_defValue</a>; }</span></span></div>

</div>


<p>References <a href="#ac71d10f13c0188d844d5cdac50239b64">m_defValue</a> and <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a>.</p>


<p>Referenced by <a href="#a6d566ed793c0f4f3e3832f46954dbc86">compareDoxyfile</a> and <a href="#a3a2a4df7089b3688fe9ee14669600bd8">writeXMLDoxyfile</a>.</p>

</div>
</div>

### setValueString() {#acfabddfc8b65f1850cb7b1bdfcfb6ae1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigBool::setValueString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; v)</td>
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



<p>Definition at line 269 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acfabddfc8b65f1850cb7b1bdfcfb6ae1">269</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acfabddfc8b65f1850cb7b1bdfcfb6ae1">setValueString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;v) { <a href="#acf2434135022696b299873aad44a2b86">m_valueString</a> = v; }</span></span></div>

</div>


<p>Reference <a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>.</p>

</div>
</div>

### substEnvVars() {#a5682d107b4ebf92ae60ea0ba5ece3c5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigBool::substEnvVars ()</td>
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



<p>Declaration at line 268 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1516 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5682d107b4ebf92ae60ea0ba5ece3c5c">1516</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5682d107b4ebf92ae60ea0ba5ece3c5c">ConfigBool::substEnvVars</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>(<a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#acf2434135022696b299873aad44a2b86">m_valueString</a> and <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afcf1a493801a3f065ef9ca18e7c4f6c6">substEnvVarsInString</a>.</p>

</div>
</div>

### valueRef() {#a46d53a46ed6d14a02838a901a9deed3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool * ConfigBool::valueRef ()</td>
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



<p>Definition at line 266 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a46d53a46ed6d14a02838a901a9deed3b">266</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> *<a href="#a46d53a46ed6d14a02838a901a9deed3b">valueRef</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a>; }</span></span></div>

</div>


<p>Reference <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a>.</p>

</div>
</div>

### valueStringRef() {#a68ac670d16fb28e4dd4df321457c7b29}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString * ConfigBool::valueStringRef ()</td>
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



<p>Definition at line 265 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a68ac670d16fb28e4dd4df321457c7b29">265</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *<a href="#a68ac670d16fb28e4dd4df321457c7b29">valueStringRef</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> &amp;<a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>; }</span></span></div>

</div>


<p>Reference <a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a> and <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>.</p>

</div>
</div>

### writeTemplate() {#a05d11e6e431f77eca9a55cc8d161ff9d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigBool::writeTemplate (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, bool sl, bool upd)</td>
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



<p>Declaration at line 270 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 572 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a05d11e6e431f77eca9a55cc8d161ff9d">572</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a05d11e6e431f77eca9a55cc8d161ff9d">ConfigBool::writeTemplate</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sl,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> upd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!sl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>(<a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">m_doc</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> spaces = <a href="/web-doxygen/docs/api/classes/configoption/#aa3ef6fe13a480dad1404aee1bb0f2d11">m_spaces</a>.left(<a href="/web-doxygen/docs/api/classes/configoption/#a641ee9c39bb9c1951b3079073b09d965aa40e4123355dbeb41dc6ca0c68c0d346">MAX_OPTION_LENGTH</a>-<a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a>.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; spaces &lt;&lt; </span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (upd &amp;&amp; !<a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">writeStringValue</a>(t,<a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configoption/#af1841ab62c57c5ec4e594950f25115cd">writeBoolValue</a>(t,<a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a28fdea8e9fdf86e73faae697454c17ab">ConfigOption::m_doc</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>, <a href="/web-doxygen/docs/api/classes/configoption/#aa3ef6fe13a480dad1404aee1bb0f2d11">ConfigOption::m_spaces</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">ConfigOption::m_userComment</a>, <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a>, <a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a641ee9c39bb9c1951b3079073b09d965aa40e4123355dbeb41dc6ca0c68c0d346">ConfigOption::MAX_OPTION_LENGTH</a>, <a href="/web-doxygen/docs/api/classes/configoption/#af1841ab62c57c5ec4e594950f25115cd">ConfigOption::writeBoolValue</a> and <a href="/web-doxygen/docs/api/classes/configoption/#a369bfd358cef4c5e7c6bf10505ec70db">ConfigOption::writeStringValue</a>.</p>


<p>Referenced by <a href="#a6d566ed793c0f4f3e3832f46954dbc86">compareDoxyfile</a>.</p>

</div>
</div>

### writeXMLDoxyfile() {#a3a2a4df7089b3688fe9ee14669600bd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigBool::writeXMLDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



<p>Declaration at line 272 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 602 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a2a4df7089b3688fe9ee14669600bd8">602</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3a2a4df7089b3688fe9ee14669600bd8">ConfigBool::writeXMLDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  &lt;option  id='"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" default='"</span><span class="doxyHighlight"> &lt;&lt; (<a href="#a2a12389bdfc8de565bf4bdbff0c94832">isDefault</a>() ? </span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"no"</span><span class="doxyHighlight">) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" type='bool'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;value&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption/#af1841ab62c57c5ec4e594950f25115cd">writeBoolValue</a>(t,<a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a>,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/value&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/option&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a2a12389bdfc8de565bf4bdbff0c94832">isDefault</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>, <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a> and <a href="/web-doxygen/docs/api/classes/configoption/#af1841ab62c57c5ec4e594950f25115cd">ConfigOption::writeBoolValue</a>.</p>

</div>
</div>

### writeXSDDoxyfile() {#a4edb4fd3c7037c825e935765acb76273}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigBool::writeXSDDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



<p>Declaration at line 273 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 614 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4edb4fd3c7037c825e935765acb76273">614</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4edb4fd3c7037c825e935765acb76273">ConfigBool::writeXSDDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"      &lt;xsd:enumeration value=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">m_name</a> &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/classes/configoption/#a4f081d447f2443212d0d032da63b20d7">ConfigOption::m_name</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_defValue {#ac71d10f13c0188d844d5cdac50239b64}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConfigBool::m_defValue</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 278 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac71d10f13c0188d844d5cdac50239b64">278</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac71d10f13c0188d844d5cdac50239b64">m_defValue</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a0250b41f09141944729a556c4d5f8146">ConfigBool</a>, <a href="#a0563964fe558e9f907368a5a374b688e">init</a> and <a href="#a2a12389bdfc8de565bf4bdbff0c94832">isDefault</a>.</p>

</div>
</div>

### m\_value {#aefe865c4fd964415a318e9c2705520bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConfigBool::m_value</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 277 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aefe865c4fd964415a318e9c2705520bd">277</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aefe865c4fd964415a318e9c2705520bd">m_value</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a0250b41f09141944729a556c4d5f8146">ConfigBool</a>, <a href="#a78783b044295f537c27c052ce85eeeed">convertStrToVal</a>, <a href="#a0563964fe558e9f907368a5a374b688e">init</a>, <a href="#a2a12389bdfc8de565bf4bdbff0c94832">isDefault</a>, <a href="#a46d53a46ed6d14a02838a901a9deed3b">valueRef</a>, <a href="#a05d11e6e431f77eca9a55cc8d161ff9d">writeTemplate</a> and <a href="#a3a2a4df7089b3688fe9ee14669600bd8">writeXMLDoxyfile</a>.</p>

</div>
</div>

### m\_valueString {#acf2434135022696b299873aad44a2b86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigBool::m_valueString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 279 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acf2434135022696b299873aad44a2b86">279</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#acf2434135022696b299873aad44a2b86">m_valueString</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a6d566ed793c0f4f3e3832f46954dbc86">compareDoxyfile</a>, <a href="#a78783b044295f537c27c052ce85eeeed">convertStrToVal</a>, <a href="#acfabddfc8b65f1850cb7b1bdfcfb6ae1">setValueString</a>, <a href="#a5682d107b4ebf92ae60ea0ba5ece3c5c">substEnvVars</a>, <a href="#a68ac670d16fb28e4dd4df321457c7b29">valueStringRef</a> and <a href="#a05d11e6e431f77eca9a55cc8d161ff9d">writeTemplate</a>.</p>

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

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
