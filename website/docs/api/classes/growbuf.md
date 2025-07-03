---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/growbuf
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `GrowBuf` Class Reference

<p>Class representing a string buffer optimized for growing. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class GrowBuf { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/growbuf-h">src/growbuf.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af49b662ca5d8163601b91ad7f201e460">GrowBuf</a> (size_t initialSize)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab7adf8adf049747895150afb7c539d71">GrowBuf</a> (const GrowBuf &amp;other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a471132290014798c89965dd36b51e5bc">GrowBuf</a> (GrowBuf &amp;&amp;other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7206ac4d12d20889037d545e6bab0d9">~GrowBuf</a> ()</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a30ef5583d31934cffabff4fa837a9e84">operator=</a> (const GrowBuf &amp;other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac7ef149390d72537bf9f2a1be9cc3baf">operator=</a> (GrowBuf &amp;&amp;other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a3aabf69cefb88ffc5bb7b88f86b933">reserve</a> (size_t size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7aadcbc3d02fe6e01acf45d892cff0ba">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46b4677f555d2abc718f26e71a59efda">addChar</a> (char c)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb4b38e6520d3bf3a77a38e17ce669da">addStr</a> (const std::string &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2a971c747abdd4cb7cb038a3e27197b">addStr</a> (const char *s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adba54aa237c8f30b40a9f7fe28226f58">addStr</a> (const char *s, size_t n)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c84320a57fe98375add64ad01e9bf3b">addInt</a> (const char *fmt, int value)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88d6408723b8c1a58187f24da81dfd5e">get</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8291335fec63f39c9a021f40dcc15e93">get</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a0ecc7a79837ed02005befe12d49994">getPos</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98f7e0590791e42fcbd31bdfd8c75d2a">setPos</a> (size_t newPos)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const char &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7208e5ca317711c8190cbdcfae8ab702">at</a> (size_t i) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3d16113cdc8835afa7f836914db2289">empty</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">size_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a></td>
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

<p>Class representing a string buffer optimized for growing.</p>

<p>Definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### GrowBuf() {#a7868767b69ab7f10f3a36da73e2f5e5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GrowBuf::GrowBuf ()</td>
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



<p>Definition at line 30 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7868767b69ab7f10f3a36da73e2f5e5f">30</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a>() : <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>(nullptr), <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>(0), <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>(0) {}</span></span></div>

</div>


<p>References <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>, <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>


<p>Referenced by <a href="#ab7adf8adf049747895150afb7c539d71">GrowBuf</a>, <a href="#a471132290014798c89965dd36b51e5bc">GrowBuf</a>, <a href="#a30ef5583d31934cffabff4fa837a9e84">operator=</a> and <a href="#ac7ef149390d72537bf9f2a1be9cc3baf">operator=</a>.</p>

</div>
</div>

### GrowBuf() {#af49b662ca5d8163601b91ad7f201e460}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GrowBuf::GrowBuf (size_t initialSize)</td>
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



<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af49b662ca5d8163601b91ad7f201e460">31</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af49b662ca5d8163601b91ad7f201e460">GrowBuf</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> initialSize) : <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>(0), <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>(initialSize) { <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(malloc(<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>)); }</span></span></div>

</div>


<p>References <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>, <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>

</div>
</div>

### GrowBuf() {#ab7adf8adf049747895150afb7c539d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GrowBuf::GrowBuf (const <a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> &amp; other)</td>
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



<p>Definition at line 33 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab7adf8adf049747895150afb7c539d71">33</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab7adf8adf049747895150afb7c539d71">GrowBuf</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">34</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a> = other.<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> = other.<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(malloc(<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">      memcpy(<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>,other.<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>,<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a>, <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>, <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>

</div>
</div>

### GrowBuf() {#a471132290014798c89965dd36b51e5bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GrowBuf::GrowBuf (<a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> &amp;&amp; other)</td>
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



<p>Definition at line 52 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a471132290014798c89965dd36b51e5bc">52</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a471132290014798c89965dd36b51e5bc">GrowBuf</a>(<a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a> &amp;&amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>(std::exchange(other.<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>,static_cast&lt;char*&gt;(nullptr)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">      , <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>(std::exchange(other.<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>,0))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">      , <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>(std::exchange(other.<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>,0))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a>, <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>, <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~GrowBuf() {#af7206ac4d12d20889037d545e6bab0d9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GrowBuf::~GrowBuf ()</td>
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



<p>Definition at line 32 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7206ac4d12d20889037d545e6bab0d9">32</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#af7206ac4d12d20889037d545e6bab0d9">~GrowBuf</a>()         { free(<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>); }</span></span></div>

</div>


<p>Reference <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a30ef5583d31934cffabff4fa837a9e84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GrowBuf &amp; GrowBuf::operator= (const <a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> &amp; other)</td>
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



<p>Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a30ef5583d31934cffabff4fa837a9e84">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a> &amp;<a href="#a30ef5583d31934cffabff4fa837a9e84">operator=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">!=&amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">        free(<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a> = other.<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> = other.<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(malloc(<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">        memcpy(<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>,other.<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>,<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a>, <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>, <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>

</div>
</div>

### operator=() {#ac7ef149390d72537bf9f2a1be9cc3baf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">GrowBuf &amp; GrowBuf::operator= (<a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> &amp;&amp; other)</td>
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



<p>Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac7ef149390d72537bf9f2a1be9cc3baf">58</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a> &amp;<a href="#ac7ef149390d72537bf9f2a1be9cc3baf">operator=</a>(<a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a> &amp;&amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">==&amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a> = std::exchange(other.m_len,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> = std::exchange(other.m_pos,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a> = std::exchange(other.m_str,</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a>, <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>, <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addChar() {#a46b4677f555d2abc718f26e71a59efda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowBuf::addChar (char c)</td>
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



<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a46b4677f555d2abc718f26e71a59efda">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)  { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>&gt;=<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>) { <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>+=<a href="/web-doxygen/docs/api/files/src/growbuf-h/#a8b0dc2f8685a41830347ff1e73629fb3">GROW_AMOUNT</a>; <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(realloc(<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>,<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>)); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">                        <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>[<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>++]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/growbuf-h/#a8b0dc2f8685a41830347ff1e73629fb3">GROW_AMOUNT</a>, <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>, <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/searchindexexternal/#a0a0b44c02ff02fda01a1aa4f4fcbbded">SearchIndexExternal::addWord</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7d7c9238115c2656c20621678519cb87">convertToJSString</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ab1778365304892c7a24196f356222b18">convertToPSString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9884211727d9091a08b34aa1fb14c9b1">detab</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a5f369f2c5e750a453046fddfbbf06ad0">filter2008VhdlComment</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a2f5320a8c0aa3d9f5af4129d7edda49c">HtmlDocVisitor::filterQuotedCdataAttr</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a9f06f858b1cd97d3bc7b850a600b45be">formatDateTime</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#af1366ac568f1a1620961826edd2e88e7">CitationManager::getFormulas</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>.</p>

</div>
</div>

### addInt() {#a3c84320a57fe98375add64ad01e9bf3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowBuf::addInt (const char * fmt, int value)</td>
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



<p>Definition at line 109 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c84320a57fe98375add64ad01e9bf3b">109</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> value) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> tmp[50];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">                      snprintf(tmp,50,<a href="/web-doxygen/docs/api/namespaces/fmt">fmt</a>,value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">                      <a href="#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(tmp);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a9f06f858b1cd97d3bc7b850a600b45be">formatDateTime</a>.</p>

</div>
</div>

### addStr() {#a5e0ff6d9f7a7139725d77a9d669340f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowBuf::addStr (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e0ff6d9f7a7139725d77a9d669340f3">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>+l&gt;=<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>) { <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>+=l+<a href="/web-doxygen/docs/api/files/src/growbuf-h/#a8b0dc2f8685a41830347ff1e73629fb3">GROW_AMOUNT</a>; <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(realloc(<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>,<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>)); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">                          strcpy(&amp;<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>[<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>],s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>+=l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/growbuf-h/#a8b0dc2f8685a41830347ff1e73629fb3">GROW_AMOUNT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>, <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>


<p>Referenced by <a href="#a3c84320a57fe98375add64ad01e9bf3b">addInt</a>, <a href="/web-doxygen/docs/api/classes/searchindexexternal/#a0a0b44c02ff02fda01a1aa4f4fcbbded">SearchIndexExternal::addWord</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7d7c9238115c2656c20621678519cb87">convertToJSString</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ab1778365304892c7a24196f356222b18">convertToPSString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9884211727d9091a08b34aa1fb14c9b1">detab</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a2f5320a8c0aa3d9f5af4129d7edda49c">HtmlDocVisitor::filterQuotedCdataAttr</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a9f06f858b1cd97d3bc7b850a600b45be">formatDateTime</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#af1366ac568f1a1620961826edd2e88e7">CitationManager::getFormulas</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>.</p>

</div>
</div>

### addStr() {#afb4b38e6520d3bf3a77a38e17ce669da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowBuf::addStr (const std::string &amp; s)</td>
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



<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afb4b38e6520d3bf3a77a38e17ce669da">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afb4b38e6520d3bf3a77a38e17ce669da">addStr</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;s) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!s.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l=s.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>+l&gt;=<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>) { <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>+=l+<a href="/web-doxygen/docs/api/files/src/growbuf-h/#a8b0dc2f8685a41830347ff1e73629fb3">GROW_AMOUNT</a>; <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(realloc(<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>,<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>)); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">                          strcpy(&amp;<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>[<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>],s.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>+=l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/growbuf-h/#a8b0dc2f8685a41830347ff1e73629fb3">GROW_AMOUNT</a>, <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>, <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>

</div>
</div>

### addStr() {#ac2a971c747abdd4cb7cb038a3e27197b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowBuf::addStr (const char * s)</td>
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



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac2a971c747abdd4cb7cb038a3e27197b">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac2a971c747abdd4cb7cb038a3e27197b">addStr</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l=strlen(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>+l&gt;=<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>) { <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>+=l+<a href="/web-doxygen/docs/api/files/src/growbuf-h/#a8b0dc2f8685a41830347ff1e73629fb3">GROW_AMOUNT</a>; <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(realloc(<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>,<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>)); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">                          strcpy(&amp;<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>[<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>],s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>+=l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/growbuf-h/#a8b0dc2f8685a41830347ff1e73629fb3">GROW_AMOUNT</a>, <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>, <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>

</div>
</div>

### addStr() {#adba54aa237c8f30b40a9f7fe28226f58}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowBuf::addStr (const char * s, size_t n)</td>
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



<p>Definition at line 99 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adba54aa237c8f30b40a9f7fe28226f58">99</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#adba54aa237c8f30b40a9f7fe28226f58">addStr</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> n) {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">                        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">                        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> l=strlen(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n&lt;l) l=n;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>+l&gt;=<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>) { <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>+=l+<a href="/web-doxygen/docs/api/files/src/growbuf-h/#a8b0dc2f8685a41830347ff1e73629fb3">GROW_AMOUNT</a>; <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(realloc(<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>,<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>)); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">                          strncpy(&amp;<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>[<a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>],s,n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">                          <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>+=l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">                        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">                      }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/growbuf-h/#a8b0dc2f8685a41830347ff1e73629fb3">GROW_AMOUNT</a>, <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>, <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>

</div>
</div>

### at() {#a7208e5ca317711c8190cbdcfae8ab702}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char &amp; GrowBuf::at (size_t i)</td>
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



<p>Definition at line 118 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7208e5ca317711c8190cbdcfae8ab702">118</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> &amp;<a href="#a7208e5ca317711c8190cbdcfae8ab702">at</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>[i]; }</span></span></div>

</div>


<p>Reference <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a5f369f2c5e750a453046fddfbbf06ad0">filter2008VhdlComment</a>.</p>

</div>
</div>

### clear() {#a7aadcbc3d02fe6e01acf45d892cff0ba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowBuf::clear ()</td>
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



<p>Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7aadcbc3d02fe6e01acf45d892cff0ba">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7aadcbc3d02fe6e01acf45d892cff0ba">clear</a>()      { <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>=0; }</span></span></div>

</div>


<p>Reference <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a> and <a href="/web-doxygen/docs/api/classes/citationmanager/#af1366ac568f1a1620961826edd2e88e7">CitationManager::getFormulas</a>.</p>

</div>
</div>

### empty() {#aa3d16113cdc8835afa7f836914db2289}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool GrowBuf::empty ()</td>
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



<p>Definition at line 119 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa3d16113cdc8835afa7f836914db2289">119</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aa3d16113cdc8835afa7f836914db2289">empty</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>==0; }</span></span></div>

</div>


<p>Reference <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>.</p>

</div>
</div>

### get() {#a88d6408723b8c1a58187f24da81dfd5e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char * GrowBuf::get ()</td>
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



<p>Definition at line 114 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a88d6408723b8c1a58187f24da81dfd5e">114</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a88d6408723b8c1a58187f24da81dfd5e">get</a>() { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>; }</span></span></div>

</div>


<p>Reference <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#afb36c9b4d9962a775c9113434fedd520">convertCharEntitiesToUTF8</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a7d7c9238115c2656c20621678519cb87">convertToJSString</a>, <a href="/web-doxygen/docs/api/files/src/diagram-cpp/#ab1778365304892c7a24196f356222b18">convertToPSString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9884211727d9091a08b34aa1fb14c9b1">detab</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a5f369f2c5e750a453046fddfbbf06ad0">filter2008VhdlComment</a>, <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp/#a2696c55cf5da503843057747b989140c">filterId</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a2f5320a8c0aa3d9f5af4129d7edda49c">HtmlDocVisitor::filterQuotedCdataAttr</a>, <a href="/web-doxygen/docs/api/files/src/datetime-cpp/#a9f06f858b1cd97d3bc7b850a600b45be">formatDateTime</a>, <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a880152a6988921d6248a7640983bef9e">getConvertLatexMacro</a>, <a href="/web-doxygen/docs/api/classes/citationmanager/#af1366ac568f1a1620961826edd2e88e7">CitationManager::getFormulas</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a> and <a href="/web-doxygen/docs/api/files/src/htmlgen-cpp/#a2f3978430bdfefcb92e25f2da8854f45">replaceVariables</a>.</p>

</div>
</div>

### get() {#a8291335fec63f39c9a021f40dcc15e93}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * GrowBuf::get ()</td>
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



<p>Definition at line 115 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8291335fec63f39c9a021f40dcc15e93">115</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a8291335fec63f39c9a021f40dcc15e93">get</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>; }</span></span></div>

</div>


<p>Reference <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>

</div>
</div>

### getPos() {#a1a0ecc7a79837ed02005befe12d49994}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t GrowBuf::getPos ()</td>
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



<p>Definition at line 116 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a0ecc7a79837ed02005befe12d49994">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a1a0ecc7a79837ed02005befe12d49994">getPos</a>()</span><span class="doxyHighlightKeyword"> const   </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>; }</span></span></div>

</div>


<p>Reference <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/searchindexexternal/#a0a0b44c02ff02fda01a1aa4f4fcbbded">SearchIndexExternal::addWord</a>, <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a5f369f2c5e750a453046fddfbbf06ad0">filter2008VhdlComment</a> and <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a>.</p>

</div>
</div>

### reserve() {#a9a3aabf69cefb88ffc5bb7b88f86b933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowBuf::reserve (size_t size)</td>
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



<p>Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a3aabf69cefb88ffc5bb7b88f86b933">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9a3aabf69cefb88ffc5bb7b88f86b933">reserve</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size) { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>&lt;size) { <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a> = size; <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(realloc(<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>,<a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>)); } }</span></span></div>

</div>


<p>References <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a> and <a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>.</p>

</div>
</div>

### setPos() {#a98f7e0590791e42fcbd31bdfd8c75d2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void GrowBuf::setPos (size_t newPos)</td>
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



<p>Definition at line 117 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a98f7e0590791e42fcbd31bdfd8c75d2a">117</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a98f7e0590791e42fcbd31bdfd8c75d2a">setPos</a>(</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> newPos) { <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a> = newPos; }</span></span></div>

</div>


<p>Reference <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a5f369f2c5e750a453046fddfbbf06ad0">filter2008VhdlComment</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_len {#ad5ec59f43c28c517b3f11dea3e2adab6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t GrowBuf::m_len</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad5ec59f43c28c517b3f11dea3e2adab6">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#ad5ec59f43c28c517b3f11dea3e2adab6">m_len</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a46b4677f555d2abc718f26e71a59efda">addChar</a>, <a href="#ac2a971c747abdd4cb7cb038a3e27197b">addStr</a>, <a href="#adba54aa237c8f30b40a9f7fe28226f58">addStr</a>, <a href="#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>, <a href="#afb4b38e6520d3bf3a77a38e17ce669da">addStr</a>, <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a>, <a href="#ab7adf8adf049747895150afb7c539d71">GrowBuf</a>, <a href="#a471132290014798c89965dd36b51e5bc">GrowBuf</a>, <a href="#af49b662ca5d8163601b91ad7f201e460">GrowBuf</a>, <a href="#a30ef5583d31934cffabff4fa837a9e84">operator=</a>, <a href="#ac7ef149390d72537bf9f2a1be9cc3baf">operator=</a> and <a href="#a9a3aabf69cefb88ffc5bb7b88f86b933">reserve</a>.</p>

</div>
</div>

### m\_pos {#a2c1af45fdd1c692684b38dd54fcf1a6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">size_t GrowBuf::m_pos</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 122 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">122</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="#a2c1af45fdd1c692684b38dd54fcf1a6b">m_pos</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a46b4677f555d2abc718f26e71a59efda">addChar</a>, <a href="#ac2a971c747abdd4cb7cb038a3e27197b">addStr</a>, <a href="#adba54aa237c8f30b40a9f7fe28226f58">addStr</a>, <a href="#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>, <a href="#afb4b38e6520d3bf3a77a38e17ce669da">addStr</a>, <a href="#a7aadcbc3d02fe6e01acf45d892cff0ba">clear</a>, <a href="#aa3d16113cdc8835afa7f836914db2289">empty</a>, <a href="#a1a0ecc7a79837ed02005befe12d49994">getPos</a>, <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a>, <a href="#ab7adf8adf049747895150afb7c539d71">GrowBuf</a>, <a href="#a471132290014798c89965dd36b51e5bc">GrowBuf</a>, <a href="#af49b662ca5d8163601b91ad7f201e460">GrowBuf</a>, <a href="#a30ef5583d31934cffabff4fa837a9e84">operator=</a>, <a href="#ac7ef149390d72537bf9f2a1be9cc3baf">operator=</a> and <a href="#a98f7e0590791e42fcbd31bdfd8c75d2a">setPos</a>.</p>

</div>
</div>

### m\_str {#a94df360b36d76642c8ae017fa6d7e431}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char* GrowBuf::m_str</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 121 of file <a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a94df360b36d76642c8ae017fa6d7e431">121</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a94df360b36d76642c8ae017fa6d7e431">m_str</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a46b4677f555d2abc718f26e71a59efda">addChar</a>, <a href="#ac2a971c747abdd4cb7cb038a3e27197b">addStr</a>, <a href="#adba54aa237c8f30b40a9f7fe28226f58">addStr</a>, <a href="#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>, <a href="#afb4b38e6520d3bf3a77a38e17ce669da">addStr</a>, <a href="#a7208e5ca317711c8190cbdcfae8ab702">at</a>, <a href="#a88d6408723b8c1a58187f24da81dfd5e">get</a>, <a href="#a8291335fec63f39c9a021f40dcc15e93">get</a>, <a href="#a7868767b69ab7f10f3a36da73e2f5e5f">GrowBuf</a>, <a href="#ab7adf8adf049747895150afb7c539d71">GrowBuf</a>, <a href="#a471132290014798c89965dd36b51e5bc">GrowBuf</a>, <a href="#af49b662ca5d8163601b91ad7f201e460">GrowBuf</a>, <a href="#a30ef5583d31934cffabff4fa837a9e84">operator=</a>, <a href="#ac7ef149390d72537bf9f2a1be9cc3baf">operator=</a>, <a href="#a9a3aabf69cefb88ffc5bb7b88f86b933">reserve</a> and <a href="#af7206ac4d12d20889037d545e6bab0d9">~GrowBuf</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
