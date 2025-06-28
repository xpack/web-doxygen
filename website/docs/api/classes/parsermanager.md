---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/parsermanager
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `ParserManager` Class Reference

<p>Manages programming language parsers. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class ParserManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/parserintf-h">src/parserintf.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a952fe97757ee7e43c02596f73f0a6913">ParserManager</a> (const OutlineParserFactory &amp;outlineParserFactory, const CodeParserFactory &amp;codeParserFactory)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Create the parser manager. <a href="#a952fe97757ee7e43c02596f73f0a6913">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a434a1a473c7c10ebe1929d41d0af6690">registerParser</a> (const QCString &amp;name, const OutlineParserFactory &amp;outlineParserFactory, const CodeParserFactory &amp;codeParserFactory)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers an additional parser. <a href="#a434a1a473c7c10ebe1929d41d0af6690">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a150d4d51073cb46cdf38a236cc120d0a">registerExtension</a> (const QCString &amp;extension, const QCString &amp;parserName)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Registers a file <em>extension</em> with a parser with name <em>parserName</em>. <a href="#a150d4d51073cb46cdf38a236cc120d0a">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/outlineparserinterface">OutlineParserInterface</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a44739ad6424de118f9cb2ccae8ea68b9">getOutlineParser</a> (const QCString &amp;extension)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the interface to the parser associated with a given <em>extension</em>. <a href="#a44739ad6424de118f9cb2ccae8ea68b9">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/codeparserinterface">CodeParserInterface</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a691952e0c5c944e83d4a6e88117471a6">getCodeParser</a> (const QCString &amp;extension)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the interface to the parser associated with a given <em>extension</em>. <a href="#a691952e0c5c944e83d4a6e88117471a6">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/files/src/parserintf-h/#ab3d33d80825a6d236fc1ca772325c12e">CodeParserFactory</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f767ea4b80602eec90e5fa4a5c2b008">getCodeParserFactory</a> (const QCString &amp;extension)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Get the factory for create code parser objects with a given <em>extension</em>. <a href="#a8f767ea4b80602eec90e5fa4a5c2b008">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af629ad3cc57868b383cb02601fd9c7b4">getParserName</a> (const QCString &amp;extension)</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Gets the name of the parser associated with given <em>extension</em>. <a href="#af629ad3cc57868b383cb02601fd9c7b4">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/parsermanager/parserpair">ParserPair</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac5f1e3b27673fb0ab040a07469c29a87">getParsers</a> (const QCString &amp;extension)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, <a href="/web-doxygen/docs/api/structs/parsermanager/parserpair">ParserPair</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a20879de66f3c9555ec87f31d878e729b">m_parsers</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; std::string, <a href="/web-doxygen/docs/api/structs/parsermanager/parserpair">ParserPair</a> &amp; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad8743402c91d10a0a1549354ffb1c68d">m_extensions</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/structs/parsermanager/parserpair">ParserPair</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a60479453dc57c884b1411f13beedb929">m_defaultParsers</a></td>
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

<p>Manages programming language parsers.</p>


<p>This class manages the language parsers in the system. One can register parsers, and obtain a parser given a file extension.</p>

<p>Definition at line 146 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### ParserManager() {#a952fe97757ee7e43c02596f73f0a6913}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParserManager::ParserManager (const <a href="/web-doxygen/docs/api/files/src/parserintf-h/#afda01ba4e899f06f0fbbd2b0f79fd5cf">OutlineParserFactory</a> &amp; outlineParserFactory, const <a href="/web-doxygen/docs/api/files/src/parserintf-h/#ab3d33d80825a6d236fc1ca772325c12e">CodeParserFactory</a> &amp; codeParserFactory)</td>
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
<p>Create the parser manager.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">outlineParserFactory</td>
<td class="doxyParamItemDescription"><p>the fallback outline parser factory to use for unknown extensions</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">codeParserFactory</td>
<td class="doxyParamItemDescription"><p>the fallback code parser factory to use for unknown extensions</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 166 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a952fe97757ee7e43c02596f73f0a6913">166</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a952fe97757ee7e43c02596f73f0a6913">ParserManager</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/parserintf-h/#afda01ba4e899f06f0fbbd2b0f79fd5cf">OutlineParserFactory</a> &amp;outlineParserFactory,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">                  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/parserintf-h/#ab3d33d80825a6d236fc1ca772325c12e">CodeParserFactory</a>    &amp;codeParserFactory)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="#a60479453dc57c884b1411f13beedb929">m_defaultParsers</a>(outlineParserFactory,codeParserFactory, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a60479453dc57c884b1411f13beedb929">m&#95;defaultParsers</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### getCodeParser() {#a691952e0c5c944e83d4a6e88117471a6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; CodeParserInterface &gt; ParserManager::getCodeParser (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
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
<p>Gets the interface to the parser associated with a given <em>extension</em>.</p>


<p>If there is no parser explicitly registered for the supplied extension, the interface to the default parser will be returned.</p>

