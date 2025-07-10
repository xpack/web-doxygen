---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/perlmodgen-cpp
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `perlmodgen.cpp` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdlib.h&gt;
#include &lt;stack&gt;
#include "<a href="/web-doxygen/docs/api/files/src/perlmodgen-h">perlmodgen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/docnode-h">docnode.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/message-h">message.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/pagedef-h">pagedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/memberlist-h">memberlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/arguments-h">arguments.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/groupdef-h">groupdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classdef-h">classdef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/classlist-h">classlist.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filename-h">filename.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membername-h">membername.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/namespacedef-h">namespacedef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/membergroup-h">membergroup.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/section-h">section.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/util-h">util.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/htmlentity-h">htmlentity.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/emoji-h">emoji.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dir-h">dir.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/portable-h">portable.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/moduledef-h">moduledef.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/cite-h">cite.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/perlmodoutputstream">PerlModOutputStream</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/perlmodoutput">PerlModOutput</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/perlmoddocvisitor">PerlModDocVisitor</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Concrete visitor implementation for PerlMod output. <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/perlmodgenerator">PerlModGenerator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e2b9604ce397bbe6984cf81775f4fda">addTemplateArgumentList</a> (const ArgumentList &amp;al, PerlModOutput &amp;output, const QCString &amp;)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5375ce03d260026390f88a202e99fe33">addTemplateList</a> (const ClassDef *cd, PerlModOutput &amp;output)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a57fa20826d8322a1247f63872fade06f">addTemplateList</a> (const ConceptDef *cd, PerlModOutput &amp;output)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a> (PerlModOutput &amp;output, const QCString &amp;name, const QCString &amp;fileName, int lineNr, const Definition *scope, const MemberDef *md, const QCString &amp;text)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a85b31a0b9f4657070d51bb5f61e6316e">getProtectionName</a> (Protection prot)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static const char *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3db996b98d5e76eca750e67f99b4e327">getVirtualnessName</a> (Specifier virt)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a12ff1fbddd237e1c30c3d41d7e315">setPerlModDoxyfile</a> (const QCString &amp;qs)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3c604811885fb67cffd44d399931dc15">generatePerlMod</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afb0371ed59a369486ad1a67b4c2efeab">pathDoxyfile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af9a07601cdd319c7b07bd7aa46c7e5fb">pathDoxyExec</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afdc7224ef604d3ec4c5c726a408cbf96">PERLOUTPUT_MAX_INDENTATION</a>&nbsp;&nbsp;&nbsp;40</td>
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

### addPerlModDocBlock() {#af0db6e1068b93a112848a208cf955b10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addPerlModDocBlock (<a href="/web-doxygen/docs/api/classes/perlmodoutput">PerlModOutput</a> &amp; output, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int lineNr, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; text)</td>
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



