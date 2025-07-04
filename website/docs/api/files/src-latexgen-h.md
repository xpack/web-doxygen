---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/latexgen-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `latexgen.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/latexcodegenerator">LatexCodeGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for LaTeX code fragments. <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/latexgenerator">LatexGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for LaTeX output. <a href="/web-doxygen/docs/api/classes/latexgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ace2411e2a91d0794515d7319a05a96e4">writeExtraLatexPackages</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb096be4b2c37adc54becb763cc99470">writeLatexSpecialFormulaChars</a> (TextStream &amp;t)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64192627e664ac6451165d77cbe28ea3">convertToLaTeX</a> (const QCString &amp;s, bool insideTabbing, bool keepSpaces=FALSE)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4ee99b7f4c3b954efce5bf4da1518b31">filterLatexString</a> (TextStream &amp;t, const QCString &amp;str, bool insideTabbing, bool insidePre, bool insideItem, bool insideTable, bool keepSpaces, const bool retainNewline=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd297d2d96747033593750c401bfe95e">latexEscapeLabelName</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad32126ac958c2ac22491a47f6957935c">latexEscapeIndexChars</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a37bf597b522fe84aefa564de5b8489c2">latexEscapePDFString</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b4eb46ed4177d10b053426f65925171">latexFilterURL</a> (const QCString &amp;s)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6243d84ee6552fd5282db11d491c2e18">LATEX_STYLE_EXTENSION</a>&nbsp;&nbsp;&nbsp;".sty"</td>
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

### convertToLaTeX() {#a64192627e664ac6451165d77cbe28ea3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString convertToLaTeX (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, bool insideTabbing, bool keepSpaces=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 340 of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line 2546 of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5261de94ef3b325400ae7b7a0f71630a">2546</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5261de94ef3b325400ae7b7a0f71630a">convertToLaTeX</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideTabbing,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> keepSpaces)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2547</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2548</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2549</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>(t,s,insideTabbing,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,keepSpaces);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2550</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> t.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2551</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a> and <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/latexgenerator/#a33cad27a2b5dce6e2762d5915e554118">LatexGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ada58cb886cb5f74b40a96749a59eb8b3">objectLinkToString</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a0de19d805d84ae14aff81334a010c9a1">LatexGenerator::startIndexSection</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad17beb87ce167c3b4203b5260ff7b2a9">substituteLatexKeywords</a> and <a href="/web-doxygen/docs/api/classes/latexgenerator/#a29a3e4d6eb0dc0f67374c0fc6fbbe1b2">LatexGenerator::writeInheritedSectionTitle</a>.</p>

</div>
</div>

### filterLatexString() {#a4ee99b7f4c3b954efce5bf4da1518b31}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void filterLatexString (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; str, bool insideTabbing, bool insidePre, bool insideItem, bool insideTable, bool keepSpaces, const bool retainNewline=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 342 of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line 2388 of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">2388</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;str,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2389</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideTabbing,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insidePre,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> insideItem,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a2515a32b6dfcda676ef65dd34fad5abf">insideTable</a>,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> keepSpaces, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> retainNewline)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2390</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2391</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (str.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2392</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> pdfHyperlinks = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2393</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("filterLatexString(%s) insideTabbing=%d\n",qPrint(str),insideTabbing);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2394</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = str.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2395</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *q = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2396</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> pc=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2397</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2398</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2399</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2400</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*p++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2401</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2402</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (insidePre)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2403</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2404</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2405</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2406</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 0xef: </span><span class="doxyHighlightComment">// handle U+FFFD i.e. "Replacement character" caused by octal: 357 277 275 / hexadecimal 239 191 189</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2407</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightComment">// the LaTeX command \ucr has been defined in doxygen.sty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2408</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*(p)) == 191 &amp;&amp; </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*(p+1)) == 0xbd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2409</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2410</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\ucr}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2411</span><span class="doxyLineContent"><span class="doxyHighlight">            p += 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2412</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2413</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2414</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; static_cast&lt;char&gt;(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2415</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2416</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\(\\backslash\\)"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2417</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\{"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2418</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2419</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\_"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2420</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\&amp;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2421</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'%'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\%"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2422</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\#"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2423</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\$"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2424</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"{}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2425</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-\\/"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2426</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">:  <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a2515a32b6dfcda676ef65dd34fad5abf">insideTable</a> ? t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\string^"</span><span class="doxyHighlight"> : t &lt;&lt; static_cast&lt;char&gt;(c);    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2427</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\string~"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2428</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retainNewline) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\newline"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> t &lt;&lt; </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2429</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2430</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (keepSpaces) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"~"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> t &lt;&lt; </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2431</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2432</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2433</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c&lt;32) t &lt;&lt; </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// non printable control character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2434</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> t &lt;&lt; static_cast&lt;char&gt;(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2435</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2436</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2437</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2438</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2439</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2440</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight">(c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2441</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2442</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> 0xef: </span><span class="doxyHighlightComment">// handle U+FFFD i.e. "Replacement character" caused by octal: 357 277 275 / hexadecimal 239 191 189</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2443</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightComment">// the LaTeX command \ucr has been defined in doxygen.sty</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2444</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*(p)) == 191 &amp;&amp; </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(*(p+1)) == 0xbd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2445</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2446</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"{\\ucr}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2447</span><span class="doxyLineContent"><span class="doxyHighlight">            p += 2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2448</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2449</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2450</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; static_cast&lt;char&gt;(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2451</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2452</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\#"</span><span class="doxyHighlight">;           </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2453</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\$"</span><span class="doxyHighlight">;           </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2454</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'%'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\%"</span><span class="doxyHighlight">;           </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2455</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">:  <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#aabea2ded9f00d6bbeb03680918e66c02">processEntity</a>(t,pdfHyperlinks,</span><span class="doxyHighlightStringLiteral">"$^\\wedge$"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"\\string^"</span><span class="doxyHighlight">);    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2456</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">:  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2457</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightComment">// possibility to have a special symbol</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2458</span><span class="doxyLineContent"><span class="doxyHighlight">                     q = p;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2459</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> cnt = 2; </span><span class="doxyHighlightComment">// we have to count &amp; and ; as well</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2460</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((*q &gt;= </span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; *q &lt;= </span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">) || (*q &gt;= </span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> &amp;&amp; *q &lt;= </span><span class="doxyHighlightCharLiteral">'Z'</span><span class="doxyHighlight">) || (*q &gt;= </span><span class="doxyHighlightCharLiteral">'0'</span><span class="doxyHighlight"> &amp;&amp; *q &lt;= </span><span class="doxyHighlightCharLiteral">'9'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2461</span><span class="doxyLineContent"><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2462</span><span class="doxyLineContent"><span class="doxyHighlight">                       cnt++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2463</span><span class="doxyLineContent"><span class="doxyHighlight">                       q++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2464</span><span class="doxyLineContent"><span class="doxyHighlight">                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2465</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (*q == </span><span class="doxyHighlightCharLiteral">';'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2466</span><span class="doxyLineContent"><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2467</span><span class="doxyLineContent"><span class="doxyHighlight">                       --p; </span><span class="doxyHighlightComment">// we need &amp; as well</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2468</span><span class="doxyLineContent"><span class="doxyHighlight">                       <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7df">HtmlEntityMapper::SymType</a> res = <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#af0c3a82ead9d9f041131d3bf6ebf9f35">name2sym</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(p).left(cnt));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2469</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (res == <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">HtmlEntityMapper::Sym_Unknown</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2470</span><span class="doxyLineContent"><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2471</span><span class="doxyLineContent"><span class="doxyHighlight">                         p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2472</span><span class="doxyLineContent"><span class="doxyHighlight">                         t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\&amp;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2473</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2474</span><span class="doxyLineContent"><span class="doxyHighlight">                       </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2475</span><span class="doxyLineContent"><span class="doxyHighlight">                       {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2476</span><span class="doxyLineContent"><span class="doxyHighlight">                         t &lt;&lt; <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a401769ae867a274591c49695c3a819f0">latex</a>(res);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2477</span><span class="doxyLineContent"><span class="doxyHighlight">                         q++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2478</span><span class="doxyLineContent"><span class="doxyHighlight">                         p = q;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2479</span><span class="doxyLineContent"><span class="doxyHighlight">                       }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2480</span><span class="doxyLineContent"><span class="doxyHighlight">                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2481</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2482</span><span class="doxyLineContent"><span class="doxyHighlight">                     {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2483</span><span class="doxyLineContent"><span class="doxyHighlight">                       t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\&amp;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2484</span><span class="doxyLineContent"><span class="doxyHighlight">                     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2485</span><span class="doxyLineContent"><span class="doxyHighlight">                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2486</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2487</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">:  <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#aabea2ded9f00d6bbeb03680918e66c02">processEntity</a>(t,pdfHyperlinks,</span><span class="doxyHighlightStringLiteral">"$\\ast$"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"*"</span><span class="doxyHighlight">);    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2488</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideTabbing) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\+"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2489</span><span class="doxyLineContent"><span class="doxyHighlight">                   t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\_"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2490</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideTabbing) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\+"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2491</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2492</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\{"</span><span class="doxyHighlight">;           </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2493</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\}"</span><span class="doxyHighlight">;           </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2494</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&lt;'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"$&lt;$"</span><span class="doxyHighlight">;           </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2495</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&gt;'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"$&gt;$"</span><span class="doxyHighlight">;           </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2496</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight">:  <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#aabea2ded9f00d6bbeb03680918e66c02">processEntity</a>(t,pdfHyperlinks,</span><span class="doxyHighlightStringLiteral">"$\\vert$"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"|"</span><span class="doxyHighlight">);    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2497</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">:  <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#aabea2ded9f00d6bbeb03680918e66c02">processEntity</a>(t,pdfHyperlinks,</span><span class="doxyHighlightStringLiteral">"$\\sim$"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"\\string~"</span><span class="doxyHighlight">);    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2498</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS) || insideItem)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2499</span><span class="doxyLineContent"><span class="doxyHighlight">                     t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\mbox{[}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2500</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2501</span><span class="doxyLineContent"><span class="doxyHighlight">                     t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2502</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2503</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pc==</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"$\\,$"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2504</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PDF_HYPERLINKS) || insideItem)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2505</span><span class="doxyLineContent"><span class="doxyHighlight">                       t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\mbox{]}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2506</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2507</span><span class="doxyLineContent"><span class="doxyHighlight">                       t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2508</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2509</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"-\\/"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2510</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2511</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\textbackslash{}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2512</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2513</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"{}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2514</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2515</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'`'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\`{}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2516</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2517</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\''</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\textquotesingle{}"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2518</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2519</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (retainNewline) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\newline"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> t &lt;&lt; </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2520</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2521</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">:  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (keepSpaces) { </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (insideTabbing) t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\&gt;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> t &lt;&lt; </span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">; } </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> t &lt;&lt; </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2522</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2523</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2524</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2525</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightComment">//if (!insideTabbing &amp;&amp; forceBreaks &amp;&amp; c!=' ' &amp;&amp; *p!=' ')</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2526</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!insideTabbing &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2527</span><span class="doxyLineContent"><span class="doxyHighlight">                       ((c&gt;=</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'Z'</span><span class="doxyHighlight"> &amp;&amp; pc!=</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> &amp;&amp; !(pc&gt;=</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> &amp;&amp; pc &lt;= </span><span class="doxyHighlightCharLiteral">'Z'</span><span class="doxyHighlight">) &amp;&amp; pc!=</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight"> &amp;&amp; *p) || (c==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight"> &amp;&amp; pc!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) || (pc==</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight"> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(c)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2528</span><span class="doxyLineContent"><span class="doxyHighlight">                      )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2529</span><span class="doxyLineContent"><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2530</span><span class="doxyLineContent"><span class="doxyHighlight">                     t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\+"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2531</span><span class="doxyLineContent"><span class="doxyHighlight">                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2532</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c&lt;32)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2533</span><span class="doxyLineContent"><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2534</span><span class="doxyLineContent"><span class="doxyHighlight">                     t &lt;&lt; </span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// non-printable control character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2535</span><span class="doxyLineContent"><span class="doxyHighlight">                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2536</span><span class="doxyLineContent"><span class="doxyHighlight">                   </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2537</span><span class="doxyLineContent"><span class="doxyHighlight">                   {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2538</span><span class="doxyLineContent"><span class="doxyHighlight">                     t &lt;&lt; static_cast&lt;char&gt;(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2539</span><span class="doxyLineContent"><span class="doxyHighlight">                   }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2540</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2541</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2542</span><span class="doxyLineContent"><span class="doxyHighlight">    pc = c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2543</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2544</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/docparser-p-h/#a2515a32b6dfcda676ef65dd34fad5abf">insideTable</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a401769ae867a274591c49695c3a819f0">HtmlEntityMapper::latex</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#af0c3a82ead9d9f041131d3bf6ebf9f35">HtmlEntityMapper::name2sym</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#aabea2ded9f00d6bbeb03680918e66c02">processEntity</a> and <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a5fa49b07f0b74254ab5bd5b18474d7dfa4afd8f33f5ff42a444da284278109d9f">HtmlEntityMapper::Sym_Unknown</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/latexcodegenerator/#ace27d46d07e19112fc6ee3411915c8ea">LatexCodeGenerator::codify</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5261de94ef3b325400ae7b7a0f71630a">convertToLaTeX</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a4c9d7e8efc817dc5bc5a851500171308">LatexGenerator::docify</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a99fd1bd50877a6c36721da21a2a2eb1e">LatexDocVisitor::filter</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad32126ac958c2ac22491a47f6957935c">latexEscapeIndexChars</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afd297d2d96747033593750c401bfe95e">latexEscapeLabelName</a> and <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad17beb87ce167c3b4203b5260ff7b2a9">substituteLatexKeywords</a>.</p>