<p>Definition at line 218 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a691952e0c5c944e83d4a6e88117471a6">218</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;CodeParserInterface&gt; <a href="#a691952e0c5c944e83d4a6e88117471a6">getCodeParser</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;extension)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> factory = <a href="#a8f767ea4b80602eec90e5fa4a5c2b008">getCodeParserFactory</a>(extension);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> factory();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#a8f767ea4b80602eec90e5fa4a5c2b008">getCodeParserFactory</a>.
</div>
</div>

### getCodeParserFactory() {#a8f767ea4b80602eec90e5fa4a5c2b008}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeParserFactory &amp; ParserManager::getCodeParserFactory (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
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
<p>Get the factory for create code parser objects with a given <em>extension</em>.</p>

<p>Definition at line 225 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8f767ea4b80602eec90e5fa4a5c2b008">225</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/parserintf-h/#ab3d33d80825a6d236fc1ca772325c12e">CodeParserFactory</a> &amp;<a href="#a8f767ea4b80602eec90e5fa4a5c2b008">getCodeParserFactory</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;extension)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac5f1e3b27673fb0ab040a07469c29a87">getParsers</a>(extension).codeParserFactory;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#ac5f1e3b27673fb0ab040a07469c29a87">getParsers</a>.

Referenced by <a href="#a691952e0c5c944e83d4a6e88117471a6">getCodeParser</a>.
</div>
</div>

### getOutlineParser() {#a44739ad6424de118f9cb2ccae8ea68b9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; OutlineParserInterface &gt; ParserManager::getOutlineParser (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
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
<p>Gets the interface to the parser associated with a given <em>extension</em>.</p>


<p>If there is no parser explicitly registered for the supplied extension, the interface to the default parser will be returned.</p>

<p>Definition at line 209 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a44739ad6424de118f9cb2ccae8ea68b9">209</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;OutlineParserInterface&gt; <a href="#a44739ad6424de118f9cb2ccae8ea68b9">getOutlineParser</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;extension)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac5f1e3b27673fb0ab040a07469c29a87">getParsers</a>(extension).outlineParserFactory();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#ac5f1e3b27673fb0ab040a07469c29a87">getParsers</a>.
</div>
</div>

### getParserName() {#af629ad3cc57868b383cb02601fd9c7b4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString ParserManager::getParserName (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
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
<p>Gets the name of the parser associated with given <em>extension</em>.</p>


<p>If there is no parser explicitly registered for the supplied extension, the empty string will be returned.</p>

<p>Definition at line 234 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af629ad3cc57868b383cb02601fd9c7b4">234</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#af629ad3cc57868b383cb02601fd9c7b4">getParserName</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;extension)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ac5f1e3b27673fb0ab040a07469c29a87">getParsers</a>(extension).parserName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


Reference <a href="#ac5f1e3b27673fb0ab040a07469c29a87">getParsers</a>.
</div>
</div>

### registerExtension() {#a150d4d51073cb46cdf38a236cc120d0a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool ParserManager::registerExtension (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; parserName)</td>
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
<p>Registers a file <em>extension</em> with a parser with name <em>parserName</em>.</p>


<p>Returns TRUE if the extension was successfully registered.</p>

<p>Definition at line 189 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a150d4d51073cb46cdf38a236cc120d0a">189</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a150d4d51073cb46cdf38a236cc120d0a">registerExtension</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;extension, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;parserName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parserName.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || extension.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;parserIt = <a href="#a20879de66f3c9555ec87f31d878e729b">m_parsers</a>.find(parserName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parserIt == <a href="#a20879de66f3c9555ec87f31d878e729b">m_parsers</a>.end()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> extensionIt = <a href="#ad8743402c91d10a0a1549354ffb1c68d">m_extensions</a>.find(extension.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (extensionIt != <a href="#ad8743402c91d10a0a1549354ffb1c68d">m_extensions</a>.end()) </span><span class="doxyHighlightComment">// extension already exists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad8743402c91d10a0a1549354ffb1c68d">m_extensions</a>.erase(extensionIt); </span><span class="doxyHighlightComment">// remove it (e.g. user specified extension overrules built in one)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad8743402c91d10a0a1549354ffb1c68d">m_extensions</a>.emplace(extension.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),parserIt-&gt;second); </span><span class="doxyHighlightComment">// add new mapping</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ad8743402c91d10a0a1549354ffb1c68d">m&#95;extensions</a>, <a href="#a20879de66f3c9555ec87f31d878e729b">m&#95;parsers</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.
</div>
</div>

### registerParser() {#a434a1a473c7c10ebe1929d41d0af6690}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void ParserManager::registerParser (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/files/src/parserintf-h/#afda01ba4e899f06f0fbbd2b0f79fd5cf">OutlineParserFactory</a> &amp; outlineParserFactory, const <a href="/web-doxygen/docs/api/files/src/parserintf-h/#ab3d33d80825a6d236fc1ca772325c12e">CodeParserFactory</a> &amp; codeParserFactory)</td>
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
<p>Registers an additional parser.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] name</td>
<td class="doxyParamItemDescription"><p>A symbolic name of the parser, i.e. "c", "python", "fortran", "vhdl", ...</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] outlineParserFactory</td>
<td class="doxyParamItemDescription"><p>A factory method to create a language parser (scanner) that is to be used for the given name.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] codeParserFactory</td>
<td class="doxyParamItemDescription"><p>A factory method to create a code parser that is to be used for the given name.</p></td>
</tr>
</table>
</dd>
</dl>