<p>Definition at line 1370 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af0db6e1068b93a112848a208cf955b10">1370</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>(<a href="/web-doxygen/docs/api/classes/perlmodoutput">PerlModOutput</a> &amp;output,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1371</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1372</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1373</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1374</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1375</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1376</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;text)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1377</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1378</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> stext = text.<a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">stripWhiteSpace</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1379</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (stext.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1380</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1381</span><span class="doxyLineContent"><span class="doxyHighlight">    output.<a href="/web-doxygen/docs/api/classes/perlmodoutput/#a5bc6095894cc4f4272364b1eb079f14f">addField</a>(name).<a href="/web-doxygen/docs/api/classes/perlmodoutput/#a05fa4627d62acbf1413ba09f6af91460">add</a>(</span><span class="doxyHighlightStringLiteral">"{}"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1382</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1383</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1384</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1385</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> parser { <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">createDocParser</a>() };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1386</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ast    { <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>(*parser.get(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1387</span><span class="doxyLineContent"><span class="doxyHighlight">                                     fileName,lineNr,scope,md,stext,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1388</span><span class="doxyLineContent"><span class="doxyHighlight">                                     <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>) };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1389</span><span class="doxyLineContent"><span class="doxyHighlight">    output.<a href="/web-doxygen/docs/api/classes/perlmodoutput/#a6732f64915669cef37c83b416ee0a289">openHash</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1390</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> astImpl = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/docnodeast">DocNodeAST</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(ast.get());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1391</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (astImpl)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1392</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1393</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor">PerlModDocVisitor</a> visitor(output);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1394</span><span class="doxyLineContent"><span class="doxyHighlight">      std::visit(visitor,astImpl-&gt;root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1395</span><span class="doxyLineContent"><span class="doxyHighlight">      visitor.<a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a1766bc0c0c37524f9fac777d62526f59">finish</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1396</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1397</span><span class="doxyLineContent"><span class="doxyHighlight">    output.<a href="/web-doxygen/docs/api/classes/perlmodoutput/#abc61e0edcbc793127548982a569ea2bd">closeHash</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1398</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1399</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/perlmodoutput/#a05fa4627d62acbf1413ba09f6af91460">PerlModOutput::add</a>, <a href="/web-doxygen/docs/api/classes/perlmodoutput/#a5bc6095894cc4f4272364b1eb079f14f">PerlModOutput::addField</a>, <a href="/web-doxygen/docs/api/classes/perlmodoutput/#abc61e0edcbc793127548982a569ea2bd">PerlModOutput::closeHash</a>, <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">createDocParser</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/perlmoddocvisitor/#a1766bc0c0c37524f9fac777d62526f59">PerlModDocVisitor::finish</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/perlmodoutput/#a6732f64915669cef37c83b416ee0a289">PerlModOutput::openHash</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a66269a694d9e6961bfd145bb4ca72f42">QCString::stripWhiteSpace</a> and <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#ac1f8e6fa454368157eb7cdb564ee6a40">PerlModGenerator::generatePerlModForConcept</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa4d01cc3ff8a727b38849e8efd171be9">PerlModGenerator::generatePerlModForFile</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#aa29eb86a9962f547f8139ff1cfe40b01">PerlModGenerator::generatePerlModForGroup</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a4d95b912616cab9e00075658e0fa09d4">PerlModGenerator::generatePerlModForModule</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a6d79f62a76314d0c65cb976809923d80">PerlModGenerator::generatePerlModForNamespace</a> and <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a0151a88e0794af12a9e7932de2d7a928">PerlModGenerator::generatePerlModForPage</a>.</p>

</div>
</div>

### addTemplateArgumentList() {#a0e2b9604ce397bbe6984cf81775f4fda}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addTemplateArgumentList (const <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp; al, <a href="/web-doxygen/docs/api/classes/perlmodoutput">PerlModOutput</a> &amp; output, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</td>
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



<p>Definition at line 1341 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0e2b9604ce397bbe6984cf81775f4fda">1341</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0e2b9604ce397bbe6984cf81775f4fda">addTemplateArgumentList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &amp;al,<a href="/web-doxygen/docs/api/classes/perlmodoutput">PerlModOutput</a> &amp;output,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1342</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1343</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!al.<a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">hasParameters</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1344</span><span class="doxyLineContent"><span class="doxyHighlight">  output.<a href="/web-doxygen/docs/api/classes/perlmodoutput/#a93c831a7105697a97b62246f3c3cb860">openList</a>(</span><span class="doxyHighlightStringLiteral">"template_parameters"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1345</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/argument">Argument</a> &amp;a : al)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1346</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1347</span><span class="doxyLineContent"><span class="doxyHighlight">    output.<a href="/web-doxygen/docs/api/classes/perlmodoutput/#a6732f64915669cef37c83b416ee0a289">openHash</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1348</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.type.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1349</span><span class="doxyLineContent"><span class="doxyHighlight">      output.<a href="/web-doxygen/docs/api/classes/perlmodoutput/#a6e6499ad8b1180084b7ad1e07ded6194">addFieldQuotedString</a>(</span><span class="doxyHighlightStringLiteral">"type"</span><span class="doxyHighlight">, a.type);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1350</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.name.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1351</span><span class="doxyLineContent"><span class="doxyHighlight">      output.<a href="/web-doxygen/docs/api/classes/perlmodoutput/#a6e6499ad8b1180084b7ad1e07ded6194">addFieldQuotedString</a>(</span><span class="doxyHighlightStringLiteral">"declaration_name"</span><span class="doxyHighlight">, a.name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1352</span><span class="doxyLineContent"><span class="doxyHighlight">        .<a href="/web-doxygen/docs/api/classes/perlmodoutput/#a6e6499ad8b1180084b7ad1e07ded6194">addFieldQuotedString</a>(</span><span class="doxyHighlightStringLiteral">"definition_name"</span><span class="doxyHighlight">, a.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1353</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!a.defval.isEmpty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1354</span><span class="doxyLineContent"><span class="doxyHighlight">      output.<a href="/web-doxygen/docs/api/classes/perlmodoutput/#a6e6499ad8b1180084b7ad1e07ded6194">addFieldQuotedString</a>(</span><span class="doxyHighlightStringLiteral">"default"</span><span class="doxyHighlight">, a.defval);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1355</span><span class="doxyLineContent"><span class="doxyHighlight">    output.<a href="/web-doxygen/docs/api/classes/perlmodoutput/#abc61e0edcbc793127548982a569ea2bd">closeHash</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1356</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1357</span><span class="doxyLineContent"><span class="doxyHighlight">  output.<a href="/web-doxygen/docs/api/classes/perlmodoutput/#a022fcdbc2b16df17ff2fe379676c96f3">closeList</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1358</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/perlmodoutput/#a6e6499ad8b1180084b7ad1e07ded6194">PerlModOutput::addFieldQuotedString</a>, <a href="/web-doxygen/docs/api/classes/perlmodoutput/#abc61e0edcbc793127548982a569ea2bd">PerlModOutput::closeHash</a>, <a href="/web-doxygen/docs/api/classes/perlmodoutput/#a022fcdbc2b16df17ff2fe379676c96f3">PerlModOutput::closeList</a>, <a href="/web-doxygen/docs/api/classes/argumentlist/#a2ed5c45b3909206446aaac4f1ab6d640">ArgumentList::hasParameters</a>, <a href="/web-doxygen/docs/api/classes/perlmodoutput/#a6732f64915669cef37c83b416ee0a289">PerlModOutput::openHash</a> and <a href="/web-doxygen/docs/api/classes/perlmodoutput/#a93c831a7105697a97b62246f3c3cb860">PerlModOutput::openList</a>.</p>


<p>Referenced by <a href="#a5375ce03d260026390f88a202e99fe33">addTemplateList</a> and <a href="#a57fa20826d8322a1247f63872fade06f">addTemplateList</a>.</p>

</div>
</div>

### addTemplateList() {#a5375ce03d260026390f88a202e99fe33}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addTemplateList (const <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> * cd, <a href="/web-doxygen/docs/api/classes/perlmodoutput">PerlModOutput</a> &amp; output)</td>
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



<p>Definition at line 1360 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5375ce03d260026390f88a202e99fe33">1360</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5375ce03d260026390f88a202e99fe33">addTemplateList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd,<a href="/web-doxygen/docs/api/classes/perlmodoutput">PerlModOutput</a> &amp;output)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1361</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1362</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0e2b9604ce397bbe6984cf81775f4fda">addTemplateArgumentList</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">templateArguments</a>(),output,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1363</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a0e2b9604ce397bbe6984cf81775f4fda">addTemplateArgumentList</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a> and <a href="/web-doxygen/docs/api/classes/classdef/#a201b8f24043f9b7c7cc59d55282f6d47">ClassDef::templateArguments</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a> and <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#ac1f8e6fa454368157eb7cdb564ee6a40">PerlModGenerator::generatePerlModForConcept</a>.</p>

</div>
</div>

### addTemplateList() {#a57fa20826d8322a1247f63872fade06f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void addTemplateList (const <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> * cd, <a href="/web-doxygen/docs/api/classes/perlmodoutput">PerlModOutput</a> &amp; output)</td>
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



<p>Definition at line 1365 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a57fa20826d8322a1247f63872fade06f">1365</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5375ce03d260026390f88a202e99fe33">addTemplateList</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *cd,<a href="/web-doxygen/docs/api/classes/perlmodoutput">PerlModOutput</a> &amp;output)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1366</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1367</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0e2b9604ce397bbe6984cf81775f4fda">addTemplateArgumentList</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/conceptdef/#a3dc85d76254ee240faaf13633a0639ba">getTemplateParameterList</a>(),output,cd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1368</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a0e2b9604ce397bbe6984cf81775f4fda">addTemplateArgumentList</a>, <a href="/web-doxygen/docs/api/classes/conceptdef/#a3dc85d76254ee240faaf13633a0639ba">ConceptDef::getTemplateParameterList</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.</p>

</div>
</div>

### generatePerlMod() {#a3c604811885fb67cffd44d399931dc15}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generatePerlMod ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 2953 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3c604811885fb67cffd44d399931dc15">2953</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3c604811885fb67cffd44d399931dc15">generatePerlMod</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2954</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2955</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/perlmodgenerator">PerlModGenerator</a> pmg(<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(PERLMOD_PRETTY));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2956</span><span class="doxyLineContent"><span class="doxyHighlight">  pmg.<a href="/web-doxygen/docs/api/classes/perlmodgenerator/#af6bb93beb1eac9b861832d368ffad291">generate</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2957</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a> and <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#af6bb93beb1eac9b861832d368ffad291">PerlModGenerator::generate</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.</p>

</div>
</div>

### getProtectionName() {#a85b31a0b9f4657070d51bb5f61e6316e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getProtectionName (<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot)</td>
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



<p>Definition at line 1401 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a85b31a0b9f4657070d51bb5f61e6316e">1401</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a85b31a0b9f4657070d51bb5f61e6316e">getProtectionName</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a90e352184df58cd09455fe9996cd4ded">Protection</a> prot)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1402</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1403</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#aec6ffd7cb8531fdfcb9b81e521a15197">to_string_lower</a>(prot);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1404</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/types-h/#aec6ffd7cb8531fdfcb9b81e521a15197">to_string_lower</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a81142c12bb2ef7638500997115bf2f43">PerlModGenerator::addListOfAllMembers</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a> and <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>.</p>

</div>
</div>

### getVirtualnessName() {#a3db996b98d5e76eca750e67f99b4e327}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const char * getVirtualnessName (<a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> virt)</td>
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



<p>Definition at line 1406 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3db996b98d5e76eca750e67f99b4e327">1406</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *<a href="#a3db996b98d5e76eca750e67f99b4e327">getVirtualnessName</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#ab16236bdd10ddf4d73a9847350f0017e">Specifier</a> virt)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1407</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1408</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/types-h/#aec6ffd7cb8531fdfcb9b81e521a15197">to_string_lower</a>(virt);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1409</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/types-h/#aec6ffd7cb8531fdfcb9b81e521a15197">to_string_lower</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a81142c12bb2ef7638500997115bf2f43">PerlModGenerator::addListOfAllMembers</a>, <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a44b30742275d27dcfe5eb9ea286af80f">PerlModGenerator::generatePerlModForClass</a> and <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a1d2fc28014f00de3422ac4b7a68b868a">PerlModGenerator::generatePerlModForMember</a>.</p>

</div>
</div>

### setPerlModDoxyfile() {#af9a12ff1fbddd237e1c30c3d41d7e315}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void setPerlModDoxyfile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; qs)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 1414 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af9a12ff1fbddd237e1c30c3d41d7e315">1414</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#af9a12ff1fbddd237e1c30c3d41d7e315">setPerlModDoxyfile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;qs)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1415</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1416</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#afb0371ed59a369486ad1a67b4c2efeab">pathDoxyfile</a> = qs;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1417</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#af9a07601cdd319c7b07bd7aa46c7e5fb">pathDoxyExec</a> = <a href="/web-doxygen/docs/api/classes/dir/#a0f62ab07068c5f966bca7ce280f4ed49">Dir::currentDirPath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1418</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/dir/#a0f62ab07068c5f966bca7ce280f4ed49">Dir::currentDirPath</a>, <a href="#af9a07601cdd319c7b07bd7aa46c7e5fb">pathDoxyExec</a> and <a href="#afb0371ed59a369486ad1a67b4c2efeab">pathDoxyfile</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab0fa1b0c948e78e0d0d749ff1f5740b5">readConfiguration</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Variables

### pathDoxyExec {#af9a07601cdd319c7b07bd7aa46c7e5fb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString pathDoxyExec</td>
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



<p>Definition at line 1412 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af9a07601cdd319c7b07bd7aa46c7e5fb">1412</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#af9a07601cdd319c7b07bd7aa46c7e5fb">pathDoxyExec</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a72b6d57151d45a13c60402914aa50831">PerlModGenerator::generateDoxyRules</a> and <a href="#af9a12ff1fbddd237e1c30c3d41d7e315">setPerlModDoxyfile</a>.</p>

</div>
</div>

### pathDoxyfile {#afb0371ed59a369486ad1a67b4c2efeab}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString pathDoxyfile</td>
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



<p>Definition at line 1411 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afb0371ed59a369486ad1a67b4c2efeab">1411</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#afb0371ed59a369486ad1a67b4c2efeab">pathDoxyfile</a>;</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmodgenerator/#a72b6d57151d45a13c60402914aa50831">PerlModGenerator::generateDoxyRules</a> and <a href="#af9a12ff1fbddd237e1c30c3d41d7e315">setPerlModDoxyfile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Macro Definitions

### PERLOUTPUT\_MAX\_INDENTATION {#afdc7224ef604d3ec4c5c726a408cbf96}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">#define PERLOUTPUT_MAX_INDENTATION&nbsp;&nbsp;&nbsp;40</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 46 of file <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp">perlmodgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#afdc7224ef604d3ec4c5c726a408cbf96">46</a></span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#define PERLOUTPUT_MAX_INDENTATION 40</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/perlmodoutput/#a87ca2eea3d930eb4fe5f34363fb4483c">PerlModOutput::decIndent</a> and <a href="/web-doxygen/docs/api/classes/perlmodoutput/#af64a9ea9387cf24ececa9948fc6c51bf">PerlModOutput::incIndent</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
