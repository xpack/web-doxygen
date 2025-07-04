---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/statistics
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `Statistics` Class Reference



## Declaration

<div class="doxyDeclaration">
class Statistics { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60ddd90a571ed4c3ce8c0f6317a36d63">Statistics</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a98a419d6e4e62c2bccac88b27a9769ca">begin</a> (const char *name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa3c0ae123d9f74e170ba1bab16dd8575">end</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a681d86ad7e9121de36d517420e135415">print</a> ()</td>
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

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/structs/statistics/stat">stat</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a382e875ed47f4b11feaa8d8b7986810d">stats</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::chrono::steady_clock::time_point</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab0f66662f4036c7593d4f908cb1dfa40">startTime</a></td>
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


<p>Definition at line 228 of file <a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Statistics() {#a60ddd90a571ed4c3ce8c0f6317a36d63}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Statistics::Statistics ()</td>
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



<p>Definition at line 231 of file <a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60ddd90a571ed4c3ce8c0f6317a36d63">231</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a60ddd90a571ed4c3ce8c0f6317a36d63">Statistics</a>() {}</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### begin() {#a98a419d6e4e62c2bccac88b27a9769ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Statistics::begin (const char * name)</td>
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



<p>Definition at line 232 of file <a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a98a419d6e4e62c2bccac88b27a9769ca">232</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a98a419d6e4e62c2bccac88b27a9769ca">begin</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"{}"</span><span class="doxyHighlight">, name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a382e875ed47f4b11feaa8d8b7986810d">stats</a>.emplace_back(name,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab0f66662f4036c7593d4f908cb1dfa40">startTime</a> = std::chrono::steady_clock::now();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="#ab0f66662f4036c7593d4f908cb1dfa40">startTime</a> and <a href="#a382e875ed47f4b11feaa8d8b7986810d">stats</a>.</p>

</div>
</div>

### end() {#aa3c0ae123d9f74e170ba1bab16dd8575}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Statistics::end ()</td>
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



<p>Definition at line 238 of file <a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa3c0ae123d9f74e170ba1bab16dd8575">238</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aa3c0ae123d9f74e170ba1bab16dd8575">end</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">      std::chrono::steady_clock::time_point endTime = std::chrono::steady_clock::now();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a382e875ed47f4b11feaa8d8b7986810d">stats</a>.back().elapsed = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(std::chrono::duration_cast&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">                                std::chrono::microseconds&gt;(endTime - <a href="#ab0f66662f4036c7593d4f908cb1dfa40">startTime</a>).count())/1000000.0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-cpp/#aad9799c2a434877f36bc92beb8966567">warn_flush</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ab0f66662f4036c7593d4f908cb1dfa40">startTime</a>, <a href="#a382e875ed47f4b11feaa8d8b7986810d">stats</a> and <a href="/web-doxygen/docs/api/files/src/message-cpp/#aad9799c2a434877f36bc92beb8966567">warn_flush</a>.</p>

</div>
</div>

### print() {#a681d86ad7e9121de36d517420e135415}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Statistics::print ()</td>
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



<p>Definition at line 245 of file <a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a681d86ad7e9121de36d517420e135415">245</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a681d86ad7e9121de36d517420e135415">print</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> restore=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da9cbd5d3516ffd3fe86238779edb2f7c5">Debug::Time</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/debug/#a8b6226d91e39828116b504b94e22b26b">Debug::clearFlag</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da9cbd5d3516ffd3fe86238779edb2f7c5">Debug::Time</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">        restore=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"----------------------\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;s : <a href="#a382e875ed47f4b11feaa8d8b7986810d">stats</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Spent {:.6f} seconds in {}"</span><span class="doxyHighlight">,s.elapsed,s.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (restore) <a href="/web-doxygen/docs/api/classes/debug/#affb7c17adbcafb5ec252e95c70f12f53">Debug::setFlag</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da9cbd5d3516ffd3fe86238779edb2f7c5">Debug::Time</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/debug/#a8b6226d91e39828116b504b94e22b26b">Debug::clearFlag</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/classes/debug/#affb7c17adbcafb5ec252e95c70f12f53">Debug::setFlag</a>, <a href="#a382e875ed47f4b11feaa8d8b7986810d">stats</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da9cbd5d3516ffd3fe86238779edb2f7c5">Debug::Time</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### startTime {#ab0f66662f4036c7593d4f908cb1dfa40}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::chrono::steady_clock::time_point Statistics::startTime</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 269 of file <a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab0f66662f4036c7593d4f908cb1dfa40">269</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::chrono::steady_clock::time_point <a href="#ab0f66662f4036c7593d4f908cb1dfa40">startTime</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a98a419d6e4e62c2bccac88b27a9769ca">begin</a> and <a href="#aa3c0ae123d9f74e170ba1bab16dd8575">end</a>.</p>

</div>
</div>

### stats {#a382e875ed47f4b11feaa8d8b7986810d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;stat&gt; Statistics::stats</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 268 of file <a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a382e875ed47f4b11feaa8d8b7986810d">268</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;stat&gt; <a href="#a382e875ed47f4b11feaa8d8b7986810d">stats</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a98a419d6e4e62c2bccac88b27a9769ca">begin</a>, <a href="#aa3c0ae123d9f74e170ba1bab16dd8575">end</a> and <a href="#a681d86ad7e9121de36d517420e135415">print</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/doxygen-cpp">doxygen.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
