---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/tooltipmanager
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `TooltipManager` Class Reference

Class that manages the tooltips for a source file. <a href="#details">More...</a>

## Declaration

<div class="doxyDeclaration">
class TooltipManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/tooltip-h">src/tooltip.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad4c5424c1e07c7ee79236401c54b55c8">TooltipManager</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25e5789b8fb515cb4a295f2645061509">~TooltipManager</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a83c5141d20cfce3f391f36e0d9ace3d6">addTooltip</a> (const Definition *d)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
add a tooltip for a given symbol definition <a href="#a83c5141d20cfce3f391f36e0d9ace3d6">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9fabdb64f4fd1b5a5fded9d7dac90c3b">writeTooltips</a> (OutputCodeList &amp;ol)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
write the list of all collected tooltip to the given outputs <a href="#a9fabdb64f4fd1b5a5fded9d7dac90c3b">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/tooltipmanager/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa404b10145666b6973b91a7731e67217">p</a></td>
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

Class that manages the tooltips for a source file.

Definition at line 25 of file <a href="/web-doxygen/docs/api/files/src/tooltip-h">tooltip.h</a>.

<div class="doxySectionDef">

## Public Constructors

### TooltipManager() {#ad4c5424c1e07c7ee79236401c54b55c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TooltipManager::TooltipManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 28 of file <a href="/web-doxygen/docs/api/files/src/tooltip-h">tooltip.h</a>, definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/tooltip-cpp">tooltip.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad4c5424c1e07c7ee79236401c54b55c8">41</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#ad4c5424c1e07c7ee79236401c54b55c8">TooltipManager::TooltipManager</a>() : <a href="#aa404b10145666b6973b91a7731e67217">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/classes/tooltipmanager/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aa404b10145666b6973b91a7731e67217">p</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~TooltipManager() {#a25e5789b8fb515cb4a295f2645061509}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">TooltipManager::~TooltipManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 29 of file <a href="/web-doxygen/docs/api/files/src/tooltip-h">tooltip.h</a>, definition at line 45 of file <a href="/web-doxygen/docs/api/files/src/tooltip-cpp">tooltip.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a25e5789b8fb515cb4a295f2645061509">45</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a25e5789b8fb515cb4a295f2645061509">TooltipManager::~TooltipManager</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addTooltip() {#a83c5141d20cfce3f391f36e0d9ace3d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TooltipManager::addTooltip (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

add a tooltip for a given symbol definition

Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/tooltip-h">tooltip.h</a>, definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/tooltip-cpp">tooltip.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a83c5141d20cfce3f391f36e0d9ace3d6">56</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a83c5141d20cfce3f391f36e0d9ace3d6">TooltipManager::addTooltip</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sourceTooltips = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(SOURCE_TOOLTIPS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!sourceTooltips) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.right(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.length()-i-1); </span><span class="doxyHighlightComment">// strip path (for CREATE_SUBDIRS=YES)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// In case an extension is present translate this extension to something understood by the tooltip handler</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// otherwise extend t with a translated htmlFileExtension.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> currentExtension = <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (currentExtension.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> += <a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a618f6f860ec6268437b3e44d313d1f87">escapeId</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,currentExtension) + <a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a618f6f860ec6268437b3e44d313d1f87">escapeId</a>(currentExtension);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> anc = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anc.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">+=</span><span class="doxyHighlightStringLiteral">"_"</span><span class="doxyHighlight">+anc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = </span><span class="doxyHighlightStringLiteral">"a"</span><span class="doxyHighlight"> + id;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aa404b10145666b6973b91a7731e67217">p</a>-&gt;tooltipInfo.emplace(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">.str(),d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("%p: addTooltip(%s)\n",this,id.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a618f6f860ec6268437b3e44d313d1f87">escapeId</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#aa98afe79970170f82848bc45b0f076ec">Doxygen::htmlFileExtension</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aa404b10145666b6973b91a7731e67217">p</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a73d2ea8014e5ac678dac39cfd56ba148">stripExtensionGeneral</a>.
</div>
</div>

### writeTooltips() {#a9fabdb64f4fd1b5a5fded9d7dac90c3b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void TooltipManager::writeTooltips (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

write the list of all collected tooltip to the given outputs

