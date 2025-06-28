---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/docbookgen-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `docbookgen.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdlib.h&gt;
#include "<a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classlist-h">classlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/diagram-h">diagram.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/defargs-h">defargs.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotcallgraph-h">dotcallgraph.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotclassgraph-h">dotclassgraph.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotdirdeps-h">dotdirdeps.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotgroupcollaboration-h">dotgroupcollaboration.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotincldepgraph-h">dotincldepgraph.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/pagedef-h">pagedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filename-h">filename.h</a>"
#include "version.h"
#include "<a href="/web-doxygen/docs/api/files/src/docbookvisitor-h">docbookvisitor.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberdef-h">memberdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/growbuf-h">growbuf.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a598af556233ed34c685184d9e0741c3e">writeDocbookString</a> (TextStream &amp;t, const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ecdf365ec90cd93f558ce01423a6568">writeDocbookCodeString</a> (bool hide, TextStream &amp;t, const QCString &amp;str, size_t &amp;col, size_t stripIndentAmount)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac174bf305a6b97803492e067a2f8dd77">addIndexTerm</a> (TextStream &amp;t, QCString prim, QCString sec="")</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a748b4a218a6a5cd91bd9fdcf939b9c3c">writeDocbookLink</a> (TextStream &amp;t, const QCString &amp;, const QCString &amp;compoundId, const QCString &amp;anchorId, const QCString &amp;text, const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a311635f4bd437fd28ab5fe0f0309f15d">objectLinkToString</a> (const QCString &amp;, const QCString &amp;f, const QCString &amp;anchor, const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a> (const QCString &amp;s, const bool retainNewline)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static constexpr auto</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1748a7403991604b7f600589b77f9937">hex</a> ="0123456789ABCDEF"</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72e66067731a340037c60b0774b24ef4">Docbook_DB</a>(x)&nbsp;&nbsp;&nbsp;do {} while(0)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aad86f7a60609e9852bce76f5a1626d5a">DB_GEN_C1</a>(x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9e8d60bb28488aa27ff42b3c5907437">DB_GEN_C2</a>(y)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6f0e27e5a10a97d88bb77b84d6d42481">DB_GEN_C2a</a>(x, y)</td>
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

### addIndexTerm() {#ac174bf305a6b97803492e067a2f8dd77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addIndexTerm (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> prim, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sec="")</td>
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


<p>Definition at line <a href="#l00138">138</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac174bf305a6b97803492e067a2f8dd77">138</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac174bf305a6b97803492e067a2f8dd77">addIndexTerm</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> prim, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sec = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;indexterm&gt;&lt;primary&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; <a href="#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(prim);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/primary&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!sec.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;secondary&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; <a href="#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(sec);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/secondary&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/indexterm&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aaa8fd7d7ca213ca44cfc5f90aae724e2">DocbookGenerator::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aca2bba69055abb8a7a7ea9ce8ce7f11f">DocbookGenerator::endTitleHead</a> and <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a8ae15cadac821acb3d6ecfb6c541d6b9">DocbookGenerator::startMemberDoc</a>.
</div>
</div>

### convertToDocBook() {#a7c12b32b5b825c9fc989731c66ba1933}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString convertToDocBook (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, const bool retainNewline)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Converts a string to an DocBook-encoded string</p>

<p>Definition at line <a href="#l01482">1482</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7c12b32b5b825c9fc989731c66ba1933">1482</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> retainNewline)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1483</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1484</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1485</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> growBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1486</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1487</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *q = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1488</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cnt = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1489</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1490</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1491</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1492</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1493</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1494</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">: </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retainNewline) growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"&lt;literallayout&gt;&amp;#160;&amp;#xa;&lt;/literallayout&gt;"</span><span class="doxyHighlight">); growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(c);   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1495</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">:  growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"&amp;lt;"</span><span class="doxyHighlight">);   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1496</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">:  growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"&amp;gt;"</span><span class="doxyHighlight">);   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1497</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">:  </span><span class="doxyHighlightComment">// possibility to have a special symbol</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1498</span><span class="doxyLineContent"><span class="doxyHighlight">        q = p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1499</span><span class="doxyLineContent"><span class="doxyHighlight">        cnt = 2; </span><span class="doxyHighlightComment">// we have to count &amp; and ; as well</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1500</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((*q &gt;= </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; *q &lt;= </span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">) || (*q &gt;= </span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> &amp;&amp; *q &lt;= </span><span class="doxyHighlightCharLiteral">'Z'</span><span class="doxyHighlight">) || (*q &gt;= </span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight"> &amp;&amp; *q &lt;= </span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1501</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1502</span><span class="doxyLineContent"><span class="doxyHighlight">          cnt++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1503</span><span class="doxyLineContent"><span class="doxyHighlight">          q++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1504</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1505</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*q == </span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1506</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1507</span><span class="doxyLineContent"><span class="doxyHighlight">           --p; </span><span class="doxyHighlightComment">// we need &amp; as well</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1508</span><span class="doxyLineContent"><span class="doxyHighlight">           <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> res = <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#af0c3a82ead9d9f041131d3bf6ebf9f35">name2sym</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(p).left(cnt));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1509</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res == <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">HtmlEntityMapper::Sym_Unknown</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1510</span><span class="doxyLineContent"><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1511</span><span class="doxyLineContent"><span class="doxyHighlight">             p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1512</span><span class="doxyLineContent"><span class="doxyHighlight">             growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"&amp;amp;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1513</span><span class="doxyLineContent"><span class="doxyHighlight">           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1514</span><span class="doxyLineContent"><span class="doxyHighlight">           </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1515</span><span class="doxyLineContent"><span class="doxyHighlight">           {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1516</span><span class="doxyLineContent"><span class="doxyHighlight">             growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().docbook(res));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1517</span><span class="doxyLineContent"><span class="doxyHighlight">             q++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1518</span><span class="doxyLineContent"><span class="doxyHighlight">             p = q;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1519</span><span class="doxyLineContent"><span class="doxyHighlight">           }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1520</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1521</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1522</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1523</span><span class="doxyLineContent"><span class="doxyHighlight">          growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"&amp;amp;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1524</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1525</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1526</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">: growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"&amp;apos;"</span><span class="doxyHighlight">); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1527</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:  growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"&amp;quot;"</span><span class="doxyHighlight">); </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1528</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight">  1: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight">  2: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight">  3: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight">  4: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight">  5: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight">  6: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 7:  </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight">  8:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1529</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 11: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 12: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 14: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 15: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 16: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 17: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 18:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1530</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 19: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 20: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 21: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 22: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 23: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 24: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 25: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 26:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1531</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 27: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 28: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 29: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 30: </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 31:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1532</span><span class="doxyLineContent"><span class="doxyHighlight">        growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">addStr</a>(</span><span class="doxyHighlightStringLiteral">"&amp;#x24"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">        growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(<a href="#a1748a7403991604b7f600589b77f9937">hex</a>[</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint8_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(c)&gt;&gt;4]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">        growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(<a href="#a1748a7403991604b7f600589b77f9937">hex</a>[</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint8_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(c)&amp;0xF]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">        growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(</span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">        growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">  growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">get</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1544</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">GrowBuf::addChar</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">GrowBuf::addStr</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">GrowBuf::get</a>, <a href="#a1748a7403991604b7f600589b77f9937">hex</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#af0c3a82ead9d9f041131d3bf6ebf9f35">HtmlEntityMapper::name2sym</a> and <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">HtmlEntityMapper::Sym&#95;Unknown</a>.

Referenced by <a href="#ac174bf305a6b97803492e067a2f8dd77">addIndexTerm</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aea69ff69be259d30ee167aa920746fab">DocbookGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a1163472a0d3b1cc3359afdd861966aee">DocbookDocVisitor::filter</a>, <a href="#a311635f4bd437fd28ab5fe0f0309f15d">objectLinkToString</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a3db2ddaf8249d9e473d5fd51f106efd8">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a9ecd666271d67f9e23a18d15f1f259e7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab21bc8c6017db61778cf6e60cea89abe">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a942b617cd956361afbd314539cab5922">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afb8929ed5f608c71ef0d67c9bd2713a8">DocbookGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a19720fb8fa237272681c6328aed372c1">DocbookGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a8ae15cadac821acb3d6ecfb6c541d6b9">DocbookGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a49908c3a630786d98fb499887b18d8f3">DocbookGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a0afd80ec501374a1cdbdf674ec967b79">DocbookGenerator::startTocEntry</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0c4f7806424406a4dddeaf5c916abb5e">DocbookDocVisitor::visitPreStart</a>, <a href="#a598af556233ed34c685184d9e0741c3e">writeDocbookString</a> and <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af456dab6739ba95632af57ca113f2214">DocbookGenerator::writeInheritedSectionTitle</a>.
</div>
</div>

### objectLinkToString() {#a311635f4bd437fd28ab5fe0f0309f15d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString objectLinkToString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; f, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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


<p>Definition at line <a href="#l00771">771</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a311635f4bd437fd28ab5fe0f0309f15d">771</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a311635f4bd437fd28ab5fe0f0309f15d">objectLinkToString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;f,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">                                   </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aa904aecb68e232b5aea1600dbfde5c0d">DB_GEN_C</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) result += </span><span class="doxyHighlightStringLiteral">"&lt;link linkend=\"_"</span><span class="doxyHighlight"> + <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(f) + </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> + anchor + </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight">   result += </span><span class="doxyHighlightStringLiteral">"&lt;link linkend=\"_"</span><span class="doxyHighlight"> + anchor + </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">    result += </span><span class="doxyHighlightStringLiteral">"&lt;link linkend=\"_"</span><span class="doxyHighlight"> + <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(f) + </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">  result += <a href="#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">  result += </span><span class="doxyHighlightStringLiteral">"&lt;/link&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="#aa904aecb68e232b5aea1600dbfde5c0d">DB&#95;GEN&#95;C</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af456dab6739ba95632af57ca113f2214">DocbookGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a29a3e4d6eb0dc0f67374c0fc6fbbe1b2">LatexGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/mangenerator/#ad5999bc38affc6b599217cae57b813d6">ManGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a54e526de8b03280571dc1c0003a14746">RTFGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7c3028f84a8675c8b21ccae5a23e4286">DocbookGenerator::writeObjectLink</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab9d6d6bc2c0ce441e4d6dce979e14a0c">LatexGenerator::writeObjectLink</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a87ad1def7058d6ceb4c588b8e2aecfa5">RTFGenerator::writeObjectLink</a>.
</div>
</div>

### writeDocbookCodeString() {#a4ecdf365ec90cd93f558ce01423a6568}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDocbookCodeString (bool hide, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, size_t &amp; col, size_t stripIndentAmount)</td>
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


<p>Definition at line <a href="#l00083">83</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4ecdf365ec90cd93f558ce01423a6568">83</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4ecdf365ec90cd93f558ce01423a6568">writeDocbookCodeString</a>(</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hide,<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> &amp;col, </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> stripIndentAmount)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (str.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tabSize = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(TAB_SIZE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *s = str.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (hide)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">    col = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a14cfb67a8134e5c51d17d4ebc962c322">updateColumnCount</a>(s,col);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*s++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> spacesToNextTabStop = tabSize - (col%tabSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (spacesToNextTabStop--)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">              </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (col&gt;=stripIndentAmount) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#32;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">              col++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (col&gt;=stripIndentAmount) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#32;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">          col++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;lt;"</span><span class="doxyHighlight">; col++;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;gt;"</span><span class="doxyHighlight">; col++;   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;amp;"</span><span class="doxyHighlight">; col++;  </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;apos;"</span><span class="doxyHighlight">; col++; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;quot;"</span><span class="doxyHighlight">; col++; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">                     uint8_t uc = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint8_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a1748a7403991604b7f600589b77f9937">hex</a>=</span><span class="doxyHighlightStringLiteral">"0123456789ABCDEF"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (uc&lt;32)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">                       t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&amp;#x24"</span><span class="doxyHighlight"> &lt;&lt; <a href="#a1748a7403991604b7f600589b77f9937">hex</a>[uc&gt;&gt;4] &lt;&lt; <a href="#a1748a7403991604b7f600589b77f9937">hex</a>[uc&amp;0xF] &lt;&lt; </span><span class="doxyHighlightStringLiteral">";"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">                       t &lt;&lt; c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">                     col++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config&#95;getInt</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="#a1748a7403991604b7f600589b77f9937">hex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a14cfb67a8134e5c51d17d4ebc962c322">updateColumnCount</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ada15c258bd04d178eb923ca8de03ad5f">DocbookCodeGenerator::codify</a>.
</div>
</div>

### writeDocbookLink() {#a748b4a218a6a5cd91bd9fdcf939b9c3c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDocbookLink (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; compoundId, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchorId, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00151">151</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a748b4a218a6a5cd91bd9fdcf939b9c3c">151</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a748b4a218a6a5cd91bd9fdcf939b9c3c">writeDocbookLink</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; </span><span class="doxyHighlightComment">/*extRef*/</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;compoundId,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchorId,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; </span><span class="doxyHighlightComment">/*tooltip*/</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;link linkend=\"_"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a>(compoundId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchorId.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"_1"</span><span class="doxyHighlight"> &lt;&lt; anchorId;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a598af556233ed34c685184d9e0741c3e">writeDocbookString</a>(t,text);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/link&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a3d37ec79f266698bd836af54ba75e63e">stripPath</a> and <a href="#a598af556233ed34c685184d9e0741c3e">writeDocbookString</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ac0d4a8f26f5daff4ffb1702f24b35697">DocbookCodeGenerator::writeCodeLink</a>.
</div>
</div>

### writeDocbookString() {#a598af556233ed34c685184d9e0741c3e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDocbookString (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
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


<p>Definition at line <a href="#l00078">78</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a598af556233ed34c685184d9e0741c3e">78</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a598af556233ed34c685184d9e0741c3e">writeDocbookString</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; <a href="#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(s);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ada73fe6def10a3e449256fc96929e8b2">DocbookCodeGenerator::writeCodeLinkLine</a> and <a href="#a748b4a218a6a5cd91bd9fdcf939b9c3c">writeDocbookLink</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### hex {#a1748a7403991604b7f600589b77f9937}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">auto hex ="0123456789ABCDEF"</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel constexpr">constexpr</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l01479">1479</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1748a7403991604b7f600589b77f9937">1479</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="#a1748a7403991604b7f600589b77f9937">hex</a>=</span><span class="doxyHighlightStringLiteral">"0123456789ABCDEF"</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/htmlcodegenerator/#a0941dd0ea229339847ef6604ea6b8003">HtmlCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/files/src/htmldocvisitor-cpp/#a6078df856ea98140e2210721d1175764">convertIndexWordToAnchor</a>, <a href="#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2a3368111f86b401c8f223cd7374b5ac">convertToHtml</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af333eebf6d2862cf38a30e084bc36e0d">convertToId</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a588c599deed30414ade1ed583a11827d">escapeCharsInString</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#acd4ff9a433984cc6fb8e9b6f47284420">HtmlDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a2f5320a8c0aa3d9f5af4129d7edda49c">HtmlDocVisitor::filterQuotedCdataAttr</a>, <a href="/web-doxygen/docs/api/files/src/dotdirdeps-cpp/#a683792f7f7df231861acd54ff905211d">getDirectoryBackgroundColor</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5b4eb46ed4177d10b053426f65925171">latexFilterURL</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac0fd4772eabf2904003c3e2608882c80">letterToLabel</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af10f5e35396e550af824e3029bab8dd4">replaceColorMarkers</a>, <a href="/web-doxygen/docs/api/structs/searchterm/#aec66f0d2f6bb7fb2905bc14546af792b">SearchTerm::termEncoded</a> and <a href="#a4ecdf365ec90cd93f558ce01423a6568">writeDocbookCodeString</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DB&#95;GEN&#95;C {#aa904aecb68e232b5aea1600dbfde5c0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_GEN_C</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00070">70</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa904aecb68e232b5aea1600dbfde5c0d">70</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_GEN_C</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aaa8fd7d7ca213ca44cfc5f90aae724e2">DocbookGenerator::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac08ff202d3bea4e6e16eceb73d3f2043">DocbookGenerator::addLabel</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a59655593be449f9e01ce953a72233de0">DocbookGenerator::DocbookGenerator</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aea69ff69be259d30ee167aa920746fab">DocbookGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac40c97419675e944657df84aa2b944e3">DocbookGenerator::endBold</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aab1ce69f9718b3c1e05f6c1b697664e4">DocbookGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2906dcb02cfd455c0d910c9f9501bfbe">DocbookGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a56a8e5ad875fcb9b51ce32c5a6fb3fa0">DocbookGenerator::endCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a4cfc71e51ed754737f74095508e19a63">DocbookGenerator::endConstraintDocs</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afef965c128d8f6cca32eea3c92c7d1e9">DocbookGenerator::endConstraintList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af1face8672a1118ae0a38fd123f4fe1a">DocbookGenerator::endConstraintParam</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2ff006f1e7375b5d3c6e5a17a3990d68">DocbookGenerator::endConstraintType</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aef5e37d1d6cda8c759cebcd418d91c5d">DocbookGenerator::endDescTable</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a981135dd520efbaa65fabfa865f0ac97">DocbookGenerator::endDescTableData</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aeccc502a7bdfb0f61b3bc32e642123ac">DocbookGenerator::endDescTableInit</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a11a9495ef08b1736d472a7245af207b2">DocbookGenerator::endDescTableRow</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a4dfd54947422d7782b2634b041086ed8">DocbookGenerator::endDescTableTitle</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa80d2614901e7d7624514fa077cee77c">DocbookGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a4b2e6be7cbbe074a8d2be270a537c454">DocbookGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aabec02eb28588a45888b0c4d977d0a3b">DocbookGenerator::endDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afd9d65e673f95f980a82bd0bd5518903">DocbookGenerator::endExamples</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aefb08482f742251ae543aeb57983b335">DocbookGenerator::endFile</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a640f85f2e2b3f829d6561aaed542d20b">DocbookGenerator::endGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ad91c453f57c7ab68aafb726bceed5807">DocbookGenerator::endGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afa0db463a17513f4e3ae08e03d6e2615">DocbookGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a67b1d012d99a13ef16fcc4ea599b2a06">DocbookGenerator::endInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a01c30e96c02d55000d0c0282cba79924">DocbookGenerator::endInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af26580af0994f29308d81034cce3823d">DocbookGenerator::endInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2b4c585da080af5a62ca30a99c27ba01">DocbookGenerator::endLabels</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab5c9f6c8cbc6591f1a9763d5c233a8f9">DocbookGenerator::endMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#accf1f2e363b93a552fb4d3aeb09e6ff2">DocbookGenerator::endMemberDocList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a47879780f767bfd2f4ffcfaa105d8866">DocbookGenerator::endMemberDocName</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7d042582c83c4bf25dba8857f186e56d">DocbookGenerator::endMemberDocPrefixItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a45cd1dbe07a7c47ec3209b9fe1b92c0d">DocbookGenerator::endMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a22265d3dc6b9ae14e0f5db49a0b4f22a">DocbookGenerator::endMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2f941a481c8539d5ea65daf45d7d694b">DocbookGenerator::endMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a6d97af565fba4f9b4b8df0ee218a7b19">DocbookGenerator::endMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a29bb57d53d4ef49984943752371d80a9">DocbookGenerator::endMemberItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ae3b1fb5838ed0231423eb95a41173078">DocbookGenerator::endMemberList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa45cce2f709a04a6a5c741b5d2c43f2d">DocbookGenerator::endMemberTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9d5757a3649f96aaaeef61ade2f1b067">DocbookGenerator::endParagraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a852205da1a99f864d0a1c96143c3b671">DocbookGenerator::endParameterDefVal</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ae91b64667df54c993df7fef86f2a57c9">DocbookGenerator::endParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ae73f06b90526d3d375eafac0ae711af5">DocbookGenerator::endParameterList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa2de284dbf9b27c95a81298ebff29a7d">DocbookGenerator::endParameterName</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac3c2a2d5f7ee268ca127a30fcaa78fe0">DocbookGenerator::endSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a6684626f228c4b3386f33b9d0e1cb000">DocbookGenerator::endTextBlock</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aca2bba69055abb8a7a7ea9ce8ce7f11f">DocbookGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2f14bcd9d6629e6ec18be7c82343d852">DocbookGenerator::endTypewriter</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a10ee707ef187621006c30d021aaca34d">DocbookGenerator::exceptionEntry</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a1239152bed92bc91f6a1ddba37671a29">DocbookGenerator::lineBreak</a>, <a href="#a311635f4bd437fd28ab5fe0f0309f15d">objectLinkToString</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac90cbd84bc41a572f9f99ca23587847f">DocbookGenerator::startBold</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a0f1823b3bff5917f7cc686c747b2e500">DocbookGenerator::startCallGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9f0bbee1b9f39353827fe1cb34aa6c71">DocbookGenerator::startClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9b3a91c273834c43c7b48e2f0e8712d6">DocbookGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#adcaba85a73024c0104286c6480b1aaeb">DocbookGenerator::startConstraintDocs</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a57ecb947b9d729a32204364b0be5f712">DocbookGenerator::startConstraintList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a51f8405b195722cee84834e0b17f4c6e">DocbookGenerator::startConstraintParam</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a418a7b6baf025267bf10fe0b4a38c367">DocbookGenerator::startConstraintType</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afb8929ed5f608c71ef0d67c9bd2713a8">DocbookGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a155219c2c52cacd61c75a34b59e16b4e">DocbookGenerator::startDescTableData</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa64e6f62df30c7d3da3c18c9e311ef96">DocbookGenerator::startDescTableInit</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab8b9cff7a3e28360c3b659533fccbfda">DocbookGenerator::startDescTableRow</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ad6d257b8715c635fbeb2fce4183749c4">DocbookGenerator::startDescTableTitle</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a987d5becf1294c93b3d7346b07dd51f5">DocbookGenerator::startDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#abc8a470c44572d5b386f47bb53a9d519">DocbookGenerator::startDotGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab575d0e0e347d711d242bdc7fd8c7648">DocbookGenerator::startDoxyAnchor</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aaac726241831c07dc4733f0e63dab3e1">DocbookGenerator::startExamples</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7a82873f4a7eeacb88ef535768b311f4">DocbookGenerator::startFile</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a1c5271d755874098863c487bfdf49ad8">DocbookGenerator::startGroupCollaboration</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#abbd96aa5d90d0337ba3cfcf717052902">DocbookGenerator::startInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#adaf7ed17f053cb14c26da75c9d7552d4">DocbookGenerator::startInlineMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af610006b0e0386c4f5762724f30c429c">DocbookGenerator::startInlineMemberName</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac81970c0218bab9e70c805e3fe2d1826">DocbookGenerator::startInlineMemberType</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7ce24c2a590df467e4768a74958e7e22">DocbookGenerator::startLabels</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a70de26cfb00cc50138102556da46e2ce">DocbookGenerator::startMemberDocList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a97e2055991080f05a37be7769cf3509c">DocbookGenerator::startMemberDocName</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa59a7da2611e101aa060c3455084255e">DocbookGenerator::startMemberDocPrefixItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a49908c3a630786d98fb499887b18d8f3">DocbookGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9be5e6aee43e8eaadf84e8adbd58a590">DocbookGenerator::startMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afdcc8344112747cd65cd80bdb2249933">DocbookGenerator::startMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a10f198594f85e92a681337af184d913d">DocbookGenerator::startMemberHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a82557dc83927e00f34efb901409e04d4">DocbookGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa7454a8fe2d2ceafbc630ea57ce68d0b">DocbookGenerator::startMemberList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a5fc122c54d1a0667d645062bed344a6a">DocbookGenerator::startMemberTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a22b30d736cc0185909d9b3954a8e3f4e">DocbookGenerator::startParagraph</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aedc98fb288995aea0c0b83fc4eca50a2">DocbookGenerator::startParameterDefVal</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a298ee3beaa40d4f406dba0ea7908a473">DocbookGenerator::startParameterExtra</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a05a82a3d67c8acbd8ef73ca8d6d77f1c">DocbookGenerator::startParameterList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a83ad153480a66966d9e1121e004b46e4">DocbookGenerator::startParameterName</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa0fe01b830ddb0d899e151aa389087c8">DocbookGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aeca4bf8edce633fa3faa7c1e38882363">DocbookGenerator::startTextBlock</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a921181dfbb9226c3eef4536d2f06a242">DocbookGenerator::startTitleHead</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a5e66bd3d7d003c6a3205b1febaa19958">DocbookGenerator::startTypewriter</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afba9fe943d8c123f6e40256bdca2f5d3">DocbookGenerator::writeChar</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2f2d4d689d7e1c05bd243f0b23242064">DocbookGenerator::writeDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af456dab6739ba95632af57ca113f2214">DocbookGenerator::writeInheritedSectionTitle</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a3a9126201aae3ba3d2e48a2e7c9b5082">DocbookGenerator::writeLabel</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a1a4768269d4a67e9762f388db3ff6842">DocbookGenerator::writeNonBreakableSpace</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7c3028f84a8675c8b21ccae5a23e4286">DocbookGenerator::writeObjectLink</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a53279dc86a635990c995e61bc3b7104c">DocbookGenerator::writePageLink</a> and <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aac462a27783fedbf5241e95db0a5c66a">DocbookGenerator::writeString</a>.
</div>
</div>

### DB&#95;GEN&#95;C1 {#aad86f7a60609e9852bce76f5a1626d5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_GEN_C1(x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00071">71</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aad86f7a60609e9852bce76f5a1626d5a">71</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_GEN_C1(x)</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#a1dfd30b3411a87069f1f0e8e8cb31708">DocbookCodeGenerator::endCodeFragment</a> and <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#afac180046d6b800198aa9b41e964e78d">DocbookCodeGenerator::startCodeFragment</a>.
</div>
</div>

### DB&#95;GEN&#95;C2 {#ad9e8d60bb28488aa27ff42b3c5907437}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_GEN_C2(y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00072">72</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad9e8d60bb28488aa27ff42b3c5907437">72</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_GEN_C2(y)</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9a5dbcad360a1ad2a8f9403ae344d638">DocbookGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac651122c0ac17ea4be13f8a4d71c3efa">DocbookGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a19720fb8fa237272681c6328aed372c1">DocbookGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a8ae15cadac821acb3d6ecfb6c541d6b9">DocbookGenerator::startMemberDoc</a> and <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a0332a478a833682cf5d2c547a8397973">DocbookGenerator::writeRuler</a>.
</div>
</div>

### DB&#95;GEN&#95;C2a {#a6f0e27e5a10a97d88bb77b84d6d42481}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_GEN_C2a(x, y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00073">73</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6f0e27e5a10a97d88bb77b84d6d42481">73</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_GEN_C2a(x,y)</span></span></div>

</div>

</div>
</div>

### Docbook&#95;DB {#a72e66067731a340037c60b0774b24ef4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define Docbook_DB(x)&nbsp;&nbsp;&nbsp;do {} while(0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="#l00058">58</a> of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72e66067731a340037c60b0774b24ef4">58</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define Docbook_DB(x) do {} while(0)</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ada15c258bd04d178eb923ca8de03ad5f">DocbookCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#acca93adef4af10baa753afe68846138a">DocbookCodeGenerator::endCodeLine</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#a1d035c6d2cb17becc47cf8a25764e1a8">DocbookCodeGenerator::endFontClass</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#adaaaa54a0aec67674d41d61bef0f2a2b">DocbookCodeGenerator::startCodeLine</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#adcd8cfddee95768c329a3c284c4ede9f">DocbookCodeGenerator::startFontClass</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#a889f1558d0b0638e9fc8d1bf051ec1d0">DocbookCodeGenerator::writeCodeAnchor</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ac0d4a8f26f5daff4ffb1702f24b35697">DocbookCodeGenerator::writeCodeLink</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ada73fe6def10a3e449256fc96929e8b2">DocbookCodeGenerator::writeCodeLinkLine</a>, <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#ae3e188b81cd05fbb4e12621850e7d5e4">DocbookCodeGenerator::writeLineNumber</a> and <a href="/web-doxygen/docs/api/classes/docbookcodegenerator/#adfbcce024dec33fe27f6d4eaa4c1e3c1">DocbookCodeGenerator::writeTooltip</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
