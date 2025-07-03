---

# DO NOT EDIT!
# Automatically generated via docusaurus-plugin-doxygen by Doxygen.

slug: /api/classes/markdown
custom_edit_url: null
keywords:
  - doxygen
  - reference
  - class
toc_max_heading_level: 4

---

<div class="doxyPage">

# The `Markdown` Class Reference

<p>Helper class to process markdown formatted text. <a href="#details">More...</a></p>

## Declaration

<div class="doxyDeclaration">
class Markdown { ... }
</div>

## Included Headers

<div class="doxyIncludesList">#include &lt;<a href="/web-doxygen/docs/api/files/src/markdown-h">src/markdown.h</a>&gt;
</div>

## Public Constructors Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#acb219dbca88da9e2c914070e1adc443d">Markdown</a> (const QCString &amp;fileName, int lineNr, int indentLevel=0)</td>
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

## Public Destructor Index

<table class="doxyMembersIndex">

<tr class="doxyMemberIndexItem">
<td class="doxyMemberIndexItemType" align="left" valign="top"></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a582aef5e582b2751e8e76732a551a361">~Markdown</a> ()</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a></td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ad40652cc4db61282f2b0ef5202927d10">process</a> (const QCString &amp;input, int &amp;startNewlines, bool fromParseInput=false)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ac2acb2b59eeab5ffb2405f30b3c56476">extractPageTitle</a> (QCString &amp;docs, QCString &amp;id, int &amp;prepend, bool &amp;isIdGenerated)</td>
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
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#ab176950dfe9ce90a45af5db61b5acf88">setIndentLevel</a> (int level)</td>
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
<td class="doxyMemberIndexItemType" align="left" valign="top">std::unique_ptr&lt; <a href="/web-doxygen/docs/api/structs/markdown/private">Private</a> &gt;</td>
<td class="doxyMemberIndexItemName" align="left" valign="top"><a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a></td>
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

<p>Helper class to process markdown formatted text.</p>

<p>Definition at line 31 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>.</p>


<div class="doxySectionDef">

## Public Constructors

### Markdown() {#acb219dbca88da9e2c914070e1adc443d}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Markdown::Markdown (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; fileName, int lineNr, int indentLevel=0)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 34 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>, definition at line 182 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#acb219dbca88da9e2c914070e1adc443d">182</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="#acb219dbca88da9e2c914070e1adc443d">Markdown::Markdown</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;fileName,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> lineNr,</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> indentLevel)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">183</span><span class="doxyLineContent"><span class="doxyHighlight">  : <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>(std::make_unique&lt;<a href="/web-doxygen/docs/api/structs/markdown/private">Private</a>&gt;(fileName,lineNr,indentLevel))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">184</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">185</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">using namespace </span><span class="doxyHighlight">std::placeholders;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">186</span><span class="doxyLineContent"><span class="doxyHighlight">  (void)lineNr; </span><span class="doxyHighlightComment">// not used yet</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">187</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>Reference <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>.</p>


<p>Referenced by <a href="#a582aef5e582b2751e8e76732a551a361">~Markdown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Destructor

### \~Markdown() {#a582aef5e582b2751e8e76732a551a361}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">Markdown::~Markdown ()</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 35 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>.</p>


<p>Reference <a href="#acb219dbca88da9e2c914070e1adc443d">Markdown</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Public Member Functions

