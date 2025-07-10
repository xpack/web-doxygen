---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/docbookvisitor-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `docbookvisitor.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filename-h">filename.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/msc-h">msc.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dia-h">dia.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/plantuml-h">plantuml.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/codefragment-h">codefragment.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/cite-h">cite.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2696c55cf5da503843057747b989140c">filterId</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e2036260f430686eab1509bb5087359">supportedHtmlAttribute</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a973cf8133612a97554efd32640eef752">makeShortName</a> (const QCString &amp;baseName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7cb6b1e61aa0556ab096f11e04418b99">DB_VIS_C</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af12ed68841c0b4918c498797ef0d9312">DB_VIS_C1</a>(x)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac625b8993c09e0adefac75dd2be11f80">DB_VIS_C2</a>(y)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">#define</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a836d3f613efc3b01def439656e51e428">DB_VIS_C2a</a>(x, y)</td>
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

### filterId() {#a2696c55cf5da503843057747b989140c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString filterId (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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



<p>Definition at line 52 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2696c55cf5da503843057747b989140c">52</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a2696c55cf5da503843057747b989140c">filterId</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> growBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a7aadcbc3d02fe6e01acf45d892cff0ba">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">:  growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight">);   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:   growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(c);       </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">  growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">get</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">GrowBuf::addChar</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">GrowBuf::addStr</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a7aadcbc3d02fe6e01acf45d892cff0ba">GrowBuf::clear</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">GrowBuf::get</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab7fced02c41e630be0ba0d38ec7445e4">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5b206a0c1382df26146e64cde69d1085">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a3db2ddaf8249d9e473d5fd51f106efd8">DocbookDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a2ed70425e19b1b76c43d7c2fa497e289">DocbookDocVisitor::operator()</a>.</p>

</div>
</div>

### makeBaseName() {#a809219d7701732d9db2bbfef99c3e86b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString makeBaseName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 98 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a809219d7701732d9db2bbfef99c3e86b">98</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = <a href="#a973cf8133612a97554efd32640eef752">makeShortName</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = result.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">    result=result.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a> and <a href="#a973cf8133612a97554efd32640eef752">makeShortName</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ab9411b5e1c0b790a6427ac73dec643f2">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a3f3e26e49bf3e76bc2b4ab003b2f79f4">DocbookDocVisitor::startDiaFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#afe30a1c1a560e4a85206dc7623a17dc4">LatexDocVisitor::startDiaFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5e78b0ed5635b833b739d63dafe452ff">DocbookDocVisitor::startDotFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aa197e546b10f737e78020b97fdf23cb9">LatexDocVisitor::startDotFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5b2c9442335fc951437fc0cfb466c90c">DocbookDocVisitor::startMscFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aeef2a244f24ea46106204e063fae5273">LatexDocVisitor::startMscFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#adbd00a8643be133e0b0cbef298202eeb">DocbookDocVisitor::startPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aa42bf16168d38b6ac210c3f17bef7510">LatexDocVisitor::startPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a83690d197c135515366011602fa36f34">HtmlDocVisitor::writeDiaFile</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a37a4b0291dcc41a9b1072757d344b546">RTFDocVisitor::writeDiaFile</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a3264ee5213c549e45cd13604e62e7719">HtmlDocVisitor::writeDotFile</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a286a80b0680a1b0defb947466bea6762">RTFDocVisitor::writeDotFile</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a928ca1eefc8caee8adbf197d19f9d687">HtmlDocVisitor::writeMscFile</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ab70c2bad1c74761849c430861ec0d2da">RTFDocVisitor::writeMscFile</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a2ed6deb26c33df9ea8b4bc30734be81b">HtmlDocVisitor::writePlantUMLFile</a> and <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a8aaf0de986f15251aaa6221d226ab55a">RTFDocVisitor::writePlantUMLFile</a>.</p>

</div>
</div>

### makeShortName() {#a973cf8133612a97554efd32640eef752}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString makeShortName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; baseName)</td>
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



<p>Definition at line 87 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a973cf8133612a97554efd32640eef752">87</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a973cf8133612a97554efd32640eef752">makeShortName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = baseName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = result.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">    result=result.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>.</p>


<p>Referenced by <a href="#a809219d7701732d9db2bbfef99c3e86b">makeBaseName</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aab82ef451cf5eff26b1d097aefd8d421">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4931bb0ccd2eb4d8aede2a9afb7058d6">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#ac4fd6827ed35896d1c9e47d264d12a85">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aa42bf16168d38b6ac210c3f17bef7510">LatexDocVisitor::startPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a6db6e8f6eb6422a68ea68af67795231f">DocbookDocVisitor::writeDiaFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a168f142f518c0734df4301ca492859d1">LatexDocVisitor::writeDiaFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0bf39b3fd2c1a92324de55df8009ed60">DocbookDocVisitor::writeDotFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a370d999e7360a39203535dff006b1bf2">DocbookDocVisitor::writeMscFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ada18505ac90bb92f4ce279d503dba853">LatexDocVisitor::writeMscFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab259d2b0e06461957346bd3de5bb52e0">DocbookDocVisitor::writePlantUMLFile</a> and <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a92275d99afc832afc51d7e0deec3afe6">LatexDocVisitor::writePlantUMLFile</a>.</p>

</div>
</div>

### supportedHtmlAttribute() {#a9e2036260f430686eab1509bb5087359}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool supportedHtmlAttribute (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



<p>Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e2036260f430686eab1509bb5087359">71</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9e2036260f430686eab1509bb5087359">supportedHtmlAttribute</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> (name==</span><span class="doxyHighlightStringLiteral">"align"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">          name==</span><span class="doxyHighlightStringLiteral">"bgcolor"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">          name==</span><span class="doxyHighlightStringLiteral">"border"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">          name==</span><span class="doxyHighlightStringLiteral">"cellpadding"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">          name==</span><span class="doxyHighlightStringLiteral">"cellspacing"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">          name==</span><span class="doxyHighlightStringLiteral">"class"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">          name==</span><span class="doxyHighlightStringLiteral">"frame"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">          name==</span><span class="doxyHighlightStringLiteral">"label"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">          name==</span><span class="doxyHighlightStringLiteral">"style"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">          name==</span><span class="doxyHighlightStringLiteral">"width"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">          name==</span><span class="doxyHighlightStringLiteral">"tabstyle"</span><span class="doxyHighlight"> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">          name==</span><span class="doxyHighlightStringLiteral">"title"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a9ecd666271d67f9e23a18d15f1f259e7">DocbookDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab21bc8c6017db61778cf6e60cea89abe">DocbookDocVisitor::operator()</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DB\_VIS\_C {#a7cb6b1e61aa0556ab096f11e04418b99}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_VIS_C</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7cb6b1e61aa0556ab096f11e04418b99">46</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_VIS_C</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ace8d7feef248a290d19da45c81f0ea26">DocbookDocVisitor::DocbookDocVisitor</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0c5e2bcbdfe6dc01259ed748ca1fc0fa">DocbookDocVisitor::endDiaFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a7d88687aa2a9c7544925377d4a967fc8">DocbookDocVisitor::endDotFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4e805a87b4b320f63f31b6d29fe8bbd6">DocbookDocVisitor::endLink</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ac5fa71d08ee9df28f986474abcf9eaf3">DocbookDocVisitor::endMscFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a64e204c832acb152c1909f650536d550">DocbookDocVisitor::endPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a1163472a0d3b1cc3359afdd861966aee">DocbookDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab7fced02c41e630be0ba0d38ec7445e4">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a6316cd4b961705e7c3bfee3d7628af09">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ae5fcc77a1bf0ac87ca740473f83ce834">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5b206a0c1382df26146e64cde69d1085">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a789f7802c80a054fd7ee0d9e5f2fb4dc">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4f170949904015a222fd834618f71046">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0eca51c43b643d592b22070d062a3b77">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a633ea27d943ce438a831b1043b37af8c">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a391493662c00d8761a7b1817c0c6e6d7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a3db2ddaf8249d9e473d5fd51f106efd8">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ae5c4df795b9cbaacf62f451369d4ed53">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a2ed70425e19b1b76c43d7c2fa497e289">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a9ecd666271d67f9e23a18d15f1f259e7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a73a37d31a03800401baf118ecad9e7d8">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a3a24a7573ff52b20b5b852a72eb779a3">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a52bcad32fdbc97d73c81802524cfce1c">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a9392f6b1374f2be71799e29b52e27c29">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#adc99d97063bc21b16852e5345a5ff4f0">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a2ef300f18d17dba697499319c88c8eb7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab3dc4aca49387c2801b733951162e52c">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab21bc8c6017db61778cf6e60cea89abe">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a14f3e3855449c3ee44c7e988e2fc4c38">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab9d3c8796370b41a72f6158fa461f5ca">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aab82ef451cf5eff26b1d097aefd8d421">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a1abe1e85619493e4e99240d290c3bdd2">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a1f5c051f908207108e9a88c130a79703">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a2df620c0b51848655090f6d5e7ee5c26">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aa29700a65140a358d78dbb9b46f3e520">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#abd98eb5e7a8634efc8df1ed1580ac99a">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ac2e45c96a087cd77d7c8bd55c7c46a6e">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a29f23f1bb1c5d9e7c00ca23bae19be54">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5aa189a4fd5b9a6ff4647ffc13e70978">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aa1add073cbb95e81ea333d8528797784">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a85d9cb1979f0d09164d205bfd447b494">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#acfb18992e55be4c79b5dad6a8b8ae4b7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a986a7c2b2b0094683654ef479b0204ef">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ac3af5572195fe68a70f0692dc9ab2ea3">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#af1963a24dee9df501c8f65d4cdc02584">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a7f022b87284463cbdd463a89f13d7694">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a01dac5e12f73fbc5dd499dca9b16c946">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aea2df716439077851a238f878500460e">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aad39609386bf77fe37c6e6a3861e92c5">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aff7829d4c3cf2759e0eca9b3abbc5173">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a04c01d6cac8654f0a25efcf25fb783d6">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5d1246ae30e71d074a6fb40c745494cc">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a942b617cd956361afbd314539cab5922">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a7020b73e1f3135df92e8becc99fcacb4">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aa5dd013610540bba019aaef10157b416">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#af30a5c4fe2669a2bdb78dd0c964af909">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab9b9df7cb5c9cf603f903416f7b31bca">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ad654cd7e66da83fdf2ff02f9bdcf34fd">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aca919f8124510f7e03ef62e8def34408">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a4931bb0ccd2eb4d8aede2a9afb7058d6">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a14b0a6b57523bfcdf584ce2b3f14e1fd">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab014c099dfdb3ac2e7cda9129c153253">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0e98d6606eee027d17aebcbe7ad90c85">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#aa9a4faa0f71f2de7b7d2dad36d9af4e7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a3f3e26e49bf3e76bc2b4ab003b2f79f4">DocbookDocVisitor::startDiaFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5e78b0ed5635b833b739d63dafe452ff">DocbookDocVisitor::startDotFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a32ae4842f51bff5b91ddb9f00815ddb0">DocbookDocVisitor::startLink</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5b2c9442335fc951437fc0cfb466c90c">DocbookDocVisitor::startMscFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#adbd00a8643be133e0b0cbef298202eeb">DocbookDocVisitor::startPlantUmlFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a6db6e8f6eb6422a68ea68af67795231f">DocbookDocVisitor::writeDiaFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0bf39b3fd2c1a92324de55df8009ed60">DocbookDocVisitor::writeDotFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a370d999e7360a39203535dff006b1bf2">DocbookDocVisitor::writeMscFile</a> and <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab259d2b0e06461957346bd3de5bb52e0">DocbookDocVisitor::writePlantUMLFile</a>.</p>

</div>
</div>

### DB\_VIS\_C1 {#af12ed68841c0b4918c498797ef0d9312}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_VIS_C1(x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af12ed68841c0b4918c498797ef0d9312">47</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_VIS_C1(x)</span></span></div>

</div>

</div>
</div>

### DB\_VIS\_C2 {#ac625b8993c09e0adefac75dd2be11f80}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_VIS_C2(y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 48 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac625b8993c09e0adefac75dd2be11f80">48</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_VIS_C2(y)</span></span></div>

</div>

</div>
</div>

### DB\_VIS\_C2a {#a836d3f613efc3b01def439656e51e428}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_VIS_C2a(x, y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/docbookvisitor-cpp">docbookvisitor.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a836d3f613efc3b01def439656e51e428">49</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_VIS_C2a(x,y)</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