<p>Definition at line 180 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a434a1a473c7c10ebe1929d41d0af6690">180</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a434a1a473c7c10ebe1929d41d0af6690">registerParser</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/parserintf-h/#afda01ba4e899f06f0fbbd2b0f79fd5cf">OutlineParserFactory</a> &amp;outlineParserFactory,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">                                             </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/parserintf-h/#ab3d33d80825a6d236fc1ca772325c12e">CodeParserFactory</a>    &amp;codeParserFactory)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a20879de66f3c9555ec87f31d878e729b">m_parsers</a>.emplace(name.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="/web-doxygen/docs/api/structs/parsermanager/parserpair">ParserPair</a>(outlineParserFactory,codeParserFactory,name));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="#a20879de66f3c9555ec87f31d878e729b">m&#95;parsers</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### getParsers() {#ac5f1e3b27673fb0ab040a07469c29a87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParserPair &amp; ParserManager::getParsers (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; extension)</td>
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


<p>Definition at line 240 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac5f1e3b27673fb0ab040a07469c29a87">240</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/parsermanager/parserpair">ParserPair</a> &amp;<a href="#ac5f1e3b27673fb0ab040a07469c29a87">getParsers</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;extension)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> ext = extension.<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ext.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) ext=</span><span class="doxyHighlightStringLiteral">".no_extension"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ad8743402c91d10a0a1549354ffb1c68d">m_extensions</a>.find(ext.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#ad8743402c91d10a0a1549354ffb1c68d">m_extensions</a>.end() &amp;&amp; ext.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()&gt;4)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">        it = <a href="#ad8743402c91d10a0a1549354ffb1c68d">m_extensions</a>.find(ext.<a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">left</a>(4).<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#ad8743402c91d10a0a1549354ffb1c68d">m_extensions</a>.end() ? it-&gt;second : <a href="#a60479453dc57c884b1411f13beedb929">m_defaultParsers</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aecf8b66312c4e97333219cc344c11a4f">QCString::left</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="#a60479453dc57c884b1411f13beedb929">m&#95;defaultParsers</a> and <a href="#ad8743402c91d10a0a1549354ffb1c68d">m&#95;extensions</a>.

Referenced by <a href="#a8f767ea4b80602eec90e5fa4a5c2b008">getCodeParserFactory</a>, <a href="#a44739ad6424de118f9cb2ccae8ea68b9">getOutlineParser</a> and <a href="#af629ad3cc57868b383cb02601fd9c7b4">getParserName</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;defaultParsers {#a60479453dc57c884b1411f13beedb929}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">ParserPair ParserManager::m_defaultParsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 254 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a60479453dc57c884b1411f13beedb929">254</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/structs/parsermanager/parserpair">ParserPair</a> <a href="#a60479453dc57c884b1411f13beedb929">m_defaultParsers</a>;</span></span></div>

</div>


Referenced by <a href="#ac5f1e3b27673fb0ab040a07469c29a87">getParsers</a> and <a href="#a952fe97757ee7e43c02596f73f0a6913">ParserManager</a>.
</div>
</div>

### m&#95;extensions {#ad8743402c91d10a0a1549354ffb1c68d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string,ParserPair &amp;&gt; ParserManager::m_extensions</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 253 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad8743402c91d10a0a1549354ffb1c68d">253</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::map&lt;std::string,ParserPair &amp;&gt; <a href="#ad8743402c91d10a0a1549354ffb1c68d">m_extensions</a>;</span></span></div>

</div>


Referenced by <a href="#ac5f1e3b27673fb0ab040a07469c29a87">getParsers</a> and <a href="#a150d4d51073cb46cdf38a236cc120d0a">registerExtension</a>.
</div>
</div>

### m&#95;parsers {#a20879de66f3c9555ec87f31d878e729b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;std::string,ParserPair&gt; ParserManager::m_parsers</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 252 of file <a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a20879de66f3c9555ec87f31d878e729b">252</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::map&lt;std::string,ParserPair&gt; <a href="#a20879de66f3c9555ec87f31d878e729b">m_parsers</a>;</span></span></div>

</div>


Referenced by <a href="#a150d4d51073cb46cdf38a236cc120d0a">registerExtension</a> and <a href="#a434a1a473c7c10ebe1929d41d0af6690">registerParser</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following file:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/parserintf-h">parserintf.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