### extractPageTitle() {#ac2acb2b59eeab5ffb2405f30b3c56476}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString Markdown::extractPageTitle (<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; docs, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; id, int &amp; prepend, bool &amp; isIdGenerated)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 38 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>, definition at line 3496 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ac2acb2b59eeab5ffb2405f30b3c56476">3496</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ac2acb2b59eeab5ffb2405f30b3c56476">Markdown::extractPageTitle</a>(<a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;docs, <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;prepend, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> &amp;isIdGenerated)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3497</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3498</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>(</span><span class="doxyHighlightStringLiteral">"docs={} prepend={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(docs),</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,prepend);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3499</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// first first non-empty line</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3500</span><span class="doxyLineContent"><span class="doxyHighlight">  prepend = 0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3501</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3502</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> i=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3503</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> docs_org(docs);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3504</span><span class="doxyLineContent"><span class="doxyHighlight">  std::string_view data(docs_org.<a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">str</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3505</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> size = data.size();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3506</span><span class="doxyLineContent"><span class="doxyHighlight">  docs.<a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">clear</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3507</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (i&lt;size &amp;&amp; (data[i]==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight"> || data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3508</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3509</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (data[i]==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) prepend++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3510</span><span class="doxyLineContent"><span class="doxyHighlight">    i++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3511</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3512</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&gt;=size) { </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a>(); }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3513</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> end1=i+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3514</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (end1&lt;size &amp;&amp; data[end1-1]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) end1++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3515</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("i=%d end1=%d size=%d line='%s'\n",i,end1,size,docs.mid(i,end1-i).data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3516</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// first line from i..end1</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3517</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (end1&lt;size)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3518</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3519</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// second line form end1..end2</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3520</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> end2=end1+1;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3521</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (end2&lt;size &amp;&amp; data[end2-1]!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) end2++;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3522</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;isHeaderline(data.substr(end1),<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>))</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3523</span><span class="doxyLineContent"><span class="doxyHighlight">    {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3524</span><span class="doxyLineContent"><span class="doxyHighlight">      title = data.substr(i,end1-i-1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3525</span><span class="doxyLineContent"><span class="doxyHighlight">      docs+=</span><span class="doxyHighlightStringLiteral">"\n\n"</span><span class="doxyHighlight">+docs_org.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(end2);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3526</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;extractTitleId(title, 0, &amp;isIdGenerated);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3527</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightComment">//printf("extractPageTitle(title='%s' docs='%s' id='%s')\n",title.data(),docs.data(),id.data());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3528</span><span class="doxyLineContent"><span class="doxyHighlight">      <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={} id={} isIdGenerated={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(title),</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,isIdGenerated);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3529</span><span class="doxyLineContent"><span class="doxyHighlight">      </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3530</span><span class="doxyLineContent"><span class="doxyHighlight">    }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3531</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3532</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (i&lt;end1 &amp;&amp; prv-&gt;isAtxHeader(data.substr(i,end1-i),title,</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>,&amp;isIdGenerated)&gt;0)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3533</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3534</span><span class="doxyLineContent"><span class="doxyHighlight">    docs+=</span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3535</span><span class="doxyLineContent"><span class="doxyHighlight">    docs+=docs_org.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(end1);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3536</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3537</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3538</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3539</span><span class="doxyLineContent"><span class="doxyHighlight">    docs=docs_org;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3540</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight"> = <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;extractTitleId(title, 0, &amp;isIdGenerated);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3541</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3542</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>(</span><span class="doxyHighlightStringLiteral">"result={} id={} isIdGenerated={}"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>(title),</span><span class="doxyHighlightKeywordType">id</span><span class="doxyHighlight">,isIdGenerated);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3543</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> title;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3544</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a210042a14f3a393be09c743c219126ae">AUTO_TRACE</a>, <a href="/web-doxygen/docs/api/files/src/docnode-cpp/#a81912d2a3d12aab7a9e546e5299e2e09">AUTO_TRACE_EXIT</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#af4848e7058516bdbbcff3b43779aea30">QCString::clear</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#aa93f0eb578d23995850d61f7d61c55c1">FALSE</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a875e9ad762554ef12f3ed69b015bb245">QCString::str</a> and <a href="/web-doxygen/docs/api/namespaces/trace/#a1859b0ba7161e012fecbd71dd4ec64d6">Trace::trunc</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>.</p>

</div>
</div>

