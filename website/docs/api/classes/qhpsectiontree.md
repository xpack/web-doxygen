---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/qhpsectiontree
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `QhpSectionTree` Class Reference



## Declaration

<div class="doxyDeclaration">
class QhpSectionTree { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0024e8aa0d3de992e9437761b7e192fa">addSection</a> (const QCString &amp;title, const QCString &amp;ref)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7bd89954679eedf422a930584e2b1244">incLevel</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac4ac23960ed57860151b8b58177e17da">decLevel</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6e807fd7b2edf13ef2d02669c2b61569">writeToc</a> (TextStream &amp;t) const</td>
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

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9a072680707ccb788470b5463a984c38">traverse</a> (const Node &amp;root, TextStream &amp;t, int indent) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/qhpsectiontree/node">Node</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a239c13edd441b116470818051f899257">m_root</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/qhpsectiontree/node">Node</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m_current</a> = &amp;<a href="#a239c13edd441b116470818051f899257">m\_root</a></td>
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


Definition at line 45 of file <a href="/web-doxygen/docs/api/files/src/qhp-cpp">qhp.cpp</a>.

<div class="doxySectionDef">

## Public Member Functions

### addSection() {#a0024e8aa0d3de992e9437761b7e192fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void QhpSectionTree::addSection (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; ref)</td>
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



Definition at line 123 of file <a href="/web-doxygen/docs/api/files/src/qhp-cpp">qhp.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0024e8aa0d3de992e9437761b7e192fa">123</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0024e8aa0d3de992e9437761b7e192fa">addSection</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;ref)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m_current</a>-&gt;children.push_back(std::make_unique&lt;Node&gt;(<a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m_current</a>,title,ref));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m\_current</a>.
</div>
</div>

### decLevel() {#ac4ac23960ed57860151b8b58177e17da}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void QhpSectionTree::decLevel ()</td>
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



Definition at line 133 of file <a href="/web-doxygen/docs/api/files/src/qhp-cpp">qhp.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac4ac23960ed57860151b8b58177e17da">133</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac4ac23960ed57860151b8b58177e17da">decLevel</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">      assert(<a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m_current</a>-&gt;parent!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m_current</a>-&gt;parent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m_current</a> = <a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m_current</a>-&gt;parent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m\_current</a>.
</div>
</div>

### incLevel() {#a7bd89954679eedf422a930584e2b1244}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void QhpSectionTree::incLevel ()</td>
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



Definition at line 127 of file <a href="/web-doxygen/docs/api/files/src/qhp-cpp">qhp.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7bd89954679eedf422a930584e2b1244">127</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7bd89954679eedf422a930584e2b1244">incLevel</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> newNode = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/qhpsectiontree/node">Node</a>(<a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m_current</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m_current</a>-&gt;children.push_back(std::unique_ptr&lt;Node&gt;(newNode));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m_current</a> = newNode;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m\_current</a>.
</div>
</div>

### writeToc() {#a6e807fd7b2edf13ef2d02669c2b61569}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void QhpSectionTree::writeToc (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t)</td>
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



