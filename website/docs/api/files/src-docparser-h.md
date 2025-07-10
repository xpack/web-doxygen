---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/docparser-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `docparser.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;stdio.h&gt;
#include &lt;memory&gt;
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/growvector-h">growvector.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/config-h">config.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/idocparser">IDocParser</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>opaque parser interface <a href="/web-doxygen/docs/api/classes/idocparser/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/idocnodeast">IDocNodeAST</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>opaque representation of the abstract syntax tree (AST) <a href="/web-doxygen/docs/api/classes/idocnodeast/#details">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Typedefs Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a46dd0a995d5a164236b9264a86758622">IDocParserPtr</a> = std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/idocparser">IDocParser</a> &gt;</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>pointer to parser interface <a href="#a46dd0a995d5a164236b9264a86758622">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">using</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a03066f1adfa357c8a7fa806069caa6ed">IDocNodeASTPtr</a> = std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/idocnodeast">IDocNodeAST</a> &gt;</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a46dd0a995d5a164236b9264a86758622">IDocParserPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7a169cbf0edeed85c90868675799b875">createDocParser</a> ()</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>factory function to create a parser <a href="#a7a169cbf0edeed85c90868675799b875">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a03066f1adfa357c8a7fa806069caa6ed">IDocNodeASTPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a25d6b1f807d8ecdcbf950168ff8a1c13">validatingParseDoc</a> (IDocParser &amp;parserIntf, const QCString &amp;fileName, int startLine, const Definition *ctx, const MemberDef *md, const QCString &amp;input, bool indexWords, bool isExample, const QCString &amp;exampleName, bool singleLine, bool linkFromIndex, bool markdownSupport=Config_getBool(MARKDOWN_SUPPORT), bool autolinkSupport=Config_getBool(AUTOLINK_SUPPORT))</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a03066f1adfa357c8a7fa806069caa6ed">IDocNodeASTPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#afd6219ce4bc112d331cd21cb79aefac7">validatingParseText</a> (IDocParser &amp;parser, const QCString &amp;input)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a03066f1adfa357c8a7fa806069caa6ed">IDocNodeASTPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a> (IDocParser &amp;parserIntf, const QCString &amp;fileName, int lineNr, const QCString &amp;input)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="#a03066f1adfa357c8a7fa806069caa6ed">IDocNodeASTPtr</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9de12220454dedcb0fa161b4d6eb6c85">createRef</a> (IDocParser &amp;parser, const QCString &amp;target, const QCString &amp;context, const QCString &amp;srcFile="", int srcLine=-1)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0fc0d3e4ca95dd0dc254d0efb1fd045a">docFindSections</a> (const QCString &amp;input, const Definition *d, const QCString &amp;fileName)</td>
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

## Typedefs

### IDocNodeASTPtr {#a03066f1adfa357c8a7fa806069caa6ed}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using IDocNodeASTPtr =  std::unique_ptr&lt;IDocNodeAST&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 57 of file <a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a03066f1adfa357c8a7fa806069caa6ed">57</a></span><span class="doxyLineContent"><span class="doxyHighlight">using <a href="#a03066f1adfa357c8a7fa806069caa6ed">IDocNodeASTPtr</a> = std::unique_ptr&lt;<a href="/web-doxygen/docs/api/classes/idocnodeast">IDocNodeAST</a>&gt;;</span></span></div>

</div>

</div>
</div>

### IDocParserPtr {#a46dd0a995d5a164236b9264a86758622}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">using IDocParserPtr =  std::unique_ptr&lt;IDocParser&gt;</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>pointer to parser interface</p>

<p>Definition at line 41 of file <a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a46dd0a995d5a164236b9264a86758622">41</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">using </span><span class="doxyHighlight"><a href="#a46dd0a995d5a164236b9264a86758622">IDocParserPtr</a> = std::unique_ptr&lt;IDocParser&gt;;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### createDocParser() {#a7a169cbf0edeed85c90868675799b875}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IDocParserPtr createDocParser ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">

<p>factory function to create a parser</p>

<p>Declaration at line 44 of file <a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>, definition at line 55 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">55</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a46dd0a995d5a164236b9264a86758622">IDocParserPtr</a> <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a7a169cbf0edeed85c90868675799b875">createDocParser</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;DocParser&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#aa8d9375638b4b082c242439fa6be97a0">convertMapFile</a>, <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a53124fcb14c157228188e339625da475">generateBriefDoc</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ac371cebadb37ea8ab3ae59502036c427">OutputList::generateDoc</a>, <a href="/web-doxygen/docs/api/files/src/singlecomment-cpp/#ae8dd6bba2e9ad92dab454422a3136a26">generateHtmlOutput</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a24141a97ca3b089d108db4129d4047f6">parseCommentAsHtml</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a336a6313626a3a3931e2086fd507bedc">parseCommentAsText</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#adfdcf2ba925f05be8beb8cf43deb168a">OutputList::parseText</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a>, <a href="/web-doxygen/docs/api/structs/layoutnaventry/#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">LayoutNavEntry::url</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a1f234d06f4ded36681d8976f055d5929">writeXMLDocBlock</a>.</p>

</div>
</div>

### createRef() {#a9de12220454dedcb0fa161b4d6eb6c85}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IDocNodeASTPtr createRef (<a href="/web-doxygen/docs/api/classes/idocparser">IDocParser</a> &amp; parser, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; target, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; context, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile="", int srcLine=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 102 of file <a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>, definition at line 2163 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a81d4810c1b7d0715b60aea2ac421bfd1">2163</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a03066f1adfa357c8a7fa806069caa6ed">IDocNodeASTPtr</a> <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a81d4810c1b7d0715b60aea2ac421bfd1">createRef</a>(<a href="/web-doxygen/docs/api/classes/idocparser">IDocParser</a> &amp;parserIntf,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;target,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;context, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2164</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2165</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *parser = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/docparser">DocParser</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(&amp;parserIntf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2166</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(parser!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2167</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parser==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2168</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!srcFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2169</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2170</span><span class="doxyLineContent"><span class="doxyHighlight">    parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a2b4c522f7f52850b1956b1b1504c4f1b">fileName</a> = srcFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2171</span><span class="doxyLineContent"><span class="doxyHighlight">    parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a2ffd450e14852a41762e405e33efed7d">setLineNr</a>(srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2172</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2173</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> std::make_unique&lt;DocNodeAST&gt;(<a href="/web-doxygen/docs/api/classes/docref">DocRef</a>(parser,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,target,context));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2174</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a2b4c522f7f52850b1956b1b1504c4f1b">DocParserContext::fileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a2ffd450e14852a41762e405e33efed7d">DocTokenizer::setLineNr</a> and <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/msc-cpp/#aa8d9375638b4b082c242439fa6be97a0">convertMapFile</a>, <a href="/web-doxygen/docs/api/files/src/dotfilepatcher-cpp/#a79f47c101daa51c0e727788d0f134f7e">replaceRef</a> and <a href="/web-doxygen/docs/api/structs/layoutnaventry/#a1c873f2a034fd33d3c1ddcfcd0c2ecf0">LayoutNavEntry::url</a>.</p>

</div>
</div>

### docFindSections() {#a0fc0d3e4ca95dd0dc254d0efb1fd045a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void docFindSections (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * d, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Searches for section and anchor commands in the input Sections found will be added to the <a href="/web-doxygen/docs/api/classes/sectionmanager">SectionManager</a>.</p>


<p>Declaration at line 109 of file <a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>, definition at line 2176 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a0fc0d3e4ca95dd0dc254d0efb1fd045a">2176</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a0fc0d3e4ca95dd0dc254d0efb1fd045a">docFindSections</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;input,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2177</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *d,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2178</span><span class="doxyLineContent"><span class="doxyHighlight">                     </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2179</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2180</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> parser;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2181</span><span class="doxyLineContent"><span class="doxyHighlight">  parser.<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a640bce791d53e83dcbd47f7ab01620e8">findSections</a>(input,d,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2182</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doctokenizer/#a640bce791d53e83dcbd47f7ab01620e8">DocTokenizer::findSections</a> and <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/classdefimpl/#a8c79cd46ab87017122f86075bafd990d">ClassDefImpl::findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a82adc533d200b145435736ca454fc0a8">ConceptDefImpl::findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a0397dc0871ba57cd932d58bc11260a6b">FileDefImpl::findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#a8470e2f1b8579459d58c1e84736dcb4d">GroupDefImpl::findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a35ffcd165bc8c26879b2e7b7e85cc60d">MemberDefImpl::findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/classes/membergroup/#a2718e48c3a7d884ef429b93487b7f83e">MemberGroup::findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#ab485ec1999243c813656dd89d7ed21f3">ModuleDefImpl::findSectionsInDocumentation</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#aacdda17a5034aced632d535473a15963">NamespaceDefImpl::findSectionsInDocumentation</a> and <a href="/web-doxygen/docs/api/classes/pagedefimpl/#a8ac76ea99a4f360d99342116b632015f">PageDefImpl::findSectionsInDocumentation</a>.</p>

</div>
</div>

### validatingParseDoc() {#a25d6b1f807d8ecdcbf950168ff8a1c13}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IDocNodeASTPtr validatingParseDoc (<a href="/web-doxygen/docs/api/classes/idocparser">IDocParser</a> &amp; parserIntf, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int startLine, const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * ctx, const <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> * md, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input, bool indexWords, bool isExample, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; exampleName, bool singleLine, bool linkFromIndex, bool markdownSupport=<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT), bool autolinkSupport=<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(AUTOLINK_SUPPORT))</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Main entry point for the comment block parser.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">parserIntf</td>
<td class="doxyParamItemDescription"><p>The parser object created via <a href="#a7a169cbf0edeed85c90868675799b875">createDocParser()</a></p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">fileName</td>
<td class="doxyParamItemDescription"><p>File in which the documentation block is found (or the name of the example file in case isExample is TRUE).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">startLine</td>
<td class="doxyParamItemDescription"><p>Line at which the documentation block is found.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">ctx</td>
<td class="doxyParamItemDescription"><p>Class or namespace to which this block belongs.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">md</td>
<td class="doxyParamItemDescription"><p>Member definition to which the documentation belongs. Can be 0.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">input</td>
<td class="doxyParamItemDescription"><p>String representation of the documentation block.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">indexWords</td>
<td class="doxyParamItemDescription"><p>Indicates whether or not words should be put in the search index.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">isExample</td>
<td class="doxyParamItemDescription"><p>TRUE if the documentation belongs to an example.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">exampleName</td>
<td class="doxyParamItemDescription"><p>Base name of the example file (0 if isExample is FALSE).</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">singleLine</td>
<td class="doxyParamItemDescription"><p>Output should be presented on a single line, so without starting a new paragraph at the end.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">linkFromIndex</td>
<td class="doxyParamItemDescription"><p>TRUE if the documentation is generated from an index page. In this case context is not used to determine the relative path when making a link.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">markdownSupport</td>
<td class="doxyParamItemDescription"><p>TRUE if the input needs to take markdown markup into account.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">autolinkSupport</td>
<td class="doxyParamItemDescription"><p>TRUE if the input need to perform auto linking of words</p></td>
</tr>
</table>
</dd>
</dl>

<dl class="doxySectionUser">
<dt>Returns</dt>
<dd><p>An object representing the abstract syntax tree. Ownership of the pointer is handed over to the caller.</p></dd>
</dl>


<p>Declaration at line 83 of file <a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>, definition at line 1922 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">1922</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a03066f1adfa357c8a7fa806069caa6ed">IDocNodeASTPtr</a> <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a5b6203b6c11e050448bcd6e090720f32">validatingParseDoc</a>(<a href="/web-doxygen/docs/api/classes/idocparser">IDocParser</a> &amp;parserIntf,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1923</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1924</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *ctx,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1925</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;input,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> indexWords,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1926</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isExample, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;exampleName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1927</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> singleLine, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> linkFromIndex,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1928</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> markdownSupport,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1929</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> autolinkSupport)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1930</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1931</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *parser = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/docparser">DocParser</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(&amp;parserIntf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1932</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(parser!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1933</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parser==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1934</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("validatingParseDoc(%s,%s)=[%s]\n",ctx?qPrint(ctx-&gt;name()):"&lt;none&gt;",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1935</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//                                     md?qPrint(md-&gt;name()):"&lt;none&gt;",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1936</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//                                     qPrint(input));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1937</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("========== validating %s at line %d\n",qPrint(fileName),startLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1938</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("---------------- input --------------------\n%s\n----------- end input -------------------\n",qPrint(input));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1939</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1940</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// set initial token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1941</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a> = parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#aeaf8532d281e202aaf58eb8daa3e5742">resetToken</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1942</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1943</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ctx &amp;&amp; ctx!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a> &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1944</span><span class="doxyLineContent"><span class="doxyHighlight">      (ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a> ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1945</span><span class="doxyLineContent"><span class="doxyHighlight">       ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1946</span><span class="doxyLineContent"><span class="doxyHighlight">      )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1947</span><span class="doxyLineContent"><span class="doxyHighlight">     )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1948</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1949</span><span class="doxyLineContent"><span class="doxyHighlight">    parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a440e2d11196fe51c4b5bc991345d866d">context</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>(),<a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>(ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>(),</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">),</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1950</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1951</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ctx &amp;&amp; ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eaabb46c37c736d27a367f4ea582a667ca">Definition::TypePage</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1952</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1953</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope = (<a href="/web-doxygen/docs/api/files/src/pagedef-cpp/#a7697e578ee832ee5d8e992bf6dc93617">toPageDef</a>(ctx))-&gt;getPageScope();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1954</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope &amp;&amp; scope!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1955</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1956</span><span class="doxyLineContent"><span class="doxyHighlight">      parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a440e2d11196fe51c4b5bc991345d866d">context</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),<a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>(scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>(),</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">),</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1957</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1958</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1959</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ctx &amp;&amp; ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eade4f51e436ce466a886244c7a4c373eb">Definition::TypeGroup</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1960</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1961</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *scope = (<a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a>(ctx))-&gt;getGroupScope();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1962</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (scope &amp;&amp; scope!=<a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1963</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1964</span><span class="doxyLineContent"><span class="doxyHighlight">      parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a440e2d11196fe51c4b5bc991345d866d">context</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>(),<a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>(scope-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>(),</span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">),</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1965</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1966</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1967</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1968</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1969</span><span class="doxyLineContent"><span class="doxyHighlight">    parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a440e2d11196fe51c4b5bc991345d866d">context</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1970</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1971</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a6a6d3121e0f44479868da6c290db6766">scope</a> = ctx;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1972</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a9fc77f516caaacac57c0ddc2ef5850a3">lang</a> = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1973</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1974</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (indexWords &amp;&amp; <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.enabled())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1975</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1976</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1977</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1978</span><span class="doxyLineContent"><span class="doxyHighlight">      parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#aa2bfd37ddbdec7e8751e6585cc53beb8">searchUrl</a>=md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1979</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.setCurrentDoc(md,md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1980</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1981</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ctx)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1982</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1983</span><span class="doxyLineContent"><span class="doxyHighlight">      parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#aa2bfd37ddbdec7e8751e6585cc53beb8">searchUrl</a>=ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1984</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>.setCurrentDoc(ctx,ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">anchor</a>(),</span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1985</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1986</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1987</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1988</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1989</span><span class="doxyLineContent"><span class="doxyHighlight">    parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#aa2bfd37ddbdec7e8751e6585cc53beb8">searchUrl</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1990</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1991</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1992</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a2b4c522f7f52850b1956b1b1504c4f1b">fileName</a> = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1993</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a603ea82abcc694bf2aeb91d85378aa0d">relPath</a> = (!linkFromIndex &amp;&amp; ctx) ?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1994</span><span class="doxyLineContent"><span class="doxyHighlight">               <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(<a href="/web-doxygen/docs/api/files/src/util-cpp/#a6cc78f4946029df8c7135fbf36e625e4">relativePathToRoot</a>(ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>())) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1995</span><span class="doxyLineContent"><span class="doxyHighlight">               <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1996</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("ctx-&gt;name=%s relPath=%s\n",qPrint(ctx-&gt;name()),qPrint(parser-&gt;context.relPath));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1997</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ae353d958ff093eac18151351deaebf42">memberDef</a> = md;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1998</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c4b8ce9d77e0e425ea3191235ec27a">nodeStack</a>.empty()) parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c4b8ce9d77e0e425ea3191235ec27a">nodeStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">1999</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">styleStack</a>.empty()) parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">styleStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2000</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8e520e4b1b8b7a5e76c91b618fea071e">initialStyleStack</a>.empty()) parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8e520e4b1b8b7a5e76c91b618fea071e">initialStyleStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2001</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a9e9561c7ec0edba0d50cdcb482942bea">inSeeBlock</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2002</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a5b98ca02af34e324862e5b5b8bbfb207">xmlComment</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2003</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a88cb2bde6d7f9ded45c9d33f33b65bb3">insideHtmlLink</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2004</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a741637628985f24ccf69b051638804ca">includeFileText</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2005</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ad7292216a7f27bb942f5e2a29d661526">includeFileOffset</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2006</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a084f5a404c6d0e3af240a514a40ea028">includeFileLength</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2007</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#aa499773e2ac0458b4f616b07386e5685">isExample</a> = isExample;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2008</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a688f0551d40b6f51fb0daaa76631502b">exampleName</a> = exampleName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2009</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">hasParamCommand</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2010</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ae20ce1c3e50ef1b4399b50f29f61607f">hasReturnCommand</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2011</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a0040f57941740a96566faa6d223d5bcb">retvalsFound</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2012</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c9e8118731d26df0aaf5da3795fd4f">paramsFound</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2013</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ac471382981c9338c82ac73b036d7a3ff">markdownSupport</a> = markdownSupport;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2014</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a87c34f5f92f5f414033ccaa71701a879">autolinkSupport</a> = autolinkSupport;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2015</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2016</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Starting comment block at %s:%d\n",qPrint(parser-&gt;context.fileName),startLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2017</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a2ffd450e14852a41762e405e33efed7d">setLineNr</a>(startLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2018</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ioLen = input.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2019</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> inpStr = parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">processCopyDoc</a>(input.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),ioLen);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2020</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inpStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>() || inpStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(inpStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1)!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2021</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2022</span><span class="doxyLineContent"><span class="doxyHighlight">    inpStr+=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2023</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2024</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("processCopyDoc(in='%s' out='%s')\n",input,qPrint(inpStr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2025</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a27ef42f7f738e8eef6801d5f701b4b8f">init</a>(inpStr.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a2b4c522f7f52850b1956b1b1504c4f1b">fileName</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2026</span><span class="doxyLineContent"><span class="doxyHighlight">                         parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ac471382981c9338c82ac73b036d7a3ff">markdownSupport</a>,parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a88cb2bde6d7f9ded45c9d33f33b65bb3">insideHtmlLink</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2027</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2028</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// build abstract syntax tree</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2029</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ast = std::make_unique&lt;DocNodeAST&gt;(<a href="/web-doxygen/docs/api/classes/docroot">DocRoot</a>(parser,md!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,singleLine));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2030</span><span class="doxyLineContent"><span class="doxyHighlight">  std::get&lt;DocRoot&gt;(ast-&gt;root).parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2031</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2032</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da92b8cea26e6d5e2a5d3d04b63686bb2b">Debug::PrintTree</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2033</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2034</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// pretty print the result</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2035</span><span class="doxyLineContent"><span class="doxyHighlight">    std::visit(<a href="/web-doxygen/docs/api/classes/printdocvisitor">PrintDocVisitor</a>{},ast-&gt;root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2036</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2037</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2038</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (md &amp;&amp; md-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#a5e6ace25ee464a601e1b3f2b8016ddad">isFunction</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2039</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2040</span><span class="doxyLineContent"><span class="doxyHighlight">    parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">checkUnOrMultipleDocumentedParams</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2041</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2042</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ae353d958ff093eac18151351deaebf42">memberDef</a>) parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ae353d958ff093eac18151351deaebf42">memberDef</a>-&gt;<a href="/web-doxygen/docs/api/classes/memberdef/#ae191114ab6407a74711b5dad045a20c9">detectUndocumentedParams</a>(parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">hasParamCommand</a>,parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ae20ce1c3e50ef1b4399b50f29f61607f">hasReturnCommand</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2043</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2044</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// reset token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2045</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#aeaf8532d281e202aaf58eb8daa3e5742">resetToken</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2046</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2047</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("&gt;&gt;&gt;&gt;&gt;&gt; end validatingParseDoc(%s,%s)\n",ctx?qPrint(ctx-&gt;name()):"&lt;none&gt;",</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2048</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//                                     md?qPrint(md-&gt;name()):"&lt;none&gt;");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2049</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2050</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ast;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2051</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/definition/#a56e91f9b76f41208a22cfb2336871604">Definition::anchor</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a87c34f5f92f5f414033ccaa71701a879">DocParserContext::autolinkSupport</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a9ca6efdbb8e10b7908ad6906f26ff1bd">DocParser::checkUnOrMultipleDocumentedParams</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a440e2d11196fe51c4b5bc991345d866d">DocParserContext::context</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#ae191114ab6407a74711b5dad045a20c9">MemberDef::detectUndocumentedParams</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a688f0551d40b6f51fb0daaa76631502b">DocParserContext::exampleName</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a2b4c522f7f52850b1956b1b1504c4f1b">DocParserContext::fileName</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a70414f815dfe6f9b6605380312f0dbc2">Doxygen::globalScope</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">DocParserContext::hasParamCommand</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ae20ce1c3e50ef1b4399b50f29f61607f">DocParserContext::hasReturnCommand</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a084f5a404c6d0e3af240a514a40ea028">DocParserContext::includeFileLength</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ad7292216a7f27bb942f5e2a29d661526">DocParserContext::includeFileOffset</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a741637628985f24ccf69b051638804ca">DocParserContext::includeFileText</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a27ef42f7f738e8eef6801d5f701b4b8f">DocTokenizer::init</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8e520e4b1b8b7a5e76c91b618fea071e">DocParserContext::initialStyleStack</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a9e9561c7ec0edba0d50cdcb482942bea">DocParserContext::inSeeBlock</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a88cb2bde6d7f9ded45c9d33f33b65bb3">DocParserContext::insideHtmlLink</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#aa499773e2ac0458b4f616b07386e5685">DocParserContext::isExample</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/memberdef/#a5e6ace25ee464a601e1b3f2b8016ddad">MemberDef::isFunction</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a9fc77f516caaacac57c0ddc2ef5850a3">DocParserContext::lang</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ac471382981c9338c82ac73b036d7a3ff">DocParserContext::markdownSupport</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ae353d958ff093eac18151351deaebf42">DocParserContext::memberDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c4b8ce9d77e0e425ea3191235ec27a">DocParserContext::nodeStack</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c9e8118731d26df0aaf5da3795fd4f">DocParserContext::paramsFound</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da92b8cea26e6d5e2a5d3d04b63686bb2b">Debug::PrintTree</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a6cc78f4946029df8c7135fbf36e625e4">relativePathToRoot</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a603ea82abcc694bf2aeb91d85378aa0d">DocParserContext::relPath</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#aeaf8532d281e202aaf58eb8daa3e5742">DocTokenizer::resetToken</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a0040f57941740a96566faa6d223d5bcb">DocParserContext::retvalsFound</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a6a6d3121e0f44479868da6c290db6766">DocParserContext::scope</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#ae3d8cc749e66634e3902def93f814d07">Doxygen::searchIndex</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#aa2bfd37ddbdec7e8751e6585cc53beb8">DocParserContext::searchUrl</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a2ffd450e14852a41762e405e33efed7d">DocTokenizer::setLineNr</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">DocParserContext::styleStack</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a>, <a href="/web-doxygen/docs/api/files/src/pagedef-cpp/#a7697e578ee832ee5d8e992bf6dc93617">toPageDef</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eade4f51e436ce466a886244c7a4c373eb">Definition::TypeGroup</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eaabb46c37c736d27a367f4ea582a667ca">Definition::TypePage</a> and <a href="/web-doxygen/docs/api/structs/docparsercontext/#a5b98ca02af34e324862e5b5b8bbfb207">DocParserContext::xmlComment</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/perlmodgen-cpp/#af0db6e1068b93a112848a208cf955b10">addPerlModDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/ftvhelp-cpp/#a53124fcb14c157228188e339625da475">generateBriefDoc</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ac371cebadb37ea8ab3ae59502036c427">OutputList::generateDoc</a>, <a href="/web-doxygen/docs/api/files/src/singlecomment-cpp/#ae8dd6bba2e9ad92dab454422a3136a26">generateHtmlOutput</a>, <a href="/web-doxygen/docs/api/files/src/sqlite3gen-cpp/#a088166e0f872cd290425780f4b5c45f6">getSQLDocBlock</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a336a6313626a3a3931e2086fd507bedc">parseCommentAsText</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5e4ee157b195e01006571421e974e6ae">ConceptDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/dirdefimpl/#ae0542f5746743ac8432bce5c33ce49e9">DirDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/filedefimpl/#a095d9cfd1d2c9744349cf2ebaf8e36ac">FileDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/groupdefimpl/#afe5e2e0fd77327686c9e2bb53761ae09">GroupDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aa971ee2e191c69cc2c456dd380b30970">ModuleDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/namespacedefimpl/#a71fe9eb6f290e8d1ec281e3bb9aa6f25">NamespaceDefImpl::writeBriefDescription</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a3ce80dae66a91da51b4a44ad1d5f3440">MemberDefImpl::writeDeclaration</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a5e115bcb69ec54c8107838c540f58231">ClassDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/conceptdefimpl/#a5ad45b87269607bace4adb282d8d0804">ConceptDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/moduledefimpl/#aecf1313398fd4c9d4440a741d9b3891d">ModuleDefImpl::writeDeclarationLink</a>, <a href="/web-doxygen/docs/api/classes/memberlist/#a65c0018e97550e259481590d8f9d5bee">MemberList::writePlainDeclarations</a> and <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a1f234d06f4ded36681d8976f055d5929">writeXMLDocBlock</a>.</p>

</div>
</div>

### validatingParseText() {#afd6219ce4bc112d331cd21cb79aefac7}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IDocNodeASTPtr validatingParseText (<a href="/web-doxygen/docs/api/classes/idocparser">IDocParser</a> &amp; parser, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Main entry point for parsing simple text fragments. These fragments are limited to words, whitespace and symbols.</p>


<p>Declaration at line 94 of file <a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>, definition at line 2105 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">2105</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a03066f1adfa357c8a7fa806069caa6ed">IDocNodeASTPtr</a> <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#a50b831629db52bab3309267c0a06b38b">validatingParseText</a>(<a href="/web-doxygen/docs/api/classes/idocparser">IDocParser</a> &amp;parserIntf,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;input)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2106</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2107</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *parser = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/docparser">DocParser</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(&amp;parserIntf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2108</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(parser!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2109</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parser==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2110</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2111</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// set initial token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2112</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a> = parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#aeaf8532d281e202aaf58eb8daa3e5742">resetToken</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2113</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2114</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("------------ input ---------\n%s\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2115</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//       "------------ end input -----\n",input);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2116</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//parser-&gt;context.token = new TokenInfo;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2117</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a440e2d11196fe51c4b5bc991345d866d">context</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2118</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a2b4c522f7f52850b1956b1b1504c4f1b">fileName</a> = </span><span class="doxyHighlightStringLiteral">"&lt;parseText&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2119</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a603ea82abcc694bf2aeb91d85378aa0d">relPath</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2120</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ae353d958ff093eac18151351deaebf42">memberDef</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2121</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c4b8ce9d77e0e425ea3191235ec27a">nodeStack</a>.empty()) parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c4b8ce9d77e0e425ea3191235ec27a">nodeStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2122</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">styleStack</a>.empty()) parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">styleStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2123</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8e520e4b1b8b7a5e76c91b618fea071e">initialStyleStack</a>.empty()) parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8e520e4b1b8b7a5e76c91b618fea071e">initialStyleStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2124</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a9e9561c7ec0edba0d50cdcb482942bea">inSeeBlock</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2125</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a5b98ca02af34e324862e5b5b8bbfb207">xmlComment</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2126</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a88cb2bde6d7f9ded45c9d33f33b65bb3">insideHtmlLink</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2127</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a741637628985f24ccf69b051638804ca">includeFileText</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2128</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ad7292216a7f27bb942f5e2a29d661526">includeFileOffset</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2129</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a084f5a404c6d0e3af240a514a40ea028">includeFileLength</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2130</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#aa499773e2ac0458b4f616b07386e5685">isExample</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2131</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a688f0551d40b6f51fb0daaa76631502b">exampleName</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2132</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">hasParamCommand</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2133</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ae20ce1c3e50ef1b4399b50f29f61607f">hasReturnCommand</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2134</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a0040f57941740a96566faa6d223d5bcb">retvalsFound</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2135</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c9e8118731d26df0aaf5da3795fd4f">paramsFound</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2136</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#aa2bfd37ddbdec7e8751e6585cc53beb8">searchUrl</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2137</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a9fc77f516caaacac57c0ddc2ef5850a3">lang</a> = SrcLangExt::Unknown;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2138</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ac471382981c9338c82ac73b036d7a3ff">markdownSupport</a> = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2139</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a87c34f5f92f5f414033ccaa71701a879">autolinkSupport</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2140</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2141</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2142</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ast = std::make_unique&lt;DocNodeAST&gt;(<a href="/web-doxygen/docs/api/classes/doctext">DocText</a>(parser));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2143</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2144</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!input.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2145</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2146</span><span class="doxyLineContent"><span class="doxyHighlight">    parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a2ffd450e14852a41762e405e33efed7d">setLineNr</a>(1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2147</span><span class="doxyLineContent"><span class="doxyHighlight">    parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#a27ef42f7f738e8eef6801d5f701b4b8f">init</a>(input.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a2b4c522f7f52850b1956b1b1504c4f1b">fileName</a>,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2148</span><span class="doxyLineContent"><span class="doxyHighlight">                           parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ac471382981c9338c82ac73b036d7a3ff">markdownSupport</a>,parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a88cb2bde6d7f9ded45c9d33f33b65bb3">insideHtmlLink</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2149</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2150</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// build abstract syntax tree</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2151</span><span class="doxyLineContent"><span class="doxyHighlight">    std::get&lt;DocText&gt;(ast-&gt;root).parse();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2152</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2153</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da92b8cea26e6d5e2a5d3d04b63686bb2b">Debug::PrintTree</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2154</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2155</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// pretty print the result</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2156</span><span class="doxyLineContent"><span class="doxyHighlight">      std::visit(<a href="/web-doxygen/docs/api/classes/printdocvisitor">PrintDocVisitor</a>{},ast-&gt;root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2157</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2158</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2159</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2160</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ast;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2161</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docparsercontext/#a87c34f5f92f5f414033ccaa71701a879">DocParserContext::autolinkSupport</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a440e2d11196fe51c4b5bc991345d866d">DocParserContext::context</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a688f0551d40b6f51fb0daaa76631502b">DocParserContext::exampleName</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a2b4c522f7f52850b1956b1b1504c4f1b">DocParserContext::fileName</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">DocParserContext::hasParamCommand</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ae20ce1c3e50ef1b4399b50f29f61607f">DocParserContext::hasReturnCommand</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a084f5a404c6d0e3af240a514a40ea028">DocParserContext::includeFileLength</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ad7292216a7f27bb942f5e2a29d661526">DocParserContext::includeFileOffset</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a741637628985f24ccf69b051638804ca">DocParserContext::includeFileText</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a27ef42f7f738e8eef6801d5f701b4b8f">DocTokenizer::init</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8e520e4b1b8b7a5e76c91b618fea071e">DocParserContext::initialStyleStack</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a9e9561c7ec0edba0d50cdcb482942bea">DocParserContext::inSeeBlock</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a88cb2bde6d7f9ded45c9d33f33b65bb3">DocParserContext::insideHtmlLink</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#aa499773e2ac0458b4f616b07386e5685">DocParserContext::isExample</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a9fc77f516caaacac57c0ddc2ef5850a3">DocParserContext::lang</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ac471382981c9338c82ac73b036d7a3ff">DocParserContext::markdownSupport</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ae353d958ff093eac18151351deaebf42">DocParserContext::memberDef</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c4b8ce9d77e0e425ea3191235ec27a">DocParserContext::nodeStack</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c9e8118731d26df0aaf5da3795fd4f">DocParserContext::paramsFound</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da92b8cea26e6d5e2a5d3d04b63686bb2b">Debug::PrintTree</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a603ea82abcc694bf2aeb91d85378aa0d">DocParserContext::relPath</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#aeaf8532d281e202aaf58eb8daa3e5742">DocTokenizer::resetToken</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a0040f57941740a96566faa6d223d5bcb">DocParserContext::retvalsFound</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#aa2bfd37ddbdec7e8751e6585cc53beb8">DocParserContext::searchUrl</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#a2ffd450e14852a41762e405e33efed7d">DocTokenizer::setLineNr</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">DocParserContext::styleStack</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a> and <a href="/web-doxygen/docs/api/structs/docparsercontext/#a5b98ca02af34e324862e5b5b8bbfb207">DocParserContext::xmlComment</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/rtfgenerator/#a8b7ec3b26aa3098463f3a6a2881f3394">RTFGenerator::endIndexSection</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#adfdcf2ba925f05be8beb8cf43deb168a">OutputList::parseText</a>.</p>

</div>
</div>

### validatingParseTitle() {#ad09a75bc25675328e8df85135924c6fa}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">IDocNodeASTPtr validatingParseTitle (<a href="/web-doxygen/docs/api/classes/idocparser">IDocParser</a> &amp; parserIntf, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int lineNr, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Main entry point for parsing titles. These allow limited markup commands</p>


<p>Declaration at line 98 of file <a href="/web-doxygen/docs/api/files/src/docparser-h">docparser.h</a>, definition at line 2053 of file <a href="/web-doxygen/docs/api/files/src/docparser-cpp">docparser.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">2053</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a03066f1adfa357c8a7fa806069caa6ed">IDocNodeASTPtr</a> <a href="/web-doxygen/docs/api/files/src/docparser-cpp/#ad09a75bc25675328e8df85135924c6fa">validatingParseTitle</a>(<a href="/web-doxygen/docs/api/classes/idocparser">IDocParser</a> &amp;parserIntf,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;input)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2054</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2055</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/docparser">DocParser</a> *parser = </span><span class="doxyHighlightKeyword">dynamic_cast&lt;</span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/docparser">DocParser</a>*</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(&amp;parserIntf);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2056</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(parser!=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2057</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (parser==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2058</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2059</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// set initial token</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2060</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">token</a> = parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">tokenizer</a>.<a href="/web-doxygen/docs/api/classes/doctokenizer/#aeaf8532d281e202aaf58eb8daa3e5742">resetToken</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2061</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2062</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("------------ input ---------\n%s\n"</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2063</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//       "------------ end input -----\n",input);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2064</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a440e2d11196fe51c4b5bc991345d866d">context</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2065</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a2b4c522f7f52850b1956b1b1504c4f1b">fileName</a> = fileName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2066</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a603ea82abcc694bf2aeb91d85378aa0d">relPath</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2067</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ae353d958ff093eac18151351deaebf42">memberDef</a> = </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2068</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c4b8ce9d77e0e425ea3191235ec27a">nodeStack</a>.empty()) parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c4b8ce9d77e0e425ea3191235ec27a">nodeStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2069</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">styleStack</a>.empty()) parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">styleStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2070</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (!parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8e520e4b1b8b7a5e76c91b618fea071e">initialStyleStack</a>.empty()) parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a8e520e4b1b8b7a5e76c91b618fea071e">initialStyleStack</a>.pop();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2071</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a9e9561c7ec0edba0d50cdcb482942bea">inSeeBlock</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2072</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a5b98ca02af34e324862e5b5b8bbfb207">xmlComment</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2073</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a88cb2bde6d7f9ded45c9d33f33b65bb3">insideHtmlLink</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2074</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a741637628985f24ccf69b051638804ca">includeFileText</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2075</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ad7292216a7f27bb942f5e2a29d661526">includeFileOffset</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2076</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a084f5a404c6d0e3af240a514a40ea028">includeFileLength</a> = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2077</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#aa499773e2ac0458b4f616b07386e5685">isExample</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2078</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a688f0551d40b6f51fb0daaa76631502b">exampleName</a> = </span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2079</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">hasParamCommand</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2080</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ae20ce1c3e50ef1b4399b50f29f61607f">hasReturnCommand</a> = <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2081</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a0040f57941740a96566faa6d223d5bcb">retvalsFound</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2082</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c9e8118731d26df0aaf5da3795fd4f">paramsFound</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2083</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#aa2bfd37ddbdec7e8751e6585cc53beb8">searchUrl</a>=</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2084</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a9fc77f516caaacac57c0ddc2ef5850a3">lang</a> = SrcLangExt::Unknown;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2085</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#ac471382981c9338c82ac73b036d7a3ff">markdownSupport</a> = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(MARKDOWN_SUPPORT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2086</span><span class="doxyLineContent"><span class="doxyHighlight">  parser-&gt;<a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">context</a>.<a href="/web-doxygen/docs/api/structs/docparsercontext/#a87c34f5f92f5f414033ccaa71701a879">autolinkSupport</a> = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2087</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2088</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> ast = std::make_unique&lt;DocNodeAST&gt;(<a href="/web-doxygen/docs/api/classes/doctitle">DocTitle</a>(parser,</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2089</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2090</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!input.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2091</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2092</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// build abstract syntax tree from title string</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2093</span><span class="doxyLineContent"><span class="doxyHighlight">    std::get&lt;DocTitle&gt;(ast-&gt;root).parseFromString(</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,input);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2094</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2095</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da92b8cea26e6d5e2a5d3d04b63686bb2b">Debug::PrintTree</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2096</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2097</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// pretty print the result</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2098</span><span class="doxyLineContent"><span class="doxyHighlight">      std::visit(<a href="/web-doxygen/docs/api/classes/printdocvisitor">PrintDocVisitor</a>{},ast-&gt;root);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2099</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2100</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2101</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2102</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> ast;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2103</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/docparsercontext/#a87c34f5f92f5f414033ccaa71701a879">DocParserContext::autolinkSupport</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/classes/docparser/#ad6738a87a82c364cedd836a084394960">DocParser::context</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a440e2d11196fe51c4b5bc991345d866d">DocParserContext::context</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a688f0551d40b6f51fb0daaa76631502b">DocParserContext::exampleName</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a2b4c522f7f52850b1956b1b1504c4f1b">DocParserContext::fileName</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#adfc69df470290ef49cf32d0e6cd83556">DocParserContext::hasParamCommand</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ae20ce1c3e50ef1b4399b50f29f61607f">DocParserContext::hasReturnCommand</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a084f5a404c6d0e3af240a514a40ea028">DocParserContext::includeFileLength</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ad7292216a7f27bb942f5e2a29d661526">DocParserContext::includeFileOffset</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a741637628985f24ccf69b051638804ca">DocParserContext::includeFileText</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8e520e4b1b8b7a5e76c91b618fea071e">DocParserContext::initialStyleStack</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a9e9561c7ec0edba0d50cdcb482942bea">DocParserContext::inSeeBlock</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a88cb2bde6d7f9ded45c9d33f33b65bb3">DocParserContext::insideHtmlLink</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#aa499773e2ac0458b4f616b07386e5685">DocParserContext::isExample</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a9fc77f516caaacac57c0ddc2ef5850a3">DocParserContext::lang</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ac471382981c9338c82ac73b036d7a3ff">DocParserContext::markdownSupport</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#ae353d958ff093eac18151351deaebf42">DocParserContext::memberDef</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c4b8ce9d77e0e425ea3191235ec27a">DocParserContext::nodeStack</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a60c9e8118731d26df0aaf5da3795fd4f">DocParserContext::paramsFound</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da92b8cea26e6d5e2a5d3d04b63686bb2b">Debug::PrintTree</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a603ea82abcc694bf2aeb91d85378aa0d">DocParserContext::relPath</a>, <a href="/web-doxygen/docs/api/classes/doctokenizer/#aeaf8532d281e202aaf58eb8daa3e5742">DocTokenizer::resetToken</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a0040f57941740a96566faa6d223d5bcb">DocParserContext::retvalsFound</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#aa2bfd37ddbdec7e8751e6585cc53beb8">DocParserContext::searchUrl</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a00b654ab5913a22f3c0add04642776ff">DocParserContext::styleStack</a>, <a href="/web-doxygen/docs/api/structs/docparsercontext/#a8da54182d40bdc81e85cd29db88230b6">DocParserContext::token</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a31ff77e4308ae2b7691a8381736201d1">DocParser::tokenizer</a> and <a href="/web-doxygen/docs/api/structs/docparsercontext/#a5b98ca02af34e324862e5b5b8bbfb207">DocParserContext::xmlComment</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/util-cpp/#a24141a97ca3b089d108db4129d4047f6">parseCommentAsHtml</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
