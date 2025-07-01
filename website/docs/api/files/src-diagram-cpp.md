---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/diagram-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `diagram.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;algorithm&gt;
#include "<a href="/web-doxygen/docs/api/files/src/diagram-h">diagram.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/image-h">image.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classlist-h">classlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/textstream-h">textstream.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class representing a single node in the built-in class diagram. <a href="/web-doxygen/docs/api/classes/diagramitem/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/diagramrow">DiagramRow</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class representing a row in the built-in class diagram. <a href="/web-doxygen/docs/api/classes/diagramrow/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/treediagram">TreeDiagram</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Class representing the tree layout for the built-in class diagram. <a href="/web-doxygen/docs/api/classes/treediagram/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dualdiriterator">DualDirIterator&lt;C, I&gt;</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
helper class representing an iterator that can iterate forwards or backwards <a href="/web-doxygen/docs/api/classes/dualdiriterator/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/classdiagram/private">Private</a></td>
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

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a603348be77849aaf4416a4673fa207b6">DiagramItemList</a> = std::vector&lt; <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> * &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae83b8312932399969490a2948e15a7db">protToMask</a> (Protection p)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint8_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac815a4d282922c6d48976d582826d1b5">protToColor</a> (Protection p)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad92050b3f6c2e59066cbf6f03a76c1d8">protToString</a> (Protection p)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac71ce95e0e325a4f796901db0f6f41d5">virtToMask</a> (Specifier p)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab1778365304892c7a24196f356222b18">convertToPSString</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa7edd2f3dfefdfd9655c162adc982e70">getMinProtectionLevel</a> (const DiagramItemList &amp;dil)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4a6853a6b7f98f30da5d61d680d86041">writeBitmapBox</a> (DiagramItem *di, Image *image, uint32_t x, uint32_t y, uint32_t w, uint32_t h, bool firstRow, bool hasDocs, bool children=FALSE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac45380e90067e3138b21af2a68dc19f3">writeVectorBox</a> (TextStream &amp;t, DiagramItem *di, float x, float y, bool children=FALSE)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2e8ce3b3d8bd736fca765b669093772c">writeMapArea</a> (TextStream &amp;t, const ClassDef *cd, QCString relPath, uint32_t x, uint32_t y, uint32_t w, uint32_t h)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08f611cf182c7d6d2e6c7b944c7511dc">maxTreeWidth</a> = 8</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2955a33900313eb54d0a7f5318421db7">gridWidth</a> = 100</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a> = 100</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a486228a1ff55861685b37025028df553">labelHorSpacing</a> = 10</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a> = 32</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1633af3b4b6c08d35ec5538e9f599543">labelHorMargin</a> = 6</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const uint32_t</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa13a42b6fd4f4b0c89be8c3bab657be3">fontHeight</a> = 12</td>
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

## Macro Definitions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addf4ae1173df3a2d96b5862df8960117">IMAGE_EXT</a>&nbsp;&nbsp;&nbsp;".png"</td>
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

## Typedefs

### DiagramItemList {#a603348be77849aaf4416a4673fa207b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using DiagramItemList =  std::vector&lt;DiagramItem*&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a603348be77849aaf4416a4673fa207b6">38</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a603348be77849aaf4416a4673fa207b6">DiagramItemList</a> = std::vector&lt;DiagramItem*&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### convertToPSString() {#ab1778365304892c7a24196f356222b18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString convertToPSString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



Definition at line 195 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab1778365304892c7a24196f356222b18">195</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab1778365304892c7a24196f356222b18">convertToPSString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> growBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'('</span><span class="doxyHighlight">:  growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"\\("</span><span class="doxyHighlight">); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">')'</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"\\)"</span><span class="doxyHighlight">); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:   growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(c);   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">get</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">GrowBuf::addChar</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">GrowBuf::addStr</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">GrowBuf::get</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdiagram/#acb331a908252968ca8ba371ee560aa51">ClassDiagram::writeFigure</a> and <a href="#ac45380e90067e3138b21af2a68dc19f3">writeVectorBox</a>.
</div>
</div>

### getMinProtectionLevel() {#aa7edd2f3dfefdfd9655c162adc982e70}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Protection getMinProtectionLevel (const <a href="#a603348be77849aaf4416a4673fa207b6">DiagramItemList</a> &amp; dil)</td>
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



Definition at line 215 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa7edd2f3dfefdfd9655c162adc982e70">215</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> <a href="#aa7edd2f3dfefdfd9655c162adc982e70">getMinProtectionLevel</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a603348be77849aaf4416a4673fa207b6">DiagramItemList</a> &amp;dil)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = dil.begin();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> result = Protection::Private;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=dil.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">    result=(*it)-&gt;protection();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (++it;it!=dil.end();++it)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p=(*it)-&gt;protection();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p!=result)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result==Protection::Protected &amp;&amp; p==Protection::Public) result=p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result==Protection::Private) result=p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a>.
</div>
</div>

### protToColor() {#ac815a4d282922c6d48976d582826d1b5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint8_t protToColor (<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p)</td>
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



Definition at line 160 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac815a4d282922c6d48976d582826d1b5">160</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> uint8_t <a href="#ac815a4d282922c6d48976d582826d1b5">protToColor</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Public:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 6;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Package: </span><span class="doxyHighlightComment">// package is not possible!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Protected: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 5;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Private:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 4;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a>.
</div>
</div>

### protToMask() {#ae83b8312932399969490a2948e15a7db}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t protToMask (<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p)</td>
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



Definition at line 148 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae83b8312932399969490a2948e15a7db">148</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> uint32_t <a href="#ae83b8312932399969490a2948e15a7db">protToMask</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Public:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0xffffffff;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Package: </span><span class="doxyHighlightComment">// package is not possible!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Protected: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0xcccccccc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Private:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0xaaaaaaaa;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a>.
</div>
</div>

### protToString() {#ad92050b3f6c2e59066cbf6f03a76c1d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString protToString (<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p)</td>
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



Definition at line 172 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad92050b3f6c2e59066cbf6f03a76c1d8">172</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad92050b3f6c2e59066cbf6f03a76c1d8">protToString</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Public:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"solid"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Package: </span><span class="doxyHighlightComment">// package is not possible!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Protected: </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"dashed"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Protection::Private:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">"dotted"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a>.
</div>
</div>

### virtToMask() {#ac71ce95e0e325a4f796901db0f6f41d5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">uint32_t virtToMask (<a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> p)</td>
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



Definition at line 184 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac71ce95e0e325a4f796901db0f6f41d5">184</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> uint32_t <a href="#ac71ce95e0e325a4f796901db0f6f41d5">virtToMask</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Specifier::Normal:    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0xffffffff;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> Specifier::Virtual:   </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0xf0f0f0f0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="#a4a6853a6b7f98f30da5d61d680d86041">writeBitmapBox</a>.
</div>
</div>

### writeBitmapBox() {#a4a6853a6b7f98f30da5d61d680d86041}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeBitmapBox (<a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> * di, <a href="/web-doxygen/docs/api/classes/image">Image</a> * image, uint32_t x, uint32_t y, uint32_t w, uint32_t h, bool firstRow, bool hasDocs, bool children=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
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



Definition at line 235 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4a6853a6b7f98f30da5d61d680d86041">235</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4a6853a6b7f98f30da5d61d680d86041">writeBitmapBox</a>(<a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *di,<a href="/web-doxygen/docs/api/classes/image">Image</a> *image,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">                           uint32_t x,uint32_t y,uint32_t w,uint32_t h,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> firstRow,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasDocs,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> children=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">  uint8_t colFill = hasDocs ? (firstRow ? 8 : 2) : 7;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  uint8_t colBorder = (firstRow || !hasDocs) ? 1 : 3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t l = <a href="/web-doxygen/docs/api/classes/image/#af25a570683d7f6392bdba0bf433f6c30">Image::stringLength</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ab0d5760c4d7ff79eb2ed90652a825b54">label</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t mask=<a href="#ac71ce95e0e325a4f796901db0f6f41d5">virtToMask</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a11ec77d7b8a9920793793ead700627e1">virtualness</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a6bc83fab8a49849bea576d9cdcbc2a74">fillRect</a>(x+1,y+1,w-2,h-2,colFill,mask);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">  image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a84642fefb94260db8b9f4f1d05ed6354">drawRect</a>(x,y,w,h,colBorder,mask);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a9548b8956604519c4260cbdaf7854792">writeString</a>(x+(w-l)/2, y+(h-<a href="#aa13a42b6fd4f4b0c89be8c3bab657be3">fontHeight</a>)/2, di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ab0d5760c4d7ff79eb2ed90652a825b54">label</a>(),1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (children)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (uint32_t i=0;i&lt;5;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      image-&gt;<a href="/web-doxygen/docs/api/classes/image/#a3963507ed7da8333a1b7766d890e12b4">drawHorzLine</a>(y+h+i-6,x+w-2-i,x+w-2,firstRow?1:3,0xffffffff);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/image/#a3963507ed7da8333a1b7766d890e12b4">Image::drawHorzLine</a>, <a href="/web-doxygen/docs/api/classes/image/#a84642fefb94260db8b9f4f1d05ed6354">Image::drawRect</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/image/#a6bc83fab8a49849bea576d9cdcbc2a74">Image::fillRect</a>, <a href="#aa13a42b6fd4f4b0c89be8c3bab657be3">fontHeight</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ab0d5760c4d7ff79eb2ed90652a825b54">DiagramItem::label</a>, <a href="/web-doxygen/docs/api/classes/image/#af25a570683d7f6392bdba0bf433f6c30">Image::stringLength</a>, <a href="#ac71ce95e0e325a4f796901db0f6f41d5">virtToMask</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#a11ec77d7b8a9920793793ead700627e1">DiagramItem::virtualness</a> and <a href="/web-doxygen/docs/api/classes/image/#a9548b8956604519c4260cbdaf7854792">Image::writeString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a7916cd8dbb3b48d335e036c9717ac00d">TreeDiagram::drawBoxes</a>.
</div>
</div>

### writeMapArea() {#a2e8ce3b3d8bd736fca765b669093772c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeMapArea (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> relPath, uint32_t x, uint32_t y, uint32_t w, uint32_t h)</td>
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



Definition at line 264 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2e8ce3b3d8bd736fca765b669093772c">264</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a2e8ce3b3d8bd736fca765b669093772c">writeMapArea</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">                         uint32_t x,uint32_t y,uint32_t w,uint32_t h)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">isLinkable</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ref=cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">getReference</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;area "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!ref.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"href=\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>(relPath,ref,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fn = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>(fn);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; fn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight"> &lt;&lt; cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tooltip = cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">briefDescriptionAsTooltip</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tooltip.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"title=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>(tooltip) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"alt=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac4741f70f06baac174cf71b3e11d06ac">displayName</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" shape=\"rect\" coords=\""</span><span class="doxyHighlight"> &lt;&lt; x &lt;&lt; </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight"> &lt;&lt; y &lt;&lt; </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; (x+w) &lt;&lt; </span><span class="doxyHighlightStringLiteral">","</span><span class="doxyHighlight"> &lt;&lt; (y+h) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/util-cpp/#afeb116177e3265cffe5a3b810461194f">addHtmlExtensionIfMissing</a>, <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/definition/#a5915353219702c6ea73cc1476bda793a">Definition::briefDescriptionAsTooltip</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac4741f70f06baac174cf71b3e11d06ac">Definition::displayName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad3f3c94bc6e432d34fa1a51db3b7d5e2">externalLinkTarget</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a06ba0c2593b3fd5f103151bd342e206f">externalRef</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/definition/#aab5f8631606d43a73f371833eb6425ee">Definition::getReference</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/definition/#a4002fd79c2d4dcf667c37c83d4214deb">Definition::isLinkable</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a7916cd8dbb3b48d335e036c9717ac00d">TreeDiagram::drawBoxes</a>.
</div>
</div>

### writeVectorBox() {#ac45380e90067e3138b21af2a68dc19f3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeVectorBox (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> * di, float x, float y, bool children=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
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



Definition at line 255 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac45380e90067e3138b21af2a68dc19f3">255</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac45380e90067e3138b21af2a68dc19f3">writeVectorBox</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,<a href="/web-doxygen/docs/api/classes/diagramitem">DiagramItem</a> *di,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlight"> x,</span><span class="doxyHighlightKeywordType">float</span><span class="doxyHighlight"> y,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> children=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a11ec77d7b8a9920793793ead700627e1">virtualness</a>()==Specifier::Virtual) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"dashed\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">" ("</span><span class="doxyHighlight"> &lt;&lt; <a href="#ab1778365304892c7a24196f356222b18">convertToPSString</a>(di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#ab0d5760c4d7ff79eb2ed90652a825b54">label</a>()) &lt;&lt; </span><span class="doxyHighlightStringLiteral">") "</span><span class="doxyHighlight"> &lt;&lt; x &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; y &lt;&lt; </span><span class="doxyHighlightStringLiteral">" box\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (children) t &lt;&lt; x &lt;&lt; </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight"> &lt;&lt; y &lt;&lt; </span><span class="doxyHighlightStringLiteral">" mark\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (di-&gt;<a href="/web-doxygen/docs/api/classes/diagramitem/#a11ec77d7b8a9920793793ead700627e1">virtualness</a>()==Specifier::Virtual) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"solid\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#ab1778365304892c7a24196f356222b18">convertToPSString</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/diagramitem/#ab0d5760c4d7ff79eb2ed90652a825b54">DiagramItem::label</a> and <a href="/web-doxygen/docs/api/classes/diagramitem/#a11ec77d7b8a9920793793ead700627e1">DiagramItem::virtualness</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a7916cd8dbb3b48d335e036c9717ac00d">TreeDiagram::drawBoxes</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### fontHeight {#aa13a42b6fd4f4b0c89be8c3bab657be3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t fontHeight = 12</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa13a42b6fd4f4b0c89be8c3bab657be3">146</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> uint32_t <a href="#aa13a42b6fd4f4b0c89be8c3bab657be3">fontHeight</a>       = 12;  </span><span class="doxyHighlightComment">// height of a character</span></span></div>

</div>


Referenced by <a href="#a4a6853a6b7f98f30da5d61d680d86041">writeBitmapBox</a> and <a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">ClassDiagram::writeImage</a>.
</div>
</div>

### gridHeight {#a993acabcec0ddbb0fc27ff4eb47b9368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t gridHeight = 100</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a993acabcec0ddbb0fc27ff4eb47b9368">141</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> uint32_t <a href="#a993acabcec0ddbb0fc27ff4eb47b9368">gridHeight</a> = 100;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a7916cd8dbb3b48d335e036c9717ac00d">TreeDiagram::drawBoxes</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a> and <a href="/web-doxygen/docs/api/classes/diagramrow/#a8c301e781bb14b1a23c00974d2050496">DiagramRow::insertClass</a>.
</div>
</div>

### gridWidth {#a2955a33900313eb54d0a7f5318421db7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t gridWidth = 100</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 140 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2955a33900313eb54d0a7f5318421db7">140</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> uint32_t <a href="#a2955a33900313eb54d0a7f5318421db7">gridWidth</a>  = 100;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a940a3aaf1985a9f2ff19dc95aa91716b">TreeDiagram::computeLayout</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a7916cd8dbb3b48d335e036c9717ac00d">TreeDiagram::drawBoxes</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a>, <a href="/web-doxygen/docs/api/classes/diagramrow/#a8c301e781bb14b1a23c00974d2050496">DiagramRow::insertClass</a>, <a href="/web-doxygen/docs/api/classes/classdiagram/#acb331a908252968ca8ba371ee560aa51">ClassDiagram::writeFigure</a> and <a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">ClassDiagram::writeImage</a>.
</div>
</div>

### labelHorMargin {#a1633af3b4b6c08d35ec5538e9f599543}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t labelHorMargin = 6</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 145 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1633af3b4b6c08d35ec5538e9f599543">145</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> uint32_t <a href="#a1633af3b4b6c08d35ec5538e9f599543">labelHorMargin</a>   = 6;   </span><span class="doxyHighlightComment">// horiz. spacing between label and box</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">ClassDiagram::writeImage</a>.
</div>
</div>

### labelHorSpacing {#a486228a1ff55861685b37025028df553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t labelHorSpacing = 10</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 143 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a486228a1ff55861685b37025028df553">143</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> uint32_t <a href="#a486228a1ff55861685b37025028df553">labelHorSpacing</a>  = 10;  </span><span class="doxyHighlightComment">// horizontal distance between labels</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a7916cd8dbb3b48d335e036c9717ac00d">TreeDiagram::drawBoxes</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a> and <a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">ClassDiagram::writeImage</a>.
</div>
</div>

### labelVertSpacing {#aefcc016999157bad4cd16a4b11656a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t labelVertSpacing = 32</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 144 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aefcc016999157bad4cd16a4b11656a87">144</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> uint32_t <a href="#aefcc016999157bad4cd16a4b11656a87">labelVertSpacing</a> = 32;  </span><span class="doxyHighlightComment">// vertical distance between labels</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a7916cd8dbb3b48d335e036c9717ac00d">TreeDiagram::drawBoxes</a>, <a href="/web-doxygen/docs/api/classes/treediagram/#a0993890eece743a86f2d874f288b6f7d">TreeDiagram::drawConnectors</a> and <a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">ClassDiagram::writeImage</a>.
</div>
</div>

### maxTreeWidth {#a08f611cf182c7d6d2e6c7b944c7511dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const uint32_t maxTreeWidth = 8</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a08f611cf182c7d6d2e6c7b944c7511dc">139</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> uint32_t <a href="#a08f611cf182c7d6d2e6c7b944c7511dc">maxTreeWidth</a> = 8;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/treediagram/#a940a3aaf1985a9f2ff19dc95aa91716b">TreeDiagram::computeLayout</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### IMAGE\_EXT {#addf4ae1173df3a2d96b5862df8960117}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define IMAGE_EXT&nbsp;&nbsp;&nbsp;".png"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1396 of file <a href="/web-doxygen/docs/api/files/src/diagram-cpp">diagram.cpp</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/classdiagram/#a79829a2cdb414f49e138e3df9eeb14cd">ClassDiagram::writeImage</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