### process() {#ad40652cc4db61282f2b0ef5202927d10}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">QCString Markdown::process (const <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp; input, int &amp; startNewlines, bool fromParseInput=false)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 37 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>, definition at line 3549 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ad40652cc4db61282f2b0ef5202927d10">3549</a></span><span class="doxyLineContent"><span class="doxyHighlight"><a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> <a href="#ad40652cc4db61282f2b0ef5202927d10">Markdown::process</a>(</span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> &amp;input, </span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> &amp;startNewlines, </span><span class="doxyHighlightKeywordType">bool</span><span class="doxyHighlight"> fromParseInput)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3550</span><span class="doxyLineContent"><span class="doxyHighlight">{</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3551</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (input.<a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">isEmpty</a>()) </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> input;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3552</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordType">size_t</span><span class="doxyHighlight"> refIndent=0;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3553</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3554</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// for replace tabs by spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3555</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> s = input;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3556</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (s.<a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">at</a>(s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>()-1)!=</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) s += </span><span class="doxyHighlightStringLiteral">"\n"</span><span class="doxyHighlight">; </span><span class="doxyHighlightComment">// see PR #6766</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3557</span><span class="doxyLineContent"><span class="doxyHighlight">  s = <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9884211727d9091a08b34aa1fb14c9b1">detab</a>(s,refIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3558</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("======== DeTab =========\n---- output -----\n%s\n---------\n",qPrint(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3559</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3560</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// then process quotation blocks (as these may contain other blocks)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3561</span><span class="doxyLineContent"><span class="doxyHighlight">  s = <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;processQuotations(s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">view</a>(),refIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3562</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("======== Quotations =========\n---- output -----\n%s\n---------\n",qPrint(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3563</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3564</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// then process block items (headers, rules, and code blocks, references)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3565</span><span class="doxyLineContent"><span class="doxyHighlight">  s = <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;processBlocks(s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">view</a>(),refIndent);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3566</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">//printf("======== Blocks =========\n---- output -----\n%s\n---------\n",qPrint(s));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3567</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3568</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// finally process the inline markup (links, emphasis and code spans)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3569</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;out.clear();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3570</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;out.reserve(s.<a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">length</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3571</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;processInline(s.<a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">view</a>());</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3572</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (fromParseInput)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3573</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3574</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4e7a964cec1d0423c74ab7045c1f6f6d">Debug::Markdown</a>,0,</span><span class="doxyHighlightStringLiteral">"---- output -----\n{}\n=========\n"</span><span class="doxyHighlight">,<a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>(<a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;out));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3575</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3576</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">else</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3577</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3578</span><span class="doxyLineContent"><span class="doxyHighlight">    <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>(<a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4e7a964cec1d0423c74ab7045c1f6f6d">Debug::Markdown</a>,0,</span><span class="doxyHighlightStringLiteral">"======== Markdown =========\n---- input ------- \n{}\n---- output -----\n{}\n=========\n"</span><span class="doxyHighlight">,input,<a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;out);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3579</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3580</span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3581</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightComment">// post processing</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3582</span><span class="doxyLineContent"><span class="doxyHighlight">  <a href="/web-doxygen/docs/api/classes/qcstring">QCString</a> result = <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a>(<a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;out,<a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a5411339961a1e433bf9b59570c97fa6a">g_doxy_nbsp</a>,</span><span class="doxyHighlightStringLiteral">"&amp;nbsp;"</span><span class="doxyHighlight">);</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3583</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeyword">const</span><span class="doxyHighlight"> </span><span class="doxyHighlightKeywordType">char</span><span class="doxyHighlight"> *p = result.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>();</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3584</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p)</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3585</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3586</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">' '</span><span class="doxyHighlight">)  p++; </span><span class="doxyHighlightComment">// skip over spaces</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3587</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">while</span><span class="doxyHighlight"> (*p==</span><span class="doxyHighlightCharLiteral">'\n'</span><span class="doxyHighlight">) {startNewlines++;p++;}; </span><span class="doxyHighlightComment">// skip over newlines</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3588</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (<a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>(p,</span><span class="doxyHighlightStringLiteral">"&lt;br&gt;"</span><span class="doxyHighlight">)) p+=4; </span><span class="doxyHighlightComment">// skip over &lt;br&gt;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3589</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3590</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">if</span><span class="doxyHighlight"> (p&gt;result.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>())</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3591</span><span class="doxyLineContent"><span class="doxyHighlight">  {</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3592</span><span class="doxyLineContent"><span class="doxyHighlight">    </span><span class="doxyHighlightComment">// strip part of the input</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3593</span><span class="doxyLineContent"><span class="doxyHighlight">    result = result.<a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">mid</a>(</span><span class="doxyHighlightKeyword">static_cast&lt;</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlightKeyword">&gt;</span><span class="doxyHighlight">(p-result.<a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">data</a>()));</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3594</span><span class="doxyLineContent"><span class="doxyHighlight">  }</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3595</span><span class="doxyLineContent"><span class="doxyHighlight">  </span><span class="doxyHighlightKeywordFlow">return</span><span class="doxyHighlight"> result;</span></span></div>
<div class="doxyCodeLine"><span class="doxyLineNumber">3596</span><span class="doxyLineContent"><span class="doxyHighlight">}</span></span></div>

</div>


