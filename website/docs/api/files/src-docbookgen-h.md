---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/docbookgen-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `docbookgen.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;memory&gt;
#include &lt;array&gt;
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docbookcodegenerator">DocbookCodeGenerator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/docbookgenerator">DocbookGenerator</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/docbookgenerator/tocstate">TocState</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af32154cfef85d65fcb0f241aab484a38">convertToDocBook</a> (const QCString &amp;s, const bool retainNewline=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aabdfe0663066be45a134b9b84d4e9c94">DB_GEN_EMPTY</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5e32f161e5fae39ad07802b65c249c11">DB_GEN_H</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0c3b66d754ec25f578e683aae263b6a5">DB_GEN_H1</a>(x)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a02de2f5a4d4f71dd2a81f4b2326735e8">DB_GEN_H2</a>(y)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8977092614430609f5db50a7a865be2c">DB_GEN_H2a</a>(x, y)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a78e3360983610c19426244e6363928f1">DB_GEN_NEW</a></td>
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

### convertToDocBook() {#af32154cfef85d65fcb0f241aab484a38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString convertToDocBook (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, const bool retainNewline=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Converts a string to an DocBook-encoded string</p>

<p>Declaration at line 352 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>, definition at line 1482 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp">docbookgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">1482</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a7c12b32b5b825c9fc989731c66ba1933">convertToDocBook</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> retainNewline)</span></span></div>
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
<div class="doxyCodeLine"><span class="doxyLineNumber">1533</span><span class="doxyLineContent"><span class="doxyHighlight">        growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(<a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint8_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(c)&gt;&gt;4]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1534</span><span class="doxyLineContent"><span class="doxyHighlight">        growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(<a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">uint8_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(c)&amp;0xF]);</span></span></div>
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


References <a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">GrowBuf::addChar</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a5e0ff6d9f7a7139725d77a9d669340f3">GrowBuf::addStr</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">GrowBuf::get</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#af0c3a82ead9d9f041131d3bf6ebf9f35">HtmlEntityMapper::name2sym</a> and <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">HtmlEntityMapper::Sym&#95;Unknown</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#ac174bf305a6b97803492e067a2f8dd77">addIndexTerm</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aea69ff69be259d30ee167aa920746fab">DocbookGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a1163472a0d3b1cc3359afdd861966aee">DocbookDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a311635f4bd437fd28ab5fe0f0309f15d">objectLinkToString</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a3db2ddaf8249d9e473d5fd51f106efd8">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a9ecd666271d67f9e23a18d15f1f259e7">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#ab21bc8c6017db61778cf6e60cea89abe">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a942b617cd956361afbd314539cab5922">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afb8929ed5f608c71ef0d67c9bd2713a8">DocbookGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a19720fb8fa237272681c6328aed372c1">DocbookGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a8ae15cadac821acb3d6ecfb6c541d6b9">DocbookGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a49908c3a630786d98fb499887b18d8f3">DocbookGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a0afd80ec501374a1cdbdf674ec967b79">DocbookGenerator::startTocEntry</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0c4f7806424406a4dddeaf5c916abb5e">DocbookDocVisitor::visitPreStart</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a598af556233ed34c685184d9e0741c3e">writeDocbookString</a> and <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af456dab6739ba95632af57ca113f2214">DocbookGenerator::writeInheritedSectionTitle</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### DB&#95;GEN&#95;EMPTY {#aabdfe0663066be45a134b9b84d4e9c94}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_GEN_EMPTY</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 26 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aabdfe0663066be45a134b9b84d4e9c94">26</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_GEN_EMPTY</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aca505307dec429b7a18add100af59912">DocbookGenerator::endAnonTypeScope</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a33a21c7a3169dfc7f8c4c1149dc6f6ed">DocbookGenerator::endContents</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7c3bde6063e62666c8937ab1c6ff06b1">DocbookGenerator::endDescForItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a6a4000026c8f34db3cb7fa38b88068f2">DocbookGenerator::endHeaderSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a247327c61f5c0cdc9e7f2323d7f978ca">DocbookGenerator::endIndent</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af738e039ccb42d9da57626ff43ede2b5">DocbookGenerator::endItemList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a950f3ae4aac5c5cd548e64bd81b2e980">DocbookGenerator::endItemListItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa3041625348d5b377dabccf8d7b81782">DocbookGenerator::endMemberDeclaration</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ad6bcc9d1588d49850a41ae5e2a1899cd">DocbookGenerator::endMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab056fe61e03329c403886763b05029f9">DocbookGenerator::endMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a576ba898a2b833304ffaee52a9aee2be">DocbookGenerator::endMemberSections</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a8c63d39214124f23059f9a6f2fb4dd1d">DocbookGenerator::endMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9388e552fa8c8e18d8b03e43de804022">DocbookGenerator::endPageDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a0ae9695b1371e245c5e4b458acae99ed">DocbookGenerator::endParameterType</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ae2a279cfe88218bf0526fb0a5c2ca51f">DocbookGenerator::endQuickIndices</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afc2f215c948518de991a642f6a021635">DocbookGenerator::insertMemberAlign</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a5e10e2665a803a6c5c931050172ea4b1">DocbookGenerator::insertMemberAlignLeft</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a3d3a346fb2272e6241e3b5cd75cf0b0e">DocbookGenerator::lastIndexPage</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a72485dc1f19c70c869b6807d1ce1b8e5">DocbookGenerator::startAnonTypeScope</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ad92f550c473ab4d6fc714ed633fd2bbc">DocbookGenerator::startContents</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a50c0a3308c5ae4a4740799c07c8b160f">DocbookGenerator::startDescForItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a8859f548070610da1b29fc339d390fd2">DocbookGenerator::startHeaderSection</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a5f52440d2fe3025eaf9f7853974c44cd">DocbookGenerator::startIndent</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ae0410be0719eae1da884ade02d1612af">DocbookGenerator::startItemList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a24d221cf16ecc55edd136306797d289a">DocbookGenerator::startItemListItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#afecf0cbb2b97e57f44fa5df8acd422b1">DocbookGenerator::startMemberDeclaration</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a4bbf1226470e991f2d1aac02fe3b443b">DocbookGenerator::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a310be7aaf9518ecf21dec09a0ed3bfd8">DocbookGenerator::startMemberGroupDocs</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab76e2ad69e7649f9127d74c06bc93278">DocbookGenerator::startMemberSections</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a53f3f2e01a47d65a20615e1fb8e5d245">DocbookGenerator::startMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#abf38a4b2f36d31a465f67498ce919c83">DocbookGenerator::startPageDoc</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7e94634814ad6933ca72763614845a09">DocbookGenerator::startParameterType</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aa50fb495205963cd96fc92210a406db8">DocbookGenerator::startQuickIndices</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a7134e69943d0a4a7ed1939735417851a">DocbookGenerator::writeAnchor</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a02aacfb4e28b9a83f0cc1ae519525192">DocbookGenerator::writeLatexSpacing</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aebdedaea9ee0b74162e2f30b5b9d8650">DocbookGenerator::writePageOutline</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a17247283fb1821451810341e9d0cc3d5">DocbookGenerator::writeQuickLinks</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aaf1cd7095f2e35a8a08a35b5708d0290">DocbookGenerator::writeSearchInfo</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a1d027d0e3f93bdc7fb18e0744dddc54c">DocbookGenerator::writeSplitBar</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a684db300b5edf11b5bfa42ba0dac2da0">DocbookGenerator::writeStyleInfo</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a3656cbeda9530a97ef7aca5a93e476dd">DocbookGenerator::writeSummaryLink</a> and <a href="/web-doxygen/docs/api/classes/docbookgenerator/#abbc5974b7b5e7711e3319c50f23b32c5">DocbookGenerator::writeSynopsis</a>.
</div>
</div>

### DB&#95;GEN&#95;H {#a5e32f161e5fae39ad07802b65c249c11}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_GEN_H</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 38 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5e32f161e5fae39ad07802b65c249c11">38</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_GEN_H</span></span></div>

</div>

</div>
</div>

### DB&#95;GEN&#95;H1 {#a0c3b66d754ec25f578e683aae263b6a5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_GEN_H1(x)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 39 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0c3b66d754ec25f578e683aae263b6a5">39</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_GEN_H1(x)</span></span></div>

</div>

</div>
</div>

### DB&#95;GEN&#95;H2 {#a02de2f5a4d4f71dd2a81f4b2326735e8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_GEN_H2(y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 40 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02de2f5a4d4f71dd2a81f4b2326735e8">40</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_GEN_H2(y)</span></span></div>

</div>

</div>
</div>

### DB&#95;GEN&#95;H2a {#a8977092614430609f5db50a7a865be2c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_GEN_H2a(x, y)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8977092614430609f5db50a7a865be2c">41</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_GEN_H2a(x,y)</span></span></div>

</div>

</div>
</div>

### DB&#95;GEN&#95;NEW {#a78e3360983610c19426244e6363928f1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define DB_GEN_NEW</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/src/docbookgen-h">docbookgen.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a78e3360983610c19426244e6363928f1">42</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define DB_GEN_NEW</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a150df485d395188cbbee63799370c003">DocbookGenerator::endCenter</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a9e11d900e3d524f1536fd952f8f1f0eb">DocbookGenerator::endEmphasis</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a04113da78567eeb8144cdc82714c95bf">DocbookGenerator::endIndexItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab3825760a95d9e6034ce0434d09ed398">DocbookGenerator::endIndexKey</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a297162e483491a92715883063295624a">DocbookGenerator::endIndexList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a6a51602b9f23553d2f742fe7a3f3326e">DocbookGenerator::endIndexListItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a03eb777494759912f235f33cbcfadadf">DocbookGenerator::endIndexValue</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a221ea4ee3970e79c64e1636f4ae11782">DocbookGenerator::endInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a0e98c2ae5445679208c1207c7e8fd650">DocbookGenerator::endPageRef</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2cf173307e9344cbbe45d4ccdae94807">DocbookGenerator::endProjectNumber</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a1f0fa2e1d6f9a5c11796e884ae962afc">DocbookGenerator::endSmall</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a8f7bdbae7f979fc69d532fd791b4fa44">DocbookGenerator::endTextLink</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#aaea0ab82cc8fde7fb6b7b870fe1f5c61">DocbookGenerator::startCenter</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a4d1419af8e3808bc8876a8f7ac9d0b2c">DocbookGenerator::startEmphasis</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a165b08f7f0cefa958779ddd2faf7e965">DocbookGenerator::startIndexItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2c7a1105dc4b6faa8e81088a35f0a47d">DocbookGenerator::startIndexKey</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a0f3154fbaf3e01e59f00c50f3f34c6d3">DocbookGenerator::startIndexList</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af8a68054558e4135bf42a6d444fdb71c">DocbookGenerator::startIndexListItem</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a28cb580557bb6f9808d05cc5bcc3b4bf">DocbookGenerator::startIndexValue</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a2fdb74bc21106b41053aea156ef99b2c">DocbookGenerator::startInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ac6ffcbf4bd345ac9afabf49898b5890e">DocbookGenerator::startPageRef</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a97781f8b5e046d402d50a6a49744acb0">DocbookGenerator::startProjectNumber</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ae501cb3410c7ed6e7daefc2c6bff8bab">DocbookGenerator::startSmall</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a0cf8bbe3120d24b4bc0d254d14268296">DocbookGenerator::startTextLink</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#af59fcb6ef3fc574f346a35719889d4b4">DocbookGenerator::writeFooter</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a0b12a50011caf4cb18e36d78a82c636d">DocbookGenerator::writeGraphicalHierarchy</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a84d793a7a3cfbef2635c31b9b47be6fd">DocbookGenerator::writeLogo</a>, <a href="/web-doxygen/docs/api/classes/docbookgenerator/#ab37bcd37222fea70d11024ed92294636">DocbookGenerator::writeNavigationPath</a> and <a href="/web-doxygen/docs/api/classes/docbookgenerator/#a4cf676ad6c4def51f89550c68fe4a064">DocbookGenerator::writeStartAnnoItem</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
