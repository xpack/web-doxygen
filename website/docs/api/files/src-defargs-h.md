---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/defargs-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `defargs.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/types-h">types.h</a>"
#include &lt;memory&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a88825bfb79a9c15e54ff57415b4de54d">stringToArgumentList</a> (SrcLangExt lang, const QCString &amp;argsString, QCString *extraTypeChars=nullptr)</td>
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

### stringToArgumentList() {#a88825bfb79a9c15e54ff57415b4de54d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt; ArgumentList &gt; stringToArgumentList (<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; argsString, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> * extraTypeChars=nullptr)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">




<p>Converts an argument string into an <a href="/web-doxygen/docs/api/classes/argumentlist">ArgumentList</a>.</p>


<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] lang</td>
<td class="doxyParamItemDescription"><p>language of the current argument list</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[in] argsString</td>
<td class="doxyParamItemDescription"><p>the list of Arguments.</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">[out] extraTypeChars</td>
<td class="doxyParamItemDescription"><p>point to string to which trailing characters for complex types are written to</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line 27 of file <a href="/web-doxygen/docs/api/files/src/defargs-h">defargs.h</a>, definition at line 814 of file <a href="/web-doxygen/docs/api/files/src/defargs-l">defargs.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a88825bfb79a9c15e54ff57415b4de54d">814</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::unique_ptr&lt;ArgumentList&gt; <a href="/web-doxygen/docs/api/files/src/defargs-l/#adcc79fb659af7f9b25501a5c166cea53">stringToArgumentList</a>(<a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> lang, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;argsString,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> *extraTypeChars)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">815</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">816</span><span class="doxyLineContent"><span class="doxyHighlight">  std::unique_ptr&lt;ArgumentList&gt; al = std::make_unique&lt;ArgumentList&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">817</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (argsString.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> al;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">818</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">819</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/code-l/#a9484188abbc459dafcbd4c96425fa70b">yyscan_t</a> yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">820</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/structs/defargsyy-state">defargsYY_state</a> extra(argsString.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>(),al,lang);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">821</span><span class="doxyLineContent"><span class="doxyHighlight">  defargsYYlex_init_extra(&amp;extra,&amp;yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">822</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#ifdef FLEX_DEBUG</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">823</span><span class="doxyLineContent"><span class="doxyHighlight">  defargsYYset_debug(<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da2dbbd7c420176dca999210d256d1e223">Debug::Lex_defargs</a>)?1:0,yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">824</span><span class="doxyLineContent"><span class="doxyHighlightPreprocessor">#endif</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">825</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t *yyg = (</span><span class="doxyHighlightKeyword">struct </span><span class="doxyHighlight">yyguts_t*)yyscanner;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">826</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debuglex">DebugLex</a> debugLex(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da2dbbd7c420176dca999210d256d1e223">Debug::Lex_defargs</a>, __FILE__, </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">827</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">828</span><span class="doxyLineContent"><span class="doxyHighlight">  defargsYYrestart( </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">, yyscanner );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">829</span><span class="doxyLineContent"><span class="doxyHighlight">  BEGIN( Start );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">830</span><span class="doxyLineContent"><span class="doxyHighlight">  defargsYYlex(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">831</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (yyextra-&gt;argList-&gt;empty())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">832</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">833</span><span class="doxyLineContent"><span class="doxyHighlight">    yyextra-&gt;argList-&gt;setNoParameters(<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">834</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">835</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (extraTypeChars) *extraTypeChars=yyextra-&gt;extraTypeChars;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">836</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("stringToArgumentList(%s) result=%s\n",argsString,qPrint(argListToString(*al)));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">837</span><span class="doxyLineContent"><span class="doxyHighlight">  defargsYYlex_destroy(yyscanner);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">838</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> al;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">839</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da2dbbd7c420176dca999210d256d1e223">Debug::Lex_defargs</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#a1f7c3408ea1bf71c19a8e593763d88f7">ClassDefImpl::addMemberToTemplateInstance</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#afb0da87d7d3ab2047204073d584974ad">buildDefineList</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ab72aa92f752458fe8b7b855b75cc5598">buildFunctionList</a>, <a href="/web-doxygen/docs/api/classes/anonymous-tagreader-cpp-/tagfileparser/#aa5dd16fd497d034a55fdca37a3c17804">anonymous{tagreader.cpp}::TagFileParser::buildMemberList</a>, <a href="/web-doxygen/docs/api/files/src/memberdef-cpp/#abaf3303e28a7a9e34bdcfbe4bfc893cb">combineDeclarationAndDefinition</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a0f3c855d0eed91d3e4f728d4beff4080">computeTemplateClassRelations</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#aa266ab08127667eabf8093a23e37ff9a">findMembersWithSpecificName</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3f26028922a120817dd5292aad1bcef4">findTemplateInstanceRelation</a>, <a href="/web-doxygen/docs/api/files/src/defgen-cpp/#a55c1d02b9b69cd2fe313413575cc3d2c">generateDEFForMember</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a2fdb07a3ae3b43c58c64eecb52ed866b">getDefsOld</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a40f0f9c9cb6b6b7392ae6e695fc74671">SymbolResolver::Private::getResolvedSymbol</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a41fdc2a524c5339afd35c067a828459d">SymbolResolver::Private::getResolvedSymbolRec</a>, <a href="/web-doxygen/docs/api/structs/symbolresolver/private/#a3aea62dc3d2f6c0e0109e5aefc155a41">SymbolResolver::Private::getResolvedTypeRec</a>, <a href="/web-doxygen/docs/api/classes/memberdefimpl/#a2dd347b6be51aa404a4e6bc679736606">MemberDefImpl::init</a>, <a href="/web-doxygen/docs/api/classes/classdefimpl/#af3eab25ba334db0ed299983b354a89cb">ClassDefImpl::insertTemplateInstance</a> and <a href="/web-doxygen/docs/api/files/src/util-cpp/#a52cc252e59332d38e224e11bd019f632">matchCanonicalTypes</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
