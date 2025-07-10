---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/xmlgen-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `xmlgen.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include "<a href="/web-doxygen/docs/api/files/src/outputgen-h">outputgen.h</a>"
</div>

## Classes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/xmlcodegenerator">XMLCodeGenerator</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f9b3e222369b7d908441a0825b0da84">generateXML</a> ()</td>
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

### generateXML() {#a0f9b3e222369b7d908441a0825b0da84}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void generateXML ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 70 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-h">xmlgen.h</a>, definition at line 2196 of file <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp">xmlgen.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">2196</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0f9b3e222369b7d908441a0825b0da84">generateXML</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2197</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2198</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + classes</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2199</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + concepts</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2200</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + namespaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2201</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2202</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + groups</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2203</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// + related pages</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2204</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// - examples</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2205</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2206</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> outputDirectory = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(XML_OUTPUT);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2207</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> xmlDir(outputDirectory.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2208</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a77685956f8517f3a6e062e66925fc93c">createSubDirs</a>(xmlDir);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2209</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2210</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">copyResource</a>(</span><span class="doxyHighlightStringLiteral">"xml.xsd"</span><span class="doxyHighlight">,outputDirectory);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2211</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">copyResource</a>(</span><span class="doxyHighlightStringLiteral">"index.xsd"</span><span class="doxyHighlight">,outputDirectory);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2212</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2213</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> fileName=outputDirectory+</span><span class="doxyHighlightStringLiteral">"/compound.xsd"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2214</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2215</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2216</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2217</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Cannot open file {} for writing!\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2218</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2219</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2220</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2221</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2222</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2223</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// write compound.xsd, but replace special marker with the entities</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2224</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> compound_xsd = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"compound.xsd"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2225</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *startLine = compound_xsd.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2226</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*startLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2227</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2228</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// find end of the line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2229</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *endLine = startLine+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2230</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*endLine &amp;&amp; *(endLine-1)!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) endLine++; </span><span class="doxyHighlightComment">// skip to end of the line including \n</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2231</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(endLine-startLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2232</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2233</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2234</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s(startLine,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2235</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"&lt;!-- Automatically insert here the HTML entities --&gt;"</span><span class="doxyHighlight">)!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2236</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2237</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>().<a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a7c7b82a1151c72c7df57732517379a14">writeXMLSchema</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2238</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2239</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2240</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2241</span><span class="doxyLineContent"><span class="doxyHighlight">          t.<a href="/web-doxygen/docs/api/classes/textstream/#aaa78941b7f04d95ca3be7d11073828f0">write</a>(startLine,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2242</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2243</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2244</span><span class="doxyLineContent"><span class="doxyHighlight">      startLine=endLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2245</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2246</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2247</span><span class="doxyLineContent"><span class="doxyHighlight">  f.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2248</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2249</span><span class="doxyLineContent"><span class="doxyHighlight">  fileName=outputDirectory+</span><span class="doxyHighlightStringLiteral">"/doxyfile.xsd"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2250</span><span class="doxyLineContent"><span class="doxyHighlight">  f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2251</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2252</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2253</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Cannot open file {} for writing!\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2254</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2255</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2256</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2257</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2258</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2259</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// write doxyfile.xsd, but replace special marker with the entities</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2260</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> doxyfile_xsd = <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>().<a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">getAsString</a>(</span><span class="doxyHighlightStringLiteral">"doxyfile.xsd"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2261</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *startLine = doxyfile_xsd.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2262</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*startLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2263</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2264</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// find end of the line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2265</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *endLine = startLine+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2266</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*endLine &amp;&amp; *(endLine-1)!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) endLine++; </span><span class="doxyHighlightComment">// skip to end of the line including \n</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2267</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> len=</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(endLine-startLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2268</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (len&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2269</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2270</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s(startLine,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2271</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">find</a>(</span><span class="doxyHighlightStringLiteral">"&lt;!-- Automatically insert here the configuration settings --&gt;"</span><span class="doxyHighlight">)!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2272</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2273</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/namespaces/config/#a8dfcffe6278ca640b592ae6661b794b5">Config::writeXSDDoxyfile</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2274</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2275</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2276</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2277</span><span class="doxyLineContent"><span class="doxyHighlight">          t.<a href="/web-doxygen/docs/api/classes/textstream/#aaa78941b7f04d95ca3be7d11073828f0">write</a>(startLine,len);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2278</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2279</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2280</span><span class="doxyLineContent"><span class="doxyHighlight">      startLine=endLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2281</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2282</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2283</span><span class="doxyLineContent"><span class="doxyHighlight">  f.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2284</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2285</span><span class="doxyLineContent"><span class="doxyHighlight">  fileName=outputDirectory+</span><span class="doxyHighlightStringLiteral">"/Doxyfile.xml"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2286</span><span class="doxyLineContent"><span class="doxyHighlight">  f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2287</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2288</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2289</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Cannot open file {} for writing\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2290</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2291</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2292</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2293</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2294</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2295</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/namespaces/config/#a5744a411e57f8a3a18ce6569e843b11e">Config::writeXMLDoxyfile</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2296</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2297</span><span class="doxyLineContent"><span class="doxyHighlight">  f.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2298</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2299</span><span class="doxyLineContent"><span class="doxyHighlight">  fileName=outputDirectory+</span><span class="doxyHighlightStringLiteral">"/index.xml"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2300</span><span class="doxyLineContent"><span class="doxyHighlight">  f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2301</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2302</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2303</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>(</span><span class="doxyHighlightStringLiteral">"Cannot open file {} for writing!\n"</span><span class="doxyHighlight">,fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2304</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2305</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2306</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2307</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2308</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2309</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2310</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// write index header</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2311</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;?xml version='1.0' encoding='UTF-8' standalone='no'?&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2312</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;doxygenindex xmlns:xsi=\"http://www.w3.org/2001/XMLSchema-instance\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2313</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"xsi:noNamespaceSchemaLocation=\"index.xsd\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2314</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"version=\""</span><span class="doxyHighlight"> &lt;&lt; getDoxygenVersion() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" "</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2315</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"xml:lang=\""</span><span class="doxyHighlight"> &lt;&lt; <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trISOLang() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\""</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2316</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2317</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2318</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2319</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2320</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a>(cd.get(),t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2321</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2322</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;cd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a0de9b52b3098ea1a4bee5e248e8287c8">Doxygen::conceptLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2323</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2324</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating XML output for concept {}\n"</span><span class="doxyHighlight">,cd-&gt;displayName());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2325</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aac5793331bb86627d87dd42dcaa637b4">generateXMLForConcept</a>(cd.get(),t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2326</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2327</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;nd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2328</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2329</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating XML output for namespace {}\n"</span><span class="doxyHighlight">,nd-&gt;displayName());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2330</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a9371126c00d478f6d9b76346e4fa77dd">generateXMLForNamespace</a>(nd.get(),t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2331</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2332</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fn : *<a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2333</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2334</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fd : *fn)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2335</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2336</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating XML output for file {}\n"</span><span class="doxyHighlight">,fd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2337</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a541a7f1681d4e6c18ba0fb4902f2b9d3">generateXMLForFile</a>(fd.get(),t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2338</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2339</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2340</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;gd : *<a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2341</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2342</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating XML output for group {}\n"</span><span class="doxyHighlight">,gd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2343</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a>(gd.get(),t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2344</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2345</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pd : *<a href="/web-doxygen/docs/api/classes/doxygen/#abd2756663a014ee48e1660d32a48cac5">Doxygen::pageLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2346</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2347</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating XML output for page {}\n"</span><span class="doxyHighlight">,pd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2348</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa324f7a9171409ff704f91dd087e8de">generateXMLForPage</a>(pd.get(),t,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2349</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2350</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dd : *<a href="/web-doxygen/docs/api/classes/doxygen/#ad179803c33ab064adfd6adf681a0a805">Doxygen::dirLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2351</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2352</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generate XML output for dir {}\n"</span><span class="doxyHighlight">,dd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2353</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#af23bb9f6e1a0a0bddb2da660425f7da4">generateXMLForDir</a>(dd.get(),t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2354</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2355</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;mod : <a href="/web-doxygen/docs/api/classes/modulemanager/#a4f48cf5d05907a6acc4b9c6ddec752b7">ModuleManager::instance</a>().modules())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2356</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2357</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating XML output for module {}\n"</span><span class="doxyHighlight">,mod-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2358</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aab9f9e82c47dc3b0efdb1955d4867a2f">generateXMLForModule</a>(mod.get(),t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2359</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2360</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;pd : *<a href="/web-doxygen/docs/api/classes/doxygen/#a6cfac206c42a62e6e3ba66d5d4e4a471">Doxygen::exampleLinkedMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2361</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2362</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating XML output for example {}\n"</span><span class="doxyHighlight">,pd-&gt;name());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2363</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa324f7a9171409ff704f91dd087e8de">generateXMLForPage</a>(pd.get(),t,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2364</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2365</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2366</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2367</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Generating XML output for the main page\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2368</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa324f7a9171409ff704f91dd087e8de">generateXMLForPage</a>(<a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>.get(),t,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2369</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2370</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2371</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">//t &lt;&lt; "  &lt;/compoundlist&gt;\n";</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2372</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/doxygenindex&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2373</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2374</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2375</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afdcb651fa099a6b705bd08e02e24333f">writeCombineScript</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2376</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/util-cpp/#a706b1f8eeae91066c7b1d7bb7c0d7ef9">clearSubDirs</a>(xmlDir);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">2377</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/doxygen/#a5f4b7acdd27a42865b4832e4e7ffe82c">Doxygen::classLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a706b1f8eeae91066c7b1d7bb7c0d7ef9">clearSubDirs</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a0de9b52b3098ea1a4bee5e248e8287c8">Doxygen::conceptLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a32b8297da656a43a255a3a1b27c210b9">ResourceMgr::copyResource</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a77685956f8517f3a6e062e66925fc93c">createSubDirs</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#ad179803c33ab064adfd6adf681a0a805">Doxygen::dirLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aacd8f4b44e327860edbf38228d5918b0">err</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a6cfac206c42a62e6e3ba66d5d4e4a471">Doxygen::exampleLinkedMap</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a0182ece6b76dad6475dafb53e2faaf10">QCString::find</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a4dc2c1db665be657de3548de437246d2">generateXMLForClass</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aac5793331bb86627d87dd42dcaa637b4">generateXMLForConcept</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#af23bb9f6e1a0a0bddb2da660425f7da4">generateXMLForDir</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a541a7f1681d4e6c18ba0fb4902f2b9d3">generateXMLForFile</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a0da7be0853343b6580993a525ed72a62">generateXMLForGroup</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#aab9f9e82c47dc3b0efdb1955d4867a2f">generateXMLForModule</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#a9371126c00d478f6d9b76346e4fa77dd">generateXMLForNamespace</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afa324f7a9171409ff704f91dd087e8de">generateXMLForPage</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#aa60ef164e79a11cfa31de29221db11aa">ResourceMgr::getAsString</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#afd89d49084b42d085e9d40fc2636da9c">Doxygen::groupLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a31a5a5856417ba3f05eccaf1f85e9958">Doxygen::inputNameLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a9170301bb5ed20abd90f396a53e3e1f7">HtmlEntityMapper::instance</a>, <a href="/web-doxygen/docs/api/classes/modulemanager/#a4f48cf5d05907a6acc4b9c6ddec752b7">ModuleManager::instance</a>, <a href="/web-doxygen/docs/api/classes/resourcemgr/#a02fb3176893696eaf659d680c8b08064">ResourceMgr::instance</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a2cc3616eca3e3c550a211d8b1eaf4661">Doxygen::mainPage</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a033b4829afda05c5eef5cd54749b19bf">Doxygen::namespaceLinkedMap</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#abd2756663a014ee48e1660d32a48cac5">Doxygen::pageLinkedMap</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa8cecfc5c5c054d2875c03e77b7be15d">TRUE</a>, <a href="/web-doxygen/docs/api/classes/textstream/#aaa78941b7f04d95ca3be7d11073828f0">TextStream::write</a>, <a href="/web-doxygen/docs/api/files/src/xmlgen-cpp/#afdcb651fa099a6b705bd08e02e24333f">writeCombineScript</a>, <a href="/web-doxygen/docs/api/namespaces/config/#a5744a411e57f8a3a18ce6569e843b11e">Config::writeXMLDoxyfile</a>, <a href="/web-doxygen/docs/api/classes/htmlentitymapper/#a7c7b82a1151c72c7df57732517379a14">HtmlEntityMapper::writeXMLSchema</a> and <a href="/web-doxygen/docs/api/namespaces/config/#a8dfcffe6278ca640b592ae6661b794b5">Config::writeXSDDoxyfile</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
