---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/callcontext
custom_edit_url: null
toc_max_heading_level: 4
keywords:
  - doxygen
  - reference
  - class

---

<div class="doxyPage">

# The `CallContext` Class Reference

<p>Represents the call context. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class CallContext { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">src/scopedtypevariant.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acf102c125585ad2e1bbfd53f71bdf736">CallContext</a> ()</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8757d0d18b9145ac439489a6d48e5109">setScope</a> (const ScopedTypeVariant &amp;stv)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8f402077d952a747c4c590e4242dd9eb">pushScope</a> (const QCString &amp;name_, const QCString &amp;type_, int bracketCount_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8147660c0aef8f928270662b79d5907f">popScope</a> (QCString &amp;name_, QCString &amp;type_, int &amp;bracketCount_)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a7869d538aef25757711715bbd042ab62">clear</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/scopedtypevariant">ScopedTypeVariant</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a59fbf46a5795170aaea214c2a47c9553">getScope</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::vector&lt; <a href="/web-doxygen/docs/api/structs/callcontext/ctx">Ctx</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a></td>
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

<p>Represents the call context.</p>

<p>Definition at line 139 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### CallContext() {#acf102c125585ad2e1bbfd53f71bdf736}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">CallContext::CallContext ()</td>
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



<p>Definition at line 151 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acf102c125585ad2e1bbfd53f71bdf736">151</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#acf102c125585ad2e1bbfd53f71bdf736">CallContext</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">152</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">153</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#a7869d538aef25757711715bbd042ab62">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">154</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#a7869d538aef25757711715bbd042ab62">clear</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### clear() {#a7869d538aef25757711715bbd042ab62}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallContext::clear ()</td>
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



<p>Definition at line 175 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a7869d538aef25757711715bbd042ab62">175</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a7869d538aef25757711715bbd042ab62">clear</a>()</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">176</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">177</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">178</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>.emplace_back(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(),0);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">179</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>.</p>


<p>Referenced by <a href="#acf102c125585ad2e1bbfd53f71bdf736">CallContext</a>.</p>

</div>
</div>

### getScope() {#a59fbf46a5795170aaea214c2a47c9553}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const ScopedTypeVariant CallContext::getScope ()</td>
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



<p>Definition at line 180 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a59fbf46a5795170aaea214c2a47c9553">180</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/scopedtypevariant">ScopedTypeVariant</a> <a href="#a59fbf46a5795170aaea214c2a47c9553">getScope</a>()</span><span class="doxyHighlightKeyword"> const</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">181</span><span class="doxyLineContent"><span class="doxyHighlightKeyword">    </span><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">182</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>.back().stv;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>.</p>

</div>
</div>

### popScope() {#a8147660c0aef8f928270662b79d5907f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallContext::popScope (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name_, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type_, int &amp; bracketCount_)</td>
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



<p>Definition at line 164 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8147660c0aef8f928270662b79d5907f">164</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8147660c0aef8f928270662b79d5907f">popScope</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name_,<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;type_, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;bracketCount_)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">165</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">166</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>.size()&gt;1)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">167</span><span class="doxyLineContent"><span class="doxyHighlight">      {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">168</span><span class="doxyLineContent"><span class="doxyHighlight">        </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/structs/callcontext/ctx">Ctx</a> &amp;ctx = <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">169</span><span class="doxyLineContent"><span class="doxyHighlight">        name_ = ctx.<a href="/web-doxygen/docs/api/structs/callcontext/ctx/#a25706b50d9a1377bc3c8d955047ad4fc">name</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">170</span><span class="doxyLineContent"><span class="doxyHighlight">        type_ = ctx.<a href="/web-doxygen/docs/api/structs/callcontext/ctx/#a4f7150e244df309082ff5cc1abb0806f">type</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">171</span><span class="doxyLineContent"><span class="doxyHighlight">        bracketCount_ = ctx.<a href="/web-doxygen/docs/api/structs/callcontext/ctx/#a8768bac9d029bdc223a04b1e11ab282f">bracketCount</a>;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">172</span><span class="doxyLineContent"><span class="doxyHighlight">        <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>.pop_back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">173</span><span class="doxyLineContent"><span class="doxyHighlight">      }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">174</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/structs/callcontext/ctx/#a8768bac9d029bdc223a04b1e11ab282f">CallContext::Ctx::bracketCount</a>, <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>, <a href="/web-doxygen/docs/api/structs/callcontext/ctx/#a25706b50d9a1377bc3c8d955047ad4fc">CallContext::Ctx::name</a> and <a href="/web-doxygen/docs/api/structs/callcontext/ctx/#a4f7150e244df309082ff5cc1abb0806f">CallContext::Ctx::type</a>.</p>

</div>
</div>

### pushScope() {#a8f402077d952a747c4c590e4242dd9eb}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallContext::pushScope (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name_, const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; type_, int bracketCount_)</td>
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



<p>Definition at line 160 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8f402077d952a747c4c590e4242dd9eb">160</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8f402077d952a747c4c590e4242dd9eb">pushScope</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name_,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;type_, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> bracketCount_)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">161</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">162</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>.emplace_back(name_,type_,bracketCount_);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">163</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>Reference <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>.</p>

</div>
</div>

### setScope() {#a8757d0d18b9145ac439489a6d48e5109}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void CallContext::setScope (const <a href="/web-doxygen/docs/api/classes/scopedtypevariant">ScopedTypeVariant</a> &amp; stv)</td>
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



<p>Definition at line 155 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8757d0d18b9145ac439489a6d48e5109">155</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a8757d0d18b9145ac439489a6d48e5109">setScope</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/scopedtypevariant">ScopedTypeVariant</a> &amp;stv)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">156</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">157</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/structs/callcontext/ctx">Ctx</a> &amp;ctx = <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>.back();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">      ctx.<a href="/web-doxygen/docs/api/structs/callcontext/ctx/#a725fa748acce00d5e41f9c1f00c7be95">stv</a>=stv;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">159</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>

</div>


<p>References <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a> and <a href="/web-doxygen/docs/api/structs/callcontext/ctx/#a725fa748acce00d5e41f9c1f00c7be95">CallContext::Ctx::stv</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m\_stvList {#ab06d8743378a2f8012f1f6268321298e}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::vector&lt;Ctx&gt; CallContext::m_stvList</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 186 of file <a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab06d8743378a2f8012f1f6268321298e">186</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::vector&lt;Ctx&gt; <a href="#ab06d8743378a2f8012f1f6268321298e">m_stvList</a>;</span></span></div>

</div>


<p>Referenced by <a href="#a7869d538aef25757711715bbd042ab62">clear</a>, <a href="#a59fbf46a5795170aaea214c2a47c9553">getScope</a>, <a href="#a8147660c0aef8f928270662b79d5907f">popScope</a>, <a href="#a8f402077d952a747c4c590e4242dd9eb">pushScope</a> and <a href="#a8757d0d18b9145ac439489a6d48e5109">setScope</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following file:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/scopedtypevariant-h">scopedtypevariant.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
