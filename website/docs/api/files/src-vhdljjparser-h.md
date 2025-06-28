---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/vhdljjparser-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `vhdljjparser.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;vector&gt;
#include &lt;memory&gt;
#include &lt;string&gt;
#include "<a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>"
#include &lt;stdio.h&gt;
#include &lt;stdlib.h&gt;
#include &lt;assert.h&gt;
#include &lt;ctype.h&gt;
#include "<a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdloutlineparser">VHDLOutlineParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>VHDL parser using state-based lexical scanning. <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">VhdlSection { <a href="#a02fbf486f00c210089e02f7153a7e55b">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/files/src/entry-h/#abd47085ad2ebd874e6b5d92f426e31b1">EntryList</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a182203e7e4b8c08526f2bda22d394855">getVhdlInstList</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5f369f2c5e750a453046fddfbbf06ad0">filter2008VhdlComment</a> (const QCString &amp;s)</td>
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

## Enumerations

### VhdlSection {#a02fbf486f00c210089e02f7153a7e55b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class VhdlSection </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">UNKNOWN<a id="a02fbf486f00c210089e02f7153a7e55ba696b031073e74bf2cb98e5ef201d4aa3"></a></td>
<td class="doxyEnumItemDescription"><p> (= 0)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">GEN_SEC<a id="a02fbf486f00c210089e02f7153a7e55bace9b6b1321f6162e00ed2ae15192733f"></a></td>
<td class="doxyEnumItemDescription"><p> (=0x1)</p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PARAM_SEC<a id="a02fbf486f00c210089e02f7153a7e55ba03e3141cc2c3c15cbb2e2e901cb51f51"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">CONTEXT_SEC<a id="a02fbf486f00c210089e02f7153a7e55baacf46948c6ab40ac68701e7bb2502b39"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">PROTECTED_SEC<a id="a02fbf486f00c210089e02f7153a7e55ba511fdf5647052639b72dce7f1d292e8c"></a></td>
<td class="doxyEnumItemDescription"><p></p></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line <a href="#l00020">20</a> of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a02fbf486f00c210089e02f7153a7e55baacf46948c6ab40ac68701e7bb2502b39">20</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">enum  class</span><span class="doxyHighlight"> <a href="#a02fbf486f00c210089e02f7153a7e55b">VhdlSection</a> { <a href="/web-doxygen/docs/api/files/src/cmdmapper-h/#a21e038f5b8958e203d28bc4f18472352a696b031073e74bf2cb98e5ef201d4aa3">UNKNOWN</a> = 0, <a href="#a02fbf486f00c210089e02f7153a7e55bace9b6b1321f6162e00ed2ae15192733f">GEN_SEC</a>=0x1, <a href="#a02fbf486f00c210089e02f7153a7e55ba03e3141cc2c3c15cbb2e2e901cb51f51">PARAM_SEC</a>,<a href="#a02fbf486f00c210089e02f7153a7e55baacf46948c6ab40ac68701e7bb2502b39">CONTEXT_SEC</a>,<a href="#a02fbf486f00c210089e02f7153a7e55ba511fdf5647052639b72dce7f1d292e8c">PROTECTED_SEC</a> } ;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### filter2008VhdlComment() {#a5f369f2c5e750a453046fddfbbf06ad0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString filter2008VhdlComment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00078">78</a> of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#l00868">868</a> of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a5f369f2c5e750a453046fddfbbf06ad0">868</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a5f369f2c5e750a453046fddfbbf06ad0">filter2008VhdlComment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()&lt;4) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/growbuf">GrowBuf</a> growBuf;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+3; </span><span class="doxyHighlightComment">// skip /*!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p == </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || *p == </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">    growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c == </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// special handling of space followed by * at beginning of line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p == </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || *p == </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p == </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// special attention in case character at end is /</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*p == </span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">) p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// special attention in case */ at end of last line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> len = growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a1a0ecc7a79837ed02005befe12d49994">getPos</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len&gt;=2 &amp;&amp; growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a7208e5ca317711c8190cbdcfae8ab702">at</a>(len-1) == </span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> &amp;&amp; growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a7208e5ca317711c8190cbdcfae8ab702">at</a>(len-2) == </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">    len -= 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (len&gt;0 &amp;&amp; growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a7208e5ca317711c8190cbdcfae8ab702">at</a>(len-1) == </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) len--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (len&gt;0 &amp;&amp; ((c = growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a7208e5ca317711c8190cbdcfae8ab702">at</a>(len-1)) == </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || c == </span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">)) len--;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span><span class="doxyLineContent"><span class="doxyHighlight">    growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a98f7e0590791e42fcbd31bdfd8c75d2a">setPos</a>(len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">  growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">addChar</a>(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> growBuf.<a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">get</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/growbuf/#a46b4677f555d2abc718f26e71a59efda">GrowBuf::addChar</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a7208e5ca317711c8190cbdcfae8ab702">GrowBuf::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a88d6408723b8c1a58187f24da81dfd5e">GrowBuf::get</a>, <a href="/web-doxygen/docs/api/classes/growbuf/#a1a0ecc7a79837ed02005befe12d49994">GrowBuf::getPos</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="/web-doxygen/docs/api/classes/growbuf/#a98f7e0590791e42fcbd31bdfd8c75d2a">GrowBuf::setPos</a>.
</div>
</div>

### getVhdlInstList() {#a182203e7e4b8c08526f2bda22d394855}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const EntryList &amp; getVhdlInstList ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00076">76</a> of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-h">vhdljjparser.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#l00845">845</a> of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a182203e7e4b8c08526f2bda22d394855">845</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/entry-h/#abd47085ad2ebd874e6b5d92f426e31b1">EntryList</a> &amp;<a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a182203e7e4b8c08526f2bda22d394855">getVhdlInstList</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a61ffdba0efc8d9b6390969cb7fa5d37b">g_instFiles</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp/#a61ffdba0efc8d9b6390969cb7fa5d37b">g&#95;instFiles</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#ab8681769cd2f027fbf46a4836d3825e9">VhdlDocGen::computeVhdlComponentRelations</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
