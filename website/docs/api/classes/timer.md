---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/timer
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Timer` Class Reference



## Declaration

<div class="doxyDeclaration">
class Timer { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a8b5272198d029779dc9302a54305a8">start</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9b89127c8224e7fb787da4f11ef8d364">elapsedTimeS</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::chrono::time_point&lt; std::chrono::steady_clock &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4d1bd480e339ce43c46e0ccbad7fe0b6">m_startTime</a></td>
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


<p>Definition at line 176 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>

<div class="doxySectionDef">

## Public Member Functions

### elapsedTimeS() {#a9b89127c8224e7fb787da4f11ef8d364}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double Timer::elapsedTimeS ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/debug-cpp/#l00183">183</a> of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9b89127c8224e7fb787da4f11ef8d364">183</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> <a href="#a9b89127c8224e7fb787da4f11ef8d364">elapsedTimeS</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">              std::chrono::duration_cast&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">                  std::chrono::microseconds&gt;(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">                  std::chrono::steady_clock::now() - <a href="#a4d1bd480e339ce43c46e0ccbad7fe0b6">m_startTime</a>).count()) / 1000000.0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a4d1bd480e339ce43c46e0ccbad7fe0b6">m&#95;startTime</a>.
</div>
</div>

### start() {#a3a8b5272198d029779dc9302a54305a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Timer::start ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/debug-cpp/#l00179">179</a> of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a8b5272198d029779dc9302a54305a8">179</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3a8b5272198d029779dc9302a54305a8">start</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a4d1bd480e339ce43c46e0ccbad7fe0b6">m_startTime</a> = std::chrono::steady_clock::now();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a4d1bd480e339ce43c46e0ccbad7fe0b6">m&#95;startTime</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;startTime {#a4d1bd480e339ce43c46e0ccbad7fe0b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::chrono::time_point&lt;std::chrono::steady_clock&gt; Timer::m_startTime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/debug-cpp/#l00191">191</a> of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4d1bd480e339ce43c46e0ccbad7fe0b6">191</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::chrono::time_point&lt;std::chrono::steady_clock&gt; <a href="#a4d1bd480e339ce43c46e0ccbad7fe0b6">m_startTime</a>;</span></span></div>

</div>


Referenced by <a href="#a9b89127c8224e7fb787da4f11ef8d364">elapsedTimeS</a> and <a href="#a3a8b5272198d029779dc9302a54305a8">start</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
