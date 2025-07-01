---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/definition-cpp
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `definition.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;algorithm&gt;
#include &lt;iterator&gt;
#include &lt;unordered_map&gt;
#include &lt;string&gt;
#include &lt;optional&gt;
#include &lt;cctype&gt;
#include &lt;cstdio&gt;
#include &lt;cstdlib&gt;
#include &lt;cassert&gt;
#include "<a href="/web-doxygen/docs/api/files/src/anchor-h">anchor.h</a>"
#include "md5.h"
#include "<a href="/web-doxygen/docs/api/files/src/regex-h">regex.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/definitionimpl-h">definitionimpl.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/language-h">language.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/outputlist-h">outputlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/code-h">code.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/pagedef-h">pagedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htags-h">htags.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/debug-h">debug.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/vhdldocgen-h">vhdldocgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/reflist-h">reflist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/utf8-h">utf8.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/indexlist-h">indexlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/fileinfo-h">fileinfo.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definitionimpl/private">Private</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<a href="/web-doxygen/docs/api/classes/definitionimpl/private">Private</a> data associated with a Symbol <a href="/web-doxygen/docs/api/classes/definitionimpl">DefinitionImpl</a> object. <a href="/web-doxygen/docs/api/classes/definitionimpl/private/#details">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/filtercache">FilterCache</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/filtercache/filtercacheitem">FilterCacheItem</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a> (const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a29d1f8fcda9166d21abaf8d785c378c5">addToMap</a> (const QCString &amp;name, Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a19333e44397bbe89c9c283e0b1181f86">removeFromMap</a> (const QCString &amp;name, Definition *d)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a> (const QCString &amp;fileName, bool isMacro, int &amp;startLine, int &amp;endLine, QCString &amp;result)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
Reads a fragment from file <em>fileName</em> starting with line <em>startLine</em> and ending with line <em>endLine</em>. <a href="#a1b30645f1030c1ee4b259526cf6d46a7">More...</a>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae91eb6342041a59b5b4f4fc916d6ffe5">refMapToVector</a> (const std::unordered_map&lt; std::string, MemberDef * &gt; &amp;map)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af14d495cc8aa43bd9a23c357e56b4454">stripWord</a> (QCString &amp;s, QCString w)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a> (const QCString &amp;s, const QCString &amp;name)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definition">Definition</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab43e817b86eeee8909980167d1a140c8">toDefinition</a> (DefinitionMutable *dm)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afe6bb7de7547134d0e29feddc1f894d7">toDefinitionMutable</a> (Definition *d)</td>
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

## Variables Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::recursive_mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef4f117a1f0f6eebcd68a693dce76a24">g_qualifiedNameMutex</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static std::mutex</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0bc92abff18d90b3f61f3a59d2540316">g_memberReferenceMutex</a></td>
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

### abbreviate() {#a73a802f4c5838f2ebe51f19aa9c2d8ea}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString abbreviate (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 1547 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73a802f4c5838f2ebe51f19aa9c2d8ea">1547</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1548</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1549</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> scopelessName=name;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1550</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=scopelessName.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1551</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1) scopelessName=scopelessName.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(i+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1552</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result=s;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1553</span><span class="doxyLineContent"><span class="doxyHighlight">  result=result.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1554</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// strip trailing .</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1555</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!result.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; result.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1)==</span><span class="doxyHighlightCharLiteral">'.'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1556</span><span class="doxyLineContent"><span class="doxyHighlight">    result=result.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1557</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1558</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// strip any predefined prefix</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1559</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;briefDescAbbrev = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(ABBREVIATE_BRIEF);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1560</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;p : briefDescAbbrev)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1561</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1562</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> str = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(p.c_str(),</span><span class="doxyHighlightStringLiteral">"$name"</span><span class="doxyHighlight">,scopelessName); </span><span class="doxyHighlightComment">// replace $name with entity name</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1563</span><span class="doxyLineContent"><span class="doxyHighlight">    str += </span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1564</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af14d495cc8aa43bd9a23c357e56b4454">stripWord</a>(result,str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1565</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1566</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1567</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// capitalize first word</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1568</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!result.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1569</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1570</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=result[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1571</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c&gt;=</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; c&lt;=</span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">) c+=</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight">-</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1572</span><span class="doxyLineContent"><span class="doxyHighlight">    result[0]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1573</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1574</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1575</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config\_getList</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a>, <a href="#af14d495cc8aa43bd9a23c357e56b4454">stripWord</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definition/#a8ca2bb51665eab1ffd981a38c2b5f188">Definition::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definitionaliasmixin/#ae275169a9c2d3322467308254d1a4d0a">DefinitionAliasMixin&lt; Base &gt;::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#aaec58f963ba447a3a6a1b36c0310d1f3">DefinitionImpl::briefDescription</a>, <a href="/web-doxygen/docs/api/classes/definitionmixin/#a7dc1bbded3ac0ed218fff164f1da0504">DefinitionMixin&lt; Base &gt;::briefDescription</a> and <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6006a1443e18366206b8485ee2d7b8a3">DefinitionImpl::operator=</a>.
</div>
</div>

### addToMap() {#a29d1f8fcda9166d21abaf8d785c378c5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addToMap (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
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



Definition at line 212 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a29d1f8fcda9166d21abaf8d785c378c5">212</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a29d1f8fcda9166d21abaf8d785c378c5">addToMap</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/classes/definitionimpl/#aa16d39d8b97162b87d1af3916babf7b5">name</a>,<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> vhdlOpt = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(OPTIMIZE_OUTPUT_VHDL);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="/web-doxygen/docs/api/classes/definitionimpl/#a5a924b79bfc06f3d12eeab5fb35168b6">symbolName</a> = <a href="/web-doxygen/docs/api/classes/definitionimpl/#aa16d39d8b97162b87d1af3916babf7b5">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> index=<a href="/web-doxygen/docs/api/files/src/util-cpp/#a84e80a5dfaa2db05ad8b5d2e8d0f58f7">computeQualifiedIndex</a>(<a href="/web-doxygen/docs/api/classes/definitionimpl/#a5a924b79bfc06f3d12eeab5fb35168b6">symbolName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!vhdlOpt &amp;&amp; index!=-1) <a href="/web-doxygen/docs/api/classes/definitionimpl/#a5a924b79bfc06f3d12eeab5fb35168b6">symbolName</a>=<a href="/web-doxygen/docs/api/classes/definitionimpl/#a5a924b79bfc06f3d12eeab5fb35168b6">symbolName</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(index+2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/definitionimpl/#a5a924b79bfc06f3d12eeab5fb35168b6">symbolName</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("adding symbol %s\n",qPrint(symbolName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>-&gt;add(<a href="/web-doxygen/docs/api/classes/definitionimpl/#a5a924b79bfc06f3d12eeab5fb35168b6">symbolName</a>,d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">    d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ab0059012da8842e6a1768b0448f32867">_setSymbolName</a>(<a href="/web-doxygen/docs/api/classes/definitionimpl/#a5a924b79bfc06f3d12eeab5fb35168b6">symbolName</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definition/#ab0059012da8842e6a1768b0448f32867">Definition::\_setSymbolName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a84e80a5dfaa2db05ad8b5d2e8d0f58f7">computeQualifiedIndex</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#aa16d39d8b97162b87d1af3916babf7b5">DefinitionImpl::name</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a> and <a href="/web-doxygen/docs/api/classes/definitionimpl/#a5a924b79bfc06f3d12eeab5fb35168b6">DefinitionImpl::symbolName</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a11dbc9f8f8f95b07b88d38c3d311b1d5">DefinitionImpl::DefinitionImpl</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#afa510f0e0d64789d3b98a0cf4968d494">DefinitionImpl::DefinitionImpl</a> and <a href="/web-doxygen/docs/api/classes/definitionaliasimpl/#ac8f280c992abc7b4cc4b47cb31a5c383">DefinitionAliasImpl::init</a>.
</div>
</div>

### matchExcludedSymbols() {#a4af6f5bd4b9fd624dd2c2a8c410fc9cf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool matchExcludedSymbols (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
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



Definition at line 157 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">157</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4af6f5bd4b9fd624dd2c2a8c410fc9cf">matchExcludedSymbols</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/classes/definitionimpl/#aa16d39d8b97162b87d1af3916babf7b5">name</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;exclSyms = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(EXCLUDE_SYMBOLS);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (exclSyms.empty()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>; </span><span class="doxyHighlightComment">// nothing specified</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string symName = <a href="/web-doxygen/docs/api/classes/definitionimpl/#aa16d39d8b97162b87d1af3916babf7b5">name</a>.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pat : exclSyms)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> pattern = pat.c_str();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> forceStart=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> forceEnd=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0)==</span><span class="doxyHighlightCharLiteral">'^'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">      pattern=pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(1),forceStart=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1)==</span><span class="doxyHighlightCharLiteral">'$'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">      pattern=pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1),forceEnd=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">)!=-1) </span><span class="doxyHighlightComment">// wildcard mode</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re(<a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(pattern,</span><span class="doxyHighlightStringLiteral">"*"</span><span class="doxyHighlight">,</span><span class="doxyHighlightStringLiteral">".*"</span><span class="doxyHighlight">).str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(symName,match,re)) </span><span class="doxyHighlightComment">// wildcard match</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ui = match.position();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pl = match.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> sl = symName.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((ui==0     || pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(0)==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">                  || (!<a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(symName.at(ui-1))  &amp;&amp; !forceStart)) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">            (ui+pl==sl || pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1)==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight"> || (!<a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(symName.at(ui+pl)) &amp;&amp; !forceEnd))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">           )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("--&gt; name=%s pattern=%s match at %d\n",qPrint(symName),qPrint(pattern),i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightComment">// match words</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i = symName.find(pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=std::string::npos) </span><span class="doxyHighlightComment">// we have a match!</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ui=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> pl=pattern.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> sl=symName.length();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// check if it is a whole word match</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((ui==0     || (!<a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(symName.at(ui-1))  &amp;&amp; !forceStart)) &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">            (ui+pl==sl || (!<a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>(symName.at(ui+pl)) &amp;&amp; !forceEnd))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">           )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">//printf("--&gt; name=%s pattern=%s match at %d\n",qPrint(symName),qPrint(pattern),i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("--&gt; name=%s: no match\n",name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config\_getList</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/files/src/util-h/#ae320c88a8522836f00095d566529046f">isId</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#aa16d39d8b97162b87d1af3916babf7b5">DefinitionImpl::name</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#afa510f0e0d64789d3b98a0cf4968d494">DefinitionImpl::DefinitionImpl</a>.
</div>
</div>

### readCodeFragment() {#a1b30645f1030c1ee4b259526cf6d46a7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool readCodeFragment (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, bool isMacro, int &amp; startLine, int &amp; endLine, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; result)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

Reads a fragment from file <em>fileName</em> starting with line <em>startLine</em> and ending with line <em>endLine</em>.


Reads a fragment of code from file <em>fileName</em> starting at line <em>startLine</em> and ending at line <em>endLine</em> (inclusive). The fragment is stored in <em>result</em>. If FALSE is returned the code fragment could not be found.

The file is scanned for a opening bracket ('{') from <em>startLine</em> onward The line actually containing the bracket is returned via startLine. The file is scanned for a closing bracket ('}') from <em>endLine</em> backward. The line actually containing the bracket is returned via endLine. Note that for VHDL code the bracket search is not done.

Definition at line 749 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1b30645f1030c1ee4b259526cf6d46a7">749</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a1b30645f1030c1ee4b259526cf6d46a7">readCodeFragment</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isMacro,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;startLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;endLine,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;result)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> filterSourceFiles = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FILTER_SOURCE_FILES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> filter = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad4426e053bb11589c58bd5c6828817e2">getFileFilter</a>(fileName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> usePipe = !filter.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; filterSourceFiles;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> tabSize = <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(TAB_SIZE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> blockSize = 4096;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string str;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/filtercache/#a75634f3ff0bcd32cd82ba3d0fc8afbb3">FilterCache::instance</a>().<a href="/web-doxygen/docs/api/classes/filtercache/#aa5d001d30e4d16855d3656989947df29">getFileContents</a>(fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(std::max(1,startLine)),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">761</span><span class="doxyLineContent"><span class="doxyHighlight">                                          </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(std::max({1,startLine,endLine})),str);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">762</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("readCodeFragment(%s,startLine=%d,endLine=%d)=\n[[[\n%s]]]\n",qPrint(fileName),startLine,endLine,qPrint(str));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found = lang==SrcLangExt::VHDL   ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">               lang==SrcLangExt::Python ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">               lang==SrcLangExt::Fortran ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">               isMacro;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">               </span><span class="doxyHighlightComment">// for VHDL, Python, and Fortran no bracket search is possible</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p=str.data();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p &amp;&amp; *p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">773</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> col=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">774</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr=startLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// skip until the opening bracket or lonely : is found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> cn=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p &amp;&amp; !found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pc=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++)!=</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight"> &amp;&amp; c!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight"> &amp;&amp; c!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("parsing char '%c'\n",c);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">785</span><span class="doxyLineContent"><span class="doxyHighlight">          lineNr++,col=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">786</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">787</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">788</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">          col+=tabSize - (col%tabSize);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pc==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> &amp;&amp; c==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip single line comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">793</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p++)!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight"> &amp;&amp; c!=0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">794</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) lineNr++,col=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pc==</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> &amp;&amp; c==</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// skip C style comment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (((c=*p++)!=</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight"> || pc!=</span><span class="doxyHighlightCharLiteral">'*'</span><span class="doxyHighlight">) &amp;&amp; c!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) lineNr++,col=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">            pc=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">806</span><span class="doxyLineContent"><span class="doxyHighlight">          col++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">807</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">808</span><span class="doxyLineContent"><span class="doxyHighlight">        pc = c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">809</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">810</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">811</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">812</span><span class="doxyLineContent"><span class="doxyHighlight">        cn=*p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">813</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cn!=</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">) found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">814</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'{'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">        found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf(" -&gt; readCodeFragment(%s,%d,%d) lineNr=%d\n",fileName,startLine,endLine,lineNr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (found)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// For code with more than one line,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// fill the line with spaces until we are at the right column</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// so that the opening brace lines up with the closing brace</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (endLine!=startLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> spaces;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">        spaces.<a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">fill</a>(</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">,col);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=spaces;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// copy until end of line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c) result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">      startLine=lineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">840</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">841</span><span class="doxyLineContent"><span class="doxyHighlight">        result+=cn;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">842</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cn==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) lineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">843</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">844</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> lineStr[blockSize];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">845</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">do</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">846</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">847</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("reading line %d in range %d-%d\n",lineNr,startLine,endLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">848</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> size_read=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">849</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">do</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">850</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">851</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightComment">// read up to blockSize-1 non-zero characters</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">852</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">853</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((c=*p) &amp;&amp; i&lt;blockSize-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">854</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">855</span><span class="doxyLineContent"><span class="doxyHighlight">            lineStr[i++]=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">856</span><span class="doxyLineContent"><span class="doxyHighlight">            p++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">857</span><span class="doxyLineContent"><span class="doxyHighlight">            </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// stop at end of the line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">858</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">859</span><span class="doxyLineContent"><span class="doxyHighlight">          lineStr[i]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">860</span><span class="doxyLineContent"><span class="doxyHighlight">          size_read=i;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">861</span><span class="doxyLineContent"><span class="doxyHighlight">          result+=lineStr; </span><span class="doxyHighlightComment">// append line to the output</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">862</span><span class="doxyLineContent"><span class="doxyHighlight">        } </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (size_read == (blockSize-1)); </span><span class="doxyHighlightComment">// append more if line does not fit in buffer</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">863</span><span class="doxyLineContent"><span class="doxyHighlight">        lineNr++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">864</span><span class="doxyLineContent"><span class="doxyHighlight">      } </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">865</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">866</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// strip stuff after closing bracket</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">867</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> newLineIndex = result.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">868</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> braceIndex   = result.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'}'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">869</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (braceIndex &gt; newLineIndex)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">870</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">871</span><span class="doxyLineContent"><span class="doxyHighlight">        result.<a href="/web-doxygen/docs/api/classes/qcstring/#a747c587f5fee7b891e52909aa309323e">resize</a>(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(braceIndex+1));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">872</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">873</span><span class="doxyLineContent"><span class="doxyHighlight">      endLine=lineNr-1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">874</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">875</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (usePipe)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">876</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">877</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5e47cf9df9552fe30480288b70288d72">Debug::FilterOutput</a>, 0, </span><span class="doxyHighlightStringLiteral">"Filter output\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">878</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5e47cf9df9552fe30480288b70288d72">Debug::FilterOutput</a>,0,</span><span class="doxyHighlightStringLiteral">"-------------\n{}\n-------------\n"</span><span class="doxyHighlight">,result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">879</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">880</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">881</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> encoding = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac369a1df025c6505f067a880d197d8d8">getEncoding</a>(<a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a>(fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">882</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (encoding!=</span><span class="doxyHighlightStringLiteral">"UTF-8"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">883</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">884</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string encBuf = result.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">885</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> ok = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a>(encBuf,encoding.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">886</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ok)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">887</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">888</span><span class="doxyLineContent"><span class="doxyHighlight">      result = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(encBuf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">889</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">890</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">891</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">892</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"failed to transcode characters in code fragment in file {} lines {} to {}, from input encoding {} to UTF-8\n"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">893</span><span class="doxyLineContent"><span class="doxyHighlight">          fileName,startLine,endLine,encoding);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">894</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">895</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">896</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">897</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!result.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() &amp;&amp; result.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(result.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1)!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) result += </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">898</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("readCodeFragment(%d-%d)=%s\n",startLine,endLine,qPrint(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">899</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> found;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">900</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config\_getInt</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a08003d3e6c9acc46e4d392612ba492f7">QCString::fill</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da5e47cf9df9552fe30480288b70288d72">Debug::FilterOutput</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ac369a1df025c6505f067a880d197d8d8">getEncoding</a>, <a href="/web-doxygen/docs/api/classes/filtercache/#aa5d001d30e4d16855d3656989947df29">FilterCache::getFileContents</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad4426e053bb11589c58bd5c6828817e2">getFileFilter</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/filtercache/#a75634f3ff0bcd32cd82ba3d0fc8afbb3">FilterCache::instance</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a747c587f5fee7b891e52909aa309323e">QCString::resize</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a5030d1ce0680325d5a1fa0d7a36448c5">transcodeCharacterStringToUTF8</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/vhdldocgen/#a2de08afddfa24b4a037c36ac329185ff">VhdlDocGen::createFlowChart</a>, <a href="/web-doxygen/docs/api/classes/definitionmutable/#a648211c215471d74b9b7330c856bce35">DefinitionMutable::toDefinition\_</a> and <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6bab634f62d558e8d56cb84dee170cd2">DefinitionImpl::writeInlineCode</a>.
</div>
</div>

### refMapToVector() {#ae91eb6342041a59b5b4f4fc916d6ffe5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">MemberVector refMapToVector (const std::unordered_map&lt; std::string, <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * &gt; &amp; map)</td>
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



Definition at line 1061 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae91eb6342041a59b5b4f4fc916d6ffe5">1061</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a> <a href="#ae91eb6342041a59b5b4f4fc916d6ffe5">refMapToVector</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::unordered_map&lt;std::string,MemberDef *&gt; &amp;map)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1062</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1063</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// convert map to a vector of values</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1064</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/membervector">MemberVector</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1065</span><span class="doxyLineContent"><span class="doxyHighlight">  std::transform(map.begin(),map.end(),      </span><span class="doxyHighlightComment">// iterate over map</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1066</span><span class="doxyLineContent"><span class="doxyHighlight">                 std::back_inserter(result), </span><span class="doxyHighlightComment">// add results to vector</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1067</span><span class="doxyLineContent"><span class="doxyHighlight">                 [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;item)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1068</span><span class="doxyLineContent"><span class="doxyHighlight">                 { return item.second; }     </span><span class="doxyHighlightComment">// extract value to add from map Key,Value pair</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1069</span><span class="doxyLineContent"><span class="doxyHighlight">                );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1070</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// and sort it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1071</span><span class="doxyLineContent"><span class="doxyHighlight">  std::stable_sort(result.<a href="/web-doxygen/docs/api/classes/membervector/#ae59b75a387fce804f30cbf31ea9c3297">begin</a>(),result.<a href="/web-doxygen/docs/api/classes/membervector/#ab51414ef16b6467930e5e6ea6865177b">end</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1072</span><span class="doxyLineContent"><span class="doxyHighlight">              [](</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;m1,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;m2) { return genericCompareMembers(m1,m2)&lt;0; });</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1073</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1074</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/membervector/#ae59b75a387fce804f30cbf31ea9c3297">MemberVector::begin</a> and <a href="/web-doxygen/docs/api/classes/membervector/#ab51414ef16b6467930e5e6ea6865177b">MemberVector::end</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a4fb272d2b927cc1073e7a9ac0f7c1751">DefinitionImpl::\_writeSourceRefList</a>, <a href="/web-doxygen/docs/api/classes/definitionimpl/#af761f68b4366152c5b242c9f1ccb847e">DefinitionImpl::getReferencedByMembers</a> and <a href="/web-doxygen/docs/api/classes/definitionimpl/#a65837eed1bdeb332615af6ea1fbad1cd">DefinitionImpl::getReferencesMembers</a>.
</div>
</div>

### removeFromMap() {#a19333e44397bbe89c9c283e0b1181f86}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void removeFromMap (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
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



Definition at line 227 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a19333e44397bbe89c9c283e0b1181f86">227</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a19333e44397bbe89c9c283e0b1181f86">removeFromMap</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;<a href="/web-doxygen/docs/api/classes/definitionimpl/#aa16d39d8b97162b87d1af3916babf7b5">name</a>,<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>-&gt;remove(<a href="/web-doxygen/docs/api/classes/definitionimpl/#aa16d39d8b97162b87d1af3916babf7b5">name</a>,d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definitionimpl/#aa16d39d8b97162b87d1af3916babf7b5">DefinitionImpl::name</a> and <a href="/web-doxygen/docs/api/classes/doxygen/#adcf907e4baf6aafe25d9a812c2f58e14">Doxygen::symbolMap</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/definitionaliasimpl/#ac69a03632c6a5af839e26c104329623f">DefinitionAliasImpl::deinit</a> and <a href="/web-doxygen/docs/api/classes/definitionimpl/#aa7e7868bd00eb4970333fc6da39aae39">DefinitionImpl::\~DefinitionImpl</a>.
</div>
</div>

### stripWord() {#af14d495cc8aa43bd9a23c357e56b4454}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool stripWord (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> w)</td>
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



Definition at line 1534 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af14d495cc8aa43bd9a23c357e56b4454">1534</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#af14d495cc8aa43bd9a23c357e56b4454">stripWord</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1535</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1536</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> success=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1537</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(w.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>())==w)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1538</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1539</span><span class="doxyLineContent"><span class="doxyHighlight">    success=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1540</span><span class="doxyLineContent"><span class="doxyHighlight">    s=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-w.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1541</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1542</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> success;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1543</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="#a73a802f4c5838f2ebe51f19aa9c2d8ea">abbreviate</a>.
</div>
</div>

### toDefinition() {#ab43e817b86eeee8909980167d1a140c8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Definition * toDefinition (<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> * dm)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1923 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/classes/definitionmutable/#ab43e817b86eeee8909980167d1a140c8">1923</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/definition">Definition</a> *<a href="#ab43e817b86eeee8909980167d1a140c8">toDefinition</a>(<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> *dm)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (dm==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> dm-&gt;<a href="/web-doxygen/docs/api/classes/definitionmutable/#a648211c215471d74b9b7330c856bce35">toDefinition_</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/definitionimpl/#a6f374f174ab36ce42c32a8ee1a2949a6">DefinitionImpl::docLine</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad0b372f3669056d6a88f41daeb3a3865">stripLeadingAndTrailingEmptyLines</a> and <a href="/web-doxygen/docs/api/files/src/stringutil-h/#aef47e534975880014a6514745e885a99">stripWhiteSpace</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acc3d9699d44f100227430700d7c62a68">buildScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac1850678fe273e83bcda397bc2f1b6ec">endFileWithNavPath</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a8cb9252694dc27b52bd30efe903f9654">findScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#a0c64550144b1c5be3dfa3e79ad1a2ac1">toClassDef</a>, <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#aef7eaf07a699cd7ef3d8286d9f44dcde">toConceptDef</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#aadf8d5c103d1bd6ff91c784f02ebe2dd">toMemberDef</a>, <a href="/web-doxygen/docs/api/files/src/namespacedef-cpp/#a11cdaa39ac25a83a376fa59f6b0a9cde">toNamespaceDef</a> and <a href="/web-doxygen/docs/api/classes/memberlist/#af29c795d264e74de8cc53f3d5c550d41">MemberList::writeDocumentationPage</a>.
</div>
</div>

### toDefinitionMutable() {#afe6bb7de7547134d0e29feddc1f894d7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefinitionMutable * toDefinitionMutable (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 1929 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/classes/definition/#afe6bb7de7547134d0e29feddc1f894d7">1929</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> *<a href="#afe6bb7de7547134d0e29feddc1f894d7">toDefinitionMutable</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a79aff03392a397ddc87e8147d10d5959">toDefinitionMutable_</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a71f923667206aac9e24848997edd6d8b">buildNamespaceList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acc3d9699d44f100227430700d7c62a68">buildScopeFromQualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#adc2cc0c0248747e3608de552a9947cfb">computeTooltipTexts</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad4d18463536d31e211957c9151fdbac2">createTagLessInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a34157df0fe53d6d10cc4560ca942f488">resolveClassNestingRelations</a> and <a href="/web-doxygen/docs/api/classes/definitionmutable/#a648211c215471d74b9b7330c856bce35">DefinitionMutable::toDefinition\_</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### g\_memberReferenceMutex {#a0bc92abff18d90b3f61f3a59d2540316}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::mutex g_memberReferenceMutex</td>
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



Definition at line 1718 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0bc92abff18d90b3f61f3a59d2540316">1718</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::mutex <a href="#a0bc92abff18d90b3f61f3a59d2540316">g_memberReferenceMutex</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#af761f68b4366152c5b242c9f1ccb847e">DefinitionImpl::getReferencedByMembers</a> and <a href="/web-doxygen/docs/api/classes/definitionimpl/#a65837eed1bdeb332615af6ea1fbad1cd">DefinitionImpl::getReferencesMembers</a>.
</div>
</div>

### g\_qualifiedNameMutex {#aef4f117a1f0f6eebcd68a693dce76a24}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::recursive_mutex g_qualifiedNameMutex</td>
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



Definition at line 1217 of file <a href="/web-doxygen/docs/api/files/src/definition-cpp">definition.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aef4f117a1f0f6eebcd68a693dce76a24">1217</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> std::recursive_mutex <a href="#aef4f117a1f0f6eebcd68a693dce76a24">g_qualifiedNameMutex</a>;</span></span></div>

</div>


Referenced by <a href="/web-doxygen/docs/api/classes/definitionimpl/#a62a24770cf13f60eb5eadedc59138565">DefinitionImpl::qualifiedName</a> and <a href="/web-doxygen/docs/api/classes/definitionimpl/#a5d1139c74f8fa368052a5707ec292eef">DefinitionImpl::setOuterScope</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
