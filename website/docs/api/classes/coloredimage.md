---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/coloredimage
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `ColoredImage` Class Reference

<p>Class representing a bitmap image colored based on hue/sat/gamma settings. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ColoredImage { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/image-h">src/image.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3906bc1e14d1e528b1ab1db940905a1">ColoredImage</a> (uint32_t width, uint32_t height, const uint8_t *greyLevels, const uint8_t *alphaLevels, int saturation, int hue, int gamma)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15d68911020c041ae76934d6e9bf4806">~ColoredImage</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae4a3366368b665b83c8b821fd9bdeae7">save</a> (const QCString &amp;fileName)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/coloredimage/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa28cffecb75cf52b6b457178851704c5">hsl2rgb</a> (double h, double s, double l, double *pRed, double *pGreen, double *pBlue)</td>
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

<p>Class representing a bitmap image colored based on hue/sat/gamma settings.</p>

<p>Definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/image-h">image.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### ColoredImage() {#ab3906bc1e14d1e528b1ab1db940905a1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ColoredImage::ColoredImage (uint32_t width, uint32_t height, const uint8_t * greyLevels, const uint8_t * alphaLevels, int saturation, int hue, int gamma)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 58 of file <a href="/web-doxygen/docs/api/files/src/image-h">image.h</a>, definition at line 432 of file <a href="/web-doxygen/docs/api/files/src/image-cpp">image.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab3906bc1e14d1e528b1ab1db940905a1">432</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ab3906bc1e14d1e528b1ab1db940905a1">ColoredImage::ColoredImage</a>(uint32_t width,uint32_t height,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> uint8_t *greyLevels,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> uint8_t *alphaLevels,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> saturation,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> hue,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> gamma) : <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/coloredimage/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;hasAlpha = alphaLevels!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;width    = width;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;height   = height;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;data.resize(width*height*4);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (uint32_t i=0;i&lt;width*height;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> red=0.0, green=0.0, blue=0.0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa28cffecb75cf52b6b457178851704c5">hsl2rgb</a>(hue/360.0,                            </span><span class="doxyHighlightComment">// hue</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">            saturation/255.0,                     </span><span class="doxyHighlightComment">// saturation</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">            pow(greyLevels[i]/255.0,gamma/100.0), </span><span class="doxyHighlightComment">// luma (gamma corrected)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">            &amp;red,&amp;green,&amp;blue);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/image-cpp/#ae3a497195d617519e5353ea7b417940f">Byte</a> r = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/image-cpp/#ae3a497195d617519e5353ea7b417940f">Byte</a></span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(red  *255.0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/image-cpp/#ae3a497195d617519e5353ea7b417940f">Byte</a> g = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/image-cpp/#ae3a497195d617519e5353ea7b417940f">Byte</a></span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(green*255.0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/image-cpp/#ae3a497195d617519e5353ea7b417940f">Byte</a> b = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/image-cpp/#ae3a497195d617519e5353ea7b417940f">Byte</a></span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(blue *255.0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/image-cpp/#ae3a497195d617519e5353ea7b417940f">Byte</a> a = alphaLevels ? alphaLevels[i] : 255;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;data[i*4+0]=r;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;data[i*4+1]=g;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;data[i*4+2]=b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;data[i*4+3]=a;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#aa28cffecb75cf52b6b457178851704c5">hsl2rgb</a> and <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>.</p>


<p>Referenced by <a href="#a15d68911020c041ae76934d6e9bf4806">~ColoredImage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~ColoredImage() {#a15d68911020c041ae76934d6e9bf4806}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ColoredImage::~ColoredImage ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/image-h">image.h</a>.</p>


<p>Reference <a href="#ab3906bc1e14d1e528b1ab1db940905a1">ColoredImage</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### save() {#ae4a3366368b665b83c8b821fd9bdeae7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ColoredImage::save (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 64 of file <a href="/web-doxygen/docs/api/files/src/image-h">image.h</a>, definition at line 460 of file <a href="/web-doxygen/docs/api/files/src/image-cpp">image.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae4a3366368b665b83c8b821fd9bdeae7">460</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ae4a3366368b665b83c8b821fd9bdeae7">ColoredImage::save</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">  uint8_t *buffer = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> bufferSize = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">  LodePNG_Encoder encoder;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">  LodePNG_Encoder_init(&amp;encoder);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">  encoder.infoPng.color.colorType = <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;hasAlpha ? 6 : 2; </span><span class="doxyHighlightComment">// 2=RGB 24 bit, 6=RGBA 32 bit</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">  encoder.infoRaw.color.colorType = 6; </span><span class="doxyHighlightComment">// 6=RGBA 32 bit</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">  LodePNG_encode(&amp;encoder, &amp;buffer, &amp;bufferSize, &amp;<a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;data[0], <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;width, <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>-&gt;height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">  LodePNG_saveFile(buffer, bufferSize, fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">  LodePNG_Encoder_cleanup(&amp;encoder);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">  free(buffer);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#af543a98b46249a2b115f47f0166e9a81">writeColoredImgData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#ac2cba7e2fb5d732880c34fd62fdbdf8a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; ColoredImage::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/image-h">image.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#ac2cba7e2fb5d732880c34fd62fdbdf8a">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ab3906bc1e14d1e528b1ab1db940905a1">ColoredImage</a> and <a href="#ae4a3366368b665b83c8b821fd9bdeae7">save</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### hsl2rgb() {#aa28cffecb75cf52b6b457178851704c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ColoredImage::hsl2rgb (double h, double s, double l, double * pRed, double * pGreen, double * pBlue)</td>
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



<p>Declaration at line 65 of file <a href="/web-doxygen/docs/api/files/src/image-h">image.h</a>, definition at line 368 of file <a href="/web-doxygen/docs/api/files/src/image-cpp">image.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa28cffecb75cf52b6b457178851704c5">368</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa28cffecb75cf52b6b457178851704c5">ColoredImage::hsl2rgb</a>(</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> h,</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> s,</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> l,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">                         </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> *pRed,</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> *pGreen,</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> *pBlue)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> r = l;   </span><span class="doxyHighlightComment">// default to gray</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> g = l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> b = l;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> v = (l &lt;= 0.5) ? (l * (1.0 + s)) : (l + s - l * s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (v &gt; 0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> m       = l + l - v;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> sv      = ( v - m ) / v;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">    h      *= 6.0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> sextant = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(h);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> fract   = h - sextant;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> vsf     = v * sv * fract;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> mid1    = m + vsf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> mid2    = v - vsf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (sextant)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 0:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">        r = v;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">        g = mid1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">        b = m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 1:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">        r = mid2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">        g = v;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">        b = m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 2:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">        r = m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">        g = v;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">        b = mid1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 3:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">        r = m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">        g = mid2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">        b = v;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 4:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">        r = mid1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">        g = m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">        b = v;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 5:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">        r = v;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">        g = m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">        b = mid2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">  *pRed   = r;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">  *pGreen = g;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">  *pBlue  = b;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="#ab3906bc1e14d1e528b1ab1db940905a1">ColoredImage</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a683792f7f7df231861acd54ff905211d">getDirectoryBackgroundColor</a>, <a href="/web-doxygen/docs/api/classes/image/#af2e9cc7a6c902dc1d3905d23a8be7cf2">Image::Image</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/image-cpp">image.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/image-h">image.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
