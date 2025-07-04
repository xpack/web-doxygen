---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/sitemap-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `sitemap.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;algorithm&gt;
#include &lt;memory&gt;
#include &lt;string.h&gt;
#include &lt;vector&gt;
#include &lt;cassert&gt;
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/sitemap-h">sitemap.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "version.h"
#include "<a href="/web-doxygen/docs/api/files/src/containers-h">containers.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/sitemap/private">Private</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/crawlmap/private">Private</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#accfbeaf0954a9bf961a17b0c7e243763">makeFileName</a> (const QCString &amp;withoutExtension)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1ed13b7ecf64ac700cd4249371fb1165">makeRef</a> (const QCString &amp;withoutExtension, const QCString &amp;anchor)</td>
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

## Functions

### makeFileName() {#accfbeaf0954a9bf961a17b0c7e243763}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString makeFileName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; withoutExtension)</td>
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



<p>Definition at line 170 of file <a href="/web-doxygen/docs/api/files/src/sitemap-cpp">sitemap.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#accfbeaf0954a9bf961a17b0c7e243763">170</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#accfbeaf0954a9bf961a17b0c7e243763">makeFileName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; withoutExtension)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result=withoutExtension;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!result.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0)==</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// relative URL -&gt; strip marker</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">      result=result.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// add specified HTML extension</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>.</p>


<p>Referenced by <a href="#a1ed13b7ecf64ac700cd4249371fb1165">makeRef</a>.</p>

</div>
</div>

### makeRef() {#a1ed13b7ecf64ac700cd4249371fb1165}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString makeRef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; withoutExtension, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</td>
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



<p>Definition at line 187 of file <a href="/web-doxygen/docs/api/files/src/sitemap-cpp">sitemap.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1ed13b7ecf64ac700cd4249371fb1165">187</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a1ed13b7ecf64ac700cd4249371fb1165">makeRef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; withoutExtension, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (withoutExtension.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = <a href="#accfbeaf0954a9bf961a17b0c7e243763">makeFileName</a>(withoutExtension);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result+</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">+anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#accfbeaf0954a9bf961a17b0c7e243763">makeFileName</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
