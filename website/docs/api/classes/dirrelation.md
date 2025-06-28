---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/dirrelation
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `DirRelation` Class Reference

<p>A usage relation between two directories. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class DirRelation { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/dirdef-h">src/dirdef.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#af7ea0932aa290846b11b631dbdde6f65">DirRelation</a> (const QCString &amp;name, const DirDef *src, UsedDir *dst)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#aab57e18f87ae233fae48a141b9d9fcba">source</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/useddir">UsedDir</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a2fc1b42862174170fcb18d6b997b7fcf">destination</a> () const</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a5fa861050993dafb351589f2f1c05326">writeDocumentation</a> (OutputList &amp;ol)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a73890fdede27fd42215794b10b76b05a">getOutputFileBase</a> () const</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a470369422b9a291d75c8ea3cdf48fc5f">m_name</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a0f8d40ddf8119bf256e3c12b33685093">m_src</a></td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/useddir">UsedDir</a> *</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a3e4e275033d30b182a7b88338f11fb77">m_dst</a></td>
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

<p>A usage relation between two directories.</p>

<p>Definition at line 154 of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

<div class="doxySectionDef">

## Public Constructors

### DirRelation() {#af7ea0932aa290846b11b631dbdde6f65}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">DirRelation::DirRelation (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; name, const <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> * src, <a href="/web-doxygen/docs/api/classes/useddir">UsedDir</a> * dst)</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dirdef-h/#l00157">157</a> of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#af7ea0932aa290846b11b631dbdde6f65">157</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#af7ea0932aa290846b11b631dbdde6f65">DirRelation</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;name,</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a> *src,<a href="/web-doxygen/docs/api/classes/useddir">UsedDir</a> *dst)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">158</span><span class="doxyLineContent"><span class="doxyHighlight">      : <a href="#a470369422b9a291d75c8ea3cdf48fc5f">m_name</a>(name), <a href="#a0f8d40ddf8119bf256e3c12b33685093">m_src</a>(src), <a href="#a3e4e275033d30b182a7b88338f11fb77">m_dst</a>(dst) {}</span></span></div>

</div>


References <a href="#a3e4e275033d30b182a7b88338f11fb77">m&#95;dst</a>, <a href="#a470369422b9a291d75c8ea3cdf48fc5f">m&#95;name</a> and <a href="#a0f8d40ddf8119bf256e3c12b33685093">m&#95;src</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### destination() {#a2fc1b42862174170fcb18d6b997b7fcf}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UsedDir * DirRelation::destination ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dirdef-h/#l00160">160</a> of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a2fc1b42862174170fcb18d6b997b7fcf">160</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/useddir">UsedDir</a> *<a href="#a2fc1b42862174170fcb18d6b997b7fcf">destination</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a3e4e275033d30b182a7b88338f11fb77">m_dst</a>; }</span></span></div>

</div>


Reference <a href="#a3e4e275033d30b182a7b88338f11fb77">m&#95;dst</a>.
</div>
</div>

### getOutputFileBase() {#a73890fdede27fd42215794b10b76b05a}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DirRelation::getOutputFileBase ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dirdef-h/#l00162">162</a> of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a73890fdede27fd42215794b10b76b05a">162</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a73890fdede27fd42215794b10b76b05a">getOutputFileBase</a>()</span><span class="doxyHighlightKeyword"> const </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a470369422b9a291d75c8ea3cdf48fc5f">m_name</a>; }</span></span></div>

</div>


Reference <a href="#a470369422b9a291d75c8ea3cdf48fc5f">m&#95;name</a>.

Referenced by <a href="#a5fa861050993dafb351589f2f1c05326">writeDocumentation</a>.
</div>
</div>

### source() {#aab57e18f87ae233fae48a141b9d9fcba}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DirDef * DirRelation::source ()</td>
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


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dirdef-h/#l00159">159</a> of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#aab57e18f87ae233fae48a141b9d9fcba">159</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a>  *<a href="#aab57e18f87ae233fae48a141b9d9fcba">source</a>()</span><span class="doxyHighlightKeyword"> const      </span><span class="doxyHighlight">{ </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="#a0f8d40ddf8119bf256e3c12b33685093">m_src</a>; }</span></span></div>

</div>


Reference <a href="#a0f8d40ddf8119bf256e3c12b33685093">m&#95;src</a>.
</div>
</div>

### writeDocumentation() {#a5fa861050993dafb351589f2f1c05326}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void DirRelation::writeDocumentation (<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp; ol)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Declaration at line <a href="/web-doxygen/docs/api/files/src/dirdef-h/#l00161">161</a> of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>, definition at line <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#l00942">942</a> of file <a href="/web-doxygen/docs/api/files/src/dirdef-cpp">dirdef.cpp</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a5fa861050993dafb351589f2f1c05326">942</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#a5fa861050993dafb351589f2f1c05326">DirRelation::writeDocumentation</a>(<a href="/web-doxygen/docs/api/classes/outputlist">OutputList</a> &amp;ol)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">943</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">944</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> generateTreeView = <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config_getBool</a>(GENERATE_TREEVIEW);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">945</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a885957a64f7d87aefb663c4ec903188f">pushGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">946</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a91f9afddff1974d7805c3d022b754ddf">disableAllBut</a>(<a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">OutputType::Html</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">947</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">948</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> shortTitle=<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDirRelation(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">949</span><span class="doxyLineContent"><span class="doxyHighlight">                      (<a href="#a0f8d40ddf8119bf256e3c12b33685093">m_src</a>-&gt;shortName()+</span><span class="doxyHighlightStringLiteral">" &amp;rarr; "</span><span class="doxyHighlight">+<a href="#a3e4e275033d30b182a7b88338f11fb77">m_dst</a>-&gt;dir()-&gt;shortName()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">950</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> title=<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trDirRelation(</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">951</span><span class="doxyLineContent"><span class="doxyHighlight">                 (<a href="#a0f8d40ddf8119bf256e3c12b33685093">m_src</a>-&gt;displayName()+</span><span class="doxyHighlightStringLiteral">" -&gt; "</span><span class="doxyHighlight">+<a href="#a3e4e275033d30b182a7b88338f11fb77">m_dst</a>-&gt;dir()-&gt;shortName()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">952</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"title={}"</span><span class="doxyHighlight">,title);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">953</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/index-cpp/#a8183f7413c2945be8d3a2ca7ee4f237f">startFile</a>(ol,<a href="#a73890fdede27fd42215794b10b76b05a">getOutputFileBase</a>(),<a href="#a73890fdede27fd42215794b10b76b05a">getOutputFileBase</a>(),</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">954</span><span class="doxyLineContent"><span class="doxyHighlight">            title,<a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a6adf97f83acf6453d4a6a4b1070f3754">HighlightedItem::None</a>,!generateTreeView,<a href="#a0f8d40ddf8119bf256e3c12b33685093">m_src</a>-&gt;getOutputFileBase());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">955</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">956</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (!generateTreeView)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">957</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">958</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// write navigation path</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">959</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="#a0f8d40ddf8119bf256e3c12b33685093">m_src</a>-&gt;writeNavigationPath(ol);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">960</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ab1da800b31634af3c518bfa8c0b8323b">endQuickIndices</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">961</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">962</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#ac891ad4a7081e1ab9d42a637596111db">startContents</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">963</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">964</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;h3&gt;"</span><span class="doxyHighlight">+shortTitle+</span><span class="doxyHighlightStringLiteral">"&lt;/h3&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">965</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;table class=\"dirtab\"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">966</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;tr class=\"dirtab\"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">967</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;th class=\"dirtab\"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">968</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#adfdcf2ba925f05be8beb8cf43deb168a">parseText</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trFileIn(<a href="#a0f8d40ddf8119bf256e3c12b33685093">m_src</a>-&gt;pathFragment()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">969</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;/th&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">970</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;th class=\"dirtab\"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">971</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#adfdcf2ba925f05be8beb8cf43deb168a">parseText</a>(<a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>-&gt;trIncludesFileIn(<a href="#a3e4e275033d30b182a7b88338f11fb77">m_dst</a>-&gt;dir()-&gt;pathFragment()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">972</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;/th&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">973</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;/tr&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">974</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">975</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">for</span><span class="doxyHighlight"> (</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeyword">auto</span><span class="doxyHighlight"> &amp;fp : <a href="#a3e4e275033d30b182a7b88338f11fb77">m_dst</a>-&gt;filePairs())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">976</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">977</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;tr class=\"dirtab\"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">978</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;td class=\"dirtab\"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">979</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a50a5ca2a633e8e9e98f1fdb284b96186">writePartialFilePath</a>(ol,<a href="#a0f8d40ddf8119bf256e3c12b33685093">m_src</a>,fp-&gt;source());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">980</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">981</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;td class=\"dirtab\"&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">982</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a50a5ca2a633e8e9e98f1fdb284b96186">writePartialFilePath</a>(ol,<a href="#a3e4e275033d30b182a7b88338f11fb77">m_dst</a>-&gt;dir(),fp-&gt;destination());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">983</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;/td&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">984</span><span class="doxyLineContent"><span class="doxyHighlight">    ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;/tr&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">985</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">986</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">writeString</a>(</span><span class="doxyHighlightStringLiteral">"&lt;/table&gt;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">987</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">988</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a317bae5a753eac709cf776b2ec2fb732">endContents</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">989</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">990</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac1850678fe273e83bcda397bc2f1b6ec">endFileWithNavPath</a>(ol,<a href="#a0f8d40ddf8119bf256e3c12b33685093">m_src</a>);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">991</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">992</span><span class="doxyLineContent"><span class="doxyHighlight">  ol.<a href="/web-doxygen/docs/api/classes/outputlist/#a94eb1af2ea07425ef1faa539d24adcf8">popGeneratorState</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">993</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO&#95;TRACE</a>, <a href="/web-doxygen/docs/api/files/src/config-h/#a5373d0332a31f16ad7a42037733e8c79">Config&#95;getBool</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a91f9afddff1974d7805c3d022b754ddf">OutputList::disableAllBut</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a317bae5a753eac709cf776b2ec2fb732">OutputList::endContents</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#ac1850678fe273e83bcda397bc2f1b6ec">endFileWithNavPath</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ab1da800b31634af3c518bfa8c0b8323b">OutputList::endQuickIndices</a>, <a href="#a73890fdede27fd42215794b10b76b05a">getOutputFileBase</a>, <a href="/web-doxygen/docs/api/files/src/outputgen-h/#a4e0517338e6c4a31a2addafc06d4f3a3a3135f4019bee015e2d1ae7f77f9f3f64">Html</a>, <a href="#a3e4e275033d30b182a7b88338f11fb77">m&#95;dst</a>, <a href="#a0f8d40ddf8119bf256e3c12b33685093">m&#95;src</a>, <a href="/web-doxygen/docs/api/files/src/index-h/#a6643b7765422a7eb577f0b2ed8fb2e09a6adf97f83acf6453d4a6a4b1070f3754">None</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#adfdcf2ba925f05be8beb8cf43deb168a">OutputList::parseText</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a94eb1af2ea07425ef1faa539d24adcf8">OutputList::popGeneratorState</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#a885957a64f7d87aefb663c4ec903188f">OutputList::pushGeneratorState</a>, <a href="/web-doxygen/docs/api/classes/outputlist/#ac891ad4a7081e1ab9d42a637596111db">OutputList::startContents</a>, <a href="/web-doxygen/docs/api/files/src/index-cpp/#a8183f7413c2945be8d3a2ca7ee4f237f">startFile</a>, <a href="/web-doxygen/docs/api/files/src/language-cpp/#a07b18e39f7c5156cd370829e7e6f8534">theTranslator</a>, <a href="/web-doxygen/docs/api/files/src/dirdef-cpp/#a50a5ca2a633e8e9e98f1fdb284b96186">writePartialFilePath</a> and <a href="/web-doxygen/docs/api/classes/outputlist/#a07cac8a8981da35314f77d8f3edb7f76">OutputList::writeString</a>.
</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### m&#95;dst {#a3e4e275033d30b182a7b88338f11fb77}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">UsedDir* DirRelation::m_dst</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dirdef-h/#l00167">167</a> of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a3e4e275033d30b182a7b88338f11fb77">167</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/useddir">UsedDir</a> *<a href="#a3e4e275033d30b182a7b88338f11fb77">m_dst</a>;</span></span></div>

</div>


Referenced by <a href="#a2fc1b42862174170fcb18d6b997b7fcf">destination</a>, <a href="#af7ea0932aa290846b11b631dbdde6f65">DirRelation</a> and <a href="#a5fa861050993dafb351589f2f1c05326">writeDocumentation</a>.
</div>
</div>

### m&#95;name {#a470369422b9a291d75c8ea3cdf48fc5f}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString DirRelation::m_name</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dirdef-h/#l00165">165</a> of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a470369422b9a291d75c8ea3cdf48fc5f">165</a></span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#a470369422b9a291d75c8ea3cdf48fc5f">m_name</a>;</span></span></div>

</div>


Referenced by <a href="#af7ea0932aa290846b11b631dbdde6f65">DirRelation</a> and <a href="#a73890fdede27fd42215794b10b76b05a">getOutputFileBase</a>.
</div>
</div>

### m&#95;src {#a0f8d40ddf8119bf256e3c12b33685093}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">const DirDef* DirRelation::m_src</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">


<p>Definition at line <a href="/web-doxygen/docs/api/files/src/dirdef-h/#l00166">166</a> of file <a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a>.</p>

<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a0f8d40ddf8119bf256e3c12b33685093">166</a></span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/dirdef">DirDef</a>  *<a href="#a0f8d40ddf8119bf256e3c12b33685093">m_src</a>;</span></span></div>

</div>


Referenced by <a href="#af7ea0932aa290846b11b631dbdde6f65">DirRelation</a>, <a href="#aab57e18f87ae233fae48a141b9d9fcba">source</a> and <a href="#a5fa861050993dafb351589f2f1c05326">writeDocumentation</a>.
</div>
</div>

</div>

<hr/>

<p>The documentation for this class was generated from the following files:</p>

<ul>
<li><a href="/web-doxygen/docs/api/files/src/dirdef-cpp">dirdef.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/dirdef-h">dirdef.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