</div>
</div>

### latexEscapeIndexChars() {#ad32126ac958c2ac22491a47f6957935c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString latexEscapeIndexChars (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 351 of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line 2598 of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad32126ac958c2ac22491a47f6957935c">2598</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad32126ac958c2ac22491a47f6957935c">latexEscapeIndexChars</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2599</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2600</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("latexEscapeIndexChars(%s)\n",qPrint(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2601</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2602</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp(s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>(), <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2603</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2604</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2605</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2606</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2607</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2608</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2609</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2610</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"!"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2611</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"\""</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2612</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"@"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2613</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\texttt{\"|}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2614</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"["</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2615</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"]"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2616</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\lcurly{}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2617</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\rcurly{}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2618</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// NOTE: adding a case here, means adding it to while below as well!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2619</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2620</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2621</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2622</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// collect as long string as possible, before handing it to docify</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2623</span><span class="doxyLineContent"><span class="doxyHighlight">          tmp[i++]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2624</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p) &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'"'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2625</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2626</span><span class="doxyLineContent"><span class="doxyHighlight">            tmp[i++]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2627</span><span class="doxyLineContent"><span class="doxyHighlight">            p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2628</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2629</span><span class="doxyLineContent"><span class="doxyHighlight">          tmp[i]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2630</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>(t,tmp,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2631</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,   </span><span class="doxyHighlightComment">// insideTabbing</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2632</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,  </span><span class="doxyHighlightComment">// insidePre</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2633</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,  </span><span class="doxyHighlightComment">// insideItem</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2634</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,  </span><span class="doxyHighlightComment">// insideTable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2635</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">   </span><span class="doxyHighlightComment">// keepSpaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2636</span><span class="doxyLineContent"><span class="doxyHighlight">                           );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2637</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2638</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2639</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2640</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2641</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> t.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2642</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab85e90fb1ce212b54481688febedbc09">LatexGenerator::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a6f9db23dee65e962246bc08bec382947">LatexGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a718f5fc73955ee4e43228ede93284235">LatexDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1f3960465ed8ddd25b9ee0c1bec95622">LatexGenerator::startMemberDoc</a>.</p>

