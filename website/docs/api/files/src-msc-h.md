---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/msc-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `msc.h` File Reference



## Enumerations Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">enum class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top">MscOutputFormat { <a href="#a6cf71dda84c5602c6239cca31028f656">...</a> }</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a> (const QCString &amp;inFile, const QCString &amp;outDir, const QCString &amp;outFile, MscOutputFormat format, const QCString &amp;srcFile, int srcLine)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a67e28708c6995f956731257a78846696">getMscImageMapFromFile</a> (const QCString &amp;inFile, const QCString &amp;outDir, const QCString &amp;relPath, const QCString &amp;context, const QCString &amp;srcFile, int srcLine)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a1a9fc7a255fa7160711dd47a9de1695b">writeMscImageMapFromFile</a> (TextStream &amp;t, const QCString &amp;inFile, const QCString &amp;outDir, const QCString &amp;relPath, const QCString &amp;baseName, const QCString &amp;context, MscOutputFormat format, const QCString &amp;srcFile, int srcLine)</td>
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

## Enumerations

### MscOutputFormat {#a6cf71dda84c5602c6239cca31028f656}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">enum class MscOutputFormat </td>
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
<td class="doxyEnumItemName">BITMAP<a id="a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">EPS<a id="a6cf71dda84c5602c6239cca31028f656ac2c027d8c62500300145c3043546d4c6"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

<tr class="doxyEnumItem">
<td class="doxyEnumItemName">SVG<a id="a6cf71dda84c5602c6239cca31028f656acd15a75c26008696647b31a3f0de43b3"></a></td>
<td class="doxyEnumItemDescription"></td>
</tr>

</table>
</dd>
</dl>

<p>Definition at line 22 of file <a href="/web-doxygen/docs/api/files/src/msc-h">msc.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544">22</a></span><span class="doxyLineContent"><span class="doxyHighlightKeyword">enum class</span><span class="doxyHighlight"> <a href="#a6cf71dda84c5602c6239cca31028f656">MscOutputFormat</a> { <a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35a75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/dia-h/#abc13e8949e66677e61029ee294434c35ac2c027d8c62500300145c3043546d4c6">EPS</a>, <a href="#a6cf71dda84c5602c6239cca31028f656acd15a75c26008696647b31a3f0de43b3">SVG</a> };</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Functions

### getMscImageMapFromFile() {#a67e28708c6995f956731257a78846696}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString getMscImageMapFromFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inFile, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; outDir, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; context, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 28 of file <a href="/web-doxygen/docs/api/files/src/msc-h">msc.h</a>.</p>

</div>
</div>

