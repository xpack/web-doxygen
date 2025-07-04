---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/configimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ConfigImpl` Class Reference

<p>Singleton for configuration variables. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ConfigImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/configimpl-h">src/configimpl.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af661fbf44e03c43d5ae7c3e30ef33a18">ConfigImpl</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7948af854eb611524c208def210db01">writeTemplate</a> (TextStream &amp;t, bool shortIndex, bool updateOnly)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24a3e5ba9f648d261101861a8dd22f83">compareDoxyfile</a> (TextStream &amp;t, Config::CompareMode compareMode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87163252416c500d2000ad78353400a2">writeXMLDoxyfile</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a933b57616dbd31be7ff204d7b467758a">writeXSDDoxyfile</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a85a09dc81100da9de0dcb148e63c65">setHeader</a> (const char *header)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2a79d804dac59ea90af094a58e52ad1f">convertStrToVal</a> (Config::CompareMode compareMode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0072f7a4546b40a6c445e826bb6e027">emptyValueToDefault</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a56797aabb7ab52c9bd60f32634e41a5b">substituteEnvironmentVars</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a50654e77279eecd43b0dd91cb21420e5">init</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a574ffab8ab91f47f27b9f142cbf1bdc4">parseString</a> (const QCString &amp;fn, const QCString &amp;str, bool upd=FALSE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5d06627b2afb76668e8315613a76b9d3">parse</a> (const QCString &amp;fn, bool upd=FALSE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a016d2f1ef3643494fb1b1e3201e928">appendStartComment</a> (const QCString &amp;u)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a33e3594e6a4848cd7803990e15b452de">appendUserComment</a> (const QCString &amp;u)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7724c925f3325a62e970a76bd69d4078">appendStoreRepl</a> (const QCString &amp;u)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e909c1b38e02a4536e16a33790ddca0">takeStartComment</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a998060bb7c8a5948956b7ccf192d62da">takeUserComment</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a081f10e7e8dd317e08b1596950abdb17">takeStoreRepl</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/configimpl-h/#aa0ece99d9324f0261354e12217c6888f">ConfigOptionList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/configimpl-h/#aa0ece99d9324f0261354e12217c6888f">ConfigOptionList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1fae542e0daf98695b00b6a577804e14">m_obsolete</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/configimpl-h/#aa0ece99d9324f0261354e12217c6888f">ConfigOptionList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad7a7bd125697fa33303c3328ffa78712">m_disabled</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/configimpl-h/#aad500d29f5bc4a52cf7a6b5e4d3c2bf8">ConfigOptionMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a206f323c81afa079e0d1043519343c81">m_dict</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab6cfed000bafe37aec0a101b4eb058a1">m_startComment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9846040bbd2475c0d797d479f5bcdd2">m_userComment</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13c917c3c9fc2c541b686edf371f4cff">m_storeRepl</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af583f0410601ca82409b3ed626516dd2">m_header</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/configimpl">ConfigImpl</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a501e98a30e96c9930ac4b1791b80c09a">instance</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a11be9a99f82898b014f311b5fd9437c1">deleteInstance</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b70bfd9dfb25eeca6a6d9308e67a8c4">config_err_</a> (fmt::string_view fmt, fmt::format_args args)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4933289a8ef6b198c98c5a555fa9013f">config_term_</a> (fmt::string_view fmt, fmt::format_args args)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace74e2339d8c059f2842d934b8da1238">config_warn_</a> (fmt::string_view fmt, fmt::format_args args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a2f513f81f77c64fb9b7fd78245482b42">config_err</a> (fmt::format_string&lt; Args... &gt; fmt, Args &amp;&amp;... args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a> (fmt::format_string&lt; Args... &gt; fmt, Args &amp;&amp;... args)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename ... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aa631fde6f0b7e94b180b07252096ec12">config_warn</a> (fmt::format_string&lt; Args... &gt; fmt, Args &amp;&amp;... args)</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/configimpl">ConfigImpl</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac44172d91ba7a3ee9ccfec8a9c764d37">m_instance</a></td>
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

## Getting configuration values. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb11a49a6e7c717d0242fedf10a36309">getString</a> (const char *fileName, int num, const char *name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee52acd5fe0eebe4410be051ebb4363">getList</a> (const char *fileName, int num, const char *name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5c8800850fd2447c50f320ffb4ee0357">getEnum</a> (const char *fileName, int num, const char *name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adb74a4b0533fcb0452aa355bc0f931b6">getInt</a> (const char *fileName, int num, const char *name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad598f15be45d231f792b68314f7b0468">getBool</a> (const char *fileName, int num, const char *name) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6ee5f5279077a8be14ca6e22d525f104">get</a> (const QCString &amp;name) const</td>
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

## Adding configuration options. Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configinfo">ConfigInfo</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aac7264ca82b6c9265c39ee010056a2f2">addInfo</a> (const char *name, const char *doc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f6352eef16a95f0af17e28d8cc472a8">addString</a> (const char *name, const char *doc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09d7a6327e02376011d6c4a28e8b384c">addEnum</a> (const char *name, const char *doc, const char *defVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configlist">ConfigList</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a52d03dcef339e7d828141b75223c0f08">addList</a> (const char *name, const char *doc)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configint">ConfigInt</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a00e4c51763bed0ccb6e017308c46a8f7">addInt</a> (const char *name, const char *doc, int minVal, int maxVal, int defVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configbool">ConfigBool</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aadfbf98b2e5762c07fa871bc76ebce81">addBool</a> (const char *name, const char *doc, bool defVal)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf9c8d995aff187d5be5489e62c0f738">addObsolete</a> (const char *name, ConfigOption::OptionType orgType)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a376d29ff41f6772b2ccfd055af34d9bb">addDisabled</a> (const char *name)</td>
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

<p>Singleton for configuration variables.</p>


<p>This object holds the global static variables read from a user-supplied configuration file. The static member <a href="#a501e98a30e96c9930ac4b1791b80c09a">instance()</a> can be used to get a pointer to the one and only instance.</p>


<p>Set all variables to their default values by calling Config::instance()-&gt;<a href="#a50654e77279eecd43b0dd91cb21420e5">init()</a></p>


<p>Definition at line 342 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ConfigImpl() {#af661fbf44e03c43d5ae7c3e30ef33a18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigImpl::ConfigImpl ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 348 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1564 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af661fbf44e03c43d5ae7c3e30ef33a18">1564</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#af661fbf44e03c43d5ae7c3e30ef33a18">ConfigImpl::ConfigImpl</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configoptions-h/#abc359bc733e3ae3512278e3014d83eb4">addConfigOptions</a>(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/configoptions-h/#abc359bc733e3ae3512278e3014d83eb4">addConfigOptions</a>.</p>


<p>Referenced by <a href="#a501e98a30e96c9930ac4b1791b80c09a">instance</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### appendStartComment() {#a7a016d2f1ef3643494fb1b1e3201e928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::appendStartComment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; u)</td>
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




<p>Append user start comment</p>


<p>Definition at line 566 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7a016d2f1ef3643494fb1b1e3201e928">566</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7a016d2f1ef3643494fb1b1e3201e928">appendStartComment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab6cfed000bafe37aec0a101b4eb058a1">m_startComment</a> += u;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ab6cfed000bafe37aec0a101b4eb058a1">m_startComment</a>.</p>

</div>
</div>

### appendStoreRepl() {#a7724c925f3325a62e970a76bd69d4078}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::appendStoreRepl (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; u)</td>
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




<p>Append replacement string</p>


<p>Definition at line 578 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7724c925f3325a62e970a76bd69d4078">578</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7724c925f3325a62e970a76bd69d4078">appendStoreRepl</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13c917c3c9fc2c541b686edf371f4cff">m_storeRepl</a> += u;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a13c917c3c9fc2c541b686edf371f4cff">m_storeRepl</a>.</p>

</div>
</div>

### appendUserComment() {#a33e3594e6a4848cd7803990e15b452de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::appendUserComment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; u)</td>
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




<p>Append user comment</p>


<p>Definition at line 572 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a33e3594e6a4848cd7803990e15b452de">572</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a33e3594e6a4848cd7803990e15b452de">appendUserComment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;u)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad9846040bbd2475c0d797d479f5bcdd2">m_userComment</a> += u;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ad9846040bbd2475c0d797d479f5bcdd2">m_userComment</a>.</p>

</div>
</div>

### compareDoxyfile() {#a24a3e5ba9f648d261101861a8dd22f83}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::compareDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Writes a the differences between the current configuration and the template configuration to stream <em>t</em>.</p>


<p>Declaration at line 517 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1334 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24a3e5ba9f648d261101861a8dd22f83">1334</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a24a3e5ba9f648d261101861a8dd22f83">ConfigImpl::compareDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1335</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1336</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"# Difference with default Doxyfile "</span><span class="doxyHighlight"> &lt;&lt; getFullVersion();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1337</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1338</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;option : <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1339</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1340</span><span class="doxyLineContent"><span class="doxyHighlight">    option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">m_userComment</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1341</span><span class="doxyLineContent"><span class="doxyHighlight">    option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#ac0dd72c98355eb3e455b8c4ee3f188dd">compareDoxyfile</a>(t,compareMode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a13c917c3c9fc2c541b686edf371f4cff">m_storeRepl</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="#a081f10e7e8dd317e08b1596950abdb17">takeStoreRepl</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/configoption/#ac0dd72c98355eb3e455b8c4ee3f188dd">ConfigOption::compareDoxyfile</a>, <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>, <a href="#a13c917c3c9fc2c541b686edf371f4cff">m_storeRepl</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a5e54ead18c124c6c6c03ed3b678a7103">ConfigOption::m_userComment</a> and <a href="#a081f10e7e8dd317e08b1596950abdb17">takeStoreRepl</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a6cc61dde8935f986295262513d2feb2d">Config::compareDoxyfile</a>.</p>

</div>
</div>

### convertStrToVal() {#a2a79d804dac59ea90af094a58e52ad1f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::convertStrToVal (<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Converts the string values read from the configuration file to real values for non-string type options (like int, and bools)</p>


<p>Declaration at line 538 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1373 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2a79d804dac59ea90af094a58e52ad1f">1373</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2a79d804dac59ea90af094a58e52ad1f">ConfigImpl::convertStrToVal</a>(<a href="/web-doxygen/docs/api/namespaces/config/#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;option : <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">    option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a0054663d1825e1e0dd0a91a91a2b8810">convertStrToVal</a>(compareMode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/configoption/#a0054663d1825e1e0dd0a91a91a2b8810">ConfigOption::convertStrToVal</a> and <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.</p>

</div>
</div>

### emptyValueToDefault() {#ae0072f7a4546b40a6c445e826bb6e027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::emptyValueToDefault ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Sets default value in case value is empty</p>


<p>Declaration at line 542 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1380 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae0072f7a4546b40a6c445e826bb6e027">1380</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae0072f7a4546b40a6c445e826bb6e027">ConfigImpl::emptyValueToDefault</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;option : <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">    option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#aaf0c9e86e3c98248442e907e12513dd5">emptyValueToDefault</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/configoption/#aaf0c9e86e3c98248442e907e12513dd5">ConfigOption::emptyValueToDefault</a> and <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.</p>

</div>
</div>

### init() {#a50654e77279eecd43b0dd91cb21420e5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::init ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Initialize config variables to their default value</p>


<p>Declaration at line 550 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1541 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a50654e77279eecd43b0dd91cb21420e5">1541</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a50654e77279eecd43b0dd91cb21420e5">ConfigImpl::init</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;option : <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1545</span><span class="doxyLineContent"><span class="doxyHighlight">    option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a1dabfad39230674fc07f5f535392fd35">init</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1546</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1547</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// sanity check if all depends relations are valid</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;option : <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> depName = option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a8a744f63445f4cd0ce86d7f423bc7161">dependsOn</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!depName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> * opt = <a href="#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="#a6ee5f5279077a8be14ca6e22d525f104">get</a>(depName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (opt==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(</span><span class="doxyHighlightStringLiteral">"Config option '{}' has invalid depends relation on unknown option '{}'\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">            option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>(),depName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a8a744f63445f4cd0ce86d7f423bc7161">ConfigOption::dependsOn</a>, <a href="#a6ee5f5279077a8be14ca6e22d525f104">get</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a1dabfad39230674fc07f5f535392fd35">ConfigOption::init</a>, <a href="#a501e98a30e96c9930ac4b1791b80c09a">instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a> and <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">ConfigOption::name</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a91bcb187ed95ec673137e413a4d77203">Config::init</a>.</p>

</div>
</div>

### parse() {#a5d06627b2afb76668e8315613a76b9d3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConfigImpl::parse (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fn, bool upd=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Parse a configuration file with name <em>fn</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>TRUE if successful, FALSE if the file could not be opened or read.</p></dd>
</dl>


<p>Declaration at line 562 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1620 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5d06627b2afb76668e8315613a76b9d3">1620</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a5d06627b2afb76668e8315613a76b9d3">ConfigImpl::parse</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fn,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> update)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1621</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1622</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a> = </span><span class="doxyHighlightStringLiteral">"UTF-8"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1623</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dadd2524ea0de5e1eadcd197a6f5925a83">Debug::Lex_configimpl</a>, __FILE__, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(fn));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1624</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> retval =  <a href="#a574ffab8ab91f47f27b9f142cbf1bdc4">parseString</a>(fn,<a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6acafb836a24013a01bc21ab92381ad7">configFileToString</a>(fn), update);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1625</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> retval;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1626</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6acafb836a24013a01bc21ab92381ad7">configFileToString</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1d031dea12ce5dfc5759802ec854c2d2">g_encoding</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dadd2524ea0de5e1eadcd197a6f5925a83">Debug::Lex_configimpl</a>, <a href="#a574ffab8ab91f47f27b9f142cbf1bdc4">parseString</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a88ed583dc36b1439108163403cc4224f">Config::parse</a>.</p>

</div>
</div>

### parseString() {#a574ffab8ab91f47f27b9f142cbf1bdc4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ConfigImpl::parseString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fn, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, bool upd=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Parse a configuration data in string <em>str</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>TRUE if successful, or FALSE if the string could not be parsed.</p></dd>
</dl>


<p>Declaration at line 556 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1600 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a574ffab8ab91f47f27b9f142cbf1bdc4">1600</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a574ffab8ab91f47f27b9f142cbf1bdc4">ConfigImpl::parseString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fn,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> update)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1601</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1602</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1603</span><span class="doxyLineContent"><span class="doxyHighlight">  configimplYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dadd2524ea0de5e1eadcd197a6f5925a83">Debug::Lex_configimpl</a>)?1:0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1604</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1605</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ac8c998011c1de1f3c38cb48c908af98b">g_config</a> = <a href="#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1606</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4884b04c016cb29c59e337c3849a08fd">g_inputString</a>   = str.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1607</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a5f7e5ad6f4837038547f7d2ea8e031eb">g_inputPosition</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1608</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>    = fn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1609</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>      = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1610</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1611</span><span class="doxyLineContent"><span class="doxyHighlight">  configimplYYrestart( configimplYYin );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1612</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN( Start );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1613</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a73e0a7c37c8a540748c113811329f998">g_configUpdate</a> = update;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1614</span><span class="doxyLineContent"><span class="doxyHighlight">  configimplYYlex();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1615</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a73e0a7c37c8a540748c113811329f998">g_configUpdate</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1616</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4884b04c016cb29c59e337c3849a08fd">g_inputString</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1617</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1618</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a73e0a7c37c8a540748c113811329f998">g_configUpdate</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a53705fefd416a984be4714f1d0ca36a6">g_includeStack</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a5f7e5ad6f4837038547f7d2ea8e031eb">g_inputPosition</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4884b04c016cb29c59e337c3849a08fd">g_inputString</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#afec8ce807dc9bf79f073fa691fafe1f8">g_yyFileName</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ada427227e611310f718c3d614f32d032">g_yyLineNr</a>, <a href="#a501e98a30e96c9930ac4b1791b80c09a">instance</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dadd2524ea0de5e1eadcd197a6f5925a83">Debug::Lex_configimpl</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#a5d06627b2afb76668e8315613a76b9d3">parse</a>.</p>

</div>
</div>

### setHeader() {#a5a85a09dc81100da9de0dcb148e63c65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::setHeader (const char * header)</td>
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



<p>Definition at line 529 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5a85a09dc81100da9de0dcb148e63c65">529</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5a85a09dc81100da9de0dcb148e63c65">setHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *header) { <a href="#af583f0410601ca82409b3ed626516dd2">m_header</a> = header; }</span></span></div>

</div>


<p>Reference <a href="#af583f0410601ca82409b3ed626516dd2">m_header</a>.</p>

</div>
</div>

### substituteEnvironmentVars() {#a56797aabb7ab52c9bd60f32634e41a5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::substituteEnvironmentVars ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Replaces references to environment variable by the actual value of the environment variable.</p>


<p>Declaration at line 547 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1533 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a56797aabb7ab52c9bd60f32634e41a5b">1533</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a56797aabb7ab52c9bd60f32634e41a5b">ConfigImpl::substituteEnvironmentVars</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;option : <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">    option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#aeb6ac539f2fe79e07f2baefd5c4d89c1">substEnvVars</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a> and <a href="/web-doxygen/docs/api/classes/configoption/#aeb6ac539f2fe79e07f2baefd5c4d89c1">ConfigOption::substEnvVars</a>.</p>

</div>
</div>

### takeStartComment() {#a6e909c1b38e02a4536e16a33790ddca0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigImpl::takeStartComment ()</td>
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




<p>Take the user start comment and reset it internally</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>user start comment</p></dd>
</dl>


<p>Definition at line 585 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e909c1b38e02a4536e16a33790ddca0">585</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6e909c1b38e02a4536e16a33790ddca0">takeStartComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result=<a href="#ab6cfed000bafe37aec0a101b4eb058a1">m_startComment</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab6cfed000bafe37aec0a101b4eb058a1">m_startComment</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(result,</span><span class="doxyHighlightStringLiteral">"\r"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ab6cfed000bafe37aec0a101b4eb058a1">m_startComment</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.</p>


<p>Referenced by <a href="#aa7948af854eb611524c208def210db01">writeTemplate</a>.</p>

</div>
</div>

### takeStoreRepl() {#a081f10e7e8dd317e08b1596950abdb17}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigImpl::takeStoreRepl ()</td>
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




<p>Take the replacement string</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>the replacement string</p></dd>
</dl>


<p>Definition at line 603 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a081f10e7e8dd317e08b1596950abdb17">603</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a081f10e7e8dd317e08b1596950abdb17">takeStoreRepl</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result=<a href="#a13c917c3c9fc2c541b686edf371f4cff">m_storeRepl</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a13c917c3c9fc2c541b686edf371f4cff">m_storeRepl</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(result,</span><span class="doxyHighlightStringLiteral">"\r"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a13c917c3c9fc2c541b686edf371f4cff">m_storeRepl</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.</p>


<p>Referenced by <a href="#a24a3e5ba9f648d261101861a8dd22f83">compareDoxyfile</a>.</p>

</div>
</div>

### takeUserComment() {#a998060bb7c8a5948956b7ccf192d62da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigImpl::takeUserComment ()</td>
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




<p>Take the user comment and reset it internally</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>user comment</p></dd>
</dl>


<p>Definition at line 594 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a998060bb7c8a5948956b7ccf192d62da">594</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a998060bb7c8a5948956b7ccf192d62da">takeUserComment</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result=<a href="#ad9846040bbd2475c0d797d479f5bcdd2">m_userComment</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad9846040bbd2475c0d797d479f5bcdd2">m_userComment</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(result,</span><span class="doxyHighlightStringLiteral">"\r"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ad9846040bbd2475c0d797d479f5bcdd2">m_userComment</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.</p>


<p>Referenced by <a href="#aa7948af854eb611524c208def210db01">writeTemplate</a>.</p>

</div>
</div>

### writeTemplate() {#aa7948af854eb611524c208def210db01}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::writeTemplate (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, bool shortIndex, bool updateOnly)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Writes a template configuration to stream <em>t</em>. If <em>shortIndex</em> is <span class="doxyComputerOutput">TRUE</span> the description of each configuration option will be omitted.</p>


<p>Declaration at line 512 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1310 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa7948af854eb611524c208def210db01">1310</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa7948af854eb611524c208def210db01">ConfigImpl::writeTemplate</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sl,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> upd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1311</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1312</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* print first lines of user comment that were at the beginning of the file, might have special meaning for editors */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1313</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ab6cfed000bafe37aec0a101b4eb058a1">m_startComment</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1314</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1315</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="#a6e909c1b38e02a4536e16a33790ddca0">takeStartComment</a>() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1316</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1317</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"# Doxyfile "</span><span class="doxyHighlight"> &lt;&lt; getDoxygenVersion() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1318</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!sl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1319</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1320</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>(<a href="#af583f0410601ca82409b3ed626516dd2">m_header</a>,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1321</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1322</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;option : <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1323</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1324</span><span class="doxyLineContent"><span class="doxyHighlight">    option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a5847d1259b18ad354fcfd5e2e0cd0563">writeTemplate</a>(t,sl,upd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1325</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1326</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">/* print last lines of user comment that were at the end of the file */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1327</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad9846040bbd2475c0d797d479f5bcdd2">m_userComment</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1328</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1329</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1330</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="#a998060bb7c8a5948956b7ccf192d62da">takeUserComment</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1331</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1332</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a48749817b1eba2606c9762ba1bb4d43b">convertToComment</a>, <a href="#af583f0410601ca82409b3ed626516dd2">m_header</a>, <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>, <a href="#ab6cfed000bafe37aec0a101b4eb058a1">m_startComment</a>, <a href="#ad9846040bbd2475c0d797d479f5bcdd2">m_userComment</a>, <a href="#a6e909c1b38e02a4536e16a33790ddca0">takeStartComment</a>, <a href="#a998060bb7c8a5948956b7ccf192d62da">takeUserComment</a> and <a href="/web-doxygen/docs/api/classes/configoption/#a5847d1259b18ad354fcfd5e2e0cd0563">ConfigOption::writeTemplate</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a98dcadaa623b84d8929dc38239f31cb2">Config::writeTemplate</a>.</p>

</div>
</div>

### writeXMLDoxyfile() {#a87163252416c500d2000ad78353400a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::writeXMLDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Writes a the used settings of the current configuration as XML format to stream <em>t</em>.</p>


<p>Declaration at line 522 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1350 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87163252416c500d2000ad78353400a2">1350</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a87163252416c500d2000ad78353400a2">ConfigImpl::writeXMLDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;?xml version='1.0' encoding='UTF-8' standalone='no'?&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;doxyfile xmlns:xsi=\"http://www.w3.org/2001/XMLSchema-instance\" xsi:noNamespaceSchemaLocation=\"doxyfile.xsd\" version=\""</span><span class="doxyHighlight"> &lt;&lt; getDoxygenVersion() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" xml:lang=\""</span><span class="doxyHighlight"> &lt;&lt;  <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trISOLang() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;option : <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">    option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a33dbcfdb94648f726afd2e85462c184a">writeXMLDoxyfile</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/doxyfile&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a> and <a href="/web-doxygen/docs/api/classes/configoption/#a33dbcfdb94648f726afd2e85462c184a">ConfigOption::writeXMLDoxyfile</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a5744a411e57f8a3a18ce6569e843b11e">Config::writeXMLDoxyfile</a>.</p>

</div>
</div>

### writeXSDDoxyfile() {#a933b57616dbd31be7ff204d7b467758a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::writeXSDDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Writes all possible setting ids to an XSD file for validation through the stream <em>t</em>.</p>


<p>Declaration at line 527 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 1361 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a933b57616dbd31be7ff204d7b467758a">1361</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a933b57616dbd31be7ff204d7b467758a">ConfigImpl::writeXSDDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;option : <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">    option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a8849d547bfcd44d86708882d35dac3ad">writeXSDDoxyfile</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;option : <a href="#ad7a7bd125697fa33303c3328ffa78712">m_disabled</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">    option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a8849d547bfcd44d86708882d35dac3ad">writeXSDDoxyfile</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#ad7a7bd125697fa33303c3328ffa78712">m_disabled</a>, <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a> and <a href="/web-doxygen/docs/api/classes/configoption/#a8849d547bfcd44d86708882d35dac3ad">ConfigOption::writeXSDDoxyfile</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a8dfcffe6278ca640b592ae6661b794b5">Config::writeXSDDoxyfile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_dict {#a206f323c81afa079e0d1043519343c81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigOptionMap ConfigImpl::m_dict</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 636 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a206f323c81afa079e0d1043519343c81">636</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-h/#aad500d29f5bc4a52cf7a6b5e4d3c2bf8">ConfigOptionMap</a>  <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aadfbf98b2e5762c07fa871bc76ebce81">addBool</a>, <a href="#a376d29ff41f6772b2ccfd055af34d9bb">addDisabled</a>, <a href="#a09d7a6327e02376011d6c4a28e8b384c">addEnum</a>, <a href="#a00e4c51763bed0ccb6e017308c46a8f7">addInt</a>, <a href="#a52d03dcef339e7d828141b75223c0f08">addList</a>, <a href="#adf9c8d995aff187d5be5489e62c0f738">addObsolete</a>, <a href="#a9f6352eef16a95f0af17e28d8cc472a8">addString</a>, <a href="#a6ee5f5279077a8be14ca6e22d525f104">get</a>, <a href="#ad598f15be45d231f792b68314f7b0468">getBool</a>, <a href="#a5c8800850fd2447c50f320ffb4ee0357">getEnum</a>, <a href="#adb74a4b0533fcb0452aa355bc0f931b6">getInt</a>, <a href="#a8ee52acd5fe0eebe4410be051ebb4363">getList</a> and <a href="#afb11a49a6e7c717d0242fedf10a36309">getString</a>.</p>

</div>
</div>

### m\_disabled {#ad7a7bd125697fa33303c3328ffa78712}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigOptionList ConfigImpl::m_disabled</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 635 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad7a7bd125697fa33303c3328ffa78712">635</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-h/#aa0ece99d9324f0261354e12217c6888f">ConfigOptionList</a> <a href="#ad7a7bd125697fa33303c3328ffa78712">m_disabled</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a376d29ff41f6772b2ccfd055af34d9bb">addDisabled</a> and <a href="#a933b57616dbd31be7ff204d7b467758a">writeXSDDoxyfile</a>.</p>

</div>
</div>

### m\_header {#af583f0410601ca82409b3ed626516dd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigImpl::m_header</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 641 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af583f0410601ca82409b3ed626516dd2">641</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#af583f0410601ca82409b3ed626516dd2">m_header</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a5a85a09dc81100da9de0dcb148e63c65">setHeader</a> and <a href="#aa7948af854eb611524c208def210db01">writeTemplate</a>.</p>

</div>
</div>

### m\_obsolete {#a1fae542e0daf98695b00b6a577804e14}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigOptionList ConfigImpl::m_obsolete</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 634 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1fae542e0daf98695b00b6a577804e14">634</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-h/#aa0ece99d9324f0261354e12217c6888f">ConfigOptionList</a> <a href="#a1fae542e0daf98695b00b6a577804e14">m_obsolete</a>;</span></span></div>

</div>


<p>Referenced by <a href="#adf9c8d995aff187d5be5489e62c0f738">addObsolete</a>.</p>

</div>
</div>

### m\_options {#a0a2a4ac7bd14b923fd7e3434af27eedf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigOptionList ConfigImpl::m_options</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 633 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">633</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-h/#aa0ece99d9324f0261354e12217c6888f">ConfigOptionList</a> <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aadfbf98b2e5762c07fa871bc76ebce81">addBool</a>, <a href="#a09d7a6327e02376011d6c4a28e8b384c">addEnum</a>, <a href="#aac7264ca82b6c9265c39ee010056a2f2">addInfo</a>, <a href="#a00e4c51763bed0ccb6e017308c46a8f7">addInt</a>, <a href="#a52d03dcef339e7d828141b75223c0f08">addList</a>, <a href="#a9f6352eef16a95f0af17e28d8cc472a8">addString</a>, <a href="#a24a3e5ba9f648d261101861a8dd22f83">compareDoxyfile</a>, <a href="#a2a79d804dac59ea90af094a58e52ad1f">convertStrToVal</a>, <a href="#ae0072f7a4546b40a6c445e826bb6e027">emptyValueToDefault</a>, <a href="#a50654e77279eecd43b0dd91cb21420e5">init</a>, <a href="#a56797aabb7ab52c9bd60f32634e41a5b">substituteEnvironmentVars</a>, <a href="#aa7948af854eb611524c208def210db01">writeTemplate</a>, <a href="#a87163252416c500d2000ad78353400a2">writeXMLDoxyfile</a> and <a href="#a933b57616dbd31be7ff204d7b467758a">writeXSDDoxyfile</a>.</p>

</div>
</div>

### m\_startComment {#ab6cfed000bafe37aec0a101b4eb058a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigImpl::m_startComment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 638 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab6cfed000bafe37aec0a101b4eb058a1">638</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab6cfed000bafe37aec0a101b4eb058a1">m_startComment</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a7a016d2f1ef3643494fb1b1e3201e928">appendStartComment</a>, <a href="#a6e909c1b38e02a4536e16a33790ddca0">takeStartComment</a> and <a href="#aa7948af854eb611524c208def210db01">writeTemplate</a>.</p>

</div>
</div>

### m\_storeRepl {#a13c917c3c9fc2c541b686edf371f4cff}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigImpl::m_storeRepl</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 640 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a13c917c3c9fc2c541b686edf371f4cff">640</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a13c917c3c9fc2c541b686edf371f4cff">m_storeRepl</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a7724c925f3325a62e970a76bd69d4078">appendStoreRepl</a>, <a href="#a24a3e5ba9f648d261101861a8dd22f83">compareDoxyfile</a> and <a href="#a081f10e7e8dd317e08b1596950abdb17">takeStoreRepl</a>.</p>

</div>
</div>

### m\_userComment {#ad9846040bbd2475c0d797d479f5bcdd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ConfigImpl::m_userComment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 639 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad9846040bbd2475c0d797d479f5bcdd2">639</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad9846040bbd2475c0d797d479f5bcdd2">m_userComment</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a33e3594e6a4848cd7803990e15b452de">appendUserComment</a>, <a href="#a998060bb7c8a5948956b7ccf192d62da">takeUserComment</a> and <a href="#aa7948af854eb611524c208def210db01">writeTemplate</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### config\_err() {#a2f513f81f77c64fb9b7fd78245482b42}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::config_err (fmt::format_string&lt; Args... &gt; fmt, Args &amp;&amp;... args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 615 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2f513f81f77c64fb9b7fd78245482b42">615</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2f513f81f77c64fb9b7fd78245482b42">config_err</a>(fmt::format_string&lt;Args...&gt; <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, Args&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9b70bfd9dfb25eeca6a6d9308e67a8c4">config_err_</a>(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,fmt::make_format_args(args...));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a9b70bfd9dfb25eeca6a6d9308e67a8c4">config_err_</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/configimpl-l/#aae6d9aa97d4044248e4537678a0a38af">tryPath</a>.</p>

</div>
</div>

### config\_err\_() {#a9b70bfd9dfb25eeca6a6d9308e67a8c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::config_err_ (fmt::string_view fmt, fmt::format_args args)</td>
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



<p>Declaration at line 610 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b70bfd9dfb25eeca6a6d9308e67a8c4">59</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9b70bfd9dfb25eeca6a6d9308e67a8c4">ConfigImpl::config_err_</a>(fmt::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, fmt::format_args args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  fmt::print(stderr,</span><span class="doxyHighlightStringLiteral">"{}{}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/configimpl-l/#adda1f8011db5f4f0ec3d8ece91cfa724">error_str</a>,fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/configimpl-l/#adda1f8011db5f4f0ec3d8ece91cfa724">error_str</a>.</p>


<p>Referenced by <a href="#a2f513f81f77c64fb9b7fd78245482b42">config_err</a>.</p>

</div>
</div>

### config\_term() {#a0b752f150eb5a0ec002ee2a3b245bbd2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::config_term (fmt::format_string&lt; Args... &gt; fmt, Args &amp;&amp;... args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 621 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">621</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(fmt::format_string&lt;Args...&gt; <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, Args&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4933289a8ef6b198c98c5a555fa9013f">config_term_</a>(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,fmt::make_format_args(args...));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a4933289a8ef6b198c98c5a555fa9013f">config_term_</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6acafb836a24013a01bc21ab92381ad7">configFileToString</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a6c24725da6b5b59e4c8867995e84648f">configStringRecode</a>, <a href="#ad598f15be45d231f792b68314f7b0468">getBool</a>, <a href="#a5c8800850fd2447c50f320ffb4ee0357">getEnum</a>, <a href="#adb74a4b0533fcb0452aa355bc0f931b6">getInt</a>, <a href="#a8ee52acd5fe0eebe4410be051ebb4363">getList</a>, <a href="#afb11a49a6e7c717d0242fedf10a36309">getString</a>, <a href="#a50654e77279eecd43b0dd91cb21420e5">init</a> and <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a692163c1902febf3d5dc44644e851f26">readIncludeFile</a>.</p>

</div>
</div>

### config\_term\_() {#a4933289a8ef6b198c98c5a555fa9013f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::config_term_ (fmt::string_view fmt, fmt::format_args args)</td>
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



<p>Declaration at line 611 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4933289a8ef6b198c98c5a555fa9013f">64</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4933289a8ef6b198c98c5a555fa9013f">ConfigImpl::config_term_</a>(fmt::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, fmt::format_args args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  fmt::print(stderr,</span><span class="doxyHighlightStringLiteral">"{}{}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/configimpl-l/#adda1f8011db5f4f0ec3d8ece91cfa724">error_str</a>,fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  fmt::print(stderr,</span><span class="doxyHighlightStringLiteral">"{}\n"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"Exiting..."</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  exit(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/configimpl-l/#adda1f8011db5f4f0ec3d8ece91cfa724">error_str</a>.</p>


<p>Referenced by <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>.</p>

</div>
</div>

### config\_warn() {#aa631fde6f0b7e94b180b07252096ec12}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename ... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::config_warn (fmt::format_string&lt; Args... &gt; fmt, Args &amp;&amp;... args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 627 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa631fde6f0b7e94b180b07252096ec12">627</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa631fde6f0b7e94b180b07252096ec12">config_warn</a>(fmt::format_string&lt;Args...&gt; <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, Args&amp;&amp;... args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ace74e2339d8c059f2842d934b8da1238">config_warn_</a>(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,fmt::make_format_args(args...));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ace74e2339d8c059f2842d934b8da1238">config_warn_</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/configbool/#a78783b044295f537c27c052ce85eeeed">ConfigBool::convertStrToVal</a>, <a href="/web-doxygen/docs/api/classes/configenum/#ae34a7c55e7f889b4f676bcd4b763965c">ConfigEnum::convertStrToVal</a>, <a href="/web-doxygen/docs/api/classes/configint/#a6b0d01345ae582a8ba26a294c6e1b890">ConfigInt::convertStrToVal</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1004c5eacd365bb12bb64c344baeebc6">processList</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a53f751007ffe5b7c105c3821039a970c">processString</a> and <a href="/web-doxygen/docs/api/files/src/language-cpp/#a1035c7c56bdac87a032ba8a18a58eb38">setTranslator</a>.</p>

</div>
</div>

### config\_warn\_() {#ace74e2339d8c059f2842d934b8da1238}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::config_warn_ (fmt::string_view fmt, fmt::format_args args)</td>
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



<p>Declaration at line 612 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ace74e2339d8c059f2842d934b8da1238">71</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ace74e2339d8c059f2842d934b8da1238">ConfigImpl::config_warn_</a>(fmt::string_view <a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, fmt::format_args args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  fmt::print(stderr,</span><span class="doxyHighlightStringLiteral">"{}{}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4b306c7d6514a51d731a5b581ce6c2a4">warning_str</a>,fmt::vformat(<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,args));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a4b306c7d6514a51d731a5b581ce6c2a4">warning_str</a>.</p>


<p>Referenced by <a href="#aa631fde6f0b7e94b180b07252096ec12">config_warn</a>.</p>

</div>
</div>

### deleteInstance() {#a11be9a99f82898b014f311b5fd9437c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ConfigImpl::deleteInstance ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Delete the instance</p>


<p>Definition at line 357 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a11be9a99f82898b014f311b5fd9437c1">357</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a11be9a99f82898b014f311b5fd9437c1">deleteInstance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac44172d91ba7a3ee9ccfec8a9c764d37">m_instance</a>.reset();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ac44172d91ba7a3ee9ccfec8a9c764d37">m_instance</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a7b3346b2e70cc73d231d540df5d67e57">Config::deinit</a>.</p>

</div>
</div>

### instance() {#a501e98a30e96c9930ac4b1791b80c09a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigImpl * ConfigImpl::instance ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Returns the one and only instance of this class</p>


<p>Definition at line 351 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a501e98a30e96c9930ac4b1791b80c09a">351</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#af661fbf44e03c43d5ae7c3e30ef33a18">ConfigImpl</a> *<a href="#a501e98a30e96c9930ac4b1791b80c09a">instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ac44172d91ba7a3ee9ccfec8a9c764d37">m_instance</a>) <a href="#ac44172d91ba7a3ee9ccfec8a9c764d37">m_instance</a> = std::make_unique&lt;ConfigImpl&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac44172d91ba7a3ee9ccfec8a9c764d37">m_instance</a>.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#af661fbf44e03c43d5ae7c3e30ef33a18">ConfigImpl</a> and <a href="#ac44172d91ba7a3ee9ccfec8a9c764d37">m_instance</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/namespaces/config/#a6cc61dde8935f986295262513d2feb2d">Config::compareDoxyfile</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a7b3346b2e70cc73d231d540df5d67e57">Config::deinit</a>, <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a91bcb187ed95ec673137e413a4d77203">Config::init</a>, <a href="#a50654e77279eecd43b0dd91cb21420e5">init</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a88ed583dc36b1439108163403cc4224f">Config::parse</a>, <a href="#a574ffab8ab91f47f27b9f142cbf1bdc4">parseString</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a04731f96560c04835ce340aa776251cb">Config::postProcess</a>, <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a98dcadaa623b84d8929dc38239f31cb2">Config::writeTemplate</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a5744a411e57f8a3a18ce6569e843b11e">Config::writeXMLDoxyfile</a> and <a href="/web-doxygen/docs/api/namespaces/config/#a8dfcffe6278ca640b592ae6661b794b5">Config::writeXSDDoxyfile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### m\_instance {#ac44172d91ba7a3ee9ccfec8a9c764d37}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ConfigImpl &gt; ConfigImpl::m_instance</td>
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



<p>Definition at line 637 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac44172d91ba7a3ee9ccfec8a9c764d37">637</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::unique_ptr&lt;ConfigImpl&gt; <a href="#ac44172d91ba7a3ee9ccfec8a9c764d37">m_instance</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a11be9a99f82898b014f311b5fd9437c1">deleteInstance</a> and <a href="#a501e98a30e96c9930ac4b1791b80c09a">instance</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Getting configuration values.

### get {#a6ee5f5279077a8be14ca6e22d525f104}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigOption * ConfigImpl::get (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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




<p>Returns the <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> corresponding with <em>name</em> or 0 if the option is not supported.</p>


<p>Definition at line 400 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6ee5f5279077a8be14ca6e22d525f104">400</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *<a href="#a6ee5f5279077a8be14ca6e22d525f104">get</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.find(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.end() ? it-&gt;second : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a22c8bd336d14e9baf38a3ffcec3d0476">DocPara::handleDoxyConfig</a>, <a href="#a50654e77279eecd43b0dd91cb21420e5">init</a> and <a href="/web-doxygen/docs/api/namespaces/config/#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>.</p>

</div>
</div>

### getBool {#ad598f15be45d231f792b68314f7b0468}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool &amp; ConfigImpl::getBool (const char * fileName, int num, const char * name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Returns the value of the boolean option with name <em>fileName</em>. The arguments <em>num</em> and <em>name</em> are for debugging purposes only. There is a convenience function <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool()</a> for this.</p>


<p>Declaration at line 395 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 341 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad598f15be45d231f792b68314f7b0468">341</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> &amp;<a href="#ad598f15be45d231f792b68314f7b0468">ConfigImpl::getBool</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> num,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.find(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(</span><span class="doxyHighlightStringLiteral">"{}&lt;{}&gt;: Internal error: Requested unknown option {}!\n"</span><span class="doxyHighlight">,fileName,num,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it-&gt;second-&gt;kind()!=<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O_Bool</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(</span><span class="doxyHighlightStringLiteral">"{}&lt;{}&gt;: Internal error: Requested option {} not of boolean type!\n"</span><span class="doxyHighlight">,fileName,num,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *(</span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configbool">ConfigBool</a> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(it-&gt;second))-&gt;valueRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>, <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O_Bool</a>.</p>

</div>
</div>

### getEnum {#a5c8800850fd2447c50f320ffb4ee0357}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; ConfigImpl::getEnum (const char * fileName, int num, const char * name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Returns the value of the enum option with name <em>fileName</em>. The arguments <em>num</em> and <em>name</em> are for debugging purposes only. There is a convenience function <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum()</a> for this.</p>


<p>Declaration at line 383 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 313 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5c8800850fd2447c50f320ffb4ee0357">313</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#a5c8800850fd2447c50f320ffb4ee0357">ConfigImpl::getEnum</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> num,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.find(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(</span><span class="doxyHighlightStringLiteral">"{}&lt;{}&gt;: Internal error: Requested unknown option {}!\n"</span><span class="doxyHighlight">,fileName,num,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it-&gt;second-&gt;kind()!=<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa1ba2565ddffed94550a83a5b537e6a31">ConfigOption::O_Enum</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(</span><span class="doxyHighlightStringLiteral">"{}&lt;{}&gt;: Internal error: Requested option {} not of enum type!\n"</span><span class="doxyHighlight">,fileName,num,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *(</span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(it-&gt;second))-&gt;valueRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>, <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa1ba2565ddffed94550a83a5b537e6a31">ConfigOption::O_Enum</a>.</p>

</div>
</div>

### getInt {#adb74a4b0533fcb0452aa355bc0f931b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int &amp; ConfigImpl::getInt (const char * fileName, int num, const char * name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Returns the value of the integer option with name <em>fileName</em>. The arguments <em>num</em> and <em>name</em> are for debugging purposes only. There is a convenience function <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt()</a> for this.</p>


<p>Declaration at line 389 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 327 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adb74a4b0533fcb0452aa355bc0f931b6">327</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;<a href="#adb74a4b0533fcb0452aa355bc0f931b6">ConfigImpl::getInt</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> num,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.find(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(</span><span class="doxyHighlightStringLiteral">"{}&lt;{}&gt;: Internal error: Requested unknown option {}!\n"</span><span class="doxyHighlight">,fileName,num,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it-&gt;second-&gt;kind()!=<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaac029c8062b88308de12914e88e12dcd8">ConfigOption::O_Int</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(</span><span class="doxyHighlightStringLiteral">"{}&lt;{}&gt;: Internal error: Requested option {} not of integer type!\n"</span><span class="doxyHighlight">,fileName,num,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *(</span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configint">ConfigInt</a> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(it-&gt;second))-&gt;valueRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>, <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaac029c8062b88308de12914e88e12dcd8">ConfigOption::O_Int</a>.</p>

</div>
</div>

### getList {#a8ee52acd5fe0eebe4410be051ebb4363}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StringVector &amp; ConfigImpl::getList (const char * fileName, int num, const char * name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Returns the value of the list option with name <em>fileName</em>. The arguments <em>num</em> and <em>name</em> are for debugging purposes only. There is a convenience function <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList()</a> for this.</p>


<p>Declaration at line 377 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 299 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ee52acd5fe0eebe4410be051ebb4363">299</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;<a href="#a8ee52acd5fe0eebe4410be051ebb4363">ConfigImpl::getList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> num,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.find(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(</span><span class="doxyHighlightStringLiteral">"{}&lt;{}&gt;: Internal error: Requested unknown option {}!\n"</span><span class="doxyHighlight">,fileName,num,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it-&gt;second-&gt;kind()!=<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa18c0785bb1948fb57402ee80324ef1a7">ConfigOption::O_List</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(</span><span class="doxyHighlightStringLiteral">"{}&lt;{}&gt;: Internal error: Requested option {} not of list type!\n"</span><span class="doxyHighlight">,fileName,num,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *(</span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configlist">ConfigList</a> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(it-&gt;second))-&gt;valueRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>, <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa18c0785bb1948fb57402ee80324ef1a7">ConfigOption::O_List</a>.</p>

</div>
</div>

### getString {#afb11a49a6e7c717d0242fedf10a36309}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString &amp; ConfigImpl::getString (const char * fileName, int num, const char * name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Returns the value of the string option with name <em>fileName</em>. The arguments <em>num</em> and <em>name</em> are for debugging purposes only. There is a convenience function <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString()</a> for this.</p>


<p>Declaration at line 371 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>, definition at line 285 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afb11a49a6e7c717d0242fedf10a36309">285</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="#afb11a49a6e7c717d0242fedf10a36309">ConfigImpl::getString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> num,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.find(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(</span><span class="doxyHighlightStringLiteral">"{}&lt;{}&gt;: Internal error: Requested unknown option {}!\n"</span><span class="doxyHighlight">,fileName,num,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it-&gt;second-&gt;kind()!=<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa3aa84b958a247d79889f28f4244a7d7f">ConfigOption::O_String</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>(</span><span class="doxyHighlightStringLiteral">"{}&lt;{}&gt;: Internal error: Requested option {} not of string type!\n"</span><span class="doxyHighlight">,fileName,num,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *(</span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a> *</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(it-&gt;second))-&gt;valueRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a0b752f150eb5a0ec002ee2a3b245bbd2">config_term</a>, <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa3aa84b958a247d79889f28f4244a7d7f">ConfigOption::O_String</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Adding configuration options.

### addBool {#aadfbf98b2e5762c07fa871bc76ebce81}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigBool * ConfigImpl::addBool (const char * name, const char * doc, bool defVal)</td>
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




<p>Adds a new boolean option with <em>name</em> and documentation <em>doc</em>. The boolean has a default value of <em>defVal</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An object representing the option.</p></dd>
</dl>


<p>Definition at line 479 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aadfbf98b2e5762c07fa871bc76ebce81">479</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configbool">ConfigBool</a>   *<a href="#aadfbf98b2e5762c07fa871bc76ebce81">addBool</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *doc,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> defVal)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configbool">ConfigBool</a> *result = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configbool">ConfigBool</a>(name,doc,defVal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.push_back(std::unique_ptr&lt;ConfigOption&gt;(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.emplace(name,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.</p>

</div>
</div>

### addDisabled {#a376d29ff41f6772b2ccfd055af34d9bb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigOption * ConfigImpl::addDisabled (const char * name)</td>
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




<p>Adds an option that has been disabled at compile time.</p>


<p>Definition at line 499 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a376d29ff41f6772b2ccfd055af34d9bb">499</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *<a href="#a376d29ff41f6772b2ccfd055af34d9bb">addDisabled</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configdisabled">ConfigDisabled</a> *result = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configdisabled">ConfigDisabled</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad7a7bd125697fa33303c3328ffa78712">m_disabled</a>.push_back(std::unique_ptr&lt;ConfigOption&gt;(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.emplace(name,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="#ad7a7bd125697fa33303c3328ffa78712">m_disabled</a>.</p>

</div>
</div>

### addEnum {#a09d7a6327e02376011d6c4a28e8b384c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigEnum * ConfigImpl::addEnum (const char * name, const char * doc, const char * defVal)</td>
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




<p>Adds a new enumeration option with <em>name</em> and documentation <em>doc</em> and initial value <em>defVal</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An object representing the option.</p></dd>
</dl>


<p>Definition at line 438 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a09d7a6327e02376011d6c4a28e8b384c">438</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a>   *<a href="#a09d7a6327e02376011d6c4a28e8b384c">addEnum</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *doc,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *defVal)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a> *result = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a>(name,doc,defVal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.push_back(std::unique_ptr&lt;ConfigOption&gt;(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.emplace(name,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.</p>

</div>
</div>

### addInfo {#aac7264ca82b6c9265c39ee010056a2f2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigInfo * ConfigImpl::addInfo (const char * name, const char * doc)</td>
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




<p>Starts a new configuration section with <em>name</em> and description <em>doc</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An object representing the option.</p></dd>
</dl>


<p>Definition at line 415 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aac7264ca82b6c9265c39ee010056a2f2">415</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configinfo">ConfigInfo</a>   *<a href="#aac7264ca82b6c9265c39ee010056a2f2">addInfo</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *doc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configinfo">ConfigInfo</a> *result = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configinfo">ConfigInfo</a>(name,doc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.push_back(std::unique_ptr&lt;ConfigOption&gt;(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.</p>

</div>
</div>

### addInt {#a00e4c51763bed0ccb6e017308c46a8f7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigInt * ConfigImpl::addInt (const char * name, const char * doc, int minVal, int maxVal, int defVal)</td>
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




<p>Adds a new integer option with <em>name</em> and documentation <em>doc</em>. The integer has a range between <em>minVal</em> and <em>maxVal</em> and a default value of <em>defVal</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An object representing the option.</p></dd>
</dl>


<p>Definition at line 465 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a00e4c51763bed0ccb6e017308c46a8f7">465</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configint">ConfigInt</a>    *<a href="#a00e4c51763bed0ccb6e017308c46a8f7">addInt</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *doc,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> minVal,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> maxVal,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> defVal)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configint">ConfigInt</a> *result = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configint">ConfigInt</a>(name,doc,minVal,maxVal,defVal);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.push_back(std::unique_ptr&lt;ConfigOption&gt;(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.emplace(name,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.</p>

</div>
</div>

### addList {#a52d03dcef339e7d828141b75223c0f08}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigList * ConfigImpl::addList (const char * name, const char * doc)</td>
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




<p>Adds a new string option with <em>name</em> and documentation <em>doc</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An object representing the option.</p></dd>
</dl>


<p>Definition at line 451 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a52d03dcef339e7d828141b75223c0f08">451</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configlist">ConfigList</a>   *<a href="#a52d03dcef339e7d828141b75223c0f08">addList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *doc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configlist">ConfigList</a> *result = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configlist">ConfigList</a>(name,doc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.push_back(std::unique_ptr&lt;ConfigOption&gt;(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.emplace(name,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.</p>

</div>
</div>

### addObsolete {#adf9c8d995aff187d5be5489e62c0f738}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigOption * ConfigImpl::addObsolete (const char * name, <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fda">ConfigOption::OptionType</a> orgType)</td>
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




<p>Adds an option that has become obsolete.</p>


<p>Definition at line 490 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adf9c8d995aff187d5be5489e62c0f738">490</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *<a href="#adf9c8d995aff187d5be5489e62c0f738">addObsolete</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name,<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fda">ConfigOption::OptionType</a> orgType)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a> *result = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>(name,orgType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1fae542e0daf98695b00b6a577804e14">m_obsolete</a>.push_back(std::unique_ptr&lt;ConfigOption&gt;(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.emplace(name,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="#a1fae542e0daf98695b00b6a577804e14">m_obsolete</a>.</p>

</div>
</div>

### addString {#a9f6352eef16a95f0af17e28d8cc472a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConfigString * ConfigImpl::addString (const char * name, const char * doc)</td>
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




<p>Adds a new string option with <em>name</em> and documentation <em>doc</em>.</p>


<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An object representing the option.</p></dd>
</dl>


<p>Definition at line 425 of file <a href="/web-doxygen/docs/api/files/src/configimpl-h">configimpl.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f6352eef16a95f0af17e28d8cc472a8">425</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a> *<a href="#a9f6352eef16a95f0af17e28d8cc472a8">addString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *doc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a> *result = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a>(name,doc);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.push_back(std::unique_ptr&lt;ConfigOption&gt;(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a>.emplace(name,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a206f323c81afa079e0d1043519343c81">m_dict</a> and <a href="#a0a2a4ac7bd14b923fd7e3434af27eedf">m_options</a>.</p>

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