</div>
</div>

### latexEscapeLabelName() {#afd297d2d96747033593750c401bfe95e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString latexEscapeLabelName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 350 of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line 2553 of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afd297d2d96747033593750c401bfe95e">2553</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afd297d2d96747033593750c401bfe95e">latexEscapeLabelName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2554</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2555</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("latexEscapeLabelName(%s)\n",qPrint(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2556</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2557</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tmp(s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>(), <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2558</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2559</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2560</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2561</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2562</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2563</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2564</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2565</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\texttt{\"|}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2566</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"!"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2567</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"@"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2568</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'%'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\%"</span><span class="doxyHighlight">;       </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2569</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\lcurly{}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2570</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\rcurly{}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2571</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"````~"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// to get it a bit better in index together with other special characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2572</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// NOTE: adding a case here, means adding it to while below as well!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2573</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2574</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2575</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2576</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// collect as long string as possible, before handing it to docify</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2577</span><span class="doxyLineContent"><span class="doxyHighlight">          tmp[i++]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2578</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p) &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'@'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">']'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'!'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">'|'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2579</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2580</span><span class="doxyLineContent"><span class="doxyHighlight">            tmp[i++]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2581</span><span class="doxyLineContent"><span class="doxyHighlight">            p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2582</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2583</span><span class="doxyLineContent"><span class="doxyHighlight">          tmp[i]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2584</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>(t,tmp,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2585</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,  </span><span class="doxyHighlightComment">// insideTabbing</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2586</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">, </span><span class="doxyHighlightComment">// insidePre</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2587</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">, </span><span class="doxyHighlightComment">// insideItem</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2588</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">, </span><span class="doxyHighlightComment">// insideTable</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2589</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// keepSpaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2590</span><span class="doxyLineContent"><span class="doxyHighlight">                           );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2591</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2592</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2593</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2594</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2595</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> t.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2596</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a96afd525d79a1a43fbaabae3483b2e6b">filterLatexString</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/latexgenerator/#ab85e90fb1ce212b54481688febedbc09">LatexGenerator::addIndexItem</a>, <a href="/web-doxygen/docs/api/classes/latexgenerator/#a6f9db23dee65e962246bc08bec382947">LatexGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a718f5fc73955ee4e43228ede93284235">LatexDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1f3960465ed8ddd25b9ee0c1bec95622">LatexGenerator::startMemberDoc</a>.</p>