### writeMscGraphFromFile() {#a9bc09a2eafdeb16f4333068ebdf962ca}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeMscGraphFromFile (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inFile, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; outDir, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; outFile, <a href="#a6cf71dda84c5602c6239cca31028f656">MscOutputFormat</a> format, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-doxygen/docs/api/files/src/msc-h">msc.h</a>, definition at line 157 of file <a href="/web-doxygen/docs/api/files/src/msc-cpp">msc.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">157</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a9bc09a2eafdeb16f4333068ebdf962ca">writeMscGraphFromFile</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inFile,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;outDir,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;outFile,<a href="#a6cf71dda84c5602c6239cca31028f656">MscOutputFormat</a> format,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">                           </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">160</span><span class="doxyLineContent"><span class="doxyHighlight">                          )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> absOutFile = outDir;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">  absOutFile+=<a href="/web-doxygen/docs/api/namespaces/portable/#a0f30be3f0aed0b88804816f3e6310ee4">Portable::pathSeparator</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">164</span><span class="doxyLineContent"><span class="doxyHighlight">  absOutFile+=outFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">  mscgen_format_t msc_format = mscgen_format_png;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imgName = absOutFile;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (format)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544">MscOutputFormat::BITMAP</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">      msc_format = mscgen_format_png;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">      imgName+=</span><span class="doxyHighlightStringLiteral">".png"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a6cf71dda84c5602c6239cca31028f656ac2c027d8c62500300145c3043546d4c6">MscOutputFormat::EPS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      msc_format = mscgen_format_eps;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">      imgName+=</span><span class="doxyHighlightStringLiteral">".eps"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a6cf71dda84c5602c6239cca31028f656acd15a75c26008696647b31a3f0de43b3">MscOutputFormat::SVG</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">      msc_format = mscgen_format_svg;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">      imgName+=</span><span class="doxyHighlightStringLiteral">".svg"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!<a href="/web-doxygen/docs/api/files/src/msc-cpp/#af50f1fc37531bed71dba97fcf1ea5dd9">do_mscgen_generate</a>(inFile,imgName,msc_format,srcFile,srcLine))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> ( (format==<a href="#a6cf71dda84c5602c6239cca31028f656ac2c027d8c62500300145c3043546d4c6">MscOutputFormat::EPS</a>) &amp;&amp; (<a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(USE_PDFLATEX)) )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> epstopdfArgs(<a href="/web-doxygen/docs/api/files/src/dia-cpp/#ad1b6b56d95d64570f2be3ca005b63412">maxCmdLine</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">    epstopdfArgs.<a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">sprintf</a>(</span><span class="doxyHighlightStringLiteral">"\"%s.eps\" --outfile=\"%s.pdf\""</span><span class="doxyHighlight">,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">                         <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(absOutFile),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(absOutFile));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">195</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>(</span><span class="doxyHighlightStringLiteral">"epstopdf"</span><span class="doxyHighlight">,epstopdfArgs)!=0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">196</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/message-h/#aeeea1c30323e9f0c650090553516bc25">err_full</a>(srcFile,srcLine,</span><span class="doxyHighlightStringLiteral">"Problems running epstopdf when processing '{}.eps'. Check your TeX installation!"</span><span class="doxyHighlight">, absOutFile);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/classes/dir">Dir</a>().<a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">remove</a>((absOutFile + </span><span class="doxyHighlightStringLiteral">".eps"</span><span class="doxyHighlight">).data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> i=std::max(imgName.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'/'</span><span class="doxyHighlight">),imgName.<a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">findRev</a>(</span><span class="doxyHighlightCharLiteral">'\\'</span><span class="doxyHighlight">));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">206</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i!=-1) </span><span class="doxyHighlightComment">// strip path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">207</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlight">    imgName=imgName.<a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">right</a>(imgName.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-i-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>-&gt;addImageFile(imgName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#af50f1fc37531bed71dba97fcf1ea5dd9">do_mscgen_generate</a>, <a href="#a6cf71dda84c5602c6239cca31028f656ac2c027d8c62500300145c3043546d4c6">EPS</a>, <a href="/web-doxygen/docs/api/files/src/message-h/#aeeea1c30323e9f0c650090553516bc25">err_full</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aac487a6223e056bcf37b9c7c0f993e30ac1748698805fbe34841ed03d0be6a647">QCString::ExplicitSize</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ab47a6435c16d61d04fb448f1080b4e26">QCString::findRev</a>, <a href="/web-doxygen/docs/api/classes/doxygen/#a91aa9805ef52783816d9da5e457b8cfb">Doxygen::indexList</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/files/src/dia-cpp/#ad1b6b56d95d64570f2be3ca005b63412">maxCmdLine</a>, <a href="/web-doxygen/docs/api/namespaces/portable/#a0f30be3f0aed0b88804816f3e6310ee4">Portable::pathSeparator</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/classes/dir/#a5a64060f8e1731e8f00da7e8f7051e4b">Dir::remove</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a8f4aa5417f6a834f28c7148a1fe262d5">QCString::right</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#aa2dccf89cb25346c3ee81d75aa5859da">QCString::sprintf</a>, <a href="#a6cf71dda84c5602c6239cca31028f656acd15a75c26008696647b31a3f0de43b3">SVG</a> and <a href="/web-doxygen/docs/api/namespaces/portable/#ab30a636186b72a67d57e9f7f1e917e99">Portable::system</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a5b2c9442335fc951437fc0cfb466c90c">DocbookDocVisitor::startMscFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#aeef2a244f24ea46106204e063fae5273">LatexDocVisitor::startMscFile</a>, <a href="/web-doxygen/docs/api/classes/docbookdocvisitor/#a370d999e7360a39203535dff006b1bf2">DocbookDocVisitor::writeMscFile</a>, <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a928ca1eefc8caee8adbf197d19f9d687">HtmlDocVisitor::writeMscFile</a>, <a href="/web-doxygen/docs/api/classes/latexdocvisitor/#ada18505ac90bb92f4ce279d503dba853">LatexDocVisitor::writeMscFile</a> and <a href="/web-doxygen/docs/api/classes/rtfdocvisitor/#ab70c2bad1c74761849c430861ec0d2da">RTFDocVisitor::writeMscFile</a>.</p>

</div>
</div>