Declaration at line 36 of file <a href="/web-doxygen/docs/api/files/src/tooltip-h">tooltip.h</a>, definition at line 89 of file <a href="/web-doxygen/docs/api/files/src/tooltip-cpp">tooltip.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9fabdb64f4fd1b5a5fded9d7dac90c3b">89</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9fabdb64f4fd1b5a5fded9d7dac90c3b">TooltipManager::writeTooltips</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp;ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  std::unordered_map&lt;int, std::unordered_set&lt;std::string&gt; &gt;::iterator it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// critical section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a2ad76ff3dd21154ebd52f74298f7c4fe">g_tooltipsFileMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = ol.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a6fdb262f6dcf3dc188a8c91814e9cba4">id</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    it = <a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a9b6cb3bf98d1845d47e6adb5872161af">g_tooltipsWrittenPerFile</a>.find(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a9b6cb3bf98d1845d47e6adb5872161af">g_tooltipsWrittenPerFile</a>.end()) </span><span class="doxyHighlightComment">// new file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">      it = <a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a9b6cb3bf98d1845d47e6adb5872161af">g_tooltipsWrittenPerFile</a>.emplace(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,std::unordered_set&lt;std::string&gt;()).first;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,d] : <a href="#aa404b10145666b6973b91a7731e67217">p</a>-&gt;tooltipInfo)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> written = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// critical section</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">      std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a8a3ee38616df2e8b83a710e63f559f75">g_tooltipsTipMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      written = it-&gt;second.find(name)!=it-&gt;second.end();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!written) </span><span class="doxyHighlightComment">// only write tooltips once</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        it-&gt;second.insert(name); </span><span class="doxyHighlightComment">// remember we wrote this tooltip for the given file id</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!written)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("%p: writeTooltips(%s) ol=%d\n",this,name.c_str(),ol.id());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/doclinkinfo">DocLinkInfo</a> docInfo;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">      docInfo.<a href="/web-doxygen/docs/api/structs/doclinkinfo/#a92c73ddcfa2201e6b0029f4b4e64458b">name</a>   = d-&gt;qualifiedName();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">      docInfo.<a href="/web-doxygen/docs/api/structs/doclinkinfo/#abe4bbcd9b1709f58b0b29a9020c42e42">ref</a>    = d-&gt;getReference();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">      docInfo.<a href="/web-doxygen/docs/api/structs/doclinkinfo/#a7607f6298e3e16dd3ef26d2f823bbb9c">url</a>    = d-&gt;getOutputFileBase();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">      docInfo.<a href="/web-doxygen/docs/api/structs/doclinkinfo/#a2827af934ddee422d0f8711c9889f5e8">anchor</a> = d-&gt;anchor();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> defInfo;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;getBodyDef() &amp;&amp; d-&gt;getStartBodyLine()!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">        defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a17c887dc311b8da42681dc4e9803692d">file</a>    = d-&gt;getBodyDef()-&gt;name();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">        defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#abff71a239d4a657ea1543c0426b5726c">line</a>    = d-&gt;getStartBodyLine();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">        defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#af1fd0f6d7c9418bf922d33d591d7f196">url</a>     = d-&gt;getSourceFileBase();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">        defInfo.<a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a3a271e40098bce60ea2d71f452be7fa6">anchor</a>  = d-&gt;getSourceAnchor();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/sourcelinkinfo">SourceLinkInfo</a> declInfo; </span><span class="doxyHighlightComment">// TODO: fill in...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> decl;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d-&gt;definitionType()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">isAnonymous</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">          decl = md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a1003f3dd9b61ac1d8e115600f8ffaa06">declaration</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">      ol.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a81f3db752795807f3c67e25f6fdcb081">writeTooltip</a>(name.c_str(),    </span><span class="doxyHighlightComment">// id</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">          docInfo,                         </span><span class="doxyHighlightComment">// symName</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">          decl,                            </span><span class="doxyHighlightComment">// decl</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">          d-&gt;briefDescriptionAsTooltip(),  </span><span class="doxyHighlightComment">// desc</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">          defInfo,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">          declInfo</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/doclinkinfo/#a2827af934ddee422d0f8711c9889f5e8">DocLinkInfo::anchor</a>, <a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a3a271e40098bce60ea2d71f452be7fa6">SourceLinkInfo::anchor</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a1003f3dd9b61ac1d8e115600f8ffaa06">MemberDef::declaration</a>, <a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#a17c887dc311b8da42681dc4e9803692d">SourceLinkInfo::file</a>, <a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a2ad76ff3dd21154ebd52f74298f7c4fe">g\_tooltipsFileMutex</a>, <a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a8a3ee38616df2e8b83a710e63f559f75">g\_tooltipsTipMutex</a>, <a href="/web-doxygen/docs/api/files/src/tooltip-cpp/#a9b6cb3bf98d1845d47e6adb5872161af">g\_tooltipsWrittenPerFile</a>, <a href="/web-doxygen/docs/api/classes/outputcodelist/#a6fdb262f6dcf3dc188a8c91814e9cba4">OutputCodeList::id</a>, <a href="/web-doxygen/docs/api/classes/definition/#a8f18141678a6bf5fb86e8de29bc0f1cd">Definition::isAnonymous</a>, <a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#abff71a239d4a657ea1543c0426b5726c">SourceLinkInfo::line</a>, <a href="/web-doxygen/docs/api/structs/doclinkinfo/#a92c73ddcfa2201e6b0029f4b4e64458b">DocLinkInfo::name</a>, <a href="#aa404b10145666b6973b91a7731e67217">p</a>, <a href="/web-doxygen/docs/api/structs/doclinkinfo/#abe4bbcd9b1709f58b0b29a9020c42e42">DocLinkInfo::ref</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a>, <a href="/web-doxygen/docs/api/structs/doclinkinfo/#a7607f6298e3e16dd3ef26d2f823bbb9c">DocLinkInfo::url</a>, <a href="/web-doxygen/docs/api/structs/sourcelinkinfo/#af1fd0f6d7c9418bf922d33d591d7f196">SourceLinkInfo::url</a> and <a href="/web-doxygen/docs/api/classes/outputcodelist/#a81f3db752795807f3c67e25f6fdcb081">OutputCodeList::writeTooltip</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#aa404b10145666b6973b91a7731e67217}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; TooltipManager::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/tooltip-h">tooltip.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa404b10145666b6973b91a7731e67217">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#aa404b10145666b6973b91a7731e67217">p</a>;</span></span></div>

</div>


Referenced by <a href="#a83c5141d20cfce3f391f36e0d9ace3d6">addTooltip</a>, <a href="#ad4c5424c1e07c7ee79236401c54b55c8">TooltipManager</a> and <a href="#a9fabdb64f4fd1b5a5fded9d7dac90c3b">writeTooltips</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/tooltip-cpp">tooltip.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/tooltip-h">tooltip.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
