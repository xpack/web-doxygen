---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/tagreader-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `tagreader.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/tagreader-h">tagreader.h</a>"
#include &lt;map&gt;
#include &lt;functional&gt;
#include &lt;utility&gt;
#include &lt;algorithm&gt;
#include &lt;variant&gt;
#include &lt;assert.h&gt;
#include &lt;stdio.h&gt;
#include &lt;stdarg.h&gt;
#include "<a href="/web-doxygen/docs/api/files/libxml/xml-h">xml.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/entry-h">entry.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/defargs-h">defargs.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filename-h">filename.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/containers-h">containers.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>"
</div>

## Namespaces Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">namespace</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/namespaces/anonymous-tagreader-cpp-">anonymous{tagreader.cpp}</a></td>
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

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/taganchorinfo">TagAnchorInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Information about an linkable anchor. <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/taganchorinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagenumvalueinfo">TagEnumValueInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for enum values that are scoped within an enum. <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagenumvalueinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagincludeinfo">TagIncludeInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for include info that can be read from a tagfile. <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagincludeinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagmemberinfo">TagMemberInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for member specific info that can be read from a tagfile. <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagmemberinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo">TagCompoundInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Base class for all compound types. <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagcompoundinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo">TagClassInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for class specific info that can be read from a tagfile. <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagclassinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagconceptinfo">TagConceptInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for concept specific info that can be read from a tagfile. <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagconceptinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagmoduleinfo">TagModuleInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for module specific info that can be read from a tagfile. <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagmoduleinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo">TagNamespaceInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for namespace specific info that can be read from a tagfile. <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagnamespaceinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpackageinfo">TagPackageInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for package specific info that can be read from a tagfile. <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpackageinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo">TagFileInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for file specific info that can be read from a tagfile. <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo">TagGroupInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for group specific info that can be read from a tagfile. <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/taggroupinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo">TagPageInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for page specific info that can be read from a tagfile. <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagpageinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo">TagDirInfo</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Container for directory specific info that can be read from a tagfile. <a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagdirinfo/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant">TagCompoundVariant</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Variant class that holds a unique pointer to one of the specific container types. <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagcompoundvariant/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser">TagFileParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Tag file parser. <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/tagfileparser/classnode">ClassNode</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/elementcallbacks">ElementCallbacks</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">struct</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/anonymous-namespace-tagreader-cpp-/compoundfactory">CompoundFactory</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a> (const std::shared_ptr&lt; Entry &gt; &amp;root, const char *fullName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae5b3a55c16d6fcd320b824837e28e42a">p_warn</a>(fmt, ...)&nbsp;&nbsp;&nbsp;...</td>
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

### parseTagFile() {#a1cb67a3965d52e8078507f0bfd354337}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void parseTagFile (const std::shared_ptr&lt; <a href="/web-doxygen/docs/api/classes/entry">Entry</a> &gt; &amp; root, const char * fullName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1864 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1cb67a3965d52e8078507f0bfd354337">1864</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1cb67a3965d52e8078507f0bfd354337">parseTagFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::shared_ptr&lt;Entry&gt; &amp;root,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *fullName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1865</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1866</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a43f4ea41f01f767ade7898b8d69d0f43">TagFileParser</a> tagFileParser(fullName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1867</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> inputStr = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>(fullName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1868</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/xmlhandlers">XMLHandlers</a> handlers;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1869</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// connect the generic events handlers of the XML parser to the specific handlers of the tagFileParser object</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1870</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#ae666b94024ae82743cc7b8ae6445e684">startDocument</a> = [&amp;tagFileParser]()                                                              { tagFileParser.startDocument(); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1871</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#a75b4fb2c24bd41404fe59c31a6dbd493">startElement</a>  = [&amp;tagFileParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a15cedeea046e36465580e5654121387e">XMLHandlers::Attributes</a> &amp;attrs)  { tagFileParser.startElement(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(name),attrs); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1872</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#a623bc48085a8ced78c3202713a24724e">endElement</a>    = [&amp;tagFileParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;name)                                       { tagFileParser.endElement(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(name)); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1873</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#a895a088f5352bced5cf6a998da7fc06a">characters</a>    = [&amp;tagFileParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;chars)                                      { tagFileParser.characters(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(chars)); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1874</span><span class="doxyLineContent"><span class="doxyHighlight">  handlers.<a href="/web-doxygen/docs/api/classes/xmlhandlers/#adf5e4d9f4927edb0fb5d1259a4da9960">error</a>         = [&amp;tagFileParser](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>) { tagFileParser.error(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(fileName),lineNr,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(<a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>)); };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1875</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/xmlparser">XMLParser</a> parser(handlers);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1876</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFileParser.setDocumentLocator(&amp;parser);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1877</span><span class="doxyLineContent"><span class="doxyHighlight">  parser.<a href="/web-doxygen/docs/api/classes/xmlparser/#ad9b0a380760223431fbb84d35a8f12e9">parse</a>(fullName,inputStr.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Debug::Lex_xml</a>),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1878</span><span class="doxyLineContent"><span class="doxyHighlight">               [&amp;]() { DebugLex::print(Debug::Lex_xml,</span><span class="doxyHighlightStringLiteral">"Entering"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">"libxml/xml.l"</span><span class="doxyHighlight">,fullName); },</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1879</span><span class="doxyLineContent"><span class="doxyHighlight">               [&amp;]() { DebugLex::print(Debug::Lex_xml,</span><span class="doxyHighlightStringLiteral">"Finished"</span><span class="doxyHighlight">, </span><span class="doxyHighlightStringLiteral">"libxml/xml.l"</span><span class="doxyHighlight">,fullName); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1880</span><span class="doxyLineContent"><span class="doxyHighlight">              );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1881</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFileParser.buildLists(root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1882</span><span class="doxyLineContent"><span class="doxyHighlight">  tagFileParser.addIncludes();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1883</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1884</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1885</span><span class="doxyLineContent"><span class="doxyHighlight">    tagFileParser.dump();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1886</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1887</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a895a088f5352bced5cf6a998da7fc06a">XMLHandlers::characters</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a623bc48085a8ced78c3202713a24724e">XMLHandlers::endElement</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#adf5e4d9f4927edb0fb5d1259a4da9960">XMLHandlers::error</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a71d0079fa5936a41b6ff2d1ca5eb5480">fileToString</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daa212cad6fd21d6eb9f0cbc82c1a14e97">Debug::Lex\_xml</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/classes/xmlparser/#ad9b0a380760223431fbb84d35a8f12e9">XMLParser::parse</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#ae666b94024ae82743cc7b8ae6445e684">XMLHandlers::startDocument</a>, <a href="/web-doxygen/docs/api/classes/xmlhandlers/#a75b4fb2c24bd41404fe59c31a6dbd493">XMLHandlers::startElement</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da533ce7b02d8ce4b77e168009734b13d9">Debug::Tag</a> and <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a43f4ea41f01f767ade7898b8d69d0f43">anonymous\_namespace{tagreader.cpp}::TagFileParser::TagFileParser</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a7389d7a8c7a2859d36b88ff0dc477cdb">readTagFile</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### p\_warn {#ae5b3a55c16d6fcd320b824837e28e42a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define p_warn(fmt, ...)&nbsp;&nbsp;&nbsp;...</td>
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
<div class="doxyVerbatim">     do {                                             \
     <a href="/web-doxygen/docs/api/files/src/message-h/#a85b390806d83bbaeb7d12383001c0dfb">warn</a>(m_locator-&gt;fileName(),m_locator-&gt;lineNr(),fmt,##__VA_ARGS__);  \
   } while(0)
</div>
</dd>
</dl>

Definition at line 330 of file <a href="/web-doxygen/docs/api/files/src/tagreader-cpp">tagreader.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae5b3a55c16d6fcd320b824837e28e42a">330</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define p_warn(fmt,...) do {                                             \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">     warn(m_locator-&gt;fileName(),m_locator-&gt;lineNr(),fmt,##__VA_ARGS__);  \</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">   } while(0)</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a9a2a4b0accaef9069229937226e60b10">anonymous\_namespace{tagreader.cpp}::TagFileParser::buildLists</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a42aff7a35ce87a4df59d4a05f374f54e">anonymous\_namespace{tagreader.cpp}::TagFileParser::endAnchor</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a898f929ad250f095d46ce638e8fce78a">anonymous\_namespace{tagreader.cpp}::TagFileParser::endAnchorFile</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a005718bfd790617c0cf8b3ab0c86a6c3">anonymous\_namespace{tagreader.cpp}::TagFileParser::endArglist</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a1ac7de66e90ffbf93cd637c67c7cc76c">anonymous\_namespace{tagreader.cpp}::TagFileParser::endBase</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#ab27d1e74556a11f12e2d6a3b0dfa1225">anonymous\_namespace{tagreader.cpp}::TagFileParser::endClangId</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#ab0af5855a848b20e3136d941d7840732">anonymous\_namespace{tagreader.cpp}::TagFileParser::endClass</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a3e0857519c95a2ab4f2649588f52b244">anonymous\_namespace{tagreader.cpp}::TagFileParser::endCompound</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a88c616e8f2d519406f88102cf9913811">anonymous\_namespace{tagreader.cpp}::TagFileParser::endConcept</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#af120fd7d4ed4df2d800e4a531152728d">anonymous\_namespace{tagreader.cpp}::TagFileParser::endDir</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a5b2c9b8ab174e898f87b90803529766c">anonymous\_namespace{tagreader.cpp}::TagFileParser::endDocAnchor</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a3e01aed32d5dbf43b922e4152b65b54f">anonymous\_namespace{tagreader.cpp}::TagFileParser::endElement</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a34e5a973da1491d711704a2ee6ee8ae0">anonymous\_namespace{tagreader.cpp}::TagFileParser::endFile</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#acb8e913e38db3f6aa9c1bbb9a641a17f">anonymous\_namespace{tagreader.cpp}::TagFileParser::endFilename</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a18f64ce17ad437b8675f4bd7b9f8a974">anonymous\_namespace{tagreader.cpp}::TagFileParser::endIncludes</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#afce64693b86203b0106f25a6697a8076">anonymous\_namespace{tagreader.cpp}::TagFileParser::endMember</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#aa0c63ea4440394d9c1089cc804f6b3cb">anonymous\_namespace{tagreader.cpp}::TagFileParser::endModule</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#af5d579a5b02bb8153e8be2ffe25d2b90">anonymous\_namespace{tagreader.cpp}::TagFileParser::endName</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a5f364b44aa47f45ead81e1892359c3ee">anonymous\_namespace{tagreader.cpp}::TagFileParser::endNamespace</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a40b954bb215265f9d331f673102f8e11">anonymous\_namespace{tagreader.cpp}::TagFileParser::endPage</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a8020f9f5e883fd98854ac72e4e6e776d">anonymous\_namespace{tagreader.cpp}::TagFileParser::endPath</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#ab01b451a3fc33322e98c40bd5cca5878">anonymous\_namespace{tagreader.cpp}::TagFileParser::endSubgroup</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a6fd29da85de1ed3faf625ee0d27122ae">anonymous\_namespace{tagreader.cpp}::TagFileParser::endSubpage</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a942847def781fe793b9bf3b1a7179c3f">anonymous\_namespace{tagreader.cpp}::TagFileParser::endTemplateArg</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#aa6e06a88bac03298d1b7b1d960786089">anonymous\_namespace{tagreader.cpp}::TagFileParser::endTitle</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a1f6885619a9e437468650af93b8f05f3">anonymous\_namespace{tagreader.cpp}::TagFileParser::endType</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a6927f64d6b3e45878b5102852e1e2fac">anonymous\_namespace{tagreader.cpp}::TagFileParser::startBase</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#ab17fadda7f7d30dce3d68f186aaed55d">anonymous\_namespace{tagreader.cpp}::TagFileParser::startCompound</a>, <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#a487b3d40047a75c0612f66ab78f61d96">anonymous\_namespace{tagreader.cpp}::TagFileParser::startElement</a> and <a href="/web-doxygen/docs/api/classes/anonymous-namespace-tagreader-cpp-/tagfileparser/#afc3a2293108d7a644b0c57ad06f29c11">anonymous\_namespace{tagreader.cpp}::TagFileParser::startEnumValue</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
