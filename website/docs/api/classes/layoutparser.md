---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/layoutparser
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `LayoutParser` Class Reference



## Declaration

<div class="doxyDeclaration">
class LayoutParser { ... }
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c46432d802f9820d16f0da35c258ce3">LayoutParser</a> (LayoutDocManager &amp;manager)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a27bcf121a54f586745ec706921dc955b">setDocumentLocator</a> (const XMLLocator *locator)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4bec4061de53be8bf8585c227844737d">error</a> (const std::string &amp;fileName, int lineNr, const std::string &amp;msg)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aec3d26d68ff653ee286a16533ba98560">startElement</a> (const std::string &amp;name, const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acbe58d70dfdb7b82544b3c6390a3ffa9">endElement</a> (const std::string &amp;name)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a300bf87a1f25049f900cabbf39921714">startSimpleEntry</a> (LayoutDocEntry::Kind k, const std::string &amp;id, const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3a78c06f8d054ac9c9b0b210d243f9b6">startSectionEntry</a> (LayoutDocEntry::Kind k, const std::string &amp;id, const XMLHandlers::Attributes &amp;attrib, const QCString &amp;title)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afcd6c1e555f2bc462f5703468b23c3d8">startMemberDeclEntry</a> (const std::string &amp;id, const XMLHandlers::Attributes &amp;attrib, MemberListType type, const QCString &amp;title, const QCString &amp;subscript)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a159d9ffd0d6742275e763d2bb25ae3f0">startMemberDefEntry</a> (const std::string &amp;id, const XMLHandlers::Attributes &amp;attrib, MemberListType type, const QCString &amp;title, const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae1e94d4f205f79a8b052e4140d575cb9">startLayout</a> (const std::string &amp;, const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a314407ef719f76e868dab2366d52b036">startNavIndex</a> (const std::string &amp;, const XMLHandlers::Attributes &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a245cae7606ecd9bd4ee135b802b030d2">endNavIndex</a> (const std::string &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aba3b3876764867eeb32b9dcce3d4b63b">startNavEntry</a> (const std::string &amp;, const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9f6db63ad970b43690ec22a4558aaea7">endNavEntry</a> (const std::string &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a63da49c04af1554c5205a7c8fd4831b6">startTop</a> (const std::string &amp;, const XMLHandlers::Attributes &amp;attrib, LayoutDocManager::LayoutPart part, const QCString &amp;scope, LayoutNavEntry::Kind nav)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19d81b682415be8d632795f5a0572a5c">endTop</a> (const std::string &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#abf6e0ed11a67228356030bafc743c57f">startMemberDef</a> (const std::string &amp;id, const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a959b2ab0ecbb71a6f7c9f8ee87a36a2a">endMemberDef</a> (const std::string &amp;id)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a80ec53b42b990b7291e15d55351e1921">startMemberDecl</a> (const std::string &amp;id, const XMLHandlers::Attributes &amp;attrib)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8a6bfc037293b6fb0178f1c51c257b06">endMemberDecl</a> (const std::string &amp;id)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a75f8b4ee2ad4de9bf624c5427ce75fae">majorVersion</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9883cc99cb60a2b4c3c4135521ddc12c">minorVersion</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/layoutdocmanager">LayoutDocManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aee13a925ea1f915c542ecd7f579ebc94">LayoutDocManager::LayoutPart</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a> = LayoutDocManager::Undefined</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9da971c25670c1827d1a08877fb091c1">m_invalidEntry</a> = false</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> = true</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/xmllocator">XMLLocator</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">m_locator</a> = nullptr</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af618114530371cf25f106991592452eb">m_majorVersion</a> = 1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67669eb35ad908dd62d9e3adc8b8dd51">m_minorVersion</a> = 0</td>
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

## Private Static Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static int</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a280d75b3f9fd09d4cace0bc11c78c18e">m_userGroupCount</a> =0</td>
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


<p>Definition at line 194 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### LayoutParser() {#a3c46432d802f9820d16f0da35c258ce3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutParser::LayoutParser (<a href="/web-doxygen/docs/api/classes/layoutdocmanager">LayoutDocManager</a> &amp; manager)</td>
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



<p>Definition at line 197 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c46432d802f9820d16f0da35c258ce3">197</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a3c46432d802f9820d16f0da35c258ce3">LayoutParser</a>(<a href="/web-doxygen/docs/api/classes/layoutdocmanager">LayoutDocManager</a> &amp;manager) : <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>(manager) {}</span></span></div>

</div>


<p>Reference <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### endElement() {#acbe58d70dfdb7b82544b3c6390a3ffa9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::endElement (const std::string &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 209 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acbe58d70dfdb7b82544b3c6390a3ffa9">1373</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acbe58d70dfdb7b82544b3c6390a3ffa9">LayoutParser::endElement</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;name )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("endElement [%s]::[%s]\n",qPrint(m_scope),qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it=<a href="/web-doxygen/docs/api/namespaces/anonymous-layout-cpp-/#a470220b386daeb653bf189ad7b6c419f">g_elementHandlers</a>.end();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.isEmpty() &amp;&amp; <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.right(name.length()+1)==name+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">  { </span><span class="doxyHighlightComment">// element ends current scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">    it = <a href="/web-doxygen/docs/api/namespaces/anonymous-layout-cpp-/#a470220b386daeb653bf189ad7b6c419f">g_elementHandlers</a>.find(<a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.left(<a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.length()-1).str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// continue with current scope</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">    it = <a href="/web-doxygen/docs/api/namespaces/anonymous-layout-cpp-/#a470220b386daeb653bf189ad7b6c419f">g_elementHandlers</a>.find(<a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.str()+name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/namespaces/anonymous-layout-cpp-/#a470220b386daeb653bf189ad7b6c419f">g_elementHandlers</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">    it-&gt;second.endCb(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,it-&gt;first+</span><span class="doxyHighlightStringLiteral">" end"</span><span class="doxyHighlight">); </span><span class="doxyHighlightComment">// added end to id to make it unique</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/namespaces/anonymous-layout-cpp-/#a470220b386daeb653bf189ad7b6c419f">anonymous_namespace{layout.cpp}::g_elementHandlers</a> and <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a> and <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a>.</p>

</div>
</div>

### endMemberDecl() {#a8a6bfc037293b6fb0178f1c51c257b06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::endMemberDecl (const std::string &amp; id)</td>
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



<p>Definition at line 681 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8a6bfc037293b6fb0178f1c51c257b06">681</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8a6bfc037293b6fb0178f1c51c257b06">endMemberDecl</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=<a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.findRev(</span><span class="doxyHighlightStringLiteral">"memberdecl/"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">684</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">685</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>=<a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.left(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isVisible = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;lde : <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.docEntries(<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">690</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lde-&gt;kind() == LayoutDocEntry::MemberDeclStart)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">691</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">             isVisible = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/layoutdocentrysimple">LayoutDocEntrySimple</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(lde.get())-&gt;<a href="/web-doxygen/docs/api/structs/layoutdocentrysimple/#a576cf86e0f990156f94753d1de8debaf">visible</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>!=LayoutDocManager::Undefined)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.addEntry(<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>,std::make_unique&lt;LayoutDocEntrySimple&gt;(LayoutDocEntry::MemberDeclEnd,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,isVisible));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>, <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>, <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a> and <a href="/web-doxygen/docs/api/structs/layoutdocentrysimple/#a576cf86e0f990156f94753d1de8debaf">LayoutDocEntrySimple::visible</a>.</p>

</div>
</div>

### endMemberDef() {#a959b2ab0ecbb71a6f7c9f8ee87a36a2a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::endMemberDef (const std::string &amp; id)</td>
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



<p>Definition at line 648 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a959b2ab0ecbb71a6f7c9f8ee87a36a2a">648</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a959b2ab0ecbb71a6f7c9f8ee87a36a2a">endMemberDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scopeOrg = <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=<a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.findRev(</span><span class="doxyHighlightStringLiteral">"memberdef/"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>=<a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.left(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isVisible = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;lde : <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.docEntries(<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lde-&gt;kind() == LayoutDocEntry::MemberDefStart)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">             isVisible = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/layoutdocentrysimple">LayoutDocEntrySimple</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(lde.get())-&gt;<a href="/web-doxygen/docs/api/structs/layoutdocentrysimple/#a576cf86e0f990156f94753d1de8debaf">visible</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>!=LayoutDocManager::Undefined)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.addEntry(<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>,std::make_unique&lt;LayoutDocEntrySimple&gt;(LayoutDocEntry::MemberDefEnd,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,isVisible));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>, <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>, <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a> and <a href="/web-doxygen/docs/api/structs/layoutdocentrysimple/#a576cf86e0f990156f94753d1de8debaf">LayoutDocEntrySimple::visible</a>.</p>

</div>
</div>

### endNavEntry() {#a9f6db63ad970b43690ec22a4558aaea7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::endNavEntry (const std::string &amp;)</td>
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



<p>Definition at line 616 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9f6db63ad970b43690ec22a4558aaea7">616</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9f6db63ad970b43690ec22a4558aaea7">endNavEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// set the root back to the parent</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a> &amp;&amp; !<a href="#a9da971c25670c1827d1a08877fb091c1">m_invalidEntry</a>) <a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a> = <a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a>-&gt;parent();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a9da971c25670c1827d1a08877fb091c1">m_invalidEntry</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="#a9da971c25670c1827d1a08877fb091c1">m_invalidEntry</a> and <a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a>.</p>

</div>
</div>

### endNavIndex() {#a245cae7606ecd9bd4ee135b802b030d2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::endNavIndex (const std::string &amp;)</td>
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



<p>Definition at line 286 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a245cae7606ecd9bd4ee135b802b030d2">286</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a245cae7606ecd9bd4ee135b802b030d2">endNavIndex</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a> &amp;&amp; !<a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a>-&gt;find(LayoutNavEntry::MainPage))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// no MainPage node... add one as the first item of the root node...</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a>-&gt;insertChild(0,std::make_unique&lt;LayoutNavEntry&gt;(<a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a>,LayoutNavEntry::MainPage, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">                                                   </span><span class="doxyHighlightStringLiteral">"index"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trMainPage(),</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a>, <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>

</div>
</div>

### endTop() {#a19d81b682415be8d632795f5a0572a5c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::endTop (const std::string &amp;)</td>
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



<p>Definition at line 632 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19d81b682415be8d632795f5a0572a5c">632</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a19d81b682415be8d632795f5a0572a5c">endTop</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">635</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a> = LayoutDocManager::Undefined;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">636</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a> and <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.</p>

</div>
</div>

### error() {#a4bec4061de53be8bf8585c227844737d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::error (const std::string &amp; fileName, int lineNr, const std::string &amp; msg)</td>
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



<p>Definition at line 204 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4bec4061de53be8bf8585c227844737d">204</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a4bec4061de53be8bf8585c227844737d">error</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#ae67293b4e15438bb5812e59146f0750d">warn_layout</a>(fileName.c_str(),lineNr,</span><span class="doxyHighlightStringLiteral">"{}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#ae67293b4e15438bb5812e59146f0750d">warn_layout</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a> and <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a>.</p>

</div>
</div>

### majorVersion() {#a75f8b4ee2ad4de9bf624c5427ce75fae}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LayoutParser::majorVersion ()</td>
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



<p>Definition at line 703 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a75f8b4ee2ad4de9bf624c5427ce75fae">703</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a75f8b4ee2ad4de9bf624c5427ce75fae">majorVersion</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#af618114530371cf25f106991592452eb">m_majorVersion</a>; }</span></span></div>

</div>


<p>Reference <a href="#af618114530371cf25f106991592452eb">m_majorVersion</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a> and <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a>.</p>

</div>
</div>

### minorVersion() {#a9883cc99cb60a2b4c3c4135521ddc12c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LayoutParser::minorVersion ()</td>
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



<p>Definition at line 704 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9883cc99cb60a2b4c3c4135521ddc12c">704</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a9883cc99cb60a2b4c3c4135521ddc12c">minorVersion</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a67669eb35ad908dd62d9e3adc8b8dd51">m_minorVersion</a>; }</span></span></div>

</div>


<p>Reference <a href="#a67669eb35ad908dd62d9e3adc8b8dd51">m_minorVersion</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a> and <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a>.</p>

</div>
</div>

### setDocumentLocator() {#a27bcf121a54f586745ec706921dc955b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::setDocumentLocator (const <a href="/web-doxygen/docs/api/classes/xmllocator">XMLLocator</a> * locator)</td>
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



<p>Definition at line 200 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a27bcf121a54f586745ec706921dc955b">200</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a27bcf121a54f586745ec706921dc955b">setDocumentLocator</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmllocator">XMLLocator</a> *locator)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">m_locator</a> = locator;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">m_locator</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a> and <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a>.</p>

</div>
</div>

### startElement() {#aec3d26d68ff653ee286a16533ba98560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::startElement (const std::string &amp; name, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 208 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aec3d26d68ff653ee286a16533ba98560">1357</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aec3d26d68ff653ee286a16533ba98560">LayoutParser::startElement</a>( </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;name, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a>&amp; attrib )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1359</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("startElement [%s]::[%s]\n",qPrint(m_scope),qPrint(name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1360</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="/web-doxygen/docs/api/namespaces/anonymous-layout-cpp-/#a470220b386daeb653bf189ad7b6c419f">g_elementHandlers</a>.find(<a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.str()+name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="/web-doxygen/docs/api/namespaces/anonymous-layout-cpp-/#a470220b386daeb653bf189ad7b6c419f">g_elementHandlers</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">    it-&gt;second.startCb(*</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">,it-&gt;first,attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1364</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1365</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string fileName = <a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">m_locator</a>-&gt;fileName();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#ae67293b4e15438bb5812e59146f0750d">warn_layout</a>(fileName.c_str(),<a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">m_locator</a>-&gt;lineNr(),</span><span class="doxyHighlightStringLiteral">"Unexpected start tag '{}' found in scope='{}'!"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1369</span><span class="doxyLineContent"><span class="doxyHighlight">        name,<a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1370</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/namespaces/anonymous-layout-cpp-/#a470220b386daeb653bf189ad7b6c419f">anonymous_namespace{layout.cpp}::g_elementHandlers</a>, <a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">m_locator</a>, <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#ae67293b4e15438bb5812e59146f0750d">warn_layout</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#a920748477d4262faf758d21ddbe2329d">LayoutDocManager::init</a> and <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aa40638bbc3b82e1b24a760b6e5dff877">LayoutDocManager::parse</a>.</p>

</div>
</div>

### startLayout() {#ae1e94d4f205f79a8b052e4140d575cb9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::startLayout (const std::string &amp;, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
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



<p>Definition at line 266 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae1e94d4f205f79a8b052e4140d575cb9">266</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ae1e94d4f205f79a8b052e4140d575cb9">startLayout</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrib)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// extract and store version number</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a94b2a502ca15f65f6111c08f674fae4a">version</a> = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"version"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re(R</span><span class="doxyHighlightStringLiteral">"((\d+)\.(\d+))");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#abd83bf57cdc053d40135b7c8f211f2b9">reg::match</a>(<a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a94b2a502ca15f65f6111c08f674fae4a">version</a>.view(),match,re))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#af618114530371cf25f106991592452eb">m_majorVersion</a> = atoi(match[1].str().c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a67669eb35ad908dd62d9e3adc8b8dd51">m_minorVersion</a> = atoi(match[2].str().c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("layout version %d.%d\n",m_versionMajor,m_versionMinor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#af618114530371cf25f106991592452eb">m_majorVersion</a>, <a href="#a67669eb35ad908dd62d9e3adc8b8dd51">m_minorVersion</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#abd83bf57cdc053d40135b7c8f211f2b9">reg::match</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a94b2a502ca15f65f6111c08f674fae4a">version</a>.</p>

</div>
</div>

### startMemberDecl() {#a80ec53b42b990b7291e15d55351e1921}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::startMemberDecl (const std::string &amp; id, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
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



<p>Definition at line 671 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a80ec53b42b990b7291e15d55351e1921">671</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a80ec53b42b990b7291e15d55351e1921">startMemberDecl</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrib)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>+=</span><span class="doxyHighlightStringLiteral">"memberdecl/"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isVisible = <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>(attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>!=LayoutDocManager::Undefined)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.addEntry(<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>,std::make_unique&lt;LayoutDocEntrySimple&gt;(LayoutDocEntry::MemberDeclStart,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,isVisible));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>, <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>, <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a> and <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a>.</p>

</div>
</div>

### startMemberDeclEntry() {#afcd6c1e555f2bc462f5703468b23c3d8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::startMemberDeclEntry (const std::string &amp; id, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; subscript)</td>
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



<p>Definition at line 239 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afcd6c1e555f2bc462f5703468b23c3d8">239</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#afcd6c1e555f2bc462f5703468b23c3d8">startMemberDeclEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrib,<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> type,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;subscript)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> userTitle     = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"title"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> userSubscript = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"subtitle"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (userTitle.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())     userTitle     = title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (userSubscript.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) userSubscript = subscript;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isVisible = <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>(attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>!=LayoutDocManager::Undefined)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.addEntry(<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>,std::make_unique&lt;LayoutDocEntryMemberDecl&gt;(type,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,userTitle,userSubscript,isVisible));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>, <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>, <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> and <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>.</p>

</div>
</div>

### startMemberDef() {#abf6e0ed11a67228356030bafc743c57f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::startMemberDef (const std::string &amp; id, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
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



<p>Definition at line 638 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#abf6e0ed11a67228356030bafc743c57f">638</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#abf6e0ed11a67228356030bafc743c57f">startMemberDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrib)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>+=</span><span class="doxyHighlightStringLiteral">"memberdef/"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isVisible = <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>(attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>!=LayoutDocManager::Undefined)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.addEntry(<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>,std::make_unique&lt;LayoutDocEntrySimple&gt;(LayoutDocEntry::MemberDefStart,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,isVisible));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>, <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>, <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a> and <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a>.</p>

</div>
</div>

### startMemberDefEntry() {#a159d9ffd0d6742275e763d2bb25ae3f0}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::startMemberDefEntry (const std::string &amp; id, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib, <a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> type, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 253 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a159d9ffd0d6742275e763d2bb25ae3f0">253</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a159d9ffd0d6742275e763d2bb25ae3f0">startMemberDefEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrib,<a href="/web-doxygen/docs/api/classes/memberlisttype">MemberListType</a> type,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">                             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> userTitle = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"title"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (userTitle.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) userTitle = title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("memberdef: %s\n",qPrint(userTitle));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isVisible = <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>(attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>!=LayoutDocManager::Undefined)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.addEntry(<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>,std::make_unique&lt;LayoutDocEntryMemberDef&gt;(type,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,userTitle,isVisible));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>, <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>, <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> and <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>.</p>

</div>
</div>

### startNavEntry() {#aba3b3876764867eeb32b9dcce3d4b63b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::startNavEntry (const std::string &amp;, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
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



<p>Definition at line 297 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aba3b3876764867eeb32b9dcce3d4b63b">297</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aba3b3876764867eeb32b9dcce3d4b63b">startNavEntry</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrib)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> javaOpt    = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_JAVA);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> fortranOpt = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_FOR_FORTRAN);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> vhdlOpt    = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_VHDL);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> sliceOpt   = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_SLICE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasGraphicalHierarchy = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(HAVE_DOT) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">                                          <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GRAPHICAL_HIERARCHY);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> extractAll = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(EXTRACT_ALL);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">NavEntryMap</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *typeStr;       </span><span class="doxyHighlightComment">// type attribute name in the XML file</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> kind; </span><span class="doxyHighlightComment">// corresponding enum name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mainName;         </span><span class="doxyHighlightComment">// default title for an item if it has children</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> subName;          </span><span class="doxyHighlightComment">// optional name for an item if it is rendered as a child</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> intro;            </span><span class="doxyHighlightComment">// introduction text to be put on the index page</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseFile;         </span><span class="doxyHighlightComment">// base name of the file containing the index page</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">      } mapping[] =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"mainpage"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::MainPage,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trMainPage(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"index"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"pages"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::Pages,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trRelatedPages(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trRelatedPagesDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"pages"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"topics"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::Topics,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trTopics(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trTopicListDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"topics"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"modules"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::Modules,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModules(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"modules"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"modulelist"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::ModuleList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesListDescription(extractAll),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"modules"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"modulemembers"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::ModuleMembers,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesMembers(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesMemberDescription(extractAll),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"modulemembers"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"namespaces"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::Namespaces,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">          javaOpt || vhdlOpt   ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPackages() : fortranOpt || sliceOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModules() : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNamespaces(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">          javaOpt || vhdlOpt   ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPackageList() : fortranOpt || sliceOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesList() : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNamespaceList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">          javaOpt || vhdlOpt   ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPackageListDescription() : fortranOpt || sliceOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesListDescription(extractAll) : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNamespaceListDescription(extractAll),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"namespaces"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"namespacelist"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::NamespaceList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">          javaOpt || vhdlOpt   ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPackageList() : fortranOpt || sliceOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesList() : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNamespaceList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">          javaOpt || vhdlOpt   ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPackageListDescription() : fortranOpt || sliceOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesListDescription(extractAll) : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNamespaceListDescription(extractAll),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"namespaces"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"namespacemembers"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::NamespaceMembers,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">          javaOpt || vhdlOpt   ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPackageMembers() : fortranOpt || sliceOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesMembers() : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNamespaceMembers(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">          fortranOpt || sliceOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModulesMemberDescription(extractAll) : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNamespaceMemberDescription(extractAll),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"namespacemembers"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"concepts"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::Concepts,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trConcept(</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trConceptList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">383</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trConceptListDescription(extractAll),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">384</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"concepts"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">385</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">386</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"classindex"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">387</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::ClassIndex,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">388</span><span class="doxyLineContent"><span class="doxyHighlight">          fortranOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundIndexFortran() : vhdlOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDesignUnitIndex() : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundIndex(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">389</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">390</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">391</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"classes"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">392</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">393</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"classes"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">394</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::Classes,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">395</span><span class="doxyLineContent"><span class="doxyHighlight">          fortranOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDataTypes() : vhdlOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDesignUnits() : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trClasses(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">396</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">397</span><span class="doxyLineContent"><span class="doxyHighlight">          fortranOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundListDescriptionFortran() : vhdlOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDesignUnitListDescription() : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundListDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">398</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"annotated"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">399</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">400</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"classlist"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">401</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::ClassList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">402</span><span class="doxyLineContent"><span class="doxyHighlight">          fortranOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundListFortran() : vhdlOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDesignUnitList() : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">403</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">404</span><span class="doxyLineContent"><span class="doxyHighlight">          fortranOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundListDescriptionFortran() : vhdlOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDesignUnitListDescription() : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundListDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">405</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"annotated"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">406</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">407</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"hierarchy"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">408</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::ClassHierarchy,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">409</span><span class="doxyLineContent"><span class="doxyHighlight">          vhdlOpt    ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDesignUnitHierarchy() : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trClassHierarchy(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">410</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">411</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trClassHierarchyDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">412</span><span class="doxyLineContent"><span class="doxyHighlight">          hasGraphicalHierarchy ? </span><span class="doxyHighlightStringLiteral">"inherits"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"hierarchy"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">413</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">414</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"classmembers"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">415</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::ClassMembers,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">416</span><span class="doxyLineContent"><span class="doxyHighlight">          fortranOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundMembersFortran() : vhdlOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDesignUnitMembers() : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundMembers(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">417</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">418</span><span class="doxyLineContent"><span class="doxyHighlight">          fortranOpt ? <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundMembersDescriptionFortran(extractAll) : <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trCompoundMembersDescription(extractAll),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">419</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"functions"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">420</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">421</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"interfaceindex"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">422</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::InterfaceIndex,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">423</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInterfaceIndex(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">424</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">425</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">426</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"interfaces"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">427</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">428</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"interfaces"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">429</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::Interfaces,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">430</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSliceInterfaces(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">431</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInterfaceList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">432</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInterfaceListDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">433</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"annotatedinterfaces"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">434</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">435</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"interfacelist"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">436</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::InterfaceList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">437</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInterfaceList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">438</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">439</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInterfaceListDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">440</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"annotatedinterfaces"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">441</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">442</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"interfacehierarchy"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">443</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::InterfaceHierarchy,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">444</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInterfaceHierarchy(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">445</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">446</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trInterfaceHierarchyDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">447</span><span class="doxyLineContent"><span class="doxyHighlight">          hasGraphicalHierarchy ? </span><span class="doxyHighlightStringLiteral">"interfaceinherits"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"interfacehierarchy"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">448</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">449</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"structindex"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">450</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::StructIndex,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">451</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trStructIndex(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">452</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">453</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">454</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"structs"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">455</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">456</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"structs"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">457</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::Structs,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">458</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trStructs(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">459</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trStructList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">460</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trStructListDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">461</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"annotatedstructs"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">462</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">463</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"structlist"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">464</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::StructList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">465</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trStructList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">466</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">467</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trStructListDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">468</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"annotatedstructs"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">469</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">470</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"exceptionindex"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">471</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::ExceptionIndex,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">472</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptionIndex(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">473</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">474</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">475</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"exceptions"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">476</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">477</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"exceptions"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">478</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::Exceptions,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">479</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptions(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">480</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptionList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">481</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptionListDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">482</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"annotatedexceptions"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">483</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">484</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"exceptionlist"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">485</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::ExceptionList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">486</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptionList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">487</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">488</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptionListDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">489</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"annotatedexceptions"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">490</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">491</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"exceptionhierarchy"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">492</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::ExceptionHierarchy,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">493</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptionHierarchy(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">494</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">495</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExceptionHierarchyDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">496</span><span class="doxyLineContent"><span class="doxyHighlight">          hasGraphicalHierarchy ? </span><span class="doxyHighlightStringLiteral">"exceptioninherits"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"exceptionhierarchy"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">497</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">498</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"files"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">499</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::Files,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">500</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trFile(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">501</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trFileList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">502</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trFileListDescription(extractAll),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">503</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"files"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">504</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"filelist"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::FileList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trFileList(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trFileListDescription(extractAll),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"files"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"globals"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">513</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::FileGlobals,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">514</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trFileMembers(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">515</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">516</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trFileMembersDescription(extractAll),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">517</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"globals"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">518</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">519</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"examples"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">520</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::Examples,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">521</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExamples(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">522</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">523</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trExamplesDescription(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">524</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"examples"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">525</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">526</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"user"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">527</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::User,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">528</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"user"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">532</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">533</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightStringLiteral">"usergroup"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">534</span><span class="doxyLineContent"><span class="doxyHighlight">          LayoutNavEntry::UserGroup,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">535</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">536</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">537</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">538</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightStringLiteral">"usergroup"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">539</span><span class="doxyLineContent"><span class="doxyHighlight">        },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">540</span><span class="doxyLineContent"><span class="doxyHighlight">        { </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, </span><span class="doxyHighlightComment">// end of list</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">541</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a></span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(0),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">542</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">543</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">544</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">545</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">546</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">547</span><span class="doxyLineContent"><span class="doxyHighlight">      };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">548</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// find type in the table</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">549</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">550</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> type = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">551</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (mapping[i].typeStr)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">552</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">553</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mapping[i].typeStr==type)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">        i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mapping[i].typeStr==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">        std::string fileName = <a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">m_locator</a>-&gt;fileName();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (type.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#ae67293b4e15438bb5812e59146f0750d">warn_layout</a>(fileName.c_str(),<a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">m_locator</a>-&gt;lineNr(),</span><span class="doxyHighlightStringLiteral">"an entry tag within a navindex has no type attribute! Check your layout file!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#ae67293b4e15438bb5812e59146f0750d">warn_layout</a>(fileName.c_str(),<a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">m_locator</a>-&gt;lineNr(),</span><span class="doxyHighlightStringLiteral">"the type '{}' is not supported for the entry tag within a navindex! Check your layout file!"</span><span class="doxyHighlight">,type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#a9da971c25670c1827d1a08877fb091c1">m_invalidEntry</a>=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> kind = mapping[i].kind;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseFile = mapping[i].baseFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> title = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"title"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isVisible = <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>(attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (title.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// use default title</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">        title = mapping[i].mainName; </span><span class="doxyHighlightComment">// use title for main row</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a>!=<a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.rootNavEntry() &amp;&amp; !mapping[i].subName.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">          title = mapping[i].subName; </span><span class="doxyHighlightComment">// if this is a child of another row, use the subName if available</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">                                      </span><span class="doxyHighlightComment">// this is mainly done to get compatible naming with older versions.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> intro = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"intro"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (intro.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// use default intro text</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">        intro = mapping[i].intro;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"url"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mapping[i].kind==LayoutNavEntry::User &amp;&amp; !url.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">        baseFile=url;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (kind==LayoutNavEntry::UserGroup)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!url.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (url == </span><span class="doxyHighlightStringLiteral">"[none]"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">            baseFile = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span><span class="doxyLineContent"><span class="doxyHighlight">            baseFile=url;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">          baseFile+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"%d"</span><span class="doxyHighlight">,<a href="#a280d75b3f9fd09d4cace0bc11c78c18e">m_userGroupCount</a>++);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// create new item and make it the new root</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a> = <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.createChildNavEntry(<a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a>,kind,isVisible,baseFile,title,intro);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a9da971c25670c1827d1a08877fb091c1">m_invalidEntry</a>, <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>, <a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">m_locator</a>, <a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a>, <a href="#a280d75b3f9fd09d4cace0bc11c78c18e">m_userGroupCount</a>, <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#ae67293b4e15438bb5812e59146f0750d">warn_layout</a>.</p>

</div>
</div>

### startNavIndex() {#a314407ef719f76e868dab2366d52b036}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::startNavIndex (const std::string &amp;, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;)</td>
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



<p>Definition at line 280 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a314407ef719f76e868dab2366d52b036">280</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a314407ef719f76e868dab2366d52b036">startNavIndex</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>=</span><span class="doxyHighlightStringLiteral">"navindex/"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a> = <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.rootNavEntry();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>, <a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a> and <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>.</p>

</div>
</div>

### startSectionEntry() {#a3a78c06f8d054ac9c9b0b210d243f9b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::startSectionEntry (<a href="/web-doxygen/docs/api/structs/layoutdocentry/#a89dcbe762ed7e7f7790d8c034cf8ea01">LayoutDocEntry::Kind</a> k, const std::string &amp; id, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; title)</td>
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



<p>Definition at line 224 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3a78c06f8d054ac9c9b0b210d243f9b6">224</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3a78c06f8d054ac9c9b0b210d243f9b6">startSectionEntry</a>(<a href="/web-doxygen/docs/api/structs/layoutdocentry/#a89dcbe762ed7e7f7790d8c034cf8ea01">LayoutDocEntry::Kind</a> k,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrib,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;title)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isVisible = <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>(attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> userTitle = <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>(attrib,</span><span class="doxyHighlightStringLiteral">"title"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("startSectionEntry: title='%s' userTitle='%s'\n",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//    qPrint(title),qPrint(userTitle));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (userTitle.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())  userTitle = title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>!=LayoutDocManager::Undefined)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.addEntry(<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>,std::make_unique&lt;LayoutDocEntrySection&gt;(k,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,userTitle,isVisible));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>, <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>, <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> and <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ad2d3b265aa5d98961404eb3ebd539921">XMLHandlers::value</a>.</p>

</div>
</div>

### startSimpleEntry() {#a300bf87a1f25049f900cabbf39921714}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::startSimpleEntry (<a href="/web-doxygen/docs/api/structs/layoutdocentry/#a89dcbe762ed7e7f7790d8c034cf8ea01">LayoutDocEntry::Kind</a> k, const std::string &amp; id, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib)</td>
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



<p>Definition at line 211 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a300bf87a1f25049f900cabbf39921714">211</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a300bf87a1f25049f900cabbf39921714">startSimpleEntry</a>(<a href="/web-doxygen/docs/api/structs/layoutdocentry/#a89dcbe762ed7e7f7790d8c034cf8ea01">LayoutDocEntry::Kind</a> k,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrib)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isVisible = <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> &amp;&amp; <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>(attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>!=LayoutDocManager::Undefined)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> elem = std::make_unique&lt;LayoutDocEntrySimple&gt;(k,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,isVisible);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("startSimpleEntry(%s) isVisible=%d visible=%d\n",qPrint(elem-&gt;entryToString()),isVisible,elem-&gt;visible());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>.addEntry(<a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>,std::move(elem));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>, <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a> and <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a>.</p>

</div>
</div>

### startTop() {#a63da49c04af1554c5205a7c8fd4831b6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void LayoutParser::startTop (const std::string &amp;, const <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp; attrib, <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aee13a925ea1f915c542ecd7f579ebc94">LayoutDocManager::LayoutPart</a> part, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scope, <a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> nav)</td>
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



<p>Definition at line 623 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a63da49c04af1554c5205a7c8fd4831b6">623</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a63da49c04af1554c5205a7c8fd4831b6">startTop</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrib,<a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aee13a925ea1f915c542ecd7f579ebc94">LayoutDocManager::LayoutPart</a> part,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;scope, <a href="/web-doxygen/docs/api/structs/layoutnaventry/#aef36305dd829f7cde87ca203ae647c7c">LayoutNavEntry::Kind</a> nav)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("startTop(scope=%s)\n",qPrint(scope));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a> = scope;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a> = part;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> = <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>(attrib);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/layout-cpp/#a655e33094d44e8925db5939ca9d68d36">elemIsVisible</a>, <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a>, <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a> and <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_invalidEntry {#a9da971c25670c1827d1a08877fb091c1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LayoutParser::m_invalidEntry = false</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 711 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9da971c25670c1827d1a08877fb091c1">711</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a9da971c25670c1827d1a08877fb091c1">m_invalidEntry</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a9f6db63ad970b43690ec22a4558aaea7">endNavEntry</a> and <a href="#aba3b3876764867eeb32b9dcce3d4b63b">startNavEntry</a>.</p>

</div>
</div>

### m\_layoutDocManager {#ab4dbd373d27fba09897b1889ee03624d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutDocManager&amp; LayoutParser::m_layoutDocManager</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 708 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab4dbd373d27fba09897b1889ee03624d">708</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/layoutdocmanager">LayoutDocManager</a> &amp;<a href="#ab4dbd373d27fba09897b1889ee03624d">m_layoutDocManager</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a8a6bfc037293b6fb0178f1c51c257b06">endMemberDecl</a>, <a href="#a959b2ab0ecbb71a6f7c9f8ee87a36a2a">endMemberDef</a>, <a href="#a3c46432d802f9820d16f0da35c258ce3">LayoutParser</a>, <a href="#a80ec53b42b990b7291e15d55351e1921">startMemberDecl</a>, <a href="#afcd6c1e555f2bc462f5703468b23c3d8">startMemberDeclEntry</a>, <a href="#abf6e0ed11a67228356030bafc743c57f">startMemberDef</a>, <a href="#a159d9ffd0d6742275e763d2bb25ae3f0">startMemberDefEntry</a>, <a href="#aba3b3876764867eeb32b9dcce3d4b63b">startNavEntry</a>, <a href="#a314407ef719f76e868dab2366d52b036">startNavIndex</a>, <a href="#a3a78c06f8d054ac9c9b0b210d243f9b6">startSectionEntry</a> and <a href="#a300bf87a1f25049f900cabbf39921714">startSimpleEntry</a>.</p>

</div>
</div>

### m\_locator {#a64bbc5fb3177a7eaf9cf83b29a662aeb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const XMLLocator* LayoutParser::m_locator = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 714 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">714</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmllocator">XMLLocator</a> *<a href="#a64bbc5fb3177a7eaf9cf83b29a662aeb">m_locator</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a27bcf121a54f586745ec706921dc955b">setDocumentLocator</a>, <a href="#aec3d26d68ff653ee286a16533ba98560">startElement</a> and <a href="#aba3b3876764867eeb32b9dcce3d4b63b">startNavEntry</a>.</p>

</div>
</div>

### m\_majorVersion {#af618114530371cf25f106991592452eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LayoutParser::m_majorVersion = 1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 715 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af618114530371cf25f106991592452eb">715</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#af618114530371cf25f106991592452eb">m_majorVersion</a> = 1;</span></span></div>

</div>


<p>Referenced by <a href="#a75f8b4ee2ad4de9bf624c5427ce75fae">majorVersion</a> and <a href="#ae1e94d4f205f79a8b052e4140d575cb9">startLayout</a>.</p>

</div>
</div>

### m\_minorVersion {#a67669eb35ad908dd62d9e3adc8b8dd51}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LayoutParser::m_minorVersion = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 716 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a67669eb35ad908dd62d9e3adc8b8dd51">716</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a67669eb35ad908dd62d9e3adc8b8dd51">m_minorVersion</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#a9883cc99cb60a2b4c3c4135521ddc12c">minorVersion</a> and <a href="#ae1e94d4f205f79a8b052e4140d575cb9">startLayout</a>.</p>

</div>
</div>

### m\_part {#aeca69df11998a1fa5043e1de0387b56f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutDocManager::LayoutPart LayoutParser::m_part = LayoutDocManager::Undefined</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 709 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aeca69df11998a1fa5043e1de0387b56f">709</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/layoutdocmanager/#aee13a925ea1f915c542ecd7f579ebc94">LayoutDocManager::LayoutPart</a> <a href="#aeca69df11998a1fa5043e1de0387b56f">m_part</a> = LayoutDocManager::Undefined;</span></span></div>

</div>


<p>Referenced by <a href="#a8a6bfc037293b6fb0178f1c51c257b06">endMemberDecl</a>, <a href="#a959b2ab0ecbb71a6f7c9f8ee87a36a2a">endMemberDef</a>, <a href="#a19d81b682415be8d632795f5a0572a5c">endTop</a>, <a href="#a80ec53b42b990b7291e15d55351e1921">startMemberDecl</a>, <a href="#afcd6c1e555f2bc462f5703468b23c3d8">startMemberDeclEntry</a>, <a href="#abf6e0ed11a67228356030bafc743c57f">startMemberDef</a>, <a href="#a159d9ffd0d6742275e763d2bb25ae3f0">startMemberDefEntry</a>, <a href="#a3a78c06f8d054ac9c9b0b210d243f9b6">startSectionEntry</a>, <a href="#a300bf87a1f25049f900cabbf39921714">startSimpleEntry</a> and <a href="#a63da49c04af1554c5205a7c8fd4831b6">startTop</a>.</p>

</div>
</div>

### m\_rootNav {#ae0622ae2c94c9380801ebabe0248c6b3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">LayoutNavEntry* LayoutParser::m_rootNav = nullptr</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 710 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae0622ae2c94c9380801ebabe0248c6b3">710</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/layoutnaventry">LayoutNavEntry</a> *<a href="#ae0622ae2c94c9380801ebabe0248c6b3">m_rootNav</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a9f6db63ad970b43690ec22a4558aaea7">endNavEntry</a>, <a href="#a245cae7606ecd9bd4ee135b802b030d2">endNavIndex</a>, <a href="#aba3b3876764867eeb32b9dcce3d4b63b">startNavEntry</a> and <a href="#a314407ef719f76e868dab2366d52b036">startNavIndex</a>.</p>

</div>
</div>

### m\_scope {#a03ed81aca66391771e47ecaad3b4302a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString LayoutParser::m_scope</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 707 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a03ed81aca66391771e47ecaad3b4302a">707</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a03ed81aca66391771e47ecaad3b4302a">m_scope</a>;</span></span></div>

</div>


<p>Referenced by <a href="#acbe58d70dfdb7b82544b3c6390a3ffa9">endElement</a>, <a href="#a8a6bfc037293b6fb0178f1c51c257b06">endMemberDecl</a>, <a href="#a959b2ab0ecbb71a6f7c9f8ee87a36a2a">endMemberDef</a>, <a href="#a245cae7606ecd9bd4ee135b802b030d2">endNavIndex</a>, <a href="#a19d81b682415be8d632795f5a0572a5c">endTop</a>, <a href="#aec3d26d68ff653ee286a16533ba98560">startElement</a>, <a href="#a80ec53b42b990b7291e15d55351e1921">startMemberDecl</a>, <a href="#abf6e0ed11a67228356030bafc743c57f">startMemberDef</a>, <a href="#a314407ef719f76e868dab2366d52b036">startNavIndex</a> and <a href="#a63da49c04af1554c5205a7c8fd4831b6">startTop</a>.</p>

</div>
</div>

### m\_visible {#ac47b5d26e217722c25c9a728a7dce55c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool LayoutParser::m_visible = true</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 712 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac47b5d26e217722c25c9a728a7dce55c">712</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#ac47b5d26e217722c25c9a728a7dce55c">m_visible</a> = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>

</div>


<p>Referenced by <a href="#a80ec53b42b990b7291e15d55351e1921">startMemberDecl</a>, <a href="#afcd6c1e555f2bc462f5703468b23c3d8">startMemberDeclEntry</a>, <a href="#abf6e0ed11a67228356030bafc743c57f">startMemberDef</a>, <a href="#a159d9ffd0d6742275e763d2bb25ae3f0">startMemberDefEntry</a>, <a href="#aba3b3876764867eeb32b9dcce3d4b63b">startNavEntry</a>, <a href="#a3a78c06f8d054ac9c9b0b210d243f9b6">startSectionEntry</a>, <a href="#a300bf87a1f25049f900cabbf39921714">startSimpleEntry</a> and <a href="#a63da49c04af1554c5205a7c8fd4831b6">startTop</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Static Attributes

### m\_userGroupCount {#a280d75b3f9fd09d4cace0bc11c78c18e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int LayoutParser::m_userGroupCount =0</td>
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



<p>Definition at line 713 of file <a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a280d75b3f9fd09d4cace0bc11c78c18e">713</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a280d75b3f9fd09d4cace0bc11c78c18e">m_userGroupCount</a>;</span></span></div>

</div>


<p>Referenced by <a href="#aba3b3876764867eeb32b9dcce3d4b63b">startNavEntry</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/layout-cpp">layout.cpp</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
