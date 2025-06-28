---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/anchorgenerator
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `AnchorGenerator` Class Reference

<p>Singleton class used to generate anchors for <a href="/web-doxygen/docs/api/classes/markdown">Markdown</a> headers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class AnchorGenerator { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/anchor-h">src/anchor.h</a>&gt;
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a51d1a14474d1ffb69f1bea4306331310">AnchorGenerator</a> ()</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3417ff75cc68717cde6b70e06006039e">~AnchorGenerator</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a557525dbf46d474a3baea1642fe756bd">generate</a> (const std::string &amp;title)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>generates an anchor for a section with <em>title</em>. <a href="#a557525dbf46d474a3baea1642fe756bd">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a16179e60383f1fbeb2f4c4950501f6ce">isGenerated</a> (const std::string &amp;anchor) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true iff <em>anchor</em> is one of the generated anchors. <a href="#a16179e60383f1fbeb2f4c4950501f6ce">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a87ae2bfecf788b4815f1cd7fa2276436">reserve</a> (const std::string &amp;anchor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Reserves a non-generated anchor. <a href="#a87ae2bfecf788b4815f1cd7fa2276436">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/anchorgenerator/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab02a0dfd52baab313191a848b306c476">p</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/anchorgenerator">AnchorGenerator</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a282543ddcf48b1b7cf7d2921573d453d">instance</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns the singleton instance. <a href="#a282543ddcf48b1b7cf7d2921573d453d">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8d3ac23f544142e96ccf645831743432">looksGenerated</a> (const std::string &amp;anchor)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Returns true if <em>anchor</em> is a potentially generated anchor. <a href="#a8d3ac23f544142e96ccf645831743432">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a54e3a84d24e7a6e688ebd6b46a566544">addPrefixIfNeeded</a> (const std::string &amp;anchor)</td>
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

<p>Singleton class used to generate anchors for <a href="/web-doxygen/docs/api/classes/markdown">Markdown</a> headers.</p>

<p>Definition at line 25 of file <a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>.</p>

<div class="doxySectionDef">

## Private Constructors

### AnchorGenerator() {#a51d1a14474d1ffb69f1bea4306331310}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnchorGenerator::AnchorGenerator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/anchor-h/#l00050">50</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#l00034">34</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a51d1a14474d1ffb69f1bea4306331310">34</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a51d1a14474d1ffb69f1bea4306331310">AnchorGenerator::AnchorGenerator</a>() : <a href="#ab02a0dfd52baab313191a848b306c476">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/anchorgenerator/private">Private</a>&gt;()) {}</span></span></div>

</div>


Reference <a href="#ab02a0dfd52baab313191a848b306c476">p</a>.

Referenced by <a href="#a282543ddcf48b1b7cf7d2921573d453d">instance</a> and <a href="#a3417ff75cc68717cde6b70e06006039e">~AnchorGenerator</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### ~AnchorGenerator() {#a3417ff75cc68717cde6b70e06006039e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnchorGenerator::~AnchorGenerator ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/anchor-h/#l00051">51</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>.</p>

Reference <a href="#a51d1a14474d1ffb69f1bea4306331310">AnchorGenerator</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### generate() {#a557525dbf46d474a3baea1642fe756bd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string AnchorGenerator::generate (const std::string &amp; title)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>generates an anchor for a section with <em>title</em>.</p>


<p>Returns the anchor.</p>

<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/anchor-h/#l00034">34</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#l00059">59</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a557525dbf46d474a3baea1642fe756bd">59</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="#a557525dbf46d474a3baea1642fe756bd">AnchorGenerator::generate</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;label)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="#ab02a0dfd52baab313191a848b306c476">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> createDoxygenStyleAnchor = [&amp;]()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// overwrite result with the doxygen style anchor</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    result = <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>+std::to_string(<a href="#ab02a0dfd52baab313191a848b306c476">p</a>-&gt;anchorCount++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> createGitHubStyleAnchor = [&amp;]()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">    result.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pos=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (pos&lt;label.length())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">      uint8_t bytes       = <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a>(label[pos]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string charStr = <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>(label,pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">      uint32_t cUnicode   = <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a83a5739b379d70400986a723aefd42b0">getUnicodeForUTF8CharAt</a>(label,pos);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c = charStr[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>(c) || c==</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=</span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c!=</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight"> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a562d68eff947d2e12b2b56800825e552">isUTF8PunctuationCharacter</a>(cUnicode))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// skip punctuation characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// normal UTF8 character</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=<a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>(charStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      pos+=bytes;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("label='%s' result='%s'\n",qPrint(label),qPrint(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (result.empty()) </span><span class="doxyHighlightComment">// fallback use doxygen style anchor</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">      createDoxygenStyleAnchor();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">      result = <a href="#a54e3a84d24e7a6e688ebd6b46a566544">addPrefixIfNeeded</a>(result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;count = <a href="#ab02a0dfd52baab313191a848b306c476">p</a>-&gt;idCount[result];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// Add end digits if an identical header already exists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (count&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=</span><span class="doxyHighlightStringLiteral">"-"</span><span class="doxyHighlight">+std::to_string(count);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">      count++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">  };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(MARKDOWN_ID_STYLE))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> MARKDOWN_ID_STYLE_t::DOXYGEN:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">      createDoxygenStyleAnchor();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> MARKDOWN_ID_STYLE_t::GITHUB:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      createGitHubStyleAnchor();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ab02a0dfd52baab313191a848b306c476">p</a>-&gt;anchorsUsed.insert(result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="#a54e3a84d24e7a6e688ebd6b46a566544">addPrefixIfNeeded</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config&#95;getEnum</a>, <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a90000b3876f8ff0fed72d2c31ecdfe11">convertUTF8ToLower</a>, <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a83a5739b379d70400986a723aefd42b0">getUnicodeForUTF8CharAt</a>, <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#ac0c19c2bb475bc6f27dbf06345c865a3">getUTF8CharAt</a>, <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#aaca02fb609a02d6006c4ae5d02a20b9b">getUTF8CharNumBytes</a>, <a href="/web-doxygen/docs/api/files/src/utf8-cpp/#a562d68eff947d2e12b2b56800825e552">isUTF8PunctuationCharacter</a>, <a href="#ab02a0dfd52baab313191a848b306c476">p</a>, <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a77c877f20c7388af72f6a936072b5109">qisspace</a>.

Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a46231fc8d72391f38170f184dd956ed1">Markdown::Private::extractTitleId</a> and <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>.
</div>
</div>

### isGenerated() {#a16179e60383f1fbeb2f4c4950501f6ce}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AnchorGenerator::isGenerated (const std::string &amp; anchor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Returns true iff <em>anchor</em> is one of the generated anchors.</p>

<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/anchor-h/#l00037">37</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#l00128">128</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a16179e60383f1fbeb2f4c4950501f6ce">128</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a16179e60383f1fbeb2f4c4950501f6ce">AnchorGenerator::isGenerated</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;anchor)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="#ab02a0dfd52baab313191a848b306c476">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab02a0dfd52baab313191a848b306c476">p</a>-&gt;anchorsUsed.find(anchor)!=<a href="#ab02a0dfd52baab313191a848b306c476">p</a>-&gt;anchorsUsed.end();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ab02a0dfd52baab313191a848b306c476">p</a>.
</div>
</div>

### reserve() {#a87ae2bfecf788b4815f1cd7fa2276436}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int AnchorGenerator::reserve (const std::string &amp; anchor)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">
<p>Reserves a non-generated anchor.</p>

<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/anchor-h/#l00040">40</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#l00134">134</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a87ae2bfecf788b4815f1cd7fa2276436">134</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a87ae2bfecf788b4815f1cd7fa2276436">AnchorGenerator::reserve</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(<a href="#ab02a0dfd52baab313191a848b306c476">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab02a0dfd52baab313191a848b306c476">p</a>-&gt;idCount[anchor]++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ab02a0dfd52baab313191a848b306c476">p</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#ab02a0dfd52baab313191a848b306c476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; AnchorGenerator::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/anchor-h/#l00054">54</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab02a0dfd52baab313191a848b306c476">54</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#ab02a0dfd52baab313191a848b306c476">p</a>;</span></span></div>

</div>


Referenced by <a href="#a51d1a14474d1ffb69f1bea4306331310">AnchorGenerator</a>, <a href="#a557525dbf46d474a3baea1642fe756bd">generate</a>, <a href="#a16179e60383f1fbeb2f4c4950501f6ce">isGenerated</a> and <a href="#a87ae2bfecf788b4815f1cd7fa2276436">reserve</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### addPrefixIfNeeded() {#a54e3a84d24e7a6e688ebd6b46a566544}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string AnchorGenerator::addPrefixIfNeeded (const std::string &amp; anchor)</td>
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


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/anchor-h/#l00047">47</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#l00046">46</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a54e3a84d24e7a6e688ebd6b46a566544">46</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="#a54e3a84d24e7a6e688ebd6b46a566544">AnchorGenerator::addPrefixIfNeeded</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(MARKDOWN_ID_STYLE)==MARKDOWN_ID_STYLE_t::GITHUB &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">      (anchor.empty() || anchor.front() == </span><span class="doxyHighlightCharLiteral">'-'</span><span class="doxyHighlight"> || std::isdigit(anchor.front())))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>+anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">53</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">54</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config&#95;getEnum</a> and <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.

Referenced by <a href="#a557525dbf46d474a3baea1642fe756bd">generate</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>.
</div>
</div>

### instance() {#a282543ddcf48b1b7cf7d2921573d453d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">AnchorGenerator &amp; AnchorGenerator::instance ()</td>
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
<p>Returns the singleton instance.</p>

<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/anchor-h/#l00029">29</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#l00038">38</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a282543ddcf48b1b7cf7d2921573d453d">38</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a51d1a14474d1ffb69f1bea4306331310">AnchorGenerator</a> &amp;<a href="#a282543ddcf48b1b7cf7d2921573d453d">AnchorGenerator::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">39</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">40</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#a51d1a14474d1ffb69f1bea4306331310">AnchorGenerator</a> am;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">41</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> am;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">42</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#a51d1a14474d1ffb69f1bea4306331310">AnchorGenerator</a>.

Referenced by <a href="/web-doxygen/docs/api/structs/markdown/private/#a46231fc8d72391f38170f184dd956ed1">Markdown::Private::extractTitleId</a>, <a href="/web-doxygen/docs/api/classes/docroot/#a860207dd6bee34648ddbfd55e3ddaff8">DocRoot::parse</a>, <a href="/web-doxygen/docs/api/classes/docsection/#a9b6c66c2f51de17bc5748754090c1e41">DocSection::parse</a>, <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a> and <a href="/web-doxygen/docs/api/classes/definitionimpl/#afb6a683a89f794ddafb8f8fd1cb55fc9">DefinitionImpl::writeDocAnchorsToTagFile</a>.
</div>
</div>

### looksGenerated() {#a8d3ac23f544142e96ccf645831743432}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool AnchorGenerator::looksGenerated (const std::string &amp; anchor)</td>
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
<p>Returns true if <em>anchor</em> is a potentially generated anchor.</p>


<p>Note this is a much weaker check than <a href="#a16179e60383f1fbeb2f4c4950501f6ce">isGenerated()</a> and may not always work.</p>

<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/anchor-h/#l00045">45</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#l00140">140</a> of file <a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8d3ac23f544142e96ccf645831743432">140</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a8d3ac23f544142e96ccf645831743432">AnchorGenerator::looksGenerated</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;anchor)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(MARKDOWN_ID_STYLE)==MARKDOWN_ID_STYLE_t::DOXYGEN &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">         <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(anchor).<a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">startsWith</a>(</span><span class="doxyHighlightStringLiteral">"autotoc_md"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config&#95;getEnum</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a1f43c0a4958cf17f086dc0e3a4b13a68">QCString::startsWith</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a5b2c9b8ab174e898f87b90803529766c">anonymous&#95;namespace{tagreader.cpp}::TagFileParser::endDocAnchor</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/anchor-cpp">anchor.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
