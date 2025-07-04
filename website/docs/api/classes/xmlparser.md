---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/xmlparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `XMLParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class XMLParser { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/libxml/xml-h">libxml/xml.h</a>&gt;
</div>

## Base class

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/xmllocator">XMLLocator</a></td>
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

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2ddf61bb8a1cf64f816de4399538c94c">Transcode</a> = bool(std::string &amp;, const char *)</td>
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

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9856a2a00cc80bea9de207cb444111f9">XMLParser</a> (const XMLHandlers &amp;handlers)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac607d8b81aac2bce2256e5ec90207368">XMLParser</a> (const XMLParser &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a91b31f9c9e974dfe2dcf4bff278c5394">XMLParser</a> (XMLParser &amp;&amp;)=delete</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af78ce69588b5f76f2e8d63730002876b">~XMLParser</a> () override</td>
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

## Public Operators Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/xmlparser">XMLParser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a618752ff31a52f1d15eff066f1388bf0">operator=</a> (const XMLParser &amp;)=delete</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/xmlparser">XMLParser</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0a662c231c3306603f57ce4fb931c05f">operator=</a> (XMLParser &amp;&amp;)=delete</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad9b0a380760223431fbb84d35a8f12e9">parse</a> (const char *fileName, const char *inputString, bool debugEnabled, std::function&lt; void()&gt; debugStart, std::function&lt; void()&gt; debugEnd, std::function&lt; Transcode &gt; transcoder=[](std::string &amp;s, const char *){ return true;})</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a177a167c4699833eba81b62fe941da5a">lineNr</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a61a320231529e8d2f16bd57f3a9493dd">fileName</a> () const override</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/xmlparser/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a></td>
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



<p>Very basic SAX style parser to parse XML documents.</p>


<p>Definition at line 70 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Transcode {#a2ddf61bb8a1cf64f816de4399538c94c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using XMLParser::Transcode =  bool(std::string &amp;,const char *)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 86 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2ddf61bb8a1cf64f816de4399538c94c">86</a></span><span class="doxyLineContent"><span class="doxyHighlight">   </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a2ddf61bb8a1cf64f816de4399538c94c">Transcode</a> = bool(std::string &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *);</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Constructors

### XMLParser() {#a9856a2a00cc80bea9de207cb444111f9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XMLParser::XMLParser (const <a href="/web-doxygen/docs/api/classes/xmlhandlers">XMLHandlers</a> &amp; handlers)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Creates an instance of the parser object. Different instances can run on different threads without interference.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">handlers</td>
<td class="doxyParamItemDescription"><p>The event handlers passed by the client.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 78 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>, definition at line 436 of file <a href="/web-doxygen/docs/api/files/libxml/xml-l">xml.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9856a2a00cc80bea9de207cb444111f9">436</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a9856a2a00cc80bea9de207cb444111f9">XMLParser::XMLParser</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers">XMLHandlers</a> &amp;handlers) : <a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>(new <a href="/web-doxygen/docs/api/structs/xmlparser/private">Private</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">  xmlYYlex_init_extra(&amp;<a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>-&gt;xmlYY_extra,&amp;<a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>-&gt;xmlYY_extra.handlers = handlers;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>.</p>


<p>Referenced by <a href="#a618752ff31a52f1d15eff066f1388bf0">operator=</a>, <a href="#a0a662c231c3306603f57ce4fb931c05f">operator=</a>, <a href="#ac607d8b81aac2bce2256e5ec90207368">XMLParser</a> and <a href="#a91b31f9c9e974dfe2dcf4bff278c5394">XMLParser</a>.</p>

</div>
</div>

### XMLParser() {#ac607d8b81aac2bce2256e5ec90207368}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XMLParser::XMLParser (const <a href="/web-doxygen/docs/api/classes/xmlparser">XMLParser</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<p>Reference <a href="#a9856a2a00cc80bea9de207cb444111f9">XMLParser</a>.</p>

</div>
</div>

### XMLParser() {#a91b31f9c9e974dfe2dcf4bff278c5394}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XMLParser::XMLParser (<a href="/web-doxygen/docs/api/classes/xmlparser">XMLParser</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 83 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<p>Reference <a href="#a9856a2a00cc80bea9de207cb444111f9">XMLParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~XMLParser() {#af78ce69588b5f76f2e8d63730002876b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XMLParser::~XMLParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Destructor</p>


<p>Declaration at line 80 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>, definition at line 442 of file <a href="/web-doxygen/docs/api/files/libxml/xml-l">xml.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af78ce69588b5f76f2e8d63730002876b">442</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#af78ce69588b5f76f2e8d63730002876b">XMLParser::~XMLParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">  xmlYYlex_destroy(<a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Operators

### operator=() {#a618752ff31a52f1d15eff066f1388bf0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XMLParser &amp; XMLParser::operator= (const <a href="/web-doxygen/docs/api/classes/xmlparser">XMLParser</a> &amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 82 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<p>Reference <a href="#a9856a2a00cc80bea9de207cb444111f9">XMLParser</a>.</p>

</div>
</div>

### operator=() {#a0a662c231c3306603f57ce4fb931c05f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">XMLParser &amp; XMLParser::operator= (<a href="/web-doxygen/docs/api/classes/xmlparser">XMLParser</a> &amp;&amp;)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel delete">delete</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 84 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<p>Reference <a href="#a9856a2a00cc80bea9de207cb444111f9">XMLParser</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parse() {#ad9b0a380760223431fbb84d35a8f12e9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void XMLParser::parse (const char * fileName, const char * inputString, bool debugEnabled, std::function&lt; void()&gt; debugStart, std::function&lt; void()&gt; debugEnd, std::function&lt; <a href="#a2ddf61bb8a1cf64f816de4399538c94c">Transcode</a> &gt; transcoder=[](std::string &amp;s, const char *){ return true;})</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Parses a file gives the contents of the file as a string.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">fileName</td>
<td class="doxyParamItemDescription"><p>the name of the file, used for error reporting.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">inputString</td>
<td class="doxyParamItemDescription"><p>the contents of the file as a zero terminated UTF-8 string.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">debugEnabled</td>
<td class="doxyParamItemDescription"><p>indicates if debugging via -d lex is enabled or not.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">debugStart</td>
<td class="doxyParamItemDescription"><p>hook that is to be called before starting with parsing</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">debugEnd</td>
<td class="doxyParamItemDescription"><p>hook that is to be called after finishing with parsing</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">transcoder</td>
<td class="doxyParamItemDescription"><p>hook that is to be called when transcoding text to UTF-8</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 96 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>, definition at line 447 of file <a href="/web-doxygen/docs/api/files/libxml/xml-l">xml.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad9b0a380760223431fbb84d35a8f12e9">447</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ad9b0a380760223431fbb84d35a8f12e9">XMLParser::parse</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a61a320231529e8d2f16bd57f3a9493dd">fileName</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *inputStr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> debugEnabled,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">                      std::function&lt;</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">()&gt; debugStart,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">                      std::function&lt;</span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight">()&gt; debugEnd,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">                      std::function&lt;Transcode&gt; <a href="/web-doxygen/docs/api/structs/xmlyy-state/#ae91a738255618a3ddad96477a363f0be">transcodeFunc</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner = <a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">  xmlYYset_debug(debugEnabled?1:0,<a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>-&gt;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inputStr==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight"> || inputStr[0]==</span><span class="doxyHighlightCharLiteral">'\0'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// empty input</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">  debugStart();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN(Initial);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;fileName      = <a href="#a61a320231529e8d2f16bd57f3a9493dd">fileName</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;lineNr        = 1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputString   = inputStr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;inputPosition = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">  yyextra-&gt;transcodeFunc = transcodeFunc;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(inputStr[0])==0xEF &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(inputStr[1])==0xBB &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">unsigned</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(inputStr[2])==0xBF)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;inputPosition = 3; </span><span class="doxyHighlightComment">// remove UTF-8 BOM</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">  xmlYYrestart( 0, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;handlers.startDocument)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;handlers.startDocument();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">  xmlYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;handlers.endDocument)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;handlers.endDocument();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!yyextra-&gt;xpath.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string tagName = yyextra-&gt;xpath.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a> = </span><span class="doxyHighlightStringLiteral">"End of file reached while expecting closing tag '"</span><span class="doxyHighlight">+tagName+</span><span class="doxyHighlightStringLiteral">"'"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/libxml/xml-l/#a6207ba2d15395f88f479b1b8a61ee94c">reportError</a>(yyscanner,<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">  debugEnd();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a61a320231529e8d2f16bd57f3a9493dd">fileName</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a> and <a href="/web-doxygen/docs/api/files/libxml/xml-l/#a6207ba2d15395f88f479b1b8a61ee94c">reportError</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### fileName() {#a61a320231529e8d2f16bd57f3a9493dd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string XMLParser::fileName ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 107 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>, definition at line 507 of file <a href="/web-doxygen/docs/api/files/libxml/xml-l">xml.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a61a320231529e8d2f16bd57f3a9493dd">507</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="#a61a320231529e8d2f16bd57f3a9493dd">XMLParser::fileName</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> yyextra-&gt;fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>.</p>


<p>Referenced by <a href="#ad9b0a380760223431fbb84d35a8f12e9">parse</a>.</p>

</div>
</div>

### lineNr() {#a177a167c4699833eba81b62fe941da5a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int XMLParser::lineNr ()</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel virtual">virtual</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 106 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>, definition at line 501 of file <a href="/web-doxygen/docs/api/files/libxml/xml-l">xml.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a177a167c4699833eba81b62fe941da5a">501</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a177a167c4699833eba81b62fe941da5a">XMLParser::lineNr</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)<a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>-&gt;yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> yyextra-&gt;lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#a38ae48d06930f9672f64cbf1adb9a242}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; XMLParser::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 109 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a38ae48d06930f9672f64cbf1adb9a242">109</a></span><span class="doxyLineContent"><span class="doxyHighlight">   std::unique_ptr&lt;Private&gt; <a href="#a38ae48d06930f9672f64cbf1adb9a242">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a61a320231529e8d2f16bd57f3a9493dd">fileName</a>, <a href="#a177a167c4699833eba81b62fe941da5a">lineNr</a>, <a href="#ad9b0a380760223431fbb84d35a8f12e9">parse</a>, <a href="#a9856a2a00cc80bea9de207cb444111f9">XMLParser</a> and <a href="#af78ce69588b5f76f2e8d63730002876b">~XMLParser</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a></li>
<li><a href="/web-doxygen/docs/api/files/libxml/xml-l">xml.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
