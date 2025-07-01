---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/namespaces/trace
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - namespace
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Trace` Namespace Reference



## Definition

<div class="doxyDefinition">
namespace Trace { ... }
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1859b0ba7161e012fecbd71dd4ec64d6">trunc</a> (const QCString &amp;s, size_t numChars=15)</td>
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

### trunc() {#a1859b0ba7161e012fecbd71dd4ec64d6}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString Trace::trunc (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; s, size_t numChars=15)</td>
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



Definition at line 56 of file <a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1859b0ba7161e012fecbd71dd4ec64d6">56</a></span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">inline</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a1859b0ba7161e012fecbd71dd4ec64d6">trunc</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;s,</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/image-cpp/#a7039c6d467143b65eee4688f35178297">numChars</a>=15)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">59</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">60</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (; i&lt;<a href="/web-doxygen/docs/api/files/src/image-cpp/#a7039c6d467143b65eee4688f35178297">numChars</a> &amp;&amp; i&lt;s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>(); i++)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> c=s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(i);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight">      (c==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) { result+=</span><span class="doxyHighlightStringLiteral">"\\n"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\t'</span><span class="doxyHighlight">) { result+=</span><span class="doxyHighlightStringLiteral">"\\t"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\r'</span><span class="doxyHighlight">) { result+=</span><span class="doxyHighlightStringLiteral">"\\r"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (c==</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">) { result+=</span><span class="doxyHighlightStringLiteral">"\\\\"</span><span class="doxyHighlight">; }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> result+=c;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()) result+=</span><span class="doxyHighlightStringLiteral">"..."</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a> and <a href="/web-doxygen/docs/api/files/src/image-cpp/#a7039c6d467143b65eee4688f35178297">numChars</a>.

Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a00bea66ca12b6dc9dc1885d61542b87b">addClassToContext</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a681582d0e894782b9509baa541931151">Markdown::Private::addStrEscapeUtf8Nbsp</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a515c2b44ec8500cdb661ff5ab86c60af">computeIndentExcludingListMarkers</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3d4cb7f7e85f41df2eab7827e3bec33e">escapeDoubleQuotes</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a5ba50f3a46a2d635f06fbc600356ee4a">escapeSpecialChars</a>, <a href="/web-doxygen/docs/api/classes/markdown/#ac2acb2b59eeab5ffb2405f30b3c56476">Markdown::extractPageTitle</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a46231fc8d72391f38170f184dd956ed1">Markdown::Private::extractTitleId</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a5b661698b94e4b37748ee38025784690">Markdown::Private::findEmphasisChar</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aad2fb530e3d19a77de38a8c1b633b786">Markdown::Private::findEndOfLine</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a90640de61c785c42e3dc3787610b18eb">findTableColumns</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aae0b93eceac30fcc7b8bbb6795b588a2">handleParametersCommentBlocks</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a228aefe349d4d8c9272c606c9fbc8c81">hasLineBreak</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa8a42c32241bc89aa626ce55c23b7df5">Markdown::Private::isAtxHeader</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a6d7d4814ead5c919439c6b2d681e2ce7">Markdown::Private::isBlockCommand</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a32f3ae19472e55905bc21e27835568d5">isBlockQuote</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a76c8e357497a35b016ee0289e26ee0dd">isCodeBlock</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a7b54fef3d70eef54bd49dda068709f43">isEmptyLine</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a4808ea595b45102dac19491e80d2ac9c">isEndOfList</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a9ef42eb1068c60ccbe59ef0024ed1c90">isExplicitPage</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#acea395582e617dd69781da74f320161e">isFencedCodeBlock</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a5628c6052a120856d53921f8746d0251">Markdown::Private::isHeaderline</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad1f1abe1811f3c45c5b4ee867c15989f">isHRuler</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a3712f14d18ec5d547f7c55413abdb9fb">isLinkRef</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#ad0a6b598945a869cd184d17fe1f16812">isListMarker</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2e37305849fa544aff8f399a6f41c7b1">Markdown::Private::isSpecialCommand</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#aefadebc5df285d25ef8121a87639323e">isTableBlock</a>, <a href="/web-doxygen/docs/api/classes/docinclude/#a191446e0b57311d58cf1ef51a91417ee">DocInclude::parse</a>, <a href="/web-doxygen/docs/api/classes/docincoperator/#a468e20836d11e4cd9e62159e169acc68">DocIncOperator::parse</a>, <a href="/web-doxygen/docs/api/classes/commentscanner/#a2e48aae075e2f44ddd785428b4099f4a">CommentScanner::parseCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a3383c871b9fd5e4b1cf4a549de88a1f3">parseCompounds</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#a4e7dce846ca75b58d7010c2855a84ed6">parsePrototype</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9835402c2d15b122de1c3ba4180ebd58">Markdown::Private::processBlocks</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a42dc4e1d481af0574e750df55678d54d">Markdown::Private::processCodeSpan</a>, <a href="/web-doxygen/docs/api/classes/docparser/#a4b7d1c2724099f28c4f3a4c56c52d912">DocParser::processCopyDoc</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9ac768dc126226996971e96ef20923aa">Markdown::Private::processEmphasis</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a0bb20b07bce14eca215477b9ec05adbd">Markdown::Private::processEmphasis1</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#abbb763f2449b932ef3468560e30a0478">Markdown::Private::processEmphasis2</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a4041a1e946c4402894bfff49b611e63b">Markdown::Private::processEmphasis3</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a7ef2d648f867a25fac44f095b89630c6">Markdown::Private::processHtmlTag</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#aa4f4085dfd3e73ae354c7cfd6fa69faf">Markdown::Private::processHtmlTagWrite</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#ac0a9e3273eb76713a9e197d5be61e11a">Markdown::Private::processInline</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9b99b7f5084eb08d7ffe43f3fbe79d69">Markdown::Private::processLink</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#adafbef72995b1327272b82a2b2075480">Markdown::Private::processNmdash</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a9792322da9173be90556ef009d37afa4">Markdown::Private::processQuotations</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a0f211ac431de2f23ca4874c125ab1551">Markdown::Private::processQuoted</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a43b1695a69a83037471e5445c7c940ce">Markdown::Private::processSpecialCommand</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a2a97ed987f163573d91e6a46363c99de">Markdown::Private::writeBlockQuote</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a79fd3fae285ba1f1beeb84c8e858bf46">Markdown::Private::writeCodeBlock</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a494fc3fc6c848a37caa06e5d85854ffe">Markdown::Private::writeFencedCodeBlock</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#a1213861d8af699057686e457bce66509">Markdown::Private::writeMarkdownImage</a>, <a href="/web-doxygen/docs/api/structs/markdown/private/#af7ceebe6b90c368816a6d9bd0ca501c0">Markdown::Private::writeOneLineHeaderOrRuler</a> and <a href="/web-doxygen/docs/api/structs/markdown/private/#a21b82aade2e5a369ec438f0cd49f8107">Markdown::Private::writeTableBlock</a>.
</div>
</div>

</div>

<hr/>

The documentation for this namespace was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/trace-h">trace.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
