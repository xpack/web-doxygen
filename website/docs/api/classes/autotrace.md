---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/autotrace
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `AutoTrace` Class Reference

<p>Helper class to trace an entry statement at creation and another one at destruction. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class AutoTrace { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/trace-h">src/trace.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a232c02242ad1c8822d71ce108ee0c084">AutoTrace</a> (spdlog::source_loc loc)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemNoTypeNameTemplate" colspan="2" align="left" valign="top"><a href="#a121e03a3e610d9d91e97aca3aee4aef3">AutoTrace</a> (spdlog::source_loc loc, const std::string &amp;fmt, Args &amp;&amp;...args)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63ff9e892c88faa5df232fb42a551d45">~AutoTrace</a> ()</td>
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

<tr class="doxyMemberIndexTemplate">
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#acfa6eaddb2b7bfd6bfca73321b80e8ba">add</a> (spdlog::source_loc loc, const std::string &amp;fmt, Args &amp;&amp;...args)</td>
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
<td class="doxyMemberIndexTemplate" colspan="2"><div>template &lt;typename... Args&gt;</div></td>
</tr>
<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemTypeTemplate" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemNameTemplate" align="left" valign="top"><a href="#aec8bc479a6ca67cab45c03d776851435">setExit</a> (spdlog::source_loc loc, const std::string &amp;msg, Args &amp;&amp;...args)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">spdlog::source_loc</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f60f88ddaf899f795b0b7e943d16577">m_loc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a21d601254adb64f3273f2bb09a67d">m_exitMessage</a></td>
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

<p>Helper class to trace an entry statement at creation and another one at destruction.</p>

<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### AutoTrace() {#a232c02242ad1c8822d71ce108ee0c084}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AutoTrace::AutoTrace (spdlog::source_loc loc)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a232c02242ad1c8822d71ce108ee0c084">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#a232c02242ad1c8822d71ce108ee0c084">AutoTrace</a>(spdlog::source_loc loc) : <a href="#a6f60f88ddaf899f795b0b7e943d16577">m_loc</a>(loc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g_tracer</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g_tracer</a>-&gt;log(<a href="#a6f60f88ddaf899f795b0b7e943d16577">m_loc</a>,spdlog::level::trace,</span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g&#95;tracer</a> and <a href="#a6f60f88ddaf899f795b0b7e943d16577">m&#95;loc</a>.
</div>
</div>

### AutoTrace() {#a121e03a3e610d9d91e97aca3aee4aef3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AutoTrace::AutoTrace (spdlog::source_loc loc, const std::string &amp; fmt, Args &amp;&amp;... args)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel explicit">explicit</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a121e03a3e610d9d91e97aca3aee4aef3">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">explicit</span><span class="doxyHighlight"> <a href="#a121e03a3e610d9d91e97aca3aee4aef3">AutoTrace</a>(spdlog::source_loc loc,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, Args&amp;&amp;...args) : <a href="#a6f60f88ddaf899f795b0b7e943d16577">m_loc</a>(loc)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g_tracer</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g_tracer</a>-&gt;log(<a href="#a6f60f88ddaf899f795b0b7e943d16577">m_loc</a>,spdlog::level::trace,</span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g_tracer</a>-&gt;log(<a href="#a6f60f88ddaf899f795b0b7e943d16577">m_loc</a>,spdlog::level::trace,fmt::runtime(</span><span class="doxyHighlightStringLiteral">"&gt; "</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>),std::forward&lt;Args&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g&#95;tracer</a> and <a href="#a6f60f88ddaf899f795b0b7e943d16577">m&#95;loc</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### ~AutoTrace() {#a63ff9e892c88faa5df232fb42a551d45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AutoTrace::~AutoTrace ()</td>
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


<p>Definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a63ff9e892c88faa5df232fb42a551d45">107</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#a63ff9e892c88faa5df232fb42a551d45">~AutoTrace</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g_tracer</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ac2a21d601254adb64f3273f2bb09a67d">m_exitMessage</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g_tracer</a>-&gt;log(<a href="#a6f60f88ddaf899f795b0b7e943d16577">m_loc</a>,spdlog::level::trace,</span><span class="doxyHighlightStringLiteral">"&lt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g_tracer</a>-&gt;log(<a href="#a6f60f88ddaf899f795b0b7e943d16577">m_loc</a>,spdlog::level::trace,</span><span class="doxyHighlightStringLiteral">"&lt; "</span><span class="doxyHighlight">+<a href="#ac2a21d601254adb64f3273f2bb09a67d">m_exitMessage</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g&#95;tracer</a>, <a href="#ac2a21d601254adb64f3273f2bb09a67d">m&#95;exitMessage</a> and <a href="#a6f60f88ddaf899f795b0b7e943d16577">m&#95;loc</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### add() {#acfa6eaddb2b7bfd6bfca73321b80e8ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AutoTrace::add (spdlog::source_loc loc, const std::string &amp; fmt, Args &amp;&amp;... args)</td>
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


<p>Definition at line 124 of file <a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acfa6eaddb2b7bfd6bfca73321b80e8ba">124</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acfa6eaddb2b7bfd6bfca73321b80e8ba">add</a>(spdlog::source_loc loc,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>, Args&amp;&amp;...args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g_tracer</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g_tracer</a>-&gt;log(loc,spdlog::level::trace,fmt::runtime(</span><span class="doxyHighlightStringLiteral">": "</span><span class="doxyHighlight">+<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>),std::forward&lt;Args&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/trace-h/#a5cba80b7682f3c7fb87a3a34c9b9cef8">g&#95;tracer</a>.
</div>
</div>

### setExit() {#aec8bc479a6ca67cab45c03d776851435}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<div class="doxyMemberTemplate">template &lt;typename... Args&gt;</div>
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void AutoTrace::setExit (spdlog::source_loc loc, const std::string &amp; msg, Args &amp;&amp;... args)</td>
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


<p>Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aec8bc479a6ca67cab45c03d776851435">133</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aec8bc479a6ca67cab45c03d776851435">setExit</a>(spdlog::source_loc loc,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">                 </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>,Args&amp;&amp;...args)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a6f60f88ddaf899f795b0b7e943d16577">m_loc</a> = loc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac2a21d601254adb64f3273f2bb09a67d">m_exitMessage</a> = fmt::format(fmt::runtime(<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>),std::forward&lt;Args&gt;(args)...);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#ac2a21d601254adb64f3273f2bb09a67d">m&#95;exitMessage</a>, <a href="#a6f60f88ddaf899f795b0b7e943d16577">m&#95;loc</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;exitMessage {#ac2a21d601254adb64f3273f2bb09a67d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string AutoTrace::m_exitMessage</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac2a21d601254adb64f3273f2bb09a67d">141</a></span><span class="doxyLineContent"><span class="doxyHighlight">   std::string <a href="#ac2a21d601254adb64f3273f2bb09a67d">m_exitMessage</a>;</span></span></div>

</div>


Referenced by <a href="#aec8bc479a6ca67cab45c03d776851435">setExit</a> and <a href="#a63ff9e892c88faa5df232fb42a551d45">~AutoTrace</a>.
</div>
</div>

### m&#95;loc {#a6f60f88ddaf899f795b0b7e943d16577}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">spdlog::source_loc AutoTrace::m_loc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f60f88ddaf899f795b0b7e943d16577">140</a></span><span class="doxyLineContent"><span class="doxyHighlight">   spdlog::source_loc <a href="#a6f60f88ddaf899f795b0b7e943d16577">m_loc</a>;</span></span></div>

</div>


Referenced by <a href="#a232c02242ad1c8822d71ce108ee0c084">AutoTrace</a>, <a href="#a121e03a3e610d9d91e97aca3aee4aef3">AutoTrace</a>, <a href="#aec8bc479a6ca67cab45c03d776851435">setExit</a> and <a href="#a63ff9e892c88faa5df232fb42a551d45">~AutoTrace</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
