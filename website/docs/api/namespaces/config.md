---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/namespaces/config
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - namespace
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Config` Namespace Reference

Public function to deal with the configuration file. <a href="#details">More...</a>

## Definition

<div class="doxyDefinition">
namespace Config { ... }
</div>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">CompareMode { <a href="#a098ed7e63f2ba437f0e540316e6cd940">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91bcb187ed95ec673137e413a4d77203">init</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98dcadaa623b84d8929dc38239f31cb2">writeTemplate</a> (TextStream &amp;t, bool shortList, bool updateOnly=FALSE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc61dde8935f986295262513d2feb2d">compareDoxyfile</a> (TextStream &amp;t, CompareMode compareMode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5744a411e57f8a3a18ce6569e843b11e">writeXMLDoxyfile</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8dfcffe6278ca640b592ae6661b794b5">writeXSDDoxyfile</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88ed583dc36b1439108163403cc4224f">parse</a> (const QCString &amp;fileName, bool update=FALSE, CompareMode compareMode=CompareMode::Full)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04731f96560c04835ce340aa776251cb">postProcess</a> (bool clearHeaderAndFooter, CompareMode compareMode=CompareMode::Full)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a43f9512cdb148a0f68a30519debac43f">checkAndCorrect</a> (bool quiet, const bool check)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad27e22c157d0c2d33414923d0a41c200">updateObsolete</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7b3346b2e70cc73d231d540df5d67e57">deinit</a> ()</td>
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

Public function to deal with the configuration file.

<div class="doxySectionDef">

## Enumerations

### CompareMode {#a098ed7e63f2ba437f0e540316e6cd940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class Config::CompareMode </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
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
<td class="doxyEnumItemName">Full<a id="a098ed7e63f2ba437f0e540316e6cd940abbd47109890259c0127154db1af26c75"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Compressed<a id="a098ed7e63f2ba437f0e540316e6cd940a4d602abc0c0f2f7c1a5156d964517e4e"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CompressedNoEnv<a id="a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

Definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a098ed7e63f2ba437f0e540316e6cd940">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#a098ed7e63f2ba437f0e540316e6cd940">CompareMode</a> { <a href="#a098ed7e63f2ba437f0e540316e6cd940abbd47109890259c0127154db1af26c75">Full</a>, <a href="#a098ed7e63f2ba437f0e540316e6cd940a4d602abc0c0f2f7c1a5156d964517e4e">Compressed</a>, <a href="#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">CompressedNoEnv</a> };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### checkAndCorrect() {#a43f9512cdb148a0f68a30519debac43f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Config::checkAndCorrect (bool quiet, const bool check)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Check the validity of the parsed options and correct or warn the user where needed.

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">quiet</td>
<td class="doxyParamItemDescription">setting for the QUIET option (can have been overruled by means of a command line option)</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">check</td>
<td class="doxyParamItemDescription">check HTML / LaTeX header file etc. on existence (and terminate when not present)</td>
</tr>
</table>
</dd>
</dl>

Declaration at line 98 of file <a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>, definition at line 1753 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a43f9512cdb148a0f68a30519debac43f">1753</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a43f9512cdb148a0f68a30519debac43f">Config::checkAndCorrect</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> quiet, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> check)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1754</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1755</span><span class="doxyLineContent"><span class="doxyHighlight">  ConfigValues::instance().init();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1756</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1757</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/config-h/#a252335f9ceadbd28f4394ec14a7f2777">Config_updateBool</a>(QUIET,quiet || <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(QUIET));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1758</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1759</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check WARN_FORMAT</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1760</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> warnFormat = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(WARN_FORMAT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1761</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (warnFormat.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"$file"</span><span class="doxyHighlight">)==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1762</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1763</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"warning format does not contain a $file tag!\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1764</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1765</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (warnFormat.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"$line"</span><span class="doxyHighlight">)==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1766</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1767</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"warning format does not contain a $line tag!\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1768</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1769</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (warnFormat.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"$text"</span><span class="doxyHighlight">)==-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1770</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1771</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"warning format does not contain a $text tag!\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1772</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1773</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1774</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1775</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check and correct PAPER_TYPE</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1776</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> paperType = <a href="/web-doxygen/docs/api/files/src/config-h/#a251399cde30dd4c356bbd5634c6eb472">Config_getEnumAsString</a>(PAPER_TYPE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1777</span><span class="doxyLineContent"><span class="doxyHighlight">  paperType=paperType.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1778</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (paperType.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || paperType==</span><span class="doxyHighlightStringLiteral">"a4wide"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1779</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1780</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// use a4</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1781</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a8c58e5a30ece3e745e1561edd00f6c68">Config_updateEnum</a>(PAPER_TYPE,PAPER_TYPE_t::a4);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1782</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1783</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (paperType!=</span><span class="doxyHighlightStringLiteral">"a4"</span><span class="doxyHighlight"> &amp;&amp; paperType!=</span><span class="doxyHighlightStringLiteral">"letter"</span><span class="doxyHighlight"> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1784</span><span class="doxyLineContent"><span class="doxyHighlight">           paperType!=</span><span class="doxyHighlightStringLiteral">"legal"</span><span class="doxyHighlight"> &amp;&amp; paperType!=</span><span class="doxyHighlightStringLiteral">"executive"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1785</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1786</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Unknown page type '{}' specified\n"</span><span class="doxyHighlight">,paperType);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1787</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a8c58e5a30ece3e745e1561edd00f6c68">Config_updateEnum</a>(PAPER_TYPE,PAPER_TYPE_t::a4);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1788</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1789</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1790</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1791</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check &amp; correct STRIP_FROM_PATH</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1792</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a> = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(STRIP_FROM_PATH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1793</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>.empty()) </span><span class="doxyHighlightComment">// by default use the current path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1794</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1795</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string p = <a href="/web-doxygen/docs/api/classes/dir/#a0f62ab07068c5f966bca7ce280f4ed49">Dir::currentDirPath</a>()+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1796</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>.push_back(p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1797</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1798</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1799</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1800</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#aa60539b340894c76de2aa43ef25aede5">cleanUpPaths</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1801</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1802</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/config-h/#a77eefd6119ed441632a00d7d274184af">Config_updateList</a>(STRIP_FROM_PATH,<a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1803</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1804</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1805</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check &amp; correct STRIP_FROM_INC_PATH</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1806</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> stripFromIncPath = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(STRIP_FROM_INC_PATH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1807</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#aa60539b340894c76de2aa43ef25aede5">cleanUpPaths</a>(stripFromIncPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1808</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/config-h/#a77eefd6119ed441632a00d7d274184af">Config_updateList</a>(STRIP_FROM_INC_PATH,stripFromIncPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1809</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1810</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1811</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Test to see if HTML header is valid</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1812</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> headerFile = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_HEADER);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1813</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (check &amp;&amp; !headerFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1814</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1815</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(headerFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1816</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1817</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1818</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>(</span><span class="doxyHighlightStringLiteral">"tag HTML_HEADER: header file '{}' "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1819</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"does not exist\n"</span><span class="doxyHighlight">,headerFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1820</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1821</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1822</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1823</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1824</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Test to see if HTML footer is valid</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1825</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> footerFile = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_FOOTER);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1826</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (check &amp;&amp; !footerFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1827</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1828</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(footerFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1829</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1830</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1831</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>(</span><span class="doxyHighlightStringLiteral">"tag HTML_FOOTER: footer file '{}' "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1832</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"does not exist\n"</span><span class="doxyHighlight">,footerFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1833</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1834</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1835</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1836</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1837</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Test to see if MathJax code file is valid</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1838</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(USE_MATHJAX))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1839</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1840</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mathJaxFormat = <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(MATHJAX_FORMAT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1841</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> mathjaxVersion = <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(MATHJAX_VERSION);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1842</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mathjaxVersion == MATHJAX_VERSION_t::MathJax_2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1843</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1844</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mathJaxFormat==MATHJAX_FORMAT_t::chtml)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1845</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1846</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/config-h/#a8c58e5a30ece3e745e1561edd00f6c68">Config_updateEnum</a>(MATHJAX_FORMAT,MATHJAX_FORMAT_t::HTML_CSS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1847</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1848</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1849</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1850</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1851</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mathJaxFormat==MATHJAX_FORMAT_t::HTML_CSS || mathJaxFormat==MATHJAX_FORMAT_t::NativeMML)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1852</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1853</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/config-h/#a8c58e5a30ece3e745e1561edd00f6c68">Config_updateEnum</a>(MATHJAX_FORMAT,MATHJAX_FORMAT_t::chtml);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1854</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1855</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1856</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1857</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mathJaxCodefile = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(MATHJAX_CODEFILE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1858</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (check &amp;&amp; !mathJaxCodefile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1859</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1860</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(mathJaxCodefile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1861</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1862</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1863</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>(</span><span class="doxyHighlightStringLiteral">"tag MATHJAX_CODEFILE file '{}' "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1864</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"does not exist\n"</span><span class="doxyHighlight">,mathJaxCodefile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> path = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(MATHJAX_RELPATH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (path.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">      path = </span><span class="doxyHighlightStringLiteral">"https://cdn.jsdelivr.net/npm/mathjax@"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (mathjaxVersion)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> MATHJAX_VERSION_t::MathJax_2: path += </span><span class="doxyHighlightStringLiteral">"2"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> MATHJAX_VERSION_t::MathJax_3: path += </span><span class="doxyHighlightStringLiteral">"3"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (path.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(path.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1)!=</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">      path+=</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config_updateString</a>(MATHJAX_RELPATH,path);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Test to see if LaTeX header is valid</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> latexHeaderFile = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_HEADER);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1888</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (check &amp;&amp; !latexHeaderFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1889</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1890</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(latexHeaderFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1891</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1892</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1893</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>(</span><span class="doxyHighlightStringLiteral">"tag LATEX_HEADER: header file '{}' "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1894</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"does not exist\n"</span><span class="doxyHighlight">,latexHeaderFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1895</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1896</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1897</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1898</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1899</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Test to see if LaTeX footer is valid</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1900</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> latexFooterFile = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(LATEX_FOOTER);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1901</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (check &amp;&amp; !latexFooterFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1902</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1903</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(latexFooterFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1904</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1905</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1906</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config_term</a>(</span><span class="doxyHighlightStringLiteral">"tag LATEX_FOOTER: footer file '{}' "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1907</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"does not exist\n"</span><span class="doxyHighlight">,latexFooterFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1908</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1909</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1910</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1911</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1912</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check include path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1913</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;includePath = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(INCLUDE_PATH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1914</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : includePath)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1915</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1916</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1917</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1918</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1919</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"tag INCLUDE_PATH: include path '{}' does not exist\n"</span><span class="doxyHighlight">,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1920</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1921</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1922</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check PREDEFINED</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(ENABLE_PREPROCESSING))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;predefList = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(PREDEFINED);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : predefList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> predef=s.c_str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">      predef=predef.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i_equals=predef.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'='</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i_obrace=predef.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((i_obrace==0) || (i_equals==0) || (i_equals==1 &amp;&amp; predef.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i_equals-1)==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Illegal PREDEFINED format '{}', no define name specified\n"</span><span class="doxyHighlight">,predef);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check EXTENSION_MAPPING</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(EXTENSION_MAPPING),</span><span class="doxyHighlightStringLiteral">"EXTENSION_MAPPING"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check FILTER_PATTERNS</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(FILTER_PATTERNS),</span><span class="doxyHighlightStringLiteral">"FILTER_PATTERNS"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check FILTER_SOURCE_PATTERNS</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(FILTER_SOURCE_PATTERNS),</span><span class="doxyHighlightStringLiteral">"FILTER_SOURCE_PATTERNS"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check INPUT_FILE_ENCODING</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(INPUT_FILE_ENCODING),</span><span class="doxyHighlightStringLiteral">"INPUT_FILE_ENCODING"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check TAGFILES</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(TAGFILES),</span><span class="doxyHighlightStringLiteral">"TAGFILES"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check EXTRA_SEARCH_MAPPINGS</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SEARCHENGINE) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_HTML))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(EXTRA_SEARCH_MAPPINGS),</span><span class="doxyHighlightStringLiteral">"EXTRA_SEARCH_MAPPING"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> numThreads = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(NUM_PROC_THREADS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (numThreads==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">     numThreads = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(std::thread::hardware_concurrency());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span><span class="doxyLineContent"><span class="doxyHighlight">     <a href="/web-doxygen/docs/api/files/src/config-h/#a24f565457c1536240757e5c8ebbf2e97">Config_updateInt</a>(NUM_PROC_THREADS,numThreads);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check for settings that are inconsistent with having GENERATE_HTMLHELP enabled</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_HTMLHELP))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *depOption = </span><span class="doxyHighlightStringLiteral">"GENERATE_HTMLHELP"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(  depOption, </span><span class="doxyHighlightStringLiteral">"GENERATE_TREEVIEW"</span><span class="doxyHighlight">,    </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(  depOption, </span><span class="doxyHighlightStringLiteral">"SEARCHENGINE"</span><span class="doxyHighlight">,         </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(  depOption, </span><span class="doxyHighlightStringLiteral">"HTML_DYNAMIC_MENUS"</span><span class="doxyHighlight">,   </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(  depOption, </span><span class="doxyHighlightStringLiteral">"HTML_DYNAMIC_SECTIONS"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(  depOption, </span><span class="doxyHighlightStringLiteral">"HTML_COPY_CLIPBOARD"</span><span class="doxyHighlight">,  </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">  );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a0fba7b39cbe6dd4fe499dcd29ae2af0c">adjustStringSetting</a>(depOption, </span><span class="doxyHighlightStringLiteral">"HTML_FILE_EXTENSION"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">".html"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a16c4b1e165f06becc4b5debd88592a49">adjustColorStyleSetting</a>(depOption);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;tagFileList = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(TAGFILES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> filteredTagFileList;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : tagFileList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> validUrl = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> eqPos = s.find(</span><span class="doxyHighlightCharLiteral">'='</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (eqPos!=std::string::npos) </span><span class="doxyHighlightComment">// tag command contains a destination</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(s.substr(eqPos+1)).<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">        validUrl = url.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"http:"</span><span class="doxyHighlight">) || url.<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"https:"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (validUrl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">        filteredTagFileList.push_back(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"When enabling GENERATE_HTMLHELP the TAGFILES option should only contain destinations "</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightStringLiteral">"with https / http addresses (not: {}). I'll adjust it for you.\n"</span><span class="doxyHighlight">,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a77eefd6119ed441632a00d7d274184af">Config_updateList</a>(TAGFILES,filteredTagFileList);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check for settings that are inconsistent with having INLINE_GROUPED_CLASSES enabled</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(INLINE_GROUPED_CLASSES))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *depOption = </span><span class="doxyHighlightStringLiteral">"INLINE_GROUPED_CLASSES"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(depOption, </span><span class="doxyHighlightStringLiteral">"SEPARATE_MEMBER_PAGES"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// clip number of threads</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> dotNumThreads = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(DOT_NUM_THREADS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dotNumThreads&gt;32)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2024</span><span class="doxyLineContent"><span class="doxyHighlight">    dotNumThreads=32;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dotNumThreads&lt;=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">    dotNumThreads=std::max(2u,std::thread::hardware_concurrency()+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/config-h/#a24f565457c1536240757e5c8ebbf2e97">Config_updateInt</a>(DOT_NUM_THREADS,dotNumThreads);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check plantuml path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> plantumlJarPath = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(PLANTUML_JAR_PATH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!plantumlJarPath.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> pu(plantumlJarPath.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pu.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; pu.<a href="/web-doxygen/docs/api/classes/fileinfo/#aa941e087c82c28ff498d9d3dec551b1f">isDir</a>()) </span><span class="doxyHighlightComment">// PLANTUML_JAR_PATH is directory</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> plantumlJar = plantumlJarPath+<a href="/web-doxygen/docs/api/namespaces/portable/#a0f30be3f0aed0b88804816f3e6310ee4">Portable::pathSeparator</a>()+</span><span class="doxyHighlightStringLiteral">"plantuml.jar"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> jar(plantumlJar.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (jar.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; jar.<a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">isFile</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">        plantumlJarPath = plantumlJar;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2047</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2048</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Jar file 'plantuml.jar' not found at location specified via PLANTUML_JAR_PATH: '{}'\n"</span><span class="doxyHighlight">,plantumlJarPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span><span class="doxyLineContent"><span class="doxyHighlight">        plantumlJarPath=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2052</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pu.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; pu.<a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">isFile</a>()) </span><span class="doxyHighlightComment">// PLANTUML_JAR_PATH is file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2053</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// Nothing to be done</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"PLANTUML_JAR_PATH is not a directory with a 'plantuml.jar' file or is not an existing file: {}\n"</span><span class="doxyHighlight">,plantumlJarPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2059</span><span class="doxyLineContent"><span class="doxyHighlight">      plantumlJarPath=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2060</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2061</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config_updateString</a>(PLANTUML_JAR_PATH,plantumlJarPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2062</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check dia path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> diaPath = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(DIA_PATH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!diaPath.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> diaExe = diaPath+</span><span class="doxyHighlightStringLiteral">"/dia"</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/namespaces/portable/#acf75def6ec394875d4a3c380ffc301b7">Portable::commandExtension</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> dp(diaExe.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!dp.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() || !dp.<a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">isFile</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"dia could not be found at {}\n"</span><span class="doxyHighlight">,diaPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">      diaPath=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2076</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2077</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">      diaPath=dp.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#if defined(_WIN32) </span><span class="doxyHighlightComment">// convert slashes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0,l=diaPath.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2081</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (i=0;i&lt;l;i++) </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (diaPath.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i)==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">) diaPath.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i)=</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2082</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2083</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config_updateString</a>(DIA_PATH,diaPath);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2087</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2088</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check INPUT</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> inputSources=<a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(INPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inputSources.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2091</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// use current dir as the default</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2093</span><span class="doxyLineContent"><span class="doxyHighlight">    inputSources.push_back(<a href="/web-doxygen/docs/api/classes/dir/#a0f62ab07068c5f966bca7ce280f4ed49">Dir::currentDirPath</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2094</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2095</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2096</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : inputSources)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(s.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"tag INPUT: input source '{}' does not exist\n"</span><span class="doxyHighlight">,s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2104</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2105</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/config-h/#a77eefd6119ed441632a00d7d274184af">Config_updateList</a>(INPUT,inputSources);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2108</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2109</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// if no output format is enabled, warn the user</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2110</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_HTML)    &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">      !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_LATEX)   &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">      !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_MAN)     &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span><span class="doxyLineContent"><span class="doxyHighlight">      !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_RTF)     &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">      !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_XML)     &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">      !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_PERLMOD) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">      !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_RTF)     &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span><span class="doxyLineContent"><span class="doxyHighlight">      !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_DOCBOOK) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">      !<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_AUTOGEN_DEF) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2119</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(GENERATE_TAGFILE).isEmpty()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"No output formats selected! Set at least one of the main GENERATE_* options to YES.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2124</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2125</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2126</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check HTMLHELP creation requirements</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2127</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_HTML) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2128</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_HTMLHELP))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2129</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"GENERATE_HTMLHELP=YES requires GENERATE_HTML=YES.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2133</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check sitemap creation requirements</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_HTML) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span><span class="doxyLineContent"><span class="doxyHighlight">      !<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(SITEMAP_URL).isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2137</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2138</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"Setting SITEMAP_URL requires GENERATE_HTML=YES.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2139</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2140</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2141</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2142</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check QHP creation requirements</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2143</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_QHP))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_HTML))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2146</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2147</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"GENERATE_QHP=YES requires GENERATE_HTML=YES.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2148</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2149</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(QHP_NAMESPACE).isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2150</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"GENERATE_QHP=YES requires QHP_NAMESPACE to be set. Using 'org.doxygen.doc' as default!.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2152</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config_updateString</a>(QHP_NAMESPACE,</span><span class="doxyHighlightStringLiteral">"org.doxygen.doc"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2153</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2154</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2155</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(QHP_VIRTUAL_FOLDER).isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"GENERATE_QHP=YES requires QHP_VIRTUAL_FOLDER to be set. Using 'doc' as default!\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config_updateString</a>(QHP_VIRTUAL_FOLDER,</span><span class="doxyHighlightStringLiteral">"doc"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;tagFileList = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(TAGFILES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tagFileList.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2162</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2163</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"When enabling GENERATE_QHP the TAGFILES option should be empty. I'll adjust it for you.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2164</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/config-h/#a77eefd6119ed441632a00d7d274184af">Config_updateList</a>(TAGFILES,<a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2165</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2166</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2167</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2168</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2169</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_JAVA) &amp;&amp; <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(INLINE_INFO))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2170</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2171</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// don't show inline info for Java output, since Java has no inline</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2172</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// concept.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2173</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a252335f9ceadbd28f4394ec14a7f2777">Config_updateBool</a>(INLINE_INFO,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2175</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2176</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2177</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> depth = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(MAX_DOT_GRAPH_DEPTH);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2178</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (depth==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a24f565457c1536240757e5c8ebbf2e97">Config_updateInt</a>(MAX_DOT_GRAPH_DEPTH,1000);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2181</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2182</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2183</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(INTERACTIVE_SVG))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2185</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2186</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// issue 11308</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2187</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(DOT_IMAGE_FORMAT) == DOT_IMAGE_FORMAT_t::svg_cairo) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2188</span><span class="doxyLineContent"><span class="doxyHighlight">        (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(DOT_IMAGE_FORMAT) == DOT_IMAGE_FORMAT_t::svg_cairo_cairo))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2189</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2190</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"When using DOT_IMAGE_FORMAT with {} the INTERACTIVE_SVG option should be disabled. I'll adjust it for you.\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2191</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/config-h/#a251399cde30dd4c356bbd5634c6eb472">Config_getEnumAsString</a>(DOT_IMAGE_FORMAT));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2192</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/config-h/#a252335f9ceadbd28f4394ec14a7f2777">Config_updateBool</a>(INTERACTIVE_SVG,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2193</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2194</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2195</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2197</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check for settings that are inconsistent with having OPTIMIZED_OUTPUT_VHDL enabled</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_VHDL))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2199</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *depOption = </span><span class="doxyHighlightStringLiteral">"OPTIMIZE_OUTPUT_VHDL"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(depOption,</span><span class="doxyHighlightStringLiteral">"INLINE_INHERITED_MEMB"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(depOption,</span><span class="doxyHighlightStringLiteral">"INHERIT_DOCS"</span><span class="doxyHighlight">,         </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(depOption,</span><span class="doxyHighlightStringLiteral">"HIDE_SCOPE_NAMES"</span><span class="doxyHighlight">,     </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight"> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2204</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(depOption,</span><span class="doxyHighlightStringLiteral">"EXTRACT_PRIVATE"</span><span class="doxyHighlight">,      </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight"> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2205</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(depOption,</span><span class="doxyHighlightStringLiteral">"ENABLE_PREPROCESSING"</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>(depOption,</span><span class="doxyHighlightStringLiteral">"EXTRACT_PACKAGE"</span><span class="doxyHighlight">,      </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight"> );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2207</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2208</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/configimpl-l/#ac191ad1786e980d514c4535505cf99d6">checkFileName</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(GENERATE_TAGFILE),</span><span class="doxyHighlightStringLiteral">"GENERATE_TAGFILE"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2210</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2211</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config_updateString</a>(GENERATE_TAGFILE,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2212</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2213</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2214</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#if 0 </span><span class="doxyHighlightComment">// TODO: this breaks test 25; SOURCEBROWSER = NO and SOURCE_TOOLTIPS = YES.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2215</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// So this and other regressions should be analyzed and fixed before this can be enabled</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// disable any boolean options that depend on disabled options</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;option : m_options)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2219</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> depName = option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#a8a744f63445f4cd0ce86d7f423bc7161">dependsOn</a>(); </span><span class="doxyHighlightComment">// option has a dependency</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2220</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!depName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2221</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2222</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> * dep = Config::instance()-&gt;get(depName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2223</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dep-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#af9d4d56d36500792b82fce5b11202a60">kind</a>()==<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O_Bool</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2224</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/configimpl-h/#aae7186f5d5a06fedba658e712974a9c8">ConfigImpl_getBool</a>(</span><span class="doxyHighlightStringLiteral">"depName"</span><span class="doxyHighlight">)==<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>) </span><span class="doxyHighlightComment">// dependent option is disabled</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2225</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2226</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#af9d4d56d36500792b82fce5b11202a60">kind</a>()==<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O_Bool</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2227</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2228</span><span class="doxyLineContent"><span class="doxyHighlight">          printf(</span><span class="doxyHighlightStringLiteral">"disabling option %s\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(option-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">name</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2229</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/configimpl-h/#aae7186f5d5a06fedba658e712974a9c8">ConfigImpl_getBool</a>(</span><span class="doxyHighlightStringLiteral">"option-&gt;name("</span><span class="doxyHighlight">))=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; </span><span class="doxyHighlightComment">// also disable this option</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2230</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2231</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2232</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2233</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2234</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2235</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2236</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ad8f84f9572072b97ac930fb0f1a7ba9f">adjustBoolSetting</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a16c4b1e165f06becc4b5debd88592a49">adjustColorStyleSetting</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a0fba7b39cbe6dd4fe499dcd29ae2af0c">adjustStringSetting</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ac191ad1786e980d514c4535505cf99d6">checkFileName</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#abb0ac5ce17fb9a60710a1ad77a2ebb14">checkList</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#aa60539b340894c76de2aa43ef25aede5">cleanUpPaths</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#acf75def6ec394875d4a3c380ffc301b7">Portable::commandExtension</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config\_getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a251399cde30dd4c356bbd5634c6eb472">Config\_getEnumAsString</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config\_getInt</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config\_getList</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config\_getString</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a0b752f150eb5a0ec002ee2a3b245bbd2">ConfigImpl::config\_term</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a252335f9ceadbd28f4394ec14a7f2777">Config\_updateBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a8c58e5a30ece3e745e1561edd00f6c68">Config\_updateEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a24f565457c1536240757e5c8ebbf2e97">Config\_updateInt</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a77eefd6119ed441632a00d7d274184af">Config\_updateList</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config\_updateString</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-h/#aae7186f5d5a06fedba658e712974a9c8">ConfigImpl\_getBool</a>, <a href="/web-doxygen/docs/api/classes/dir/#a0f62ab07068c5f966bca7ce280f4ed49">Dir::currentDirPath</a>, <a href="/web-doxygen/docs/api/classes/configoption/#a8a744f63445f4cd0ce86d7f423bc7161">ConfigOption::dependsOn</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#aa941e087c82c28ff498d9d3dec551b1f">FileInfo::isDir</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#ab7840bb4fca4b3d9938c1b3f0e1352ef">FileInfo::isFile</a>, <a href="/web-doxygen/docs/api/classes/configoption/#af9d4d56d36500792b82fce5b11202a60">ConfigOption::kind</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ab89196927c521e95680eb5efdc562187">ConfigOption::name</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O\_Bool</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a0f30be3f0aed0b88804816f3e6310ee4">Portable::pathSeparator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a8c90a81fbaf02ad9af7387f3ed1c20c1">stripFromPath</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn\_uncond</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2426bb829c785229969c3052f3e37fb1">checkConfiguration</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.
</div>
</div>

### compareDoxyfile() {#a6cc61dde8935f986295262513d2feb2d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Config::compareDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="#a098ed7e63f2ba437f0e540316e6cd940">CompareMode</a> compareMode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Writes a the differences between the current configuration and the template configuration to stream <em>t</em>.

Declaration at line 68 of file <a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>, definition at line 2348 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6cc61dde8935f986295262513d2feb2d">2348</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6cc61dde8935f986295262513d2feb2d">Config::compareDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2349</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2350</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a04731f96560c04835ce340aa776251cb">postProcess</a>(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, compareMode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2351</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a24a3e5ba9f648d261101861a8dd22f83">compareDoxyfile</a>(t, compareMode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2352</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/configimpl/#a24a3e5ba9f648d261101861a8dd22f83">ConfigImpl::compareDoxyfile</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a> and <a href="#a04731f96560c04835ce340aa776251cb">postProcess</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a66afbf89d01cdca028632ff568be036d">compareDoxyfile</a>.
</div>
</div>

### deinit() {#a7b3346b2e70cc73d231d540df5d67e57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Config::deinit ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Clean up any data

Declaration at line 104 of file <a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>, definition at line 2396 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7b3346b2e70cc73d231d540df5d67e57">2396</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7b3346b2e70cc73d231d540df5d67e57">Config::deinit</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2397</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2398</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a11be9a99f82898b014f311b5fd9437c1">deleteInstance</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2399</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/configimpl/#a11be9a99f82898b014f311b5fd9437c1">ConfigImpl::deleteInstance</a> and <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.
</div>
</div>

### init() {#a91bcb187ed95ec673137e413a4d77203}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Config::init ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Initialize configuration variables to their default value

Declaration at line 57 of file <a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>, definition at line 1662 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a91bcb187ed95ec673137e413a4d77203">1662</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a91bcb187ed95ec673137e413a4d77203">Config::init</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1663</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1664</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a50654e77279eecd43b0dd91cb21420e5">init</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1665</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/configimpl/#a50654e77279eecd43b0dd91cb21420e5">ConfigImpl::init</a> and <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.
</div>
</div>

### parse() {#a88ed583dc36b1439108163403cc4224f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool Config::parse (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, bool update=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a098ed7e63f2ba437f0e540316e6cd940">CompareMode</a> compareMode=<a href="#a098ed7e63f2ba437f0e540316e6cd940abbd47109890259c0127154db1af26c75">CompareMode::Full</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Parses a configuration file with name <em>fn</em>.

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd>
TRUE if successful, FALSE if the file could not be opened or read.
</dd>
</dl>


Declaration at line 84 of file <a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>, definition at line 2364 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a88ed583dc36b1439108163403cc4224f">2364</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a88ed583dc36b1439108163403cc4224f">Config::parse</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> update, <a href="#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2365</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2366</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/configimpl-l/#aba980278adc63976f725abf4f355309c">g_compareMode</a> = compareMode;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2367</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> parseRes = <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a5d06627b2afb76668e8315613a76b9d3">parse</a>(fileName,update);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2368</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!parseRes) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> parseRes;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2369</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2370</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// Internally we use the default format UTF-8 and</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2371</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// when updating etc. the output is in this format as well and not in the read format</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2372</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a> *option = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/files/src/configimpl-l/#ac8c998011c1de1f3c38cb48c908af98b">g_config</a>-&gt;get(</span><span class="doxyHighlightStringLiteral">"DOXYFILE_ENCODING"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2373</span><span class="doxyLineContent"><span class="doxyHighlight">  option-&gt;<a href="/web-doxygen/docs/api/classes/configstring/#ae2509071329426c4c5749eda585e1409">init</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2374</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2375</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> parseRes;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2376</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/configimpl-l/#aba980278adc63976f725abf4f355309c">g\_compareMode</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#ac8c998011c1de1f3c38cb48c908af98b">g\_config</a>, <a href="/web-doxygen/docs/api/classes/configstring/#ae2509071329426c4c5749eda585e1409">ConfigString::init</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a> and <a href="/web-doxygen/docs/api/classes/configimpl/#a5d06627b2afb76668e8315613a76b9d3">ConfigImpl::parse</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.
</div>
</div>

### postProcess() {#a04731f96560c04835ce340aa776251cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Config::postProcess (bool clearHeaderAndFooter, <a href="#a098ed7e63f2ba437f0e540316e6cd940">CompareMode</a> compareMode=<a href="#a098ed7e63f2ba437f0e540316e6cd940abbd47109890259c0127154db1af26c75">CompareMode::Full</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Post processed the parsed data. Replaces raw string values by the actual values. and replaces environment variables.

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">clearHeaderAndFooter</td>
<td class="doxyParamItemDescription">set to TRUE when writing header and footer templates.</td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">compareMode</td>
<td class="doxyParamItemDescription">signals if we in Doxyfile compare (<code>-x</code> or <code>-x_noenv</code>) mode are or not. Influences setting of the default value and replacement of environment variables and CMake type replacement variables.</td>
</tr>
</table>
</dd>
</dl>

Declaration at line 92 of file <a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>, definition at line 2378 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a04731f96560c04835ce340aa776251cb">2378</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a04731f96560c04835ce340aa776251cb">Config::postProcess</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> clearHeaderAndFooter, <a href="#a098ed7e63f2ba437f0e540316e6cd940">Config::CompareMode</a> compareMode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2379</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2380</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> configInst = <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2381</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (compareMode != <a href="#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">CompareMode::CompressedNoEnv</a>) configInst-&gt;substituteEnvironmentVars();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2382</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (compareMode == <a href="#a098ed7e63f2ba437f0e540316e6cd940abbd47109890259c0127154db1af26c75">CompareMode::Full</a>)            configInst-&gt;emptyValueToDefault();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2383</span><span class="doxyLineContent"><span class="doxyHighlight">  configInst-&gt;convertStrToVal(compareMode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2384</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2385</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// avoid bootstrapping issues when the g_config file already</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2386</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// refers to the files that we are supposed to parse.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2387</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (clearHeaderAndFooter)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2388</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2389</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config_updateString</a>(HTML_HEADER ,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2390</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config_updateString</a>(HTML_FOOTER ,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2391</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config_updateString</a>(LATEX_HEADER,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2392</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config_updateString</a>(LATEX_FOOTER,</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2393</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2394</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a098ed7e63f2ba437f0e540316e6cd940aa0ba248fb99f2c67cce98a6822482fba">CompressedNoEnv</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a168f2876d56397a94af9140753974f38">Config\_updateString</a>, <a href="#a098ed7e63f2ba437f0e540316e6cd940abbd47109890259c0127154db1af26c75">Full</a> and <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2426bb829c785229969c3052f3e37fb1">checkConfiguration</a>, <a href="#a6cc61dde8935f986295262513d2feb2d">compareDoxyfile</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.
</div>
</div>

### updateObsolete() {#ad27e22c157d0c2d33414923d0a41c200}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Config::updateObsolete ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Adjust any configuration values based on the value of obsolete options.

Declaration at line 101 of file <a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>, definition at line 2243 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad27e22c157d0c2d33414923d0a41c200">2243</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad27e22c157d0c2d33414923d0a41c200">Config::updateObsolete</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2244</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2245</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//------------------------</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// check for presence of obsolete CLASS_DIAGRAM option and correct CLASS_GRAPH if needed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2247</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *classDiagramsOpt = <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">get</a>(</span><span class="doxyHighlightStringLiteral">"CLASS_DIAGRAMS"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2248</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *haveDotOpt       = <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">get</a>(</span><span class="doxyHighlightStringLiteral">"HAVE_DOT"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2249</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *classGraphOpt    = <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">get</a>(</span><span class="doxyHighlightStringLiteral">"CLASS_GRAPH"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2250</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (classDiagramsOpt &amp;&amp; classDiagramsOpt-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#af9d4d56d36500792b82fce5b11202a60">kind</a>()==<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaab60c019594029c214e601ec24988d6ac">ConfigOption::O_Obsolete</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2251</span><span class="doxyLineContent"><span class="doxyHighlight">      haveDotOpt &amp;&amp; classGraphOpt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2252</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2253</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a> *classDiagramsOpt_ = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(classDiagramsOpt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2254</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configbool">ConfigBool</a>     *haveDotOpt_       = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configbool">ConfigBool</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(haveDotOpt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2255</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a>     *classGraphOpt_    = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(classGraphOpt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2256</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (classDiagramsOpt_ &amp;&amp; haveDotOpt_ &amp;&amp; classGraphOpt_ &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2257</span><span class="doxyLineContent"><span class="doxyHighlight">        classDiagramsOpt_-&gt;<a href="/web-doxygen/docs/api/classes/configobsolete/#a2fb91ca94787c2b9767f7010f11571ea">isPresent</a>() &amp;&amp; classDiagramsOpt_-&gt;<a href="/web-doxygen/docs/api/classes/configobsolete/#a7514acb34d8d15c46be2715d63e2680c">orgType</a>()==<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O_Bool</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2258</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2259</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> classDiagramValue = *classDiagramsOpt_-&gt;<a href="/web-doxygen/docs/api/classes/configobsolete/#a5b2f5633d6d13cfe0c2873ab683db80e">valueStringRef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2260</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> haveDotValue      = *haveDotOpt_-&gt;<a href="/web-doxygen/docs/api/classes/configbool/#a68ac670d16fb28e4dd4df321457c7b29">valueStringRef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2261</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;classGraphValue  = *classGraphOpt_-&gt;<a href="/web-doxygen/docs/api/classes/configenum/#a63af270856c22528eaa62970056d583f">valueRef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2262</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isValid1=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">, isValid2=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2263</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bClassDiagrams = <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a>(classDiagramValue,isValid1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2264</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bHaveDot       = haveDotValue.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() ? false : <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a>(haveDotValue,     isValid2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2265</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isValid1 &amp;&amp; isValid2 &amp;&amp; !bClassDiagrams &amp;&amp; !bHaveDot &amp;&amp; classGraphValue.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>()==</span><span class="doxyHighlightStringLiteral">"yes"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2266</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2267</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"Changing CLASS_GRAPH option to TEXT because obsolete option CLASS_DIAGRAM was found and set to NO.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2268</span><span class="doxyLineContent"><span class="doxyHighlight">        classGraphValue=</span><span class="doxyHighlightStringLiteral">"TEXT"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2269</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2270</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2271</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2272</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2273</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// update TIMESTAMP based on HTML_TIMESTAMP and LATEX_TIMESTAMP</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2274</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *HtmlTimestamp = <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">get</a>(</span><span class="doxyHighlightStringLiteral">"HTML_TIMESTAMP"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2275</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *timestampOpt    = <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">get</a>(</span><span class="doxyHighlightStringLiteral">"TIMESTAMP"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2276</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> reset = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2277</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (HtmlTimestamp &amp;&amp; HtmlTimestamp-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#af9d4d56d36500792b82fce5b11202a60">kind</a>()==<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaab60c019594029c214e601ec24988d6ac">ConfigOption::O_Obsolete</a> &amp;&amp; timestampOpt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2278</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2279</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a> *htmlTimestamp_ = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(HtmlTimestamp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2280</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a>     *timestampOpt_ = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(timestampOpt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2281</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (htmlTimestamp_ &amp;&amp; timestampOpt_ &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2282</span><span class="doxyLineContent"><span class="doxyHighlight">        htmlTimestamp_-&gt;<a href="/web-doxygen/docs/api/classes/configobsolete/#a2fb91ca94787c2b9767f7010f11571ea">isPresent</a>() &amp;&amp; htmlTimestamp_-&gt;<a href="/web-doxygen/docs/api/classes/configobsolete/#a7514acb34d8d15c46be2715d63e2680c">orgType</a>()==<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O_Bool</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2283</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2284</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;timestampValue  = *timestampOpt_-&gt;<a href="/web-doxygen/docs/api/classes/configenum/#a63af270856c22528eaa62970056d583f">valueRef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2285</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> htmlTimestampValue = *htmlTimestamp_-&gt;<a href="/web-doxygen/docs/api/classes/configobsolete/#a5b2f5633d6d13cfe0c2873ab683db80e">valueStringRef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2286</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isValid=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2287</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bTimestamp = <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a>(htmlTimestampValue,isValid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2288</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isValid &amp;&amp; bTimestamp)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2289</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2290</span><span class="doxyLineContent"><span class="doxyHighlight">        reset = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2291</span><span class="doxyLineContent"><span class="doxyHighlight">        timestampValue = </span><span class="doxyHighlightStringLiteral">"YES"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2292</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2293</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2294</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2295</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configoption">ConfigOption</a> *LatexTimestamp = <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">get</a>(</span><span class="doxyHighlightStringLiteral">"LATEX_TIMESTAMP"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2296</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!reset &amp;&amp; LatexTimestamp &amp;&amp; LatexTimestamp-&gt;<a href="/web-doxygen/docs/api/classes/configoption/#af9d4d56d36500792b82fce5b11202a60">kind</a>()==<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaab60c019594029c214e601ec24988d6ac">ConfigOption::O_Obsolete</a> &amp;&amp; timestampOpt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2297</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2298</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a> *latexTimestamp_ = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(LatexTimestamp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2299</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a>     *timestampOpt_ = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configenum">ConfigEnum</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(timestampOpt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2300</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (latexTimestamp_ &amp;&amp; timestampOpt_ &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2301</span><span class="doxyLineContent"><span class="doxyHighlight">        latexTimestamp_-&gt;<a href="/web-doxygen/docs/api/classes/configobsolete/#a2fb91ca94787c2b9767f7010f11571ea">isPresent</a>() &amp;&amp; latexTimestamp_-&gt;<a href="/web-doxygen/docs/api/classes/configobsolete/#a7514acb34d8d15c46be2715d63e2680c">orgType</a>()==<a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O_Bool</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2302</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2303</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;timestampValue  = *timestampOpt_-&gt;<a href="/web-doxygen/docs/api/classes/configenum/#a63af270856c22528eaa62970056d583f">valueRef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2304</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> latexTimestampValue = *latexTimestamp_-&gt;<a href="/web-doxygen/docs/api/classes/configobsolete/#a5b2f5633d6d13cfe0c2873ab683db80e">valueStringRef</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2305</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isValid=</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2306</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> bTimestamp = <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a>(latexTimestampValue,isValid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2307</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (isValid &amp;&amp; bTimestamp) timestampValue = </span><span class="doxyHighlightStringLiteral">"YES"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2308</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2309</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2310</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2311</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fontname = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">get</a>(</span><span class="doxyHighlightStringLiteral">"DOT_FONTNAME"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2312</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fontsize = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configobsolete">ConfigObsolete</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">get</a>(</span><span class="doxyHighlightStringLiteral">"DOT_FONTSIZE"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2313</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2314</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// correct DOT_FONTNAME if needed</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2315</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fontname &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2316</span><span class="doxyLineContent"><span class="doxyHighlight">      (*fontname-&gt;valueStringRef() == </span><span class="doxyHighlightStringLiteral">"FreeSans"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2317</span><span class="doxyLineContent"><span class="doxyHighlight">      || *fontname-&gt;valueStringRef() == </span><span class="doxyHighlightStringLiteral">"FreeSans.ttf"</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2318</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"doxygen no longer ships with the FreeSans font.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2319</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"  You may want to clear or change DOT_FONTNAME.\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2320</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightStringLiteral">"  Otherwise you run the risk that the wrong font is being used for dot generated graphs.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2321</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2322</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> commonAttrOpt = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">get</a>(</span><span class="doxyHighlightStringLiteral">"DOT_COMMON_ATTR"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2323</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (commonAttrOpt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2324</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2325</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; commonAttrStr = *commonAttrOpt-&gt;valueRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2326</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotattributes">DotAttributes</a> commonAttr(commonAttrStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2327</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1ab01907c143c95a407993630bdfeba9">updateAttribute</a>(commonAttr, </span><span class="doxyHighlightStringLiteral">"fontname"</span><span class="doxyHighlight">, fontname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2328</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1ab01907c143c95a407993630bdfeba9">updateAttribute</a>(commonAttr, </span><span class="doxyHighlightStringLiteral">"fontsize"</span><span class="doxyHighlight">, fontsize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2329</span><span class="doxyLineContent"><span class="doxyHighlight">    commonAttrStr = commonAttr.<a href="/web-doxygen/docs/api/classes/dotattributes/#aaee5c25bd25303a97739d3c43ee72449">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2330</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2331</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2332</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> edgeAttrOpt = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/configstring">ConfigString</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">get</a>(</span><span class="doxyHighlightStringLiteral">"DOT_EDGE_ATTR"</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2333</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (edgeAttrOpt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2334</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2335</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>&amp; edgeAttrStr = *edgeAttrOpt-&gt;valueRef();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2336</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotattributes">DotAttributes</a> edgeAttr(edgeAttrStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2337</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1ab01907c143c95a407993630bdfeba9">updateAttribute</a>(edgeAttr, </span><span class="doxyHighlightStringLiteral">"labelfontname"</span><span class="doxyHighlight">, fontname);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2338</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1ab01907c143c95a407993630bdfeba9">updateAttribute</a>(edgeAttr, </span><span class="doxyHighlightStringLiteral">"labelfontsize"</span><span class="doxyHighlight">, fontsize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2339</span><span class="doxyLineContent"><span class="doxyHighlight">    edgeAttrStr = edgeAttr.<a href="/web-doxygen/docs/api/classes/dotattributes/#aaee5c25bd25303a97739d3c43ee72449">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2340</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2341</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a7b04c2a27074eeeccf2fadb03b80fc42">convertStringToBool</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a6ee5f5279077a8be14ca6e22d525f104">ConfigImpl::get</a>, <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/configobsolete/#a2fb91ca94787c2b9767f7010f11571ea">ConfigObsolete::isPresent</a>, <a href="/web-doxygen/docs/api/classes/configoption/#af9d4d56d36500792b82fce5b11202a60">ConfigOption::kind</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaa306962172c18f2b309fb729e66e32e81">ConfigOption::O\_Bool</a>, <a href="/web-doxygen/docs/api/classes/configoption/#ad60cb308cdf307e72796dc2fc2a40fdaab60c019594029c214e601ec24988d6ac">ConfigOption::O\_Obsolete</a>, <a href="/web-doxygen/docs/api/classes/configobsolete/#a7514acb34d8d15c46be2715d63e2680c">ConfigObsolete::orgType</a>, <a href="/web-doxygen/docs/api/classes/dotattributes/#aaee5c25bd25303a97739d3c43ee72449">DotAttributes::str</a>, <a href="/web-doxygen/docs/api/files/src/configimpl-l/#a1ab01907c143c95a407993630bdfeba9">updateAttribute</a>, <a href="/web-doxygen/docs/api/classes/configenum/#a63af270856c22528eaa62970056d583f">ConfigEnum::valueRef</a>, <a href="/web-doxygen/docs/api/classes/configbool/#a68ac670d16fb28e4dd4df321457c7b29">ConfigBool::valueStringRef</a>, <a href="/web-doxygen/docs/api/classes/configobsolete/#a5b2f5633d6d13cfe0c2873ab683db80e">ConfigObsolete::valueStringRef</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn\_uncond</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a2426bb829c785229969c3052f3e37fb1">checkConfiguration</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.
</div>
</div>

### writeTemplate() {#a98dcadaa623b84d8929dc38239f31cb2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Config::writeTemplate (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, bool shortList, bool updateOnly=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Writes a template configuration to stream <em>t</em>. If <em>shortList</em> is <code>TRUE</code> the description of each configuration option will be omitted.

Declaration at line 63 of file <a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>, definition at line 2343 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a98dcadaa623b84d8929dc38239f31cb2">2343</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a98dcadaa623b84d8929dc38239f31cb2">Config::writeTemplate</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> shortList,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> update)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2344</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2345</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#aa7948af854eb611524c208def210db01">writeTemplate</a>(t,shortList,update);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2346</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a> and <a href="/web-doxygen/docs/api/classes/configimpl/#aa7948af854eb611524c208def210db01">ConfigImpl::writeTemplate</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a41448de2244811dc71fc91a111c2012a">generateConfigFile</a>.
</div>
</div>

### writeXMLDoxyfile() {#a5744a411e57f8a3a18ce6569e843b11e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Config::writeXMLDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Writes a the used settings of the current configuration as XML format to stream <em>t</em>.

Declaration at line 73 of file <a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>, definition at line 2354 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5744a411e57f8a3a18ce6569e843b11e">2354</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5744a411e57f8a3a18ce6569e843b11e">Config::writeXMLDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2355</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2356</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a87163252416c500d2000ad78353400a2">writeXMLDoxyfile</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2357</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a> and <a href="/web-doxygen/docs/api/classes/configimpl/#a87163252416c500d2000ad78353400a2">ConfigImpl::writeXMLDoxyfile</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>.
</div>
</div>

### writeXSDDoxyfile() {#a8dfcffe6278ca640b592ae6661b794b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Config::writeXSDDoxyfile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




Writes all possible setting ids to an XSD file for validation through the stream <em>t</em>.

Declaration at line 78 of file <a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>, definition at line 2359 of file <a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8dfcffe6278ca640b592ae6661b794b5">2359</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8dfcffe6278ca640b592ae6661b794b5">Config::writeXSDDoxyfile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2360</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2361</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a>()-&gt;<a href="/web-doxygen/docs/api/classes/configimpl/#a933b57616dbd31be7ff204d7b467758a">writeXSDDoxyfile</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2362</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/configimpl/#a501e98a30e96c9930ac4b1791b80c09a">ConfigImpl::instance</a> and <a href="/web-doxygen/docs/api/classes/configimpl/#a933b57616dbd31be7ff204d7b467758a">ConfigImpl::writeXSDDoxyfile</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>.
</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/config-h">config.h</a></li>
<li><a href="/web-doxygen/docs/api/files/src/configimpl-l">configimpl.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