Definition at line 141 of file <a href="/web-doxygen/docs/api/files/src/qhp-cpp">qhp.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6e807fd7b2edf13ef2d02669c2b61569">141</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6e807fd7b2edf13ef2d02669c2b61569">writeToc</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#aded82e3cc34ae902387a6b62a97616b7">writeIndent</a>(t,2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;toc&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9a072680707ccb788470b5463a984c38">traverse</a>(<a href="#a239c13edd441b116470818051f899257">m_root</a>,t,3);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#aded82e3cc34ae902387a6b62a97616b7">writeIndent</a>(t,2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/toc&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a239c13edd441b116470818051f899257">m\_root</a>, <a href="#a9a072680707ccb788470b5463a984c38">traverse</a> and <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#aded82e3cc34ae902387a6b62a97616b7">writeIndent</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### traverse() {#a9a072680707ccb788470b5463a984c38}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void QhpSectionTree::traverse (const <a href="/web-doxygen/docs/api/structs/qhpsectiontree/node">Node</a> &amp; root, <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, int indent)</td>
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



Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/qhp-cpp">qhp.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9a072680707ccb788470b5463a984c38">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9a072680707ccb788470b5463a984c38">traverse</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/qhpsectiontree/node">Node</a> &amp;root,<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indent)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">/* Input:          Output:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * =================================================</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * Section1        &lt;section title=".." ref=".."&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * Dir1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlightComment">       *   Section2         &lt;section title=".." ref=".."&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlightComment">       *   Dir2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlightComment">       *     Section3          &lt;section title=".." ref=".."/&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlightComment">       *                    &lt;/section&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlightComment">       *                 &lt;/section&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * Section4        &lt;section title=".." ref="..&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * Dir3</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlightComment">       *   Dir4</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlightComment">       *     Section5       &lt;section title=.." ref=.."/&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlightComment">       *                 &lt;/section&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlightComment">       * Section6        &lt;section title=".." ref=".."/&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlightComment">       */</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> numChildren = root.<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#a1541f06740584f5b34a4c2c90e65d757">children</a>.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;numChildren)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (root.<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#a1541f06740584f5b34a4c2c90e65d757">children</a>[i]-&gt;type==<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#aa19c2c4bb91af14d01fabd837474f295ad2c24d59e0baff4d0155fbdf62590867">Node::Type::Section</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">          i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;numChildren &amp;&amp; root.<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#a1541f06740584f5b34a4c2c90e65d757">children</a>[i]-&gt;type==<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#aa19c2c4bb91af14d01fabd837474f295a3c4e6dbf3e1df93a734d9959bac9ee94">Node::Type::Dir</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightComment">// we have a dir node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#aded82e3cc34ae902387a6b62a97616b7">writeIndent</a>(t,indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;section title=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(root.<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#a1541f06740584f5b34a4c2c90e65d757">children</a>[i-1]-&gt;title) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">              &lt;&lt;         </span><span class="doxyHighlightStringLiteral">" ref=\""</span><span class="doxyHighlight">   &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(root.<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#a1541f06740584f5b34a4c2c90e65d757">children</a>[i-1]-&gt;ref)   &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;numChildren &amp;&amp; root.<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#a1541f06740584f5b34a4c2c90e65d757">children</a>[i]-&gt;type==<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#aa19c2c4bb91af14d01fabd837474f295a3c4e6dbf3e1df93a734d9959bac9ee94">Node::Type::Dir</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">            {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">              <a href="#a9a072680707ccb788470b5463a984c38">traverse</a>(*root.<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#a1541f06740584f5b34a4c2c90e65d757">children</a>[i].get(),t,indent+1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">              i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">            }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#aded82e3cc34ae902387a6b62a97616b7">writeIndent</a>(t,indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/section&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// we have a leaf section node</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#aded82e3cc34ae902387a6b62a97616b7">writeIndent</a>(t,indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">            t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;section title=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(root.<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#a1541f06740584f5b34a4c2c90e65d757">children</a>[i-1]-&gt;title) &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">              &lt;&lt;           </span><span class="doxyHighlightStringLiteral">" ref=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>(root.<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#a1541f06740584f5b34a4c2c90e65d757">children</a>[i-1]-&gt;ref)   &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// dir without preceding section (no extra indent)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#a9a072680707ccb788470b5463a984c38">traverse</a>(*root.<a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#a1541f06740584f5b34a4c2c90e65d757">children</a>[i].get(),t,indent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">          i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#a1541f06740584f5b34a4c2c90e65d757">QhpSectionTree::Node::children</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a93c7f78ab05807663dd8947d0dd5423f">convertToXML</a>, <a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#aa19c2c4bb91af14d01fabd837474f295a3c4e6dbf3e1df93a734d9959bac9ee94">QhpSectionTree::Node::Dir</a>, <a href="/web-doxygen/docs/api/structs/qhpsectiontree/node/#aa19c2c4bb91af14d01fabd837474f295ad2c24d59e0baff4d0155fbdf62590867">QhpSectionTree::Node::Section</a>, <a href="#a9a072680707ccb788470b5463a984c38">traverse</a> and <a href="/web-doxygen/docs/api/files/src/qhp-cpp/#aded82e3cc34ae902387a6b62a97616b7">writeIndent</a>.

Referenced by <a href="#a9a072680707ccb788470b5463a984c38">traverse</a> and <a href="#a6e807fd7b2edf13ef2d02669c2b61569">writeToc</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_current {#aaa1d4a6c4b74924ce2a000762d3ea7e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node* QhpSectionTree::m_current = &amp;<a href="#a239c13edd441b116470818051f899257">m\_root</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/qhp-cpp">qhp.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/qhpsectiontree/node">Node</a> *<a href="#aaa1d4a6c4b74924ce2a000762d3ea7e7">m_current</a> = &amp;<a href="#a239c13edd441b116470818051f899257">m_root</a>;</span></span></div>

</div>


Referenced by <a href="#a0024e8aa0d3de992e9437761b7e192fa">addSection</a>, <a href="#ac4ac23960ed57860151b8b58177e17da">decLevel</a> and <a href="#a7bd89954679eedf422a930584e2b1244">incLevel</a>.
</div>
</div>

### m\_root {#a239c13edd441b116470818051f899257}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Node QhpSectionTree::m_root</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/qhp-cpp">qhp.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a239c13edd441b116470818051f899257">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/qhpsectiontree/node">Node</a> <a href="#a239c13edd441b116470818051f899257">m_root</a>;</span></span></div>

</div>


Referenced by <a href="#a6e807fd7b2edf13ef2d02669c2b61569">writeToc</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/qhp-cpp">qhp.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
