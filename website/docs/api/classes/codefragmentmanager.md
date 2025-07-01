---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/codefragmentmanager
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `CodeFragmentManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class CodeFragmentManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/codefragment-h">src/codefragment.h</a>&gt;
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab4632a864ea279b13117ba0ce00a80c">CodeFragmentManager</a> ()</td>
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

## Private Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa265eeac1e211cdb969c3f0dc213ff6b">~CodeFragmentManager</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1aa709870f1258a753c2b952f95175be">parseCodeFragment</a> (OutputCodeList &amp;codeOutList, const QCString &amp;fileName, const QCString &amp;blockId, const QCString &amp;scopeName, bool showLineNumbers, bool trimLeft, bool stripCodeComments)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/codefragmentmanager/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ae86de07778bcb4412a419bb0dc1f47cd">p</a></td>
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

## Public Static Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/codefragmentmanager">CodeFragmentManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b0cbb8f093db7897882856c9172886e">instance</a> ()</td>
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


Definition at line 29 of file <a href="/web-doxygen/docs/api/files/src/codefragment-h">codefragment.h</a>.

<div class="doxySectionDef">

## Private Constructors

### CodeFragmentManager() {#aab4632a864ea279b13117ba0ce00a80c}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeFragmentManager::CodeFragmentManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 42 of file <a href="/web-doxygen/docs/api/files/src/codefragment-h">codefragment.h</a>, definition at line 183 of file <a href="/web-doxygen/docs/api/files/src/codefragment-cpp">codefragment.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aab4632a864ea279b13117ba0ce00a80c">183</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aab4632a864ea279b13117ba0ce00a80c">CodeFragmentManager::CodeFragmentManager</a>() : <a href="#ae86de07778bcb4412a419bb0dc1f47cd">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/codefragmentmanager/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#ae86de07778bcb4412a419bb0dc1f47cd">p</a>.

Referenced by <a href="#a6b0cbb8f093db7897882856c9172886e">instance</a> and <a href="#aa265eeac1e211cdb969c3f0dc213ff6b">\~CodeFragmentManager</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Destructor

### \~CodeFragmentManager() {#aa265eeac1e211cdb969c3f0dc213ff6b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeFragmentManager::~CodeFragmentManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/codefragment-h">codefragment.h</a>.

Reference <a href="#aab4632a864ea279b13117ba0ce00a80c">CodeFragmentManager</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### parseCodeFragment() {#a1aa709870f1258a753c2b952f95175be}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CodeFragmentManager::parseCodeFragment (<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; codeOutList, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; blockId, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName, bool showLineNumbers, bool trimLeft, bool stripCodeComments)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Declaration at line 33 of file <a href="/web-doxygen/docs/api/files/src/codefragment-h">codefragment.h</a>, definition at line 238 of file <a href="/web-doxygen/docs/api/files/src/codefragment-cpp">codefragment.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a1aa709870f1258a753c2b952f95175be">238</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a1aa709870f1258a753c2b952f95175be">CodeFragmentManager::parseCodeFragment</a>(<a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> &amp; codeOutList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; blockId,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; scopeName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">             showLineNumbers,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">             trimLeft,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">                                            </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight">             stripCodeComments</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">                                           )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"CodeFragmentManager::parseCodeFragment({},blockId={},scopeName={},showLineNumber={},trimLeft={},stripCodeComments={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      fileName, blockId, scopeName, showLineNumbers, trimLeft, stripCodeComments);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string fragmentKey=fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()+</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">+scopeName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">  std::unordered_map&lt; std::string,std::unique_ptr&lt;Private::FragmentInfo&gt; &gt;::iterator it;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> inserted = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// create new entry if it is not yet in the map</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">    std::lock_guard lock(<a href="#ae86de07778bcb4412a419bb0dc1f47cd">p</a>-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    it = <a href="#ae86de07778bcb4412a419bb0dc1f47cd">p</a>-&gt;fragments.find(fragmentKey);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it == <a href="#ae86de07778bcb4412a419bb0dc1f47cd">p</a>-&gt;fragments.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      it = <a href="#ae86de07778bcb4412a419bb0dc1f47cd">p</a>-&gt;fragments.emplace(fragmentKey, std::make_unique&lt;Private::FragmentInfo&gt;()).first;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">      inserted = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"new fragment"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// only lock the one item we are working with</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;codeFragment = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  std::lock_guard lock(codeFragment-&gt;mutex);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (inserted) </span><span class="doxyHighlightComment">// new entry, need to parse the file and record the output and cache it</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/types-h/#a9974623ce72fc23df5d64426b9178bf2">SrcLangExt</a> langExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> cfi( fileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> fd = <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>( cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">dirPath</a>(), cfi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>() );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">271</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> intf = <a href="/web-doxygen/docs/api/classes/doxygen/#a3882f6ce51621c77d409060e46cae378">Doxygen::parserManager</a>-&gt;getCodeParser(<a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>(fileName));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">272</span><span class="doxyLineContent"><span class="doxyHighlight">    intf-&gt;resetCodeParserState();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">273</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> filterSourceFiles = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(FILTER_SOURCE_FILES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">274</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> needs2PassParsing =</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">275</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/doxygen/#a19687ee2473747b1c587aa6c033daa6c">Doxygen::parseSourcesNeeded</a> &amp;&amp;                </span><span class="doxyHighlightComment">// we need to parse (filtered) sources for cross-references</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">276</span><span class="doxyLineContent"><span class="doxyHighlight">        !filterSourceFiles &amp;&amp;                         </span><span class="doxyHighlightComment">// but user wants to show sources as-is</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">277</span><span class="doxyLineContent"><span class="doxyHighlight">        !<a href="/web-doxygen/docs/api/files/src/util-cpp/#ad4426e053bb11589c58bd5c6828817e2">getFileFilter</a>(fileName,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>).<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>();     </span><span class="doxyHighlightComment">// and there is a filter used while parsing</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">278</span><span class="doxyLineContent"><span class="doxyHighlight">    codeFragment-&gt;fileContents = <a href="/web-doxygen/docs/api/files/src/codefragment-cpp/#a8c33a344ab42361aefb90541f2be4e6e">readTextFileByName</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">279</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//printf("fileContents=[%s]\n",qPrint(codeFragment-&gt;fileContents));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">280</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (needs2PassParsing)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">281</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">282</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/outputcodelist">OutputCodeList</a> devNullList;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">283</span><span class="doxyLineContent"><span class="doxyHighlight">      devNullList.<a href="/web-doxygen/docs/api/classes/outputcodelist/#a60b7d69b02fe400d0111a3321c9f0265">add</a>&lt;<a href="/web-doxygen/docs/api/classes/devnullcodegenerator">DevNullCodeGenerator</a>&gt;();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">      intf-&gt;parseCode(devNullList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">                      scopeName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">                      codeFragment-&gt;fileContents,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">                      langExt,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">                      stripCodeComments, </span><span class="doxyHighlightComment">// actually not important here</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span><span class="doxyLineContent"><span class="doxyHighlight">                      </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">                      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">                      );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">    codeFragment-&gt;findBlockMarkers();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (codeFragment-&gt;fileContents.length()&gt;0) </span><span class="doxyHighlightComment">// parse the normal version</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">      intf-&gt;parseCode(codeFragment-&gt;recorderCodeList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">          scopeName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">          codeFragment-&gt;fileContents,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">          langExt,            </span><span class="doxyHighlightComment">// lang</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,              </span><span class="doxyHighlightComment">// strip code comments (overruled before replaying)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">,              </span><span class="doxyHighlightComment">// isExampleBlock</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),         </span><span class="doxyHighlightComment">// exampleName</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">          fd.get(),           </span><span class="doxyHighlightComment">// fileDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">          -1,                 </span><span class="doxyHighlightComment">// startLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">          -1,                 </span><span class="doxyHighlightComment">// endLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,               </span><span class="doxyHighlightComment">// inlineFragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,            </span><span class="doxyHighlightComment">// memberDef</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">,               </span><span class="doxyHighlightComment">// showLineNumbers</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">,            </span><span class="doxyHighlightComment">// searchCtx</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">               </span><span class="doxyHighlightComment">// collectXRefs</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">          );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// use the recorded OutputCodeList from the cache to output a pre-recorded fragment</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> blockKv = codeFragment-&gt;blocksById.find(blockId.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (blockKv != codeFragment-&gt;blocksById.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;marker = blockKv-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> startLine = marker-&gt;lines[0];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> endLine   = marker-&gt;lines[1];</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indent    = marker-&gt;indent;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"replay(start={},end={},indent={}) fileContentsTrimLeft.empty()={}"</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">        startLine,endLine,indent,codeFragment-&gt;fileContentsTrimLeft.isEmpty());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> recorder = codeFragment-&gt;recorderCodeList.get&lt;<a href="/web-doxygen/docs/api/classes/outputcoderecorder">OutputCodeRecorder</a>&gt;(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a1aff765143dc4bf8ef68f698234e10f6">OutputType::Recorder</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">    recorder-&gt;<a href="/web-doxygen/docs/api/classes/outputcoderecorder/#a89166fa9eb6c282a2351da070e85fe63">replay</a>(codeOutList,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">                    startLine+1,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">                    endLine,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">                    showLineNumbers,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">                    stripCodeComments,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">                    trimLeft ? </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(indent) : 0</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">                   );</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">332</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">333</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">334</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">335</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO_TRACE_ADD</a>(</span><span class="doxyHighlightStringLiteral">"block not found!"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">336</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">337</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/outputcodelist/#a60b7d69b02fe400d0111a3321c9f0265">OutputCodeList::add</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO\_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a05be586784f268b947ad777aa316c4e6">AUTO\_TRACE\_ADD</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config\_getBool</a>, <a href="/web-doxygen/docs/api/files/src/filedef-cpp/#a3d27ebc7a7c763172f0ed0a7d7d56026">createFileDef</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#add9c23cbe0868fc947a85d157087de02">FileInfo::dirPath</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad4426e053bb11589c58bd5c6828817e2">getFileFilter</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#af18ed4687438f52f5c7fe9dfb226244c">getFileNameExtension</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a1b56719a14e986911d90aae56767dd5b">getLanguageFromFileName</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#ae86de07778bcb4412a419bb0dc1f47cd">p</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a3882f6ce51621c77d409060e46cae378">Doxygen::parserManager</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a19687ee2473747b1c587aa6c033daa6c">Doxygen::parseSourcesNeeded</a>, <a href="/web-doxygen/docs/api/files/src/codefragment-cpp/#a8c33a344ab42361aefb90541f2be4e6e">readTextFileByName</a>, <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a1aff765143dc4bf8ef68f698234e10f6">Recorder</a>, <a href="/web-doxygen/docs/api/classes/outputcoderecorder/#a89166fa9eb6c282a2351da070e85fe63">OutputCodeRecorder::replay</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#ae86de07778bcb4412a419bb0dc1f47cd}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; CodeFragmentManager::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



Definition at line 47 of file <a href="/web-doxygen/docs/api/files/src/codefragment-h">codefragment.h</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae86de07778bcb4412a419bb0dc1f47cd">47</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#ae86de07778bcb4412a419bb0dc1f47cd">p</a>;</span></span></div>

</div>


Referenced by <a href="#aab4632a864ea279b13117ba0ce00a80c">CodeFragmentManager</a> and <a href="#a1aa709870f1258a753c2b952f95175be">parseCodeFragment</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#a6b0cbb8f093db7897882856c9172886e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CodeFragmentManager &amp; CodeFragmentManager::instance ()</td>
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



Declaration at line 32 of file <a href="/web-doxygen/docs/api/files/src/codefragment-h">codefragment.h</a>, definition at line 189 of file <a href="/web-doxygen/docs/api/files/src/codefragment-cpp">codefragment.cpp</a>.

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6b0cbb8f093db7897882856c9172886e">189</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#aab4632a864ea279b13117ba0ce00a80c">CodeFragmentManager</a> &amp;<a href="#a6b0cbb8f093db7897882856c9172886e">CodeFragmentManager::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#aab4632a864ea279b13117ba0ce00a80c">CodeFragmentManager</a> m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> m;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


Reference <a href="#aab4632a864ea279b13117ba0ce00a80c">CodeFragmentManager</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5826ce8044be2553216f205ef64ead74">DocbookDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#abfd0aac31a863e63e61dc67da22a349c">HtmlDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ade1c6d00759ad30078d9f5a51cbfc009">LatexDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/mandocvisitor/#a103c34bd91c4bf67cadfca22f2b61466">ManDocVisitor::operator()</a>, <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ac315ddf81b73a005764278a3c190d1a4">RTFDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/classes/xmldocvisitor/#a32d2017f02e0835ea865360773ac1eda">XmlDocVisitor::operator()</a>.
</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/codefragment-cpp">codefragment.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/codefragment-h">codefragment.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
