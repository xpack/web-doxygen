---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/rtfgen-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `rtfgen.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;array&gt;
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/rtfcodegenerator">RTFCodeGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for RTF code fragments. <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/rtfgenerator">RTFGenerator</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Generator for RTF output. <a href="/web-doxygen/docs/api/classes/rtfgenerator/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/rtfgenerator/rtflistiteminfo">RTFListItemInfo</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a> (const QCString &amp;name)</td>
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

### rtfFormatBmkStr() {#a0de8a7e9fdf9ae4c06959f6bc834b12c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString rtfFormatBmkStr (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line 349 of file <a href="/web-doxygen/docs/api/files/src/rtfgen-h">rtfgen.h</a>, definition at line 2870 of file <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp">rtfgen.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">2870</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a0de8a7e9fdf9ae4c06959f6bc834b12c">rtfFormatBmkStr</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/structs/rtf-style-default/#a6e3e9ffcccb14d865f1615b58b9e63a0">name</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2871</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2872</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a1c10ae83cddf03b9a2198b25d7b0421d">g_rtfFormatMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2873</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2874</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// To overcome the 40-character tag limitation, we</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2875</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// substitute a short arbitrary string for the name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2876</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// supplied, and keep track of the correspondence</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2877</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// between names and strings.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2878</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#aaa1996c51dca055b59204961ffaa07ad">g_tagMap</a>.find(<a href="/web-doxygen/docs/api/structs/rtf-style-default/#a6e3e9ffcccb14d865f1615b58b9e63a0">name</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2879</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#aaa1996c51dca055b59204961ffaa07ad">g_tagMap</a>.end()) </span><span class="doxyHighlightComment">// already known</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2880</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2881</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(it-&gt;second);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2882</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2883</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2884</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> tag = <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a7cd668f8677c840778f623ea4b67f531">g_nextTag</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2885</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> result = <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#aaa1996c51dca055b59204961ffaa07ad">g_tagMap</a>.emplace(<a href="/web-doxygen/docs/api/structs/rtf-style-default/#a6e3e9ffcccb14d865f1615b58b9e63a0">name</a>.str(), <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a7cd668f8677c840778f623ea4b67f531">g_nextTag</a>.str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2886</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2887</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result.second) </span><span class="doxyHighlightComment">// new item was added</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2888</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2889</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// increment the next tag.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2890</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2891</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight">* nxtTag = <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a7cd668f8677c840778f623ea4b67f531">g_nextTag</a>.rawData() + <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a7cd668f8677c840778f623ea4b67f531">g_nextTag</a>.length() - 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2892</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> ( </span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i = 0; i &lt; <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a7cd668f8677c840778f623ea4b67f531">g_nextTag</a>.length(); ++i, --nxtTag )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2893</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2894</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( ( ++(*nxtTag) ) &gt; </span><span class="doxyHighlightCharLiteral">'Z'</span><span class="doxyHighlight"> )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2895</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2896</span><span class="doxyLineContent"><span class="doxyHighlight">        *nxtTag = </span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2897</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2898</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2899</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2900</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// Since there was no carry, we can stop now</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2901</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2902</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2903</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2904</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2905</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2906</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da19caf08ac865a4bd2241cbdf9d310ecc">Debug::Rtf</a>,0,</span><span class="doxyHighlightStringLiteral">"Name = {} RTF_tag = {}\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/structs/rtf-style-default/#a6e3e9ffcccb14d865f1615b58b9e63a0">name</a>,tag);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2907</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> tag;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2908</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a7cd668f8677c840778f623ea4b67f531">g&#95;nextTag</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a1c10ae83cddf03b9a2198b25d7b0421d">g&#95;rtfFormatMutex</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#aaa1996c51dca055b59204961ffaa07ad">g&#95;tagMap</a>, <a href="/web-doxygen/docs/api/structs/rtf-style-default/#a6e3e9ffcccb14d865f1615b58b9e63a0">Rtf&#95;Style&#95;Default::name</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a> and <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da19caf08ac865a4bd2241cbdf9d310ecc">Debug::Rtf</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a69e6795499d9f7fb8867f5496c590e26">RTFGenerator::endDoxyAnchor</a>, <a href="/web-doxygen/docs/api/files/src/rtfgen-cpp/#a02024f4f45b1070b31d529c2f1307533">objectLinkToString</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a2993bfecac33a60da6408f79586b7da2">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#af199af5695c344c4730378ecfce43079">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a3c72fc623be48174c003bb47c523d6c1">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a89b1ef4b308483fcf725cef8081e5849">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a7f10a43fc0a35475e9078305d745951f">RTFDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a02328f0a76dfca6a9e0d24167905289e">RTFDocVisitor::startLink</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a46e5dfbc859151dfe39ea12ec75a5c13">RTFGenerator::startTextLink</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#aa7ae50a52d4e01f107667b89ead7b3a3">RTFGenerator::writeAnchor</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#a2d50b342c2ca0801234fb76838f7e880">RTFCodeGenerator::writeCodeLink</a>, <a href="/web-doxygen/docs/api/classes/rtfcodegenerator/#ad7fd3e3cc19d62798aa65d318a42e47c">RTFCodeGenerator::writeLineNumber</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a83b81c6e8ba89a61601bef74e92dd594">RTFGenerator::writeRTFReference</a> and <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a06cb016c789f240eabead87f1a10325a">RTFGenerator::writeStartAnnoItem</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
