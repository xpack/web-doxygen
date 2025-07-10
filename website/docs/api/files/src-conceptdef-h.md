---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/conceptdef-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `conceptdef.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;memory&gt;
#include "<a href="/web-doxygen/docs/api/files/src/definition-h">definition.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/filedef-h">filedef.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptdefmutable">ConceptDefMutable</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptlinkedmap">ConceptLinkedMap</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptlinkedrefmap">ConceptLinkedRefMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6278cdad145147794f426e0415f7f2cd">createConceptDef</a> (const QCString &amp;fileName, int startLine, int startColumn, const QCString &amp;name, const QCString &amp;tagRef=QCString(), const QCString &amp;tagFile=QCString())</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac3907be09ae35f7ef088faa47d2d6a06">createConceptDefAlias</a> (const Definition *newScope, const ConceptDef *cd)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8aca54b155c35ee664b836f60a6f3af3">toConceptDef</a> (Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8b08d9beda67854a8cca74e2ec70e392">toConceptDef</a> (DefinitionMutable *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6736050f29f0450c766bb42ec743fcfd">toConceptDef</a> (const Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptdefmutable">ConceptDefMutable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a04c0091865f3e596872d27767ba1061a">toConceptDefMutable</a> (Definition *d)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5b1ec1b9e1f818d3bc0af4e94497179d">getConcept</a> (const QCString &amp;key)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptdefmutable">ConceptDefMutable</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa69eb58d1d5fb6100606dae5ca070416">getConceptMutable</a> (const QCString &amp;key)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0903a7476e802457067b008928f55225">getResolvedConcept</a> (const Definition *scope, const QCString &amp;name)</td>
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

### createConceptDef() {#a6278cdad145147794f426e0415f7f2cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ConceptDef &gt; createConceptDef (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int startLine, int startColumn, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tagRef=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(), const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; tagFile=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 61 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>, definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp">conceptdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#acc6115230c47267766eb73392f9de1f9">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;ConceptDef&gt; <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#acc6115230c47267766eb73392f9de1f9">createConceptDef</a>(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startColumn,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tagRef,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;tagFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;ConceptDefImpl&gt;(fileName,startLine,startColumn,name,tagRef,tagFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a> and <a href="/web-doxygen/docs/api/classes/conceptdefmutable/#aa31429fc142be78fdbe11ff30e933960">ConceptDefMutable::setModuleDef</a>.</p>

</div>
</div>

### createConceptDefAlias() {#ac3907be09ae35f7ef088faa47d2d6a06}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ConceptDef &gt; createConceptDefAlias (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * newScope, const <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> * cd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>, definition at line 149 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp">conceptdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#ac3907be09ae35f7ef088faa47d2d6a06">149</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;ConceptDef&gt; <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#ac3907be09ae35f7ef088faa47d2d6a06">createConceptDefAlias</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *newScope,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *cd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;ConceptDefAliasImpl&gt;(newScope,cd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/conceptdefmutable/#aa31429fc142be78fdbe11ff30e933960">ConceptDefMutable::setModuleDef</a>.</p>

</div>
</div>

### getConcept() {#a5b1ec1b9e1f818d3bc0af4e94497179d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConceptDef * getConcept (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 89 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>, definition at line 788 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp">conceptdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#abc9dcc96b75f1a299589ec14c2a97c97">788</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *<a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#abc9dcc96b75f1a299589ec14c2a97c97">getConcept</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;n)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">789</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">790</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (n.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">791</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/doxygen/#a0de9b52b3098ea1a4bee5e248e8287c8">Doxygen::conceptLinkedMap</a>-&gt;find(n);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">792</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doxygen/#a0de9b52b3098ea1a4bee5e248e8287c8">Doxygen::conceptLinkedMap</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>.</p>


<p>Referenced by <a href="#aa69eb58d1d5fb6100606dae5ca070416">getConceptMutable</a>, <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a6bc5655b365e44b18669ff804724d11e">getResolvedConcept</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae61ca16879462ab6bd55475fa265b251">linkifyText</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a832a4486d71b72fba73e98a6dfdf33e4">resolveLink</a>.</p>

</div>
</div>

### getConceptMutable() {#aa69eb58d1d5fb6100606dae5ca070416}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConceptDefMutable * getConceptMutable (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; key)</td>
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



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa69eb58d1d5fb6100606dae5ca070416">90</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/conceptdefmutable">ConceptDefMutable</a> *<a href="#aa69eb58d1d5fb6100606dae5ca070416">getConceptMutable</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;key)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a04c0091865f3e596872d27767ba1061a">toConceptDefMutable</a>(<a href="#a5b1ec1b9e1f818d3bc0af4e94497179d">getConcept</a>(key));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a5b1ec1b9e1f818d3bc0af4e94497179d">getConcept</a> and <a href="#a04c0091865f3e596872d27767ba1061a">toConceptDefMutable</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>.</p>

</div>
</div>

### getResolvedConcept() {#a0903a7476e802457067b008928f55225}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConceptDef * getResolvedConcept (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * scope, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 94 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>, definition at line 794 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp">conceptdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a6bc5655b365e44b18669ff804724d11e">794</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *<a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a6bc5655b365e44b18669ff804724d11e">getResolvedConcept</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">795</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">796</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *cd=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">797</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (d &amp;&amp; d!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">798</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">799</span><span class="doxyLineContent"><span class="doxyHighlight">    cd = <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#abc9dcc96b75f1a299589ec14c2a97c97">getConcept</a>(d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>()+</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">+name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">800</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (cd) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">801</span><span class="doxyLineContent"><span class="doxyHighlight">    d = d-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">getOuterScope</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">802</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">803</span><span class="doxyLineContent"><span class="doxyHighlight">  cd = <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#abc9dcc96b75f1a299589ec14c2a97c97">getConcept</a>(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">804</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> cd;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">805</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#abc9dcc96b75f1a299589ec14c2a97c97">getConcept</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabf5ee4ca8de43bbcc5cd5736f150e5">Definition::getOuterScope</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a> and <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/code-l/#a3345ad9e2ab3a9d1b524391ae5f6c545">generateClassOrGlobalLink</a>.</p>

</div>
</div>

### toConceptDef() {#a8aca54b155c35ee664b836f60a6f3af3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConceptDef * toConceptDef (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>, definition at line 737 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp">conceptdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a8aca54b155c35ee664b836f60a6f3af3">737</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *<a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a8aca54b155c35ee664b836f60a6f3af3">toConceptDef</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">738</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">739</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; (</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/conceptdefimpl">ConceptDefImpl</a>) || </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl">ConceptDefAliasImpl</a>)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">740</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">741</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">742</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">743</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">744</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">745</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">746</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">747</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a34803fafd2b7ff3f593f4c9a97c59f2d">NamespaceDefImpl::addInnerCompound</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a67d97db3c717b89b9a6211ae48e9273b">findModuleDef</a>, <a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl/#ab1feaee394182b5b6c31dc504e2bdd88">ConceptDefAliasImpl::getCdAlias</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a92aa0c495ca4eb835bb914dbb5fefa35">getDefsNew</a>.</p>

</div>
</div>

### toConceptDef() {#a8b08d9beda67854a8cca74e2ec70e392}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConceptDef * toConceptDef (<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 83 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>, definition at line 749 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp">conceptdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#aef7eaf07a699cd7ef3d8286d9f44dcde">749</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *<a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a8aca54b155c35ee664b836f60a6f3af3">toConceptDef</a>(<a href="/web-doxygen/docs/api/classes/definitionmutable">DefinitionMutable</a> *md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">750</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">751</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d = <a href="/web-doxygen/docs/api/files/src/definition-cpp/#ab43e817b86eeee8909980167d1a140c8">toDefinition</a>(md);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">752</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/conceptdefimpl">ConceptDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">753</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">754</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">755</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">756</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">757</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">758</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">759</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">760</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/definition-cpp/#ab43e817b86eeee8909980167d1a140c8">toDefinition</a>.</p>

</div>
</div>

### toConceptDef() {#a6736050f29f0450c766bb42ec743fcfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ConceptDef * toConceptDef (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 84 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>, definition at line 762 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp">conceptdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a6736050f29f0450c766bb42ec743fcfd">762</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a> *<a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a8aca54b155c35ee664b836f60a6f3af3">toConceptDef</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">763</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">764</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; (</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/conceptdefimpl">ConceptDefImpl</a>) || </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/conceptdefaliasimpl">ConceptDefAliasImpl</a>)))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">765</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">766</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeyword">const </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/conceptdef">ConceptDef</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">767</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">768</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">769</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">770</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">771</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">772</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>

</div>
</div>

### toConceptDefMutable() {#a04c0091865f3e596872d27767ba1061a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ConceptDefMutable * toConceptDefMutable (<a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 85 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-h">conceptdef.h</a>, definition at line 774 of file <a href="/web-doxygen/docs/api/files/src/conceptdef-cpp">conceptdef.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a04c0091865f3e596872d27767ba1061a">774</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/conceptdefmutable">ConceptDefMutable</a> *<a href="/web-doxygen/docs/api/files/src/conceptdef-cpp/#a04c0091865f3e596872d27767ba1061a">toConceptDefMutable</a>(<a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">775</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">776</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (d &amp;&amp; </span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(*d)==</span><span class="doxyHighlightKeyword">typeid</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/classes/conceptdefimpl">ConceptDefImpl</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">777</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">778</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/conceptdefmutable">ConceptDefMutable</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(d);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">779</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">780</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">781</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">782</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">783</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">784</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a115ebb5e081b43164c747df76e55af9f">addConceptToContext</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a9ed7b5fc926a79337a09aa8ecef0e41d">addConceptToGroups</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#a3bed85d27e567e04fe01b0192a58db97">ModuleDefImpl::addConceptToModule</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a6698b2bf23de9dc94a27ad7b898c205b">ModuleManager::addConceptToModule</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a4867a5cabf355b71e9540e4316ba17dd">distributeConceptGroups</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ad0183e79b7d98cfc8d0fd1b32efa27d5">findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae7c1288552887f734e87c470ea2c91c1">generateConceptDocs</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a34eca88c480e8203f29afff92f5393df">generateNamespaceConceptDocs</a>, <a href="#aa69eb58d1d5fb6100606dae5ca070416">getConceptMutable</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#acbd9db076ae71bddeb6c5e9b27dd23da">writeTagFile</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
