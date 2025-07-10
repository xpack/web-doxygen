---

# DO NOT EDIT!
# Automatically generated via doxygen2docusaurus by Doxygen.

slug: /api/files/src/aliases-h
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - file

---

<div class="doxyPage">

# The `aliases.h` File Reference



## Included Headers

<div class="doxyIncludesList">#include &lt;string&gt;
#include &lt;string_view&gt;
</div>

## Functions Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top">std::string</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a6b8eb655dd98d5b700055fc5ae0440dc">resolveAliasCmd</a> (std::string_view aliasCmd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0e6d82cb4e5eee3e0fa6a2edb6c2180f">isAliasCmd</a> (std::string_view aliasCmd)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af229513c065c90147eff5559f0844c00">readAliases</a> ()</td>
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

### isAliasCmd() {#a0e6d82cb4e5eee3e0fa6a2edb6c2180f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">bool isAliasCmd (std::string_view aliasCmd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 23 of file <a href="/web-doxygen/docs/api/files/src/aliases-h">aliases.h</a>, definition at line 528 of file <a href="/web-doxygen/docs/api/files/src/aliases-cpp">aliases.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/aliases-cpp/#a0e6d82cb4e5eee3e0fa6a2edb6c2180f">528</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#a0e6d82cb4e5eee3e0fa6a2edb6c2180f">isAliasCmd</a>(std::string_view aliasCmd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">529</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">530</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#aabfebc02acd057d5239011aef3275a64">g_aliasInfoMap</a>.find(std::string{aliasCmd}) != <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#aabfebc02acd057d5239011aef3275a64">g_aliasInfoMap</a>.end();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">531</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#aabfebc02acd057d5239011aef3275a64">g_aliasInfoMap</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/docpara/#a1e432b15eb1a56ba1c560815a145aea3">DocPara::handleCommand</a>.</p>

</div>
</div>

### readAliases() {#af229513c065c90147eff5559f0844c00}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void readAliases ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 24 of file <a href="/web-doxygen/docs/api/files/src/aliases-h">aliases.h</a>, definition at line 170 of file <a href="/web-doxygen/docs/api/files/src/aliases-cpp">aliases.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/aliases-cpp/#af229513c065c90147eff5559f0844c00">170</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#af229513c065c90147eff5559f0844c00">readAliases</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// add aliases to a dictionary</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/files/src/containers-h/#ac8d53003529fb2d062d614077fe6857c">StringVector</a> &amp;aliasList = <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>(ALIASES);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;al : aliasList)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">175</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#ad1fa14f7ebd8d6adedcac12a2fb83ae1">addValidAliasToMap</a>(al);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,overloads] : <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#aabfebc02acd057d5239011aef3275a64">g_aliasInfoMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">180</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[numParams,aliasInfo] : overloads)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">      aliasInfo.value = <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#a436ad51276d8a9373fa734742a56fb4f">expandAlias</a>(name+</span><span class="doxyHighlightStringLiteral">":"</span><span class="doxyHighlight">+std::to_string(numParams),aliasInfo.value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[name,overloads] : <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#aabfebc02acd057d5239011aef3275a64">g_aliasInfoMap</a>)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;[numParams,aliasInfo] : overloads)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">188</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">189</span><span class="doxyLineContent"><span class="doxyHighlight">      aliasInfo.value = <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#af47739c31cd60617e53ac5a363514817">escapeAlias</a>(aliasInfo.value);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">190</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">191</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">192</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#ad1fa14f7ebd8d6adedcac12a2fb83ae1">addValidAliasToMap</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a15e896ce0b99792d1344b66af98928e7">Config_getList</a>, <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#af47739c31cd60617e53ac5a363514817">escapeAlias</a>, <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#a436ad51276d8a9373fa734742a56fb4f">expandAlias</a> and <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#aabfebc02acd057d5239011aef3275a64">g_aliasInfoMap</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/doxygen-cpp/#a10458b8a16238a4eae5fb5019df747e8">adjustConfiguration</a>.</p>

</div>
</div>

### resolveAliasCmd() {#a6b8eb655dd98d5b700055fc5ae0440dc}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::string resolveAliasCmd (std::string_view aliasCmd)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 22 of file <a href="/web-doxygen/docs/api/files/src/aliases-h">aliases.h</a>, definition at line 504 of file <a href="/web-doxygen/docs/api/files/src/aliases-cpp">aliases.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="/web-doxygen/docs/api/files/src/aliases-cpp/#a6b8eb655dd98d5b700055fc5ae0440dc">504</a></span><span class="doxyLineContent"><span class="doxyHighlight">std::string <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#a6b8eb655dd98d5b700055fc5ae0440dc">resolveAliasCmd</a>(std::string_view aliasCmd)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">505</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">506</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/containers-h/#a68c09b08e1fafb7be76584846eebe628">StringUnorderedSet</a> aliasesProcessed;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">507</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Expanding: '%s'\n",qPrint(aliasCmd));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">508</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string result = <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#acbc401cf2a803e0e3517389a8a1a5f2e">expandAliasRec</a>(aliasesProcessed,aliasCmd);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">509</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("Expanding result: '%s'-&gt;'%s'\n",qPrint(aliasCmd),qPrint(result));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">510</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da30a6935f9c8708d6bba6a36006c376dc">Debug::Alias</a>,0,</span><span class="doxyHighlightStringLiteral">"Resolving alias: cmd='{}' result='{}'\n"</span><span class="doxyHighlight">,std::string{aliasCmd},result);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">511</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">512</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da30a6935f9c8708d6bba6a36006c376dc">Debug::Alias</a>, <a href="/web-doxygen/docs/api/files/src/aliases-cpp/#acbc401cf2a803e0e3517389a8a1a5f2e">expandAliasRec</a> and <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/commentcnv-l/#a7d6c5be747e636417e19cc8dbbaa38b9">replaceAliases</a>.</p>

</div>
</div>

</div>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/doxygen2docusaurus">doxygen2docusaurus</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