</div>
</div>

### latexEscapePDFString() {#a37bf597b522fe84aefa564de5b8489c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString latexEscapePDFString (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 352 of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line 2644 of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a37bf597b522fe84aefa564de5b8489c2">2644</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a37bf597b522fe84aefa564de5b8489c2">latexEscapePDFString</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2645</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2646</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2647</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2648</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2649</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2650</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2651</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2652</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2653</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2654</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">: t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\textbackslash{}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2655</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\{"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2656</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\}"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2657</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\_"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2658</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'%'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\%"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2659</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'&amp;'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\&amp;"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2660</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\#"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2661</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\$"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2662</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\string^"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2663</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'~'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\string~"</span><span class="doxyHighlight">;    </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2664</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2665</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2666</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2667</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2668</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2669</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> t.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2670</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/latexgenerator/#a1f3960465ed8ddd25b9ee0c1bec95622">LatexGenerator::startMemberDoc</a>.</p>

</div>
</div>

### latexFilterURL() {#a5b4eb46ed4177d10b053426f65925171}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString latexFilterURL (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 353 of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line 2672 of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5b4eb46ed4177d10b053426f65925171">2672</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a5b4eb46ed4177d10b053426f65925171">latexFilterURL</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2673</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2674</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">constexpr</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a> = </span><span class="doxyHighlightStringLiteral">"0123456789ABCDEF"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2675</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2676</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2677</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2678</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2679</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2680</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2681</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (c)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2682</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2683</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\#"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2684</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'%'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\%"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2685</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> </span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">:  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\\\"</span><span class="doxyHighlight">; </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2686</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2687</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c&lt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2688</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2689</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2690</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\%"</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">&gt;&gt;4] &lt;&lt; <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>[</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">&amp;0xF];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2691</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2692</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2693</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2694</span><span class="doxyLineContent"><span class="doxyHighlight">          t &lt;&lt; c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2695</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2696</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2697</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2698</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2699</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> t.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2700</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/docbookgen-cpp/#a1748a7403991604b7f600589b77f9937">hex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#a39ce90cc4d05a3748cffe6519957ba59">LatexDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ae73d9be71f9eba3b4aab19bb46c69fc8">LatexDocVisitor::operator()</a>.</p>

