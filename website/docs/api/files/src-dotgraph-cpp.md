---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/dotgraph-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `dotgraph.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;mutex&gt;
#include &lt;regex&gt;
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>"
#include "md5.h"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotrunner-h">dotrunner.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotgraph-h">dotgraph.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotnode-h">dotnode.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a272779001504a5c1f52817f54569298f">sameMd5Signature</a> (const QCString &amp;baseName, const QCString &amp;md5)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad65fb794eac705b1f9e896602c59bbe">deliverablesPresent</a> (const QCString &amp;file1, const QCString &amp;file2)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a174bf83fed06cf0780ec37022bfb931c">insertMapFile</a> (TextStream &amp;out, const QCString &amp;mapFile, const QCString &amp;relPath, const QCString &amp;mapLabel)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4c77ee56010cac577323cba8c6a1ee4">g_dotIndexListMutex</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e61450eb94b16e866568ad3aed2d9f1">MAP_CMD</a>&nbsp;&nbsp;&nbsp;"cmapx"</td>
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

### deliverablesPresent() {#aad65fb794eac705b1f9e896602c59bbe}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool deliverablesPresent (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file1, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file2)</td>
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



<p>Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/dotgraph-cpp">dotgraph.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad65fb794eac705b1f9e896602c59bbe">69</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#aad65fb794eac705b1f9e896602c59bbe">deliverablesPresent</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;file2)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> file1Ok = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> file2Ok = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file1.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(file1.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">    file1Ok = (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a5b5da50c67491de7a7e96ee10ccb9b1a">size</a>()&gt;0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file2.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(file2.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">    file2Ok = (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a5b5da50c67491de7a7e96ee10ccb9b1a">size</a>()&gt;0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> file1Ok &amp;&amp; file2Ok;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a5b5da50c67491de7a7e96ee10ccb9b1a">FileInfo::size</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dotgraph/#a45d99cae5ecb12b8735454b57c505e42">DotGraph::prepareDotFile</a>.</p>

</div>
</div>

### insertMapFile() {#a174bf83fed06cf0780ec37022bfb931c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool insertMapFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; out, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; mapFile, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; mapLabel)</td>
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



<p>Definition at line 86 of file <a href="/web-doxygen/docs/api/files/src/dotgraph-cpp">dotgraph.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a174bf83fed06cf0780ec37022bfb931c">86</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a174bf83fed06cf0780ec37022bfb931c">insertMapFile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;out,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;mapFile,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">                          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;mapLabel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(mapFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() &amp;&amp; fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a5b5da50c67491de7a7e96ee10ccb9b1a">size</a>()&gt;0) </span><span class="doxyHighlightComment">// reuse existing map file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>(t,mapFile,relPath,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!t.<a href="/web-doxygen/docs/api/classes/textstream/#a0859a9bfd6a7b6bafc7050d9f3aef046">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">      out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;map name=\""</span><span class="doxyHighlight"> &lt;&lt; mapLabel &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" id=\""</span><span class="doxyHighlight"> &lt;&lt; mapLabel &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">      out &lt;&lt; t.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">      out &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/map&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// no map file yet, need to generate it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>, <a href="/web-doxygen/docs/api/classes/textstream/#a0859a9bfd6a7b6bafc7050d9f3aef046">TextStream::empty</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a5b5da50c67491de7a7e96ee10ccb9b1a">FileInfo::size</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dotgraph/#a456518c674e7ae8f45d4eea8935bdc38">DotGraph::generateCode</a>.</p>

</div>
</div>

### sameMd5Signature() {#a272779001504a5c1f52817f54569298f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool sameMd5Signature (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; baseName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; md5)</td>
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




<p>Checks if a file "baseName".md5 exists. If so the contents are compared with <em>md5</em>. If equal FALSE is returned. The .md5 is created or updated after successful creation of the output file.</p>


<p>Definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/dotgraph-cpp">dotgraph.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a272779001504a5c1f52817f54569298f">43</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a272779001504a5c1f52817f54569298f">sameMd5Signature</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">                             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;md5)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> same = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> md5stored[33];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  md5stored[0]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ifstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>(baseName+</span><span class="doxyHighlightStringLiteral">".md5"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// read checksum</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">    f.read(md5stored,32);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">    md5stored[32]=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// compare checksum</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.fail() &amp;&amp; md5==md5stored)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">      same = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("sameSignature(%s,%s==%s)=%d\n",qPrint(baseName),md5stored,qPrint(md5),same);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("sameSignature(%s) not found\n",qPrint(baseName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> same;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dotgraph/#a45d99cae5ecb12b8735454b57c505e42">DotGraph::prepareDotFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### g\_dotIndexListMutex {#ac4c77ee56010cac577323cba8c6a1ee4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_dotIndexListMutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 113 of file <a href="/web-doxygen/docs/api/files/src/dotgraph-cpp">dotgraph.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac4c77ee56010cac577323cba8c6a1ee4">113</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::mutex <a href="#ac4c77ee56010cac577323cba8c6a1ee4">g_dotIndexListMutex</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/dotgraph/#ae6cbbb6ad88d59dec93692d8c6f70a07">DotGraph::writeGraph</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### MAP\_CMD {#a8e61450eb94b16e866568ad3aed2d9f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define MAP_CMD&nbsp;&nbsp;&nbsp;"cmapx"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/dotgraph-cpp">dotgraph.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e61450eb94b16e866568ad3aed2d9f1">34</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define MAP_CMD "cmapx"</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