### writeMscImageMapFromFile() {#a1a9fc7a255fa7160711dd47a9de1695b}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void writeMscImageMapFromFile (<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp; t, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; inFile, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; outDir, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; relPath, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; baseName, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; context, <a href="#a6cf71dda84c5602c6239cca31028f656">MscOutputFormat</a> format, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; srcFile, int srcLine)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 32 of file <a href="/web-doxygen/docs/api/files/src/msc-h">msc.h</a>, definition at line 233 of file <a href="/web-doxygen/docs/api/files/src/msc-cpp">msc.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/msc-cpp/#a1a9fc7a255fa7160711dd47a9de1695b">233</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/msc-cpp/#a1a9fc7a255fa7160711dd47a9de1695b">writeMscImageMapFromFile</a>(<a href="/web-doxygen/docs/api/classes/textstream">TextStream</a> &amp;t,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;inFile,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">234</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;outDir,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">235</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;relPath,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">236</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;baseName,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">237</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;context,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">238</span><span class="doxyLineContent"><span class="doxyHighlight">                              <a href="#a6cf71dda84c5602c6239cca31028f656">MscOutputFormat</a> format,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">239</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;srcFile,</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">240</span><span class="doxyLineContent"><span class="doxyHighlight">                              </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> srcLine</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">241</span><span class="doxyLineContent"><span class="doxyHighlight">                            )</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">242</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">243</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> mapName = baseName+</span><span class="doxyHighlightStringLiteral">".map"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">244</span><span class="doxyLineContent"><span class="doxyHighlight">  t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;img src=\""</span><span class="doxyHighlight"> &lt;&lt; relPath &lt;&lt; baseName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"."</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">245</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">switch</span><span class="doxyHighlight"> (format)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">246</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">247</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544">MscOutputFormat::BITMAP</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">248</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"png"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">249</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">250</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a6cf71dda84c5602c6239cca31028f656ac2c027d8c62500300145c3043546d4c6">MscOutputFormat::EPS</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">251</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"eps"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">252</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">253</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">case</span><span class="doxyHighlight"> <a href="#a6cf71dda84c5602c6239cca31028f656acd15a75c26008696647b31a3f0de43b3">MscOutputFormat::SVG</a>:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">254</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"svg"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">255</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">break</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">256</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">default</span><span class="doxyHighlight">:</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">257</span><span class="doxyLineContent"><span class="doxyHighlight">      t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"unknown"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">258</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">259</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> imap = <a href="/web-doxygen/docs/api/files/src/msc-cpp/#aa243c32e58b19c8d831a826a03bf3562">getMscImageMapFromFile</a>(inFile,outDir,relPath,context,format==<a href="#a6cf71dda84c5602c6239cca31028f656acd15a75c26008696647b31a3f0de43b3">MscOutputFormat::SVG</a>,srcFile,srcLine);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">260</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!imap.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">261</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">262</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" alt=\""</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">263</span><span class="doxyLineContent"><span class="doxyHighlight">      &lt;&lt; baseName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" border=\"0\" usemap=\"#"</span><span class="doxyHighlight"> &lt;&lt; mapName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">264</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;map name=\""</span><span class="doxyHighlight"> &lt;&lt; mapName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" id=\""</span><span class="doxyHighlight"> &lt;&lt; mapName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\"&gt;"</span><span class="doxyHighlight"> &lt;&lt; imap &lt;&lt; </span><span class="doxyHighlightStringLiteral">"&lt;/map&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">265</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">266</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">267</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">268</span><span class="doxyLineContent"><span class="doxyHighlight">    t &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" alt=\""</span><span class="doxyHighlight"> &lt;&lt; baseName &lt;&lt; </span><span class="doxyHighlightStringLiteral">"\" border=\"0\"/&gt;\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">269</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">270</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="#a6cf71dda84c5602c6239cca31028f656a75948fda661fec9a2342cec45646e544">BITMAP</a>, <a href="#a6cf71dda84c5602c6239cca31028f656ac2c027d8c62500300145c3043546d4c6">EPS</a>, <a href="/web-doxygen/docs/api/files/src/msc-cpp/#aa243c32e58b19c8d831a826a03bf3562">getMscImageMapFromFile</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a> and <a href="#a6cf71dda84c5602c6239cca31028f656acd15a75c26008696647b31a3f0de43b3">SVG</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/htmldocvisitor/#a928ca1eefc8caee8adbf197d19f9d687">HtmlDocVisitor::writeMscFile</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
