---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/xmlhandlers
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `XMLHandlers` Class Reference

<p>Event handlers that can installed by the client and called while parsing a XML document. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class XMLHandlers { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/libxml/xml-h">libxml/xml.h</a>&gt;
</div>

## Public Member Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a15cedeea046e36465580e5654121387e">Attributes</a> = std::unordered_map&lt; std::string, std::string &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9e5f0a29ad7b6d7b436ee85f91489928">StartDocType</a> = void()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2815400305c46e529a579f4b60d8461d">EndDocType</a> = void()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64536885798db372a91fd0cda75cf79a">StartElementType</a> = void(const std::string &amp;, const <a href="#a15cedeea046e36465580e5654121387e">Attributes</a> &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abe07ca39dbbd23c9c58bd944a1a515a4">EndElementType</a> = void(const std::string &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8034920e7bf0b89382769264fc482060">ErrorType</a> = void(const std::string, int, const std::string &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1defe3e13b4080a973e982a5a426967f">CharsType</a> = void(const std::string &amp;)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="#a9e5f0a29ad7b6d7b436ee85f91489928">StartDocType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae666b94024ae82743cc7b8ae6445e684">startDocument</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>handler invoked at the start of the document <a href="#ae666b94024ae82743cc7b8ae6445e684">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="#a2815400305c46e529a579f4b60d8461d">EndDocType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a762ceef4d0f235077af889915799facf">endDocument</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>handler invoked at the end of the document <a href="#a762ceef4d0f235077af889915799facf">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="#a64536885798db372a91fd0cda75cf79a">StartElementType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75b4fb2c24bd41404fe59c31a6dbd493">startElement</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>handler invoked when an opening tag has been found <a href="#a75b4fb2c24bd41404fe59c31a6dbd493">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="#abe07ca39dbbd23c9c58bd944a1a515a4">EndElementType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a623bc48085a8ced78c3202713a24724e">endElement</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>handler invoked when a closing tag has been found <a href="#a623bc48085a8ced78c3202713a24724e">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="#a1defe3e13b4080a973e982a5a426967f">CharsType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a895a088f5352bced5cf6a998da7fc06a">characters</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>handler invoked when content between tags has been found <a href="#a895a088f5352bced5cf6a998da7fc06a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::function&lt; <a href="#a8034920e7bf0b89382769264fc482060">ErrorType</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#adf5e4d9f4927edb0fb5d1259a4da9960">error</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>handler invoked when the parser encounters an error <a href="#adf5e4d9f4927edb0fb5d1259a4da9960">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad2d3b265aa5d98961404eb3ebd539921">value</a> (const Attributes &amp;attrib, const std::string &amp;key)</td>
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

<p>Event handlers that can installed by the client and called while parsing a XML document.</p>

<p>Definition at line 26 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxySectionDef">

## Public Member Typedefs

### Attributes {#a15cedeea046e36465580e5654121387e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using XMLHandlers::Attributes =  std::unordered_map&lt;std::string,std::string&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 29 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a15cedeea046e36465580e5654121387e">29</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a15cedeea046e36465580e5654121387e">Attributes</a>       = std::unordered_map&lt;std::string,std::string&gt;;</span></span></div>

</div>

</div>
</div>

### CharsType {#a1defe3e13b4080a973e982a5a426967f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using XMLHandlers::CharsType =  void(const std::string &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1defe3e13b4080a973e982a5a426967f">35</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a1defe3e13b4080a973e982a5a426967f">CharsType</a>        = void(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;);</span></span></div>

</div>

</div>
</div>

### EndDocType {#a2815400305c46e529a579f4b60d8461d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using XMLHandlers::EndDocType =  void()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2815400305c46e529a579f4b60d8461d">31</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a2815400305c46e529a579f4b60d8461d">EndDocType</a>       = void();</span></span></div>

</div>

</div>
</div>

### EndElementType {#abe07ca39dbbd23c9c58bd944a1a515a4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using XMLHandlers::EndElementType =  void(const std::string &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 33 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abe07ca39dbbd23c9c58bd944a1a515a4">33</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#abe07ca39dbbd23c9c58bd944a1a515a4">EndElementType</a>   = void(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;);</span></span></div>

</div>

</div>
</div>

### ErrorType {#a8034920e7bf0b89382769264fc482060}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using XMLHandlers::ErrorType =  void(const std::string,int,const std::string &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 34 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8034920e7bf0b89382769264fc482060">34</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a8034920e7bf0b89382769264fc482060">ErrorType</a>        = void(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;);</span></span></div>

</div>

</div>
</div>

### StartDocType {#a9e5f0a29ad7b6d7b436ee85f91489928}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using XMLHandlers::StartDocType =  void()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 30 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9e5f0a29ad7b6d7b436ee85f91489928">30</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a9e5f0a29ad7b6d7b436ee85f91489928">StartDocType</a>     = void();</span></span></div>

</div>

</div>
</div>

### StartElementType {#a64536885798db372a91fd0cda75cf79a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using XMLHandlers::StartElementType =  void(const std::string &amp;,const Attributes &amp;)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 32 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64536885798db372a91fd0cda75cf79a">32</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a64536885798db372a91fd0cda75cf79a">StartElementType</a> = void(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a15cedeea046e36465580e5654121387e">Attributes</a> &amp;);</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Attributes

### characters {#a895a088f5352bced5cf6a998da7fc06a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;CharsType&gt; XMLHandlers::characters</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>handler invoked when content between tags has been found</p>

<p>Definition at line 41 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a895a088f5352bced5cf6a998da7fc06a">41</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::function&lt;CharsType&gt;         <a href="#a895a088f5352bced5cf6a998da7fc06a">characters</a>;    </span><span class="doxyHighlightComment">/**&lt; handler invoked when content between tags has been found */</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a>.</p>

</div>
</div>

### endDocument {#a762ceef4d0f235077af889915799facf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;EndDocType&gt; XMLHandlers::endDocument</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>handler invoked at the end of the document</p>

<p>Definition at line 38 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a762ceef4d0f235077af889915799facf">38</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::function&lt;EndDocType&gt;        <a href="#a762ceef4d0f235077af889915799facf">endDocument</a>;   </span><span class="doxyHighlightComment">/**&lt; handler invoked at the end of the document */</span></span></div>

</div>

</div>
</div>

### endElement {#a623bc48085a8ced78c3202713a24724e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;EndElementType&gt; XMLHandlers::endElement</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>handler invoked when a closing tag has been found</p>

<p>Definition at line 40 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a623bc48085a8ced78c3202713a24724e">40</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::function&lt;EndElementType&gt;    <a href="#a623bc48085a8ced78c3202713a24724e">endElement</a>;    </span><span class="doxyHighlightComment">/**&lt; handler invoked when a closing tag has been found */</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a>.</p>

</div>
</div>

### error {#adf5e4d9f4927edb0fb5d1259a4da9960}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;ErrorType&gt; XMLHandlers::error</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>handler invoked when the parser encounters an error</p>

<p>Definition at line 42 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#adf5e4d9f4927edb0fb5d1259a4da9960">42</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::function&lt;ErrorType&gt;         <a href="#adf5e4d9f4927edb0fb5d1259a4da9960">error</a>;         </span><span class="doxyHighlightComment">/**&lt; handler invoked when the parser encounters an error */</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a>.</p>

</div>
</div>

### startDocument {#ae666b94024ae82743cc7b8ae6445e684}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;StartDocType&gt; XMLHandlers::startDocument</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>handler invoked at the start of the document</p>

<p>Definition at line 37 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae666b94024ae82743cc7b8ae6445e684">37</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::function&lt;StartDocType&gt;      <a href="#ae666b94024ae82743cc7b8ae6445e684">startDocument</a>; </span><span class="doxyHighlightComment">/**&lt; handler invoked at the start of the document */</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a>.</p>

</div>
</div>

### startElement {#a75b4fb2c24bd41404fe59c31a6dbd493}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::function&lt;StartElementType&gt; XMLHandlers::startElement</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>handler invoked when an opening tag has been found</p>

<p>Definition at line 39 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75b4fb2c24bd41404fe59c31a6dbd493">39</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::function&lt;StartElementType&gt;  <a href="#a75b4fb2c24bd41404fe59c31a6dbd493">startElement</a>;  </span><span class="doxyHighlightComment">/**&lt; handler invoked when an opening tag has been found */</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a>, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a> and <a href="/web-doxygen/docs/api/files/src/tagreader-cpp/#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### value() {#ad2d3b265aa5d98961404eb3ebd539921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string XMLHandlers::value (const <a href="#a15cedeea046e36465580e5654121387e">Attributes</a> &amp; attrib, const std::string &amp; key)</td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel inline">inline</span>
<span class="doxyMemberLabel static">static</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 44 of file <a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad2d3b265aa5d98961404eb3ebd539921">44</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::string <a href="#ad2d3b265aa5d98961404eb3ebd539921">value</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="#a15cedeea046e36465580e5654121387e">Attributes</a> &amp;attrib,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">45</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">46</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = attrib.find(key);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">47</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=attrib.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">48</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">49</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">50</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a6927f64d6b3e45878b5102852e1e2fac">anonymous{tagreader.cpp}::TagFileParser::startBase</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#ab17fadda7f7d30dce3d68f186aaed55d">anonymous{tagreader.cpp}::TagFileParser::startCompound</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a3646ed3d0fe02e98b159d52ff914f305">anonymous{tagreader.cpp}::TagFileParser::startDocAnchor</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#afc3a2293108d7a644b0c57ad06f29c11">anonymous{tagreader.cpp}::TagFileParser::startEnumValue</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#a347e401a684f17633b5d23c1010b3f28">anonymous{tagreader.cpp}::TagFileParser::startIncludes</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#ae1e94d4f205f79a8b052e4140d575cb9">LayoutParser::startLayout</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#aa4db9510d59066b8d7f847bda9fb9574">anonymous{tagreader.cpp}::TagFileParser::startMember</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#afcd6c1e555f2bc462f5703468b23c3d8">LayoutParser::startMemberDeclEntry</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#a159d9ffd0d6742275e763d2bb25ae3f0">LayoutParser::startMemberDefEntry</a>, <a href="/web-doxygen/docs/api/classes/layoutparser/#aba3b3876764867eeb32b9dcce3d4b63b">LayoutParser::startNavEntry</a> and <a href="/web-doxygen/docs/api/classes/layoutparser/#a3a78c06f8d054ac9c9b0b210d243f9b6">LayoutParser::startSectionEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
