---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/formulamanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `FormulaManager` Class Reference



## Declaration

<div class="doxyDeclaration">
class FormulaManager { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/formula-h">src/formula.h</a>&gt;
</div>

## Private Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a13fd2eedbb1c7f086bd66cbd6e049911">FormulaManager</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab24723d7cedd2c780f895fea971fb484">createFormulasTexFile</a> (Dir &amp;d, Format format, HighDPI hd, Mode mode)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f96928dbcf6279d70d38ee11b35ea55">createLatexFile</a> (const QCString &amp;fileName, Format format, Mode mode, IntVector &amp;formulasToGenerate)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/formulamanager/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">static <a href="/web-doxygen/docs/api/classes/formulamanager">FormulaManager</a> &amp;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab5c33a247a1b081414e3350552beb6ee">instance</a> ()</td>
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

## generator functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Format { <a href="#aa538ca4ffea4dd937920ebdd41222e69">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">HighDPI { <a href="#ae7fe54b64ef2fa9eff2494118fab761e">...</a> }</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">Mode { <a href="#a417a154a8ce0abdc51353d4475005419">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aef1d730d619e5441ab6206a8fd5b1a45">generateImages</a> (const QCString &amp;outputDir, Format format, HighDPI hd=HighDPI::Off)</td>
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

## repository functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a10998c967b5e151acf3dad299deb0bc9">initFromRepository</a> (const QCString &amp;dir)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9ff2d153c001e2b9d9b054200d34c6a2">checkRepositories</a> ()</td>
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

## formula functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">void</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5a181349991e3e72a331b231c9c25f8b">clear</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a263c84263295a94dd1593d39f2c435f5">addFormula</a> (const std::string &amp;formulaText, int width=-1, int height=-1)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/formula">Formula</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aa15bea658260218b4b6c3193df2c5856">findFormula</a> (int formulaId) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">bool</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a4b5c2d7e0c8001ae48514de0b468eb87">hasFormulas</a> () const</td>
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



<p>Manager class to handle formulas</p>


<p>Definition at line 58 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>.</p>


<div class="doxySectionDef">

## Private Constructors

### FormulaManager() {#a13fd2eedbb1c7f086bd66cbd6e049911}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FormulaManager::FormulaManager ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 88 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>, definition at line 50 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a13fd2eedbb1c7f086bd66cbd6e049911">50</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a13fd2eedbb1c7f086bd66cbd6e049911">FormulaManager::FormulaManager</a>() : <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/formulamanager/private">Private</a>&gt;())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">51</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">52</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>.</p>


<p>Referenced by <a href="#ab5c33a247a1b081414e3350552beb6ee">instance</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### createFormulasTexFile() {#ab24723d7cedd2c780f895fea971fb484}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FormulaManager::createFormulasTexFile (<a href="/web-doxygen/docs/api/classes/dir">Dir</a> &amp; d, <a href="#aa538ca4ffea4dd937920ebdd41222e69">Format</a> format, <a href="#ae7fe54b64ef2fa9eff2494118fab761e">HighDPI</a> hd, <a href="#a417a154a8ce0abdc51353d4475005419">Mode</a> mode)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 86 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>, definition at line 553 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab24723d7cedd2c780f895fea971fb484">553</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab24723d7cedd2c780f895fea971fb484">FormulaManager::createFormulasTexFile</a>(<a href="/web-doxygen/docs/api/classes/dir">Dir</a> &amp;thisDir,<a href="#aa538ca4ffea4dd937920ebdd41222e69">Format</a> format,<a href="#ae7fe54b64ef2fa9eff2494118fab761e">HighDPI</a> hd,<a href="#a417a154a8ce0abdc51353d4475005419">Mode</a> mode)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">554</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">555</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#a0b244579717fb04b2fb4ac89ee2f0f35">IntVector</a> formulasToGenerate;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">556</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> formulaFileName = mode==<a href="#a417a154a8ce0abdc51353d4475005419a9914a0ce04a7b7b6a8e39bec55064b82">Mode::Light</a> ? </span><span class="doxyHighlightStringLiteral">"_formulas"</span><span class="doxyHighlight"> : </span><span class="doxyHighlightStringLiteral">"_formulas_dark"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">557</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a0f96928dbcf6279d70d38ee11b35ea55">createLatexFile</a>(formulaFileName,format,mode,formulasToGenerate);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">558</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">559</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!formulasToGenerate.empty()) </span><span class="doxyHighlightComment">// there are new formulas</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">560</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">561</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/formula-cpp/#a704ccf2352fafe16ddf093abbaa6f7b4">createDVIFile</a>(formulaFileName)) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">562</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">563</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> getFormula = [</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">](</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pageNum) -&gt; <a href="/web-doxygen/docs/api/classes/formula">Formula</a> *</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">564</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">565</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulaIdMap.find(pageNum);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">566</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulaIdMap.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">567</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">568</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">569</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">570</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">571</span><span class="doxyLineContent"><span class="doxyHighlight">    };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">572</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">573</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pageIndex=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">574</span><span class="doxyLineContent"><span class="doxyHighlight">    std::size_t numThreads = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlight">std::size_t</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>(NUM_PROC_THREADS));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">575</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (numThreads&gt;1) </span><span class="doxyHighlightComment">// multi-threaded version</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">576</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">577</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/threadpool">ThreadPool</a> threadPool(numThreads);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">578</span><span class="doxyLineContent"><span class="doxyHighlight">      std::vector&lt; std::future&lt; StringVector &gt; &gt; results;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">579</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pageNum : formulasToGenerate)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">580</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">581</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// create images for each formula.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">582</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> formula = getFormula(pageNum);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">583</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> processFormula = [=]() -&gt; <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a></span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">584</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">585</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a62cf6f788807da125c5433670c59d393">generateFormula</a>(thisDir,formulaFileName,formula,pageNum,pageIndex,format,hd,mode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">586</span><span class="doxyLineContent"><span class="doxyHighlight">        };</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">587</span><span class="doxyLineContent"><span class="doxyHighlight">        results.emplace_back(threadPool.<a href="/web-doxygen/docs/api/classes/threadpool/#a90398abffcd9d81901195160315b1bc9">queue</a>(processFormula));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">588</span><span class="doxyLineContent"><span class="doxyHighlight">        pageIndex++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">589</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">590</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;f : results)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">591</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">592</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> tf = f.get();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">593</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;tempFiles.insert(<a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;tempFiles.end(),tf.begin(),tf.end()); </span><span class="doxyHighlightComment">// append tf to p-&gt;tempFiles</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">594</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">595</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">596</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// single threaded version</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">597</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">598</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> pageNum : formulasToGenerate)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">599</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">600</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// create images for each formula.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">601</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> formula = getFormula(pageNum);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">602</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> tf = <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a62cf6f788807da125c5433670c59d393">generateFormula</a>(thisDir,formulaFileName,formula,pageNum,pageIndex,format,hd,mode);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">603</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;tempFiles.insert(<a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;tempFiles.end(),tf.begin(),tf.end()); </span><span class="doxyHighlightComment">// append tf to p-&gt;tempFiles</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">604</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">605</span><span class="doxyLineContent"><span class="doxyHighlight">        pageIndex++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">606</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">607</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">608</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// remove intermediate files produced by latex</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">609</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;tempFiles.push_back(formulaFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()+</span><span class="doxyHighlightStringLiteral">".dvi"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">610</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;tempFiles.push_back(formulaFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()+</span><span class="doxyHighlightStringLiteral">".log"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">611</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;tempFiles.push_back(formulaFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()+</span><span class="doxyHighlightStringLiteral">".aux"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">612</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">613</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// remove the latex file itself</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">614</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;tempFiles.push_back(formulaFileName.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()+</span><span class="doxyHighlightStringLiteral">".tex"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">615</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">616</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// write/update the formula repository so we know what text the</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">617</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// generated images represent (we use this next time to avoid regeneration</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">618</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// of the images, and to avoid forcing the user to delete all images in order</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">619</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// to let a browser refresh the images).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">620</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(</span><span class="doxyHighlightStringLiteral">"formula.repository"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">621</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">622</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">623</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">624</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;formula : <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulas)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">625</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">626</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\_form#"</span><span class="doxyHighlight"> &lt;&lt; formula-&gt;id();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">627</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (formula-&gt;width()!=-1 &amp;&amp; formula-&gt;height()!=-1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">628</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">629</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"="</span><span class="doxyHighlight"> &lt;&lt; formula-&gt;width() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"x"</span><span class="doxyHighlight"> &lt;&lt; formula-&gt;height();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">630</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">631</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight"> &lt;&lt; formula-&gt;text() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">632</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">633</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">634</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a06b59c3720174e9078f613095a89b295">Config_getInt</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a704ccf2352fafe16ddf093abbaa6f7b4">createDVIFile</a>, <a href="#a0f96928dbcf6279d70d38ee11b35ea55">createLatexFile</a>, <a href="/web-doxygen/docs/api/files/src/formula-cpp/#a62cf6f788807da125c5433670c59d393">generateFormula</a>, <a href="#a417a154a8ce0abdc51353d4475005419a9914a0ce04a7b7b6a8e39bec55064b82">Light</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>, <a href="/web-doxygen/docs/api/classes/threadpool/#a90398abffcd9d81901195160315b1bc9">ThreadPool::queue</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>.</p>


<p>Referenced by <a href="#aef1d730d619e5441ab6206a8fd5b1a45">generateImages</a>.</p>

</div>
</div>

### createLatexFile() {#a0f96928dbcf6279d70d38ee11b35ea55}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FormulaManager::createLatexFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, <a href="#aa538ca4ffea4dd937920ebdd41222e69">Format</a> format, <a href="#a417a154a8ce0abdc51353d4475005419">Mode</a> mode, <a href="/web-doxygen/docs/api/files/src/containers-h/#a0b244579717fb04b2fb4ac89ee2f0f35">IntVector</a> &amp; formulasToGenerate)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 87 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>, definition at line 184 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f96928dbcf6279d70d38ee11b35ea55">184</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a0f96928dbcf6279d70d38ee11b35ea55">FormulaManager::createLatexFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,<a href="#aa538ca4ffea4dd937920ebdd41222e69">Format</a> format,<a href="#a417a154a8ce0abdc51353d4475005419">Mode</a> mode,<a href="/web-doxygen/docs/api/files/src/containers-h/#a0b244579717fb04b2fb4ac89ee2f0f35">IntVector</a> &amp;formulasToGenerate)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// generate a latex file containing one formula per page.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> texName=fileName+</span><span class="doxyHighlightStringLiteral">".tex"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ofstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>(texName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> t(&amp;f);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\documentclass{article}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\usepackage{iftex}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\usepackage{ifthen}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\usepackage{epsfig}\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// for those who want to include images</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\usepackage[utf8]{inputenc}\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// looks like some older distributions with newunicode package 1.1 need this option.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\usepackage{xcolor}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (mode==<a href="#a417a154a8ce0abdc51353d4475005419aa18366b217ebf811ad1886e4f4f865b2">Mode::Dark</a>) </span><span class="doxyHighlightComment">// invert page and text colors</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\color{white}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\pagecolor{black}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ace2411e2a91d0794515d7319a05a96e4">writeExtraLatexPackages</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afb096be4b2c37adc54becb763cc99470">writeLatexSpecialFormulaChars</a>(t);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> macroFile = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(FORMULA_MACROFILE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!macroFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(macroFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> stripMacroFile = fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\input{"</span><span class="doxyHighlight"> &lt;&lt; stripMacroFile &lt;&lt; </span><span class="doxyHighlightStringLiteral">"}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">216</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\pagestyle{empty}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">217</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\begin{document}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">218</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;formula : <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulas)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">219</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = formula-&gt;id();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// only formulas for which no image is cached are generated</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("check formula %d: cached=%d cachedDark=%d\n",formula-&gt;id(),formula-&gt;isCached(),formula-&gt;isCachedDark());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ((mode==<a href="#a417a154a8ce0abdc51353d4475005419a9914a0ce04a7b7b6a8e39bec55064b82">Mode::Light</a> &amp;&amp; !formula-&gt;isCached()) ||</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">224</span><span class="doxyLineContent"><span class="doxyHighlight">          (mode==<a href="#a417a154a8ce0abdc51353d4475005419aa18366b217ebf811ad1886e4f4f865b2">Mode::Dark</a> &amp;&amp; !formula-&gt;isCachedDark())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">225</span><span class="doxyLineContent"><span class="doxyHighlight">         )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">226</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">227</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// we force a pagebreak after each formula</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">228</span><span class="doxyLineContent"><span class="doxyHighlight">        t &lt;&lt; formula-&gt;text() &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\n\\pagebreak\n\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">229</span><span class="doxyLineContent"><span class="doxyHighlight">        formulasToGenerate.push_back(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">230</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">231</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> resultName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">232</span><span class="doxyLineContent"><span class="doxyHighlight">      resultName.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"form_%d%s.%s"</span><span class="doxyHighlight">,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">, mode==<a href="#a417a154a8ce0abdc51353d4475005419a9914a0ce04a7b7b6a8e39bec55064b82">Mode::Light</a>?</span><span class="doxyHighlightStringLiteral">""</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"_dark"</span><span class="doxyHighlight">, format==<a href="#aa538ca4ffea4dd937920ebdd41222e69a57dea6f5039281b7fee517fc43bf3110">Format::Vector</a>?</span><span class="doxyHighlightStringLiteral">"svg"</span><span class="doxyHighlight">:</span><span class="doxyHighlightStringLiteral">"png"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">233</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addImageFile(resultName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\\end{document}\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">    t.<a href="/web-doxygen/docs/api/classes/textstream/#a907937b613a56aa4124608b3a092b820">flush</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">    f.close();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="#a417a154a8ce0abdc51353d4475005419aa18366b217ebf811ad1886e4f4f865b2">Dark</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/textstream/#a907937b613a56aa4124608b3a092b820">TextStream::flush</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="#a417a154a8ce0abdc51353d4475005419a9914a0ce04a7b7b6a8e39bec55064b82">Light</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a230fceefc8f9abd1e8d4be71d7eef281">Portable::openOutputStream</a>, <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="#aa538ca4ffea4dd937920ebdd41222e69a57dea6f5039281b7fee517fc43bf3110">Vector</a>, <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#ace2411e2a91d0794515d7319a05a96e4">writeExtraLatexPackages</a> and <a href="/web-doxygen/docs/api/files/src/latexgen-cpp/#afb096be4b2c37adc54becb763cc99470">writeLatexSpecialFormulaChars</a>.</p>


<p>Referenced by <a href="#ab24723d7cedd2c780f895fea971fb484">createFormulasTexFile</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### p {#ad6efed826faf400f0c45b49d7dd79f0d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; FormulaManager::p</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 90 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad6efed826faf400f0c45b49d7dd79f0d">90</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a263c84263295a94dd1593d39f2c435f5">addFormula</a>, <a href="#a9ff2d153c001e2b9d9b054200d34c6a2">checkRepositories</a>, <a href="#a5a181349991e3e72a331b231c9c25f8b">clear</a>, <a href="#ab24723d7cedd2c780f895fea971fb484">createFormulasTexFile</a>, <a href="#a0f96928dbcf6279d70d38ee11b35ea55">createLatexFile</a>, <a href="#aa15bea658260218b4b6c3193df2c5856">findFormula</a>, <a href="#a13fd2eedbb1c7f086bd66cbd6e049911">FormulaManager</a>, <a href="#aef1d730d619e5441ab6206a8fd5b1a45">generateImages</a>, <a href="#a4b5c2d7e0c8001ae48514de0b468eb87">hasFormulas</a> and <a href="#a10998c967b5e151acf3dad299deb0bc9">initFromRepository</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Static Functions

### instance() {#ab5c33a247a1b081414e3350552beb6ee}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">FormulaManager &amp; FormulaManager::instance ()</td>
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



<p>Declaration at line 61 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>, definition at line 54 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab5c33a247a1b081414e3350552beb6ee">54</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#a13fd2eedbb1c7f086bd66cbd6e049911">FormulaManager</a> &amp;<a href="#ab5c33a247a1b081414e3350552beb6ee">FormulaManager::instance</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">55</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">56</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> <a href="#a13fd2eedbb1c7f086bd66cbd6e049911">FormulaManager</a> fm;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">57</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> fm;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">58</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a13fd2eedbb1c7f086bd66cbd6e049911">FormulaManager</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad7328f0606e5f8d93daecd7d5babee1d">addFormula</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae12e94f5218f3afc8df4086a2121cd4d">cleanUpDoxygen</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a798729dca95209ecdc609807a653a2bf">clearAll</a>, <a href="/web-doxygen/docs/api/classes/docformula/#ae40d1dafb6c93681ddf0a9bc2e961053">DocFormula::DocFormula</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa9e3a7cf34aceba68750ff3ff94acf34">HtmlDocVisitor::operator()</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## generator functions

### Format {#aa538ca4ffea4dd937920ebdd41222e69}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class FormulaManager::Format </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Bitmap<a id="aa538ca4ffea4dd937920ebdd41222e69a86ee74baff479d85d18f2cda9f8a9518"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Vector<a id="aa538ca4ffea4dd937920ebdd41222e69a57dea6f5039281b7fee517fc43bf3110"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 79 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa538ca4ffea4dd937920ebdd41222e69a86ee74baff479d85d18f2cda9f8a9518">79</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#aa538ca4ffea4dd937920ebdd41222e69">Format</a> { <a href="#aa538ca4ffea4dd937920ebdd41222e69a86ee74baff479d85d18f2cda9f8a9518">Bitmap</a>, <a href="#aa538ca4ffea4dd937920ebdd41222e69a57dea6f5039281b7fee517fc43bf3110">Vector</a> };</span></span></div>

</div>

</div>
</div>

### generateImages {#aef1d730d619e5441ab6206a8fd5b1a45}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FormulaManager::generateImages (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; outputDir, <a href="#aa538ca4ffea4dd937920ebdd41222e69">Format</a> format, <a href="#ae7fe54b64ef2fa9eff2494118fab761e">HighDPI</a> hd=<a href="#ae7fe54b64ef2fa9eff2494118fab761ead15305d7a4e34e02489c74a5ef542f36">HighDPI::Off</a>)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 82 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>, definition at line 636 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aef1d730d619e5441ab6206a8fd5b1a45">636</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#aef1d730d619e5441ab6206a8fd5b1a45">FormulaManager::generateImages</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;path,<a href="#aa538ca4ffea4dd937920ebdd41222e69">Format</a> format,<a href="#ae7fe54b64ef2fa9eff2494118fab761e">HighDPI</a> hd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">637</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">638</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> d(path.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">639</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// store the original directory</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">640</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!d.<a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">exists</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">641</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">642</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>(</span><span class="doxyHighlightStringLiteral">"Output directory '{}' does not exist!\n"</span><span class="doxyHighlight">,path);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">643</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">644</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string oldDir = <a href="/web-doxygen/docs/api/classes/dir/#a0f62ab07068c5f966bca7ce280f4ed49">Dir::currentDirPath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">645</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">646</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> macroFile = <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>(FORMULA_MACROFILE);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">647</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> stripMacroFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">648</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!macroFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">649</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">650</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fi(macroFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">651</span><span class="doxyLineContent"><span class="doxyHighlight">    macroFile=fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">absFilePath</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">652</span><span class="doxyLineContent"><span class="doxyHighlight">    stripMacroFile = fi.<a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">fileName</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">653</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">654</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">655</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// go to the html output directory (i.e. path)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">656</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir/#ab3b09edc88159dc30426999bdc7d6d7b">Dir::setCurrent</a>(d.<a href="/web-doxygen/docs/api/classes/dir/#a226b0db1117e46393bbb241e545f8609">absPath</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">657</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir">Dir</a> thisDir;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">658</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">659</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!macroFile.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">660</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">661</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>(macroFile,stripMacroFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">662</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">663</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">664</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ab24723d7cedd2c780f895fea971fb484">createFormulasTexFile</a>(thisDir,format,hd,<a href="#a417a154a8ce0abdc51353d4475005419a9914a0ce04a7b7b6a8e39bec55064b82">Mode::Light</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">665</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>(HTML_COLORSTYLE)!=HTML_COLORSTYLE_t::LIGHT) </span><span class="doxyHighlightComment">// all modes other than light need a dark version</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">666</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">667</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// note that the dark version reuses the bounding box of the light version so it needs to be</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">668</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// created after the light version.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">669</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ab24723d7cedd2c780f895fea971fb484">createFormulasTexFile</a>(thisDir,format,hd,<a href="#a417a154a8ce0abdc51353d4475005419aa18366b217ebf811ad1886e4f4f865b2">Mode::Dark</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">670</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">671</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">672</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// clean up temporary files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">673</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daaa4539102b2cba0227fb56f4fd90e997">Debug::Formula</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">674</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">675</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;file : <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;tempFiles)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">676</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">677</span><span class="doxyLineContent"><span class="doxyHighlight">      thisDir.<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>(file);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">678</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">679</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">680</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">681</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// reset the directory to the original location.</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">682</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/dir/#ab3b09edc88159dc30426999bdc7d6d7b">Dir::setCurrent</a>(oldDir);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">683</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/fileinfo/#af69e3949475014dcdbd504d742bdf270">FileInfo::absFilePath</a>, <a href="/web-doxygen/docs/api/classes/dir/#a226b0db1117e46393bbb241e545f8609">Dir::absPath</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#afe899eec751dfb75a60c37ec3840e288">Config_getEnum</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a737741e6991bdb5694a50075437a9d89">Config_getString</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#ad35d4038b3882fdd09976d28f4a043bf">copyFile</a>, <a href="#ab24723d7cedd2c780f895fea971fb484">createFormulasTexFile</a>, <a href="/web-doxygen/docs/api/classes/dir/#a0f62ab07068c5f966bca7ce280f4ed49">Dir::currentDirPath</a>, <a href="#a417a154a8ce0abdc51353d4475005419aa18366b217ebf811ad1886e4f4f865b2">Dark</a>, <a href="/web-doxygen/docs/api/classes/dir/#ac6bf80b5b3a034e8c144c86ef48ae309">Dir::exists</a>, <a href="/web-doxygen/docs/api/classes/fileinfo/#a8ae2069796787d27306bb49bd70e3e3a">FileInfo::fileName</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7daaa4539102b2cba0227fb56f4fd90e997">Debug::Formula</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/debug/#a96e9401783e852c91f341b3f98198061">Debug::isFlagSet</a>, <a href="#a417a154a8ce0abdc51353d4475005419a9914a0ce04a7b7b6a8e39bec55064b82">Light</a>, <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>, <a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">Dir::remove</a>, <a href="/web-doxygen/docs/api/classes/dir/#ab3b09edc88159dc30426999bdc7d6d7b">Dir::setCurrent</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#acdcc4bcb46c31bcfda7ef3e2364b9264">term</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.</p>

</div>
</div>

### HighDPI {#ae7fe54b64ef2fa9eff2494118fab761e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class FormulaManager::HighDPI </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">On<a id="ae7fe54b64ef2fa9eff2494118fab761ea521c36a31c2762741cf0f8890cbe05e3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Off<a id="ae7fe54b64ef2fa9eff2494118fab761ead15305d7a4e34e02489c74a5ef542f36"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 80 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ae7fe54b64ef2fa9eff2494118fab761e">80</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#ae7fe54b64ef2fa9eff2494118fab761e">HighDPI</a> { <a href="#ae7fe54b64ef2fa9eff2494118fab761ea521c36a31c2762741cf0f8890cbe05e3">On</a>, <a href="#ae7fe54b64ef2fa9eff2494118fab761ead15305d7a4e34e02489c74a5ef542f36">Off</a> };</span></span></div>

</div>

</div>
</div>

### Mode {#a417a154a8ce0abdc51353d4475005419}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class FormulaManager::Mode </td>
</tr>
</table>
</td>
<td class="doxyMemberLabelsRight">
<span class="doxyMemberLabels">
<span class="doxyMemberLabel strong">strong</span>
</span>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<dl class="doxyEnumList">
<dt class="doxyEnumTableTitle">Enumeration values</dt>
<dd>
<table class="doxyEnumTable">

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Dark<a id="a417a154a8ce0abdc51353d4475005419aa18366b217ebf811ad1886e4f4f865b2"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">Light<a id="a417a154a8ce0abdc51353d4475005419a9914a0ce04a7b7b6a8e39bec55064b82"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 81 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a417a154a8ce0abdc51353d4475005419aa18366b217ebf811ad1886e4f4f865b2">81</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#a417a154a8ce0abdc51353d4475005419">Mode</a> { <a href="#a417a154a8ce0abdc51353d4475005419aa18366b217ebf811ad1886e4f4f865b2">Dark</a>, <a href="#a417a154a8ce0abdc51353d4475005419a9914a0ce04a7b7b6a8e39bec55064b82">Light</a> };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## repository functions

### checkRepositories {#a9ff2d153c001e2b9d9b054200d34c6a2}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FormulaManager::checkRepositories ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 66 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>, definition at line 173 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a9ff2d153c001e2b9d9b054200d34c6a2">173</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a9ff2d153c001e2b9d9b054200d34c6a2">FormulaManager::checkRepositories</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("checkRepositories valid=%d\n",p-&gt;repositoriesValid);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;repositoriesValid)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a5a181349991e3e72a331b231c9c25f8b">clear</a>(); </span><span class="doxyHighlightComment">// clear cached formulas, so the corresponding images and repository files</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">             </span><span class="doxyHighlightComment">// are regenerated</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;repositoriesValid = </span><span class="doxyHighlightKeyword">true</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a5a181349991e3e72a331b231c9c25f8b">clear</a> and <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>.</p>

</div>
</div>

### initFromRepository {#a10998c967b5e151acf3dad299deb0bc9}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FormulaManager::initFromRepository (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; dir)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 65 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>, definition at line 60 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a10998c967b5e151acf3dad299deb0bc9">60</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a10998c967b5e151acf3dad299deb0bc9">FormulaManager::initFromRepository</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;dir)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">61</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">62</span><span class="doxyLineContent"><span class="doxyHighlight">  std::ifstream f = <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>(dir+</span><span class="doxyHighlightStringLiteral">"/formula.repository"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">63</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (f.is_open())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">64</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">65</span><span class="doxyLineContent"><span class="doxyHighlight">    uint32_t formulaCount=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">66</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"Reading formula repository...\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">67</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string readLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">68</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string line;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">69</span><span class="doxyLineContent"><span class="doxyHighlight">    std::string <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>(</span><span class="doxyHighlightStringLiteral">"\\_form#"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">70</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> nextLineNr=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">71</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> hasNextLine = !getline(f,readLine).fail();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">72</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (hasNextLine)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">73</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">74</span><span class="doxyLineContent"><span class="doxyHighlight">      line = readLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">75</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr = nextLineNr;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">76</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">77</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// look ahead a bit because a formula can be spread over several lines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">78</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> ((hasNextLine = !getline(f,readLine).fail()))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">79</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">80</span><span class="doxyLineContent"><span class="doxyHighlight">        nextLineNr+=1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">81</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!readLine.compare(0, <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>.size(), <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>)) </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">82</span><span class="doxyLineContent"><span class="doxyHighlight">        line += </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight"> + readLine;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">83</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">84</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">85</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">// new format: \_form#&lt;digits&gt;=&lt;digits&gt;x&lt;digits&gt;:formula</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">86</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re_new(R</span><span class="doxyHighlightStringLiteral">"(\\_form#(\d+)=(\d+)x(\d+):)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">87</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      </span><span class="doxyHighlightComment">// old format: \_form#&lt;digits&gt;:formula</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">88</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">static</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/reg/ex">reg::Ex</a> re_old(R</span><span class="doxyHighlightStringLiteral">"(\\_form#(\d+):)");</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">89</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">90</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      <a href="/web-doxygen/docs/api/classes/reg/match">reg::Match</a> match;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">91</span><span class="doxyLineContent"><span class="doxyHighlightStringLiteral">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">     = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">92</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> width  = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">93</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> height = -1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">94</span><span class="doxyLineContent"><span class="doxyHighlight">      std::string text;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">95</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(line,match,re_new)) </span><span class="doxyHighlightComment">// try new format first</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">96</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">97</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">     = std::stoi(match[1].str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">98</span><span class="doxyLineContent"><span class="doxyHighlight">        width  = std::stoi(match[2].str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">99</span><span class="doxyLineContent"><span class="doxyHighlight">        height = std::stoi(match[3].str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">100</span><span class="doxyLineContent"><span class="doxyHighlight">        text   = line.substr(match.position()+match.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">101</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("new format found id=%d width=%d height=%d text=%s\n",id,width,height,text.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">102</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">103</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>(line,match,re_old)) </span><span class="doxyHighlightComment">// check for old format</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">104</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">105</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//id     = std::stoi(match[1].str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">106</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//text   = line.substr(match.position()+match.length());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">107</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("old format found id=%d text=%s\n",id,text.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">108</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"old formula.repository format detected; forcing upgrade.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">109</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;repositoriesValid = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">110</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">111</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">112</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// unexpected content</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">113</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">114</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>(</span><span class="doxyHighlightStringLiteral">"{}/formula.repository contains invalid content at line {}: found: '{}'\n"</span><span class="doxyHighlight">,dir,lineNr,line);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">115</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;repositoriesValid = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">116</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">117</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">118</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">119</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulaIdMap.find(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">120</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/formula">Formula</a> *formula=</span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">121</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulaIdMap.end()) </span><span class="doxyHighlightComment">// formula already found in a repository for another output format</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">122</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">123</span><span class="doxyLineContent"><span class="doxyHighlight">        formula = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">124</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (formula-&gt;<a href="/web-doxygen/docs/api/classes/formula/#a67b9ebbbe7e4814eb09bbf734af69b0e">text</a>().<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>()!=text) </span><span class="doxyHighlightComment">// inconsistency between repositories detected</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">125</span><span class="doxyLineContent"><span class="doxyHighlight">        {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">126</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"differences detected between formula.repository files; forcing upgrade.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">127</span><span class="doxyLineContent"><span class="doxyHighlight">          <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;repositoriesValid = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">128</span><span class="doxyLineContent"><span class="doxyHighlight">          </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">129</span><span class="doxyLineContent"><span class="doxyHighlight">        }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">130</span><span class="doxyLineContent"><span class="doxyHighlight">        formulaCount++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">131</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">132</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// create new formula from cache</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">133</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">134</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("formula not found adding it under id=%d\n",id);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">135</span><span class="doxyLineContent"><span class="doxyHighlight">        formula = <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulas.add(text.c_str(),</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,width,height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">136</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulaIdMap.emplace(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,formula);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">137</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">138</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">139</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (formula) </span><span class="doxyHighlightComment">// if an entry in the repository exists also check if there is a generated image</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">140</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">141</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> formImgName;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">142</span><span class="doxyLineContent"><span class="doxyHighlight">        formImgName.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"form_%d"</span><span class="doxyHighlight">,formula-&gt;<a href="/web-doxygen/docs/api/classes/formula/#ae4b7648ae0124da8456fa2c8e51991ba">id</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">143</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fiPng((dir+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+formImgName+</span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">).str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">144</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fiSvg((dir+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+formImgName+</span><span class="doxyHighlightStringLiteral">".svg"</span><span class="doxyHighlight">).str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">145</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">// mark formula as cached, so we do not need to regenerate the images</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">146</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isCached = fiPng.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() || fiSvg.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">147</span><span class="doxyLineContent"><span class="doxyHighlight">        formula-&gt;<a href="/web-doxygen/docs/api/classes/formula/#ab1e3947577b724a83ee9f51124abc71e">setCached</a>(isCached);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">148</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("formula %d: cached=%d\n",formula-&gt;id(),isCached);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">149</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">150</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fiPngDark((dir+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+formImgName+</span><span class="doxyHighlightStringLiteral">"_dark.png"</span><span class="doxyHighlight">).str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">151</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="/web-doxygen/docs/api/classes/fileinfo">FileInfo</a> fiSvgDark((dir+</span><span class="doxyHighlightStringLiteral">"/"</span><span class="doxyHighlight">+formImgName+</span><span class="doxyHighlightStringLiteral">"_dark.svg"</span><span class="doxyHighlight">).str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> isCachedDark = fiPngDark.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>() || fiSvgDark.<a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">exists</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">        formula-&gt;<a href="/web-doxygen/docs/api/classes/formula/#a3a025efe9a3c4850b11efd9f5905213e">setCachedDark</a>(isCachedDark);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightComment">//printf("formula %d: cachedDark=%d\n",formula-&gt;id(),isCachedDark);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">155</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// For the first repository all formulas should be new (e.g. formulaCount==0).</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// For the other repositories the same number of formulas should be found</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// (and number of formulas should be the same for all repositories, content is already check above)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (formulaCount&gt;0 &amp;&amp; formulaCount!=<a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulas.size()) </span><span class="doxyHighlightComment">// inconsistency between repositories</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>(</span><span class="doxyHighlightStringLiteral">"differences detected between formula.repository files; forcing upgrade.\n"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;repositoriesValid = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span><span class="doxyHighlight"> </span><span class="doxyHighlightComment">// no repository found for an output format</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;repositoriesValid = </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/fileinfo/#a47d49db8cb8797153885c4d5b7b0911f">FileInfo::exists</a>, <a href="/web-doxygen/docs/api/classes/formula/#ae4b7648ae0124da8456fa2c8e51991ba">Formula::id</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#a8f2cc27e16d343117eb7cdf4e279dbef">msg</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a0579eaf8c245a77f1e804a3cf1b0aa73">Portable::openInputStream</a>, <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>, <a href="/web-doxygen/docs/api/files/src/anchor-cpp/#a85ba602a660bdb3bbeb43cc600de3008">prefix</a>, <a href="/web-doxygen/docs/api/namespaces/reg/#a168f937e54607f4cf5597fa8e5aabcb7">reg::search</a>, <a href="/web-doxygen/docs/api/classes/formula/#ab1e3947577b724a83ee9f51124abc71e">Formula::setCached</a>, <a href="/web-doxygen/docs/api/classes/formula/#a3a025efe9a3c4850b11efd9f5905213e">Formula::setCachedDark</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a>, <a href="/web-doxygen/docs/api/classes/formula/#a67b9ebbbe7e4814eb09bbf734af69b0e">Formula::text</a> and <a href="/web-doxygen/docs/api/files/src/message-h/#a57260e9c056d53af9794da5e7a11b522">warn_uncond</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a59d66805ece9da6ffd55fa4cc8252ef1">parseInput</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## formula functions

### addFormula {#a263c84263295a94dd1593d39f2c435f5}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">int FormulaManager::addFormula (const std::string &amp; formulaText, int width=-1, int height=-1)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 72 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>, definition at line 691 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a263c84263295a94dd1593d39f2c435f5">691</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> <a href="#a263c84263295a94dd1593d39f2c435f5">FormulaManager::addFormula</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;formulaText,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> width,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> height)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">692</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">693</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/formula">Formula</a> *formula = <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulas.find(formulaText);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">694</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (formula) </span><span class="doxyHighlightComment">// same formula already stored</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">695</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">696</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> formula-&gt;<a href="/web-doxygen/docs/api/classes/formula/#ae4b7648ae0124da8456fa2c8e51991ba">id</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">697</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">698</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// add new formula</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">699</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = </span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(<a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulas.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">700</span><span class="doxyLineContent"><span class="doxyHighlight">  formula = <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulas.add(formulaText.c_str(),</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,width,height);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">701</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulaIdMap.emplace(</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,formula);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">702</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> id;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">703</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/formula/#ae4b7648ae0124da8456fa2c8e51991ba">Formula::id</a> and <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/commentscan-l/#ad7328f0606e5f8d93daecd7d5babee1d">addFormula</a>.</p>

</div>
</div>

### clear {#a5a181349991e3e72a331b231c9c25f8b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void FormulaManager::clear ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 71 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>, definition at line 685 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5a181349991e3e72a331b231c9c25f8b">685</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5a181349991e3e72a331b231c9c25f8b">FormulaManager::clear</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">686</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">687</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulas.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">688</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulaIdMap.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">689</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>.</p>


<p>Referenced by <a href="#a9ff2d153c001e2b9d9b054200d34c6a2">checkRepositories</a>, <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#ae12e94f5218f3afc8df4086a2121cd4d">cleanUpDoxygen</a> and <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a798729dca95209ecdc609807a653a2bf">clearAll</a>.</p>

</div>
</div>

### findFormula {#aa15bea658260218b4b6c3193df2c5856}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const Formula * FormulaManager::findFormula (int formulaId)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 73 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>, definition at line 705 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aa15bea658260218b4b6c3193df2c5856">705</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/formula">Formula</a> *<a href="#aa15bea658260218b4b6c3193df2c5856">FormulaManager::findFormula</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> formulaId)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">706</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">707</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight">   it  = <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulaIdMap.find(formulaId);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">708</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it != <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulaIdMap.end() ? it-&gt;second : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">709</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docformula/#ae40d1dafb6c93681ddf0a9bc2e961053">DocFormula::DocFormula</a> and <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#aa9e3a7cf34aceba68750ff3ff94acf34">HtmlDocVisitor::operator()</a>.</p>

</div>
</div>

### hasFormulas {#a4b5c2d7e0c8001ae48514de0b468eb87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool FormulaManager::hasFormulas ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 74 of file <a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a>, definition at line 720 of file <a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a4b5c2d7e0c8001ae48514de0b468eb87">720</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a4b5c2d7e0c8001ae48514de0b468eb87">FormulaManager::hasFormulas</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">721</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">722</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> !<a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>-&gt;formulas.empty();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">723</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#ad6efed826faf400f0c45b49d7dd79f0d">p</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a3efb8cd50f4362e3d58e72febfb872fa">generateOutput</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/formula-cpp">formula.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/formula-h">formula.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
