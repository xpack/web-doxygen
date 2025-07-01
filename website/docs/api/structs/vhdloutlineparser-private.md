---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/structs/vhdloutlineparser/private
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - struct
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Private` Struct Reference



## Declaration

<div class="doxyDeclaration">
struct VHDLOutlineParser::Private { ... }
</div>

## Public Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a09e1a5b366fadb1761f46049e67df6c5">parseVhdlfile</a> (const QCString &amp;fileName, const QCString &amp;inputBuffer, bool inLine)</td>
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

## Public Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdloutlineparser">VHDLOutlineParser</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7709a3aa2d9e17ede59340cb8d1fd027">thisParser</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2202f9de751b3979497bcb5a8bbd826b">vhdlParser</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/commentscanner">CommentScanner</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ade21d21f2639b7b770f6f7a65ac12d9f">commentScanner</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a070b72383c499b5eb7567c2460446c4d">yyFileName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5770f6cf7636cab2f4163b7d2c8fe8c4">yyLineNr</a> = 1</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/containers-h/#a0b244579717fb04b2fb4ac89ee2f0f35">IntVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a08d3f1873df4b9f07e0081946625f67f">lineParse</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2b88a8c704057effb040662febb53a5d">iDocLine</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a81c4e8f817ecd956db9f70b0420af1fc">inputString</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/entry">Entry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9c72ac79a9c5ada2822c68dd4c91b2e">gBlock</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/entry">Entry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4506c1d22fb4537368f57ccab37a5ca4">previous</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/entry">Entry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac641d31084d1aec24c1cf3943f5d4dda">oldEntry</a> = nullptr</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a201c2f3706d9ff695fe4644665a55548">varr</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa99637f391142599e5695a656de6f283">varName</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/entry-h/#abd47085ad2ebd874e6b5d92f426e31b1">EntryList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a023cb648de43246794dac2ccd64a6984">libUse</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/entry-h/#abd47085ad2ebd874e6b5d92f426e31b1">EntryList</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aded5a24f8bf2e9a4f814ae81ad63e7e7">lineEntry</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6834e6e7bf00906b7dd3d83e28008fc7">strComment</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6c699a22b680aab6bbce6eca5f587631">iCodeLen</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/vhdldocinfo">VHDLDocInfo</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab25f91029f9ed634b655a017ea17bf5a">str_doc</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9e0800d0b8fd8902270d7b81cb8055a">shared</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a72d5bbab136180d8ba84d0df30c31b8e">forL</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a99f6729c631ea452a542a42b55a8c472">code</a> = 0</td>
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


Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxySectionDef">

## Public Member Functions

### parseVhdlfile() {#a09e1a5b366fadb1761f46049e67df6c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void VHDLOutlineParser::Private::parseVhdlfile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inputBuffer, bool inLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 59 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a09e1a5b366fadb1761f46049e67df6c5">88</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a09e1a5b366fadb1761f46049e67df6c5">VHDLOutlineParser::Private::parseVhdlfile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">                                               </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inputBuffer,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s =inputBuffer;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdl/parser/charstream">CharStream</a> *stream = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/vhdl/parser/charstream">CharStream</a>(</span><span class="doxyHighlightKeyword">reinterpret_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/files/vhdlparser/javacc-h/#ac92fa8b4f5fb2ad4efec4f05be1c911b">JJChar</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()), (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">)s.<a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">size</a>(), 1, 1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager">VhdlParserTokenManager</a> *tokenManager = </span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager">VhdlParserTokenManager</a>(stream);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdltokenmanagererrorhandler">VhdlTokenManagerErrorHandler</a> *tokErrHandler=</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdltokenmanagererrorhandler">VhdlTokenManagerErrorHandler</a>(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2202f9de751b3979497bcb5a8bbd826b">vhdlParser</a>=</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a>(tokenManager);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2202f9de751b3979497bcb5a8bbd826b">vhdlParser</a>-&gt;setOutlineParser(<a href="#a7709a3aa2d9e17ede59340cb8d1fd027">thisParser</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2202f9de751b3979497bcb5a8bbd826b">vhdlParser</a>-&gt;setSharedState(&amp;<a href="#af9e0800d0b8fd8902270d7b81cb8055a">shared</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">  tokenManager-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/tokenparser/#ac5cb74c3a7c9a7f4620c34d939da9fbc">setLexParser</a>(<a href="#a2202f9de751b3979497bcb5a8bbd826b">vhdlParser</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">  tokenManager-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager/#a117f0df3f3675897ccb4a63c63a12721">ReInit</a>(stream,0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">  tokenManager-&gt;<a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager/#af10e66a2453415cb8f5778d60d4f6dd2">setErrorHandler</a>(tokErrHandler);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler">VhdlErrorHandler</a> *parserErrHandler=</span><span class="doxyHighlightKeyword">new</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlerrorhandler">VhdlErrorHandler</a>(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a2202f9de751b3979497bcb5a8bbd826b">vhdlParser</a>-&gt;setErrorHandler(parserErrHandler);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">try</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">(inLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a2202f9de751b3979497bcb5a8bbd826b">vhdlParser</a>-&gt;parseInline();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightComment">// vhdlParser-&gt;interface_variable_declaration(); //interface_declaration() ;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a2202f9de751b3979497bcb5a8bbd826b">vhdlParser</a>-&gt;design_file();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">catch</span><span class="doxyHighlight">( std::exception &amp;){ </span><span class="doxyHighlightComment">/* fprintf(stderr,"\n[%s]",e.what()); */</span><span class="doxyHighlight"> }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//  fprintf(stderr,"\n\nparsed lines: %d\n",yyLineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//  fprintf(stderr,"\n\nerrors : %d\n\n",myErr-&gt;getErrorCount());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">delete</span><span class="doxyHighlight"> <a href="#a2202f9de751b3979497bcb5a8bbd826b">vhdlParser</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">delete</span><span class="doxyHighlight"> tokenManager;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">delete</span><span class="doxyHighlight"> stream;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager/#a117f0df3f3675897ccb4a63c63a12721">vhdl::parser::VhdlParserTokenManager::ReInit</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparsertokenmanager/#af10e66a2453415cb8f5778d60d4f6dd2">vhdl::parser::VhdlParserTokenManager::setErrorHandler</a>, <a href="/web-doxygen/docs/api/classes/vhdl/parser/tokenparser/#ac5cb74c3a7c9a7f4620c34d939da9fbc">vhdl::parser::TokenParser::setLexParser</a>, <a href="#af9e0800d0b8fd8902270d7b81cb8055a">shared</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a957be37e3b98707fc7e8daeff18e391b">QCString::size</a>, <a href="#a7709a3aa2d9e17ede59340cb8d1fd027">thisParser</a> and <a href="#a2202f9de751b3979497bcb5a8bbd826b">vhdlParser</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### code {#a99f6729c631ea452a542a42b55a8c472}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VHDLOutlineParser::Private::code = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 84 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a99f6729c631ea452a542a42b55a8c472">84</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a99f6729c631ea452a542a42b55a8c472">code</a> = 0;</span></span></div>

</div>

</div>
</div>

### commentScanner {#ade21d21f2639b7b770f6f7a65ac12d9f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CommentScanner VHDLOutlineParser::Private::commentScanner</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 63 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ade21d21f2639b7b770f6f7a65ac12d9f">63</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/commentscanner">CommentScanner</a>          <a href="#ade21d21f2639b7b770f6f7a65ac12d9f">commentScanner</a>;</span></span></div>

</div>

</div>
</div>

### forL {#a72d5bbab136180d8ba84d0df30c31b8e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VHDLOutlineParser::Private::forL</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 83 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a72d5bbab136180d8ba84d0df30c31b8e">83</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                <a href="#a72d5bbab136180d8ba84d0df30c31b8e">forL</a>;</span></span></div>

</div>

</div>
</div>

### gBlock {#ad9c72ac79a9c5ada2822c68dd4c91b2e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Entry* VHDLOutlineParser::Private::gBlock = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 70 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad9c72ac79a9c5ada2822c68dd4c91b2e">70</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/entry">Entry</a>*                  <a href="#ad9c72ac79a9c5ada2822c68dd4c91b2e">gBlock</a>        = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### iCodeLen {#a6c699a22b680aab6bbce6eca5f587631}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VHDLOutlineParser::Private::iCodeLen</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6c699a22b680aab6bbce6eca5f587631">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                     <a href="#a6c699a22b680aab6bbce6eca5f587631">iCodeLen</a>;</span></span></div>

</div>

</div>
</div>

### iDocLine {#a2b88a8c704057effb040662febb53a5d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VHDLOutlineParser::Private::iDocLine = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 68 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2b88a8c704057effb040662febb53a5d">68</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                     <a href="#a2b88a8c704057effb040662febb53a5d">iDocLine</a>      = -1;</span></span></div>

</div>

</div>
</div>

### inputString {#a81c4e8f817ecd956db9f70b0420af1fc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VHDLOutlineParser::Private::inputString</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a81c4e8f817ecd956db9f70b0420af1fc">69</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                <a href="#a81c4e8f817ecd956db9f70b0420af1fc">inputString</a>;</span></span></div>

</div>

</div>
</div>

### libUse {#a023cb648de43246794dac2ccd64a6984}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EntryList VHDLOutlineParser::Private::libUse</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 77 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a023cb648de43246794dac2ccd64a6984">77</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/entry-h/#abd47085ad2ebd874e6b5d92f426e31b1">EntryList</a>               <a href="#a023cb648de43246794dac2ccd64a6984">libUse</a>;</span></span></div>

</div>

</div>
</div>

### lineEntry {#aded5a24f8bf2e9a4f814ae81ad63e7e7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">EntryList VHDLOutlineParser::Private::lineEntry</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 78 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aded5a24f8bf2e9a4f814ae81ad63e7e7">78</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/entry-h/#abd47085ad2ebd874e6b5d92f426e31b1">EntryList</a>               <a href="#aded5a24f8bf2e9a4f814ae81ad63e7e7">lineEntry</a>;</span></span></div>

</div>

</div>
</div>

### lineParse {#a08d3f1873df4b9f07e0081946625f67f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IntVector VHDLOutlineParser::Private::lineParse</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 67 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a08d3f1873df4b9f07e0081946625f67f">67</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#a0b244579717fb04b2fb4ac89ee2f0f35">IntVector</a>               <a href="#a08d3f1873df4b9f07e0081946625f67f">lineParse</a>;</span></span></div>

</div>

</div>
</div>

### oldEntry {#ac641d31084d1aec24c1cf3943f5d4dda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Entry* VHDLOutlineParser::Private::oldEntry = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac641d31084d1aec24c1cf3943f5d4dda">74</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/entry">Entry</a>*                  <a href="#ac641d31084d1aec24c1cf3943f5d4dda">oldEntry</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### previous {#a4506c1d22fb4537368f57ccab37a5ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Entry* VHDLOutlineParser::Private::previous = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 71 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4506c1d22fb4537368f57ccab37a5ca4">71</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/entry">Entry</a>*                  <a href="#a4506c1d22fb4537368f57ccab37a5ca4">previous</a>      = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>

</div>
</div>

### shared {#af9e0800d0b8fd8902270d7b81cb8055a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlParser::SharedState VHDLOutlineParser::Private::shared</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 82 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af9e0800d0b8fd8902270d7b81cb8055a">82</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdl/parser/vhdlparser/sharedstate">VhdlParser::SharedState</a> <a href="#af9e0800d0b8fd8902270d7b81cb8055a">shared</a>;</span></span></div>

</div>


Referenced by <a href="#a09e1a5b366fadb1761f46049e67df6c5">parseVhdlfile</a>.
</div>
</div>

### str\_doc {#ab25f91029f9ed634b655a017ea17bf5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VHDLDocInfo VHDLOutlineParser::Private::str_doc</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab25f91029f9ed634b655a017ea17bf5a">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/vhdldocinfo">VHDLDocInfo</a>             <a href="#ab25f91029f9ed634b655a017ea17bf5a">str_doc</a>;</span></span></div>

</div>

</div>
</div>

### strComment {#a6834e6e7bf00906b7dd3d83e28008fc7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VHDLOutlineParser::Private::strComment</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6834e6e7bf00906b7dd3d83e28008fc7">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                <a href="#a6834e6e7bf00906b7dd3d83e28008fc7">strComment</a>;</span></span></div>

</div>

</div>
</div>

### thisParser {#a7709a3aa2d9e17ede59340cb8d1fd027}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VHDLOutlineParser* VHDLOutlineParser::Private::thisParser = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 61 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7709a3aa2d9e17ede59340cb8d1fd027">61</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#afed30c38099a7370ae59ee670b7dc5e4">VHDLOutlineParser</a>      *<a href="#a7709a3aa2d9e17ede59340cb8d1fd027">thisParser</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a09e1a5b366fadb1761f46049e67df6c5">parseVhdlfile</a>.
</div>
</div>

### varName {#aa99637f391142599e5695a656de6f283}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VHDLOutlineParser::Private::varName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 76 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa99637f391142599e5695a656de6f283">76</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                <a href="#aa99637f391142599e5695a656de6f283">varName</a>;</span></span></div>

</div>

</div>
</div>

### varr {#a201c2f3706d9ff695fe4644665a55548}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool VHDLOutlineParser::Private::varr = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a></td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 75 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a201c2f3706d9ff695fe4644665a55548">75</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">                    <a href="#a201c2f3706d9ff695fe4644665a55548">varr</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>

</div>

</div>
</div>

### vhdlParser {#a2202f9de751b3979497bcb5a8bbd826b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">VhdlParser* VHDLOutlineParser::Private::vhdlParser = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 62 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2202f9de751b3979497bcb5a8bbd826b">62</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/vhdl/parser/vhdlparser">VhdlParser</a>             *<a href="#a2202f9de751b3979497bcb5a8bbd826b">vhdlParser</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


Referenced by <a href="#a09e1a5b366fadb1761f46049e67df6c5">parseVhdlfile</a>.
</div>
</div>

### yyFileName {#a070b72383c499b5eb7567c2460446c4d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString VHDLOutlineParser::Private::yyFileName</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a070b72383c499b5eb7567c2460446c4d">65</a></span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>                <a href="#a070b72383c499b5eb7567c2460446c4d">yyFileName</a>;</span></span></div>

</div>

</div>
</div>

### yyLineNr {#a5770f6cf7636cab2f4163b7d2c8fe8c4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int VHDLOutlineParser::Private::yyLineNr = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 66 of file <a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5770f6cf7636cab2f4163b7d2c8fe8c4">66</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">                     <a href="#a5770f6cf7636cab2f4163b7d2c8fe8c4">yyLineNr</a>      = 1;</span></span></div>

</div>

</div>
</div>

</div>

<hr/>

The documentation for this struct was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/vhdljjparser-cpp">vhdljjparser.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
