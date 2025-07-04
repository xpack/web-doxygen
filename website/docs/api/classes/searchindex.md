---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/searchindex
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `SearchIndex` Class Reference

<p>Writes search index for doxygen provided server based search engine that uses PHP. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class SearchIndex { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/searchindex-h">src/searchindex.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8204a0f9ad5a7f7ecfbe5d4617613294">SearchIndex</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac8f6bb104126c1406d2d6e5ad368822c">setCurrentDoc</a> (const Definition *ctx, const QCString &amp;anchor, bool isSourceFile)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3682b0b970d4422622723a8abe4d35ca">addWord</a> (const QCString &amp;word, bool hiPriority)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac64814075d6e3f962df64b5f13ecff32">write</a> (const QCString &amp;file)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a32913d63f72fe21010e49b4f77bc5cfd">addWordRec</a> (const QCString &amp;word, bool hiPrio, bool recurse)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a94c8476a68e3394f72ffe2d0dea68518">m_words</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; std::vector&lt; <a href="/web-doxygen/docs/api/classes/searchindex/indexword">IndexWord</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, int &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa06f7bb4f5d2ed2dee01f390446be6c2">m_url2IdMap</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::map&lt; int, <a href="/web-doxygen/docs/api/structs/searchindex/url">URL</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2d410345f7d657bb9d6a1ba014f09560">m_urls</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a40461e0e23f44bd6c1ec8fd42fd3a54e">m_urlIndex</a> = -1</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac48958318e80356f3dd535cdf564dbe3">m_urlMaxIndex</a> = 0</td>
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

<p>Writes search index for doxygen provided server based search engine that uses PHP.</p>

<p>Definition at line 65 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### SearchIndex() {#a8204a0f9ad5a7f7ecfbe5d4617613294}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">SearchIndex::SearchIndex ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 96 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>, definition at line 69 of file <a href="/web-doxygen/docs/api/files/src/searchindex-cpp">searchindex.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8204a0f9ad5a7f7ecfbe5d4617613294">69</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a8204a0f9ad5a7f7ecfbe5d4617613294">SearchIndex::SearchIndex</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>.resize(<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a99ffca8320d09c3e2c5ce800855f1469">numIndexEntries</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a> and <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a99ffca8320d09c3e2c5ce800855f1469">numIndexEntries</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addWord() {#a3682b0b970d4422622723a8abe4d35ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SearchIndex::addWord (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; word, bool hiPriority)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 98 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>, definition at line 236 of file <a href="/web-doxygen/docs/api/files/src/searchindex-cpp">searchindex.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3682b0b970d4422622723a8abe4d35ca">236</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a3682b0b970d4422622723a8abe4d35ca">SearchIndex::addWord</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;word,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hiPriority)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a327880ec7a71c2658cfa974939ddef30">g_searchIndexMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a32913d63f72fe21010e49b4f77bc5cfd">addWordRec</a>(word,hiPriority,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a32913d63f72fe21010e49b4f77bc5cfd">addWordRec</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a> and <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a327880ec7a71c2658cfa974939ddef30">g_searchIndexMutex</a>.</p>

</div>
</div>

### setCurrentDoc() {#ac8f6bb104126c1406d2d6e5ad368822c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SearchIndex::setCurrentDoc (const <a href="/web-doxygen/docs/api/classes/definition">Definition</a> * ctx, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; anchor, bool isSourceFile)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 97 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>, definition at line 74 of file <a href="/web-doxygen/docs/api/files/src/searchindex-cpp">searchindex.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac8f6bb104126c1406d2d6e5ad368822c">74</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac8f6bb104126c1406d2d6e5ad368822c">SearchIndex::setCurrentDoc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition">Definition</a> *ctx,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;anchor,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isSourceFile)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ctx==</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard&lt;std::mutex&gt; lock(<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a327880ec7a71c2658cfa974939ddef30">g_searchIndexMutex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">  assert(!isSourceFile || ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("SearchIndex::setCurrentDoc(%s,%s,%s)\n",name,baseName,anchor);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> url=isSourceFile ? (<a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>(ctx))-&gt;getSourceFileBase() : ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">getOutputFileBase</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">  url+=<a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(HTML_FILE_EXTENSION);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> baseUrl = url;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!anchor.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) url+=<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(</span><span class="doxyHighlightStringLiteral">"#"</span><span class="doxyHighlight">)+anchor;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!isSourceFile) baseUrl=url;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> name=ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">qualifiedName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>()==<a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/memberdef">MemberDef</a> *md = <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>(ctx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span><span class="doxyLineContent"><span class="doxyHighlight">    name.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>((md-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>()==SrcLangExt::Fortran  ?</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trSubprogram(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>) :</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlight">                 <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trMember(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>))+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// compound type</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang = ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">getLanguage</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> sep = <a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>(lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (sep!=</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">      name = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(name,</span><span class="doxyHighlightStringLiteral">"::"</span><span class="doxyHighlight">,sep);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (ctx-&gt;<a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">definitionType</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eaabb46c37c736d27a367f4ea582a667ca">Definition::TypePage</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/pagedef">PageDef</a> *pd = <a href="/web-doxygen/docs/api/files/src/pagedef-cpp/#a7697e578ee832ee5d8e992bf6dc93617">toPageDef</a>(ctx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (pd-&gt;<a href="/web-doxygen/docs/api/classes/pagedef/#a73c07c74e91e201e5c9dc6f60528f229">hasTitle</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">            name = <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPage(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+pd-&gt;<a href="/web-doxygen/docs/api/classes/pagedef/#aae487f3fd3ce36b104cb6b82e287cfaa">title</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">            name = <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPage(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+pd-&gt;<a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">name</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/classdef">ClassDef</a> *cd = <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>(ctx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">          name.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(cd-&gt;<a href="/web-doxygen/docs/api/classes/classdef/#a239fe977638806153345cd2411c28062">compoundTypeString</a>()+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::Java || lang==SrcLangExt::CSharp)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">            name = <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trPackage(name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (lang==SrcLangExt::Fortran)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">            name.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModule(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">            name.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trNamespace(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eade4f51e436ce466a886244c7a4c373eb">Definition::TypeGroup</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/groupdef">GroupDef</a> *gd = <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a>(ctx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a2caedefd187d92eb8c4afe01d403456e">groupTitle</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">            name = <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trGroup(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">+gd-&gt;<a href="/web-doxygen/docs/api/classes/groupdef/#a2caedefd187d92eb8c4afe01d403456e">groupTitle</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">            name.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trGroup(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea3a91bc6cdee1a47194d4e8be5ff00156">Definition::TypeModule</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">          name.<a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">prepend</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trModule(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>)+</span><span class="doxyHighlightStringLiteral">" "</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#aa06f7bb4f5d2ed2dee01f390446be6c2">m_url2IdMap</a>.find(baseUrl.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it == <a href="#aa06f7bb4f5d2ed2dee01f390446be6c2">m_url2IdMap</a>.end()) </span><span class="doxyHighlightComment">// new entry</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a40461e0e23f44bd6c1ec8fd42fd3a54e">m_urlIndex</a> = <a href="#ac48958318e80356f3dd535cdf564dbe3">m_urlMaxIndex</a>++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#aa06f7bb4f5d2ed2dee01f390446be6c2">m_url2IdMap</a>.emplace(baseUrl.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(),<a href="#a40461e0e23f44bd6c1ec8fd42fd3a54e">m_urlIndex</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2d410345f7d657bb9d6a1ba014f09560">m_urls</a>.emplace(<a href="#a40461e0e23f44bd6c1ec8fd42fd3a54e">m_urlIndex</a>,<a href="/web-doxygen/docs/api/structs/searchindex/url">URL</a>(name,url));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// existing entry</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a40461e0e23f44bd6c1ec8fd42fd3a54e">m_urlIndex</a>=it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a2d410345f7d657bb9d6a1ba014f09560">m_urls</a>.emplace(it-&gt;second,<a href="/web-doxygen/docs/api/structs/searchindex/url">URL</a>(name,url));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/classdef/#a239fe977638806153345cd2411c28062">ClassDef::compoundTypeString</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/classes/definition/#a526c39074637d4b17a3f67df56d961ff">Definition::definitionType</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a327880ec7a71c2658cfa974939ddef30">g_searchIndexMutex</a>, <a href="/web-doxygen/docs/api/classes/definition/#a0dda9f50f2f9754e6341a10373eafec7">Definition::getLanguage</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aab590e3dd52a9375bb3afe31dc6f8609">getLanguageSpecificSeparator</a>, <a href="/web-doxygen/docs/api/classes/definition/#acabecdc6bfda2015811eed5f3436322d">Definition::getOutputFileBase</a>, <a href="/web-doxygen/docs/api/classes/groupdef/#a2caedefd187d92eb8c4afe01d403456e">GroupDef::groupTitle</a>, <a href="/web-doxygen/docs/api/classes/pagedef/#a73c07c74e91e201e5c9dc6f60528f229">PageDef::hasTitle</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#aa06f7bb4f5d2ed2dee01f390446be6c2">m_url2IdMap</a>, <a href="#a40461e0e23f44bd6c1ec8fd42fd3a54e">m_urlIndex</a>, <a href="#ac48958318e80356f3dd535cdf564dbe3">m_urlMaxIndex</a>, <a href="#a2d410345f7d657bb9d6a1ba014f09560">m_urls</a>, <a href="/web-doxygen/docs/api/classes/definition/#afc4fb51052226ea23c2f51b6516a3525">Definition::name</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0a6a8fe99e596b149ee15138fa8dcf0c">QCString::prepend</a>, <a href="/web-doxygen/docs/api/classes/definition/#ac3bc44bb9d5b4c8d1957f06222a5e0d7">Definition::qualifiedName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/classes/pagedef/#aae487f3fd3ce36b104cb6b82e287cfaa">PageDef::title</a>, <a href="/web-doxygen/docs/api/files/src/classdef-cpp/#ac7e9d22a4c24e745c1ab16d0af527da2">toClassDef</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a4114c484f3ccea1048608b9caa9f51de">toFileDef</a>, <a href="/web-doxygen/docs/api/files/src/groupdef-cpp/#a81b6ac5e79beed572376b9aebfa96da5">toGroupDef</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#af5b90e1ee6115fc2c7c6ce672c3dd157">toMemberDef</a>, <a href="/web-doxygen/docs/api/files/src/pagedef-cpp/#a7697e578ee832ee5d8e992bf6dc93617">toPageDef</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eafa4d5f6cdc4791da57411cbcc8fa7654">Definition::TypeClass</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea203462c7d34ced15beac624562c2708e">Definition::TypeFile</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eade4f51e436ce466a886244c7a4c373eb">Definition::TypeGroup</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea422b8b811bcf8869a67732f9829d005b">Definition::TypeMember</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea3a91bc6cdee1a47194d4e8be5ff00156">Definition::TypeModule</a>, <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8ea35a2dfa1d3ce6c023cbddb4af2cd18bc">Definition::TypeNamespace</a> and <a href="/web-doxygen/docs/api/classes/definition/#aa41b6bc53dcf93ecf745698aaf15ef8eaabb46c37c736d27a367f4ea582a667ca">Definition::TypePage</a>.</p>

</div>
</div>

### write() {#ac64814075d6e3f962df64b5f13ecff32}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SearchIndex::write (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; file)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 99 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>, definition at line 257 of file <a href="/web-doxygen/docs/api/files/src/searchindex-cpp">searchindex.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac64814075d6e3f962df64b5f13ecff32">257</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ac64814075d6e3f962df64b5f13ecff32">SearchIndex::write</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size=4; </span><span class="doxyHighlightComment">// for the header</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">  size+=4*<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a99ffca8320d09c3e2c5ce800855f1469">numIndexEntries</a>; </span><span class="doxyHighlightComment">// for the index</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> wordsOffset = size;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// first pass: compute the size of the wordlist</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a99ffca8320d09c3e2c5ce800855f1469">numIndexEntries</a>;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;wlist = <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!wlist.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;iw : wlist)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> ws = iw.word().length()+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">        size+=ws+4; </span><span class="doxyHighlightComment">// word + url info list offset</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">      size+=1; </span><span class="doxyHighlightComment">// zero list terminator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// second pass: compute the offsets in the index</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> indexOffsets[<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a99ffca8320d09c3e2c5ce800855f1469">numIndexEntries</a>];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> offset=wordsOffset;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a99ffca8320d09c3e2c5ce800855f1469">numIndexEntries</a>;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;wlist = <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!wlist.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">      indexOffsets[i]=offset;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;iw : wlist)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">        offset+= iw.word().length()+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">        offset+=4; </span><span class="doxyHighlightComment">// word + offset to url info array</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">      offset+=1; </span><span class="doxyHighlightComment">// zero list terminator</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">      indexOffsets[i]=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> padding = size;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">  size = (size+3)&amp;~3; </span><span class="doxyHighlightComment">// round up to 4 byte boundary</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">  padding = size - padding;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  std::vector&lt;size_t&gt; wordStatOffsets(<a href="#a94c8476a68e3394f72ffe2d0dea68518">m_words</a>.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> count=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// third pass: compute offset to stats info for each word</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a99ffca8320d09c3e2c5ce800855f1469">numIndexEntries</a>;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;wlist = <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!wlist.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;iw : wlist)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("wordStatOffsets[%d]=%d\n",count,size);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">        wordStatOffsets[count++] = size;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">        size+=4 + iw.urls().size() * 8; </span><span class="doxyHighlightComment">// count + (url_index,freq) per url</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">  std::vector&lt;size_t&gt; urlOffsets(<a href="#a2d410345f7d657bb9d6a1ba014f09560">m_urls</a>.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;udi : <a href="#a2d410345f7d657bb9d6a1ba014f09560">m_urls</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">    urlOffsets[udi.first]=size;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">    size+=udi.second.name.length()+1+</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">          udi.second.url.length()+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Total size %x bytes (word=%x stats=%x urls=%x)\n",size,wordsOffset,statsOffset,urlsOffset);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// write header</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">    f.put(</span><span class="doxyHighlightCharLiteral">'D'</span><span class="doxyHighlight">); f.put(</span><span class="doxyHighlightCharLiteral">'O'</span><span class="doxyHighlight">); f.put(</span><span class="doxyHighlightCharLiteral">'X'</span><span class="doxyHighlight">); f.put(</span><span class="doxyHighlightCharLiteral">'S'</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// write index</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a99ffca8320d09c3e2c5ce800855f1469">numIndexEntries</a>;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a61aa3a8c310a432e4925f68741d9bb21">writeInt</a>(f,indexOffsets[i]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">338</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">339</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// write word lists</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">340</span><span class="doxyLineContent"><span class="doxyHighlight">    count=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">341</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a99ffca8320d09c3e2c5ce800855f1469">numIndexEntries</a>;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">342</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">343</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;wlist = <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">344</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!wlist.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">345</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">346</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;iw : wlist)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">347</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">348</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a0b6667c7bad976edc1ef63202c87defe">writeString</a>(f,iw.word());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">349</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a61aa3a8c310a432e4925f68741d9bb21">writeInt</a>(f,wordStatOffsets[count++]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">350</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">351</span><span class="doxyLineContent"><span class="doxyHighlight">        f.put(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">352</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">353</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">354</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// write extra padding bytes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">355</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;padding;i++) f.put(0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">356</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// write word statistics</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">357</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;i&lt;<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a99ffca8320d09c3e2c5ce800855f1469">numIndexEntries</a>;i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">358</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">359</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;wlist = <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>[i];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">360</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!wlist.empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">361</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">362</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;iw : wlist)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">363</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">364</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> numUrls = iw.urls().size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">365</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a61aa3a8c310a432e4925f68741d9bb21">writeInt</a>(f,numUrls);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">366</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;ui : iw.urls())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">367</span><span class="doxyLineContent"><span class="doxyHighlight">          {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">368</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a61aa3a8c310a432e4925f68741d9bb21">writeInt</a>(f,urlOffsets[ui.second.urlIdx]);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">369</span><span class="doxyLineContent"><span class="doxyHighlight">            <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a61aa3a8c310a432e4925f68741d9bb21">writeInt</a>(f,ui.second.freq);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">370</span><span class="doxyLineContent"><span class="doxyHighlight">          }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">371</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">372</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">373</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">374</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// write urls</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">375</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;udi : <a href="#a2d410345f7d657bb9d6a1ba014f09560">m_urls</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">376</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">377</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a0b6667c7bad976edc1ef63202c87defe">writeString</a>(f,udi.second.name);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">378</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a0b6667c7bad976edc1ef63202c87defe">writeString</a>(f,udi.second.url);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">379</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">380</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">381</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">382</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>, <a href="#a2d410345f7d657bb9d6a1ba014f09560">m_urls</a>, <a href="#a94c8476a68e3394f72ffe2d0dea68518">m_words</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a99ffca8320d09c3e2c5ce800855f1469">numIndexEntries</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a61aa3a8c310a432e4925f68741d9bb21">writeInt</a> and <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a0b6667c7bad976edc1ef63202c87defe">writeString</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### addWordRec() {#a32913d63f72fe21010e49b4f77bc5cfd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void SearchIndex::addWordRec (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; word, bool hiPrio, bool recurse)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 101 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>, definition at line 195 of file <a href="/web-doxygen/docs/api/files/src/searchindex-cpp">searchindex.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a32913d63f72fe21010e49b4f77bc5cfd">195</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a32913d63f72fe21010e49b4f77bc5cfd">SearchIndex::addWordRec</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;word,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hiPriority,</span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> recurse)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (word.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> wStr = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(word).<a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">lower</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("SearchIndex::addWord(%s,%d) wStr=%s\n",word,hiPriority,qPrint(wStr));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> idx=<a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a7d789071ce6a6464fb8ce89eb65083d3">charsToIndex</a>(wStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (idx&lt;0 || idx&gt;=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>.size())) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#a94c8476a68e3394f72ffe2d0dea68518">m_words</a>.find(wStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#a94c8476a68e3394f72ffe2d0dea68518">m_words</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//fprintf(stderr,"addWord(%s) at index %d\n",word,idx);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>[idx].emplace_back(wStr);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">    it = <a href="#a94c8476a68e3394f72ffe2d0dea68518">m_words</a>.emplace( wStr.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>(), </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>[idx].size())-1 ).first;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>[idx][it-&gt;second].addUrlIndex(<a href="#a40461e0e23f44bd6c1ec8fd42fd3a54e">m_urlIndex</a>,hiPriority);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!recurse) </span><span class="doxyHighlightComment">// the first time we check if we can strip the prefix</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=<a href="/web-doxygen/docs/api/files/src/util-cpp/#ae052d7dcea3289dd204d8d425cf9d4c9">getPrefixIndex</a>(word);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a32913d63f72fe21010e49b4f77bc5cfd">addWordRec</a>(word.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+i,hiPriority,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">      found=<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!found) </span><span class="doxyHighlightComment">// no prefix stripped</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (word[i]!=0 &amp;&amp;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">           !((word[i]==</span><span class="doxyHighlightCharLiteral">'_'</span><span class="doxyHighlight"> || word[i]==</span><span class="doxyHighlightCharLiteral">':'</span><span class="doxyHighlight"> || (word[i]&gt;=</span><span class="doxyHighlightCharLiteral">'a'</span><span class="doxyHighlight"> &amp;&amp; word[i]&lt;=</span><span class="doxyHighlightCharLiteral">'z'</span><span class="doxyHighlight">)) &amp;&amp;  </span><span class="doxyHighlightComment">// [_a-z:]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">             (word[i+1]&gt;=</span><span class="doxyHighlightCharLiteral">'A'</span><span class="doxyHighlight"> &amp;&amp; word[i+1]&lt;=</span><span class="doxyHighlightCharLiteral">'Z'</span><span class="doxyHighlight">)))                                 </span><span class="doxyHighlightComment">// [A-Z]</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">      i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (word[i]!=0 &amp;&amp; i&gt;=1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a32913d63f72fe21010e49b4f77bc5cfd">addWordRec</a>(word.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()+i+1,hiPriority,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a32913d63f72fe21010e49b4f77bc5cfd">addWordRec</a>, <a href="/web-doxygen/docs/api/files/src/searchindex-cpp/#a7d789071ce6a6464fb8ce89eb65083d3">charsToIndex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ae052d7dcea3289dd204d8d425cf9d4c9">getPrefixIndex</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a33688239622e659cfb469fbd62c9cccb">QCString::lower</a>, <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>, <a href="#a40461e0e23f44bd6c1ec8fd42fd3a54e">m_urlIndex</a>, <a href="#a94c8476a68e3394f72ffe2d0dea68518">m_words</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="#a3682b0b970d4422622723a8abe4d35ca">addWord</a> and <a href="#a32913d63f72fe21010e49b4f77bc5cfd">addWordRec</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_index {#a7d3b63b57ca232db7b18b1a5d9861101}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt; std::vector&lt; IndexWord&gt; &gt; SearchIndex::m_index</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 103 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7d3b63b57ca232db7b18b1a5d9861101">103</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt; std::vector&lt; IndexWord&gt; &gt; <a href="#a7d3b63b57ca232db7b18b1a5d9861101">m_index</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a32913d63f72fe21010e49b4f77bc5cfd">addWordRec</a>, <a href="#a8204a0f9ad5a7f7ecfbe5d4617613294">SearchIndex</a> and <a href="#ac64814075d6e3f962df64b5f13ecff32">write</a>.</p>

</div>
</div>

### m\_url2IdMap {#aa06f7bb4f5d2ed2dee01f390446be6c2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string,int&gt; SearchIndex::m_url2IdMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 104 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa06f7bb4f5d2ed2dee01f390446be6c2">104</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unordered_map&lt;std::string,int&gt; <a href="#aa06f7bb4f5d2ed2dee01f390446be6c2">m_url2IdMap</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ac8f6bb104126c1406d2d6e5ad368822c">setCurrentDoc</a>.</p>

</div>
</div>

### m\_urlIndex {#a40461e0e23f44bd6c1ec8fd42fd3a54e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SearchIndex::m_urlIndex = -1</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 106 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a40461e0e23f44bd6c1ec8fd42fd3a54e">106</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a40461e0e23f44bd6c1ec8fd42fd3a54e">m_urlIndex</a> = -1;</span></span></div>

</div>


<p>Referenced by <a href="#a32913d63f72fe21010e49b4f77bc5cfd">addWordRec</a> and <a href="#ac8f6bb104126c1406d2d6e5ad368822c">setCurrentDoc</a>.</p>

</div>
</div>

### m\_urlMaxIndex {#ac48958318e80356f3dd535cdf564dbe3}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int SearchIndex::m_urlMaxIndex = 0</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 107 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac48958318e80356f3dd535cdf564dbe3">107</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#ac48958318e80356f3dd535cdf564dbe3">m_urlMaxIndex</a> = 0;</span></span></div>

</div>


<p>Referenced by <a href="#ac8f6bb104126c1406d2d6e5ad368822c">setCurrentDoc</a>.</p>

</div>
</div>

### m\_urls {#a2d410345f7d657bb9d6a1ba014f09560}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::map&lt;int,URL&gt; SearchIndex::m_urls</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 105 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2d410345f7d657bb9d6a1ba014f09560">105</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::map&lt;int,URL&gt; <a href="#a2d410345f7d657bb9d6a1ba014f09560">m_urls</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ac8f6bb104126c1406d2d6e5ad368822c">setCurrentDoc</a> and <a href="#ac64814075d6e3f962df64b5f13ecff32">write</a>.</p>

</div>
</div>

### m\_words {#a94c8476a68e3394f72ffe2d0dea68518}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt;std::string,int&gt; SearchIndex::m_words</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 102 of file <a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a94c8476a68e3394f72ffe2d0dea68518">102</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unordered_map&lt;std::string,int&gt; <a href="#a94c8476a68e3394f72ffe2d0dea68518">m_words</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a32913d63f72fe21010e49b4f77bc5cfd">addWordRec</a> and <a href="#ac64814075d6e3f962df64b5f13ecff32">write</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/searchindex-cpp">searchindex.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/searchindex-h">searchindex.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
