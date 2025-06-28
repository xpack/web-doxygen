---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/vhdlstring
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `VhdlString` Class Reference

<p>Minimal string class with std::string like behavior that fulfills the JavaCC string requirements. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class VhdlString { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlparser/vhdlstring.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8fe423bc361c8030dc9f6ba110d87141">VhdlString</a> (const VhdlString &amp;other)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac1475e34a382d8691a23ac4e1d25e379">VhdlString</a> (const char *s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0fb86df3d26cfde46f9822599a53269">VhdlString</a> (const char *s, int size)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1e13bd31dbfa44d0607fb9383e413fbb">~VhdlString</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a24b56e898a3ce01327cbe1b60c5382ca">operator=</a> (const VhdlString &amp;other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a367768a3dda595c59aa63ac16f68ac9c">operator[]</a> (int i)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a82a66eba004a2f6be1d3fadb8c4d6098">operator[]</a> (int i) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8823d06700e5db3a0efec2bb1e00b61a">operator+=</a> (char c)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2dded5383aa21d3c1ed37ca6619dbf21">operator+=</a> (const char *s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a477840f6e98f22f912520dc5cb3b77c7">operator+=</a> (VhdlString s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a659e399322549ea7fba70bdb338a0855">operator+</a> (const char *s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a77e327ce7f5382381cae4fca59b85d71">append</a> (const char *s, int size)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8ee025fed34552a66fbf54a8913ec7b6">append</a> (const char *s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae57f5f8bd57f7697d50d129b08e310e2">append</a> (const VhdlString &amp;other)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab19c70bd559db2d839ad189dba7d4308">substr</a> (int pos=0, int len=-1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae74bb84c2809baf748cf273204aabd20">copy</a> (char *s, int len, int pos=0) const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7fc21a1bc98e67f6739bf5520f40e5c6">c_str</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9adab5bfd895699f39b84696bee7da78">data</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1218b098a4f69fe3ab3d96e378d14f7b">length</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5deab91a4101cbd3fe7a08970b673697">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefd2a815dc508a12c9352da3b575ce8f">init</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a></td>
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

<p>Minimal string class with std::string like behavior that fulfills the JavaCC string requirements.</p>

<p>Definition at line 33 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### VhdlString() {#ad1747afcb0d13f711688ab21ae32fe9e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString::VhdlString ()</td>
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


<p>Definition at line 36 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad1747afcb0d13f711688ab21ae32fe9e">36</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aefd2a815dc508a12c9352da3b575ce8f">init</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#aefd2a815dc508a12c9352da3b575ce8f">init</a>.

Referenced by <a href="#a8ee025fed34552a66fbf54a8913ec7b6">append</a>, <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a>, <a href="#ae57f5f8bd57f7697d50d129b08e310e2">append</a>, <a href="#a659e399322549ea7fba70bdb338a0855">operator+</a>, <a href="#a8823d06700e5db3a0efec2bb1e00b61a">operator+=</a>, <a href="#a2dded5383aa21d3c1ed37ca6619dbf21">operator+=</a>, <a href="#a477840f6e98f22f912520dc5cb3b77c7">operator+=</a>, <a href="#a24b56e898a3ce01327cbe1b60c5382ca">operator=</a>, <a href="#ab19c70bd559db2d839ad189dba7d4308">substr</a> and <a href="#a8fe423bc361c8030dc9f6ba110d87141">VhdlString</a>.
</div>
</div>

### VhdlString() {#a8fe423bc361c8030dc9f6ba110d87141}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString::VhdlString (const <a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a> &amp; other)</td>
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


<p>Definition at line 40 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8fe423bc361c8030dc9f6ba110d87141">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a8fe423bc361c8030dc9f6ba110d87141">VhdlString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a> = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)malloc(other.<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">      memcpy(<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>,other.<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>,other.<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a> = other.<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>[<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m&#95;len</a>, <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a> and <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>.
</div>
</div>

### VhdlString() {#ac1475e34a382d8691a23ac4e1d25e379}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString::VhdlString (const char * s)</td>
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


<p>Definition at line 59 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac1475e34a382d8691a23ac4e1d25e379">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac1475e34a382d8691a23ac4e1d25e379">VhdlString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a> = (int)strlen(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>=(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)malloc(<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">      memcpy(<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>,s,<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m&#95;len</a> and <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a>.
</div>
</div>

### VhdlString() {#ab0fb86df3d26cfde46f9822599a53269}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString::VhdlString (const char * s, int size)</td>
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


<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab0fb86df3d26cfde46f9822599a53269">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab0fb86df3d26cfde46f9822599a53269">VhdlString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a> = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)malloc(<a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a>+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">      memcpy(<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>,s,<a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>[<a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a>]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>=<a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m&#95;len</a>, <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a> and <a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### ~VhdlString() {#a1e13bd31dbfa44d0607fb9383e413fbb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString::~VhdlString ()</td>
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


<p>Definition at line 72 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1e13bd31dbfa44d0607fb9383e413fbb">72</a></span><span class="doxyLineContent"><span class="doxyHighlight">   <a href="#a1e13bd31dbfa44d0607fb9383e413fbb">~VhdlString</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">      free(<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator&#91;&#93;() {#a367768a3dda595c59aa63ac16f68ac9c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char &amp; VhdlString::operator[] (int i)</td>
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


<p>Definition at line 112 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a367768a3dda595c59aa63ac16f68ac9c">112</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> &amp;      <a href="#a367768a3dda595c59aa63ac16f68ac9c">operator[]</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i)       { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>[i]; }</span></span></div>

</div>


Reference <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a>.
</div>
</div>

### operator&#91;&#93;() {#a82a66eba004a2f6be1d3fadb8c4d6098}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char &amp; VhdlString::operator[] (int i)</td>
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


<p>Definition at line 113 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a82a66eba004a2f6be1d3fadb8c4d6098">113</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> &amp;<a href="#a82a66eba004a2f6be1d3fadb8c4d6098">operator[]</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i)</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>[i]; }</span></span></div>

</div>


Reference <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a>.
</div>
</div>

### operator+() {#a659e399322549ea7fba70bdb338a0855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString VhdlString::operator+ (const char * s)</td>
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


<p>Definition at line 118 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a659e399322549ea7fba70bdb338a0855">118</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>   <a href="#a659e399322549ea7fba70bdb338a0855">operator+</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a>(s); }</span></span></div>

</div>


References <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a> and <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>.
</div>
</div>

### operator+=() {#a8823d06700e5db3a0efec2bb1e00b61a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString &amp; VhdlString::operator+= (char c)</td>
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


<p>Definition at line 115 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8823d06700e5db3a0efec2bb1e00b61a">115</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>  &amp;<a href="#a8823d06700e5db3a0efec2bb1e00b61a">operator+=</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c)      { </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> s[2]; s[0]=c; s[1]=0; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a>(s); }</span></span></div>

</div>


References <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a> and <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>.
</div>
</div>

### operator+=() {#a2dded5383aa21d3c1ed37ca6619dbf21}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString &amp; VhdlString::operator+= (const char * s)</td>
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


<p>Definition at line 116 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2dded5383aa21d3c1ed37ca6619dbf21">116</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>  &amp;<a href="#a2dded5383aa21d3c1ed37ca6619dbf21">operator+=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a>(s); }</span></span></div>

</div>


References <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a> and <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>.
</div>
</div>

### operator+=() {#a477840f6e98f22f912520dc5cb3b77c7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString &amp; VhdlString::operator+= (<a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a> s)</td>
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


<p>Definition at line 117 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a477840f6e98f22f912520dc5cb3b77c7">117</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>  &amp;<a href="#a477840f6e98f22f912520dc5cb3b77c7">operator+=</a>(<a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a> s) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a>(s); }</span></span></div>

</div>


References <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a> and <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>.
</div>
</div>

### operator=() {#a24b56e898a3ce01327cbe1b60c5382ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString &amp; VhdlString::operator= (const <a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a> &amp; other)</td>
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


<p>Definition at line 47 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a24b56e898a3ce01327cbe1b60c5382ca">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a> &amp;<a href="#a24b56e898a3ce01327cbe1b60c5382ca">operator=</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">!=&amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">        free(<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a> = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)malloc(other.<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">        memcpy(<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>,other.<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>,other.<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a> = other.<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>[<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m&#95;len</a>, <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a> and <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### append() {#a77e327ce7f5382381cae4fca59b85d71}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString &amp; VhdlString::append (const char * s, int size)</td>
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


<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a77e327ce7f5382381cae4fca59b85d71">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>&amp; <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> oldlen = <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>+=<a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a>+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a> = (</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)realloc(<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>,<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">        memcpy(<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>+oldlen,s,<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>-oldlen-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>[<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>-1]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> *</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m&#95;len</a>, <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a>, <a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a> and <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>.

Referenced by <a href="#a8ee025fed34552a66fbf54a8913ec7b6">append</a>, <a href="#ae57f5f8bd57f7697d50d129b08e310e2">append</a>, <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h/#a9c94336ea01c70fb077989a9fac37307">operator+</a>, <a href="#a659e399322549ea7fba70bdb338a0855">operator+</a>, <a href="#a8823d06700e5db3a0efec2bb1e00b61a">operator+=</a>, <a href="#a2dded5383aa21d3c1ed37ca6619dbf21">operator+=</a> and <a href="#a477840f6e98f22f912520dc5cb3b77c7">operator+=</a>.
</div>
</div>

### append() {#a8ee025fed34552a66fbf54a8913ec7b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString &amp; VhdlString::append (const char * s)</td>
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


<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8ee025fed34552a66fbf54a8913ec7b6">88</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>&amp; <a href="#a8ee025fed34552a66fbf54a8913ec7b6">append</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a>(s,(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)strlen(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a> and <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>.
</div>
</div>

### append() {#ae57f5f8bd57f7697d50d129b08e310e2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString &amp; VhdlString::append (const <a href="/web-doxygen/docs/api/classes/vhdlstring">VhdlString</a> &amp; other)</td>
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


<p>Definition at line 92 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae57f5f8bd57f7697d50d129b08e310e2">92</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>&amp; <a href="#ae57f5f8bd57f7697d50d129b08e310e2">append</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a> &amp;other)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a>(other.<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>,other.<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a>, <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m&#95;len</a>, <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a> and <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>.
</div>
</div>

### c&#95;str() {#a7fc21a1bc98e67f6739bf5520f40e5c6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * VhdlString::c_str ()</td>
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


<p>Definition at line 108 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7fc21a1bc98e67f6739bf5520f40e5c6">108</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a7fc21a1bc98e67f6739bf5520f40e5c6">c_str</a>()</span><span class="doxyHighlightKeyword"> const           </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>; }</span></span></div>

</div>


Reference <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a>.
</div>
</div>

### clear() {#a5deab91a4101cbd3fe7a08970b673697}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlString::clear ()</td>
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


<p>Definition at line 114 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5deab91a4101cbd3fe7a08970b673697">114</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">        <a href="#a5deab91a4101cbd3fe7a08970b673697">clear</a>()                 { free(<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>); <a href="#aefd2a815dc508a12c9352da3b575ce8f">init</a>(); }</span></span></div>

</div>


References <a href="#aefd2a815dc508a12c9352da3b575ce8f">init</a> and <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a>.
</div>
</div>

### copy() {#ae74bb84c2809baf748cf273204aabd20}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VhdlString::copy (char * s, int len, int pos=0)</td>
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


<p>Definition at line 100 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae74bb84c2809baf748cf273204aabd20">100</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ae74bb84c2809baf748cf273204aabd20">copy</a>(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos=0)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len==0) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pos&gt;=<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>) { s[0]=0; </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> r=<a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>&lt;pos+len ? <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>-pos : len;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">      memcpy(s,<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>+pos,r);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> r;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m&#95;len</a> and <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a>.
</div>
</div>

### data() {#a9adab5bfd895699f39b84696bee7da78}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * VhdlString::data ()</td>
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


<p>Definition at line 109 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9adab5bfd895699f39b84696bee7da78">109</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a9adab5bfd895699f39b84696bee7da78">data</a>()</span><span class="doxyHighlightKeyword"> const            </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>; }</span></span></div>

</div>


Reference <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a>.
</div>
</div>

### length() {#a1218b098a4f69fe3ab3d96e378d14f7b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VhdlString::length ()</td>
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


<p>Definition at line 111 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1218b098a4f69fe3ab3d96e378d14f7b">111</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">         <a href="#a1218b098a4f69fe3ab3d96e378d14f7b">length</a>()</span><span class="doxyHighlightKeyword"> const          </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>; }</span></span></div>

</div>


Reference <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m&#95;len</a>.
</div>
</div>

### size() {#a4b2f992a1dc39ae0786ad0a193cc9707}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VhdlString::size ()</td>
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


<p>Definition at line 110 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4b2f992a1dc39ae0786ad0a193cc9707">110</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">         <a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a>()</span><span class="doxyHighlightKeyword"> const            </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>; }</span></span></div>

</div>


Reference <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m&#95;len</a>.

Referenced by <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a> and <a href="#ab0fb86df3d26cfde46f9822599a53269">VhdlString</a>.
</div>
</div>

### substr() {#ab19c70bd559db2d839ad189dba7d4308}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlString VhdlString::substr (int pos=0, int len=-1)</td>
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


<p>Definition at line 96 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab19c70bd559db2d839ad189dba7d4308">96</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a> <a href="#ab19c70bd559db2d839ad189dba7d4308">substr</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pos=0,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>(<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a> ? <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>+pos : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, len==-1 ? <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>-pos : <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m&#95;len</a>, <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a> and <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### init() {#aefd2a815dc508a12c9352da3b575ce8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VhdlString::init ()</td>
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


<p>Definition at line 121 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aefd2a815dc508a12c9352da3b575ce8f">121</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aefd2a815dc508a12c9352da3b575ce8f">init</a>() { <a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>=(</span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">*)calloc(1,1); <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>=0; }</span></span></div>

</div>


References <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m&#95;len</a> and <a href="#af805f3e01abaf627912be4a982e8b1ab">m&#95;str</a>.

Referenced by <a href="#a5deab91a4101cbd3fe7a08970b673697">clear</a> and <a href="#ad1747afcb0d13f711688ab21ae32fe9e">VhdlString</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;len {#a41e5c902ccf2ef80b229644d16ec8aa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VhdlString::m_len</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 123 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a41e5c902ccf2ef80b229644d16ec8aa9">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">   <a href="#a41e5c902ccf2ef80b229644d16ec8aa9">m_len</a>;</span></span></div>

</div>


Referenced by <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a>, <a href="#ae57f5f8bd57f7697d50d129b08e310e2">append</a>, <a href="#ae74bb84c2809baf748cf273204aabd20">copy</a>, <a href="#aefd2a815dc508a12c9352da3b575ce8f">init</a>, <a href="#a1218b098a4f69fe3ab3d96e378d14f7b">length</a>, <a href="#a24b56e898a3ce01327cbe1b60c5382ca">operator=</a>, <a href="#a4b2f992a1dc39ae0786ad0a193cc9707">size</a>, <a href="#ab19c70bd559db2d839ad189dba7d4308">substr</a>, <a href="#ac1475e34a382d8691a23ac4e1d25e379">VhdlString</a>, <a href="#ab0fb86df3d26cfde46f9822599a53269">VhdlString</a> and <a href="#a8fe423bc361c8030dc9f6ba110d87141">VhdlString</a>.
</div>
</div>

### m&#95;str {#af805f3e01abaf627912be4a982e8b1ab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char* VhdlString::m_str</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 122 of file <a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af805f3e01abaf627912be4a982e8b1ab">122</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#af805f3e01abaf627912be4a982e8b1ab">m_str</a>;</span></span></div>

</div>


Referenced by <a href="#a77e327ce7f5382381cae4fca59b85d71">append</a>, <a href="#ae57f5f8bd57f7697d50d129b08e310e2">append</a>, <a href="#a7fc21a1bc98e67f6739bf5520f40e5c6">c&#95;str</a>, <a href="#a5deab91a4101cbd3fe7a08970b673697">clear</a>, <a href="#ae74bb84c2809baf748cf273204aabd20">copy</a>, <a href="#a9adab5bfd895699f39b84696bee7da78">data</a>, <a href="#aefd2a815dc508a12c9352da3b575ce8f">init</a>, <a href="#a24b56e898a3ce01327cbe1b60c5382ca">operator=</a>, <a href="#a367768a3dda595c59aa63ac16f68ac9c">operator&#91;&#93;</a>, <a href="#a82a66eba004a2f6be1d3fadb8c4d6098">operator&#91;&#93;</a>, <a href="#ab19c70bd559db2d839ad189dba7d4308">substr</a>, <a href="#ac1475e34a382d8691a23ac4e1d25e379">VhdlString</a>, <a href="#ab0fb86df3d26cfde46f9822599a53269">VhdlString</a>, <a href="#a8fe423bc361c8030dc9f6ba110d87141">VhdlString</a> and <a href="#a1e13bd31dbfa44d0607fb9383e413fbb">~VhdlString</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/vhdlparser/vhdlstring-h">vhdlstring.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