</div>
</div>

### writeExtraLatexPackages() {#ace2411e2a91d0794515d7319a05a96e4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeExtraLatexPackages (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 338 of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line 2327 of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ace2411e2a91d0794515d7319a05a96e4">2327</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ace2411e2a91d0794515d7319a05a96e4">writeExtraLatexPackages</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2328</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2329</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// User-specified packages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2330</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;extraPackages = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(EXTRA_PACKAGES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2331</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!extraPackages.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2332</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2333</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"% Packages requested by user\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2334</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pkgName : extraPackages)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2335</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2336</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((pkgName[0] == </span><span class="doxyHighlightCharLiteral">'['</span><span class="doxyHighlight">) || (pkgName[0] == </span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2337</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\usepackage"</span><span class="doxyHighlight"> &lt;&lt; pkgName.c_str() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2338</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2339</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\usepackage{"</span><span class="doxyHighlight"> &lt;&lt; pkgName.c_str() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2340</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2341</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2342</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2343</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/formulamanager/#a0f96928dbcf6279d70d38ee11b35ea55">FormulaManager::createLatexFile</a> and <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad17beb87ce167c3b4203b5260ff7b2a9">substituteLatexKeywords</a>.</p>

</div>
</div>

### writeLatexSpecialFormulaChars() {#afb096be4b2c37adc54becb763cc99470}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeLatexSpecialFormulaChars (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 339 of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>, definition at line 2345 of file <a href="/web-doxygen/docs/api/files/src/latexgen-cpp">latexgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afb096be4b2c37adc54becb763cc99470">2345</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afb096be4b2c37adc54becb763cc99470">writeLatexSpecialFormulaChars</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2346</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2347</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> minus[4]; </span><span class="doxyHighlightComment">// Superscript minus</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2348</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> sup2[3]; </span><span class="doxyHighlightComment">// Superscript two</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2349</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> sup3[3];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2350</span><span class="doxyLineContent"><span class="doxyHighlight">    minus[0]= 0xE2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2351</span><span class="doxyLineContent"><span class="doxyHighlight">    minus[1]= 0x81;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2352</span><span class="doxyLineContent"><span class="doxyHighlight">    minus[2]= 0xBB;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2353</span><span class="doxyLineContent"><span class="doxyHighlight">    minus[3]= 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2354</span><span class="doxyLineContent"><span class="doxyHighlight">    sup2[0]= 0xC2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2355</span><span class="doxyLineContent"><span class="doxyHighlight">    sup2[1]= 0xB2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2356</span><span class="doxyLineContent"><span class="doxyHighlight">    sup2[2]= 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2357</span><span class="doxyLineContent"><span class="doxyHighlight">    sup3[0]= 0xC2;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2358</span><span class="doxyLineContent"><span class="doxyHighlight">    sup3[1]= 0xB3;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2359</span><span class="doxyLineContent"><span class="doxyHighlight">    sup3[2]= 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2360</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2361</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\ifPDFTeX\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2362</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\usepackage{newunicodechar}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2363</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// taken from the newunicodechar package and removed the warning message</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2364</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// actually forcing to redefine the unicode character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2365</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  \\makeatletter\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2366</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"    \\def\\doxynewunicodechar#1#2{%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2367</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"    \\@tempswafalse\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2368</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"    \\edef\\nuc@tempa{\\detokenize{#1}}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2369</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"    \\if\\relax\\nuc@tempa\\relax\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2370</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"      \\nuc@emptyargerr\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2371</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"    \\else\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2372</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"      \\edef\\@tempb{\\expandafter\\@car\\nuc@tempa\\@nil}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2373</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"      \\nuc@check\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2374</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"      \\if@tempswa\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2375</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"        \\@namedef{u8:\\nuc@tempa}{#2}%\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2376</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"      \\fi\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2377</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"    \\fi\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2378</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"  }\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2379</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"  \\makeatother\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2380</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2381</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"  \\doxynewunicodechar{"</span><span class="doxyHighlight"> &lt;&lt; minus &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{${}^{-}$}% Superscript minus\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2382</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"  \\doxynewunicodechar{"</span><span class="doxyHighlight"> &lt;&lt; sup2  &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{${}^{2}$}% Superscript two\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2383</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"  \\doxynewunicodechar{"</span><span class="doxyHighlight"> &lt;&lt; sup3  &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}{${}^{3}$}% Superscript three\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2384</span><span class="doxyLineContent"><span class="doxyHighlight">         </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2385</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\fi\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2386</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/formulamanager/#a0f96928dbcf6279d70d38ee11b35ea55">FormulaManager::createLatexFile</a> and <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ad17beb87ce167c3b4203b5260ff7b2a9">substituteLatexKeywords</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### LATEX\_STYLE\_EXTENSION {#a6243d84ee6552fd5282db11d491c2e18}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define LATEX_STYLE_EXTENSION&nbsp;&nbsp;&nbsp;".sty"</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 22 of file <a href="/web-doxygen/docs/api/files/src/latexgen-h">latexgen.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6243d84ee6552fd5282db11d491c2e18">22</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define LATEX_STYLE_EXTENSION ".sty"</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0b6e771472be8544a7e1af3ec30dce25">copyLatexStyleSheet</a> and <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#a94fbb614f459de73cf139b286f1f1ce1">extraLatexStyleSheet</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
