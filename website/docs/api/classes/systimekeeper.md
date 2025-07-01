---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/systimekeeper
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `SysTimeKeeper` Class Reference



## Declaration

<div class="doxyDeclaration">
class SysTimeKeeper { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bb2350f48a1ce554f4499edbd8ba8ec">start</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
start a timer for this thread <a href="#a4bb2350f48a1ce554f4499edbd8ba8ec">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46b40aa916ae6873c566c85a88dd9f96">stop</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
ends a timer for this thread, accumulate time difference since start <a href="#a46b40aa916ae6873c566c85a88dd9f96">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4f6d6e92f23a8bc80ef6ec257295f101">elapsedTime</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::thread::id, std::chrono::steady_clock::time_point &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af55dfdf43ee3d196a303b500268e95b8">m_startTimes</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">double</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2320903615e5e7d57ed7c3113135c8ed">m_elapsedTime</a> = 0</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0b589e0d9fba742f915ff3b6a6f76d57">m_mutex</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/systimekeeper">SysTimeKeeper</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab2bf7ce3a2c5b37234e10ea15d667779">instance</a> ()</td>
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



Helper class to keep time interval per thread

Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a>.

<div class="doxySectionDef">

## Public Member Functions

### elapsedTime() {#a4f6d6e92f23a8bc80ef6ec257295f101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double SysTimeKeeper::elapsedTime ()</td>
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



Definition at line 73 of file <a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4f6d6e92f23a8bc80ef6ec257295f101">73</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> <a href="#a4f6d6e92f23a8bc80ef6ec257295f101">elapsedTime</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a2320903615e5e7d57ed7c3113135c8ed">m_elapsedTime</a>; }</span></span></div>

</div>


Reference <a href="#a2320903615e5e7d57ed7c3113135c8ed">m\_elapsedTime</a>.

Referenced by <a href="/web-doxygen/docs/api/namespaces/portable/#a248b5a87e07edc01e5ae424b6597142f">Portable::getSysElapsedTime</a>.
</div>
</div>

### start() {#a4bb2350f48a1ce554f4499edbd8ba8ec}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SysTimeKeeper::start ()</td>
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

start a timer for this thread

Definition at line 51 of file <a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4bb2350f48a1ce554f4499edbd8ba8ec">51</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4bb2350f48a1ce554f4499edbd8ba8ec">start</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">      std::lock_guard&lt;std::mutex&gt; lock(<a href="#a0b589e0d9fba742f915ff3b6a6f76d57">m_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#af55dfdf43ee3d196a303b500268e95b8">m_startTimes</a>[std::this_thread::get_id()] = std::chrono::steady_clock::now();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a0b589e0d9fba742f915ff3b6a6f76d57">m\_mutex</a> and <a href="#af55dfdf43ee3d196a303b500268e95b8">m\_startTimes</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/autotimekeeper/#a2e0744b11f3cd97a1429bda7c614d9aa">AutoTimeKeeper::AutoTimeKeeper</a>.
</div>
</div>

### stop() {#a46b40aa916ae6873c566c85a88dd9f96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SysTimeKeeper::stop ()</td>
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

ends a timer for this thread, accumulate time difference since start

Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a46b40aa916ae6873c566c85a88dd9f96">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a46b40aa916ae6873c566c85a88dd9f96">stop</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">      std::lock_guard&lt;std::mutex&gt; lock(<a href="#a0b589e0d9fba742f915ff3b6a6f76d57">m_mutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">      std::chrono::steady_clock::time_point endTime = std::chrono::steady_clock::now();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#af55dfdf43ee3d196a303b500268e95b8">m_startTimes</a>.find(std::this_thread::get_id());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it == <a href="#af55dfdf43ee3d196a303b500268e95b8">m_startTimes</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"SysTimeKeeper stop() called without matching start()\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> timeSpent = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(std::chrono::duration_cast&lt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">                         std::chrono::microseconds&gt;(endTime - it-&gt;second).count())/1000000.0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("timeSpent on thread %zu: %.4f seconds\n",std::hash&lt;std::thread::id&gt;{}(std::this_thread::get_id()),timeSpent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a2320903615e5e7d57ed7c3113135c8ed">m_elapsedTime</a> += timeSpent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="#a2320903615e5e7d57ed7c3113135c8ed">m\_elapsedTime</a>, <a href="#a0b589e0d9fba742f915ff3b6a6f76d57">m\_mutex</a> and <a href="#af55dfdf43ee3d196a303b500268e95b8">m\_startTimes</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/autotimekeeper/#a27439f74d48591cc5813ad2bb06915ff">AutoTimeKeeper::\~AutoTimeKeeper</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_elapsedTime {#a2320903615e5e7d57ed7c3113135c8ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">double SysTimeKeeper::m_elapsedTime = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2320903615e5e7d57ed7c3113135c8ed">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">double</span><span class="doxyHighlight"> <a href="#a2320903615e5e7d57ed7c3113135c8ed">m_elapsedTime</a> = 0;</span></span></div>

</div>


Referenced by <a href="#a4f6d6e92f23a8bc80ef6ec257295f101">elapsedTime</a> and <a href="#a46b40aa916ae6873c566c85a88dd9f96">stop</a>.
</div>
</div>

### m\_mutex {#a0b589e0d9fba742f915ff3b6a6f76d57}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex SysTimeKeeper::m_mutex</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0b589e0d9fba742f915ff3b6a6f76d57">82</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::mutex <a href="#a0b589e0d9fba742f915ff3b6a6f76d57">m_mutex</a>;</span></span></div>

</div>


Referenced by <a href="#a4bb2350f48a1ce554f4499edbd8ba8ec">start</a> and <a href="#a46b40aa916ae6873c566c85a88dd9f96">stop</a>.
</div>
</div>

### m\_startTimes {#af55dfdf43ee3d196a303b500268e95b8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::thread::id,std::chrono::steady_clock::time_point&gt; SysTimeKeeper::m_startTimes</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af55dfdf43ee3d196a303b500268e95b8">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::map&lt;std::thread::id,std::chrono::steady_clock::time_point&gt; <a href="#af55dfdf43ee3d196a303b500268e95b8">m_startTimes</a>;</span></span></div>

</div>


Referenced by <a href="#a4bb2350f48a1ce554f4499edbd8ba8ec">start</a> and <a href="#a46b40aa916ae6873c566c85a88dd9f96">stop</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#ab2bf7ce3a2c5b37234e10ea15d667779}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SysTimeKeeper &amp; SysTimeKeeper::instance ()</td>
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



Definition at line 49 of file <a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab2bf7ce3a2c5b37234e10ea15d667779">85</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/systimekeeper">SysTimeKeeper</a> &amp;<a href="#ab2bf7ce3a2c5b37234e10ea15d667779">SysTimeKeeper::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/systimekeeper">SysTimeKeeper</a> theInstance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> theInstance;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/autotimekeeper/#a2e0744b11f3cd97a1429bda7c614d9aa">AutoTimeKeeper::AutoTimeKeeper</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a248b5a87e07edc01e5ae424b6597142f">Portable::getSysElapsedTime</a> and <a href="/web-doxygen/docs/api/classes/autotimekeeper/#a27439f74d48591cc5813ad2bb06915ff">AutoTimeKeeper::\~AutoTimeKeeper</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/portable-cpp">portable.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
