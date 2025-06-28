---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/image-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `image.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;vector&gt;
#include &lt;cmath&gt;
#include "<a href="/web-doxygen/docs/api/files/src/image-h">image.h</a>"
#include "lodepng.h"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/color">Color</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper struct representing a RGBA color. <a href="/web-doxygen/docs/api/structs/color/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/image/private">Private</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/coloredimage/private">Private</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">typedef</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">unsigned char <a href="#ae3a497195d617519e5353ea7b417940f">Byte</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#addcb648439e446f4cdc7f81ed8bd7701">charSetWidth</a> =80</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac01e29ec591af8444cb2cb5e9128d130">charHeight</a> =12</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7039c6d467143b65eee4688f35178297">numChars</a> =96</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const unsigned short</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0deb38d89dca0124fc08d960657d74ed">charPos</a>[numChars] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b6c376e48d9e19606ef8b24815321de">charWidth</a>[numChars] = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const unsigned char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1f62b9caff0302178d5a0d73ac720239">fontRaw</a>[charSetWidth *charHeight]</td>
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

### Byte {#ae3a497195d617519e5353ea7b417940f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">typedef unsigned char Byte</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00023">23</a> of file <a href="/web-doxygen/docs/api/files/src/image-cpp">image.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae3a497195d617519e5353ea7b417940f">23</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">typedef</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">  <a href="#ae3a497195d617519e5353ea7b417940f">Byte</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### charHeight {#ac01e29ec591af8444cb2cb5e9128d130}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int charHeight =12</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00035">35</a> of file <a href="/web-doxygen/docs/api/files/src/image-cpp">image.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac01e29ec591af8444cb2cb5e9128d130">35</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ac01e29ec591af8444cb2cb5e9128d130">charHeight</a>=12;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/image/#ac240de8981834ae959fb666c8b878984">Image::writeChar</a>.
</div>
</div>

### charPos {#a0deb38d89dca0124fc08d960657d74ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned short charPos[numChars]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
  {
      0,  5,  8, 13, 20, 27, 38, 47,
     50, 54, 58, 65, 72, 76, 83, 87,
     91, 98,105,112,119,126,133,140,
    147,154,161,164,167,174,181,188,
    195,207,216,224,233,242,250,258,
    267,276,279,286,294,301,312,321,
    331,339,349,357,365,372,380,389,
    400,409,418,427,430,434,437,443,
    450,453,460,467,474,481,488,492,
    499,506,509,512,518,521,530,537,
    544,551,557,562,568,571,578,585,
    594,600,607,613,617,620,624,631
  }
</div>
</dd>
</dl>

<p>Definition at line <a href="#l00038">38</a> of file <a href="/web-doxygen/docs/api/files/src/image-cpp">image.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0deb38d89dca0124fc08d960657d74ed">38</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">short</span><span class="doxyHighlight"> <a href="#a0deb38d89dca0124fc08d960657d74ed">charPos</a>[<a href="#a7039c6d467143b65eee4688f35178297">numChars</a>]    =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">      0,  5,  8, 13, 20, 27, 38, 47,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">     50, 54, 58, 65, 72, 76, 83, 87,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">     91, 98,105,112,119,126,133,140,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">    147,154,161,164,167,174,181,188,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">    195,207,216,224,233,242,250,258,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">    267,276,279,286,294,301,312,321,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">    331,339,349,357,365,372,380,389,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">    400,409,418,427,430,434,437,443,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">    450,453,460,467,474,481,488,492,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">    499,506,509,512,518,521,530,537,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">    544,551,557,562,568,571,578,585,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">    594,600,607,613,617,620,624,631</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/image/#ac240de8981834ae959fb666c8b878984">Image::writeChar</a>.
</div>
</div>

### charSetWidth {#addcb648439e446f4cdc7f81ed8bd7701}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int charSetWidth =80</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00034">34</a> of file <a href="/web-doxygen/docs/api/files/src/image-cpp">image.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#addcb648439e446f4cdc7f81ed8bd7701">34</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#addcb648439e446f4cdc7f81ed8bd7701">charSetWidth</a>=80;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/image/#ac240de8981834ae959fb666c8b878984">Image::writeChar</a>.
</div>
</div>

### charWidth {#a1b6c376e48d9e19606ef8b24815321de}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char charWidth[numChars]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
  {
     5, 3, 5, 7, 7,11, 9, 3,
     4, 4, 7, 7, 4, 7, 4, 4,

     7, 7, 7, 7, 7, 7, 7, 7,
     7, 7, 3, 3, 7, 7, 7, 7,
    12, 9, 8, 9, 9, 8, 8, 9,
     9, 3, 7, 8, 7,11, 9,10,
     8,10, 8, 8, 7, 8, 9,11,
     9, 9, 9, 3, 4, 3, 6, 7,
     3, 7, 7, 7, 7, 7, 4, 7,
     7, 3, 3, 6, 3, 9, 7, 7,
     7, 6, 5, 6, 3, 7, 7, 9,
     6, 7, 6, 4, 3, 4, 7, 5
  }
</div>
</dd>
</dl>

<p>Definition at line <a href="#l00054">54</a> of file <a href="/web-doxygen/docs/api/files/src/image-cpp">image.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b6c376e48d9e19606ef8b24815321de">54</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="#a1b6c376e48d9e19606ef8b24815321de">charWidth</a>[<a href="#a7039c6d467143b65eee4688f35178297">numChars</a>] =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">     5, 3, 5, 7, 7,11, 9, 3,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">     4, 4, 7, 7, 4, 7, 4, 4,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">     7, 7, 7, 7, 7, 7, 7, 7,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">     7, 7, 3, 3, 7, 7, 7, 7,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">    12, 9, 8, 9, 9, 8, 8, 9,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">     9, 3, 7, 8, 7,11, 9,10,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">     8,10, 8, 8, 7, 8, 9,11,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">     9, 9, 9, 3, 4, 3, 6, 7,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">     3, 7, 7, 7, 7, 7, 4, 7,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">     7, 3, 3, 6, 3, 9, 7, 7,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">     7, 6, 5, 6, 3, 7, 7, 9,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">     6, 7, 6, 4, 3, 4, 7, 5</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/image/#af25a570683d7f6392bdba0bf433f6c30">Image::stringLength</a>, <a href="/web-doxygen/docs/api/classes/image/#ac240de8981834ae959fb666c8b878984">Image::writeChar</a> and <a href="/web-doxygen/docs/api/classes/image/#a9548b8956604519c4260cbdaf7854792">Image::writeString</a>.
</div>
</div>

### fontRaw {#a1f62b9caff0302178d5a0d73ac720239}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const unsigned char fontRaw[charSetWidth *charHeight]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00071">71</a> of file <a href="/web-doxygen/docs/api/files/src/image-cpp">image.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1f62b9caff0302178d5a0d73ac720239">71</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="#a1f62b9caff0302178d5a0d73ac720239">fontRaw</a>[<a href="#addcb648439e446f4cdc7f81ed8bd7701">charSetWidth</a>*<a href="#ac01e29ec591af8444cb2cb5e9128d130">charHeight</a>] = {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  0x02, 0x50, 0x01, 0x06, 0x20, 0x60, 0xc6, 0x04, 0x00, 0x00, 0x00, 0x27,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  0x04, 0x1c, 0x38, 0x11, 0xf1, 0xc7, 0xc7, 0x0e, 0x00, 0x00, 0x00, 0x03,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">  0x81, 0xf0, 0x10, 0x7c, 0x1e, 0x3e, 0x1f, 0x9f, 0x87, 0x88, 0x24, 0x09,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  0x09, 0x02, 0x02, 0x41, 0x0f, 0x0f, 0x83, 0xc3, 0xe1, 0xe7, 0xf4, 0x24,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  0x12, 0x22, 0x41, 0x20, 0x9f, 0xce, 0x30, 0x00, 0x10, 0x04, 0x00, 0x01,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x30, 0x08, 0x12, 0x41, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x40,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x01, 0xac, 0x00, 0x00, 0x02, 0x51, 0x43, 0x89,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  0x40, 0x90, 0x49, 0x15, 0x00, 0x00, 0x00, 0x28, 0x9c, 0x22, 0x44, 0x31,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  0x02, 0x20, 0x48, 0x91, 0x00, 0x00, 0x00, 0x04, 0x46, 0x08, 0x28, 0x42,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  0x21, 0x21, 0x10, 0x10, 0x08, 0x48, 0x24, 0x09, 0x11, 0x03, 0x06, 0x61,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  0x10, 0x88, 0x44, 0x22, 0x12, 0x10, 0x84, 0x24, 0x12, 0x22, 0x22, 0x20,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  0x80, 0x4a, 0x11, 0x00, 0x20, 0x04, 0x00, 0x01, 0x00, 0x40, 0x08, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  0x41, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x40, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  0x02, 0x22, 0x00, 0x00, 0x02, 0x51, 0x45, 0x49, 0x40, 0x90, 0x89, 0x0a,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x48, 0x84, 0x02, 0x04, 0x51, 0x02, 0x00, 0x88, 0x91,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x04, 0x44, 0xd4, 0x28, 0x42, 0x40, 0x20, 0x90, 0x10,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  0x10, 0x08, 0x24, 0x09, 0x21, 0x03, 0x06, 0x51, 0x20, 0x48, 0x48, 0x12,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  0x12, 0x00, 0x84, 0x22, 0x22, 0x22, 0x22, 0x11, 0x00, 0x89, 0x12, 0x80,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  0x31, 0xc5, 0x87, 0x0d, 0x1c, 0xe3, 0x4b, 0x12, 0x49, 0x29, 0x16, 0x1c,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  0x58, 0x69, 0x4c, 0xe8, 0x91, 0x44, 0x61, 0x44, 0xf2, 0x22, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  0x02, 0x07, 0xe5, 0x06, 0x80, 0x60, 0x10, 0x95, 0x08, 0x00, 0x00, 0x48,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  0x84, 0x04, 0x18, 0x51, 0xe2, 0xc0, 0x87, 0x11, 0x24, 0x18, 0x03, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  0x89, 0x24, 0x44, 0x42, 0x40, 0x20, 0x90, 0x10, 0x10, 0x08, 0x24, 0x09,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">  0x41, 0x02, 0x8a, 0x51, 0x20, 0x48, 0x48, 0x12, 0x11, 0x80, 0x84, 0x22,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">  0x21, 0x24, 0x14, 0x11, 0x01, 0x09, 0x14, 0x40, 0x02, 0x26, 0x48, 0x93,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  0x22, 0x44, 0xcc, 0x92, 0x51, 0x36, 0x99, 0x22, 0x64, 0x99, 0x92, 0x48,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  0x91, 0x44, 0x52, 0x44, 0x12, 0x22, 0x00, 0x00, 0x02, 0x01, 0x43, 0x80,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">  0x80, 0xa0, 0x10, 0x84, 0x08, 0x00, 0x00, 0x88, 0x84, 0x08, 0x04, 0x90,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  0x13, 0x21, 0x08, 0x8f, 0x00, 0x61, 0xf0, 0xc0, 0x8a, 0x24, 0x44, 0x7c,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  0x40, 0x20, 0x9f, 0x9f, 0x11, 0xcf, 0xe4, 0x09, 0xc1, 0x02, 0x8a, 0x49,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  0x20, 0x4f, 0x88, 0x13, 0xe0, 0x60, 0x84, 0x22, 0x21, 0x54, 0x08, 0x0a,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">  0x02, 0x08, 0x90, 0x00, 0x00, 0x24, 0x48, 0x11, 0x22, 0x44, 0x48, 0x92,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  0x61, 0x24, 0x91, 0x22, 0x44, 0x89, 0x10, 0x48, 0x91, 0x24, 0x8c, 0x44,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  0x22, 0x22, 0x64, 0x00, 0x02, 0x07, 0xe1, 0x41, 0x31, 0x14, 0x10, 0x80,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">  0x3e, 0x07, 0xc0, 0x88, 0x84, 0x10, 0x05, 0x10, 0x12, 0x21, 0x08, 0x81,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">  0x01, 0x80, 0x00, 0x31, 0x0a, 0x24, 0x7c, 0x42, 0x40, 0x20, 0x90, 0x10,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">  0x10, 0x48, 0x24, 0x09, 0x21, 0x02, 0x52, 0x45, 0x20, 0x48, 0x08, 0x92,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  0x20, 0x10, 0x84, 0x21, 0x41, 0x54, 0x14, 0x04, 0x04, 0x08, 0x90, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  0x01, 0xe4, 0x48, 0x11, 0x3e, 0x44, 0x48, 0x92, 0x61, 0x24, 0x91, 0x22,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">  0x44, 0x89, 0x0c, 0x48, 0x8a, 0x24, 0x8c, 0x48, 0x44, 0x21, 0x98, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">  0x02, 0x02, 0x85, 0x41, 0x49, 0x08, 0x10, 0x80, 0x08, 0x00, 0x00, 0x88,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  0x84, 0x20, 0x45, 0xf9, 0x12, 0x21, 0x08, 0x81, 0x00, 0x61, 0xf0, 0xc1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  0x0a, 0x68, 0x82, 0x42, 0x40, 0x20, 0x90, 0x10, 0x10, 0x48, 0x24, 0x89,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  0x11, 0x02, 0x52, 0x45, 0x20, 0x48, 0x08, 0x52, 0x12, 0x10, 0x84, 0x21,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  0x40, 0x88, 0x22, 0x04, 0x08, 0x08, 0x90, 0x00, 0x02, 0x24, 0x48, 0x11,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  0x20, 0x44, 0x48, 0x92, 0x51, 0x24, 0x91, 0x22, 0x44, 0x89, 0x02, 0x48,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  0x8a, 0x2a, 0x92, 0x28, 0x42, 0x22, 0x00, 0x00, 0x00, 0x02, 0x85, 0x41,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  0x49, 0x18, 0x10, 0x80, 0x08, 0x00, 0x01, 0x08, 0x84, 0x20, 0x44, 0x11,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  0x12, 0x22, 0x08, 0x91, 0x00, 0x18, 0x03, 0x00, 0x09, 0xb0, 0x82, 0x42,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  0x21, 0x21, 0x10, 0x10, 0x08, 0xc8, 0x24, 0x89, 0x09, 0x02, 0x22, 0x43,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  0x10, 0x88, 0x04, 0x22, 0x12, 0x10, 0x84, 0x20, 0x80, 0x88, 0x22, 0x04,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  0x10, 0x08, 0x50, 0x00, 0x02, 0x26, 0x48, 0x93, 0x22, 0x44, 0xc8, 0x92,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">  0x49, 0x24, 0x91, 0x22, 0x64, 0x99, 0x12, 0x49, 0x84, 0x11, 0x21, 0x28,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  0x82, 0x22, 0x00, 0x00, 0x02, 0x02, 0x83, 0x82, 0x30, 0xe4, 0x10, 0x80,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x20, 0x05, 0x07, 0x04, 0x3e, 0x38, 0x10, 0xe1, 0xc2, 0x07, 0x0e,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">  0x24, 0x00, 0x00, 0x01, 0x04, 0x00, 0x82, 0x7c, 0x1e, 0x3e, 0x1f, 0x90,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">  0x07, 0x48, 0x24, 0x71, 0x05, 0xf2, 0x22, 0x41, 0x0f, 0x08, 0x03, 0xd2,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  0x11, 0xe0, 0x83, 0xc0, 0x80, 0x88, 0x41, 0x04, 0x1f, 0xc8, 0x50, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  0x01, 0xd5, 0x87, 0x0d, 0x1c, 0x43, 0x48, 0x92, 0x45, 0x24, 0x91, 0x1c,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  0x58, 0x69, 0x0c, 0x66, 0x84, 0x11, 0x21, 0x10, 0xf2, 0x22, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x01, 0x00, 0x00, 0x00, 0x09, 0x00, 0x00, 0x20, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x04, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  0x03, 0xe0, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x00, 0x08, 0x10, 0x00, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x40, 0x02, 0x00, 0x00, 0x00, 0x00, 0x40, 0x08, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x10, 0x02, 0x22, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x09, 0x00, 0x00, 0x40, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x08, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x08, 0x10, 0x1f, 0xc0, 0x00, 0x00, 0x00, 0x00, 0x04, 0x40, 0x02,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x40, 0x08, 0x00, 0x00, 0x00, 0x00, 0x00, 0x20,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  0x02, 0x22, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x06, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x00, 0x0c, 0x30, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">  0x00, 0x00, 0x00, 0x00, 0x00, 0x03, 0x80, 0x04, 0x00, 0x00, 0x00, 0x00,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  0x40, 0x08, 0x00, 0x00, 0x00, 0x00, 0x00, 0x40, 0x01, 0xac, 0x00, 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/image/#ac240de8981834ae959fb666c8b878984">Image::writeChar</a>.
</div>
</div>

### numChars {#a7039c6d467143b65eee4688f35178297}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const int numChars =96</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00036">36</a> of file <a href="/web-doxygen/docs/api/files/src/image-cpp">image.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7039c6d467143b65eee4688f35178297">36</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a7039c6d467143b65eee4688f35178297">numChars</a>=96;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
