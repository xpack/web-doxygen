---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/classes/docgroup
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DocGroup` Class Reference



## Declaration

<div class="doxyDeclaration">
class DocGroup { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/docgroup-h">src/docgroup.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b3497cc6cc6a5f8c9aa20dcbad4d9a9">DocGroup</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af3ca5770267b6242e2b95d15c47a0db9">enterFile</a> (const QCString &amp;fileName, int)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15c99d30cd779d86716ffb2f341db5e1">leaveFile</a> (const QCString &amp;fileName, int line)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae49d781442d3cbceed9b62859b3d4b89">enterCompound</a> (const QCString &amp;fileName, int line, const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a14c0151b77e31de76f50ea2cb9d3e5cb">leaveCompound</a> (const QCString &amp;, int, const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9cb5ab2169da2f5bf14816e9c10e8290">open</a> (Entry *e, const QCString &amp;, int, bool implicit=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7610569d96adb6bd19ed159a5f53a26c">close</a> (Entry *e, const QCString &amp;fileName, int line, bool foundInline, bool implicit=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4fb2f5bfdd28daeceb60dbb262e08097">initGroupInfo</a> (Entry *e)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa6a996a17a2a292dd6f0a2936a1d9910">isEmpty</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8ca201268362991329a26c5725f174b">clearHeader</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9c704ca73aa365da5c61e2b320f8cdd8">appendHeader</a> (const char)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b79815ce3108572e1405da479f34e3d">addDocs</a> (Entry *e)</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75ac79ba2e9fa9b9feeaadf6f8567931">findExistingGroup</a> (const MemberGroupInfo *info)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24b4123e679488c274cb70529786fe35">m_openCount</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a832e0a0b5e7541fb07abef41a8f129a7">m_memberGroupHeader</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a> = 0</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a></td>
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


<p>Definition at line 24 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### DocGroup() {#a4b3497cc6cc6a5f8c9aa20dcbad4d9a9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DocGroup::DocGroup ()</td>
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



<p>Definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4b3497cc6cc6a5f8c9aa20dcbad4d9a9">27</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a4b3497cc6cc6a5f8c9aa20dcbad4d9a9">DocGroup</a>() {};</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addDocs() {#a9b79815ce3108572e1405da479f34e3d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocGroup::addDocs (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * e)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 40 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 205 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b79815ce3108572e1405da479f34e3d">205</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9b79815ce3108572e1405da479f34e3d">DocGroup::addDocs</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *e)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a967db0d8493a46efab87a53d423161eb">section</a>.isMemberGrp())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>=e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ad602ba19af5785515ed81790d843ce4c">brief</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a> = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a>(e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a>,e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a180b5fdd7f3b963e4b0d2c4ea6e0b1b5">docLine</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>.isEmpty() &amp;&amp; !e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>+=</span><span class="doxyHighlightStringLiteral">"\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>+=e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">      std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/docgroup-cpp/#a83c0259d4567db59783728e348688ab3">g_memberGroupInfoMapMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it =<a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a>.find(<a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a>.<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;info = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">        info-&gt;doc = <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">        info-&gt;docFile = e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac6841c6ec8fd7ae6121364e7e1895e94">docFile</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">        info-&gt;docLine = e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a180b5fdd7f3b963e4b0d2c4ea6e0b1b5">docLine</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">        info-&gt;setRefItems(e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac5f693ab011ce4fcc391a3bc95b0307d">sli</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">doc</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">    e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#ad602ba19af5785515ed81790d843ce4c">brief</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/entry/#ad602ba19af5785515ed81790d843ce4c">Entry::brief</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="/web-doxygen/docs/api/classes/entry/#ac02a6c1dd922221351f6de0286d48d77">Entry::doc</a>, <a href="/web-doxygen/docs/api/classes/entry/#ac6841c6ec8fd7ae6121364e7e1895e94">Entry::docFile</a>, <a href="/web-doxygen/docs/api/classes/entry/#a180b5fdd7f3b963e4b0d2c4ea6e0b1b5">Entry::docLine</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/src/docgroup-cpp/#a83c0259d4567db59783728e348688ab3">g_memberGroupInfoMapMutex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>, <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a>, <a href="/web-doxygen/docs/api/classes/entry/#a967db0d8493a46efab87a53d423161eb">Entry::section</a>, <a href="/web-doxygen/docs/api/classes/entry/#ac5f693ab011ce4fcc391a3bc95b0307d">Entry::sli</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>.</p>

</div>
</div>

### appendHeader() {#a9c704ca73aa365da5c61e2b320f8cdd8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocGroup::appendHeader (const char text)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 243 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9c704ca73aa365da5c61e2b320f8cdd8">243</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9c704ca73aa365da5c61e2b320f8cdd8">DocGroup::appendHeader</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a832e0a0b5e7541fb07abef41a8f129a7">m_memberGroupHeader</a> += text;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a832e0a0b5e7541fb07abef41a8f129a7">m_memberGroupHeader</a>.</p>

</div>
</div>

### clearHeader() {#ac8ca201268362991329a26c5725f174b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocGroup::clearHeader ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 238 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8ca201268362991329a26c5725f174b">238</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac8ca201268362991329a26c5725f174b">DocGroup::clearHeader</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a832e0a0b5e7541fb07abef41a8f129a7">m_memberGroupHeader</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a832e0a0b5e7541fb07abef41a8f129a7">m_memberGroupHeader</a>.</p>

</div>
</div>

### close() {#a7610569d96adb6bd19ed159a5f53a26c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocGroup::close (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * e, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int line, bool foundInline, bool implicit=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 35 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7610569d96adb6bd19ed159a5f53a26c">141</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7610569d96adb6bd19ed159a5f53a26c">DocGroup::close</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *e,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> foundInline,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> implicit)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!implicit)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a24b4123e679488c274cb70529786fe35">m_openCount</a> &lt; 1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(fileName,line,</span><span class="doxyHighlightStringLiteral">"unbalanced grouping commands"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a24b4123e679488c274cb70529786fe35">m_openCount</a>--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("==&gt; closeGroup(name=%s,sec=%x,file=%s,line=%d) m_autoGroupStack=%zu\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    qPrint(e-&gt;name),e-&gt;section,qPrint(fileName),line,m_autoGroupStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>!=<a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>) </span><span class="doxyHighlightComment">// end of member group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">      std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/docgroup-cpp/#a83c0259d4567db59783728e348688ab3">g_memberGroupInfoMapMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a>.find(<a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a>.<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>()) </span><span class="doxyHighlightComment">// known group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;info = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">        info-&gt;doc = <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//info-&gt;docFile = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//info-&gt;docLine = line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>=<a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!foundInline)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">      e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a9f7167fc5b369f1fcd343946803efa0d">mGrpId</a>=<a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a611ec017dea1768b7093bea6e4177cba">relates</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("new group id=%d\n",m_memberGroupId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>.empty()) </span><span class="doxyHighlightComment">// end of auto group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/grouping">Grouping</a> grp = <a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// see bug577005: we should not remove the last group for e</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!foundInline &amp;&amp; !e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">groups</a>.empty()) e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">groups</a>.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Removing %s e=%p\n",qPrint(grp-&gt;groupname),e);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!foundInline) <a href="#a4fb2f5bfdd28daeceb60dbb262e08097">initGroupInfo</a>(e);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="/web-doxygen/docs/api/files/src/docgroup-cpp/#a83c0259d4567db59783728e348688ab3">g_memberGroupInfoMapMutex</a>, <a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">Entry::groups</a>, <a href="#a4fb2f5bfdd28daeceb60dbb262e08097">initGroupInfo</a>, <a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>, <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>, <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>, <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>, <a href="#a24b4123e679488c274cb70529786fe35">m_openCount</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a>, <a href="/web-doxygen/docs/api/classes/entry/#a9f7167fc5b369f1fcd343946803efa0d">Entry::mGrpId</a>, <a href="/web-doxygen/docs/api/classes/entry/#a611ec017dea1768b7093bea6e4177cba">Entry::relates</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### enterCompound() {#ae49d781442d3cbceed9b62859b3d4b89}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocGroup::enterCompound (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int line, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae49d781442d3cbceed9b62859b3d4b89">55</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae49d781442d3cbceed9b62859b3d4b89">DocGroup::enterCompound</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>!=<a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(fileName,line,</span><span class="doxyHighlightStringLiteral">"try to put compound {} inside a member group"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>=<a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a> = name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>.find(</span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>=<a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>.left(i); </span><span class="doxyHighlightComment">// strip category (Obj-C)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>=fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("groupEnterCompound(%s)\n",qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>, <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>, <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>, <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>, <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### enterFile() {#af3ca5770267b6242e2b95d15c47a0db9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocGroup::enterFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 30 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 26 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af3ca5770267b6242e2b95d15c47a0db9">26</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af3ca5770267b6242e2b95d15c47a0db9">DocGroup::enterFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">27</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">28</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a24b4123e679488c274cb70529786fe35">m_openCount</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">29</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a> = <a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>=fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>, <a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>, <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>, <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>, <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>, <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a> and <a href="#a24b4123e679488c274cb70529786fe35">m_openCount</a>.</p>

</div>
</div>

### initGroupInfo() {#a4fb2f5bfdd28daeceb60dbb262e08097}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocGroup::initGroupInfo (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * e)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 36 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 190 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4fb2f5bfdd28daeceb60dbb262e08097">190</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4fb2f5bfdd28daeceb60dbb262e08097">DocGroup::initGroupInfo</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *e)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("==&gt; initGroup(id=%d,related=%s,e=%p,#stack=%zu)\n",m_memberGroupId,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//       qPrint(m_memberGroupRelates),(void*)e,m_autoGroupStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">  e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a9f7167fc5b369f1fcd343946803efa0d">mGrpId</a>     = <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">  e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a611ec017dea1768b7093bea6e4177cba">relates</a>    = <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("Appending group %s to %s: count=%zu entry=%p\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//  qPrint(m_autoGroupStack.back().groupname),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//    qPrint(e-&gt;name),e-&gt;groups.size(),(void*)e);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">    e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">groups</a>.emplace_back(<a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>.back());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/entry/#a7a7b0a48faf21641b21124fb8381aa1e">Entry::groups</a>, <a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>, <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>, <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>, <a href="/web-doxygen/docs/api/classes/entry/#a9f7167fc5b369f1fcd343946803efa0d">Entry::mGrpId</a> and <a href="/web-doxygen/docs/api/classes/entry/#a611ec017dea1768b7093bea6e4177cba">Entry::relates</a>.</p>


<p>Referenced by <a href="#a7610569d96adb6bd19ed159a5f53a26c">close</a>.</p>

</div>
</div>

### isEmpty() {#aa6a996a17a2a292dd6f0a2936a1d9910}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DocGroup::isEmpty ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 233 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa6a996a17a2a292dd6f0a2936a1d9910">233</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aa6a996a17a2a292dd6f0a2936a1d9910">DocGroup::isEmpty</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (<a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>==<a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a> and <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>.</p>

</div>
</div>

### leaveCompound() {#a14c0151b77e31de76f50ea2cb9d3e5cb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocGroup::leaveCompound (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, int, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a14c0151b77e31de76f50ea2cb9d3e5cb">77</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a14c0151b77e31de76f50ea2cb9d3e5cb">DocGroup::leaveCompound</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightComment">/* name */</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("groupLeaveCompound(%s)\n",qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//if (m_memberGroupId!=DOX_NOGROUP)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//  warn(fileName,line,"end of compound {} while inside a member group\n",name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>=<a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>, <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>, <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>, <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a> and <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>.</p>

</div>
</div>

### leaveFile() {#a15c99d30cd779d86716ffb2f341db5e1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocGroup::leaveFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int line)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 31 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 36 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15c99d30cd779d86716ffb2f341db5e1">36</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a15c99d30cd779d86716ffb2f341db5e1">DocGroup::leaveFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> line)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//if (m_memberGroupId!=DOX_NOGROUP)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//  warn(fileName,line,"end of file while inside a member group");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//}</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>=<a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(fileName,line,</span><span class="doxyHighlightStringLiteral">"end of file while inside a group"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a24b4123e679488c274cb70529786fe35">m_openCount</a> &gt; 0) </span><span class="doxyHighlightComment">// &lt; 0 is already handled on close call</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(fileName,line,</span><span class="doxyHighlightStringLiteral">"end of file with unbalanced grouping commands"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>, <a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>, <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>, <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>, <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>, <a href="#a24b4123e679488c274cb70529786fe35">m_openCount</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>

</div>
</div>

### open() {#a9cb5ab2169da2f5bf14816e9c10e8290}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DocGroup::open (<a href="/web-doxygen/docs/api/classes/entry">Entry</a> * e, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, int, bool implicit=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 108 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9cb5ab2169da2f5bf14816e9c10e8290">108</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9cb5ab2169da2f5bf14816e9c10e8290">DocGroup::open</a>(<a href="/web-doxygen/docs/api/classes/entry">Entry</a> *e,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> implicit)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!implicit) <a href="#a24b4123e679488c274cb70529786fe35">m_openCount</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("==&gt; openGroup(name=%s,sec=%x) m_autoGroupStack=%zu\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//    qPrint(e-&gt;name),e-&gt;section,m_autoGroupStack.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a967db0d8493a46efab87a53d423161eb">section</a>.isGroupDoc()) </span><span class="doxyHighlightComment">// auto group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>.emplace_back(e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">name</a>,e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a8aeb339b46f8827e0345a917e3302ba3">groupingPri</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// start of a member group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("    membergroup id=%d %s\n",m_memberGroupId,qPrint(m_memberGroupHeader));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>==<a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>) </span><span class="doxyHighlightComment">// no group started yet</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> info = std::make_unique&lt;MemberGroupInfo&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">      info-&gt;header = <a href="#a832e0a0b5e7541fb07abef41a8f129a7">m_memberGroupHeader</a>.stripWhiteSpace();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">      info-&gt;compoundName = <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a> = <a href="#a75ac79ba2e9fa9b9feeaadf6f8567931">findExistingGroup</a>(info.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">        std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/docgroup-cpp/#a83c0259d4567db59783728e348688ab3">g_memberGroupInfoMapMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a>.find(<a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a>.<a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("    use membergroup %d\n",m_memberGroupId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a>.emplace(<a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>,std::move(info));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a> = e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a611ec017dea1768b7093bea6e4177cba">relates</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">      e-&gt;<a href="/web-doxygen/docs/api/classes/entry/#a9f7167fc5b369f1fcd343946803efa0d">mGrpId</a> = <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/membergroup-h/#af4a5ed4e8eab2424cd34974b84562093">DOX_NOGROUP</a>, <a href="/web-doxygen/docs/api/files/src/dir-cpp/#ad0550a128905c4e07b633d437992b002">end</a>, <a href="#a75ac79ba2e9fa9b9feeaadf6f8567931">findExistingGroup</a>, <a href="/web-doxygen/docs/api/files/src/docgroup-cpp/#a83c0259d4567db59783728e348688ab3">g_memberGroupInfoMapMutex</a>, <a href="/web-doxygen/docs/api/classes/entry/#a8aeb339b46f8827e0345a917e3302ba3">Entry::groupingPri</a>, <a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>, <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>, <a href="#a832e0a0b5e7541fb07abef41a8f129a7">m_memberGroupHeader</a>, <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a>, <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>, <a href="#a24b4123e679488c274cb70529786fe35">m_openCount</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a>, <a href="/web-doxygen/docs/api/classes/entry/#a9f7167fc5b369f1fcd343946803efa0d">Entry::mGrpId</a>, <a href="/web-doxygen/docs/api/classes/entry/#a87d6afbe10ea84859ef03b6f046e34d3">Entry::name</a>, <a href="/web-doxygen/docs/api/classes/entry/#a611ec017dea1768b7093bea6e4177cba">Entry::relates</a> and <a href="/web-doxygen/docs/api/classes/entry/#a967db0d8493a46efab87a53d423161eb">Entry::section</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### findExistingGroup() {#a75ac79ba2e9fa9b9feeaadf6f8567931}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocGroup::findExistingGroup (const <a href="/web-doxygen/docs/api/structs/membergroupinfo">MemberGroupInfo</a> * info)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 43 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>, definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75ac79ba2e9fa9b9feeaadf6f8567931">90</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a75ac79ba2e9fa9b9feeaadf6f8567931">DocGroup::findExistingGroup</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/membergroupinfo">MemberGroupInfo</a> *info)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/docgroup-cpp/#a83c0259d4567db59783728e348688ab3">g_memberGroupInfoMapMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("findExistingGroup %s:%s\n",qPrint(info-&gt;header),qPrint(info-&gt;compoundName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[groupId,groupInfo] : <a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>==groupInfo-&gt;compoundName &amp;&amp;  </span><span class="doxyHighlightComment">// same file or scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">        !groupInfo-&gt;header.isEmpty() &amp;&amp;             </span><span class="doxyHighlightComment">// not a nameless group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>(groupInfo-&gt;header,info-&gt;<a href="/web-doxygen/docs/api/structs/membergroupinfo/#ae9064c66b617952b9c0f924ef30ce226">header</a>)==0  </span><span class="doxyHighlightComment">// same header name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">       )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("Found it!\n");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> groupId; </span><span class="doxyHighlightComment">// put the item in this group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ++<a href="/web-doxygen/docs/api/files/src/docgroup-cpp/#a05d0ccc0d7aaedbd3ae467c5d1479658">g_groupId</a>; </span><span class="doxyHighlightComment">// start new group</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docgroup-cpp/#a05d0ccc0d7aaedbd3ae467c5d1479658">g_groupId</a>, <a href="/web-doxygen/docs/api/files/src/docgroup-cpp/#a83c0259d4567db59783728e348688ab3">g_memberGroupInfoMapMutex</a>, <a href="/web-doxygen/docs/api/structs/membergroupinfo/#ae9064c66b617952b9c0f924ef30ce226">MemberGroupInfo::header</a>, <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a866fad781ec64b6a1acc904f31756124">Doxygen::memberGroupInfoMap</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a773d5813108052583cde43cc8517893d">qstricmp</a>.</p>


<p>Referenced by <a href="#a9cb5ab2169da2f5bf14816e9c10e8290">open</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_autoGroupStack {#aa1e9c49f1c3a008979b7bc3a0c01e189}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Grouping&gt; DocGroup::m_autoGroupStack</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">49</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;Grouping&gt; <a href="#aa1e9c49f1c3a008979b7bc3a0c01e189">m_autoGroupStack</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a7610569d96adb6bd19ed159a5f53a26c">close</a>, <a href="#af3ca5770267b6242e2b95d15c47a0db9">enterFile</a>, <a href="#a4fb2f5bfdd28daeceb60dbb262e08097">initGroupInfo</a>, <a href="#a15c99d30cd779d86716ffb2f341db5e1">leaveFile</a> and <a href="#a9cb5ab2169da2f5bf14816e9c10e8290">open</a>.</p>

</div>
</div>

### m\_compoundName {#acc0bea19eb724c39f535d47c90af7d0e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocGroup::m_compoundName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acc0bea19eb724c39f535d47c90af7d0e">50</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>         <a href="#acc0bea19eb724c39f535d47c90af7d0e">m_compoundName</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ae49d781442d3cbceed9b62859b3d4b89">enterCompound</a>, <a href="#af3ca5770267b6242e2b95d15c47a0db9">enterFile</a>, <a href="#a75ac79ba2e9fa9b9feeaadf6f8567931">findExistingGroup</a>, <a href="#a14c0151b77e31de76f50ea2cb9d3e5cb">leaveCompound</a> and <a href="#a9cb5ab2169da2f5bf14816e9c10e8290">open</a>.</p>

</div>
</div>

### m\_memberGroupDocs {#aaf85b64bbe080e4fb43b88889cefd2ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocGroup::m_memberGroupDocs</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaf85b64bbe080e4fb43b88889cefd2ce">48</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>         <a href="#aaf85b64bbe080e4fb43b88889cefd2ce">m_memberGroupDocs</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a9b79815ce3108572e1405da479f34e3d">addDocs</a>, <a href="#a7610569d96adb6bd19ed159a5f53a26c">close</a>, <a href="#ae49d781442d3cbceed9b62859b3d4b89">enterCompound</a>, <a href="#af3ca5770267b6242e2b95d15c47a0db9">enterFile</a>, <a href="#a14c0151b77e31de76f50ea2cb9d3e5cb">leaveCompound</a> and <a href="#a15c99d30cd779d86716ffb2f341db5e1">leaveFile</a>.</p>

</div>
</div>

### m\_memberGroupHeader {#a832e0a0b5e7541fb07abef41a8f129a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocGroup::m_memberGroupHeader</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 45 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a832e0a0b5e7541fb07abef41a8f129a7">45</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>         <a href="#a832e0a0b5e7541fb07abef41a8f129a7">m_memberGroupHeader</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a9c704ca73aa365da5c61e2b320f8cdd8">appendHeader</a>, <a href="#ac8ca201268362991329a26c5725f174b">clearHeader</a> and <a href="#a9cb5ab2169da2f5bf14816e9c10e8290">open</a>.</p>

</div>
</div>

### m\_memberGroupId {#a74693a9a5eccbc89f1d7935f23314c3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocGroup::m_memberGroupId = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a74693a9a5eccbc89f1d7935f23314c3b">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">              <a href="#a74693a9a5eccbc89f1d7935f23314c3b">m_memberGroupId</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a9b79815ce3108572e1405da479f34e3d">addDocs</a>, <a href="#a7610569d96adb6bd19ed159a5f53a26c">close</a>, <a href="#ae49d781442d3cbceed9b62859b3d4b89">enterCompound</a>, <a href="#af3ca5770267b6242e2b95d15c47a0db9">enterFile</a>, <a href="#a4fb2f5bfdd28daeceb60dbb262e08097">initGroupInfo</a>, <a href="#aa6a996a17a2a292dd6f0a2936a1d9910">isEmpty</a>, <a href="#a14c0151b77e31de76f50ea2cb9d3e5cb">leaveCompound</a>, <a href="#a15c99d30cd779d86716ffb2f341db5e1">leaveFile</a> and <a href="#a9cb5ab2169da2f5bf14816e9c10e8290">open</a>.</p>

</div>
</div>

### m\_memberGroupRelates {#a87c94c1d206b35937f88e458c4214aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DocGroup::m_memberGroupRelates</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87c94c1d206b35937f88e458c4214aa9">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>         <a href="#a87c94c1d206b35937f88e458c4214aa9">m_memberGroupRelates</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a7610569d96adb6bd19ed159a5f53a26c">close</a>, <a href="#ae49d781442d3cbceed9b62859b3d4b89">enterCompound</a>, <a href="#af3ca5770267b6242e2b95d15c47a0db9">enterFile</a>, <a href="#a4fb2f5bfdd28daeceb60dbb262e08097">initGroupInfo</a>, <a href="#a14c0151b77e31de76f50ea2cb9d3e5cb">leaveCompound</a>, <a href="#a15c99d30cd779d86716ffb2f341db5e1">leaveFile</a> and <a href="#a9cb5ab2169da2f5bf14816e9c10e8290">open</a>.</p>

</div>
</div>

### m\_openCount {#a24b4123e679488c274cb70529786fe35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int DocGroup::m_openCount = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24b4123e679488c274cb70529786fe35">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">              <a href="#a24b4123e679488c274cb70529786fe35">m_openCount</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a7610569d96adb6bd19ed159a5f53a26c">close</a>, <a href="#af3ca5770267b6242e2b95d15c47a0db9">enterFile</a>, <a href="#a15c99d30cd779d86716ffb2f341db5e1">leaveFile</a> and <a href="#a9cb5ab2169da2f5bf14816e9c10e8290">open</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/docgroup-cpp">docgroup.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/docgroup-h">docgroup.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