<p>References <a href="/web-doxygen/docs/api/classes/qcstring/#a4c8be5d062cc14919b53ff0a3c8f9a4f">QCString::at</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#ac3aa3ac1a1c36d3305eba22a2eb0d098">QCString::data</a>, <a href="/web-doxygen/docs/api/files/src/util-cpp/#a9884211727d9091a08b34aa1fb14c9b1">detab</a>, <a href="/web-doxygen/docs/api/files/src/markdown-cpp/#a5411339961a1e433bf9b59570c97fa6a">g_doxy_nbsp</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a621c4090d69ad7d05ef8e5234376c3d8">QCString::isEmpty</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a16362990092a086b505e08f102df4dff">QCString::length</a>, <a href="/web-doxygen/docs/api/files/src/stringutil-h/#a8e85550bd817a742a59bf46dce8f3b21">literal_at</a>, <a href="/web-doxygen/docs/api/classes/debug/#a1c3f4696cf44a23f41e034323c426f7da4e7a964cec1d0423c74ab7045c1f6f6d">Debug::Markdown</a>, <a href="/web-doxygen/docs/api/classes/qcstring/#a27136caf9c0bc4daca574cda6f113551">QCString::mid</a>, <a href="/web-doxygen/docs/api/classes/debug/#a970761e07475cafdd9fd5395a0c83544">Debug::print</a>, <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-h/#a9851ebb5ae2f65b4d2b1d08421edbfd2">qPrint</a>, <a href="/web-doxygen/docs/api/files/src/qcstring-cpp/#a99187f0723aa35b7f06be3a5506b1285">substitute</a> and <a href="/web-doxygen/docs/api/classes/qcstring/#ac853c00269498870dfefa8185f2ee79a">QCString::view</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/files/src/singlecomment-cpp/#a248b40256877fc3c467046ebf1835a8f">generateHtmlForComment</a>, <a href="/web-doxygen/docs/api/files/src/fortranscanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/pyscanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aa6551ba715391111267db3d5e8a3ead4">handleCommentBlock</a>, <a href="/web-doxygen/docs/api/classes/vhdloutlineparser/#a3df5816f7dcd092e39a99ebaf9b983cf">VHDLOutlineParser::handleCommentBlock</a>, <a href="/web-doxygen/docs/api/files/src/scanner-l/#aae0b93eceac30fcc7b8bbb6795b588a2">handleParametersCommentBlocks</a> and <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>.</p>

</div>
</div>

### setIndentLevel() {#ab176950dfe9ce90a45af5db61b5acf88}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">void Markdown::setIndentLevel (int level)</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Declaration at line 39 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>, definition at line 191 of file <a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#ab176950dfe9ce90a45af5db61b5acf88">191</a></span><span class="doxyLineContent"><span class="doxyHighlightKeywordType">void</span><span class="doxyHighlight"> <a href="#ab176950dfe9ce90a45af5db61b5acf88">Markdown::setIndentLevel</a>(</span><span class="doxyHighlightKeywordType">int</span><span class="doxyHighlight"> level) { <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>-&gt;indentLevel = level; }</span></span></div>

</div>


<p>Reference <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>.</p>


<p>Referenced by <a href="/web-doxygen/docs/api/classes/markdownoutlineparser/#a0cb95204f0f91c085e6a9808efb2ebdc">MarkdownOutlineParser::parseInput</a>.</p>

</div>
</div>

</div>

<div class="doxySectionDef">

## Private Member Attributes

### prv {#a8e6c750a54518a9aca8d9d58364f9139}

<div class="doxyMemberItem">
<div class="doxyMemberProto">
<table class="doxyMemberLabels">
<tr class="doxyMemberLabels">
<td class="doxyMemberLabelsLeft">
<table class="doxyMemberName">
<tr>
<td class="doxyMemberName">std::unique_ptr&lt;Private&gt; Markdown::prv</td>
</tr>
</table>
</td>
</tr>
</table>
</div>
<div class="doxyMemberDoc">



<p>Definition at line 43 of file <a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a>.</p>


<div class="doxyProgramListing">

<div class="doxyCodeLine"><span class="doxyLineNumber"><a href="#a8e6c750a54518a9aca8d9d58364f9139">43</a></span><span class="doxyLineContent"><span class="doxyHighlight">    std::unique_ptr&lt;Private&gt; <a href="#a8e6c750a54518a9aca8d9d58364f9139">prv</a>;</span></span></div>

</div>


<p>Referenced by <a href="#ac2acb2b59eeab5ffb2405f30b3c56476">extractPageTitle</a>, <a href="#acb219dbca88da9e2c914070e1adc443d">Markdown</a>, <a href="#ad40652cc4db61282f2b0ef5202927d10">process</a> and <a href="#ab176950dfe9ce90a45af5db61b5acf88">setIndentLevel</a>.</p>

</div>
</div>

</div>

<hr/>

The documentation for this class was generated from the following files:

<ul>
<li><a href="/web-doxygen/docs/api/files/src/markdown-cpp">markdown.cpp</a></li>
<li><a href="/web-doxygen/docs/api/files/src/markdown-h">markdown.h</a></li>
</ul>

<hr/>

<p class="doxyGeneratedBy">Generated via <a href="https://github.com/xpack/docusaurus-plugin-doxygen">docusaurus-plugin-doxygen</a> by <a href="https://www.doxygen.nl">Doxygen</a> 1.14.0.</p>

</div>
