---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/variablecontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `VariableContext` Class Reference



## Declaration

<div class="doxyDeclaration">
class VariableContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">src/scopedtypevariant.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acaf108f97a14c38cfcc698654e947e7d">Scope</a> = std::unordered_map&lt; std::string, <a href="/web-doxygen/docs/api/classes/scopedtypevariant">ScopedTypeVariant</a> &gt;</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1d858d3ad4778e79ac69a021474edab">pushScope</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a648ebfb9146a61b70dffe684aec77940">popScope</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37579e37d7d730884861f71a1b9f0439">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af762830da74924aa08900310e554e253">clearExceptGlobal</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ecf50e05c0af1f854d21a2d0574dbcf">addVariable</a> (const QCString &amp;name, ScopedTypeVariant stv)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/scopedtypevariant">ScopedTypeVariant</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa4cfe2b318b52c33b4e28b5840275d85">findVariable</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3b01492065b015f3b275ea2b9d02d2be">atGlobalScope</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#acaf108f97a14c38cfcc698654e947e7d">Scope</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1d4e3ee5731c630df8133604b05b0213">m_globalScope</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="#acaf108f97a14c38cfcc698654e947e7d">Scope</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a></td>
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



<p>Represents a stack of variable to class mappings as found in the code. Each scope is enclosed in <a href="#ae1d858d3ad4778e79ac69a021474edab">pushScope()</a> and <a href="#a648ebfb9146a61b70dffe684aec77940">popScope()</a> calls. Variables are added by calling addVariables() and one can search for variable using <a href="#aa4cfe2b318b52c33b4e28b5840275d85">findVariable()</a>.</p>


<p>Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Scope {#acaf108f97a14c38cfcc698654e947e7d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using VariableContext::Scope =  std::unordered_map&lt;std::string,ScopedTypeVariant&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acaf108f97a14c38cfcc698654e947e7d">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#acaf108f97a14c38cfcc698654e947e7d">Scope</a> = std::unordered_map&lt;std::string,ScopedTypeVariant&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addVariable() {#a8ecf50e05c0af1f854d21a2d0574dbcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VariableContext::addVariable (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, <a href="/web-doxygen/docs/api/classes/scopedtypevariant">ScopedTypeVariant</a> stv)</td>
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



<p>Definition at line 99 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ecf50e05c0af1f854d21a2d0574dbcf">99</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8ecf50e05c0af1f854d21a2d0574dbcf">addVariable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,<a href="/web-doxygen/docs/api/classes/scopedtypevariant">ScopedTypeVariant</a> stv)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#acaf108f97a14c38cfcc698654e947e7d">Scope</a> *scope = <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.empty() ? &amp;<a href="#a1d4e3ee5731c630df8133604b05b0213">m_globalScope</a> : &amp;<a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">      scope-&gt;emplace(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),std::move(stv)); </span><span class="doxyHighlightComment">// add it to a list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a1d4e3ee5731c630df8133604b05b0213">m_globalScope</a>, <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### atGlobalScope() {#a3b01492065b015f3b275ea2b9d02d2be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VariableContext::atGlobalScope ()</td>
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



<p>Definition at line 129 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3b01492065b015f3b275ea2b9d02d2be">129</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a3b01492065b015f3b275ea2b9d02d2be">atGlobalScope</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.empty(); }</span></span></div>

</div>


<p>Reference <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.</p>

</div>
</div>

### clear() {#a37579e37d7d730884861f71a1b9f0439}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VariableContext::clear ()</td>
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



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a37579e37d7d730884861f71a1b9f0439">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a37579e37d7d730884861f71a1b9f0439">clear</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a1d4e3ee5731c630df8133604b05b0213">m_globalScope</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a1d4e3ee5731c630df8133604b05b0213">m_globalScope</a> and <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.</p>

</div>
</div>

### clearExceptGlobal() {#af762830da74924aa08900310e554e253}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VariableContext::clearExceptGlobal ()</td>
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



<p>Definition at line 95 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af762830da74924aa08900310e554e253">95</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af762830da74924aa08900310e554e253">clearExceptGlobal</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.</p>

</div>
</div>

### findVariable() {#aa4cfe2b318b52c33b4e28b5840275d85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ScopedTypeVariant * VariableContext::findVariable (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa4cfe2b318b52c33b4e28b5840275d85">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/scopedtypevariant">ScopedTypeVariant</a> *<a href="#aa4cfe2b318b52c33b4e28b5840275d85">findVariable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/scopedtypevariant">ScopedTypeVariant</a> *result = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (name.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// search from inner to outer scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = std::rbegin(<a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (it != std::rend(<a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it2 = it-&gt;find(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it2 != std::end(*it))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">          result = &amp;it2-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">        ++it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// nothing found -&gt; also try the global scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it2 = <a href="#a1d4e3ee5731c630df8133604b05b0213">m_globalScope</a>.find(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it2 != <a href="#a1d4e3ee5731c630df8133604b05b0213">m_globalScope</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">        result = &amp;it2-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a1d4e3ee5731c630df8133604b05b0213">m_globalScope</a>, <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>

</div>
</div>

### popScope() {#a648ebfb9146a61b70dffe684aec77940}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VariableContext::popScope ()</td>
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



<p>Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a648ebfb9146a61b70dffe684aec77940">83</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a648ebfb9146a61b70dffe684aec77940">popScope</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.</p>

</div>
</div>

### pushScope() {#ae1d858d3ad4778e79ac69a021474edab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VariableContext::pushScope ()</td>
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



<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae1d858d3ad4778e79ac69a021474edab">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae1d858d3ad4778e79ac69a021474edab">pushScope</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.emplace_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_globalScope {#a1d4e3ee5731c630df8133604b05b0213}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Scope VariableContext::m_globalScope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 132 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1d4e3ee5731c630df8133604b05b0213">132</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#acaf108f97a14c38cfcc698654e947e7d">Scope</a>              <a href="#a1d4e3ee5731c630df8133604b05b0213">m_globalScope</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a8ecf50e05c0af1f854d21a2d0574dbcf">addVariable</a>, <a href="#a37579e37d7d730884861f71a1b9f0439">clear</a> and <a href="#aa4cfe2b318b52c33b4e28b5840275d85">findVariable</a>.</p>

</div>
</div>

### m\_scopes {#a63532cca1d69eba2ba0a0187a46ea164}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Scope&gt; VariableContext::m_scopes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a63532cca1d69eba2ba0a0187a46ea164">133</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;Scope&gt; <a href="#a63532cca1d69eba2ba0a0187a46ea164">m_scopes</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a8ecf50e05c0af1f854d21a2d0574dbcf">addVariable</a>, <a href="#a3b01492065b015f3b275ea2b9d02d2be">atGlobalScope</a>, <a href="#a37579e37d7d730884861f71a1b9f0439">clear</a>, <a href="#af762830da74924aa08900310e554e253">clearExceptGlobal</a>, <a href="#aa4cfe2b318b52c33b4e28b5840275d85">findVariable</a>, <a href="#a648ebfb9146a61b70dffe684aec77940">popScope</a> and <a href="#ae1d858d3ad4778e79ac69a021474edab">pushScope</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
