---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/debug-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `debug.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdarg.h&gt;
#include &lt;algorithm&gt;
#include &lt;stdio.h&gt;
#include &lt;map&gt;
#include &lt;string&gt;
#include &lt;chrono&gt;
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/timer">Timer</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af99cca26392cb3f3834262a20381e399">asciiToLower</a> (char in)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint64_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec8bf37b3431219d99c8dabf8961c73b">labelToEnumValue</a> (const QCString &amp;l)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::map&lt; std::string, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7d">Debug::DebugMask</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab76040705893c60ac02bcca04c9aba5f">s_labels</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static FILE *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fa8fc957f0879ebc8b79c19fe3557f4">g_debugFile</a> = stdout</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/timer">Timer</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e85396212eb9f0ea3bc706daf150cdd">g_runningTime</a></td>
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

### asciiToLower() {#af99cca26392cb3f3834262a20381e399}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char asciiToLower (char in)</td>
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



<p>Definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af99cca26392cb3f3834262a20381e399">89</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="#af99cca26392cb3f3834262a20381e399">asciiToLower</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> in) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (in &lt;= </span><span class="doxyHighlightCharLiteral">'Z'</span><span class="doxyHighlight"> &amp;&amp; in &gt;= </span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> in - (</span><span class="doxyHighlightCharLiteral">'Z'</span><span class="doxyHighlight"> - </span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> in;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a> and <a href="#aec8bf37b3431219d99c8dabf8961c73b">labelToEnumValue</a>.</p>

</div>
</div>

### labelToEnumValue() {#aec8bf37b3431219d99c8dabf8961c73b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint64_t labelToEnumValue (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; l)</td>
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



<p>Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aec8bf37b3431219d99c8dabf8961c73b">95</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> uint64_t <a href="#aec8bf37b3431219d99c8dabf8961c73b">labelToEnumValue</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;l)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string s = l.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  std::transform(s.begin(),s.end(),s.begin(),<a href="#af99cca26392cb3f3834262a20381e399">asciiToLower</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ab76040705893c60ac02bcca04c9aba5f">s_labels</a>.find(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (it!=<a href="#ab76040705893c60ac02bcca04c9aba5f">s_labels</a>.end()) ? it-&gt;second : <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa1079d9a4345660aa3e283c322fd12f3">Debug::DebugMask::Quiet</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#af99cca26392cb3f3834262a20381e399">asciiToLower</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa1079d9a4345660aa3e283c322fd12f3">Debug::Quiet</a>, <a href="#ab76040705893c60ac02bcca04c9aba5f">s_labels</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/debug/#ae37b8f08c49a5d316b436e1849dffb9c">Debug::setFlagStr</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### g\_debugFile {#a0fa8fc957f0879ebc8b79c19fe3557f4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FILE* g_debugFile = stdout</td>
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



<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0fa8fc957f0879ebc8b79c19fe3557f4">76</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> FILE *<a href="#a0fa8fc957f0879ebc8b79c19fe3557f4">g_debugFile</a> = stdout;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/debug/#af9d002a2d503fa172cc502ccb1198f8c">Debug::print_</a> and <a href="/web-doxygen/docs/api/classes/debug/#ae37b8f08c49a5d316b436e1849dffb9c">Debug::setFlagStr</a>.</p>

</div>
</div>

### g\_runningTime {#a3e85396212eb9f0ea3bc706daf150cdd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Timer g_runningTime</td>
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



<p>Definition at line 194 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3e85396212eb9f0ea3bc706daf150cdd">194</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/timer">Timer</a> <a href="#a3e85396212eb9f0ea3bc706daf150cdd">g_runningTime</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/debug/#accc1a68a6e51b015caee0ab90ddb6e87">Debug::elapsedTime</a> and <a href="/web-doxygen/docs/api/classes/debug/#ad34e8ad3d814a4cf8b29ce98fd7a96f5">Debug::startTimer</a>.</p>

</div>
</div>

### s\_labels {#ab76040705893c60ac02bcca04c9aba5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt; std::string, Debug::DebugMask &gt; s_labels</td>
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



<p>Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/debug-cpp">debug.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab76040705893c60ac02bcca04c9aba5f">29</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::map&lt; std::string, Debug::DebugMask &gt; <a href="#ab76040705893c60ac02bcca04c9aba5f">s_labels</a> =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">30</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">31</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"preprocessor"</span><span class="doxyHighlight">,       <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daec63880706f2286cd7ca9057bf407e2f">Debug::Preprocessor</a>       },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">32</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"nolineno"</span><span class="doxyHighlight">,           <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da1e4864dcfb33d0155b7c8b2506fa7c62">Debug::NoLineNo</a>           },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">33</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"commentcnv"</span><span class="doxyHighlight">,         <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daf158610d0a0e6dd08ec7cab215168fa5">Debug::CommentCnv</a>         },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"commentscan"</span><span class="doxyHighlight">,        <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dafeb3ede15e44e56c363351c25efd2504">Debug::CommentScan</a>        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"formula"</span><span class="doxyHighlight">,            <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daaa4539102b2cba0227fb56f4fd90e997">Debug::Formula</a>            },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"printtree"</span><span class="doxyHighlight">,          <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da92b8cea26e6d5e2a5d3d04b63686bb2b">Debug::PrintTree</a>          },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"time"</span><span class="doxyHighlight">,               <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da9cbd5d3516ffd3fe86238779edb2f7c5">Debug::Time</a>               },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"extcmd"</span><span class="doxyHighlight">,             <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da8dbe64e9ab683833c1ea7252649058a3">Debug::ExtCmd</a>             },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"markdown"</span><span class="doxyHighlight">,           <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4e7a964cec1d0423c74ab7045c1f6f6d">Debug::Markdown</a>           },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"filteroutput"</span><span class="doxyHighlight">,       <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5e47cf9df9552fe30480288b70288d72">Debug::FilterOutput</a>       },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"plantuml"</span><span class="doxyHighlight">,           <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa8db983f0b8626bee7c3f012c8b5d566">Debug::Plantuml</a>           },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"fortranfixed2free"</span><span class="doxyHighlight">,  <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dafae1c4a49dc51808b18e3091bbc85e28">Debug::FortranFixed2Free</a>  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"cite"</span><span class="doxyHighlight">,               <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da724abc65281c2d47105ebf8a31d6c397">Debug::Cite</a>               },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"rtf"</span><span class="doxyHighlight">,                <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da19caf08ac865a4bd2241cbdf9d310ecc">Debug::Rtf</a>                },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"qhp"</span><span class="doxyHighlight">,                <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dad9460df52aaeff184624ce6b5a5360e2">Debug::Qhp</a>                },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"tag"</span><span class="doxyHighlight">,                <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>                },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"alias"</span><span class="doxyHighlight">,              <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da30a6935f9c8708d6bba6a36006c376dc">Debug::Alias</a>              },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"entries"</span><span class="doxyHighlight">,            <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dad9c34d45743a5b17700d8c98e1fd010c">Debug::Entries</a>            },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"sections"</span><span class="doxyHighlight">,           <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da9087db4bb32e89ea9a871a7dd6e69158">Debug::Sections</a>           },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"stderr"</span><span class="doxyHighlight">,             <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa3108a5100f8de51389976d96fc76550">Debug::Stderr</a>             },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"layout"</span><span class="doxyHighlight">,             <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4baad9612a909a947fea3f6d97fb29a5">Debug::Layout</a>             },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex"</span><span class="doxyHighlight">,                <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da0c1d42bd6b09e5427669a49f082e823b">Debug::Lex</a>                },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:code"</span><span class="doxyHighlight">,           <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da65c59a01c514027443cf0634e69c7712">Debug::Lex_code</a>           },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:commentcnv"</span><span class="doxyHighlight">,     <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daaec9b8e3dfee836d4621c2cca9514037">Debug::Lex_commentcnv</a>     },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:commentscan"</span><span class="doxyHighlight">,    <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dacfc05ad911e454b3dfde1212b69d28ce">Debug::Lex_commentscan</a>    },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:configimpl"</span><span class="doxyHighlight">,     <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dadd2524ea0de5e1eadcd197a6f5925a83">Debug::Lex_configimpl</a>     },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:constexp"</span><span class="doxyHighlight">,       <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dabb929f64e4a2c8c41e79fa5bc4d763f3">Debug::Lex_constexp</a>       },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:declinfo"</span><span class="doxyHighlight">,       <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4fb818b908e028c1bc463472e3959dba">Debug::Lex_declinfo</a>       },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:defargs"</span><span class="doxyHighlight">,        <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da2dbbd7c420176dca999210d256d1e223">Debug::Lex_defargs</a>        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:doctokenizer"</span><span class="doxyHighlight">,   <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da099ed01f3be5fd04d8e8f53a4b8b808c">Debug::Lex_doctokenizer</a>   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:fortrancode"</span><span class="doxyHighlight">,    <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dac254e604d7117b1b02b7a35d96f61714">Debug::Lex_fortrancode</a>    },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:fortranscanner"</span><span class="doxyHighlight">, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da091a33c7c46121c2ed6ca91caf90462e">Debug::Lex_fortranscanner</a> },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:lexcode"</span><span class="doxyHighlight">,        <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dad74b6afb516bda607c1febfb36bcf723">Debug::Lex_lexcode</a>        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:lexscanner"</span><span class="doxyHighlight">,     <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5da3b4321d165769eecb01603fb71511">Debug::Lex_lexscanner</a>     },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:pre"</span><span class="doxyHighlight">,            <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da2a1f7084203db5870663c8778d215ad8">Debug::Lex_pre</a>            },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:pycode"</span><span class="doxyHighlight">,         <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da391da68ca9444e86fc0c86e3b45114da">Debug::Lex_pycode</a>         },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:pyscanner"</span><span class="doxyHighlight">,      <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da6b1a5b26169c22256dfd5a35fc519d4c">Debug::Lex_pyscanner</a>      },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:scanner"</span><span class="doxyHighlight">,        <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daece643cdd58630e1f75bae52dd14fda7">Debug::Lex_scanner</a>        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:sqlcode"</span><span class="doxyHighlight">,        <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da646fb0e06016ef0b89e2c998a2d4f510">Debug::Lex_sqlcode</a>        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:vhdlcode"</span><span class="doxyHighlight">,       <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dab650a956b73462ec1541f0c2e548d3c2">Debug::Lex_vhdlcode</a>       },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:xml"</span><span class="doxyHighlight">,            <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Debug::Lex_xml</a>            },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"lex:xmlcode"</span><span class="doxyHighlight">,        <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7dabe298d28c7ee8dde51e2ab7e49c864ed">Debug::Lex_xmlcode</a>        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="#aec8bf37b3431219d99c8dabf8961c73b">labelToEnumValue</a> and <a href="/web-doxygen/docs/api/classes/debug/#a2d8ac411144a380f838a1766118c6a03">Debug::printFlags</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
