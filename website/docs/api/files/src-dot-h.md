---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/files/src/dot-h
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - file
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `dot.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;map&gt;
#include "<a href="/web-doxygen/docs/api/files/src/threadpool-h">threadpool.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/qcstring-h">qcstring.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotgraph-h">dotgraph.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotfilepatcher-h">dotfilepatcher.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/dotrunner-h">dotrunner.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/doxygen-h">doxygen.h</a>"
#include "<a href="/web-doxygen/docs/api/files/src/construct-h">construct.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/dotmanager">DotManager</a></td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Singleton that manages parallel dot invocations and patching files for embedding image maps. <a href="/web-doxygen/docs/api/classes/dotmanager/#details">More...</a></p>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aee48308a96887ccde586df24f0b73ca4">writeDotGraphFromFile</a> (const QCString &amp;inFile, const QCString &amp;outDir, const QCString &amp;outFile, GraphOutputFormat format, const QCString &amp;srcFile, int srcLine)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ada988a5303d67622cb43bd75c247fec2">writeDotImageMapFromFile</a> (TextStream &amp;t, const QCString &amp;inFile, const QCString &amp;outDir, const QCString &amp;relPath, const QCString &amp;baseName, const QCString &amp;context, int graphId, const QCString &amp;srcFile, int srcLine)</td>
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

### writeDotGraphFromFile() {#aee48308a96887ccde586df24f0b73ca4}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDotGraphFromFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inFile, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; outDir, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; outFile, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> format, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="#l00052">52</a> of file <a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dot-cpp/#l00230">230</a> of file <a href="/web-doxygen/docs/api/files/src/dot-cpp">dot.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/dot-cpp/#aee48308a96887ccde586df24f0b73ca4">230</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dot-cpp/#aee48308a96887ccde586df24f0b73ca4">writeDotGraphFromFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inFile,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;outDir,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;outFile,<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523f">GraphOutputFormat</a> format,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> d(outDir.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!d.<a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Output dir {} does not exist!\n"</span><span class="doxyHighlight">,outDir);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imgExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imgName = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(outFile)+</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">+imgExt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> absImgName = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(d.<a href="/web-doxygen/docs/api/classes/dir/#a226b0db1117e46393bbb241e545f8609">absPath</a>())+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+imgName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> absOutFile = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(d.<a href="/web-doxygen/docs/api/classes/dir/#a226b0db1117e46393bbb241e545f8609">absPath</a>())+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+outFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotrunner">DotRunner</a> dotRun(inFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (format==<a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">GraphOutputFormat::BITMAP</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">    dotRun.<a href="/web-doxygen/docs/api/classes/dotrunner/#aa225ccd454acbadc5b6a23d9534e574f">addJob</a>(<a href="/web-doxygen/docs/api/files/src/config-h/#a251399cde30dd4c356bbd5634c6eb472">Config_getEnumAsString</a>(DOT_IMAGE_FORMAT),absImgName,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// format==GraphOutputFormat::EPS</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(USE_PDFLATEX))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      dotRun.<a href="/web-doxygen/docs/api/classes/dotrunner/#aa225ccd454acbadc5b6a23d9534e574f">addJob</a>(</span><span class="doxyHighlightStringLiteral">"pdf"</span><span class="doxyHighlight">,absOutFile+</span><span class="doxyHighlightStringLiteral">".pdf"</span><span class="doxyHighlight">,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">      dotRun.<a href="/web-doxygen/docs/api/classes/dotrunner/#aa225ccd454acbadc5b6a23d9534e574f">addJob</a>(</span><span class="doxyHighlightStringLiteral">"ps"</span><span class="doxyHighlight">,absOutFile+</span><span class="doxyHighlightStringLiteral">".eps"</span><span class="doxyHighlight">,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">  dotRun.<a href="/web-doxygen/docs/api/classes/dotrunner/#a2c9b6af873f263c04913504d0f420274">preventCleanUp</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!dotRun.<a href="/web-doxygen/docs/api/classes/dotrunner/#ac1afaee16ddd8bf0bc6b18aaed6b44fd">run</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">     </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addImageFile(imgName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dir/#a226b0db1117e46393bbb241e545f8609">Dir::absPath</a>, <a href="/web-doxygen/docs/api/classes/dotrunner/#aa225ccd454acbadc5b6a23d9534e574f">DotRunner::addJob</a>, <a href="/web-doxygen/docs/api/files/src/dotgraph-h/#ac60ef98d62b78366a17c9f1bda96523fa75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a251399cde30dd4c356bbd5634c6eb472">Config&#95;getEnumAsString</a>, <a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">Dir::exists</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>, <a href="/web-doxygen/docs/api/classes/dotrunner/#a2c9b6af873f263c04913504d0f420274">DotRunner::preventCleanUp</a>, <a href="/web-doxygen/docs/api/classes/dotrunner/#ac1afaee16ddd8bf0bc6b18aaed6b44fd">DotRunner::run</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5e78b0ed5635b833b739d63dafe452ff">DocbookDocVisitor::startDotFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aa197e546b10f737e78020b97fdf23cb9">LatexDocVisitor::startDotFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a0bf39b3fd2c1a92324de55df8009ed60">DocbookDocVisitor::writeDotFile</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a3264ee5213c549e45cd13604e62e7719">HtmlDocVisitor::writeDotFile</a> and <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#a286a80b0680a1b0defb947466bea6762">RTFDocVisitor::writeDotFile</a>.
</div>
</div>

### writeDotImageMapFromFile() {#ada988a5303d67622cb43bd75c247fec2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeDotImageMapFromFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inFile, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; outDir, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; baseName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; context, int graphId, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Writes user defined image map to the output.</p>

<dl class="doxyParamsList">
<dt class="doxyParamsTableTitle">Parameters</dt>
<dd>
<table class="doxyParamsTable">
<tr class="doxyParamItem">
<td class="doxyParamItemName">t</td>
<td class="doxyParamItemDescription"><p>text stream to write to</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">inFile</td>
<td class="doxyParamItemDescription"><p>just the basename part of the filename</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">outDir</td>
<td class="doxyParamItemDescription"><p>output directory</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">relPath</td>
<td class="doxyParamItemDescription"><p>relative path the to root of the output dir</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">baseName</td>
<td class="doxyParamItemDescription"><p>the base name of the output files</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">context</td>
<td class="doxyParamItemDescription"><p>the scope in which this graph is found (for resolving links)</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">graphId</td>
<td class="doxyParamItemDescription"><p>a unique id for this graph, use for dynamic sections</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">srcFile</td>
<td class="doxyParamItemDescription"><p>the source file</p></td>
</tr>
<tr class="doxyParamItem">
<td class="doxyParamItemName">srcLine</td>
<td class="doxyParamItemDescription"><p>the line number in the source file</p></td>
</tr>
</table>
</dd>
</dl>

<p>Declaration at line <a href="#l00055">55</a> of file <a href="/web-doxygen/docs/api/files/src/dot-h">dot.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dot-cpp/#l00283">283</a> of file <a href="/web-doxygen/docs/api/files/src/dot-cpp">dot.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/dot-cpp/#ada988a5303d67622cb43bd75c247fec2">283</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/dot-cpp/#ada988a5303d67622cb43bd75c247fec2">writeDotImageMapFromFile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">284</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inFile, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;outDir,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">285</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath, </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">286</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;context,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> graphId,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">287</span><span class="doxyLineContent"><span class="doxyHighlight">                            </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">288</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">289</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">290</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> d(outDir.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">291</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!d.<a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">292</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">293</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Output dir {} does not exist!\n"</span><span class="doxyHighlight">,outDir);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">294</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">295</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">296</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mapName = baseName+</span><span class="doxyHighlightStringLiteral">".map"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">297</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imgExt = <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">298</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imgName = baseName+</span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">+imgExt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">299</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> absOutFile = <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(d.<a href="/web-doxygen/docs/api/classes/dir/#a226b0db1117e46393bbb241e545f8609">absPath</a>())+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+mapName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">300</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">301</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dotrunner">DotRunner</a> dotRun(inFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">302</span><span class="doxyLineContent"><span class="doxyHighlight">  dotRun.<a href="/web-doxygen/docs/api/classes/dotrunner/#aa225ccd454acbadc5b6a23d9534e574f">addJob</a>(<a href="/web-doxygen/docs/api/files/src/dot-cpp/#a8e61450eb94b16e866568ad3aed2d9f1">MAP_CMD</a>,absOutFile,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">303</span><span class="doxyLineContent"><span class="doxyHighlight">  dotRun.<a href="/web-doxygen/docs/api/classes/dotrunner/#a2c9b6af873f263c04913504d0f420274">preventCleanUp</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">304</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!dotRun.<a href="/web-doxygen/docs/api/classes/dotrunner/#ac1afaee16ddd8bf0bc6b18aaed6b44fd">run</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">305</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">306</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">307</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">308</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">309</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (imgExt==</span><span class="doxyHighlightStringLiteral">"svg"</span><span class="doxyHighlight">) </span><span class="doxyHighlightComment">// vector graphics</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">310</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">311</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> svgName = outDir+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+baseName+</span><span class="doxyHighlightStringLiteral">".svg"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">312</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#ae41b4e8b1817e1d1de1732e4c4f9069c">DotFilePatcher::writeSVGFigureLink</a>(t,relPath,baseName,svgName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">313</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotfilepatcher">DotFilePatcher</a> patcher(svgName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">314</span><span class="doxyLineContent"><span class="doxyHighlight">    patcher.<a href="/web-doxygen/docs/api/classes/dotfilepatcher/#aac97171a3985fd07e09fef2a25819a16">addSVGConversion</a>(</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,context,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>,graphId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">315</span><span class="doxyLineContent"><span class="doxyHighlight">    patcher.<a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">run</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">316</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">317</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// bitmap graphics</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">318</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">319</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> tt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">320</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;img src=\""</span><span class="doxyHighlight"> &lt;&lt; relPath &lt;&lt; imgName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" alt=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">321</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; imgName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" border=\"0\" usemap=\"#"</span><span class="doxyHighlight"> &lt;&lt; mapName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">322</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>(tt, absOutFile, relPath ,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, context);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">323</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!tt.<a href="/web-doxygen/docs/api/classes/textstream/#a0859a9bfd6a7b6bafc7050d9f3aef046">empty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">324</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">325</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;map name=\""</span><span class="doxyHighlight"> &lt;&lt; mapName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" id=\""</span><span class="doxyHighlight"> &lt;&lt; mapName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">326</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; tt.<a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">str</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">327</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/map&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">328</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">329</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">330</span><span class="doxyLineContent"><span class="doxyHighlight">  d.<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(absOutFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">331</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/classes/dir/#a226b0db1117e46393bbb241e545f8609">Dir::absPath</a>, <a href="/web-doxygen/docs/api/classes/dotrunner/#aa225ccd454acbadc5b6a23d9534e574f">DotRunner::addJob</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#aac97171a3985fd07e09fef2a25819a16">DotFilePatcher::addSVGConversion</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a28f0ce1e173d0f12f0a4425af69958a5">DotFilePatcher::convertMapFile</a>, <a href="/web-doxygen/docs/api/classes/textstream/#a0859a9bfd6a7b6bafc7050d9f3aef046">TextStream::empty</a>, <a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">Dir::exists</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ab1cc08326518f249ccae693a16f6a10d">getDotImageExtension</a>, <a href="/web-doxygen/docs/api/files/src/dot-cpp/#a8e61450eb94b16e866568ad3aed2d9f1">MAP&#95;CMD</a>, <a href="/web-doxygen/docs/api/classes/dotrunner/#a2c9b6af873f263c04913504d0f420274">DotRunner::preventCleanUp</a>, <a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">Dir::remove</a>, <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#a02cd92c7c61a35c61c601ff6b409c5e5">DotFilePatcher::run</a>, <a href="/web-doxygen/docs/api/classes/dotrunner/#ac1afaee16ddd8bf0bc6b18aaed6b44fd">DotRunner::run</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/textstream/#aca8457da22d874f4eb30b35ffe87ebd0">TextStream::str</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a> and <a href="/web-doxygen/docs/api/classes/dotfilepatcher/#ae41b4e8b1817e1d1de1732e4c4f9069c">DotFilePatcher::writeSVGFigureLink</a>.

Referenced by <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a3264ee5213c549e45cd13604e62e7719">HtmlDocVisitor::writeDotFile</a>.
</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
