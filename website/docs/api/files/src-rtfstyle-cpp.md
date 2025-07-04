---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/rtfstyle-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `rtfstyle.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;string&gt;
#include &lt;fstream&gt;
#include "<a href="/web-doxygen/docs/api/files/src/rtfstyle-h">rtfstyle.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>"
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a60858edb01bcbd780025cecdf65c8f">loadStylesheet</a> (const QCString &amp;name, StyleDataMap &amp;map)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a36e764c0a931ef05c53d3695489d198e">loadExtensions</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a86de556a1278f74936d85c3ad6737305">rtf_title</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ababa40e3b47889c9d6a12b2c27b1dcea">rtf_subject</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab52a06ee957fd74f7e3cc2d7237ea8b9">rtf_comments</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0324698363e2cd57eab1023a6dfd3eaf">rtf_company</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6dadec111c906be2f9b08e2b20a203d0">rtf_logoFilename</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3f13730015be2d7e9ab56c1282b4b9a">rtf_author</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab3df69814841b23f1daaf5cdf52f11ce">rtf_manager</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a171eccae8452542c0917db77076e6769">rtf_documentType</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5cb613ade78225b9d6487115d840fd7">rtf_documentId</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa26f5b63acab74269d212f1559aafb5b">rtf_keywords</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::map&lt; std::string, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63b8fcd3cb27b8f30fdd944c157036bc">g_styleMap</a> = ...</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">char</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>[] = "\\pard\\plain "</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/rtf-style-default">Rtf_Style_Default</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1c7e59c4175c745476a2f8a1cb78644e">rtf_Style_Default</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/rtf-table-default">Rtf_Table_Default</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9be00547f87f6bfa84d2b558e4b211eb">rtf_Table_Default</a>[]</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7ce4348d587548a514b1e698abed1a54">s_clause</a>(R"(\\s(\d+)\s*)")</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/rtfstyle-h/#a1bdbbe05f0332d6cc81776723ad75332">StyleDataMap</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>(lvl, nest, nxt, pos, twps)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>(lvl, nest, nxt, pos, lvl2)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>(lvl, nest, nxt, pos)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>(lvl, nest, nxt, pos)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>(lvl, nest, nxt, pos)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>(lvl, nest, nxt, pos)&nbsp;&nbsp;&nbsp;...</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>(id, lvl, pos, chr)&nbsp;&nbsp;&nbsp;...</td>
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

### loadExtensions() {#a36e764c0a931ef05c53d3695489d198e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void loadExtensions (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 364 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a36e764c0a931ef05c53d3695489d198e">364</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a36e764c0a931ef05c53d3695489d198e">loadExtensions</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ifstream file(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Can't open RTF extensions file {}. Using defaults.\n"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Loading RTF extensions {}...\n"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t lineNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (std::string line ; getline(file,line) ; ) </span><span class="doxyHighlightComment">// for each line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (line.empty() || line[0]==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip blanks &amp; comments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> assignment_splitter(R</span><span class="doxyHighlightStringLiteral">"(\s*=\s*)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">    <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(line,match,assignment_splitter))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string key   = match.prefix().str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string value = match.suffix().str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a63b8fcd3cb27b8f30fdd944c157036bc">g_styleMap</a>.find(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#a63b8fcd3cb27b8f30fdd944c157036bc">g_styleMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">        it-&gt;second = value;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(name,lineNr,</span><span class="doxyHighlightStringLiteral">"Ignoring unknown extension key '{}'..."</span><span class="doxyHighlight">,key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(name,lineNr,</span><span class="doxyHighlightStringLiteral">"Assignment of style sheet name expected!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">    lineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="#a63b8fcd3cb27b8f30fdd944c157036bc">g_styleMap</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a20ebc13fc3ca037f977dc8144847db73">RTFGenerator::init</a>.</p>

</div>
</div>

### loadStylesheet() {#a1a60858edb01bcbd780025cecdf65c8f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void loadStylesheet (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, <a href="/web-doxygen/docs/api/files/src/rtfstyle-h/#a1bdbbe05f0332d6cc81776723ad75332">StyleDataMap</a> &amp; map)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 322 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1a60858edb01bcbd780025cecdf65c8f">322</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1a60858edb01bcbd780025cecdf65c8f">loadStylesheet</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name, <a href="/web-doxygen/docs/api/files/src/rtfstyle-h/#a1bdbbe05f0332d6cc81776723ad75332">StyleDataMap</a>&amp; map)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ifstream file(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!file.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Can't open RTF style sheet file {}. Using defaults.\n"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Loading RTF style sheet {}...\n"</span><span class="doxyHighlight">,name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">  uint32_t lineNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (std::string line ; getline(file,line) ; ) </span><span class="doxyHighlightComment">// for each line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (line.empty() || line[0]==</span><span class="doxyHighlightCharLiteral">'#'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">continue</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// skip blanks &amp; comments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> assignment_splitter(R</span><span class="doxyHighlightStringLiteral">"(\s*=\s*)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">    <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(line,match,assignment_splitter))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string key   = match.prefix().str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string value = match.suffix().str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = map.find(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=map.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/structs/styledata">StyleData</a>&amp; styleData = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">        styleData.<a href="/web-doxygen/docs/api/structs/styledata/#a7a9ef51c3d04534f0d123bc771ab3367">setStyle</a>(value,key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(name,lineNr,</span><span class="doxyHighlightStringLiteral">"Unknown style sheet name {} ignored."</span><span class="doxyHighlight">,key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(name,lineNr,</span><span class="doxyHighlightStringLiteral">"Assignment of style sheet name expected line='{}'!"</span><span class="doxyHighlight">,line);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">    lineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>, <a href="/web-doxygen/docs/api/structs/styledata/#a7a9ef51c3d04534f0d123bc771ab3367">StyleData::setStyle</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a20ebc13fc3ca037f977dc8144847db73">RTFGenerator::init</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### g\_styleMap {#a63b8fcd3cb27b8f30fdd944c157036bc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string,QCString &amp;&gt; g_styleMap</td>
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



<dl class="doxySectionUser">
<dt>Initialiser</dt>
<dd>
<div class="doxyVerbatim">=
{
  { "Title",        <a href="#a86de556a1278f74936d85c3ad6737305">rtf_title</a>        },
  { "Subject",      <a href="#ababa40e3b47889c9d6a12b2c27b1dcea">rtf_subject</a>      },
  { "Comments",     <a href="#ab52a06ee957fd74f7e3cc2d7237ea8b9">rtf_comments</a>     },
  { "Company",      <a href="#a0324698363e2cd57eab1023a6dfd3eaf">rtf_company</a>      },
  { "LogoFilename", <a href="#a6dadec111c906be2f9b08e2b20a203d0">rtf_logoFilename</a> },
  { "Author",       <a href="#aa3f13730015be2d7e9ab56c1282b4b9a">rtf_author</a>       },
  { "Manager",      <a href="#ab3df69814841b23f1daaf5cdf52f11ce">rtf_manager</a>      },
  { "DocumentType", <a href="#a171eccae8452542c0917db77076e6769">rtf_documentType</a> },
  { "DocumentId",   <a href="#ae5cb613ade78225b9d6487115d840fd7">rtf_documentId</a>   },
  { "Keywords",     <a href="#aa26f5b63acab74269d212f1559aafb5b">rtf_keywords</a>     }
}
</div>
</dd>
</dl>

<p>Definition at line 34 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a63b8fcd3cb27b8f30fdd944c157036bc">34</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::map&lt;std::string,QCString &amp;&gt; <a href="#a63b8fcd3cb27b8f30fdd944c157036bc">g_styleMap</a> =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">35</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">36</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Title"</span><span class="doxyHighlight">,        <a href="#a86de556a1278f74936d85c3ad6737305">rtf_title</a>        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">37</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Subject"</span><span class="doxyHighlight">,      <a href="#ababa40e3b47889c9d6a12b2c27b1dcea">rtf_subject</a>      },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">38</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Comments"</span><span class="doxyHighlight">,     <a href="#ab52a06ee957fd74f7e3cc2d7237ea8b9">rtf_comments</a>     },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Company"</span><span class="doxyHighlight">,      <a href="#a0324698363e2cd57eab1023a6dfd3eaf">rtf_company</a>      },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"LogoFilename"</span><span class="doxyHighlight">, <a href="#a6dadec111c906be2f9b08e2b20a203d0">rtf_logoFilename</a> },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Author"</span><span class="doxyHighlight">,       <a href="#aa3f13730015be2d7e9ab56c1282b4b9a">rtf_author</a>       },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Manager"</span><span class="doxyHighlight">,      <a href="#ab3df69814841b23f1daaf5cdf52f11ce">rtf_manager</a>      },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">43</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"DocumentType"</span><span class="doxyHighlight">, <a href="#a171eccae8452542c0917db77076e6769">rtf_documentType</a> },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">44</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"DocumentId"</span><span class="doxyHighlight">,   <a href="#ae5cb613ade78225b9d6487115d840fd7">rtf_documentId</a>   },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Keywords"</span><span class="doxyHighlight">,     <a href="#aa26f5b63acab74269d212f1559aafb5b">rtf_keywords</a>     }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="#a36e764c0a931ef05c53d3695489d198e">loadExtensions</a>.</p>

</div>
</div>

### rtf\_author {#aa3f13730015be2d7e9ab56c1282b4b9a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString rtf_author</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa3f13730015be2d7e9ab56c1282b4b9a">28</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aa3f13730015be2d7e9ab56c1282b4b9a">rtf_author</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>.</p>

</div>
</div>

### rtf\_comments {#ab52a06ee957fd74f7e3cc2d7237ea8b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString rtf_comments</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 25 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab52a06ee957fd74f7e3cc2d7237ea8b9">25</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab52a06ee957fd74f7e3cc2d7237ea8b9">rtf_comments</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>.</p>

</div>
</div>

### rtf\_company {#a0324698363e2cd57eab1023a6dfd3eaf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString rtf_company</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 26 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0324698363e2cd57eab1023a6dfd3eaf">26</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a0324698363e2cd57eab1023a6dfd3eaf">rtf_company</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>.</p>

</div>
</div>

### rtf\_documentId {#ae5cb613ade78225b9d6487115d840fd7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString rtf_documentId</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5cb613ade78225b9d6487115d840fd7">31</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ae5cb613ade78225b9d6487115d840fd7">rtf_documentId</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a>.</p>

</div>
</div>

### rtf\_documentType {#a171eccae8452542c0917db77076e6769}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString rtf_documentType</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a171eccae8452542c0917db77076e6769">30</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a171eccae8452542c0917db77076e6769">rtf_documentType</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>.</p>

</div>
</div>

### rtf\_keywords {#aa26f5b63acab74269d212f1559aafb5b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString rtf_keywords</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa26f5b63acab74269d212f1559aafb5b">32</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#aa26f5b63acab74269d212f1559aafb5b">rtf_keywords</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>.</p>

</div>
</div>

### rtf\_logoFilename {#a6dadec111c906be2f9b08e2b20a203d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString rtf_logoFilename</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 27 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6dadec111c906be2f9b08e2b20a203d0">27</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a6dadec111c906be2f9b08e2b20a203d0">rtf_logoFilename</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a20ebc13fc3ca037f977dc8144847db73">RTFGenerator::init</a>.</p>

</div>
</div>

### rtf\_manager {#ab3df69814841b23f1daaf5cdf52f11ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString rtf_manager</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab3df69814841b23f1daaf5cdf52f11ce">29</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ab3df69814841b23f1daaf5cdf52f11ce">rtf_manager</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>.</p>

</div>
</div>

### rtf\_Style {#a0e6daceda067f191c8ec56f44ec2486f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">StyleDataMap rtf_Style</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 362 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0e6daceda067f191c8ec56f44ec2486f">362</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/src/rtfstyle-h/#a1bdbbe05f0332d6cc81776723ad75332">StyleDataMap</a> <a href="#a0e6daceda067f191c8ec56f44ec2486f">rtf_Style</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a3a64ef0ca4a6a8f00c6b38e80e9d4545">RTFGenerator::beginRTFChapter</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aaaed62b7c9e0ef2c5ba6133eba8203a1">RTFGenerator::beginRTFDocument</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab1939f0d3e5142f9b77cf8ce807e00a7">RTFGenerator::beginRTFSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7467e3f0f800ca5303ce1e6e473cdcfe">RTFDocVisitor::getStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a20ebc13fc3ca037f977dc8144847db73">RTFGenerator::init</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a4354834197f45954df7a81d84f70c34d">RTFGenerator::lastIndexPage</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ae0c5c194fc2579df52204eb00134c6bf">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adae81723bf98cc11856ec916852cf089">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a6f4df2c3160f09e662393e6a23b2add0">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a07acb7803948c3811f88d4efa00587a4">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a89b1ef4b308483fcf725cef8081e5849">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aa17fa64bc141c519b0b24e0a475ab1e1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7f10a43fc0a35475e9078305d745951f">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9f4db29aeeb7d0f2ab033f6235a69912">RTFGenerator::rtf_BList_DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afd3768dca041d56a01b01061bb41aec5">RTFGenerator::rtf_CList_DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#a5b9f9d4a335e0e68bad617fdceb9e318">RTFCodeGenerator::rtf_Code_DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a9f8483e6f7e65c06e5f4f507f0887f67">RTFGenerator::rtf_DList_DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a7527ce8866206a633c1cfb684cc22574">RTFGenerator::rtf_EList_DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac5b5b70aa6da3566aa9724b3aa617192">RTFGenerator::rtf_LCList_DepthStyle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aad5bd8b4ea091547b08a00ba70f0aa07">RTFGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab4f116084ff07d558fd61db56501e61d">RTFGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a4e30c4664b1c3cc9a1cb26a2ae98968d">RTFGenerator::startDescTableInit</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8454a525177779c9bb183b0ad36fa56b">RTFGenerator::startDescTableTitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afc0d8b219f558b257eed6bb523c79fab">RTFGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aedc9cfff56c51ffc2bae28353a319b2e">RTFGenerator::startInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0db9ec198444ce05559d81134b3696">RTFGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aacbda0698357ec14331ff4ff82f3a2ab">RTFGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a7ec7eb8980ebddb6c74f2db073e9ab76">RTFGenerator::startMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae4e5ba15b96993174f41a6269f233a6a">RTFGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a012cbbfdb3b792d3d0204004cc7d7772">RTFGenerator::startTextBlock</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adf7c83ee8198c326eb4e8efd9f9f1a0a">RTFGenerator::startTitleHead</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a54e526de8b03280571dc1c0003a14746">RTFGenerator::writeInheritedSectionTitle</a>.</p>

</div>
</div>

### rtf\_Style\_Default {#a1c7e59c4175c745476a2f8a1cb78644e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Rtf_Style_Default rtf_Style_Default[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 88 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1c7e59c4175c745476a2f8a1cb78644e">88</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/rtf-style-default">Rtf_Style_Default</a> <a href="#a1c7e59c4175c745476a2f8a1cb78644e">rtf_Style_Default</a>[] =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Heading1"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s1\\sb240\\sa60\\keepn\\widctlpar\\adjustright \\b\\f1\\fs36\\kerning36\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext0 heading 1"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Heading2"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s2\\sb240\\sa60\\keepn\\widctlpar\\adjustright \\b\\f1\\fs28\\kerning28\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext0 heading 2"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Heading3"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s3\\sb240\\sa60\\keepn\\widctlpar\\adjustright \\b\\f1\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext0 heading 3"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Heading4"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s4\\sb240\\sa60\\keepn\\widctlpar\\adjustright \\b\\f1\\fs20\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext0 heading 4;}{\\*\\cs10 \\additive Default Paragraph Font"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Heading5"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s5\\sb90\\sa30\\keepn\\widctlpar\\adjustright \\b\\f1\\fs16\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext0 heading 5;}{\\*\\cs10 \\additive Default Paragraph Font"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Heading6"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s6\\sb90\\sa30\\keepn\\widctlpar\\adjustright \\b\\f1\\fs12\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext0 heading 6;}{\\*\\cs10 \\additive Default Paragraph Font"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Title"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s15\\qc\\sb240\\sa60\\widctlpar\\outlinelevel0\\adjustright \\b\\f1\\fs32\\kerning28\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext15 Title"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"SubTitle"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s16\\qc\\sa60\\widctlpar\\outlinelevel1\\adjustright \\f1\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext16 Subtitle"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"BodyText"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s17\\sa60\\sb30\\widctlpar\\qj \\fs22\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext17 BodyText"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"DenseText"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s18\\widctlpar\\fs22\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext18 DenseText"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Header"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s28\\widctlpar\\tqc\\tx4320\\tqr\\tx8640\\adjustright \\fs20\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext28 header"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"Footer"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s29\\widctlpar\\tqc\\tx4320\\tqr\\tx8640\\qr\\adjustright \\fs20\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext29 footer"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightStringLiteral">"GroupHeader"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\s30\\li360\\sa60\\sb120\\keepn\\widctlpar\\adjustright \\b\\f1\\fs20\\cgrid "</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightStringLiteral">"\\sbasedon0 \\snext30 GroupHeader"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">  },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>( 0, 40, 41,   0),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>( 1, 41, 42, 360),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>( 2, 42, 43, 720),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>( 3, 43, 44,1080),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>( 4, 44, 45,1440),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>( 5, 45, 46,1800),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>( 6, 46, 47,2160),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>( 7, 47, 48,2520),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>( 8, 48, 49,2880),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>( 9, 49, 50,3240),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>(10, 50, 51,3600),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>(11, 51, 52,3960),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>(12, 52, 53,4320),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a35078b7f9f90726f496eb0c2e9dec3c1">RTF_CodeExample</a>(13, 53, 53,4680),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>( 0, 60, 61,   0),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>( 1, 61, 62, 360),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>( 2, 62, 63, 720),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>( 3, 63, 64,1080),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>( 4, 64, 65,1440),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>( 5, 65, 66,1800),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>( 6, 66, 67,2160),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>( 7, 67, 68,2520),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>( 8, 68, 69,2880),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>( 9, 69, 70,3240),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>(10, 70, 71,3600),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>(11, 71, 72,3960),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>(12, 72, 73,4320),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a936372eb65e3b7a2c789d6ad29fb661d">RTF_ListContinue</a>(13, 73, 73,4680),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>( 0, 80, 81,   0),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>( 1, 81, 82, 360),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>( 2, 82, 83, 720),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>( 3, 83, 84,1080),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>( 4, 84, 85,1440),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>( 5, 85, 86,1800),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>( 6, 86, 87,2160),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>( 7, 87, 88,2520),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>( 8, 88, 89,2880),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>( 9, 89, 90,3240),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>(10, 90, 91,3600),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>(11, 91, 92,3960),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>(12, 92, 93,4320),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8cff47864029012a9b69bcd2847a5569">RTF_DescContinue</a>(13, 93, 93,4680),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>( 0,100,101,   0,30),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>( 1,101,102, 360,27),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>( 2,102,103, 720,24),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>( 3,103,104,1080,21),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>( 4,104,105,1440,18),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>( 5,105,106,1800,15),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>( 6,106,107,2160,12),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>( 7,107,108,2520, 9),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>( 8,108,109,2880, 6),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>( 9,109,110,3240, 3),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>(10,110,111,3600, 3),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>(11,111,112,3960, 3),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>(12,112,113,4320, 3),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">RTF_LatexToc</a>(13,113,113,4680, 3),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>( 0,120,121, 360, 1),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>( 1,121,122, 720, 2),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>( 2,122,123,1080, 3),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>( 3,123,124,1440, 4),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>( 4,124,125,1800, 5),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>( 5,125,126,2160, 6),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>( 6,126,127,2520, 7),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>( 7,127,128,2880, 8),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>( 8,128,129,3240, 9),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>( 9,129,130,3600,10),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>(10,130,131,3960,11),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>(11,131,132,4320,12),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>(12,132,133,4680,13),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#acf6653c078262217dfb07ef7993e2bdf">RTF_ListBullet</a>(13,133,133,5040,14),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>( 0,140,141, 360),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>( 1,141,142, 720),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>( 2,142,143,1080),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>( 3,143,144,1440),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>( 4,144,145,1800),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>( 5,145,146,2160),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>( 6,146,147,2520),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>( 7,147,148,2880),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>( 8,148,149,3240),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>( 9,149,150,3600),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>(10,150,151,3960),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>(11,151,152,4320),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>(12,152,153,4680),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">RTF_ListEnum</a>(13,153,153,5040),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a20ebc13fc3ca037f977dc8144847db73">RTFGenerator::init</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a36d46700bc6f704cb8db78dadb9ceba5">RTFGenerator::writeStyleSheetFile</a>.</p>

</div>
</div>

### rtf\_Style\_Reset {#a3588987fef5687c675e6fb979b9850c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">char rtf_Style_Reset[] = "\\pard\\plain "</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3588987fef5687c675e6fb979b9850c1">49</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> <a href="#a3588987fef5687c675e6fb979b9850c1">rtf_Style_Reset</a>[] = </span><span class="doxyHighlightStringLiteral">"\\pard\\plain "</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a3a64ef0ca4a6a8f00c6b38e80e9d4545">RTFGenerator::beginRTFChapter</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab1939f0d3e5142f9b77cf8ce807e00a7">RTFGenerator::beginRTFSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adeb275db39d63df2f74c728adaa70849">RTFGenerator::endCallGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a0322020ce9d74181bb997b886239ce19">RTFGenerator::endClassDiagram</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a1cd78a44f9072b2d24765b07fbd4f01f">RTFGenerator::endDirDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a87f599a42c46d9fce84f456797ff231c">RTFGenerator::endDotGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ad4d65d3f43a0ca0ff1e6cc7564a0164c">RTFGenerator::endGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa1a701e0ab2c31d782a7faae9e0135e1">RTFGenerator::endInclDepGraph</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a01d9e19175b7f2f875be520f1ea105b3">RTFGenerator::endMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ac82e6d2bb73a007715d4ccf10552848d">RTFGenerator::endTitleHead</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a2e791b200dd11ec24ff27a9aab0f8940">RTFDocVisitor::includePicturePreRTF</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a39a5bf02292d858e211a2cb3ee3f62c1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a022f6eb89bc55b752aeff008e9c9037d">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a85db1985a82081ef9ab2e5a25c450f28">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#acc6c497f52cf55d67723f21ec2a97c6b">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#adae81723bf98cc11856ec916852cf089">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a63f63207a160e4e99a4c2dd5b55734c8">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a75e708a4ea1b27587678f424211b8b62">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a6f4df2c3160f09e662393e6a23b2add0">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a4fcb960f7e5b593e8e6c51ea43f66a9a">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a89b1ef4b308483fcf725cef8081e5849">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#add264d5a56e09e76ec274af99af747d2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#aa17fa64bc141c519b0b24e0a475ab1e1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af3beab942bf46b1f903ac30ac39a10d2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a101e1d1d08453e6a606f9f8652a6cc73">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7f10a43fc0a35475e9078305d745951f">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#acd2fed43ebf5f693abe84471a520cbe9">RTFCodeGenerator::startCodeFragment</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aad5bd8b4ea091547b08a00ba70f0aa07">RTFGenerator::startCompoundTemplateParams</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a29a84d512d59f79ef193e7b0f5010a9d">RTFGenerator::startConstraintList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ab4f116084ff07d558fd61db56501e61d">RTFGenerator::startDescTable</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ad69c3570dc9ede5dd3058791e252c3cc">RTFGenerator::startExamples</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afc0d8b219f558b257eed6bb523c79fab">RTFGenerator::startGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a434d17937e0e38eb2a631866282cece0">RTFGenerator::startIndent</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a969f88aefb693d90e5ced9f91a20b4bc">RTFGenerator::startIndexList</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aedc9cfff56c51ffc2bae28353a319b2e">RTFGenerator::startInlineHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a6847cacb71fc0487655971490b6eb778">RTFGenerator::startItemListItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#afccb8a5712c326ee5cee2a0caea2bbb1">RTFGenerator::startMemberDescription</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0db9ec198444ce05559d81134b3696">RTFGenerator::startMemberDoc</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aacbda0698357ec14331ff4ff82f3a2ab">RTFGenerator::startMemberDocSimple</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#abbafc50a4d1a1c021aa659883d40ef45">RTFGenerator::startMemberGroup</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a7ec7eb8980ebddb6c74f2db073e9ab76">RTFGenerator::startMemberGroupHeader</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa37f27c3476aa545d3e364b3df70baa8">RTFGenerator::startMemberItem</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a5e6c5dd7997b60786df03efbfa3a04f2">RTFGenerator::startMemberSubtitle</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#ae4e5ba15b96993174f41a6269f233a6a">RTFGenerator::startSection</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a012cbbfdb3b792d3d0204004cc7d7772">RTFGenerator::startTextBlock</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#adf7c83ee8198c326eb4e8efd9f9f1a0a">RTFGenerator::startTitleHead</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a54e526de8b03280571dc1c0003a14746">RTFGenerator::writeInheritedSectionTitle</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a63e3c07d31875dab02fb233ae5541d23">RTFGenerator::writePageLink</a>.</p>

</div>
</div>

### rtf\_subject {#ababa40e3b47889c9d6a12b2c27b1dcea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString rtf_subject</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 24 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ababa40e3b47889c9d6a12b2c27b1dcea">24</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ababa40e3b47889c9d6a12b2c27b1dcea">rtf_subject</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aed0e9390b27525400fcd01d49b1f0b74">RTFGenerator::startIndexSection</a>.</p>

</div>
</div>

### rtf\_Table\_Default {#a9be00547f87f6bfa84d2b558e4b211eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Rtf_Table_Default rtf_Table_Default[]</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 245 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9be00547f87f6bfa84d2b558e4b211eb">245</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/rtf-table-default">Rtf_Table_Default</a> <a href="#a9be00547f87f6bfa84d2b558e4b211eb">rtf_Table_Default</a>[] =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 1,0, 360, 8226),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 1,1, 720, 9702),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 1,2,1080, 9642),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 1,3,1440, 8226),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 1,4,1800, 9702),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 1,5,2160, 9642),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 1,6,2520, 8662),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 1,7,2880, 9702),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 1,8,3600, 9642),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 2,0, 360, 9744),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 2,1, 720, 9744),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 2,2,1080, 9744),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 2,3,1440, 9744),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 2,4,1800, 9744),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 2,5,2160, 9744),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 2,6,2520, 9744),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 2,7,2880, 9744),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 2,8,3600, 9744),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 3,0, 360, 9746),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 3,1, 720, 9746),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 3,2,1080, 9746),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 3,3,1440, 9746),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 3,4,1800, 9746),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 3,5,2160, 9746),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 3,6,2520, 9746),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 3,7,2880, 9746),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#aaba607386910d05a3516fe956f1e70c0">RTF_ListElement</a>( 3,8,3600, 9746),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">  { 0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">    0,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">nullptr</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">};</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aaaed62b7c9e0ef2c5ba6133eba8203a1">RTFGenerator::beginRTFDocument</a> and <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac9b164379ca75fc12d225af36eac95aa">RTFDocVisitor::getListTable</a>.</p>

</div>
</div>

### rtf\_title {#a86de556a1278f74936d85c3ad6737305}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString rtf_title</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 23 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a86de556a1278f74936d85c3ad6737305">23</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a86de556a1278f74936d85c3ad6737305">rtf_title</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a>.</p>

</div>
</div>

### s\_clause {#a7ce4348d587548a514b1e698abed1a54}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const reg::Ex s_clause(R"(\\s(\d+)\s*)")</td>
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



<p>Definition at line 284 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/structs/styledata/#a7a9ef51c3d04534f0d123bc771ab3367">StyleData::setStyle</a> and <a href="/web-doxygen/docs/api/structs/styledata/#afa4e839cadb0aa89001d0a3b45845ce9">StyleData::StyleData</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### RTF\_CodeExample {#a35078b7f9f90726f496eb0c2e9dec3c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RTF_CodeExample(lvl, nest, nxt, pos)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  { "CodeExample"#lvl,                                                                       \
    "\\s"#nest"\\li"#pos"\\widctlpar\\adjustright \\shading1000\\cbpat8 \\f2\\fs16\\cgrid ", \
    "\\sbasedon0 \\snext"#nxt" Code <a href="/web-doxygen/docs/api/structs/example">Example</a> "#lvl                                            \
  }
</div>
</dd>
</dl>

<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a35078b7f9f90726f496eb0c2e9dec3c1">70</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define RTF_CodeExample(lvl,nest,nxt,pos)                                                    \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  { "CodeExample"#lvl,                                                                       \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\s"#nest"\\li"#pos"\\widctlpar\\adjustright \\shading1000\\cbpat8 \\f2\\fs16\\cgrid ", \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\sbasedon0 \\snext"#nxt" Code Example "#lvl                                            \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  }</span></span></div>

</div>

</div>
</div>

### RTF\_DescContinue {#a8cff47864029012a9b69bcd2847a5569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RTF_DescContinue(lvl, nest, nxt, pos)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  { "DescContinue"#lvl,                                                                 \
    "\\s"#nest"\\li"#pos"\\widctlpar\\ql\\adjustright \\fs20\\cgrid ",                  \
    "\\sbasedon0 \\snext"#nxt" DescContinue "#lvl                                       \
  }
</div>
</dd>
</dl>

<p>Definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8cff47864029012a9b69bcd2847a5569">82</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define RTF_DescContinue(lvl,nest,nxt,pos)                                              \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  { "DescContinue"#lvl,                                                                 \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\s"#nest"\\li"#pos"\\widctlpar\\ql\\adjustright \\fs20\\cgrid ",                  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\sbasedon0 \\snext"#nxt" DescContinue "#lvl                                       \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  }</span></span></div>

</div>

</div>
</div>

### RTF\_LatexToc {#a463599a8fbe49d5a7c3b41c2c6bf3920}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RTF_LatexToc(lvl, nest, nxt, pos, twps)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">                                                                                                            \
  { "LatexTOC"#lvl,                                                                                            \
    "\\s"#nest"\\li"#pos"\\sa"#twps"\\sb"#twps"\\widctlpar\\tqr\\tldot\\tx8640\\adjustright \\fs20\\cgrid ",\
    "\\sbasedon0 \\snext"#nxt" LatexTOC "#lvl                                                               \
  }
</div>
</dd>
</dl>

<p>Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a463599a8fbe49d5a7c3b41c2c6bf3920">51</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define RTF_LatexToc(lvl,nest,nxt,pos,twps)                                                                 \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">                                                                                                            \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  { "LatexTOC"#lvl,                                                                                            \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\s"#nest"\\li"#pos"\\sa"#twps"\\sb"#twps"\\widctlpar\\tqr\\tldot\\tx8640\\adjustright \\fs20\\cgrid ",\</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\sbasedon0 \\snext"#nxt" LatexTOC "#lvl                                                               \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  }</span></span></div>

</div>

</div>
</div>

### RTF\_ListBullet {#acf6653c078262217dfb07ef7993e2bdf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RTF_ListBullet(lvl, nest, nxt, pos, lvl2)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  { "ListBullet"#lvl,                                                \
    "\\s"#nest"\\fi-360\\li"#pos"\\widctlpar\\jclisttab\\tx"#pos"{\\*\\pn \\pnlvlbody\\ilvl0\\ls"#lvl2"\\pnrnot0\\pndec }\\ls1\\adjustright \\fs20\\cgrid ", \
    "\\sbasedon0 \\snext"#nxt" \\sautoupd <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a4ee29ca12c7d126654bd0e5275de6135">List</a> Bullet "#lvl          \
  }
</div>
</dd>
</dl>

<p>Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acf6653c078262217dfb07ef7993e2bdf">58</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define RTF_ListBullet(lvl,nest,nxt,pos,lvl2)                        \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  { "ListBullet"#lvl,                                                \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\s"#nest"\\fi-360\\li"#pos"\\widctlpar\\jclisttab\\tx"#pos"{\\*\\pn \\pnlvlbody\\ilvl0\\ls"#lvl2"\\pnrnot0\\pndec }\\ls1\\adjustright \\fs20\\cgrid ", \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\sbasedon0 \\snext"#nxt" \\sautoupd List Bullet "#lvl          \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  }</span></span></div>

</div>

</div>
</div>

### RTF\_ListContinue {#a936372eb65e3b7a2c789d6ad29fb661d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RTF_ListContinue(lvl, nest, nxt, pos)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  { "ListContinue"#lvl,                                                                 \
    "\\s"#nest"\\li"#pos"\\sa60\\sb30\\qj\\widctlpar\\qj\\adjustright \\fs20\\cgrid ",  \
    "\\sbasedon0 \\snext"#nxt" <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a4ee29ca12c7d126654bd0e5275de6135">List</a> Continue "#lvl                                      \
  }
</div>
</dd>
</dl>

<p>Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a936372eb65e3b7a2c789d6ad29fb661d">76</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define RTF_ListContinue(lvl,nest,nxt,pos)                                              \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  { "ListContinue"#lvl,                                                                 \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\s"#nest"\\li"#pos"\\sa60\\sb30\\qj\\widctlpar\\qj\\adjustright \\fs20\\cgrid ",  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\sbasedon0 \\snext"#nxt" List Continue "#lvl                                      \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  }</span></span></div>

</div>

</div>
</div>

### RTF\_ListElement {#aaba607386910d05a3516fe956f1e70c0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RTF_ListElement(id, lvl, pos, chr)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  { id, lvl,                              \
    "\\listlevel\\levelnfc23\\leveljc0\\levelstartat1\\levelfollow0{\\leveltext \\'01\\u"#chr" ?;}{\\levelnumbers;}\\f8\\dbch\\af3\\fi-360\\li"#pos, \
    "{\\*\\hyphen2\\hyphlead2\\hyphtrail2\\hyphmax0}\\nowidctlpar\\cf0\\hich\\af0\\langfe2052\\dbch\\af0\\afs24\\lang1081\\loch\\f0\\fs24\\lang1033{\\listtext\\pard\\plain \\hich\\af3\\dbch\\af3\\loch\\f8 \\'01\\u"#chr"\\tab}\\ilvl"#lvl"\\ls"#id" \\li0\\ri0\\lin0\\rin0\\fi-360\\tx"#pos"\\li"#pos"\\ri0\\lin"#pos"\\rin0\\fi-360\\kerning1\\hich\\af4\\dbch\\af5\\rtlch \\ltrch\\loch\\fs20" \
  }
</div>
</dd>
</dl>

<p>Definition at line 239 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaba607386910d05a3516fe956f1e70c0">239</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define RTF_ListElement(id,lvl,pos,chr)   \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  { id, lvl,                              \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\listlevel\\levelnfc23\\leveljc0\\levelstartat1\\levelfollow0{\\leveltext \\'01\\u"#chr" ?;}{\\levelnumbers;}\\f8\\dbch\\af3\\fi-360\\li"#pos, \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "{\\*\\hyphen2\\hyphlead2\\hyphtrail2\\hyphmax0}\\nowidctlpar\\cf0\\hich\\af0\\langfe2052\\dbch\\af0\\afs24\\lang1081\\loch\\f0\\fs24\\lang1033{\\listtext\\pard\\plain \\hich\\af3\\dbch\\af3\\loch\\f8 \\'01\\u"#chr"\\tab}\\ilvl"#lvl"\\ls"#id" \\li0\\ri0\\lin0\\rin0\\fi-360\\tx"#pos"\\li"#pos"\\ri0\\lin"#pos"\\rin0\\fi-360\\kerning1\\hich\\af4\\dbch\\af5\\rtlch \\ltrch\\loch\\fs20" \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  }</span></span></div>

</div>

</div>
</div>

### RTF\_ListEnum {#a0a0cb97c92a409dabdf406f23bd8e2d0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define RTF_ListEnum(lvl, nest, nxt, pos)&nbsp;&nbsp;&nbsp;...</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<dl class="doxySectionUser">
<dt>Value</dt>
<dd>
<div class="doxyVerbatim">  { "ListEnum"#lvl,                                          \
    "\\s"#nest"\\fi-360\\li"#pos"\\widctlpar\\fs20\\cgrid ", \
    "\\sbasedon0 \\snext"#nxt" \\sautoupd <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a4ee29ca12c7d126654bd0e5275de6135">List</a> Enum "#lvl    \
  }
</div>
</dd>
</dl>

<p>Definition at line 64 of file <a href="/web-doxygen/docs/api/files/src/rtfstyle-cpp">rtfstyle.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0a0cb97c92a409dabdf406f23bd8e2d0">64</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define RTF_ListEnum(lvl,nest,nxt,pos)                       \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  { "ListEnum"#lvl,                                          \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\s"#nest"\\fi-360\\li"#pos"\\widctlpar\\fs20\\cgrid ", \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">    "\\sbasedon0 \\snext"#nxt" \\sautoupd List Enum "#lvl    \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">  }</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
