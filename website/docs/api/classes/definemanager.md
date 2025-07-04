---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/definemanager
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `DefineManager` Class Reference

<p>Class that manages the defines available while preprocessing files. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DefineManager { ... }
</div>

## Friends Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">class</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8146c1027737f308e2f7c7dc67a09f87">DefinesPerFile</a></td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6cc40994ee9d3b5678232061d9d005a8">addInclude</a> (const std::string &amp;fromFileName, const std::string &amp;toFileName)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab191c34dd306688f725659254b218b1a">store</a> (const std::string &amp;fileName, const DefineMap &amp;fromMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acfbe87b4cb51176c4656dd471849a112">retrieve</a> (const std::string &amp;fileName, DefineMap &amp;toMap)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a483e505a7bd2ebcd9c3ae9287473afa1">alreadyProcessed</a> (const std::string &amp;fileName) const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/definemanager/definesperfile">DefinesPerFile</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af28f29db081594e4c5adbf2894075669">find</a> (const std::string &amp;fileName) const</td>
</tr>
<tr class="doxyMemberIndexDescription">
<td class="doxyMemberIndexDescriptionLeft"></td>
<td class="doxyMemberIndexDescriptionRight">
<p>Helper function to return the <a href="/web-doxygen/docs/api/classes/definemanager/definesperfile">DefinesPerFile</a> object for a given file name. <a href="#af28f29db081594e4c5adbf2894075669">More...</a></p>
</td>
</tr>
<tr class="doxyMemberIndexSeparator">
<td class="doxyMemberIndexSeparator" colspan="2"></td>
</tr>

</table>

## Private Member Attributes Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unordered_map&lt; std::string, std::unique_ptr&lt; <a href="/web-doxygen/docs/api/classes/definemanager/definesperfile">DefinesPerFile</a> &gt; &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a></td>
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

<p>Class that manages the defines available while preprocessing files.</p>

<p>Definition at line 114 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxySectionDef">

## Friends

### DefinesPerFile {#a8146c1027737f308e2f7c7dc67a09f87}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">friend class DefinesPerFile</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line 170 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8146c1027737f308e2f7c7dc67a09f87">170</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">friend</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">class </span><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/definemanager/definesperfile">DefinesPerFile</a>;</span></span></div>

</div>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### addInclude() {#a6cc40994ee9d3b5678232061d9d005a8}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefineManager::addInclude (const std::string &amp; fromFileName, const std::string &amp; toFileName)</td>
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



<p>Definition at line 173 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a6cc40994ee9d3b5678232061d9d005a8">173</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a6cc40994ee9d3b5678232061d9d005a8">addInclude</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fromFileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;toFileName)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("DefineManager::addInclude('%s'-&gt;'%s')\n",fromFileName.c_str(),toFileName.c_str());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.find(fromFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">        it = <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.emplace(fromFileName,std::make_unique&lt;DefinesPerFile&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">)).first;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dpf = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">      dpf-&gt;addInclude(toFileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.</p>

</div>
</div>

### alreadyProcessed() {#a483e505a7bd2ebcd9c3ae9287473afa1}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool DefineManager::alreadyProcessed (const std::string &amp; fileName)</td>
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



<p>Definition at line 207 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a483e505a7bd2ebcd9c3ae9287473afa1">207</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="#a483e505a7bd2ebcd9c3ae9287473afa1">alreadyProcessed</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fileName)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">208</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">209</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.find(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">210</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">211</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">212</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it-&gt;second-&gt;stored();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">213</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">214</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">false</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">215</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.</p>

</div>
</div>

### retrieve() {#acfbe87b4cb51176c4656dd471849a112}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefineManager::retrieve (const std::string &amp; fileName, <a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> &amp; toMap)</td>
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



<p>Definition at line 196 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acfbe87b4cb51176c4656dd471849a112">196</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#acfbe87b4cb51176c4656dd471849a112">retrieve</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fileName,<a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> &amp;toMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">197</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">198</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.find(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">199</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it!=<a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">200</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">201</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;dpf = it-&gt;second;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">202</span><span class="doxyLineContent"><span class="doxyHighlight">        dpf-&gt;retrieve(toMap);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">203</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">204</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("DefineManager::retrieve(%s,#=%zu)\n",fileName.c_str(),toMap.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">205</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.</p>

</div>
</div>

### store() {#ab191c34dd306688f725659254b218b1a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DefineManager::store (const std::string &amp; fileName, const <a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> &amp; fromMap)</td>
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



<p>Definition at line 185 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab191c34dd306688f725659254b218b1a">185</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab191c34dd306688f725659254b218b1a">store</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fileName,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/pre-l/#a0dd482007e6d1df4a67172cda7af1a61">DefineMap</a> &amp;fromMap)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("DefineManager::store(%s,#=%zu)\n",fileName.c_str(),fromMap.size());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.find(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (it==<a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.end())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">        it = <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.emplace(fileName,std::make_unique&lt;DefinesPerFile&gt;(</span><span class="doxyHighlightKeyword">this</span><span class="doxyHighlight">)).first;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">193</span><span class="doxyLineContent"><span class="doxyHighlight">      it-&gt;second-&gt;store(fromMap);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">194</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Functions

### find() {#af28f29db081594e4c5adbf2894075669}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DefinesPerFile * DefineManager::find (const std::string &amp; fileName)</td>
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

<p>Helper function to return the <a href="/web-doxygen/docs/api/classes/definemanager/definesperfile">DefinesPerFile</a> object for a given file name.</p>

<p>Definition at line 219 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af28f29db081594e4c5adbf2894075669">219</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/definemanager/definesperfile">DefinesPerFile</a> *<a href="#af28f29db081594e4c5adbf2894075669">find</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> std::string &amp;fileName)</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">220</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">221</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> it = <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.find(fileName);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">222</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> it!=<a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.end() ? it-&gt;second.get() : </span><span class="doxyHighlightKeyword">nullptr</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">223</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_fileMap {#ac670534f6d2a7daa296964c0ce91d216}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unordered_map&lt; std::string, std::unique_ptr&lt;DefinesPerFile&gt; &gt; DefineManager::m_fileMap</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 225 of file <a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac670534f6d2a7daa296964c0ce91d216">225</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unordered_map&lt; std::string, std::unique_ptr&lt;DefinesPerFile&gt; &gt; <a href="#ac670534f6d2a7daa296964c0ce91d216">m_fileMap</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a6cc40994ee9d3b5678232061d9d005a8">addInclude</a>, <a href="#a483e505a7bd2ebcd9c3ae9287473afa1">alreadyProcessed</a>, <a href="#af28f29db081594e4c5adbf2894075669">find</a>, <a href="#acfbe87b4cb51176c4656dd471849a112">retrieve</a> and <a href="#ab191c34dd306688f725659254b218b1a">store</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/pre-l">pre.l</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
