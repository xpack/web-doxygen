---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/textgeneratorolimpl
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `TextGeneratorOLImpl` Class Reference

<p>Implements <a href="/web-doxygen/docs/api/classes/textgeneratorintf">TextGeneratorIntf</a> for an OutputDocInterface stream. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class TextGeneratorOLImpl { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/util-h">src/util.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/textgeneratorintf">TextGeneratorIntf</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Abstract interface for a hyperlinked text fragment. <a href="/web-doxygen/docs/api/classes/textgeneratorintf/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37f94d1d2f7ce361ed9a652c1e916c77">TextGeneratorOLImpl</a> (OutputList &amp;ol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#add80058c326a14b48f31afbdd73d2402">writeString</a> (std::string_view s, bool keepSpaces) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c90aa4a3d435a4db351adb94ac62128">writeBreak</a> (int indent) const override</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abd5e4e731db512c6e98795c56d323f30">writeLink</a> (const QCString &amp;extRef, const QCString &amp;file, const QCString &amp;anchor, std::string_view text) const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a></td>
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

<p>Implements <a href="/web-doxygen/docs/api/classes/textgeneratorintf">TextGeneratorIntf</a> for an OutputDocInterface stream.</p>

<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### TextGeneratorOLImpl() {#a37f94d1d2f7ce361ed9a652c1e916c77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TextGeneratorOLImpl::TextGeneratorOLImpl (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 79 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>, definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/util-cpp">util.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a37f94d1d2f7ce361ed9a652c1e916c77">104</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a37f94d1d2f7ce361ed9a652c1e916c77">TextGeneratorOLImpl::TextGeneratorOLImpl</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol) : <a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>(ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### writeBreak() {#a7c90aa4a3d435a4db351adb94ac62128}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextGeneratorOLImpl::writeBreak (int indent)</td>
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



<p>Declaration at line 81 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>, definition at line 136 of file <a href="/web-doxygen/docs/api/files/src/util-cpp">util.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c90aa4a3d435a4db351adb94ac62128">136</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7c90aa4a3d435a4db351adb94ac62128">TextGeneratorOLImpl::writeBreak</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indent)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>.lineBreak(</span><span class="doxyHighlightStringLiteral">"typebreak"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;i&lt;indent;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>.writeNonBreakableSpace(3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>.</p>

</div>
</div>

### writeLink() {#abd5e4e731db512c6e98795c56d323f30}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextGeneratorOLImpl::writeLink (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extRef, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, std::string_view text)</td>
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



<p>Declaration at line 82 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>, definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/util-cpp">util.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abd5e4e731db512c6e98795c56d323f30">145</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abd5e4e731db512c6e98795c56d323f30">TextGeneratorOLImpl::writeLink</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;extRef,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">                                    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,std::string_view text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">                                   )</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("TextGeneratorOlImpl::writeLink('%s')\n",text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>.writeObjectLink(extRef,file,anchor,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(text));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>.</p>

</div>
</div>

### writeString() {#add80058c326a14b48f31afbdd73d2402}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TextGeneratorOLImpl::writeString (std::string_view s, bool keepSpaces)</td>
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



<p>Declaration at line 80 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>, definition at line 108 of file <a href="/web-doxygen/docs/api/files/src/util-cpp">util.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#add80058c326a14b48f31afbdd73d2402">108</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#add80058c326a14b48f31afbdd73d2402">TextGeneratorOLImpl::writeString</a>(std::string_view s,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> keepSpaces)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("TextGeneratorOlImpl::writeString('%s',%d)\n",s,keepSpaces);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (keepSpaces)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> cs[2];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">    cs[1]=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;s.length();i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = s[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>.writeNonBreakableSpace(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">        cs[0]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>.docify(cs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>.docify(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_ol {#abac06004fff3ce6dd9fa5b3b2931bc35}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">OutputList&amp; TextGeneratorOLImpl::m_ol</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abac06004fff3ce6dd9fa5b3b2931bc35">86</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;<a href="#abac06004fff3ce6dd9fa5b3b2931bc35">m_ol</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a37f94d1d2f7ce361ed9a652c1e916c77">TextGeneratorOLImpl</a>, <a href="#a7c90aa4a3d435a4db351adb94ac62128">writeBreak</a>, <a href="#abd5e4e731db512c6e98795c56d323f30">writeLink</a> and <a href="#add80058c326a14b48f31afbdd73d2402">writeString</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/util-cpp">util.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/util-h">util.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
